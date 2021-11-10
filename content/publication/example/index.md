---
abstract: >
  Single-cell atlases often include samples that span locations, labs, and
  conditions, leading to complex, nested batch effects in data. Thus, joint
  analysis of atlas datasets requires reliable data integration.

  To guide integration method choice we benchmarked 68 method and preprocessing combinations on 85 batches of gene expression, chromatin accessibility, and simulation data from 23 publications, altogether representing >1.2 million cells distributed in 13 atlas-level integration tasks. We evaluated methods according to scalability, usability, and their ability to remove batch effects while retaining biological variation using 14 evaluation metrics.

  We show that highly variable gene selection improves the performance of data integration methods, whereas scaling pushes methods to prioritize batch removal over conservation of biological variation. Overall, scANVI, Scanorama, scVI and scGen perform well, particularly on complex integration tasks, while scATAC-seq integration performance is strongly affected by choice of feature space. Our freely available Python module and benchmarking pipeline can identify optimal data integration methods for new data, benchmark new methods, and improve method development. 
slides: ""
url_pdf: ""
publication_types:
  - "2"
authors:
  - MD Luecken
  - M Büttner
  - K Chaichoompu
  - A Danese
  - M Interlandi
  - MF Müller
  - DC Strobl
  - L Zappia
  - M Dugas
  - M Colomé-Tatché
  - FJ Theis
summary: A benchmark of 16 data integration methods evaluated on 13 scRNA-seq
  and scATAC-seq integration tasks. Methods were evaluated on the basis of their
  usability, their scalability, and their performance using 14 metrics that
  measure different aspects of batch removal and biological variance
  conservation.
url_dataset: ""
url_project: ""
author_notes:
  - Equal contribution
  - Equal contribution
publication_short: Nat Meth
url_source: ""
url_video: ""
publication: Nature Methods (in press)
featured: true
date: 2021-11-10T19:18:40.764Z
url_slides: ""
title: Benchmarking atlas-level data integration in single-cell genomics
tags: []
categories:
  - Data-integration;Single-cell;Benchmarking
projects: []
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: CENTER
  preview_only: false
  filename: 20210929_120612_bestmethods_summary.png
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
doi: 10.1101/2020.05.22.111161
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

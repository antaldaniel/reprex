---
title: "Create Datasets that are Easy to Combine and Reuse"
subtitle: Our new R software package, dataset is released on CRAN

# Summary for listings and search engines
summary: "The latest Reprex R package, dataset was released today on the Comprehensive R Archive Network. It is a very early, conceptual package that will help make scientific achievements more open, governmental data easier to find, and store information that can be better combined."

authors: ["daniel_antal", "admin"]
 
# Link this post with a project
projects: ''

# Date published
date: "2022-11-22T09:09:00+01:00"
lastmod: "2022-11-22T09:09:00+01:00"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

doi: 10.5281/zenodo.7391890

links:
- icon: code
  icon_pack: fas
  name: Code & Tutorials
  url: https://iotables.dataobservatory.eu/
- icon: linkedin
  icon_pack: fab
  name: Reprex
  url: https://www.linkedin.com/company/68855596/
- icon: github
  icon_pack: fab
  name: Code
  url: https://https://github.com/dataobservatory-eu/dataset/

# Featured image
image:
  caption: ''
  focal_point: "bottom"
  placement: 2
  preview_only: true
  
categories: 
  - R_bloggers

tags:
  - Open science
  - Open data
  - RDF
  - Semantic web
  - R
---

**The latest Reprex R package, dataset was released today on the Comprehensive R Archive Network. It is a very early, conceptual package that will help make scientific achievements more open, governmental data easier to find, and store information that can be better combined.**

Data interoperability is almost a buzzword, yet we see very few comprehensive, good solutions to apply it.  Try to find information on open government portals or on big open science repositories—apart from a few good examples, most datasets are as disorganized as any PC’s hard disk that is collecting dust in a shed. 

The `dataset` package aims to bring together the best practices of data semantics, data organization, and the use of standard metadata to make sure that whatever you store in a data table, it will be immediately available for data analysis, activation, or combination in any new database.

Ambitious? It is, and `dataset 0.1.9` is a very experimental product. While our other packages are aimed at intermediate users with a clear use case in mind, dataset at this point is aimed at package developers. Casual or even heavy R users are unlikely to download it as a standalone product. Instead, `dataset` aims to be a stable developer basis for our existing products, rOpenGov packages, and many new uses.

<td style="text-align: center;">{{< figure src="img/screenshots/dataset_0_1_9.png" caption="Download [dataset](https://dataset.dataobservatory.eu/)" numbered="false" >}}</td>

The metadata aim of `dataset` it to add standardized metadata to r data.frames, tibbles, data.tables and other similar structured, tabular objects.  The organization and semantic objectives are to bring the tidy data concept closer to the datacube model, which is the basis of all statistical data exchanges, and W3C standards, which foster machine-to-machine data communications on the traditional web APIs and the semantic web.

1. Makes data importing easier and less error-prone; 
2. Leaves plenty of room for documentation automation, resulting in far better reusability and reproducibility; 
3. The publication of results from R following the [FAIR](https://www.go-fair.org/fair-principles/) principles is far easier, making the work of the R user more findable, more accessible, more interoperable and more reusable by other users;
4. Makes the placement into relational databases, semantic web applications, archives, repositories possible without time-consuming and costly data wrangling (See [From dataset To RDF](https://dataset.dataobservatory.eu/articles/RDF.html)).


The first official release offers little immediate benefits. However, if you are an R package developer, we can bring you a few steps nearer to releasing your data products in a way that conforms the [FAIR metadata](https://www.go-fair.org/fair-principles/) principles.  We can make a few steps to streamline your data wrangling.  Make integration with relational databases easier. To make a step towards the semantic web.

---
title: Data Processing
summary: We create high value key business and policy evaluation indicators. Scientific proofs require the combination of correctly matching, formatting, and verifying controlled pieces of data. Our data comes from verified and legal sources, with information about use rights and a complete history. You can always take a look at the processing code, too. We do not deal in blood diamonds.
tags:
- data-processing
date: "2021-01-21T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "The Open Pit of the Udachnaya Diamond Mine, ©[Stapanov Alexander](https://commons.wikimedia.org/w/index.php?curid=350061)"
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/EconDataObs
- icon: linkedin
  icon_pack: fab
  name: Connect
  url: https://www.linkedin.com/company/78562153/
- icon: fa-lightbulb
  icon_pack: fas
  name: Get Inspired
  url: https://contributors.dataobservatory.eu/data-curators.html#get-inspired
- icon: book-open
  icon_pack: fas
  name: Documentation
  url: https://contributors.dataobservatory.eu/
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides: ""`.
slides: data-curation
---

*Data analysts spend 80% of their time on data processing, even though computers can perform these task much faster, with far less errors, and they can document the process automatically. Data processing can be shared: an analyst in a company and an analyst in an      NGO does not have to reprocess the very same data twice**

See our blogpost [How We Add Value to Public Data With Imputation and Forecasting?](/post/2021-11-06-indicator_value_added/).

Public data sources are often plagued by missng values. Naively you may think that you can ignore them, but think twice: in most cases, missing data in a table is not missing information, but rather malformatted information. This approach of ignoring or dropping missing values will not be feasible or robust when you want to make a beautiful visualization, or use data in a business forecasting model, a machine learning (AI) applicaton, or a more complex scientific model. All of the above require complete datasets, and naively discarding missing data points amounts to an excessive waste of information. In this example we are continuing the example a not-so-easy to find public dataset.

Completing missing datapoints requires statistical production information (why might the data be missing?) and data science knowhow (how to impute the missing value.) If you do not have a good statistician or data scientist in your team, you will need high-quality, complete datasets. This is what our automated data observatories provide.

<td style="text-align: center;">{{< figure src="/img/blogposts_2021/Sisyphus_Bodleian_Library.png" caption="See our blogpost about [the Data Sisyphus](https://reprex.nl/post/2021-07-08-data-sisyphus/) blogpost." numbered="false" >}}</td>

We have a better solution. You can always rely on our API to import directly the latest, best data, but if you want to be sure, you can use our [regular backups](https://zenodo.org/record/5652118#.YYhGOGDMLIU) on Zenodo. Zenodo is an open science repository managed by CERN and supported by the European Union. On Zenodo, you can find an authoritative copy of our indicator (and its previous versions) with a digital object identifier, for example, [10.5281/zenodo.5652118](https://doi.org/10.5281/zenodo.5652118). These datasets will be preserved for decades, and nobody can manipulate them. You cannot accidentally overwrite them, and we have no backdoor access to modify them.

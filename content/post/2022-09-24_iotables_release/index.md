---
title:  "iotables: Integrate Data from Reliable Statistical Sources for Economic and Environmental Impact Analysis"
subtitle:  "The 0.9.1 version of iotables is available on CRAN and Zenodo"
date:  2022-09-24T08:13:55+02:00
lastmod:  2022-09-24T08:13:55+02:00

# authors:  ["daniel_antal"]

tags:  ["iotables", "Eviota", "Environmental Impact Analysis", "Economic Impact Analysis"]
categories: Rbloggers

summary:  "The iotables R package collects and integrates data from reliable statistical sources and performs economic and environmental impact analysis. It can be your starting point to calculate employment, tax, or greenhouse gas multipliers for various policy actions in your country for free, and it is the backbone of our connected financial-sustainability ESG reporting tool, Eviota, because it can analyze the value chains of 64 industries in every European country."

abstract:  "The iotables R package collects and integrates data from reliable statistical sources and perform economic and environmental impact analysis. It can be your starting point to calculate employment, tax, or greenhouse gas multipliers for various policy actions in your country for free, and it is the backbone of our connected financial-sustainability ESG reporting tool, Eviota, because it can analyze the value chains of 64 industries in every European country."

# Featured image
image:
  caption:  ""
  focal_point:  "TopRight"
  preview_only:  true
  
---
<td style="text-align: center;">{{< figure src="/img/screenshots/iotables_16x9_20220924.png" caption="Download [iotables](https://iotables.dataobservatory.eu/)" numbered="false" >}}</td>

The iotables R package is an open-source, scientifically validated package that collects and integrates data from reliable statistical sources and performs economic and environmental impact analysis. It is the backbone of our connected financial-sustainability reporting tool, Eviota, because it can analyze the value chains of 64 industries in every European country for free. It is your starting point to calculate employment, tax, or greenhouse gas multipliers for various policy actions in your country.

{{% callout note %}}
The 0.9.1 version of iotables was released today on CRAN. This new minor release contains a bug fix reported by a user and some documentation improvements. Check out our [product page](https://iotables.dataobservatory.eu/) and our [examples](https://iotables.dataobservatory.eu/articles/index.html).
{{% /callout %}}

* The iotables package works with the open-source R statistical environment. We programmed every example of the [Eurostat Manual of Supply, Use and Input-Output Tables](https://ec.europa.eu/eurostat/documents/3859598/5902113/KS-RA-07-013-EN.PDF/b0b3d71e-3930-4442-94be-70b36cea9b39?version=1.0), which can be used both as a control tool for our package and as a comprehensive, extended handbook on use. 
* We have also started to meet the demands of a more global audience by adding more and more examples from the  [Handbook on Supply and Use Tables and Input-Output Tables with Extensions and Applications](https://unstats.un.org/unsd/nationalaccount/docs/SUT_IOT_HB_Final_Cover.pdf) published by the United Nations. Our goal is to make both our iotables a free analytic and data processing tool and our premium Eviota ESG reporting premium solution applicable anywhere in the world.


``` r
# From CRAN:
install.packages("iotables")

# From Github (development version)
devtools::install_github("rOpenGov/iotables")

# with vignettes:
devtools::install_github("rOpenGov/iotables", build_vignettes = TRUE)
```

The iotables tool has hundreds of technical and professional users in the world. We know that it is not for the faint heart. In 2022 we started the development of a tool that will create impact assessments for small companies or civil society organizations without the need to learn and use R.

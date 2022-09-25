+++
title = "Reproducible Economic Impact Assessment"
subtitle = "New iotables release and a tidy version of the EU Taxonomy on sustainable economic activities"
date = 2021-12-19T13:00:00+01:00
lastmod = 2021-12-19T13:00:00+01:00
draft = false

authors = ["daniel_antal"]

tags = ["iotables", "Green Deal Data Observatory", "Sustainability", "EU Taxonomy"]

summary = "We made an important, peer-reviewed release of iotables in the last week as a preparation to increase the functionality of our open-source software. This release of the iotables R package currently works with economic impact assessments, and can evaluate the likely employment, tax, wage, or gross value added direct, indirect and multiplied impacts of various policy changes in about 30 countries. The new, development version (which did not go through peer-review yet) is adding new functionality for environmental impact analysis with the following pollutants and will be connected to the EU Taxonomy on sustainable economic activities."

# Featured image
[image]
  # Caption (optional)
  caption = "iotables.dataobservatory.eu"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"

  # Show image only in page previews?
  preview_only = true

+++

<td style="text-align: center;">{{< figure src="/media/img/blogposts_2021/iotables_0_4_7.png" caption="Get started with  [iotables](https://iotables.dataobservatory.eu/index.html)." numbered="false" >}}</td>

We made an important, peer-reviewed release of iotables in the last week as a preparation to increase the functionality of our open-source software. The official release of the iotables R package currently works with economic impact assessments, and can evaluate the likely employment, tax, wage, or gross value added direct, indirect and multiplied impacts of various policy changes in about 30 countries.

Originally the package was developed to calculate the economic impact of the Hungarian film tax shelter and the impact of the music sector on the Slovak economy. (See [Slovak Music Industry Report](https://music.dataobservatory.eu/publication/slovak_music_industry_2019/)).

The new CRAN release improved the documentation of the function and removed most outdated dependencies.  The new, development version (which did not go through peer-review yet) is adding new functionality for environmental impact analysis with the following pollutants:  Carbon dioxide without emissions from biomass (`CO2`), Carbon dioxide from biomass (`Biomass CO2`), Nitroux oxide (`N2O`), Methane (`CH4`), Perfluorocarbons (`PFCs`), Hydrofluorocarbons (`HFCs`), Sulphur hexafluoride (SF6) including nitrogen trifluoride (`NF3`), Nitrogen oxides (`NOx`), Non-methane volatile organic compounds, (NMVOC), Carbon monoxide (`CO`), Particulate matter < 10μm (`PM10`), Particulate matter < 2,5μm (`PM2,5`), Sulphur dioxide (`SO2`), Ammonia (`NH3`) and their combinations (see [Reference Metadata in Euro SDMX Metadata Structure (ESMS)](https://ec.europa.eu/eurostat/cache/metadata/en/env_ac_ainah_r2_esms.htm)).

Our aim is to develop new sustainable finance applications, and understand the sustainability impacts of bank’s lending activities and insurer’s underwriting activities on climate change mitigation and adoption, biodiversity, preservation of water reservers, preventing pollution, and promoting the circular economy. 

## EU Taxonomy on Sustainable Activities 

The European Commission created an created an [EU Taxonomy Compass](https://ec.europa.eu/sustainable-finance-taxonomy/tool/index_en.htm), which provides a visual representation of the contents of the EU Taxonomy, starting with the Delegated Act on the climate objectives, as adopted on 4 June 2021. Whilst you can download the EU Taxonomy in `xlsx` or `json` format, they are not tidy datasets, and they are not particularly well-suited for calculations, filtering, or inclusion in applications.

[Reprex](https://reprex.nl/) created a tidy version of the EU Taxonomy for developing better sustainability indicators into the [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/).

## Open Data

<td style="text-align: center;">{{< figure src="/img/blogposts_2021/tidy_eu_taxonomy_on_zenodo.png" caption="EU Taxonomy on Sustainable Activities (Tidy) [download](https://zenodo.org/record/5791921#.Yb9UN2jMLIU)." numbered="false" >}}</td>

Using our `iotables` is not for the faint heart.  It is a scientific software, and it requires a good command of national accounts, input-output economics and sustainability to work with.  Our Green Deal Data Observaotry is designed to be an API of scientific software, and produce clean, ready to use data for researchers, policy-makers and business planners who do not have the skills to work with scientific software. We are planning to release well-designed datasets that go through dozens of checks to make sure they have the best data quality. 

{{% callout note %}}Do you want to develop input-output models for any European country to measure the direct and indirect green house gas impacts of policy actions?  Do you need well-formatted data on interindustry linkages or other relevant topics for sustainable economy or susitainable finance research?  Get in touch with us – we are happy to help and test our new software tool with data you need, and create high-quality, open datasets that are ready to use.{{% /callout %}}



---
title: "iotables R package for working with symmetric input-output tables"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Antal

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-06-03"
lastmod: 2021-06-03T12:00:00
doi: "10.5281/zenodo.4897472"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-03T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: The Comprehensive R Archive Network
publication_short: In *CRAN*

abstract: The goal of iotables is to make allow a programmatic acces to the symmetric input-output tables of Eurostat. It creates multipliers, calculates direct, indirect and induced effects from European SIOT tables.

# Summary. An optional shortened abstract.
summary: The goal of iotables is to make allow a programmatic acces to the symmetric input-output tables of Eurostat. It creates multipliers, calculates direct, indirect and induced effects from European SIOT tables.

tags: ["Open Data"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://iotables.dataobservatory.eu/'
url_slides: ''
url_source: 'http://rOpenGov/iotables/'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

[iotables](https://iotables.dataobservatory.eu/) processes all the symmetric input-output tables of the EU member states, and calculates direct, indirect and induced effects, multipliers for GVA, employment, taxation. These are important inputs into policy evaluation, business forecasting, or granting/development indicator design. iotables is used by about 800 experts around the world. 

The symmetric input-output tables (SIOTs) are complex statistical
products that present inter-related statistics in a predefined
structure. They are often found in spreadsheets that follow this
structure, or in the case Eurostat in a data repository. In both cases
they in reproducible research must be downloaded and restructured to
programmatically accessible form. Often these highly structured
statistics need to be analyzed together with other data, for example,
when employment effects and multipliers are calculated. In this case
processing the employment data to SIOT conforming format is a
significant preprocessing challenge.

The iotables are exactly designed for these tasks. Currently the package
downloads and processes standardized European SIOTs conforming to the
latest statistical regulations, i.e., SIOTs starting from the year 2010.

The aim of this introduction is not to introduce input-output economics,
or SIOTs in detail. The [Eurostat Manual of Supply, Use and Input-Output Tables](https://ec.europa.eu/eurostat/en/web/products-manuals-and-guidelines/-/KS-RA-07-013)
and the [Eurostat thematic
page](https://ec.europa.eu/eurostat/web/esa-supply-use-input-tables/overview)
(for further reference: `Eurostat Manual`) in the documentation should
be consulted for further information about the data and the metadata.

In order to test the analytical functions of the package and to have a
manageable sized example data set, we use the real-life data from the
Eurostat manual. The `germany_1990` dataset is a simplified 6x6 sized
SIOT taken from the `Eurostat Manual` (`p481`). The package function
examples can be checked against [published results from Jörg Beutel](https://ec.europa.eu/eurostat/documents/3859598/5902113/KS-RA-07-013-EN.PDF/b0b3d71e-3930-4442-94be-70b36cea9b39?version=1.0).
These calculations can be followed in the [Germany 1990
vignette](https://iotables.dataobservatory.eu/articles/germany_1990.html).

The calculation of induced effects (Type-II multipliers) are following
the [Input-Output Multipliers Specification Sheet and Supporting
Material, Spicosa Project
Report](http://www.coastal-saf.eu/output-step/pdf/Specification%20sheet%20I_O_final.pdf).
The analytical functions are tested against this example, too.

## Installation

You can install iotables from CRAN or the latest development version
with github:

``` r
# From CRAN:
install.packages("iotables")

# From Github (development version)
devtools::install_github("rOpenGov/iotables")

#with vignettes:
#devtools::install_github("rOpenGov/iotables", build_vignettes = TRUE)
```

You can follow changes on the
[NEWS.md](https://github.com/rOpenGov/iotables/blob/master/NEWS.md)
file.

## Acquiring data

Eurostat’s data can be downloaded in several tidy, long-form, files, and
a lot of filtering is needed to start working with it.

Currently the following Eurostat SIOTs can be used:

-   product x product SIOTs `naio_10_cp1700` or `naio_10_pyp1700`;

-   industry x industry SIOTs `naio_10_cp1750` or`naio_10_pyp1750`;

-   use tables at basic prices `naio_10_cp1620` or `naio_10_pyp1610`;

-   trade and transport margins `naio_10_cp1620` or `naio_10_pyp1620`;

-   net taxes less subsidies `naio_10_cp1630` or `naio_10_pyp1630`;

-   Supply table at basic prices incl.transformation into purchasers’
    prices (naio\_10\_cp15) and Use table at purchasers’ prices
    (naio\_10\_cp16).

The `cp` element refers to basic prices and the `pyp` to previous years’
prices.

## Vignettes

Given the complexity of the data used by the package, probably the use
of the vignettes is needed to get a start.

The [Germany
1990](https://iotables.dataobservatory.eu/articles/germany_1990.html)
vignette presents most of the examples of the [Eurostat Manual of Supply, Use and Input-Output Tables](https://ec.europa.eu/eurostat/documents/3859598/5902113/KS-RA-07-013-EN.PDF/b0b3d71e-3930-4442-94be-70b36cea9b39?version=1.0)
(Eurostat Manual, Chapter 15.) This is a good introduction to understand
what will the functions do, and to check that they work correctly. The
`testthat` infrastructure of the package checks the proper working of
the functions against the published results from the `Eurostat Manual`.

The [Working with Eurostat
Data](https://iotables.dataobservatory.eu/articles/working_with_eurostat.html)
vignette shows how you can download, pre-process and use real data from
Eurostat.

The [United Kingdom Input-Output Analytical Tables 2010](https://webarchive.nationalarchives.gov.uk/20160114044923/http://www.ons.gov.uk/ons/rel/input-output/input-output-analytical-tables/2010/index.html)
are used for testing the `iotables` package, because they are
well-documented and detailed, organized data is available with them.
These calculations can be followed in the [United Kingdom Input-Output Analytical Tables](https://iotables.dataobservatory.eu/articles/united_kingdom_2010.html)
vignette.

### Contribute

Contributions are very welcome:

-   [Issue tracker](https://github.com/ropengov/iotables/issues) for
    feedback and bug reports.
-   [Pull requests](https://github.com/ropengov/iotables/)
-   [Github page](https://github.com/ropengov/iotables/)

### Acknowledgements

**Kindly cite this work** as follows:

Daniel Antal. (2020, June 3). rOpenGov/iotables: Importing and
Manipulating Symmetric Input-Output Tables (Version 0.4.4). Zenodo.
[https://doi.org/10.5281/zenodo.4897472](https://zenodo.org/record/4897472)
for released version. Development version URL:
<https://ropengov.github.io/iotables/>

Thanks to [@KKulma](https://github.com/KKulma/) for setting up new and
improved continuous integration, and
[@pitkant](https://github.com/pitkant) for implementing many good
practices on improving the code. See
[contributors](https://github.com/ropengov/iotables/graphs/contributors).
This project is part of [rOpenGov](http://ropengov.org).

## Code of Conduct

Please note that the iotables project is released with a [Contributor Code of Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.



{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}


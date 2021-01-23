---
title: "retroharmonize R package for survey harmonization"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Antal
- Marta Kołczyńska

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-08-25T00:00:00Z"
doi: "10.5281/zenodo.4041674"

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-25T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: The Comprehensive R Archive Network
publication_short: In *CRAN*

abstract: The goal of retroharmonize is to facilitate retrospective (ex-post) harmonization of data, particularly survey data, in a reproducible manner. The package provides tools for organizing the metadata, standardizing the coding of variables, variable names and value labels, including missing values, and for documenting all transformations, with the help of comprehensive S3 classes.

# Summary. An optional shortened abstract.
summary: The goal of retroharmonize is to facilitate retrospective (ex-post) harmonization of data, particularly survey data, in a reproducible manner.

tags: []

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
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: example
---

The aim of `retroharmonize` is to provide tools for reproducible
retrospective (ex-post) harmonization of datasets that contain variables
measuring the same concepts but coded in different ways. Ex-post data
harmonization enables better use of existing data and creates new
research opportunities. For example, harmonizing data from different
countries enables cross-national comparisons, while merging data from
different time points makes it possible to track changes over time.

Retrospective data harmonization is associated with challenges including
conceptual issues with establishing equivalence and comparability,
practical complications of having to standardize the naming and coding
of variables, technical difficulties with merging data stored in
different formats, and the need to document a large number of data
transformations. The `retroharmonize` package assists with the latter
three components, freeing up the capacity of researchers to focus on the
first.

Specifically, the `retroharmonize` package proposes a reproducible
workflow, including a new class for storing data together with the
harmonized and original metadata, as well as functions for importing
data from different formats, harmonizing data and metadata, documenting
the harmonization process, and converting between data types. See
[here](https://retroharmonize.dataobservatory.eu/reference/retrohamonize.html)
for an overview of the functionalities.

The new `labelled_spss_survey()` class is an extension of [haven’s
labelled\_spss
class](https://haven.tidyverse.org/reference/labelled_spss.html). It not
only preserves variable and value labels and the user-defined missing
range, but also gives an identifier, for example, the filename or the
wave number, to the vector. Additionally, it enables the preservation –
as metadata attributes – of the original variable names, labels, and
value codes and labels, from the source data, in addition to the
harmonized variable names, labels, and value codes and labels. This way,
the harmonized data also contain the pre-harmonization record. The
stored original metadata can be used for validation and documentation
purposes.

The vignette [Working With The labelled\_spss\_survey
Class](https://retroharmonize.dataobservatory.eu/articles/labelled_spss_survey.html)
provides more information about the `labelled_spss_survey()` class.

In [Harmonize Value
Labels](https://retroharmonize.dataobservatory.eu/articles/harmonize_labels.html)
we discuss the characteristics of the `labelled_spss_survey()` class and
demonstrates the problems that using this class solves.

We also provide two extensive case studies illustrating how the
`retroharmonize` package can be used for ex-post harmonization of data
from cross-national surveys on the example of the
[Afrobarometer](https://retroharmonize.dataobservatory.eu/articles/afrobarometer.html)
and the
[Eurobarometer](https://retroharmonize.dataobservatory.eu/articles/eurobarometer.html).
The creators of `retroharmonize` are not affiliated with either
Afrobarometer, Eurobarometer, or the organizations that designs,
produces or archives their surveys.

## Code of Conduct

Please note that the `retroharmonize` project is released with a
[Contributor Code of
Conduct](https://www.contributor-covenant.org/version/2/0/code_of_conduct/).
By contributing to this project, you agree to abide by its terms.


{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}


---
# Display name
title: New Developers
name: New Developers

# Username (this should match the folder name)
authors:
  - developer

# Is this the primary user of the site?
superuser: false

# Role/position
role: Future co-developer

# Organizations/Affiliations
organizations:
  - name: Your Affiliation
    url: ""

# Short bio (displayed in user profile at end of posts)
bio: We are looking for (open-source) collaborators that want to use their technical skillset to further our open data and reproducible research-based approach.

topics:
  - R programming language
  - Shiny applications
  - Open-source software
  - Open Data

education:
  courses:
    - course: Any computer science/statistics/social sciences/digital humanities
      institution: last year Master students, PhD students are welcome, too. 
      

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: "#contact" # For a direct email link, use "mailto:test@example.org".
- icon: keybase
  icon_pack: fab
  link: https://keybase.io/team/reprexcommunity
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/dataandlyrics
- icon: github
  icon_pack: fab
  link: https://github.com/dataobservatory-eu

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Organizational groups that you belong to (for People widget)
user_groups:
  - Join us
---

[Reprex](https://reprex.nl/) is a Dutch-American early stage startup based in the Netherlands specializing in making data reliable and accountable while delivering trustworthy analytics and AI solutions. Our diverse team works from several locations and countries; our ideal candidates are located in South Holland (the Hague/Rotterdam/Delft/Leiden), Western New York state/greater Toronto, Budapest, Bratislava, or Milano, where we have ongoing projects and team members, and thus more onboarding and team-building possibilities. That said, we are open to candidates from any location. We bridge industry and academia through various advanced statistical and ethical AI verification projects: while our R&D partners are leading universities, we aim to deploy our solutions in business environments. 

We welcome candidates from all backgrounds and mother tongues who are proficient in R and have a good working knowledge of the English language.

Reprex team members follow the Contributor Covenant, “pledg[ing] to make participation in our community a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.”

Our internal communication platform is Github for software development and Keybase, an open-source alternative to Slack. You do not have to be a master of Github Action and Github products but you must be able to make pull requests, commits, and solve issues on this platform. To apply to any of the positions below, please send [an email](https://reprex.nl/#contact) with a link to your résumé and a brief description of your interest. You can ask questions on [Keybase](https://keybase.io/team/reprexcommunity), too.

## R developer(s) {#r-developer}

We are looking for intermediate or advanced R users with a passion for open data and open science for the maintenance of our CRAN-released R packages and the development of further packages. We are pursuing a hybrid model, providing the R community with open-source packages, and engaging in paid work that utilizes this software in commercial or academic environments.

Our ideal candidate(s) are

a) at least intermediate-level R programmers or possess domain-specific knowledge relevant to our packages, or

b) advanced in R programming and agnostic to actual packages

c) excited to maintain and develop one or more of our packages

All of our packages follow the modernization of the R language and are built on rlang and vctrs. All the packages use the tidyverse as a dependency, which creates a consistent user interface (i.e. dplyr, tidyr, tidyselect.)

### Packages
Please visit our [dataobservatory.eu](https://github.com/dataobservatory-eu/) github page, and check out our advice for [new contributors](https://github.com/dataobservatory-eu/new-contributors).

[![R package
retroharmonize](https://img.shields.io/badge/R-retroharmonize-007CBB.svg)](https://iotables.dataobservatory.eu) [iotables](https://iotables.dataobservatory.eu/): an R package for reproducible input-output analysis, economic, and environmental impact assessment. The domain specific knowledge is input-output economics, multiplier analysis, and environmental impact analysis. A working knowledge of SNA or an interest in macro-finance is a plus. We develop this application within the rOpenGov community and the rOpenSci community. The application has various uses in banking, insurance, music industry, and policy design.

[![R package
iotables](https://img.shields.io/badge/R-retroharmonize-3EA135.svg)](https://retroharmonize.dataobservatory.eu)  [retroharmonize](https://retroharmonize.dataobservatory.eu/): an R package for retrospective survey harmonization and survey recycling. The domain specific knowledge is an interest in international, multi-language surveys, longitudinal surveys, and the reuse of survey data. We develop this application within the rOpenGov community and the rOpenSci community. The application has various uses in survey harmonization, data integration, and survey design. 

[![R package
regions](https://img.shields.io/badge/R-regions-00843A.svg)](https://regions.dataobservatory.eu) [regions](https://regions.dataobservatory.eu/): an R package for adjusting sub-national boundaries for the making of regional statistics.  While the U.S. has relatively stable sub-national boundaries (the US postal codes), most nations change their internal boundaries very frequently. Currently, regions tracks these changes in Europe, but our package could and should be extended to all ISO-conforming sub-national boundaries globally.  An ideal domain-specific interest is geography, cartography, and/or small-area statistics. The package is currently not developed actively, but we expect it to be developed in a small-area statistics context, or for surveying withing a regional component. 

[![R package
dataset](https://img.shields.io/badge/R-dataset-E4007F.svg)](https://dataset.dataobservatory.eu) [dataset](https://dataset.dataobservatory.eu/) creates datasets from standared R objects (data.fame, data.table, tibble, or well-structured lists like json) that are highly interoperable and can be placed into relational databases, semantic web applications, archives, repositories. They follow the FAIR principles: they are findable, accessible, interoperable and reusable. They contain the entire processing history of the dataset for reproducability.

[![R package
statcodelists](https://img.shields.io/badge/R-statcodelists-lightgrey.svg)](https://statcodelists.dataobservatory.eu) The goal of [statcodelists](https://statcodelists.dataobservatory.eu/) is to promote the reuse and exchange of statistical information and related metadata with making the internationally standardized SDMX code lists available for the R user.



[![R package
spotifyr](https://img.shields.io/badge/R-spotifyr-1db954.svg)](https://www.rcharlie.com/spotifyr) [spotifyr]()

- [dataobservatory](https://github.com/dataobservatory-eu/dataobservatory) The goal of dataobservatory is to facilitate the automated documentation, and the automated recording of descriptive and administrative (statistical processing) metadata for datasets. It also helps recording information about the computational environment to increase reproducability. The [dataobservatory](https://github.com/dataobservatory-eu/dataobservatory) package helps creatign well-formatted datasets for the APIs of our data observatories.

We are also contributing to a range of packages relevant for music analysis, open data access and open science data access and we are planning the release of new open source and non-open-source products.

We are looking for individual(s) who can resolve issues via Github. Time commitments are flexible and compensation is commensurate with experience and skill.

## Shiny developer {#shiny-developer}
We are looking for a contract-based Shiny developer who can create engaging, user-friendly multi-language Shiny interfaces to our R products. We are interested in working with candidates with experience in Shiny development and/or deployment skills, in particular, the ability to dockerize and deploy in the cloud. Currently we deploy on AWS and Netlify, but potentially we may need to deploy on other cloud servers.

Our Shiny applications have multiple users: 
- Music organizations and music researchers connected to our [Digital Music Observatory](https://music.dataobservatory.eu/)

- Sustainable finance, sustainable reporting, and climate mitigation policy experts related to our [Green Deal Data Observatory](https://greendeal.dataobservatory.eu/)

- Antitrust experts, antitrust authorities, and merger analysts associated with our [Competition Data Observatory](https://competition.dataobservatory.eu/)

- Various creative industry stakeholders related to our [Cultural and Creative Sectors Industries Data Observatory](https://ccsi.dataobservatory.eu/), mainly related to book publishing and film production.

- Some of our applications are expected to be able to communicate with various Rest APIs, e.g.: the Eurostat and Spotify Rest APIs.

Our applications must work with several language; buttons, alternate texts, and descriptions must be parameterized and available for localization. The visual elements must follow simple visual structures and a unified colour palette.


_Attribution: the female avatar is designed by [Andy Horvath - Flaticon](https://www.flaticon.com/free-icons/holiday)._

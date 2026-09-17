---
title: "The Finno-Ugric Data Sharing Space"
subtitle: "A Prototype for Multilingual Cultural Knowledge Incubation with Advanced Data Governance and Wikimedia Integration" 
date: 2024-11-19T17:16:00+01:00
lastmod: 2025-07-05T17:05:01+01:00
summary: "We would like to present the concept and a demo of a Finno-Ugric Data Sharing Space as a knowledge base and a trustworthy AI application, and a replication of our Slovak Comprehensive Music Database created with a data sharing space in 2020-2024."
# Tags: can be used for filtering projects.
tags: ["knowledge graph", "dataspace", "Finno-Ugric"]
external_link: ""
#   Otherwise, set `slides: ""`.
slides: "20250306_dreams"
authors: ["admin"]
links:
- icon: tv
  icon_pack: fas
  name: Sampo Semantic Browser (beta)
  url: https://finnougric.net/en/
- icon: database
  icon_pack: fas
  name: Finno-Ugric Data Sharing Space
  url: https://reprexbase.eu/fu/index.php
- icon: readme
  icon_pack: fab
  name: Tutorial
  url: https://downloads.reprex.nl/2026/eadh2026/EADH_HDT_workshop.html#/title-slide
- icon: clipboard
  icon_pack: fas
  name: Poster
  url: https://zenodo.org/records/22807042
- icon: music
  icon_pack: fas
  name: "Dreams playlist for DNBH2025"
  url: https://open.spotify.com/playlist/6KxCdrO9iqSTQnr8KHHmtr
- icon: z
  icon_pack: fab
  name: Zenodo Community
  url: https://zenodo.org/communities/finnougricdataspace/
- icon: linkedin
  icon_pack: fab
  name: Reprex
  url: https://www.linkedin.com/company/68855596/
- icon: question
  icon_pack: fas
  name: Ask a question!
  url: https://reprex.nl/contact/
  
url_pdf: ""
url_slides: ""
url_video: ""
url_code: ""
image:
  
  caption: ""
  focal_point: "Center"
  preview_only: true
slides: ""
editor_options: 
  markdown: 
    wrap: 72
---

<td style="text-align: center;">

{{< figure src="/png/fuds/wikibase/fu_better_view.png" caption="The Finno-Ugric Data Sharing Space connects dispersed cultural heritage knowledge across collections, languages and institutions." numbered="false" >}}

</td>

{{% callout note %}} The Finno-Ugric Data Sharing Space (FinFAIR) is an experimental environment for connecting fragmented cultural heritage without centralising collections or curatorial authority. It combines federated knowledge infrastructure with human review, provenance and governance to create inspectable Heritage Digital Twins. {{% /callout %}}

# From Fragmented Heritage to Federated Digital Twins

Finno-Ugric heritage is dispersed across museums, archives, research collections, community resources and private holdings in several countries. These collections use different languages, identifiers, descriptive traditions and semantic models. Our aim is not to replace them with a universal database, but to make selected knowledge **findable, inspectable and interoperable while preserving its provenance and local stewardship**.

The project has evolved from an early Wikibase prototype into a testbed for **Heritage Digital Twinning and semantic knowledge production**. Our current work starts from heterogeneous source material, represents proposed interpretations as candidate assertions, subjects them to competent human review, and connects the resulting warranted knowledge through bounded federation.

<td style="text-align: center;">

{{< figure src="/jpg/dreams/dreams-reprex-poster-2025.jpg" caption="The Finno-Ugric Data Sharing Space is developed through practical demonstrators, conference contributions and open working papers." numbered="false" >}}

</td>

# EADH 2026

At the  European Association for Digital Humanities conference in Kraków 2026 we present the current stage of this work through the paper **From Fragmented Heritage to Federated Digital Twins**, a hands-on workshop on building Heritage Digital Twins with open-source tools, and a poster bringing together the wider research programme.

The **Dēliņi farmstead demonstrator** provides the principal tutorial case. It connects buildings, museum reconstructions, photographs, archival documentation and other heterogeneous evidence while keeping distinctions between heritage entities, their representations and the knowledge established about them explicit. You can view and try out our worked tutorial examples to bring data into the format required by the ECCCH: [Building Heritage Digital Twins with Open-Source Tools](https://downloads.reprex.nl/2026/eadh2026/EADH_HDT_workshop.html#/title-slide).

The practical environment combines our Wikibase-based [Finno-Ugric Data Sharing Space](https://reprexbase.eu/fu/index.php), [finnougric.net](https://finnougric.net/en/) with the Sampo-UI for exploration, and [Betwixt](https://usebetwixt.com/) for human review and semantic knowledge stabilisation.

<td style="text-align: center;">

{{< figure src="/posters/EADH2026_From_Fragmented_Heritage_to_Federated_Digital_Twins_poster-released.jpg" caption="The Finno-Ugric Data Sharing Space is developed through practical data projects, digitisation efforts, conference contributions and open working papers." numbered="false" >}}

</td>

# Work in progress

Four working papers develop the methodological foundations behind the demonstrators:

- [Semantic knowledge production](https://doi.org/10.5281/zenodo.22099067) — candidate assertions, evidence, competent review and warranted knowledge.
- [Review algebra](https://doi.org/10.5281/zenodo.22091483) — transitions from one stabilised knowledge state to another through explicit review.
- [Bounded federation](https://doi.org/10.5281/zenodo.22091552) — exchanging warranted knowledge across independently governed graphs without requiring centralisation or complete semantic agreement.
- [Betwixt vocabulary](https://usebetwixt.com/articles/betwixt-vocabulary.html) — a lightweight semantic model for intermediate assertions, mappings, review outcomes and provenance.

Together, this work explores a simple principle: federate warranted knowledge, not databases. Collections and ontologies can remain plural while the evidence, provenance and review history needed to inspect shared knowledge travel with it.

{{% callout note %}} The project is an open research collaboration. We welcome cultural heritage collections, researchers and Wikimedia communities interested in Heritage Digital Twins, multilingual knowledge, federated cultural heritage data and accountable human–AI knowledge production. {{% /callout %}}


# References {#references}

Daniel Antal, Kata Gábor, Pigozne Ieva, Bogáta Tímár (2026). [Federating Open Knowledge through Wikibase: The Case of The Finno-Ugric Data Sharing Space](https://reprex.nl/publication). _Digital Humanities in the Nordic and Baltic Countries Publications_. <https://doi.org/10.5617/dhnbpub.12939>

Daniel Antal, Michal Grochal, and Christos Varvantakis. 2024. ‘Building a Music Data Sharing Space with Wikibase’. Zenodo. <https://doi.org/10.5281/zenodo.8046977>.

Curry, Edward. 2020. ‘Dataspaces: Fundamentals, Principles, and Techniques’. In *Real-Time Linked Dataspaces: Enabling Data Ecosystems for Intelligent Systems*, 45–62. Cham: Springer International Publishing. <https://doi.org/10.1007/978-3-030-29665-0_3>.

EBU, and Gaia-X. 2022. ‘Dataspace for Cultural and Creative Industries. Position Paper. v.2.0’. Gaia-X. <https://gaia-x.eu/wp-content/uploads/2022/10/EBU_position-paper_Media-Data-Space.pdf>.

Nagel, Lars, and Douwe Lycklama, eds. 2021. ‘Design Principles for Data Spaces. Position Paper. Version 1.0.’ Open DEI. <https://doi.org/10.5281/zenodo.5244997>.


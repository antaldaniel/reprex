---
title: "TextileBase"
subtitle: "A platform to collect, connect, and share meta- and research data on material, visual, and textual sources of historical clothing" 
date: 2025-05-11T15:05:10+01:00
lastmod: 2025-05-11T15:05:10+01:00
summary: "The main goal of TextileBase is to help dress history scholars and practitioners by creating a gateway to linked data that have been collected and stored by researchers and memory institutions."
# Tags: can be used for filtering projects.
tags: ["knowledge graph", "dataspace", "garments", "textiles"]
external_link: ""
#   Otherwise, set `slides: ""`.
slides: ""
authors: ["admin"]
links:
- icon: database
  icon_pack: fas
  name: TextileBase
  url: https://reprexbase.eu/textilebase/index.php?title=Main_Page
- icon: z
  icon_pack: fab
  name: Zenodo Community
  url: https://zenodo.org/communities/textilebase/
- icon: linkedin
  icon_pack: fab
  name: Reprex
  url: https://www.linkedin.com/company/68855596/
url_pdf: ""
url_slides: ""
url_video: ""
url_code: ""
image:
  caption: "Seto garments in the Obinitsa Museum, Setomaa, Estonia"
  focal_point: "Center"
  preview_only: false
slides: ""
editor_options: 
  markdown: 
    wrap: 72
---

{{% callout note %}} The main goal of TextileBase is to help dress history scholars and practitioners by creating a gateway to linked data that have been collected and stored by researchers and memory institutions. In that way it is a platform to collect, connect, and share meta- and research data on material, visual, and textual sources of historical clothing. We explain TextileBase as a linked, open, graph database in a different report. In this review we show how we placed a valuable, stand-alone dataset into this interoperable database. {{% /callout %}}

<td style="text-align: center;">

{{< figure src="/png/dataspace/textilebase/Textilebase_four_images.png" caption="Entry examples from `Linked Open Datasets on Garments from the Latgale Region`, from right to left: [Q142](https://reprexbase.eu/textilebase/index.php?title=Item:Q142), [Q180](https://reprexbase.eu/textilebase/index.php?title=Item:Q180), [Q179](https://reprexbase.eu/textilebase/index.php?title=Item:Q179), [Q181](https://reprexbase.eu/textilebase/index.php?title=Item:Q181)."  numbered="false" >}}

</td>

Textile research helps us understand how people live, adapt, and express themselves. By studying what people wear and how fabrics are made and traded, we uncover stories of culture, identity, innovation, and global connection. In 2025, as environmental and social sustainability become ever more urgent, learning from the past and present of textiles can inform better decisions in fashion, labour, and the environment. It's not just about clothing---it's about how threads connect us across time and place.

The development of `TextileBase` compels us to address complex challenges in data curation, validation, and interoperability---issues that are highly relevant across both commercial and academic domains. Because most textiles have a relatively short lifespan, their study often relies on secondary sources such as technical and artistic drawings, colour plates, and photographs that document how textiles were made, used, and worn. These sources introduce multimodality: our system must integrate and relate knowledge drawn from physical artefacts, digitised images, and descriptive texts. Moreover, the data originates from a wide range of institutions---research centres, museums, archives, and libraries---each employing distinct metadata standards. `TextileBase` is therefore not only a tool for textile historians, but also a model for handling complex, multimodal, and decentralised data in broader sectors.

The first published dataset, [Linked Open Datasets on Garments from the Latgale Region](https://reprexbase.eu/textilebase/index.php?title=Linked_Open_Datasets_on_Garments_from_the_Latgale_Region "Linked Open Datasets on Garments from the Latgale Region") contains data on Latvian traditional shirts and skirts from the Latgale region in Eastern Latvia. The [female](https://reprexbase.eu/textilebase/index.php?title=Item:Q232 "Item:Q232") and [male shirts](https://reprexbase.eu/textilebase/index.php?title=Item:Q233 "Item:Q233"), and the [skirts](https://reprexbase.eu/textilebase/index.php?title=Item:Q234 "Item:Q234") in the dataset are handmade and were worn in the 19th century. They represent both festive and daily wear of the local female and male peasants. The shirts are stored at the [National History Museum of Latvia](https://reprexbase.eu/textilebase/index.php?title=National_History_Museum_of_Latvia "National History Museum of Latvia") and the [Ethnographic Open-Air Museum of Latvia](https://reprexbase.eu/textilebase/index.php?title=Ethnographic_Open-Air_Museum_of_Latvia "Ethnographic Open-Air Museum of Latvia"). The data contain information on the locality of their origin, their approximate date of creation with various precisions, the materials they are made of, and the way of their fabrication, as well as their purpose of wearing (festive or daily wear) and wearer's ethnicity and gender. They also include the name of the museum each shirt is stored at, supplemented with its unique inventory number. Data on some sample shirts also include a photo of the shirt.

-   Check out the properties (relations) in the data model: [ListProperties](https://reprexbase.eu/textilebase/index.php?title=Special:ListProperties "Special:ListProperties")

-   See every entry in the database: [All items](https://reprexbase.eu/textilebase/index.php?title=Special:AllPages&from=&to=&namespace=120)

**How TextileBase Works**

`TextileBase` is an intelligent, modular system designed to support collaborative textile research and data sharing. Its main interface is a user-friendly Wikibase instance---built on the same software that powers Wikimedia projects---which allows researchers and textile enthusiasts to record, link, and validate knowledge.

Behind the scenes, `TextileBase` integrates advanced methods from digital humanities. It uses an ontological data model based on CIDOC-CRM, RiC, and DCTERMS, ensuring semantic interoperability with museum, archive, and library systems.

`TextileBase` s supported by a graph database and an experimental SPARQL endpoint. This enables translation of its structured data into linked data graphs, which can be enriched and exchanged with heritage institutions.

The system is multilingual by design. By leveraging international thesauri and computational linguistics, `TextileBase` supports cross-language discovery---essential in regions like Latvia, where historical textile records exist in multiple languages and scripts, and artefacts have travelled widely across Europe.

Data import and export are powered by Reprex's data curation and cleaning libraries. This modular design supports workflow automation and the integration of diverse, hard-to-find, multimodal sources. `TextileBase` is built to scale: it is cost-efficient, open-source, and adaptable for academic, commercial, or industry research teams of any size.

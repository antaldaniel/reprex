---
title: "TextileBase"
subtitle: "A platform to collect, connect, and share meta- and research data on material, visual, and textual sources of historical clothing" 
date: 2025-05-11T15:05:10+01:00
lastmod: 2025-06-23T14:07:00+02:00
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

The main goal of TextileBase is to help dress history scholars and practitioners by creating a gateway to linked data that have been collected and stored by researchers and memory institutions. In that way, it is a platform to collect, connect, and share meta- and research data on material, visual, and textual sources of historical clothing.

{{% callout note %}} 
1. Overview:  [How TextileBase Works](#works) 👉🏾 [connecting artefacts](#connecting) 👉🏻 [LOD challenges](#lodchallenges)
👉🏼  [secondary sources](#secondary)
---------------------------------------
2. Example: [Finno-Ugric Traditional Clothing](#fucasestudy)
---------------------------------------
3. Use cases: How the technology of TextileBase can be used 👉🏼  [e-commerce, inventory & backoffice optimisation](#business) 👉🏾   [institutional PPP with museums, NGOs, private collectors](#wiki)  👉🏿 [research automation and research data management](#ai)
{{% /callout %}}

<td style="text-align: center;">

{{< figure src="/png/dataspace/textilebase/Textilebase_four_images.png" caption="Entry examples from Linked Open Datasets on Garments from the Latgale Region, from right to left: [Q142](https://reprexbase.eu/textilebase/Item:142), [Q180](https://reprexbase.eu/textilebase/Item:Q180), [Q179](https://reprexbase.eu/textilebase/Item:Q179), [Q181](https://reprexbase.eu/textilebase/Item:Q181)." numbered="false" >}}

</td>

Textile research helps us understand how people live, adapt, and express themselves. By studying what people wear and how fabrics are made and traded, we uncover stories of culture, identity, innovation, and global connection. In 2025, as environmental and social sustainability become ever more urgent, learning from the past and present of textiles can inform better decisions in fashion, labour, and the environment. It's not just about clothing—it's about how threads connect us across time and place.

The development of `TextileBase` compels us to address complex challenges in data curation, validation, and interoperability—issues that are highly relevant across both commercial and academic domains. Because most textiles have a relatively short lifespan, their study often relies on secondary sources such as technical and artistic drawings, colour plates, and photographs that document how textiles were made, used, and worn. These sources introduce multimodality: our system must integrate and relate knowledge drawn from physical artefacts, digitised images, and descriptive texts. Moreover, the data originates from a wide range of institutions—research centres, museums, archives, and libraries—each employing distinct metadata standards. `TextileBase` is therefore not only a tool for textile historians, but also a model for handling complex, multimodal, and decentralised data in broader sectors.

The first published dataset, [Linked Open Datasets on Garments from the Latgale Region](https://reprexbase.eu/textilebase/index.php?title=Linked_Open_Datasets_on_Garments_from_the_Latgale_Region "Linked Open Datasets on Garments from the Latgale Region") contains data on Latvian traditional shirts and skirts from the Latgale region in Eastern Latvia. The [female](https://reprexbase.eu/textilebase/index.php?title=Item:Q232 "Item:Q232") and [male shirts](https://reprexbase.eu/textilebase/index.php?title=Item:Q233 "Item:Q233"), and the [skirts](https://reprexbase.eu/textilebase/index.php?title=Item:Q234 "Item:Q234") in the dataset are handmade and were worn in the 19th century. They represent both festive and daily wear of the local female and male peasants. The shirts are stored at the [National History Museum of Latvia](https://reprexbase.eu/textilebase/index.php?title=National_History_Museum_of_Latvia "National History Museum of Latvia") and the [Ethnographic Open-Air Museum of Latvia](https://reprexbase.eu/textilebase/index.php?title=Ethnographic_Open-Air_Museum_of_Latvia "Ethnographic Open-Air Museum of Latvia"). The data contain information on the locality of their origin, their approximate date of creation with various precisions, the materials they are made of, and the way of their fabrication, as well as their purpose of wearing (festive or daily wear) and wearer's ethnicity and gender. They also include the name of the museum each shirt is stored at, supplemented with its unique inventory number. Data on some sample shirts also include a photo of the shirt.

## A Semantic Knowledge Graph for Textile and Dress History

**TextileBase** is a knowledge graph that interconnects databases and secondary sources—such as artefact photographs, contemporary images, drawings, and written descriptions—related to textile and dress history. It supports diverse areas of textile research, from historical dress studies to sustainable fashion.

-   See every entry in the database: [All items](https://reprexbase.eu/textilebase/index.php?title=Special:AllPages&from=&to=&namespace=120)

### How TextileBase Works {#works}

`TextileBase` is an intelligent, modular system designed to support collaborative textile research and data sharing. Its main interface is a user-friendly Wikibase instance—built on the same software that powers Wikimedia projects—which allows researchers and textile enthusiasts to record, link, and validate knowledge.

Behind the scenes, `TextileBase` integrates advanced methods from digital humanities. It uses an ontological data model based on CIDOC-CRM, RiC, and DCTERMS, ensuring semantic interoperability with museum, archive, and library systems.

`TextileBase` is supported by a graph database and an experimental SPARQL endpoint. This enables translation of its structured data into linked data graphs, which can be enriched and exchanged with heritage institutions.

The system is multilingual by design. By leveraging international thesauri and computational linguistics, `TextileBase` supports cross-language discovery—essential in countries or regions where historical textile records exist in multiple languages and scripts, and artefacts have travelled widely across Europe.

Data import and export are powered by Reprex's data curation and cleaning libraries. This modular design supports workflow automation and the integration of diverse, hard-to-find, multimodal sources. `TextileBase` is built to scale: it is cost-efficient, open-source, and adaptable for academic, commercial, or industry research teams of any size.

Technically speaking, building an interactive website for textile history is like setting up a webshop—except all the product information is either missing or fragmented. There are no barcodes, producers, or standard descriptions. Instead, the relevant information is buried in academic knowledge, secondary sources, or scattered fragments of primary data.

This is where **AI can significantly assist**: by gathering, linking, and inferring data at a speed and scale beyond human capacity.

### Connecting Surviving Artefacts {#connecting}

Unlike metal objects or buildings, textiles are fragile and rarely survive intact. They are worn, used, and discarded. Even from the 19th century, very few textiles remain.

Our goal is to create a tool that connects fragmented museum inventories and catalogues across institutions—linking rare textile artefacts in a coherent, searchable network.

### The Challenges of Linked Open Data in Textile History {#lodchallenges}

While digital humanities frequently refer to “linked open data” or the “Internet of Things,” textile history is still at the early stages of adopting these frameworks. A key goal of TextileBase is to give each artefact—like the **Seto shirt**—a unique URI. But generating URIs for garments in small rural museums or private collections is often time-consuming and expensive.

TextileBase seeks to streamline this process—making it **faster, cheaper, and more reliable.**

<td style="text-align: center;">

{{< figure src="/png/dataspace/textilebase/Leather_shoes_with_fur_front_side_Mõniste_Rural_Life_Museum.jpg" caption="These furry leather shoes are a very rare specimen, and they are on display in the Mõniste Rural Life Museum. They do have a local inventory number, but none of the items of this small and excellent museum is available on the Internet of Things. By adding artefact photographs, a DOI, or an ISCC identifier, and giving a permanent identifier for this artefact, we can connect it with other leather shoes, other Seto garments that are found in faraway collections (TextileBase [Q256](https://reprexbase.eu/textilebase/Item:Q256)). For example, Aladár Bán collected a somewhat similar shoe in Setomaa in 1911. Finding that artefact in the digital collection of the Hungarian Ethnographic Museum in Budapest under the inventory number [NM97021](https://gyujtemeny.neprajz.hu/neprajz.01.01.php?bm=1&kv=3300296&nks=1) and the rather specialist and a bit archaic title „bocskor” is even a challenge for native speakers of that language. It is connected to traditional footwear as TextileBase [Q348](https://reprexbase.eu/textilebase/Item:Q348)." numbered="false" >}}

</td>

### The Importance of Secondary Sources {#secondary}

Historical collecting practices were often biased. Textiles worn by everyday people—peasants, laborers, minority groups—were rarely preserved. Instead, most surviving collections reflect the lives of elites or were gathered during ethnographic expeditions with colonial or exoticizing perspectives.

That’s why **secondary sources**—such as period photographs, illustrations, and books—are so valuable. They often document everyday garments, offering insights missed by early collectors.

<td style="text-align: center;">

{{< figure src="/png/dataspace/textilebase/028747_ERM_Fk213_172_028747_original_detail.jpg" caption="The Trousers of a Seto man in the village of Võmmorski in Setomaa municipality (TextileBase [Q331](https://reprexbase.eu/textilebase/Item:Q331)) is a detail from the photo collection of the Estonian National Museum’s item Johannes Pääsuke: Seto men in the village of Võmmorski in Setomaa municipality (1913). The original photo: *Setu mehed Võmmorski külas Setomaa vallas*, [ERM Fk 213:172](https://www.muis.ee/museaalview/610034), Eesti Rahva Muuseum (in TextileBase [Q332](https://reprexbase.eu/textilebase/Item:Q332))." numbered="false" >}}

</td>

## Case Study: Finno-Ugric Traditional Clothing {#fucasestudy}

We focus on the clothing traditions of small Finno-Ugric communities—such as the **Setos** and **Livonians**—due to the technical and linguistic challenges involved.

For example, Livonian communities in present-day Latvia were largely assimilated by the late 19th century. Setos are now found in southeastern Estonia and Russia's Pskov oblast. Their artefacts are scattered across Finnish, Estonian, and Hungarian archives, usually documented in those languages—rarely in Livonian, Seto, or even English.

<td style="text-align: center;">

{{< figure src="/png/dataspace/textilebase/museovirasto.7A2CD646E25259E28BA4B2F260F9864B-0-6x4_middle.jpg" caption="The Livonian skirt (in the National Museum of Finland: [SU4106:383](https://www.finna.fi/Record/museovirasto.7A2CD646E25259E28BA4B2F260F9864B); in TextileBase [Q347](https://reprexbase.eu/textilebase/Item:Q347)) has provenance information of Venäjä, Kuurinmaa, Pissen, Piza; which means roughly Russia, Courland, Pissen, Piza ([Q346](https://reprexbase.eu/textilebase/Item:Q346)). This is the Finnish-language information recorded in the early 20th century about the Courland region of Imperial Russia using the Baltic German and by now moribund Livonian village name. That village is known today as [Miķeļtornis](https://reprexbase.eu/textilebase/Item:Q346) in Latvian (local Livonian spelling: Pizā), Courland is known as Kurzeme, and of course, the country is Latvia." numbered="false" >}}

</td>

We must build a **historical namespace** of place names, languages, even spelling history, and garment classifications to search and understand this data. This includes terms like "shirt" in Finnish (paita), Hungarian (ing), or Estonian, and accounts for changing styles, materials, and local terminologies. This is one of the uses of `TextileBase`: it contains knowledge about words, placenames, their morphology, so that researchers who are not familiar with the collection's language (and its historical changes, abbreviations) can work globally.

{{% callout note %}}

### What Business Can Learn from TextileBase {#business}

You may think this is a niche academic project. But the challenges we tackle—**changing place names, multilingual records, incomplete legacy data**—are universal in business.

- When a company acquires a legacy system, it spends time and money just fixing inconsistent addresses.
- Global databases face problems when towns merge, streets are renamed, or countries change borders.
- People change names, too: marriage and divorce often change surnames. Rights are inherited by descendants who may or may not use the same surnames, making it particularly difficult to trace long-standing copyright claims.
- Searching for “a skirt from Venäjä, Kuurinmaa, Pissen” is equivalent to finding a misfiled invoice or product from a renamed supplier.

Our work shows how **semantic technology and AI can solve real-world problems** across industries—by cleaning, organizing, and making sense of historical or fragmented information.

{{% /callout %}}

### Building a Wikimuseum for Dispersed Collections {#wiki}

Inspired by Wikimedia Estonia’s multi-language, open-access model, we propose a **virtual museum**—a **Wikimuseum**—that brings together:

- Artefacts from rural museums (e.g., Mõniste, Saatse, Värska)
- Items in national museums (Estonia, Finland, Hungary)
- Private collections that would never be physically exhibited together

This approach connects dispersed knowledge—across time, languages, and borders—into a shared digital space. Please take a look at our early-stage prototype of the collaborative museum:

👉🏾  Presentation [The Concept of a WikiMuseum: WikiMuseum = GLAM Wiki + Wikibase + Data Sharing Space](https://reprex.nl/slides/20250609_wikimuseum_concept/) press **F** for full-screen view

👉🏻  <https://et.wikipedia.org/wiki/Vikipeedia:GLAM/Seto_Traditional_Culture_Heritage/1>

<td style="text-align: center;">

{{< figure src="/png/dataspace/textilebase/20250605_TextileBase_02.png" caption="Try out TextileBase: connect your artefacts, photographs, bibliographic sources, drafts, conference presentations, publications with other multimodal, textual, visual information about textiles and dress history and utilise the power of collaborative, AI-supported research." numbered="false" >}}

</td>

## Research Automation & Research Data Management

### How AI Supports Textile Research {#ai}

TextileBase incorporates **AI-driven tools**—language models, translation engines, inference systems—that can:

- Search for historical place names across multilingual archives 👉🏾  [What a Moribund Language Can Teach Spotify and Shopify?](/post/2025-06-19-gazetteer/)
- Identify garments in photos or scanned books
- Detect and match synonyms or spelling variants
- Flag potentially relevant images and documents for expert review

By operating within the TextileBase framework, our AI tools remain **human-controlled and explainable**, reducing the risk of hallucinated or misleading results.

### Research Data Management

You can do research data management better and cheaper. European and U.S. grants usually require you to do your research data management according to the 5-star FAIR model. We already apply the 8-star model that increases value and impact, adds extra impact to your research data management, and delivers more for less.

- Your data on the EU Open Data Portal, Zenodo, Europeana and the ECCCH
- Tabular datasets
- RDF datasets
- SPARQL endpoint
- Sampo UI for one-click queries

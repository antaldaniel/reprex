---
title: "TextileBase: Introduction"
subtitle: "Federating Open Knowledge About Textiles & Dress History"

projects: []
categories:

event: TextileBase Seminars 1
event_url: ""


location: ELTE Digitális Bölcsészet Tanszék
address:
  city: Budapest
  street: Múzeum krt. 6-8. II. emelet. 206.
  postcode: H-1088
  country: Hungary

summary: "We started experimenting with the legal, organisational, semantic and technical challenges of creating a genuinely trustworthy, AI-supported data-sharing space that can find and connect tangible and intangible elements of the Finno-Ugric cultural universes."

# Talk start and end times.
date: '2025-07-10T15:00:00+02:00'
date_end: '2025-07-10T16:30:00+02:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-06-23T14:52:00+02:00'

authors: ["daniel_antal", "Ieva Pigozne", "Mester, Anna", "Nagy, Mihály", "Gábor, Kata", "Frederico, Asmah"]
tags: ["Dataspace", "TextileBase", "Dataspace", "Wikidata", "Lexeme"]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Center
  preview_only: false

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

links:
- icon: linkedin
  icon_pack: fab
  name: Reprex
  url: https://www.linkedin.com/company/68855596/
- icon: database
  icon_pack: fas
  name: TextileBase
  url: https://reprexbase.eu/textilebase/index.php
- icon: info
  icon_pack: fas
  name: Project Information
  url: /project/textilebase/
- icon: z
  icon_pack: fab
  name: Zenodo Community
  url: https://zenodo.org/communities/textilebase/records?q=&l=list&p=1&s=10&sort=newest

# Markdown Slides (optional).
slides: "20250306_dreams"
---

{{% callout note %}} 
The July 10 is a hybrid event that you can attend either in person or online. Please register via the [contact form](https://reprex.nl/contact/) or via email.
For those who cannot visit this event, we offer an alternative online webinar. (Please fill out your availability [here](https://doodle.com/meeting/organize/id/dB9WEnkb)
The start time is 15.00 Central European Summer Time, 14.00 GMT and 16.00 EET. If you physically attend, please arrive a few minutes early. 
{{% /callout %}}

We warmly invite colleagues, friends, and stakeholders interested in cultural
heritage data, digital humanities, and AI-supported research to a light and lively 
summer seminar on three interconnected initiatives.

- Our main focus is on [`TextileBase`](https://reprex.nl/project/textilebase/) – our linked open data platform for dress history 
- We show a glimpse of our futuristic multi-modal, multi-language graph with data, images, music, 
audiovisual [`Finno-Ugric Data Sharing Space`](/project/finnougricdataspace/), as a way to connect clothing history into a broader regional knowledge platform.
- And the [`Wikimuseum concept`](https://reprex.nl/slides/20250609_wikimuseum_concept/) for wider impact, co-curated collections and exhibitions.

This informal gathering is not about theoretical publications (although we’re happy to send you preprints!). 
It’s about showcasing how things actually work, especially when archival depth 
is shallow and data quality is mixed. There’s a big difference between writing 
about data integration in a computer lab — and actually building tools that work 
for researchers and cultural institutions across languages, countries, 
and platforms.

## Topics For Discussion
{{% callout note %}} 
Each speaker will present a short, live demo or walkthrough (10–12 minutes), followed by Q&A and a casual hybrid meet-up.

Daniel Antal: What is TextileBase? Connecting knowledge across museums, archives, libraries, repositories, Europeana, ECCCH, Wikidata.

Anna Márta Mester: Technical, but not Deep Dive: Using the Wikibase Suite, SPARQL endpoints, and Sampo-UI for comfortable scholarly research.

Ieva Pigozne: Use Case: From years to weeks — how Latgalian data curation paved the way for rapid digitisation of Seto and Livonian datasets.

Kata Gábor: AI for Cultural Heritage: From multilingual NLP to image annotation and ontology enrichment in noisy or sparse data environments.

Asmah Federico: [WikiMuseum](https://reprex.nl/slides/20250609_wikimuseum_concept/): A vision for co-curated, multilingual virtual exhibitions with dispersed physical collections.{{% /callout %}}

### Wikibase Interfaces
<td style="text-align: center;">
{{< figure src="/png/dataspace/textilebase/Textilebase_four_images.png" caption="Entry examples from Linked Open Datasets on Garments from the Latgale Region, from right to left: [Q142](https://reprexbase.eu/textilebase/Item:142), [Q180](https://reprexbase.eu/textilebase/Item:Q180), [Q179](https://reprexbase.eu/textilebase/Item:Q179), [Q181](https://reprexbase.eu/textilebase/Item:Q181)." numbered="false" >}}
</td>

In machine-readable format: <https://reprexbase.eu/textilebase/Special:EntityData/Q180.ttl>

### SPARQL Endpoint
We will place here a few sampe querries:
- [Latgalian Garments Dataset](http://135.181.91.51:3030/#/dataset/textilebase/query?query=PREFIX%20rdf%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F1999%2F02%2F22-rdf-syntax-ns%23%3E%0APREFIX%20xsd%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2001%2FXMLSchema%23%3E%0APREFIX%20rdfs%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2000%2F01%2Frdf-schema%23%3E%0APREFIX%20owl%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2002%2F07%2Fowl%23%3E%0APREFIX%20wikibase%3A%20%3Chttp%3A%2F%2Fwikiba.se%2Fontology%23%3E%0APREFIX%20skos%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2F2004%2F02%2Fskos%2Fcore%23%3E%0APREFIX%20schema%3A%20%3Chttp%3A%2F%2Fschema.org%2F%3E%0APREFIX%20cc%3A%20%3Chttp%3A%2F%2Fcreativecommons.org%2Fns%23%3E%0APREFIX%20geo%3A%20%3Chttp%3A%2F%2Fwww.opengis.net%2Font%2Fgeosparql%23%3E%0APREFIX%20prov%3A%20%3Chttp%3A%2F%2Fwww.w3.org%2Fns%2Fprov%23%3E%0APREFIX%20wd%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fentity%2F%3E%0APREFIX%20data%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Ftextilebase%2FSpecial%3AEntityData%2F%3E%0APREFIX%20s%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fentity%2Fstatement%2F%3E%0APREFIX%20ref%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Freference%2F%3E%0APREFIX%20v%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fvalue%2F%3E%0APREFIX%20wdt%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fdirect%2F%3E%0APREFIX%20wdtn%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fdirect-normalized%2F%3E%0APREFIX%20p%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2F%3E%0APREFIX%20ps%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fstatement%2F%3E%0APREFIX%20psv%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fstatement%2Fvalue%2F%3E%0APREFIX%20psn%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fstatement%2Fvalue-normalized%2F%3E%0APREFIX%20pq%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fqualifier%2F%3E%0APREFIX%20pqv%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fqualifier%2Fvalue%2F%3E%0APREFIX%20pqn%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fqualifier%2Fvalue-normalized%2F%3E%0APREFIX%20pr%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Freference%2F%3E%0APREFIX%20prv%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Freference%2Fvalue%2F%3E%0APREFIX%20prn%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Freference%2Fvalue-normalized%2F%3E%0APREFIX%20wdno%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Fprop%2Fnovalue%2F%3E%0APREFIX%20txb%3A%20%3Chttps%3A%2F%2Freprexbase.eu%2Ftextilebase%2FItem%3A%3E%0A%0ASELECT%20%3Firi%20%3Flabel%20%3Fdescription%20%3FtypeLabel%20%3FkeeperLabel%20%3Fuser%20%3Flocation%20%3FspatialRelation%20WHERE%20%7B%0A%20%20%3Fgarment%20wdt%3AP5%20wd%3AQ141%20.%0A%0A%20%20BIND%28IRI%28REPLACE%28STR%28%3Fgarment%29%2C%20%22https%3A%2F%2Freprexbase.eu%2Fentity%2F%22%2C%20%22https%3A%2F%2Freprexbase.eu%2Ftextilebase%2FItem%3A%22%29%29%20AS%20%3Firi%29%0A%0A%20%20%3Fgarment%20rdfs%3Alabel%20%3Flabel%20.%0A%20%20FILTER%28LANG%28%3Flabel%29%20%3D%20%22en%22%29%0A%0A%20%20OPTIONAL%20%7B%20%3Fgarment%20schema%3Adescription%20%3Fdescription%20.%20FILTER%28LANG%28%3Fdescription%29%20%3D%20%22en%22%29%20%7D%0A%0A%20%20%23%20TYPE%20from%20P3%20or%20P4%2C%20show%20its%20label%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%7B%20%3Fgarment%20wdt%3AP3%20%3Ftype%20.%20%7D%0A%20%20%20%20UNION%0A%20%20%20%20%7B%20%3Fgarment%20wdt%3AP4%20%3Ftype%20.%20%7D%0A%20%20%20%20%3Ftype%20rdfs%3Alabel%20%3FtypeLabel%20.%0A%20%20%20%20FILTER%28LANG%28%3FtypeLabel%29%20%3D%20%22en%22%29%0A%20%20%7D%0A%0A%20%20%23%20Keeper%20%28P65%29%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%3Fgarment%20wdt%3AP65%20%3Fkeeper%20.%0A%20%20%20%20%3Fkeeper%20rdfs%3Alabel%20%3FkeeperLabel%20.%0A%20%20%20%20FILTER%28LANG%28%3FkeeperLabel%29%20%3D%20%22en%22%29%0A%20%20%7D%0A%0A%20%20%23%20User%20%28P28%29%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%3Fgarment%20wdt%3AP28%20%3Fuser%20.%0A%20%20%7D%0A%0A%20%20%23%20Location%20from%20any%20property%20pointing%20to%20Q45%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%3Fgarment%20%3FspatialRelation%20wd%3AQ45%20.%0A%20%20%20%20wd%3AQ45%20rdfs%3Alabel%20%3Flocation%20.%0A%20%20%20%20FILTER%28LANG%28%3Flocation%29%20%3D%20%22en%22%29%0A%20%20%7D%0A%7D%0ALIMIT%20100%0A)


### Sampo UI

We are going to unveil a similar interactive website on the webinar to the [OperaSampo](https://oopperasampo.fi/en/); `TextileBase` will run on Sampo, following [dozens of successful](https://seco.cs.aalto.fi/tools/sampo-ui/) digital humanities projects.

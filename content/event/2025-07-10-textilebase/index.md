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
date: '2025-07-03T15:00:00+02:00'
date_end: '2025-07-03T16:30:00+02:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-06-23T14:52:00+02:00'

authors: ["daniel_antal", "Ieva Pigozne", "Mester, Anna", "Nagy, Mihály", "Gábor, Kata"]
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
Please register via the [contact form](https://reprex.nl/contact/) or via email.
For those who cannot make it this day, we offer an alternative online webinar. 
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

Ieva Pigozne: Use Case: From years to weeks — how Latgalean data curation paved the way for rapid digitisation of Seto and Livonian datasets.

Kata Gábor: AI for Cultural Heritage: From multilingual NLP to image annotation and ontology enrichment in noisy or sparse data environments.

Asmah Frederico: [WikiMuseum](https://reprex.nl/slides/20250609_wikimuseum_concept/): A vision for co-curated, multilingual virtual exhibitions with dispersed physical collections.{{% /callout %}}

### Wikibase Interfaces
<td style="text-align: center;">
{{< figure src="/png/dataspace/textilebase/Textilebase_four_images.png" caption="Entry examples from Linked Open Datasets on Garments from the Latgale Region, from right to left: [Q142](https://reprexbase.eu/textilebase/Item:142), [Q180](https://reprexbase.eu/textilebase/Item:Q180), [Q179](https://reprexbase.eu/textilebase/Item:Q179), [Q181](https://reprexbase.eu/textilebase/Item:Q181)." numbered="false" >}}
</td>

In machine-readable format: <https://reprexbase.eu/textilebase/Special:EntityData/Q180.ttl>

### SPARQL Endpoint
We will place here a few sampe querries:
<http://135.181.91.51:3030/#/dataset/textilebase/query>

### Sampo UI

We are going to unveil a similar interactive website on the webinar to the [OperaSampo](https://oopperasampo.fi/en/); `TextileBase` will run on Sampo, following [dozens of successful](https://seco.cs.aalto.fi/tools/sampo-ui/) digital humanities projects.

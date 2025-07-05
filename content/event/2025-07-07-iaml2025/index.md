---
title: "Interoperability of Music Libraries and Archives with Public and Private Music Services"
subtitle: "How can music libraries and archives stay visible and relevant in an era of streaming, recommendation algorithms, and fragmented data infrastructures?"

projects: []
categories:

event: IAML 2025
event_url: "https://iaml2025.at/"

location: Mozarteum University
address:
  city: Salzburg
  street: Mirabellplatz 1
  postcode: 5020
  country: Austria

summary: ""

# Talk start and end times.
date: '2025-07-07T16:00:00+02:00'
date_end: '2025-07-07T17:30:00+02:00'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-07-05T08:52:00+02:00'

authors: ["daniel_antal", "Mester, Anna", "Zilkova, Anna"]
tags: ["Open Music Observatory", "knowledge graph", "dataspace", "library", "interoperability", "music"]
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
  name: SKMMDb (demo)
  url: 
- icon: info
  icon_pack: fas
  name: Project Information
  url: /project/skcmdb/
- icon: z
  icon_pack: fab
  name: Zenodo Community
  url: https://zenodo.org/communities/music_observatory/

# Markdown Slides (optional).
slides: "20250306_dreams"
---

{{% callout note %}} 
16:00–17:30 Our presentation takes place in the session of 
**Music Libraries of Tomorrow: Reaching out to Wider Audiences** at the 
Mozarteum University E.001 HS Thomas Bernhard room.
{{% /callout %}}



Our presentation at **IAML 2025** introduces the *Slovak Comprehensive Music Database*
(SKCMDb), a national pilot within [Open Music Europe](https://openmuse.eu/). 
It offers a pragmatic, scalable solution to a widespread challenge: aligning 
metadata from libraries, archives, rights organisations, and digital distributors 
without centralisation or heavy infrastructure.

Built on the *European Interoperability Framework*, **SKCMDb** creates a legal, 
semantic, and organisational bridge between institutions like the Slovak Music Centre, 
SOZA, and public libraries, while also integrating with global platforms like 
Wikidata and MusicBrainz. We show how library records, music rights data, and 
streaming metadata can be reused and enriched across systems—supporting 
discoverability, legal compliance (like local content quotas), and better 
access to Slovak music.

This presentation will be especially valuable for professionals working in 
metadata curation, authority control, and digital service design, and those 
seeking low-cost, high-impact pathways to public-private interoperability 
in cultural heritage.

Check out the entry examples related to Albrecht's: [Missa in C (printed, Hudobné centrum)](https://reprexbase.eu/skcmdb/Item:Q485) with library and webshop access points, and linked data on the composition itself [Q479](https://reprexbase.eu/skcmdb/Item:Q479), linked to its recorded manifestations. 

### Wikibase Interfaces
<td style="text-align: center;">
{{< figure src="/png/skcmdb/skcmdb-missa-in-c-print.png" caption="Check out the entry examples related to Albrecht's [Missa in C (printed, Hudobné centrum)](https://reprexbase.eu/skcmdb/Item:Q485) with library and webshop access points, and linked data on the composition itself [Q479](https://reprexbase.eu/skcmdb/Item:Q479), linked to its recorded manifestations." numbered="false" >}}
</td>

In machine-readable TTL format: <https://reprexbase.eu/skcmdb/Special:EntityData/Q485.ttl>
In [XML](https://reprexbase.eu/skcmdb/Special:EntityData/Q485.rdf) or 
[JSON](https://reprexbase.eu/skcmdb/Special:EntityData/Q485.json), 
[JSON-LD](https://reprexbase.eu/skcmdb/Special:EntityData/Q485.jsonld), 
[N-Triples](https://reprexbase.eu/skcmdb/Special:EntityData/Q485.nt).

### SPARQL Endpoint
<http://135.181.91.51:3030/#/dataset/skcmdb/query>; requires password.

### Sampo semantic browser

<td style="text-align: center;">
{{< figure src="/png/skcmdb/skcmdb-library-access.png" caption="Sneak peak: [http://135.181.91.51:3007/en/](http://135.181.91.51:3007/en/)" numbered="false" >}}
</td>

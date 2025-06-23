---
title: "Metadata Groundhog Day: What a Moribound Language Can Teach Spotify and Shopify"
subtitle: "Data description and data access points"

summary: "We built a multilingual gazetteer for a few villages on the Livonian coast. It accidentally solved problems that plague music metadata, e-commerce catalogs, and enterprise CRMs."

# Schedule page publish date (NOT talk date).
date: '2025-06-19T18:45:00+02:00'
lastmod: "2025-06-19T19:06:00+02:00"

authors: [daniel_antal"]
tags: ["metadata", "entity resolution", "linked data", "music tech", "e-commerce", "Reprexbase"]

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
- icon: database
  icon_pack: fas
  name: "Finno-Ugric Data Sharing Space"
  url: https://reprexbase.eu/fu/Main_Page
- icon: z
  icon_pack: fas
  name: "Zenodo"
  url: https://zenodo.org/records/15668712
- icon: file-pdf
  icon_pack: fas
  name: "Download"
  url: https://zenodo.org/records/15668712/files/Remapping_the_Livonian_Coast.pdf?download=1
- icon: linkedin
  icon_pack: fab
  name: Reprex
  url: https://www.linkedin.com/company/68855596/

# Markdown Slides (optional).
#slides: 20240605_D_Antal_CSRD_Automated_Compliance
---

And if you want to fix these errors, you may find that you are back to the **Data Sisyphus**.

When you build systems in the cloud, or in your local architecture, at one point you will realise that naming things — places, people, products — or updating their whereabouts is probably the most time-consuming, most expensive, and most error-prone workflow.

In this blogpost, we want to talk about what seems like the easiest part of a location: the name of the city, town, or village.

## Mazirbe Is Missing Again

We recently built a multilingual gazetteer — essentially a reconciled database of place names — for a tiny stretch of the Livonian coast in Latvia. At first glance, this might seem like a project rooted deeply in the digital humanities.

But here’s the twist: the very same problems we tackled here are the ones plaguing the music industry, global e-commerce platforms, and enterprise software stacks.

<td style="text-align: center;">
{{< figure src="/png/identifiers/geonames_lielirbe_2x1.png" caption="This is Gross-Irben 👉 [Lielirbe / Īra / Irben / Suur-Irben](https://reprexbase.eu/fu/Item:Q4429) 👉 [Familiar with RDF: see in TTL](https://reprexbase.eu/fu/Special:EntityData/Q4429.ttl); Klein-Irben will be near Gross-Irben, and Irē is almost Īra!"  numbered="false" >}}
</td>

Mazirbe is a small, big place. It definitely exists, and it is the cultural center of a small nation: the Livonians. Yet, when you are looking for clothing, music, or photographs that should come from Mazirbe in a relevant database, you often find nothing. Not even the place.

{{% callout note %}}
#### But Mazirbe exists! 
Depending on the record, it might appear as:
-   Mazirbe (Latvian) •  Irē (Livonian) • Мазирбе (Russian) • Klein-Irben (German) • Suur-Irben (Finnish-German hybrid) •
Мазирбе (Russian) •  Mazirbė (Lithuanian)

<td style="text-align: center;">
{{< figure src="/webp/identifiers/old_map_of_courland.webp" caption="[Meyer‘s Zeitungsatlas 050 – Russland- Gouvernement Sankt Petersburg, Esthland, Liefland, Kurland](https://upload.wikimedia.org/wikipedia/commons/0/04/Meyer%E2%80%98s_Zeitungsatlas_050_%E2%80%93_Russland-_Gouvernement_Sankt_Petersburg%2C_Esthland%2C_Liefland%2C_Kurland.jpg)"  numbered="false" >}}
</td>



{{% /callout %}}

This kind of variation isn’t just a cultural footnote — it breaks databases, mismatches search results, and silently corrupts analytics.

If you're in music metadata, this is your **"JAY Z" vs. "Jay-Z" vs. "Shawn Carter"** problem.

If you're in e-commerce, it’s **“Red Crewneck XXL” vs. “Crewneck, crimson, 2XL”**.

Same data structure. Same unresolved chaos.

## A Gazetteer That Works Like Real Life

We created a semantic, multilingual, multiscript gazetteer for the Livonian coast. Each place entry includes:

-   All known name variants across time, languages, and scripts

-   Structured links to global authority services (Wikidata, VIAF, GeoNames)

-   Canonical IDs, multilingual labels, and machine-readable formats (RDF, TTL, etc.)

-   Context about administrative boundaries, historical changes, and source provenance


Try us:

<td style="text-align: center;">
{{< figure src="/png/identifiers/fuds_mazirbe_2x1.png" caption="👉 [Mazirbe / Irē / Klein-Irben / Мазирбе / Mazirbė](https://reprexbase.eu/fu/Item:Q4202) 👉 [Familiar with RDF: see in TTL](https://reprexbase.eu/fu/Special:EntityData/Q4202.ttl)"  numbered="false" >}}
</td>

We published it using **Wikibase** — the same technology that powers Wikidata. It's not just a spreadsheet; it's a small, dynamic knowledge graph.

And we also put it into **BlazeGraph**, so you can find all these villages — and also the music, the clothing, or photographs that come from them.

## So What?

Here’s why this matters outside the northern shores of Kurzeme, or beyond the borders of Latvia:

-   In global **supply chains**, location names and vendor names drift constantly. While country boundaries are relatively stable, subnational boundary changes — counties, parishes, provinces, municipal borders — happen **thousands of times per year**, even within Europe.

-  In **streaming metadata**, artists get duplicated, misspelled, or transliterated inconsistently. It’s not unusual to find **dozens of same-named artists** in a distributor’s or rights manager’s roster.

-  In **CRM systems**, customers have multiple entries because of one diacritic. *Irē* becomes *Ire* if the user didn’t have `ē` installed.

-  In **museum heritage databases** and **webshops**, items disappear because their place of origin changed names three times since the accession record was created.

Our little example was created to accompany a digital humanities publication, but it's **not just a “humanities” problem**. It’s a **cross-sector, multilingual, historical, bureaucratic, data problem**.

And we’re all living in it.

## Lessons We Took Away

-  Don’t fight ambiguity. **Model it.**

- Linked data models (RDF, Wikibase) handle aliases and variants with elegance.

- Small, local, curated vocabularies can scale conceptually to global systems.

- Top-down standardization fails in diverse data ecosystems — **context wins**.

## See It / Fork It / Repurpose It

You can explore the full Livonian Gazetteer here:

- Web UI: <https://reprexbase.eu/fu/Main_Page>

- RDF example: <https://reprexbase.eu/fu/Special:EntityData/Q4429.ttl>

- Also check out our [TextileBase](https://reprexbase.eu/textilebase/) project — same model, but for 19th-century Latvian shirts and skirts

If your stack includes **messy location names, user-generated labels, non-English content, or legacy records** — maybe this can help.

And if you feel like you’ve seen this movie before… you have.

It’s **Data Sisyphus** all over again.

👉 <https://reprex.nl/post/2021-07-08-data-sisyphus/>

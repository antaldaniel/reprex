+++
title = "Crunchconf: Open Data, New Gold Without the Rush"
date = 2021-10-08T10:10:00  
lastmod = 2021-10-08T10:10:00  
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2021-10-08T19:10:00  
time_end = 2021-10-08T19:40:00  

authors = ["Daniel Antal, CFA"]

# Abstract and optional shortened version.
abstract = "Every year, the EU announces that billions and billions of data are now “open” again, but this is not gold. At least not in the form of nicely minted gold coins, but in gold dust and nuggets found in the muddy banks of chilly rivers. There is no rush for it, because panning out its value requires a lot of hours of hard work. Our goal is to automate this work to make open data usable at scale, even in trustworthy AI solutions."

# Name of event and optional event URL.
event = "CrunchConf 2021"
event_url = "https://crunchconf.com/schedule"

# Location of event
location = "Online"

# Is this a selected talk? (true/false)
selected = true
# Tags (optional).
tags = ["Open data"]

# Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "Crunchconf_2021"

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Does the content use math formatting?
math = false

# Featured image
[image]
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++

Every year, the EU announces that billions and billions of data are now “open” again, but this is not gold. At least not in the form of nicely minted gold coins, but in gold dust and nuggets found in the muddy banks of chilly rivers. There is no rush for it, because panning out its value requires a lot of hours of hard work. Our goal is to automate this work to make open data usable at scale, even in trustworthy AI solutions.

## Summary 

In his presentation, Daniel compared the current state of open data (including governmental open data and scientific open data) to a thrift store.  You can often find bargains, or historical data that would be impossible to source from data vendors, but on a strictly as-is basis, without a catalogue, service, or guarantee. Therefore, working with open data requires a careful reprocessing, validation, and in many cases, frequent re-validation. Open data is often over-estimated: it is never a finished product, often it cannot even be downloaded, therefore it requires further investment to make it valuable. However, because most open data arrives from the governmental sector, you can tap into information sources where no market alternative exists.  Open data in some cases may be a cheaper substitute to market vendors, but often it is an exclusive source of information that do not have any market vendors.

<td style="text-align: center;">{{< figure src="/img/blogposts_2021/Sisyphus_Bodleian_Library.png" caption="Sisyphus was punished by being forced to roll an immense boulder up a hill only for it to roll down every time it neared the top, repeating this action for eternity.  This is the price that project managers and analysts pay for the inadequate documentation of their data assets." numbered="false" >}}</td>

- The practices related to the exploitation of open data are not only relevant in an open data context: these are good data ingestion and procurement practices for *any* third party data, and in large organizations, for any cross-departmental data. (See the blogpost: [The Data Sisyphus](https://dataandlyrics.com/post/2021-07-08-data-sisyphus/).)

- Case Study:  [Belgian Drought/Flood Risk Awareness, Financial Capacity & Hydrology](https://greendeal.dataobservatory.eu/post/2021-04-23-belgium-flood-insurance/) a complex integration of various open data sources.

In the second part of the presentation, Daniel talked about our modern data observatory concept.  We have reviewed about 80 functioning and already defunct international data collection programs.  Data observatories, like Copernicus’ Observatory, are permanent infrastructure to record various domain-specific data, such as alternative fuel information, information on homelessness, or on the European music business.  In our assessment, most of the EU, OECD, UNESCO recognized or endorsed observatories use obsolete technology and do not rely on the new achievements of data science. Reprex, our start-up offers an open source, open data based alternative solution to build largely automated data observatories.  We believe that human judgement is needed in data curation, but processing, documentation and validation is best done by computers.

- Case Study: [Reprocessing geographical information with administrative boundary changes](https://greendeal.dataobservatory.eu/post/2021-03-06-regions-climate/)

At last, he presented a few development directions with our open-source software, mentioning our work withing the rOpenGov community. This part of the presentation was originally meant to open the way for a half-day open data workshop, but due to the current pandemic situation, the physical part of the conference and the workshops were not held.

The presentation largely included the topics of our Data & Lyrics blogpost: [Open Data---The New Gold Without the Rush](https://greendeal.dataobservatory.eu/post/2021-06-18-gold-without-rush/)


## Presentation Slides

See the presentation slides [here](https://reprex.nl/slides/crunchconf_2021/#/).

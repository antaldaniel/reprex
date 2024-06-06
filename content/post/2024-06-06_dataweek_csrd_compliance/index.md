---
title: "Dataweek²⁴: Data-driven Compliance with the Corporate Social Responsibility Directive"
subtitle: "Reprex's solution with data sharing spaces facilitates data exchange in the supply change"

categories:

summary: Reprex is building a data sharing system, Reprexbase, which is built around Wikibase as a knowledge broker system. We design it in a way that it help compliance with ESG reporting and the new European Sustainability Reporting Standards.

# Schedule page publish date (NOT talk date).
publishDate: '2024-06-06T16:22:00+01:00'

authors: ["daniel_antal"]
tags: ["Dataweek", "Sustainability", "Dataspace", "ESG", "Reprexbase"]

# Is this a featured talk? (true/false)
featured: true

image:
  caption: ''
  focal_point: Center
  preview_only: true

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

links:
- icon: x
  icon_pack: fab
  name: "@dataandlyrics"
  url: https://twitter.com/dataandlyrics
- icon: m
  icon_pack: fas
  name: Dataweek²⁴ Website
  url: https://data-week.eu/2024-edition-part-2/programme/
- icon: linkedin
  icon_pack: fab
  name: Reprex
  url: https://www.linkedin.com/company/68855596/

# Markdown Slides (optional).
slides: 20240605_D_Antal_CSRD_Automated_Compliance
---
<td style="text-align: center;">{{< figure src="slides/20240605_D_Antal_CSRD_Automated_Compliance/20240606_D_Antal_Dataweek_CSRD_Compliance_2.png" caption="[All slides](/slides/20240605_d_antal_csrd_automated_compliance/)" numbered="false" >}}</td>

_This is a lightly edited version of the presentation at the Data-driven and Automated Compliance section of Dataweek²⁴_  [Event page](/event/2024-06-05_dataweek_leuven/).

It has often been said that ESG reporting is a data problem.  If you want to fulfil the new requirements set by the Corporate Social Responsibility Directive, which is a legal act that changes European laws on financial accounting and its audit or assurance, you will encounter a very serious data linking and integration problem.  If you have such sustainability bookkeeping, you must be able to factually link your financial accounts to your environmental and social accounts. In simple terms, if you expense the cost of 1 MW of electricity, then you cannot calculate the footprint of 0.98 MW in your sustainability report.

<td style="text-align: center;">{{< figure src="slides/20240605_D_Antal_CSRD_Automated_Compliance/20240605_D_Antal_CSRD_Automated_Compliance_3.png" caption="[All slides](/slides/20240605_d_antal_csrd_automated_compliance/)" numbered="false" >}}</td>


ESG introduces two related challenges, which are best addressed by explicit knowledge bases, enterprise graphs connected to open knowledge graphs, and data sharing spaces.

-  [x]        The company must be able to collect data and report on other companies and things that happen outside of the boundaries of the company or company group. Such a practice had been in place in some heavily regulated industries; for example, the food industry had to bear a qualified responsibility over the entire food supply chain or the nuclear industry for the lifecycle of the fissile fuels.

- [x]         The company must also be able to curate trustworthy data about entirely new domains: data about the natural or ecological environment, such as data on biodiversity, recycling, water; and data about the social environment, for example, indicators about affected communities, workers in the supply chain or end users.

Joining a data sharing space is a good solution because the new data requirements are not one-time data upgrades but require a permanent data connection with the ecological and social environment. A company and its ERP system or its key performance management users cannot import new data, such as metadata of the EU Taxonomy regulation, and call it a day. Data curation must be an ongoing activity.

<td style="text-align: center;">{{< figure src="slides/20240605_D_Antal_CSRD_Automated_Compliance/20240605_D_Antal_CSRD_Automated_Compliance_7.png" caption="[All slides](/slides/20240605_d_antal_csrd_automated_compliance/)" numbered="false" >}}</td>

Most companies import relatively little data regularly, and therefore, they have little experience in data curation, i.e., the art of organising, annotating, and integrating data collected from various sources in a way that is presentable in the form of indicators or can be reused later.  Perhaps their bookkeeping needs to import foreign exchange rates regularly if they export or import in their activities.  Data curation will become an ongoing activity if they start to monitor and measure the environmental and social environment impacts of their actions.

So, if we agree that joining a data sharing space, i.e., an organisation that has pre-agreed terms and conditions on sharing and exchanging data, with pre-agreed terminology or vocabulary (“semantics”) and technology, the question is, what kind of data sharing organisation is the most appropriate?

The CSRD Directive has industry-agnostic elements, which must be fulfilled in every company, and industry-specific elements, which are being developed as we speak. For example, we work mainly with music and film production, both of which belong to the Media and Entertainment Group, which must apply the same industry-specific variations of the European Sustainability Development Standards. We think that the best is to create industry-specific data sharing spaces, such as the famous Data 4.0 for manufacturing, but allow them to be federated and to exploit further synergies: there are plenty of financial, economic, social or environmental data that are used by other existing data sharing spaces and it is not necessary to curate and produce them in, for example, a music or film-production oriented data sharing space.

Are for-profit and social enterprises technically ready to join data-sharing spaces?  Not without help. While some large corporations have explicit knowledge bases and enterprise graphs, most smaller European enterprises do not necessarily have a distinct IT function. It is a simple relational database with a fixed schema if they manage databases. Bringing them on board requires simple systems and assistance.

<td style="text-align: center;">{{< figure src="slides/20240605_D_Antal_CSRD_Automated_Compliance/20240605_D_Antal_CSRD_Automated_Compliance_6.png" caption="[All slides](/slides/20240605_d_antal_csrd_automated_compliance/)" numbered="false" >}}</td>

Reprex is building a data sharing system, Reprexbase, which is built around Wikibase as a knowledge broker system. Wikibase is the open-source software that hosts Wikidata, the largest open knowledge graph in the world. We extend it with various ETL modules and an ecosystem of peer-reviewed statistical libraries to create scientifically correct impact indicators and benchmarks.  These extensions are necessary not only because most enterprises are not familiar with working with linked data or graphs but also because Companies are usually familiar with creating financial indicators (for SMEs, simple accounting indicators, larger enterprises with a controlling function, and more complex indicators) but not with the creation of non-financial statistical indicators. The CSRD directive calls for reporting more than 200 indicators over five environmental and four social matter groups, which is more than a company would have on a balanced scorecard. Reliably producing so many indicators is no small feat.

Large and public companies are directly responsible for CSRD reporting, i.e., integrating financial, environmental and social accounting. They need to improve their bookkeeping or ERP systems because often they do not even organise into a database much of the contents of the current invoices (physical quantities, units), which would allow them to create the factual basis between energy cost, energy use and energy footprint, for example. However, they must ask their suppliers for further environmental and social data. Without readily applicable Digital Product Passports, this is a considerable cost, estimated at around 1500 euros per supplier. If you are a festival organiser or a film producer with hundreds of suppliers, this will quickly pay for a simple data sharing space; if you do it with a cluster in your industry, the costs can be significantly reduced. 

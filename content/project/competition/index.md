---
title: Competition
summary: Mapping data between antitrust and economic activity markets
tags:
- competition
- competitiveness
- innovation
date: "2021-05-16T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: "[Matt Ridley](https://unsplash.com/photos/mMgHe5h0_U4)"
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/EconDataObs
- icon: github
  icon_pack: fab
  link: https://github.com/dataobservatory-eu
- icon: linkedin
  icon_pack: fab
  link: https://www.linkedin.com/company/78562153
- icon: globe
  icon_pack: fas
  link: https://dataobservatory.eu/#observatories

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

`Big data` and `AI` create new inequalities in the world. `Data monopolization` can potentially lead to product and service market monopolization, too.  We are designing new policy indicators that can help competition policy practitioners and researchers to measure and understand these trends.

- We are planning to programatically access the merger database of the European Commission's [Merger Cases](https://ec.europa.eu/competition/elojade/isef/index.cfm?clear=1&policy_area_id=2), which we believe to fall under the scope of the Open Data Directive.
- We would like to connect to the [EUIPO](https://euipo.europa.eu/ohimportal/en/databases) databases to create indicators of potential killer acquisitions - acquisitions by large companies that may thwart innovation by buying up and killing start-up companiees to take hold of competitive patents.

## Mapping antitrust markets {#antitrust-market-mapping}

Most market-based analysis uses standardised industry classifications such as the NACE system in the European Union. Whilst these systems are useful to have a standardised view of the component parts of the economy, these markets are frequently very different from product markets that are defined by demand and supply conditions (literature refers to this as antitrust markets). One of the cornerstones of our Data Observatory is automating the construction and updating of a system of antitrust markets. This can be done from available antitrust market decisions. For example Affeldt et al. (2021) manually identified 20,000 product/geographic antitrust markets affected by over 2,000 mergers from DG COMP merger decisions. Automating this process will create a continuously updated source of market definitions that can directly benefit a number of users, such as small businesses caught up in costly merger litigations, academics, policy organisations. This new market classification system could also contribute to the topical debate on increasing market concentration and markups (where most current analysis uses standard industry classification systems).
Under the umbrella of our Antitrust Market Classification (AMC) and under a standard industry classification (NACE) we will create three company-level tracker datasets: 

{{< figure src="/img/blogposts_2021/nace_antitrust_map.png" caption="Computational Antitrust Project Plan" numbered="true" >}}

## Merger tracker {#merger-tracker}

We compile a merger database from constructing our antitrust markets. This will be complimented by continuously monitoring markets for M&A transactions that are below the radar of DG COMP. As a first step, we will only have this option for selected markets, until we develop a tool to systematically collect this data on a wider scope. Tracking mergers in both NACE and AMC markets helps trace how concentration evolves over time. Moreover, this is a key building block to our Competition and Innovation Data Observatory.

## Innovation tracker {#innovation-tracker}

Part of this project is to link the firms that appear in our antitrust market definitions to their historical and current innovation data. For this we will draw from patent data APIs, such as that of the European Patent Office. 
This would enable the tracking of how innovation develops as market become more/less concentrated. This is important for several reasons. First of all, innovation is an important component of economic productivity, and therefore our tracker will provide vital information to competition authorities and sectoral regulators. Second, there are increasingly vocal concerns about the innovation impact of acquisitions between companies that are either on separate antitrust markets, or include an acquired business that is below the size threshold of antitrust scrutiny (these are frequently referred to as killer acquisitions in the literature). One side of the ongoing debate argues that these acquisitions can hamper innovation, whereas other claim the opposite (it is the prospect of these acquisitions that drives innovation in many small start-up businesses). As such, our tool will be a key indicator of how healthy the environment for innovation for small businesses is.

## Ownership tracker
Finally, we will construct and ownership tracker from the shareholder reports of listed companies (from the set of companies identified in our market definition process). Once again, this is key information for gauging how healthy competition is in European markets. It has been repeatedly highlighted that overlaps in the ownership structure (in institutional investors) of the largest businesses can hinder competition. Mapping the ownership structure of European listed companies means that not only we are aware of market concentration concerns in antitrust markets, but also concerns when overlap across corporate governance structures is considered.

Photo credit: [Matt Ridley](https://unsplash.com/photos/mMgHe5h0_U4), [Unplash licence](https://unsplash.com/license). 

+++
title = "Demo Slovak Music Database"

date = 2020-12-17T17:10:00+02:00
lastmod = 2020-12-17T17:10:00+02:00
draft = false

authors = ["Daniel Antal"]

tags = ["listen-local", "Slovakia", "justice", "algorithms", "big-data", 
"recommendations", "local-content-requirements"]

summary = "We needed a database of Slovak music to show how that national repertoire is seen by media and streaming platforms, how can we give it greater visibility in radio and streaming platforms, and what are the specific problems why certain artists and music is almost invisible."

projects = ["listen-local"]

# Featured image
[image]
  # Caption (optional)
  caption = "Our Demo Application"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"

  # Show image only in page previews?
  preview_only = true

+++

We are finalizing our first local recommendation system, Listen Local Slovakia, and the accompanying Demo Slovak Music Database. Our aim is 

- Show how the Slovak repertoire is seen by media and streaming platforms
- What are the possibilities to give greater visibility to the Slovak repertoire in radio and streaming platforms
- What are the specific problems why certain artists and music is almost invisible. 

In the next year, we would like to create a modern, comprehensive national music database that serves music promotion in radio, streaming, live music within Slovakia and abroad.

To train our locally relevant, [alternative recommendation system](/post/2020-12-15-alternative-recommendations/), we filled the Demo Slovak Music Database from two sources. In the `opt-in` process we asked artists to participate in Listen Local, and we selected those artists who opted in from Slovakia, or whose language is Slovak. In the `write-in` process we collected publicly available data from other artists that our musicology team considered to be Slovak, mainly on the basis of their language use, residence, and other public biographical information. The following artists form the basis of our experiment. (_If you want to be excluded from the write-in list, [write to us](https://dataandlyrics.com/#contact), or you want to be included, please, fill out [this form](https://www.surveymonkey.com/r/ll_collector_2020)._)

<iframe seamless ="" name="iframe" src="https://dataandlyrics.com/htmlwidgets/sk_artist_table.html" width="1000" height="1050" ></iframe>

[Click here to view the table on a separate page](/htmlwidgets/sk_artist_table.html)

Modern recommendation systems usually rely on data provided by artists or their representatives, data on who and how is listening to their music, and what music is listened to by the audience of the artists, and certain musicological features of the music.  Usually they collect data from various data sources, but these data sources are mainly English language sources. 

The problem with these recommendation systems is that they do not help music discovery, and make starting new acts very difficult. Recommendation systems tend to help already established artists, and artists whose work is well described in the English language.

Our alternative recommendation system is a utility-based system that gives a user-defined priority to artists released in Slovakia, or artists identified as Slovak, or both. The system can be extended for lyrics language priorities, too.
Currently, our app is demonstration to provide a more comprehensive database-driven tool that can support various music discovery, recommendation or music export tools. Our Feasibility Study to build such tools and our Demo App is currently under consultation with Slovak stakeholders.  

*[Listen Local](https://dataandlyrics.com/tag/listen-local/) is developing transparent algorithms and open source solutions to find new audiences for independent music. We want to correct the injustice and inherent bias of market leading big data algorithms. If you want* `your music and audience` *to be analysed in Listen Local, fill* [this form](https://www.surveymonkey.com/r/ll_collector_2020) *in. We will include you in our demo application for local music recommendations and our analysis to be revealed in December.*

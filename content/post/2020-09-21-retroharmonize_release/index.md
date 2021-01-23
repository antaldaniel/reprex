+++
title = "Reproducible Survey Harmonization: retroharmonize Is Released"

date = 2020-09-21T11:31:39
lastmod = 2020-09-21T11:31:39
draft = false

authors = ["Daniel Antal, CFA"]

tags = ["R", "open-data", "reproducible", "surveys", "open-source"]

summary = "Our ex post survey harmonization package retroharmonize passed all automated tests and peer-reviews and was released today on CRAN."

# Featured image
[image]
  # Caption (optional)
  caption = "Harmonized results from Afrobarometer"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "TopLeft"

  # Show image only in page previews?
  preview_only = false

+++

Our original intention was to make surveying more accessible for music and creative industry partners, by relying more on already existing survey data, and better designing complementary, smaller surveys, becasue surveying, opinion polling is becoming increasingly expensive in the develop world.  People are less and less likely to sit down for an interview in their houses.  We have tried to harmonize our custom surveys, particuarly with Kantar in Hungary and Focus in Slovakia with exisiting EU projects.  But we ended up making a part of international survey harmonization across countries and throughout years easier to automate.

![Harmonized results from Afrobarometer](/img/packages/ab_plot1.png)

Surveys are like sensors for natural sciences and industrial production. They are essential for almost any social and economic statistical indicator, for calculating the inflation, parts of the GDP, participation in education programs.  Making surveys easier to harmonize and exploit more already existing survey data can bring down research cost, and can increase research value at the same time. (See our earlier blog post [Increase The Value Of Market Research With Open Data And Survey Harmonization](https://dataobservatory.eu/post/2020-07-10-retroharmonize/).)

So, if you are an R user, you can use `install.packages(“retroharmonize”)` to get the released 0.1.13 version and make tutorials with real Eurobarometer or Afrobarometer microdata.  With `devtools::install_github("antaldaniel/retroharmonize")` you can already install the current development version 0.1.14, which handles perl-like regex, which will be necessary for our next tutorial in the making for [Arab Barometer](https://www.arabbarometer.org/). 

**Related**:

* [retroharmonize package website](https://retroharmonize.dataobservatory.eu/)

* [retroharmonize on github](https://github.com/antaldaniel/retroharmonize/)



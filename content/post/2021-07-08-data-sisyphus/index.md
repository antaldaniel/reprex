---
title:  "The Data Sisyphus"
subtitle:  ""
date:  2021-07-08T09:00:00
lastmod:  2021-07-08T09:00:00
draft:  false

authors:  ["daniel_antal"]

tags:  ["metadata","data-as-service", "api"]

summary:  "Sisyphus was punished by being forced to roll an immense boulder up a hill only for it to roll down every time it neared the top, repeating this action for eternity.  When was a file downloaded from the internet?  What happened with it sense?  Are their updates? Did the bibliographical reference was made for quotations?  Missing values imputed?  Currency translated? Who knows about it – who created a dataset, who contributed to it?  Which is the final, checked, approved by a senior manager?"

projects:  ""

# Featured image
image: 
  # Caption (optional)
  caption:  "Sisyphus lying under grindstone Bodleian Library, University of Oxford. [Wikimedia](https://commons.wikimedia.org/wiki/Category:Sisyphus#/media/File:Midevil_sysiphus.jpeg)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point:  "Center"

  # Show image only in page previews?
  preview_only:  true

---
<td style="text-align: center;">{{< figure src="/img/blogposts_2021/Sisyphus_Bodleian_Library.png" caption="Sisyphus was punished by being forced to roll an immense boulder up a hill only for it to roll down every time it neared the top, repeating this action for eternity.  This is the price that project managers and analysts pay for the inadequate documentation of their data assets." numbered="false" >}}</td>

*When was a file downloaded from the internet?  What happened with it sense?  Are their updates? Did the bibliographical reference was made for quotations?  Missing values imputed?  Currency translated? Who knows about it – who created a dataset, who contributed to it?  Which is an intermediate format of a spreadsheet file, and which is the final, checked, approved by a senior manager?*

Big data creates inequality and injustice. On aspect of this inequality is the cost of data processing and documentation – a greatly underestimated, and usually not reported cost item. In small organizations, where there are no separate data science and data engineering roles, data is usually supposed to be processed and documented by (junior) analysts or researchers.  This a very important source of the gap between Big Tech and them: the data usually ends up very expensive, ill-formatted, not readable by computers that use machine learning and AI. Usually the documentation steps are completely omitted.

> “Data is potential information, analogous to potential energy: work is required to release it.” -- Jeffrey Pomerantz

Metadata, which is information about the history of the data, and information how it can be technically and legally reused, has a hidden cost. Cheap or low-quality external data comes with poor or no metadata, and small organizations lack the resources to add high-quality metadata to their datasets. However, this only perpetuates the problem.

## The hidden cost item behind the unbillable hours {#metadata-unbillable-hours}

As we have shown with our research partners, such metadata problems are not unique to data analysis.  Independent artists and small labels are suffering on music or book sales platforms, because their copyrighted content is not well documented.  If you automatically document tens of thousands of songs or datasets, the documentation cost is very small per item. If you, do it manually, the cost may be higher than the expected revenue from the song, or the total cost of the dataset itself. (See our research consortiums' preprint paper: [Ensuring the Visibility and Accessibility of European Creative Content on the World Market: The Need for Copyright Data Improvement in the Light of New Technologies](https://dataandlyrics.com/publication/european_visibilitiy_2021/))

In the short run, small consultancies, NGOs, or as a matter of fact, musicians, seem to logically give up on high-quality documentation and logging.  In the long run, this has two devastating consequences: computers, such as machine learning algorithms cannot read their documents, data, songs.  And as memory fades, the ill-documented resources need to be re-created, re-checked, reformatted.  Often, they are even hard to find on your internal server or laptop archive.

Metadata is a hidden destroyer of the competitiveness of corporate or academic research, or independent content management.   It never quoted on external data vendor invoices, it is not planned as a cost item, because metadata, the description of a dataset, a document, a presentation, or song, is meaningless without the resource that it describes. You never buy metadata.  But if your dataset comes without proper metadata documentation, you are bound, like Sisyphus, to search for it, to re-arrange it, to check its currency units, its digits, its formatting.  Data analysts are reported to spend about 80% of their working hours on data processing and not data analysis -- partly, because data processing is a very laborious task that can be done by computers at a scale far cheaper, and partly because they do not know if the person who sat before them at the same desk has already performed these tasks, or if the person responsible for quality control checked for errors.

<td style="text-align: center;">{{< figure src="/img/gems/Uncut-diamond_Edit.jpg" caption="Uncut diamonds need to be cut, polished, and you have to make sure that they come from a legal source. Data is similar: it needs to be tidied up, checked and documented before use. Photo: Dave Fischer." numbered="false" >}}</td>

Undocumented data is hardly informative – it may be a page in a book, a file in an obsolete file format on a governmental server, an Excel sheet that you do not remember to have checked for updates.  Most data are useless, because we do not know how it can inform us, or we do not know if we can trust it.  The processing can be a daunting task, not to mention the most boring and often neglected documentation duties after the dataset is final and pronounced error-free by the person in charge of quality control. 

## Our observatory automatically processes and documents the data {#observatory-metadata-services}

The good news about documentation and data validation costs is that they can be shared.  If many users need GDP/capita data from all over the world in euros, then it is enough if only one entity, a data observatory, collects all GDP and population data expresed in dollars, korunas, and euros, and makes sure that the latest data is correctly translated to euros, and then correctly divided by the latest population figures. These task are error-prone,and should not be repeaeted by every data journalist, NGO employee, PhD student or junior analyst.  This is one of the services of our data observatory.

- [x] The tidy data format means that the data has a uniform and clear data structure and semantics, therefore it can be automatically validated for many common errors and can be automatically documented by either our software or any other professional data science application. It is not as strict as the schema for a relational database, but it is strict enough to make, among other things, importing into a database easy.

- [x] The descriptive metadata contains information on how to find the data, access the data, join it with other data (interoperability) and use it, and reuse it, even years from now. Among others, it contains file format information and intellectual property rights information.

- [x] The processing metadata makes the data usable in strictly regulated professional environments, such as in public administration, law firms, investment consultancies, or in scientific research. We give you the entire processing history of the data, which makes peer-review or external audit much easier and cheaper.

- [x] The authoritative copy is held at an independent repository, it has a globally unique identifier that protects you from accidental data loss, mixing up with unfinished an untested version.

<td style="text-align: center;">{{< figure src="/img/gems/Diamond_Polisher.jpg" caption="Cutting the dataset to a format with clear semantics and documenting it with the FAIR metadata concep exponentially increases the value of data. It can be publisehd or sold at a premium. Photo: [Andere Andre](https://commons.wikimedia.org/w/index.php?curid=4770037)." numbered="false" >}}</td>

While humans are much better at analysing the information and human agency is required for trustworthy AI, computers are much better at processing and documenting data.  We apply to important concepts to our data service: we always process the data to the tidy format, we create an authoritative copy, and we always automatically add descriptive and processing metadata.

## The value of metadata {#value-of-metadata}

Metadata is often more valuable and more costly to make than the data itself, yet it remains an elusive concept for senior or financial management.  Metadata is information about how to correctly use the data and has no value without the data itself.  Data acquisition, such as buying from a data vendor, or paying an opinion polling company, or external data consultants appears among the material costs, but metadata is never sold alone, and you do not see its cost.  

In most cases, the reason why [there is no gold rush for open data](https://dataandlyrics.com/post/2021-06-18-gold-without-rush/) is that fact that while the EU member states release billions of euros' worth data for free, or at very low cost, annually, it comes without proper metadata. 

<td style="text-align: center;">{{< figure src="/img/gems/edgar-soto-gb0BZGae1Nk-unsplash.jpg" caption="[Data-as-Service](/services/data-as-service/)</br></br>Reusable, legal, easy-to-import, interoperable, always fresh data in tidy formats with a modern API. Photo: [Edgar Soto](https://unsplash.com/photos/gb0BZGae1Nk)." numbered="false" >}}</td>


If the data source is cheap or has a low quality, you do not even get it.  If you do not have it, it will show up as a human resource cost in research (when your analysist or junior researcher are spending countless hours to find out the missing metadata information on the correct use of the data) or in sales costs (when you try to reuse a research, consulting or legal product and you have comb through your archive and retest elements again and again.)

- [x] The data, together with the descriptive and administrative metadata, and links to the use license and the authoritative copy can be found in our API. Try it out!
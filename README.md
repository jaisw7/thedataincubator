# The data incubator entry project

Entry project for [thedataincubator](http://thedataincubator.com) fellowship. I got selected as a scholar.   

Here's what I found out by scrapping libgen database (over 70 million entries)

* How has the open-access publishing grown over the years? 
    * Does it improve the quality of research? How well does open-access translate to the quantity of research? 
    * Can we devise a normalized research quality metric based on the information?
    * To what extend does the open-access benefit the community, in particular, the developing nations? 
    
In an attempt to make federally funded research open, initiated by scientists and researchers, Library Genesis is a database for articles and books on various topics, which allows free access to content that is otherwise paywalled or not digitized elsewhere. 
> A sister site, Sci-Hub's, founder *Alexandra Elbakyan* was listed by *Nature*, in 2016, among the **top ten people that mattered in science**. US ranks *second* in the terms of web-traffic on Sci-Hub and related websites. 
> As per wikipedia: Elbakyan's Sci-Hub is widely used in both developed and developing countries, serving over 200,000 requests per day as of February 2016. 
> * How has the inception of Sci-Hub affected the quality/quantity of research in developing nations? Do more authors go on to write high quality papers in their respective fields? 
> * Has the number of papers cited per paper increased (with access to large number of papers and therefore more information)? 
> * Does their sphere of influence increase? Do they get more post-doctoral offers abroad? (This can be partially answered by looking at the collaboration graph of a researcher)
    
In this work, we shall restrict our attention to academic papers. Our study shall be based on ***database record*** of academic papers, ***not*** the actual academic papers themselves. The database, publicly available at http://booksdescr.org/dbdumps/scimag, contains over 70 million records of academic papers. It includes information of paper titles, author list, doi, etc. which in turn can be used to query citation information, abstract, etc. from Google Scholar, Pubmed, Researchgate, etc. The important point is: ***the database is relatively unanalyzed, and LibGen is perhaps the biggest such record of academic papers!*** The databse is incredibly information rich, and can be utilized to reveal insights into publishing.

* How does the paper quality of a researcher changes over time in various fields? For example: It is widely believed in Mathematics that ground-breaking contribution are from researchers below 30-35 years of age. How does that vary in other fields, by country of origin, by institution, etc? The intention of this study shall be to provide answers backed by analysis on actual data.

> Important Note
>* Our study shall be based on ***database record*** of academic papers, ***not*** the actual academic papers themselves. LibGen has been the subject of various formal academic studies. Few of them are listed below:
>    * Karaganis, Joe. *Shadow libraries: access to knowledge in global higher education*. MIT Press, 2018.
>    * Cabanac, Guillaume. *Bibliogifts in LibGen? A study of a text‐sharing platform driven by biblioleaks and crowdsourcing.* Journal of the Association for Information Science and Technology 67, no. 4 (2016): 874-884.
    
Data presentation: 
* The intention will be to generate an interactive insightful tool on academic publishing (see for example: Hans Rosling's https://www.gapminder.org/tools on socio-economic growth across the globe over years).

Tools:
* Python: Apache-Spark's ML on large datasets, MySQL, NetworkX, etc; Javascript: d3js

------

##### Most frequent author name in academia (Male):
![Most frequent author names (Male)](https://raw.githubusercontent.com/jaisw7/thedataincubator/master/academia-most-frequent-author-name.png)

##### Most frequent author name in academia (Female):
![Most frequent author names (Female)](https://raw.githubusercontent.com/jaisw7/thedataincubator/master/academia-most-frequent-names-female-scientists.png)

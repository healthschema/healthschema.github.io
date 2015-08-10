---
layout: post
title: Quantitative Analysis of Structured Data on the Web
---


References:

*Deployment of RDFa, Microdata, and Microformats on the Web – A Quantitative Analysis*
Christian Bizer, Kai Eckert, Robert Meusel, Hannes Mühleisen ,Michael Schuhmacher, and Johanna Völker
[paper](http://dws.informatik.uni-mannheim.de/fileadmin/lehrstuehle/ki/pub/Bizer-etal-DeploymentRDFaMicrodataMicroformats-ISWC-InUse-2013.pdf)


Abstract.
More and more websites embed structured data describing for instance
products, reviews, blog posts, people, organizations, events, and cooking recipes
into their HTML pages using markup standards such as Microformats, Microdata
and RDFa. This development has accelerated in the last two years as major Web
companies, such as Google, Facebook, Yahoo!, and Microsoft, have started to
use the embedded data within their applications. In this paper, we analyze the
adoption of RDFa, Microdata, and Microformats across the Web. Our study is
based on a large public Web crawl dating from early 2012 and consisting of 3
billion HTML pages which originate from over 40 million websites. The analysis
reveals the deployment of the different markup standards, the main topical areas
of the published data as well as the different vocabularies that are used within each
topical area to represent data. What distinguishes our work from earlier studies,
published by the large Web companies, is that the analyzed crawl as well as the
extracted data are publicly available. This allows our findings to be verified and to
be used as starting points for further domain-specific investigations as well as for
focused information extraction endeavors.

Links
[microformats.org](http://microformats.org)
[commoncrawl.org](http://commoncrawl.org)


Notable Quote:

Deployment by Popularity of Website: [Alexa Internet Inc.](http://www.alexa.com/) maintains a list of the
most frequently visited websites. In order to find out how many of the most popular
websites provide structured data, we analyzed the deployment of RDFa, Microdata and
Microformats on websites that are in the Alexa list of the top 1  million websites. The 
results of our analysis are given in the four rightmost columns of Table 2 and show that
**the percentage of the Alexa-listed websites providing structured data (74.75% of the top
100 and 20.56% of the top 1  million) is significantly higher than the percentage of all
websites within the Common Crawl that contain structured data (5.64%).**

Table2: Coverage of the PLDs in the Alexa top 1  million list (AL) by the Common Crawl corpus
and percentage of these PLDs containing structured data.

First x in AL       |  PLDs in CC | # % AL |  % containing structured data | overall RDFa |  Microdata | Microformats
100     | 99        |  99.00 | 74.75    | 34.34   | 55.56   | 68.69
1k      | 963       |  96.30 | 62.62    | 40.08   |  31.67  | 46.11
10k     |  9,294    |  92.94 |  47.34   | 30.47   | 15.55   | 29.75
100k    |  85,058   |  85.01 |  31.94   | 16.46   |  7.20   | 20.07
1m      |  734,882  |  73.49 |  20.56   |  7.55   | 3.04    | 14.18



Takeaway message:
* There  is a strong correlation between publishing data in structured form and search engine ranking.
* If you want your web content to be discoverable, processable, and  index-able
(by the search engines) you better start use structured data markup!






*Heuristics for Fixing Common Errors in Deployed schema.org Microdata*
Robert Meusel and Heiko Paulheim
[paper](http://dws.informatik.uni-mannheim.de/fileadmin/lehrstuehle/ki/pub/MeuselPaulheim-HeuristicsForFixingCommonErrorsInDeployedSchemaOrgMicrodata-ESWC2015.pdf)


Abstract.
Being  promoted  by  major  search  engines  such  as  Google,
Yahoo!,  Bing,  and  Yandex,  Microdata  embedded  in  web  pages,  espe-
cially using schema.org, has become one of the most important markup
languages for the Web. However, deployed Microdata is most often not
free  from  errors,  which  limits  its  practical  use.  In  this  paper,  we  use
the WebDataCommons corpus of Microdata extracted from more than
250  million  web  pages  for  a  quantitative  analysis  of  common  mistakes
in  Microdata  provision.  Since  it  is  unrealistic  that data providers will
provide clean and correct data, we discuss a set of heuristics that can
be applied on the data consumer side to x many of those mistakes in a
post-processing step. We apply those heuristics to provide an improved
knowledge base constructed from the raw Microdata extraction.



Links:
[schema.org](http://schema.org)
[webdatacommons.org](http://webdatacommons.org/structureddata)
[commoncrawl.org](http://commoncrawl.org)


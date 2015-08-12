---
layout: post
title: The Structured Data Web
---

<p align="center">
  <img src="http://www.newyorker.com/wp-content/uploads/2012/05/Google-knowledge-graph.jpg" 
  width="300px" height="250px" />
</p>


### Welcome to the Structured Data Web
The Internet is evolving from a Web of Documents to a Web of Data, driving the next generation of smarter, data-driven web applications and providing much richer integration of data and services for and by end users of the web.

Today it is not enough to publish  unstructured text in web pages.  Web crawlers search engines, and web agents are capable now of understanding structured data.  Therefore, if you want your content to be discoverable, indexable, computable, reusable, or inter-linkable on the web - and to maximize its secondary use in general - you'll want to publish your content as structured data on the web.  Some more background on why and how follow.



***

#### The Structured Data Web: What? Why? How?
* [gettins started with structured data](http://googlewebmastercentral.blogspot.com/2013/05/getting-started-with-structured-data.html)
* [intro to structured data markup](http://webdesign.tutsplus.com/articles/an-introduction-to-structured-data-markup--webdesign-8577)
* [demystifying knowledge graphs](http://searchengineland.com/demystifying-knowledge-graph-201976)
* [key improvements in googles search algorithm](http://dejanseo.com.au/2012-brings-3-key-improvements-in-googles-algorithm/)
* [New Yorker: The Web Gets Smarter](http://www.newyorker.com/culture/culture-desk/the-web-gets-smarter)


***

#### Deployment of RDFa, Microdata, and Microformats on the Web – A Quantitative Analysis
Christian Bizer, Kai Eckert, Robert Meusel, Hannes Mühleisen ,Michael Schuhmacher, and Johanna Völker
[paper](http://dws.informatik.uni-mannheim.de/fileadmin/lehrstuehle/ki/pub/Bizer-etal-DeploymentRDFaMicrodataMicroformats-ISWC-InUse-2013.pdf)

Abstract:
More and more websites embed structured data describing for instance products, reviews, blog posts, people, organizations, events, and cooking recipes into their HTML pages using markup standards such as Microformats, Microdata and RDFa. This development has accelerated in the last two years as major Web companies, such as Google, Facebook, Yahoo!, and Microsoft, have started to use the embedded data within their applications. In this paper, we analyze the adoption of RDFa, Microdata, and Microformats across the Web. 

Our study is based on a large public Web crawl dating from early 2012 and consisting of 3 billion HTML pages which originate from over 40 million websites.  The analysis reveals the deployment of the different markup standards, the main topical areas of the published data as well as the different vocabularies that are used within each topical area to represent data. What distinguishes our work from earlier studies, published by the large Web companies, is that the analyzed crawl as well as the extracted data are publicly available. This allows our findings to be verified and to be used as starting points for further domain-specific investigations as well as for focused information extraction endeavors.

Key Findings:
Deployment by Popularity of Website: [Alexa Internet Inc.](http://www.alexa.com/) maintains a list of the most frequently visited websites. In order to find out how many of the most popular websites provide structured data, we analyzed the deployment of RDFa, Microdata and Microformats on websites that are in the Alexa list of the top 1  million websites. The results of our analysis (presented in the four rightmost columns of Table 2) show that the percentage of the top-listed websites providing structured data (74.75% of the top 100 and 20.56% of the top 1  million) is significantly higher than the percentage of all other (40 million) websites that contain structured data (5.64%).

Top Ranked Sites |  PLDs in CC | # % AL |  % containing structured data | overall RDFa |  Microdata | Microformats
100     | 99        |  99.00 | 74.75    | 34.34   | 55.56   | 68.69
1k      | 963       |  96.30 | 62.62    | 40.08   |  31.67  | 46.11
10k     |  9,294    |  92.94 |  47.34   | 30.47   | 15.55   | 29.75
100k    |  85,058   |  85.01 |  31.94   | 16.46   |  7.20   | 20.07
1m      |  734,882  |  73.49 |  20.56   |  7.55   | 3.04    | 14.18

Table 2: Coverage of the Primary Level Domains (PLDs) in the Alexa List (AL) of top 1  million sites based on the Common Crawl (CC) corpus and percentage of these PLDs containing structured data.


Links:
 * http://microformats.org
 * http://commoncrawl.org


***

#### Heuristics for Fixing Common Errors in Deployed schema.org Microdata
Robert Meusel and Heiko Paulheim
[paper](http://dws.informatik.uni-mannheim.de/fileadmin/lehrstuehle/ki/pub/MeuselPaulheim-HeuristicsForFixingCommonErrorsInDeployedSchemaOrgMicrodata-ESWC2015.pdf)


Abstract:
Being  promoted  by  major  search  engines  such  as  Google, Yahoo!,  Bing,  and  Yandex,  Microdata  embedded  in  web  pages,  especially using schema.org, has become one of the most important markup languages for the Web. However, deployed Microdata is most often not free  from  errors,  which  limits  its  practical  use.  In  this  paper,  we  use the WebDataCommons corpus of Microdata extracted from more than 250  million  web  pages  for  a  quantitative  analysis  of  common  mistakes in  Microdata  provision.  Since  it  is  unrealistic  that data providers will provide clean and correct data, we discuss a set of heuristics that can be applied on the data consumer side to x many of those mistakes in a post-processing step. We apply those heuristics to provide an improved knowledge base constructed from the raw Microdata extraction.


Links:
 * http://schema.org
 * http://webdatacommons.org/structureddata
 * http://commoncrawl.org








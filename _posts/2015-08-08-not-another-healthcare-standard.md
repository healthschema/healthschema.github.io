---
layout: post
title: Not Another Healthcare Standard, Please
---


The Healthcare Data Standards Industry
-----

**Health Data Standards is a Business, not a Solution**


<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/f9/Federal_Open_Market_Committee_Meeting.jpg" width="400px" height="300px" />
</p>


**What's Wrong with Healthcare Standards Today?**

**First**, healthcare data standards are *designed by committee* behind *closed doors* by insider-balloted "experts" (Academics,  self-promoted "Industry Czars", and non-practicing or non-health professionals) rather than by the millions of front-line users and consumers of health data. The process of creating standards is not based on empirical or scientific data regarding actual usage by doctors and patients (the kinds of information search engine companies have). It is simply not a closed-loop process.  As a result these standards bloat out of control with irrelevant complexity, catering to the long tail of special and academic interests, while neglecting basic needs of the masses. 

Health data standards development is a contact sport for and by the players, not armchair experts. For the these "experts" it is antithetical to streamline, shrink, and streamline any standard. Rather, they would expanding the standard with hair-splitting nuance of little practical value.  This assures their central role and job security for continued management of bloated, arcane standards.


**Second**, all health standards development organizations (SDO) have different agendas, goals, and procedures they need to support, not least of which is to monetize their special standard to assure organizational sustainability. This leads to a wide diversity of approaches and perspectives as to even create a standard.

**Third**, many of these organizations and standards have been in sustainment for over three decades.  In information science timescales, their standards are paleolithic, pre-dating the existence the vast, dynamic, real-time world-wide information network (called the Internet) as the primary distribution channel for data and information.  Information is not controlled by special people and organizations anymore. **Everyone has a voice** on the Internet now.

**Fourth**, each healthcare data standard is its own silo, with

* **different schedules** for release (irregular, weekly, monthly, quarterly, annually, and even decade-ly)
* **different formats** (some dating over 30 years old)
* **different vintage** (all have different ages and origins, and thus differing conceptual and technological approaches)
* **different licenses** (none of them freely usable or creative commmons)
* **different data models** (with different, incompatible, and proprietary tooling)
* **different paywalls** (preventing access without paying "membership dues" for codes or schemas, ranging from $200-1500/ per provider per year, or $ millions per year for site licenses per year)
* **different defintions** (both ambigous and conflicting)
* **different granularity** (guaranteeing that there will never be any straightforward or one-to-one mapping between any of the standards).

Differing granularity is one of the largest challenges because it requires laborious human expert curation of one-to-many, many-to-one, and many-to-many mappings. These are all highly subjective and error prone with no means of automation for consistency. In other words, this will be an **expensive, laborious, error-prone, repetitive human task - forever**.


**Fifth**, it is technically impossible to implement the current HIT standards in a consistent fashion across healthcare systems because not only are they inconsistent, but they are "flexible" (if a concept doesn't fit the slot, one may insert any  free text or code desired). This allows completely implementation-specific use of the standard depending on the perspectives of the customer. 

One example of "loose" standards this is the consolidated continuity of care document (CCDA), a currently promoted standard in the U.S.  While these documents may get a 100% 'pass' on the NIST validator (which only checks correctness of syntax), only 60-65% of the actual data content is correctly encoded, leading to a 30-35% loss of information.  (See examples of real EHR output on the [CCDA Scorecard](http://ccda-scorecard.smartplatforms.org/static/ccdaScorecard) ). Note that even a 1% data dropout (depending on the information loss - incomplete allergy list,  etc.) is enough to cause patient harm. 

**Sixth**,because these standards are so inconsistent with each other (preventing interoperable implementations), standards organizations are required to spend a large fraction of their time attempting to "align" themselves with each other. This self-reinforcing behaviour is percieved to strengthens their mutual value (by making them interdependent?), but in fact only complicates the situation, because their mappings are only partial, and only short-lived (until any one of the standards changes, which they have a habit of doing frequently). 

This self-perpetuating cycle of work for all standards organizations creates much work,  while making no actual forward progress. While there may be some inter-organization social bonding through infinite meetings and conferences in nice cities  -  the effect for end users of these standards is nil. The effort spent on this never-ending alignment (see "different granularity" and "inconsistency" above) *rather than consolidation and simplification*  is a classic example of [Parkinson's Law of Triviality](https://en.wikipedia.org/wiki/Parkinson%27s_law_of_triviality).

**It is the very persistence (or recycling) of legacy healthcare data standards that remain the fundamental problem for health data management.**  Health Information Technology (HIT) product vendors support this state of legacy HIT standards because it provides them top cover: "We use HIT standard XYZ... therefore we must be interoperable!" while remaining completely silo'd because every one of these standards is completely and utterly implementation-specific.  The HIT Systems Integrators and  Consultants support the status quo, since it provides them a never-ending and lucrative supply of complex, costly data integration contracts.

**There is nothing new in the current landscape of HIT standards.**  Only re-packaging of legacy standards at a superficial level, not unlike a plumber putting silver foil on clogged and leaking lead pipes and exlaiming "Look! A brand new shiny (data) plumbing architecture!". And after a few days the customer complains bitterly "but my (data) pipes are still leaking and clogged".

All the above begs the questions:
**1. Why do we have such a proliferation "healthare-data-is-special" standards in the first place?**

**2. Does this mean that healthcare data is categorically different from any other kind of data?**


Healthcare Data is Not Special
-----

<p align="center">
Fruit Cake <img src="http://www.ultrahd4kwallpaper.in/wp-content/uploads/2014/06/fruit-cake-hd-wallpaper-2.jpg" width="150px" height="125px" />

Furosemide <img src="https://d1hekt5vpuuw9b.cloudfront.net/assets/article/fe274ef18e93e75562dc05fe87b18316_are-you-taking-too-much-medicine-580x326_featuredImage.jpg" width="150px" height="125px" />
</p>


**Healthcare data is not special.**  It does not require special containers, formats, structures, or packaging. It is just data.   Health data must be available universally and freely to the people it ultimately belongs to -patients -  in a form they can consume with their normal Internet-enabled devices.  Don't be distracted by the naysayers who bring up distracting and completely orthogonal issues (what about security? etc.)  If we can do personal banking online securely, we can surely manage healthcare online securely.  Again, it's just data.

If we can represent ingredients for a recipe in structured form in machine-processable form unambiguously throughout the Internet (See [NYT article](http://open.blogs.nytimes.com/2015/04/09/extracting-structured-data-from-recipes-using-conditional-random-fields/?_r=0) and Google's [structured web recipes](https://developers.google.com/structured-data/rich-snippets/recipes) based on a fully [web processable schema](http://schema.org/Recipe) ), surely we can represent the ingredients of a medication.   Fruit cakes or Furosemide,  meat pies or Metoprolol,  and Chardonnay or Captopril -  it makes no difference.  Patients ultimately consume all of these well identified substances, which all have well defined ingredients.

The era of "healthcare-data-is-special" is over. 

**Welcome Back, Internet of (Health) Data.**





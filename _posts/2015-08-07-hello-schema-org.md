---
layout: post
title: HealthSchema.org Intro
---


Schema.org
-----

Everything on the Internet starts with Search. 

**Google Guess**. A Google search used to be based on satistical page ranks and keyword matches, and generated hundreds of thousands of results per search. Google had no understanding of what was  meant or the intent of the search, or how to provide meaningful recommendations. It was up to the individual to sift through the results. 

**Google Know**. To support next generation of smart, semantic search (where the meaning and intent of the search is understood) the Internet search giants (Google, Yahoo, Microsoft,...) adopted a single, common, open, and universally accessible schema ( [schema.org](http://schema.org/) )to provide clear, unambigous structure and definition for information on the Internet.  

Over a trillion web searches each year now leverage Schema.org's schema, providing exact, meaningful results for information requested.  In its role providing meaning to data on the web, Schema.org is the most likely the most linked data resource on the Internet.


Schema.org has [many schemas](http://schema.org/docs/schemas.html) for data, both general-purpose (demographics ...) and concrete (restaurant).   


But what about Healthcare data?


----
Health data remains locked behind the *tens of thousands of unique proprietary schemes* of each source health information system.   

What about interoperability standards? Doesn't that solve the problem?

First, healthcare data standards are designed by committees of experts behind closed doors ("the Wizards")  rather than by the millions of consumers of this data - doctors and patients. 

Second, each health data standards organization has different agendas, goals, and procedures they need to support, not least of which is to monetize their special standard to assure organizational sustainability.  

Third, many of these organizations have been in sustainment mode for over three decades.  In information science timescales, these organizations are dinsaurs, predating the existence and adoption of the Internet (and its vast, dynamic, real-time information network) as the primary distribution channel for information.  Information is not controlled by "special" people and organizations anymore.


Fourth, each healthcare data standard is its own silo, with

* different release schedules  (weekly, monthly, quarterly, annually, or once a decade)
* different and proprietary formats (dating over 25 years old)
* different and proprietary licenses (none of them freely usable or creative commmons)
* different and proprietary models
* different payment models
* different, ambigous and conflicting defintions.  

And not to mention, fundamentally different and incompatible schemes?

Health IT product vendors support this state of incoherent and inconsistent health IT standards because it provides them the top cover to keep their data silo'd, while giving lip service to "We use HIT standard XYZ... therefore we must be interoperable!".  The HIT system vendors, Systems Integrators, and  Consultants also fully support the status quo, since it provides a never-ending supply of complex data integration contracts. 


**The state of healthcare data standards **is** the problem. **

This begs the question: Is healthcare data categorically different from any other kind of data?




HealthSchema.org
-----

Heath data should be simple. It needs designed for use by normal people, like patients. 

**Healthcare data is not special.**  It does not require special containers and formats.  If we can represent a recipe structure on the Internet, we can also  represent a medication list.

On healthschema.org, we think health data shoud be first class citizen on the free. open, world-wide information infrastructure that we call the Internet.





Stay tuned...
-----



configure:
git config --local --list
git config user.name "userName"
git config user.email "userEmail"

update:
git add 2015-08-07-hello-schema-org.md
git commit -m "intro schema.org update"
git push


#Github Markdown:

* [mastering markdown](https://guides.github.com/features/mastering-markdown/)
* [writing on github](https://help.github.com/articles/writing-on-github/)



Headers:
# This is an <h1> tag
## This is an <h2> tag
###### This is an <h6> tag


Emphasis:
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also be bold__

*You **can** combine them*



#Headings

Double-underlined heading
======

Single-underlined heading
------




#Emphasis
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~





#Lists
1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list. 
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses




#Links
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com


#Images
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"



#Code and Syntax highlighting
Inline `code` has `back-ticks around` it.


Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```



#Tables
Tables aren't part of the core Markdown spec, but they are part of GFM and Markdown Here supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3



#Blockquotes
> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy


#Inline HTML
You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>


#Horizontal Rule
Three or more...

---

Hyphens

***

Asterisks

___

Underscores


#Line Breaks
My basic recommendation for learning how line breaks work is to experiment and discover -- hit <Enter> once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend.

Here are some things to try out:

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *sam


#YouTube videos

They can't be added directly but you can add an image with a link to the video like this:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)

Referencing a bug by #bugID in your git commit links it to the slip. For example #1




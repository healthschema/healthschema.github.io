---
layout: post
title: Schema.org Introduction
---


Schema.org
-----
The Internet search giants (Google, Bing, Yahoo,...) all use to a single, common, open, and universally accessible schema ( [schema.org](http://schema.org/) )to provide a common structure and definition for information representation and search on the Internet.

Each year over a trillion web searches leverage Schema.org's schema to provide billions of web users precise, meaningful query results.  In this role in providing meaning to data on the web, Schema.org is likely the most frequently linked resource on the Internet today.

Schema.org has [many schemas](http://schema.org/docs/schemas.html) for data, both general-purpose (demographics ...) and concrete (restaurant). 


What about Healthcare data?
----
Health data remains locked behind the *tens of thousands of unique proprietary schemes* of each source health information system.   

But don't using healthcare data standards solve this problem?
The current state of healthcare data standards **is** the problem!

Healthcare data standards are "designed by committee" behind closed doors rather than by the patients or physicians on the front lines who actually use this information.  Each health standards organization has different agendas, goals, and procedures they need to support, not least of which is to monetize the standard to assure organizational growth.
The incentive is therefore to make the standard as large, complex, and difficult to understand as possible to maintain their market, maximize jobs for consultants. Health IT product vendors embrace this status quo because it gives them the top cover of an excuse: "We use HIT standards, therefore we are interoperable."

The sad truth is that each healthcare data standard is released on 
* different schedules  (weekly, monthly, quarterly, annually, or once a decade)
* different and proprietary formats
* different and proprietary licenses (none of them freely usable as creative commons)
* different models
* different licenses
* different payment models
* ambigous and conflicting defintions.  

And did I mention, different and incompatible schemes?

This begs the question:  Is healthcare data categorically different from any other kind of data?


HealthSchema.org
-----

On healthschema.org, we think heath data should an equal citizen as the rest of the data in the world, and join on the evolution to the Internet of structured data.



Stay tuned...
-----

More to come soon.






#GitHub
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



Lists:



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




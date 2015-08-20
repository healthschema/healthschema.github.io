Welcome to Heathschema.org
=====================
This is the HealthSchema.org project repository. It contains all the healthcare schemas in the same fully exposed, transparent web-developer friendly form as http://schema.org.


Formats and standards
=====================
All schemas and examples are in data/ in utf-8 encoded files.
The main schemas file is data/schema.rdfa (utf-8)
While developing schemas, using data/sdo-somethinghere-schema.rdfa can be useful.
The format is based on W3C RDFS in HTML/RDFa format, see http://schema.org/docs/datamodel.html
The examples are stored in data/examples.txt (utf-8) and other *.txt files.

As with schemas, data/*examples.txt will also be read. It can be useful to develop
using separate files. When vocabulary is finally integrated into the main repository, schema
data will be merged into schema.org. However examples will stay in separate files, as this
works better with git's file comparison machinery.

The data/releases/ hierarchy is reserved for release snapshots (see http://schema.org/version/).
The ext/*/ hierarchy is reserved for extensions (see http://schema.org/docs/extension.html).


Configuration Notes
=====================

layout and organization from [poole](https://github.com/poole/poole)

To write blogs:
* install [jekyll](https://help.github.com/articles/using-jekyll-with-pages/)
* in the base directory, run __jekyll server --watch__
* go to __localhost:4000__ in your browser to see the site
* to add or edit posts, change or add to the dated entries in the _posts directory
* to publish them on the public site, just commit and push them
* see public site at _https://healthschema.github.io/_

To edit the Poole-based theme look at:
* _config.yml
* _layouts
* _includes
* _sass (style sheets)

Note: using _robots.txt_, to tell search engines to ignore for now.

# sling-jbake
Experimenting with JBake for the Apache Sling website

## TODO
* Add proper front matter to all pages
* Use the page template instead of post
* Use tags in the page template and for navigation
* Fix internal links like `refs.project-information.path` (how? not sure so far)
* Left menu is not yellow as on the old site
* Page header and footer, logo etc
* Move images and other files to /assets and convert their links
* Remove unused assets files and templates (copied from JBake Groovy sample)
* Implement the dynamic downloads page
* Enumerate child pages in documentation/tutorials-how-tos.html
* Tables are broken in project-information.html for example

## JBake notes
* Currently using 2.5.1, see under `/bin`, docs at http://jbake.org/docs/2.5.1
* Apparently uses https://github.com/sirthias/pegdown for Markdown 
* Groovy MarkupTemplateEngine examples at https://github.com/jbake-org/jbake-example-project-groovy-mt , docs for that engine at http://groovy-lang.org/templating.html#_simpletemplateengine
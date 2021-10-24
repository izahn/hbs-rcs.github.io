# GitHubIO Pages for RCS Blog Site

Oct 23, 2021

Authors: Bob Freeman ([devbioinfoguy](https://github.com/devbioinfoguy)), Ista Zahn,
Liublinska, Xiang Ao, and Andrew Marder


## Overview:
This blog site uses the Wowchemy framework, Academic template/them, Hugo static site generator,
and TravisCI to render HTML content from various formats into HTML, which is then displayed
via GitHub Pages.

A couple of things to note:
- this seems rather fragile. See [Issue 25](https://github.com/hbs-rcs/hbs-rcs.github.io/issues/25) for a brief description of all the problems
- the TravisCI automatic engine will only render the site to GHPages if changes are pushed to 
the `source` branch. Thus, if you wish to author on any other branch, YOU MUST MERGE TO `SOURCE`
if you wish to have your posts rendered, available, and displayed.
- To follow on the previous point, the main, default branch is `source`. The rendered (GHPages) branch
is `master`. This latter branch is overwritten every build that is triggered by a commit to `source`.
- content goes only in particular directories. TBD
- There's much updating that could and should happen, both to content, repo config on GH's site, 
and the content/templating/config files. It's a hot mess. I'll add these to the repo as issues.

-Bob

NOTE: These materials and the files within are governed by the Creative Commons Attribution license (CC BY 4.0).
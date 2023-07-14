Wiki Guidelines
===============

This page lists high-level guidelines for editing https://github.com/rumpkernel/wiki/wiki/.


Titles
------

Use a page title of the form "Category: Subject".  The categories are
used for creating the navbar on the wiki.

The current categories are:

* _[Builds](https://github.com/rumpkernel/wiki/wiki/Builds)_: automated builds, tests, etc.
* _[Howto](https://github.com/rumpkernel/wiki/wiki/Howto)_: Howtos document specific tasks
* _[Info](https://github.com/rumpkernel/wiki/wiki/Info)_: General information, e.g. historical info, TODO-lists, etc.
* _[Performance](https://github.com/rumpkernel/wiki/wiki/Performance)_: important points about optimization, tuning, etc.
* _[People](https://github.com/rumpkernel/wiki/wiki/People)_: personal spaces for rump kernel project contributors.  Edit only your own page.
* _[Project ideas](https://github.com/rumpkernel/wiki/wiki/Project-Ideas)_: detailed description of a project looking for idle hands.
* _[Tutorial](https://github.com/rumpkernel/wiki/wiki/Tutorial)_: Instructions starting from zero and working towards mastering a subject area (e.g. debugging or networking)

If the article does not fit into the existing categories, please propose
a new category on the rumpkernel-users@freelists.org mailing list.

Additionally, the following categories exist, but they should be used
only if the respective code exists and is available:

* _[Repo](https://github.com/rumpkernel/wiki/wiki/Repo)_: main pages for repositories hosted under https://github.com/rumpkernel/
* _[Platforms](https://github.com/rumpkernel/wiki/wiki/Platforms)_: descriptions of platforms that rump kernels run on

Do not change titles after an article has been published, since that will
alter the article's URL and render any hyperlinks to the article invalid.


Linking
-------

Use the format \[\[text|article title\]\] to link to other articles on this wiki,
e.g. to link to the platform page you could use
`[[Platforms supported by rump kernels|Platforms]]`.
The advantage of this format is that dead links will be flagged when
the page is rendered.

To link to this wiki from an external source, use the URL `https://github.com/rumpkernel/wiki/wiki/article-name`,
e.g. https://github.com/rumpkernel/wiki/wiki/Platforms for the platforms page.
To link to a rump kernel repository (currently hosted on Github), use `https://github.com/rumpkernel/`, e.g. https://github.com/rumpkernel/buildrump.sh for buildrump.sh.


License
-------

Articles in the wiki are available under
[Creative Commons CC0](https://creativecommons.org/publicdomain/zero/1.0/).

(Note: CC0 applies only to the wiki, not to the files hosted in this repository)

Notes to myself
===============

I tend to forget how i built this, so this README is to remind
myself.

Writing new content
-------------------

Write in the content folder

Setting up in a new environment
-------------------------------

A little tricky since the theme itself is a git submodule.

* git clone repo
* cd repo
* git submodule init
* pip install pelican fabric

Branches
--------

* content branch has the editable files
* master branch has the output (becuase github need it that way)

To build
--------

* `fab build` or `fab rebuild`

To publish
----------

* `fab publish`

Knitting Projects
=================

[FOSSASIA](https://fossasia.org) has several open-source knitting projects.
This page is an overview over these projects. You can get started developing
on the projects or just check them out and install them. In the bottom,
you find the related work.

- [List of Knitting Projects][project-list]
  - [kniteditor][kniteditor]
  - [knittingpattern][knittingpattern]
  - [AYABInterface][AYABInterface]
  - [knitting.fossasia.org][knitting.fossasia.org]
  - [circle-knitting][circle-knitting]
  - [knitweb][knitweb]
  - [knitlib][knitlib]
  - [knitserver][knitserver]
- [Outdated Projects][outdated-projects]
  - [knitpat][knitpat]
  - [knitapps][knitserver]
- [Related Work][related-work]
  - [ayab-apparat][ayab-apparat]

List of Knitting Projects
-------------------------

Here you can find a list of knitting projects in the FOSSASIA organization:

### kniteditor [![View on Github][github-logo]][kniteditor-repo]

The Knit Editor is an editor for the knit exchange format.
It allows [creating digital knit works][knittingpattern] from images
and knitting it with several knitting machines.

This kniteditor is developed together with [All Yarns Are Beautiful][ayab].
You can [download the releases][kniteditor-releases] and install them.

Contribute:
[Repository][kniteditor-repo]
[![Issues Ready to Work on][kniteditor-waffle-badge]][kniteditor-waffle]
[![Read the Documentation][kniteditor-rtd-badge]][kniteditor-rtd]
[![Travis Build Status][kniteditor-travis-badge]][kniteditor-travis]
[![AppVeyor Build Status][kniteditor-appveyor-badge]][kniteditor-appveyor]
[![Code Climate][kniteditor-codeclimate-badge]][kniteditor-codeclimate]
[![Test Coverage][kniteditor-test-coverage-badge]][kniteditor-test-coverage]
[![Code Issue Count][kniteditor-issue-count-badge]][kniteditor-issue-count]
[![Code Health][kniteditor-landscape-badge]][kniteditor-landscape]
[![Python Package Index Version][kniteditor-pypi-badge]][kniteditor-pypi]
[![Python Package Index Downloads][kniteditor-pypi-downloads-badge]][kniteditor-pypi-downloads]



### knittingpattern [![View on Github][github-logo]][knittingpattern-repo]

The `knittingpattern` is a Python library for an exchange format for knit work.
It allows specifying how to knit a particular piece of work.

Contribute:
[Repository][knittingpattern-repo]
[![Issues Ready to Work on][knittingpattern-waffle-badge]][knittingpattern-waffle]
[![Read the Documentation][knittingpattern-rtd-badge]][knittingpattern-rtd]
[![Travis Build Status][knittingpattern-travis-badge]][knittingpattern-travis]
[![AppVeyor Build Status][knittingpattern-appveyor-badge]][knittingpattern-appveyor]
[![Code Climate][knittingpattern-codeclimate-badge]][knittingpattern-codeclimate]
[![Test Coverage][knittingpattern-test-coverage-badge]][knittingpattern-test-coverage]
[![Code Issue Count][knittingpattern-issue-count-badge]][knittingpattern-issue-count]
[![Code Health][knittingpattern-landscape-badge]][knittingpattern-landscape]
[![Python Package Index Version][knittingpattern-pypi-badge]][knittingpattern-pypi]
[![Python Package Index Downloads][knittingpattern-pypi-downloads-badge]][knittingpattern-pypi-downloads]



### AYABInterface [![View on Github][github-logo]][AYABInterface-repo]

The `AYABInterface` is used by the [Knit Editor][kniteditor] to
convert [knittingpatterns][knittingpattern] into machine instructions.
It can be used standalone without these other projects.

Contribute:
[Repository][AYABInterface-repo]
[![Issues Ready to Work on][AYABInterface-waffle-badge]][AYABInterface-waffle]
[![Read the Documentation][AYABInterface-rtd-badge]][AYABInterface-rtd]
[![Travis Build Status][AYABInterface-travis-badge]][AYABInterface-travis]
[![AppVeyor Build Status][AYABInterface-appveyor-badge]][AYABInterface-appveyor]
[![Code Climate][AYABInterface-codeclimate-badge]][AYABInterface-codeclimate]
[![Test Coverage][AYABInterface-test-coverage-badge]][AYABInterface-test-coverage]
[![Code Issue Count][AYABInterface-issue-count-badge]][AYABInterface-issue-count]
[![Code Health][AYABInterface-landscape-badge]][AYABInterface-landscape]
[![Python Package Index Version][AYABInterface-pypi-badge]][AYABInterface-pypi]
[![Python Package Index Downloads][AYABInterface-pypi-downloads-badge]][AYABInterface-pypi-downloads]



### knitting.fossasia.org [![View on Github][github-logo]][knitting.fossasia.org-repo]

This is this overview site over the different knitting projects. 
You can visit the [website][this-site], [add new entries][knitting.fossasia.org-edit].

Contribute:
[Repository][knitting.fossasia.org-repo]
[![Issues Ready to Work on][knitting.fossasia.org-waffle-badge]][knitting.fossasia.org-waffle]



### circle-knitting [![View on Github][github-logo]][circle-knitting-repo]

There are commercial circular knitting machines, that are nearly completely made from plastic. 
A popular modul is the Addi Express. 
Plastic can be easily printed out on 3D printers. 
This project implements the idea to code a circular knitting machine. 
As inexpensive small PCs components like the Rapsberry PI and Arduinos become increasingly powerful there is even an option to include them as optional components in such a 3D printed knitting machine.

Contribute:
[Repository][circle-knitting-repo]
[![Issues Ready to Work on][circle-knitting-waffle-badge]][circle-knitting-waffle]



### knitweb [![View on Github][github-logo]][knitweb-repo]

[`knitweb`][knitweb-repo] is an app frontend and backend that works together with the
[`knitlib`][knitserver] server and uses the [`knitpat`][knitpat] format.

Contribute:
[Repository][knitweb-repo]
[![Issues Ready to Work on][knitweb-waffle-badge]][knitweb-waffle]



### knitlib [![View on Github][github-logo]][knitlib-repo]

Knitlib is a library designed to support the operation of varied knitting machines, mechanisms, and hacks.
Knitlib is based on projects like [AYAB][ayab], PDD, and KnitterStream to control knitting machines.
Knitlib features a plugin system for knitting machines and implements an API to control machines' operation,
knitting jobs and knitting patterns. The software is based on Python.
There also is a Web API.
Among the primary tasks is to develop plugins based on this solution to add support for more machines.

Contribute:
[Repository][knitlib-repo]
[![Issues Ready to Work on][knitlib-waffle-badge]][knitlib-waffle]
[![Read the Documentation][knitlib-rtd-badge]][knitlib-rtd]
[![Travis Build Status][knitlib-travis-badge]][knitlib-travis]



### knitserver [![View on Github][github-logo]][knitserver-repo]

Knitserver is a [Knitlib][knitlib] client that provides REST API endpoints for knitting machine software and control.
Knitserver is designed to interact with [Knitweb][knitweb].

Contribute:
[Repository][knitserver-repo]
[![Issues Ready to Work on][knitserver-waffle-badge]][knitserver-waffle]



Outdated Projects
-----------------

These projects are a bit older, obsoleted or not maintained any more.

### knitpat [![View on Github][github-logo]][knitpat-repo]

`knitpat` contains a pattern definition format for knit work.
It is the predecessor of the [`knittingpattern`][knittingpattern] library.

Contribute:
[Repository][knitpat-repo]
[![Issues Ready to Work on][knitpat-waffle-badge]][knitpat-waffle]



### knitapps [![View on Github][github-logo]][knitapps-repo]

An older version of [this overview site][top].

Contribute:
[Repository][knitapps-repo]
[![Issues Ready to Work on][knitapps-waffle-badge]][knitapps-waffle]



Related Work
------------

This section contains links and related projets and work in the field of knitting.
Additionally, other overview sites are listed here.



### ayab-apparat [![View on Github][github-logo]][ayab-apparat-repo]

This Software is a predecessor of [the Knit Editor][kniteditor].
It is written in Python and Qt.
[AYAB][ayab] maintains this project.
The 2016 [Google Summer of Code Project][ayab-apparat-fork] forked this repository and added the issues for the [kniteditor][kniteditor], [knittingpattern][knittingpattern] and [AYABInterface][AYABInterface].

Contribute:
[Repository][ayab-apparat-repo]










[top]: #fossasia-knitting-projects
[project-list]: #list-of-knitting-projects
[outdated-projects]: #outdated-projects
[this-site]: https://knitting.fossasia.org
[ayab]: http://ayab-knitting.com/
[related-work]: #related-work



[kniteditor]: #kniteditor-
[kniteditor-repo]: https://github.com/fossasia/kniteditor
[kniteditor-waffle]: http://waffle.io/fossasia/kniteditor
[kniteditor-waffle-badge]: https://badge.waffle.io/fossasia/kniteditor.svg?label=ready&title=Ready "Issues Ready to Work on"
[kniteditor-travis]: https://travis-ci.org/fossasia/kniteditor
[kniteditor-travis-badge]: https://travis-ci.org/fossasia/kniteditor.svg "Travis Build Status"
[kniteditor-appveyor]: https://ci.appveyor.com/project/AllYarnsAreBeautiful/kniteditor
[kniteditor-appveyor-badge]: https://ci.appveyor.com/api/projects/status/yildjtxp8an3vejx?svg=true "AppVeyor Build Status"
[kniteditor-codeclimate]: https://codeclimate.com/github/fossasia/kniteditor
[kniteditor-codeclimate-badge]: https://codeclimate.com/github/fossasia/kniteditor/badges/gpa.svg "Code Climate"
[kniteditor-test-coverage]: https://codeclimate.com/github/fossasia/kniteditor/coverage
[kniteditor-test-coverage-badge]: https://codeclimate.com/github/fossasia/kniteditor/badges/coverage.svg "Test Coverage"
[kniteditor-issue-count]: https://codeclimate.com/github/fossasia/kniteditor
[kniteditor-issue-count-badge]: https://codeclimate.com/github/fossasia/kniteditor/badges/issue_count.svg "Code Issue Count"
[kniteditor-pypi]: https://pypi.python.org/pypi/kniteditor
[kniteditor-pypi-badge]: https://badge.fury.io/py/kniteditor.svg "Python Package Index Version"
[kniteditor-pypi-downloads]: https://pypi.python.org/pypi/kniteditor#downloads
[kniteditor-pypi-downloads-badge]: https://img.shields.io/pypi/dm/kniteditor.svg "Python Package Index Downloads"
[kniteditor-rtd]: https://kniteditor.readthedocs.org
[kniteditor-rtd-badge]: https://readthedocs.org/projects/kniteditor/badge/?version=latest "Read the Documentation"
[kniteditor-landscape]: https://landscape.io/github/fossasia/kniteditor/master
[kniteditor-landscape-badge]: https://landscape.io/github/fossasia/kniteditor/master/landscape.svg?style=flat "Code Health"

[kniteditor-releases]: https://github.com/fossasia/kniteditor/releases



[knittingpattern]: #knittingpattern-
[knittingpattern-repo]: https://github.com/fossasia/knittingpattern
[knittingpattern-waffle]: http://waffle.io/fossasia/knittingpattern
[knittingpattern-waffle-badge]: https://badge.waffle.io/fossasia/knittingpattern.svg?label=ready&title=Ready "Stories in Ready"
[knittingpattern-travis]: https://travis-ci.org/fossasia/knittingpattern
[knittingpattern-travis-badge]: https://travis-ci.org/fossasia/knittingpattern.svg "Travis Build Status"
[knittingpattern-appveyor]: https://ci.appveyor.com/project/AllYarnsAreBeautiful/knittingpattern
[knittingpattern-appveyor-badge]: https://ci.appveyor.com/api/projects/status/c1983ovsc8thlhvi?svg=true "AppVeyor Build Status"
[knittingpattern-codeclimate]: https://codeclimate.com/github/fossasia/knittingpattern
[knittingpattern-codeclimate-badge]: https://codeclimate.com/github/fossasia/knittingpattern/badges/gpa.svg "Code Climate"
[knittingpattern-test-coverage]: https://codeclimate.com/github/fossasia/knittingpattern/coverage
[knittingpattern-test-coverage-badge]: https://codeclimate.com/github/fossasia/knittingpattern/badges/coverage.svg "Test Coverage"
[knittingpattern-issue-count]: https://codeclimate.com/github/fossasia/knittingpattern
[knittingpattern-issue-count-badge]: https://codeclimate.com/github/fossasia/knittingpattern/badges/issue_count.svg "Code Issue Count"
[knittingpattern-pypi]: https://pypi.python.org/pypi/knittingpattern
[knittingpattern-pypi-badge]: https://badge.fury.io/py/knittingpattern.svg "Python Package Index Version"
[knittingpattern-pypi-downloads]: https://pypi.python.org/pypi/knittingpattern#downloads
[knittingpattern-pypi-downloads-badge]: https://img.shields.io/pypi/dm/knittingpattern.svg "Python Package Index Downloads"
[knittingpattern-rtd]: https://knittingpattern.readthedocs.org
[knittingpattern-rtd-badge]: https://readthedocs.org/projects/knittingpattern/badge/?version=latest "Read the Documentation"
[knittingpattern-landscape]: https://landscape.io/github/fossasia/knittingpattern/master
[knittingpattern-landscape-badge]: https://landscape.io/github/fossasia/knittingpattern/master/landscape.svg?style=flat "Code Health"



[AYABInterface]: #AYABInterface-
[AYABInterface-repo]: https://github.com/fossasia/AYABInterface
[AYABInterface-waffle]: http://waffle.io/fossasia/AYABInterface
[AYABInterface-waffle-badge]: https://badge.waffle.io/fossasia/AYABInterface.svg?label=ready&title=Ready "Stories in Ready"
[AYABInterface-travis]: https://travis-ci.org/fossasia/AYABInterface
[AYABInterface-travis-badge]: https://travis-ci.org/fossasia/AYABInterface.svg "Travis Build Status"
[AYABInterface-appveyor]: https://ci.appveyor.com/project/AllYarnsAreBeautiful/AYABInterface
[AYABInterface-appveyor-badge]: https://ci.appveyor.com/api/projects/status/a6yhbt0rqvb212s7?svg=true "AppVeyor Build Status"
[AYABInterface-codeclimate]: https://codeclimate.com/github/fossasia/AYABInterface
[AYABInterface-codeclimate-badge]: https://codeclimate.com/github/fossasia/AYABInterface/badges/gpa.svg "Code Climate"
[AYABInterface-test-coverage]: https://codeclimate.com/github/fossasia/AYABInterface/coverage
[AYABInterface-test-coverage-badge]: https://codeclimate.com/github/fossasia/AYABInterface/badges/coverage.svg "Test Coverage"
[AYABInterface-issue-count]: https://codeclimate.com/github/fossasia/AYABInterface
[AYABInterface-issue-count-badge]: https://codeclimate.com/github/fossasia/AYABInterface/badges/issue_count.svg "Code Issue Count"
[AYABInterface-pypi]: https://pypi.python.org/pypi/AYABInterface
[AYABInterface-pypi-badge]: https://badge.fury.io/py/AYABInterface.svg "Python Package Index Version"
[AYABInterface-pypi-downloads]: https://pypi.python.org/pypi/AYABInterface#downloads
[AYABInterface-pypi-downloads-badge]: https://img.shields.io/pypi/dm/AYABInterface.svg "Python Package Index Downloads"
[AYABInterface-rtd]: https://AYABInterface.readthedocs.org
[AYABInterface-rtd-badge]: https://readthedocs.org/projects/AYABInterface/badge/?version=latest "Read the Documentation"
[AYABInterface-landscape]: https://landscape.io/github/fossasia/AYABInterface/master
[AYABInterface-landscape-badge]: https://landscape.io/github/fossasia/AYABInterface/master/landscape.svg?style=flat "Code Health"



[knitting.fossasia.org]: #knittingfossasiaorg-
[knitting.fossasia.org-repo]: https://github.com/fossasia/knitting.fossasia.org
[knitting.fossasia.org-waffle]: http://waffle.io/fossasia/knitting.fossasia.org
[knitting.fossasia.org-waffle-badge]: https://badge.waffle.io/fossasia/knitting.fossasia.org.svg?label=ready&title=Ready "Stories in Ready"
[knitting.fossasia.org-edit]: https://github.com/fossasia/knitting.fossasia.org/edit/gh-pages/README.md



[knitweb]: #knitweb-
[knitweb-repo]: https://github.com/fossasia/knitweb
[knitweb-waffle]: http://waffle.io/fossasia/knitweb
[knitweb-waffle-badge]: https://badge.waffle.io/fossasia/knitweb.svg?label=ready&title=Ready "Stories in Ready"
[knitweb-travis]: https://travis-ci.org/fossasia/knitweb
[knitweb-travis-badge]: https://travis-ci.org/fossasia/knitweb.svg "Travis Build Status"



[circle-knitting]: #circle-knitting-
[circle-knitting-repo]: https://github.com/fossasia/circle-knitting
[circle-knitting-waffle]: http://waffle.io/fossasia/circle-knitting
[circle-knitting-waffle-badge]: https://badge.waffle.io/fossasia/circle-knitting.svg?label=ready&title=Ready "Stories in Ready"



[knitlib]: #knitlib-
[knitlib-repo]: https://github.com/fossasia/knitlib
[knitlib-waffle]: http://waffle.io/fossasia/knitlib
[knitlib-waffle-badge]: https://badge.waffle.io/fossasia/knitlib.svg?label=ready&title=Ready "Stories in Ready"
[knitlib-travis]: https://travis-ci.org/fossasia/knitlib
[knitlib-travis-badge]: https://travis-ci.org/fossasia/knitlib.svg "Travis Build Status"
[knitlib-rtd]: https://knitlib.readthedocs.org
[knitlib-rtd-badge]: https://readthedocs.org/projects/knitlib/badge/?version=latest "Read the Documentation"



[knitserver]: #knitserver-
[knitserver-repo]: https://github.com/fossasia/knitserver
[knitserver-waffle]: http://waffle.io/fossasia/knitserver
[knitserver-waffle-badge]: https://badge.waffle.io/fossasia/knitserver.svg?label=ready&title=Ready "Stories in Ready"



[knitapps]: #knitapps-
[knitapps-repo]: https://github.com/fossasia/knitapps
[knitapps-waffle]: http://waffle.io/fossasia/knitapps
[knitapps-waffle-badge]: https://badge.waffle.io/fossasia/knitapps.svg?label=ready&title=Ready "Stories in Ready"



[knitpat]: #knitpat-
[knitpat-repo]: https://github.com/fossasia/knitpat
[knitpat-waffle]: http://waffle.io/fossasia/knitpat
[knitpat-waffle-badge]: https://badge.waffle.io/fossasia/knitpat.svg?label=ready&title=Ready "Stories in Ready"



[ayab-apparat]: #ayab-apparat-
[ayab-apparat-fork]: https://github.com/allyarnsarebeautiful/ayab-desktop
[ayab-apparat-repo]: https://bitbucket.org/chris007de/ayab-apparat
[ayab-apparat-waffle]: http://waffle.io/allyarnsarebeautiful/ayab-apparat
[ayab-apparat-waffle-badge]: https://badge.waffle.io/allyarnsarebeautiful/ayab-apparat.svg?label=ready&title=Ready "Stories in Ready"



[github-logo]: images/GitHub.png "View on Github"

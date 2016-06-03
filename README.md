# Dueling Dogs Online Help Documentation - [http://help.duelingdogs.net/en/latest](http://help.duelingdogs.net/en/latest/)

[![Build Status](https://travis-ci.org/duelingdogs/dueling-docs.svg?branch=master)](https://travis-ci.org/duelingdogs/dueling-docs)

[![Documentation Status](https://readthedocs.org/projects/dueling-dogs-online-documentation/badge/?version=latest)](http://dueling-dogs-online-documentation.readthedocs.org/en/latest/?badge=latest)

### Pre-requesites

* [Git](https://git-scm.com/)
* [Sphinx](http://www.sphinx-doc.org/en/stable/) or check the [Sphinx Github Repository](https://github.com/sphinx-doc/sphinx)
* Python (for using Sphinx)
* Pip (for using/installing Sphinx)
* Text editor such as Atom, Notepad++, or SublimeText.
* Terminal/Powershell access (iTerm2, Terminal.app, etc.)
* Git Desktop client _(if you prefer a GUI instead of a shell prompt). Suggested applications would be Github Desktop Client, Sourcetree, or Tower (Mac OS X Only)_.

### Checkout Documentation for Editing

* If you've never obtained the documentation before you'll want to clone the repository. The default branch is `master`, this is good.
    * `$ git@github.com:duelingdogs/dueling-docs.git`
* If you've already cloned the repository navigate to where this is in your computer using Terminal or Powershell. Once in this directory you'll be able to execute the following:
    * `$ git fetch && git checkout master`

### How to Edit

* Edit files in `source` folder using a text editor such as Atom, SublimeText, or Notepad++.
* Files are written in `reStructuredText` syntax or `Markdown`.

### Deploying Edits to Production Environment

* `$ git commit -am "commit message documenting what you've changed"`
* `$ git push`
* Once pushed to `master` branch `Travis-CI` will attempt to compile the documentation via a combination of wizardry and science.
* If [Travis-CI](https://travis-ci.org/duelingdogs/dueling-docs) is satisfied that the build compiles properly it will send it for compiling and deployment at [ReadTheDocs](http://readthedocs.org/projects/dueling-dogs-online-documentation/)
* Confirm updates are live & accessible via accessing [http://help.duelingdogs.net](http://help.duelingdogs.net). _This may take a few minutes to fully deploy, please be patient. Check the `Travis-CI` page & `ReadTheDocs` build pages linked above._


#### Deployment Status

[![Build Status](https://travis-ci.org/duelingdogs/dueling-docs.svg?branch=master)](https://travis-ci.org/duelingdogs/dueling-docs)

[![Documentation Status](https://readthedocs.org/projects/dueling-dogs-online-documentation/badge/?version=latest)](http://dueling-dogs-online-documentation.readthedocs.org/en/latest/?badge=latest)

#### Viewing & Downloading Latest Documentation

* To view the latest documentation online simply visit [http://help.duelingdogs.net](http://help.duelingdogs.net).
* To download the latest documentation as a PDF for offline access visit [http://readthedocs.org/projects/dueling-dogs-online-documentation/downloads/pdf/latest/](http://readthedocs.org/projects/dueling-dogs-online-documentation/downloads/pdf/latest/)

#### License & Copyright

* Copyright 2015-2016, All Rights Reserved - [Dueling Dogs, LLC](https://duelingdogs.net).


#### Contributors

* [Brian J King](http://github.com/brianjking)

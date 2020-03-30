# awesome-python-bytes

😎 🐍 Awesome lists about Python Bytes <https://pythonbytes.fm/>

[Python Bytes](https://pythonbytes.fm/) is a weekly, short & sweet podcast by [Michael Kennedy](https://twitter.com/mkennedy) & [Brian Okken](https://twitter.com/brianokken).

![Python Bytes Image](https://pythonbytes.fm/static/img/banner_750.png)

This repository is intended to list the awesome packages mentioned on the podcast. Pull requests are open to anyone to add packages mentioned on the podcast that are awesome!

# Format

Each package is listed in the following format:

``` markdown
[Package Name](link/to/package)
*Link to show notes where mentioned*
Short package description
![IMAGE IF APPLICABLE]
```
<!-- omit in toc -->
# Table Of Contents

- [awesome-python-bytes](#awesome-python-bytes)
- [Format](#format)
- [Web Development](#web-development)
  - [Wagtail](#wagtail)
  - [Wooey](#wooey)
  - [Anvil](#anvil)
  - [Vue.py](#vuepy)
- [Data Science](#data-science)
  - [Great Expectations](#great-expectations)
  - [PDF Plumber](#pdf-plumber)
  - [PyJanitor](#pyjanitor)
  - [Pandas Vet](#pandas-vet)
  - [NB2XLS](#nb2xls)
  - [pylightxl](#pylightxl)
- [Data Visualisation](#data-visualisation)
  - [Pylustrator](#pylustrator)
  - [Chartify](#chartify)
- [Machine Learning](#machine-learning)
  - [PyTorch](#pytorch)
  - [Yellow Brick](#yellow-brick)
  - [Thinc](#thinc)
  - [Keras Gym](#keras-gym)
- [Databases](#databases)
  - [GeoAlchemy](#geoalchemy)
- [Command Line Interfaces (CLIs)](#command-line-interfaces-clis)
  - [Python Fire](#python-fire)
  - [Clize](#clize)
  - [Typer](#typer)
- [Guided User Interfaces (GUIs)](#guided-user-interfaces-guis)
  - [Gooey](#gooey)
  - [Eel GUI](#eel-gui)
  - [QUICK](#quick)
- [Python Development](#python-development)
  - [Attrs](#attrs)
  - [PyOxidiser](#pyoxidiser)
  - [Python Date Utils](#python-date-utils)
  - [Pycel](#pycel)
  - [PyDantic](#pydantic)
  - [Dacite](#dacite)
- [Game Development](#game-development)
  - [Panda3D](#panda3d)
- [Interesting Tidbits](#interesting-tidbits)

# Web Development

## [Wagtail](https://wagtail.io/)

*[https://pythonbytes.fm/episodes/show/70/have-you-seen-my-log-it-s-cute](https://pythonbytes.fm/episodes/show/70/have-you-seen-my-log-it-s-cute)*
`Wagtail` is a content management system (CMS) (like Wordpress), written in `Python`, based off `Django`.

[Gallery of sites made with `wagtail`](https://madewithwagtail.org/)

## [Wooey](https://github.com/wooey/Wooey)

*[https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis](https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis)*
A `Django` app that creates automatic web UIs for `Python` scripts.

Live example at: [https://wooey.herokuapp.com/](https://wooey.herokuapp.com/)

![Wooey Example]({static img/wooey-example.png})

## [Anvil](https://anvil.works/)

*[https://pythonbytes.fm/episodes/show/106/fluent-query-apis-on-python-collections](https://pythonbytes.fm/episodes/show/106/fluent-query-apis-on-python-collections)*

Full stack web apps with nothing but `Python`.

## Vue.py

*[https://pythonbytes.fm/episodes/show/140/becoming-a-10x-developer-sorta](https://pythonbytes.fm/episodes/show/140/becoming-a-10x-developer-sorta)*
use `Vue.js` with pure `Python`

`vue.py` provides `Python` bindings for `Vue.js`. It uses `brython` to run `Python` in the browser.

Live example at: [https://stefanhoelzl.github.io/vue.py/examples/todo_mvc/](https://stefanhoelzl.github.io/vue.py/examples/todo_mvc/)

![Vue.py Example](https://raw.githubusercontent.com/stefanhoelzl/vue.py/gh-pages/examples/todo_mvc/screenshot.png)

# Data Science

## [Great Expectations](https://great-expectations.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/115/dataclass-csv-reader-and-nina-drops-by](https://pythonbytes.fm/episodes/show/115/dataclass-csv-reader-and-nina-drops-by)*
`Great Expectations` is a leading tool for validating, documenting, and profiling, your data to maintain quality and improve communication between teams.

## [PDF Plumber](https://github.com/jsvine/pdfplumber)

*[https://pythonbytes.fm/episodes/show/26/how-have-you-automated-your-life-or-cli-with-python](https://pythonbytes.fm/episodes/show/26/how-have-you-automated-your-life-or-cli-with-python)*

Plumb a PDF for detailed information about each char, rectangle, line, et cetera — and easily extract text and tables.

![PDF Plumb Example](https://raw.githubusercontent.com/jsvine/pdfplumber/master/examples/screenshots/visual-debugging-in-jupyter.png)

## [PyJanitor](https://pyjanitor.readthedocs.io/)

*[https://pythonbytes.fm/episodes/show/108/spilled-data-call-the-pyjanitor](https://pythonbytes.fm/episodes/show/108/spilled-data-call-the-pyjanitor)*

`pyjanitor` is a project that extends Pandas with a verb-based API, providing convenient data cleaning routines for repetitive tasks.

## [Pandas Vet](https://github.com/deppen8/pandas-vet)

*[https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod](https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod)*

`pandas-vet` is a plugin for `flake8` that provides opinionated linting for pandas code.

## [NB2XLS](https://github.com/ideonate/nb2xls)

*[https://github.com/ideonate/nb2xls](https://github.com/ideonate/nb2xls)*
Convert `Jupyter` notebooks to Excel Spreadsheets (xlsx), through a new 'Download As' option or via `nbconvert` on the command line.
![NB2XLS Preview](https://raw.githubusercontent.com/ideonate/nb2xls/master/screenshots/Jupyter2Excel.png)

## [pylightxl](https://github.com/PydPiper/pylightxl)

*[https://pythonbytes.fm/episodes/show/165/ranges-as-dictionary-keys-oh-my](https://pythonbytes.fm/episodes/show/165/ranges-as-dictionary-keys-oh-my)*

A light weight, zero dependency (only standard libs used), to the point (no bells and whistles) Microsoft Excel reader/writer python 2.7-3+ library.
![Example Code](https://github.com/PydPiper/pylightxl/blob/master/doc/source/_static/readme_demo.gif)

Why pylightxl over pandas/openpyxl
- (compatibility +1, small lib +1) pylightxl has no external dependencies (only uses python built-in standard libs).
(compatibility +1) pylightxl was written to be compatible for python 2.7-3+ under one single pylightxl version. It does not impose rules on users to switch versions.
- (small lib +1) pylightxl was written to simply read/write, thereby making the library small without any bells or whistles which makes it easy to compile with PyInstaller and other packagers
- (user friendly +1) pylightxl was written to be as pythonic and easy to use as possible. Core developers actively survey Stack Overflow questions on working with excel files to tailor the API for most common problems.
- (see xlrd before pylightxl) Note that the xlrd library is very similar in values to pylightxl, but with much more functionality! Please take a look at xlrd to see if it is a good fit for your project. So why pick pylightxl over xlrd that has much more to offer? Currently, xlrd does not have any active developers. Pylightxl is a new library aimed to help solve current excel data issues (as surveyed by Stack Overflow), please submit your suggestions to help improve this library together.


# Data Visualisation

## [Pylustrator](https://pylustrator.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/137/advanced-python-testing-and-big-time-diffs](https://pythonbytes.fm/episodes/show/137/advanced-python-testing-and-big-time-diffs)*

`Pylustrator` offers an interactive interface to find the best way to present your data in a figure for publication. Added formatting an styling can be saved by automatically generated code. To compose multiple figures to panels, pylustrator can compose different subfigures to a single figure.

[![pylustrator demonstration](https://img.youtube.com/vi/xXPI4LLrNuM/0.jpg)](https://www.youtube.com/watch?v=xXPI4LLrNuM "pylustrator demonstration")

## [Chartify](https://github.com/spotify/chartify)

*[https://pythonbytes.fm/episodes/show/109/cpython-byte-code-explorer](https://pythonbytes.fm/episodes/show/109/cpython-byte-code-explorer)*

`Chartify` is a `Python` library that makes it easy for data scientists to create charts.

![Chartify Example](https://raw.githubusercontent.com/spotify/chartify/master/docs/_static/chartify1.png)

# Machine Learning

## [PyTorch](https://github.com/pytorch/pytorch)

*[https://pythonbytes.fm/episodes/show/80/dan-bader-drops-by-and-we-found-30-new-python-projects](https://pythonbytes.fm/episodes/show/80/dan-bader-drops-by-and-we-found-30-new-python-projects)*
Tensors and Dynamic neural networks in `Python` with strong GPU acceleration

## [Yellow Brick](https://www.scikit-yb.org/en/latest/)

*[https://pythonbytes.fm/episodes/show/74/contributing-to-open-source-effectively](https://pythonbytes.fm/episodes/show/74/contributing-to-open-source-effectively)*
`Yellowbrick` extends the `Scikit-Learn` API to make model selection and hyperparameter tuning easier. Under the hood, it’s using `Matplotlib`.
![Yellow Brick Preview](https://www.scikit-yb.org/en/latest/_images/banner.png)

## [Thinc](https://thinc.ai/)

*[https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod](https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod)*
A refreshing functional take on deep learning, compatible with your favorite libraries.
From the makers of `spaCy`, `Prodigy` & `FastAPI`

## [Keras Gym](https://github.com/KristianHolsheimer/keras-gym)

*[https://github.com/KristianHolsheimer/keras-gym](https://github.com/KristianHolsheimer/keras-gym)*
Plug-n-play reinforcement learning with OpenAI Gym and `Keras`
![Keras Gym GIF](https://raw.githubusercontent.com/KristianHolsheimer/keras-gym/master/doc/_static/img/cartpole.gif)

# Databases

## [GeoAlchemy](https://geoalchemy-2.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/77/you-don-t-have-to-be-a-workaholic-to-win](https://pythonbytes.fm/episodes/show/77/you-don-t-have-to-be-a-workaholic-to-win)*
Using `SQLAlchemy` with Spatial Databases.

`GeoAlchemy 2` provides extensions to `SQLAlchemy` for working with spatial databases.

`GeoAlchemy 2` focuses on `PostGIS`. `PostGIS 1.5` and `PostGIS 2` are supported.

# Command Line Interfaces (CLIs)

## [Python Fire](https://github.com/google/python-fire)

*[https://pythonbytes.fm/episodes/show/17/google-s-python-is-on-fire-and-simon-says-you-have-cpu-load-pythonically](https://pythonbytes.fm/episodes/show/17/google-s-python-is-on-fire-and-simon-says-you-have-cpu-load-pythonically)*
``Python`Fire` is a library for automatically generating command line interfaces (CLIs) from absolutely any `Python` object.

## [Clize](https://clize.readthedocs.io/en/stable/)

*[https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod](https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod)*

`Clize` is an argument parser for `Python`. You can use `Clize` as an alternative to `argparse` if you want an even easier way to create command-line interfaces.

## [Typer](https://typer.tiangolo.com/)

*[https://pythonbytes.fm/episodes/show/164/use-type-hints-to-build-your-next-cli-app](https://pythonbytes.fm/episodes/show/164/use-type-hints-to-build-your-next-cli-app)*

`Typer`, build great CLIs. Easy to code. Based on `Python` type hints.

# Graphical User Interfaces (GUIs)

## [Gooey](https://github.com/chriskiehl/Gooey)

*[https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis](https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis)*

I personally love `Gooey` and have it installed in almost every project lately. `Gooey` turns (almost) any `Python` command line program into a full GUI application with one line.

I have also done a tutorial blog post on Gooey as well at: [https://jackmckew.dev/making-executable-guis-with-python-gooey-pyinstaller.html](https://jackmckew.dev/making-executable-guis-with-python-gooey-pyinstaller.html#making-executable-guis-with-python-gooey-pyinstaller)

![Gooey Example](https://raw.githubusercontent.com/chriskiehl/GooeyImages/images/readme-images/1-0-3-title-card.png)

## [Eel GUI](https://github.com/samuelhwilliams/Eel)

*[https://pythonbytes.fm/episodes/show/61/on-being-a-senior-engineer](https://pythonbytes.fm/episodes/show/61/on-being-a-senior-engineer)*
`Eel` is a little `Python` library for making simple Electron-like offline HTML/JS GUI apps, with full access to `Python` capabilities and libraries.

![Eel Demo](https://raw.githubusercontent.com/samuelhwilliams/Eel/master/examples/04%20-%20file_access/Screenshot.png)

## [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI)

*[https://pythonbytes.fm/episodes/show/90/a-django-async-roadmap](https://pythonbytes.fm/episodes/show/90/a-django-async-roadmap)*

*[https://pythonbytes.fm/episodes/show/104/api-evolution-the-right-way](https://pythonbytes.fm/episodes/show/104/api-evolution-the-right-way)*

PySimpleGUI enables anyone with a week of PySimpleGUI education or more to develop an entirely custom desktop GUI application.  The underlying GUI frameworks supported include tkinter, Qt, WxPython and Remi.  PySimpleGUI code can be run on any of these underlying frameworks with little or often no modification to the source code. 

Unlike other simplified GUI pacakges, PySimpleGUI has a rich palette of widgets that are not dumbed down and can be assembled into any configuration desired, resulting in applications that look and operate as if written directly in tkinter, Qt, etc.  Simple defines the ease of writing the programs, not the class of problems that are capable of being solved. 100's of demo programs are provided to give programmers a jump start on integrating with other packages such as OpenCV, Matplotlib.  There are over 500 GitHub projects currently using PySimpleGUI.

A couple recent projects include:

A series of Rainmeter-style "Desktop Widgets": https://github.com/PySimpleGUI/PySimpleGUI-Widgets

![PSG CPU Cores Scrolling](https://user-images.githubusercontent.com/46163555/72114378-52830400-3311-11ea-8584-32bde5c265db.gif)


A photo and video colorizer: https://github.com/PySimpleGUI/PySimpleGUI-Photo-Colorizer


![SNAG-0628](https://user-images.githubusercontent.com/46163555/71523943-4327a380-2899-11ea-95b7-a2892f611109.jpg)


## [QUICK](https://github.com/szsdk/quick)

*[https://pythonbytes.fm/episodes/show/166/misunderstanding-software-clocks-and-time](https://pythonbytes.fm/episodes/show/166/misunderstanding-software-clocks-and-time)*
A real quick GUI generator for `click`. Inspired by `Gooey`, the GUI generator for classical `Python` `argparse`-based command line programs.

![QUICK Example](https://user-images.githubusercontent.com/6657200/38025934-bf93013c-32bc-11e8-8d12-91411b28946e.png)

# Python Development

## [Attrs](https://github.com/python-attrs/attrs)

*[https://pythonbytes.fm/episodes/show/11/django-2.0-is-dropping-python-2-entirely-pipenv-for-profile-functionality-and-pythonic-home-automation](https://pythonbytes.fm/episodes/show/11/django-2.0-is-dropping-python-2-entirely-pipenv-for-profile-functionality-and-pythonic-home-automation)*
`Python` Classes Without Boilerplate

## [PyOxidiser](https://github.com/indygreg/PyOxidizer)

*[https://pythonbytes.fm/episodes/show/114/what-should-be-in-the-python-standard-library](https://pythonbytes.fm/episodes/show/114/what-should-be-in-the-python-standard-library)*
`PyOxidizer` is a utility for producing binaries that embed `Python`. The over-arching goal of `PyOxidizer` is to make complex packaging and distribution problems simple so application maintainers can focus on building applications instead of toiling with build systems and packaging tools.

## [Python Date Utils](https://dateutil.readthedocs.io/en/stable/)

*[https://pythonbytes.fm/episodes/show/136/a-python-kernel-rather-than-cleaning-the-batteries](https://pythonbytes.fm/episodes/show/136/a-python-kernel-rather-than-cleaning-the-batteries)*

The `dateutil` module provides powerful extensions to the standard datetime module, available in `Python`.

## [Pycel](https://github.com/dgorissen/pycel)

*[https://pythonbytes.fm/episodes/show/171/chilled-out-python-decorators-with-pep-614](https://pythonbytes.fm/episodes/show/171/chilled-out-python-decorators-with-pep-614)*

A library for compiling excel spreadsheets to `Python` code & visualizing them as a graph

## [PyDantic](https://pydantic-docs.helpmanual.io/)

*[https://pythonbytes.fm/episodes/show/174/happy-developers-use-python-3](https://pythonbytes.fm/episodes/show/174/happy-developers-use-python-3)*

Data validation and settings management using python type annotations.

## [Dacite](https://github.com/konradhalas/dacite)

*[https://pythonbytes.fm/episodes/show/174/happy-developers-use-python-3](https://pythonbytes.fm/episodes/show/174/happy-developers-use-python-3)*

Simplifies creation of data classes from dictionaries. Converting from dict to dataclass is trivial for trivial cases: `x = MyClass(**data_as_dict)`.

# Game Development

## [Panda3D](https://www.panda3d.org/)

*[https://pythonbytes.fm/episodes/show/116/so-you-want-python-in-a-3d-graphics-engine](https://pythonbytes.fm/episodes/show/116/so-you-want-python-in-a-3d-graphics-engine)*

`Panda3D` is an open-source, completely free-to-use engine for realtime 3D games, visualizations, simulations, experiments

[![Panda3D Example](https://img.youtube.com/vi/MYlBW0f4HhA/0.jpg)](https://www.youtube.com/watch?v=MYlBW0f4HhA "Panda3D Example")

# Interesting Tidbits

* Using --prompt to name your virtualenv for easy identification later on is something I use widely now. [https://pythonbytes.fm/episodes/show/168/race-your-donkey-car-with-python](https://pythonbytes.fm/episodes/show/168/race-your-donkey-car-with-python)
* [Python Graph Gallery](https://python-graph-gallery.com/) is an amazing resource for examples of already made data visualisations.
* [Type hints for busy programmers](https://inventwithpython.com/blog/2019/11/24/type-hints-for-busy-python-programmers/) is a great resource for understanding what type hints are and why you should use them.
* [https://pythonbytes.fm/episodes/show/160/your-json-shall-be-streamed](https://pythonbytes.fm/episodes/show/160/your-json-shall-be-streamed)

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

[![IMAGE IF APPLICABLE]](link/to/package)
```
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Web Development](#web-development)
  - [Wagtail](#wagtail)
  - [Wooey](#wooey)
  - [Anvil](#anvil)
  - [Vue.py](#vuepy)
  - [fastpages](#fastpages)
- [Data Science](#data-science)
  - [D-Tale](#d-tale)
  - [Great Expectations](#great-expectations)
  - [PDF Plumber](#pdf-plumber)
  - [PyJanitor](#pyjanitor)
  - [Pandas Vet](#pandas-vet)
  - [NB2XLS](#nb2xls)
  - [pylightxl](#pylightxl)
  - [Streamlit](#streamlit)
  - [Mimesis](#mimesis)
  - [SideTable](#sidetable)
  - [Tabulate](#tabulate)
- [Data Visualization](#data-visualization)
  - [Pylustrator](#pylustrator)
  - [Chartify](#chartify)
  - [PandasBokeh](#pandasbokeh)
  - [Missingno](#missingno)
  - [HoloViz](#holoviz)
  - [Awesome Panel](#awesome-panel)
  - [Datapane](#datapane)
- [Machine Learning](#machine-learning)
  - [PyTorch](#pytorch)
  - [Yellow Brick](#yellow-brick)
  - [Thinc](#thinc)
- [Databases](#databases)
  - [GeoAlchemy](#geoalchemy)
  - [BeeKeeper Studio Open Source SQL Editor and Database Manager](#beekeeper-studio-open-source-sql-editor-and-database-manager)
- [Command Line Interfaces (CLIs)](#command-line-interfaces-clis)
  - [Python Fire](#python-fire)
  - [Clize](#clize)
  - [Typer](#typer)
  - [Rich](#rich)
- [Graphical User Interfaces (GUIs)](#graphical-user-interfaces-guis)
  - [Gooey](#gooey)
  - [Eel GUI](#eel-gui)
  - [PySimpleGUI](#pysimplegui)
  - [QUICK](#quick)
- [Python Development](#python-development)
  - [Attrs](#attrs)
  - [PyOxidizer](#pyoxidizer)
  - [Python Date Utils](#python-date-utils)
  - [Pycel](#pycel)
  - [PyDantic](#pydantic)
  - [Dacite](#dacite)
  - [wemake-python-styleguide](#wemake-python-styleguide)
  - [NBDev](#nbdev)
  - [Hypothesis](#hypothesis)
  - [Safer](#safer)
  - [Codespell](#codespell)
  - [Interrogate](#interrogate)
  - [Alive-Progress](#alive-progress)
  - [Unsync](#unsync)
  - [Pylance](#pylance)
- [Game Development](#game-development)
  - [Panda3D](#panda3d)
- [Interesting Tidbits](#interesting-tidbits)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# Web Development

## [Wagtail](https://wagtail.io/)

*[https://pythonbytes.fm/episodes/show/70/have-you-seen-my-log-it-s-cute](https://pythonbytes.fm/episodes/show/70/have-you-seen-my-log-it-s-cute)*

`Wagtail` is a content management system (CMS) (like Wordpress), written in `Python`, based off `Django`.

[Gallery of sites made with `wagtail`](https://madewithwagtail.org/)

## [Wooey](https://github.com/wooey/Wooey)

*[https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis](https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis)*

A `Django` app that creates automatic web UIs for `Python` scripts.

Live example at: [https://wooey.herokuapp.com/](https://wooey.herokuapp.com/)

[![Wooey Example](https://jackmckew.dev/img/wooey-example.png)](https://github.com/wooey/Wooey)

## [Anvil](https://anvil.works/)

*[https://pythonbytes.fm/episodes/show/106/fluent-query-apis-on-python-collections](https://pythonbytes.fm/episodes/show/106/fluent-query-apis-on-python-collections)*

Full stack web apps with nothing but `Python`.

## [Vue.py](https://github.com/stefanhoelzl/vue.py)

*[https://pythonbytes.fm/episodes/show/140/becoming-a-10x-developer-sorta](https://pythonbytes.fm/episodes/show/140/becoming-a-10x-developer-sorta)*

use `Vue.js` with pure `Python`

`vue.py` provides `Python` bindings for `Vue.js`. It uses `brython` to run `Python` in the browser.

Live example at: [https://stefanhoelzl.github.io/vue.py/examples/todo_mvc/](https://stefanhoelzl.github.io/vue.py/examples/todo_mvc/)

[![Vue.py Example](https://raw.githubusercontent.com/stefanhoelzl/vue.py/gh-pages/examples/todo_mvc/screenshot.png)](https://github.com/stefanhoelzl/vue.py)

## [fastpages](https://github.com/fastai/fastpages)

*<https://pythonbytes.fm/episodes/show/183/need-a-beautiful-database-editor-look-to-the-bees>*

An easy to use blogging platform, with enhanced support for Jupyter Notebooks.

- Uses GitHub actions to Jekyll blog posts on GitHub Pages.
- Create posts with code, output of code, formatted text, directory from Jupyter Notebooks.
- Altair interactive visualizations
- Collapsible code cells that can be open or closed by default.

![fastpages](https://raw.githubusercontent.com/fastai/fastpages/master/images/diagram.png)

# Data Science

## [D-Tale](https://github.com/man-group/dtale)

*[https://pythonbytes.fm/episodes/show/169/jupyter-notebooks-natively-on-your-ipad](https://pythonbytes.fm/episodes/show/169/jupyter-notebooks-natively-on-your-ipad)*

`D-Tale` is a Flask/React client for visualizing pandas data structures. [Live Demo](http://alphatechadmin.pythonanywhere.com/)

[![D-Tale Screenshots](https://raw.githubusercontent.com/aschonfeld/dtale-media/master/images/tiled/Tiled_screenshots.png)](https://github.com/man-group/dtale)

Why the Deets?

- Integrates easily into any python console or jupyter notebook
- Works with Google Colab & Kaggle
- Quickly explore large dataframes with our grid using sorting, filtering & show/hide/move columns
- Browse column information & statistics with "Describe"
- View correlation matrices
- Quick histograms, value counts & category breakdowns using "Column Analysis"
- Easy chart builder built on top of plotly/dash (export your charts to take them on the go as well :smile:)

## [Great Expectations](https://great-expectations.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/115/dataclass-csv-reader-and-nina-drops-by](https://pythonbytes.fm/episodes/show/115/dataclass-csv-reader-and-nina-drops-by)*

`Great Expectations` is a leading tool for validating, documenting, and profiling, your data to maintain quality and improve communication between teams.

## [PDF Plumber](https://github.com/jsvine/pdfplumber)

*[https://pythonbytes.fm/episodes/show/26/how-have-you-automated-your-life-or-cli-with-python](https://pythonbytes.fm/episodes/show/26/how-have-you-automated-your-life-or-cli-with-python)*

Plumb a PDF for detailed information about each char, rectangle, line, et cetera — and easily extract text and tables.

[![PDF Plumb Example](https://raw.githubusercontent.com/jsvine/pdfplumber/master/examples/screenshots/visual-debugging-in-jupyter.png)](https://github.com/jsvine/pdfplumber)

## [PyJanitor](https://pyjanitor.readthedocs.io/)

*[https://pythonbytes.fm/episodes/show/108/spilled-data-call-the-pyjanitor](https://pythonbytes.fm/episodes/show/108/spilled-data-call-the-pyjanitor)*

`pyjanitor` is a project that extends Pandas with a verb-based API, providing convenient data cleaning routines for repetitive tasks.

## [Pandas Vet](https://github.com/deppen8/pandas-vet)

*[https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod](https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod)*

`pandas-vet` is a plugin for `flake8` that provides opinionated linting for pandas code.

## [NB2XLS](https://github.com/ideonate/nb2xls)

*[https://github.com/ideonate/nb2xls](https://github.com/ideonate/nb2xls)*

Convert `Jupyter` notebooks to Excel Spreadsheets (xlsx), through a new 'Download As' option or via `nbconvert` on the command line.

[![NB2XLS Preview](https://raw.githubusercontent.com/ideonate/nb2xls/master/screenshots/Jupyter2Excel.png)](https://github.com/ideonate/nb2xls)

## [pylightxl](https://github.com/PydPiper/pylightxl)

*[https://pythonbytes.fm/episodes/show/165/ranges-as-dictionary-keys-oh-my](https://pythonbytes.fm/episodes/show/165/ranges-as-dictionary-keys-oh-my)*

A light weight, zero dependency (only standard libs used), to the point (no bells and whistles) Microsoft Excel reader/writer python 2.7-3+ library.

[![Example Code](https://github.com/PydPiper/pylightxl/blob/master/doc/source/_static/readme_demo.gif)](https://github.com/PydPiper/pylightxl)

Why pylightxl over pandas/openpyxl

- (compatibility +1, small lib +1) pylightxl has no external dependencies (only uses python built-in standard libs).
(compatibility +1) pylightxl was written to be compatible for python 2.7-3+ under one single pylightxl version. It does not impose rules on users to switch versions.
- (small lib +1) pylightxl was written to simply read/write, thereby making the library small without any bells or whistles which makes it easy to compile with PyInstaller and other packagers
- (user friendly +1) pylightxl was written to be as pythonic and easy to use as possible. Core developers actively survey Stack Overflow questions on working with excel files to tailor the API for most common problems.
- (see xlrd before pylightxl) Note that the xlrd library is very similar in values to pylightxl, but with much more functionality! Please take a look at xlrd to see if it is a good fit for your project. So why pick pylightxl over xlrd that has much more to offer? Currently, xlrd does not have any active developers. Pylightxl is a new library aimed to help solve current excel data issues (as surveyed by Stack Overflow), please submit your suggestions to help improve this library together.

## [Streamlit](https://www.streamlit.io/)

*<https://pythonbytes.fm/episodes/show/181/it-s-time-to-interrogate-your-python-code>*

The fastest way to build data apps.

Streamlit’s open-source app framework is the easiest way for data scientists and machine learning engineers to create beautiful, performant apps in only a few hours!  All in pure Python. All for free.

[![Streamlit Demo](https://camo.githubusercontent.com/5ae1dcfd188be26bbb0648fb62e9d6d593dbb6f5/68747470733a2f2f617773312e646973636f757273652d63646e2e636f6d2f7374616e6461726431302f75706c6f6164732f73747265616d6c69742f6f726967696e616c2f31582f323932653938356637663735656637626566386332376235383939663731663736636435373765302e676966)](https://www.streamlit.io/)

## [Mimesis](https://mimesis.name/)

Mimesis is fast and extremely easy to use Python package, which helps generate big volumes of fake data for a variety of purposes in a variety of languages.

The fake data can be particularly useful during software development and testing. For example, it could be used to populate a testing database, create beautiful JSON and XML files, anonymize data taken from a production service and etc.

## [SideTable](https://pbpython.com/sidetable.html)

*<https://pythonbytes.fm/episodes/show/186/the-treebeard-will-guard-your-notebook>*

Makes it easy to build a frequency table and simple summary of missing values in a DataFrame. A useful tool when starting data exploration on a new data set
At its core, `sidetable` is a super-charged version of pandas `value_counts` with a little bit of `crosstab` mixed in. With `sidetable` is imported, you have a new accessor on all your DataFrames - `stb` that you can use to build summary tables.

[![SideTable Preview](https://pbpython.com/images/stb_table_header.png)](https://pbpython.com/sidetable.html)

## [Tabulate](https://github.com/astanin/python-tabulate)

*<https://pythonbytes.fm/episodes/show/186/the-treebeard-will-guard-your-notebook>*

Pretty-print tabular data in Python, a library and a command-line utility.

``` python
from tabulate import tabulate

table = [["Sun",696000,1989100000],
          ["Earth",6371,5973.6],
          ["Moon",1737,73.5],
          ["Mars",3390,641.85]]
headers=["Planet","R (km)", "mass (x 10^29 kg)"]
table_str = tabulate(table, headers=headers)
print(table_str)
```

``` bash
    Planet      R (km)    mass (x 10^29 kg)
    --------  --------  -------------------
    Sun         696000           1.9891e+09
    Earth         6371        5973.6
    Moon          1737          73.5
    Mars          3390         641.85
```

# Data Visualization

## [Pylustrator](https://pylustrator.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/137/advanced-python-testing-and-big-time-diffs](https://pythonbytes.fm/episodes/show/137/advanced-python-testing-and-big-time-diffs)*

`Pylustrator` offers an interactive interface to find the best way to present your data in a figure for publication. Added formatting an styling can be saved by automatically generated code. To compose multiple figures to panels, pylustrator can compose different subfigures to a single figure.

[![pylustrator demonstration](https://img.youtube.com/vi/xXPI4LLrNuM/0.jpg)](https://www.youtube.com/watch?v=xXPI4LLrNuM "pylustrator demonstration")

## [Chartify](https://github.com/spotify/chartify)

*[https://pythonbytes.fm/episodes/show/109/cpython-byte-code-explorer](https://pythonbytes.fm/episodes/show/109/cpython-byte-code-explorer)*

`Chartify` is a `Python` library that makes it easy for data scientists to create charts.

[![Chartify Example](https://raw.githubusercontent.com/spotify/chartify/master/docs/_static/chartify1.png)](https://github.com/spotify/chartify)

## [PandasBokeh](https://github.com/PatrikHlobil/Pandas-Bokeh)

*<https://pythonbytes.fm/episodes/show/178/build-a-pypi-package-from-a-jupyter-notebook>*

Pandas-Bokeh provides a Bokeh plotting backend for Pandas, GeoPandas and Pyspark DataFrames, similar to the already existing Visualization feature of Pandas. Importing the library adds a complementary plotting method `plot_bokeh()` on DataFrames and Series.

With Pandas-Bokeh, creating stunning, interactive, HTML-based visualization is as easy as calling:

``` python
df.plot_bokeh()
```

[![PandasBokeh Example](https://raw.githubusercontent.com/PatrikHlobil/Pandas-Bokeh/master/docs/Images/Startimage.gif)](https://github.com/PatrikHlobil/Pandas-Bokeh)

## [Missingno](https://github.com/ResidentMario/missingno)

*<https://pythonbytes.fm/episodes/show/179/guido-van-rossum-drops-in-on-python-bytes>*

Messy data sets? Missing values? `missingno` provides a small tool set of flexible and easy-to-use missing data visualizations and utilities that allows you to get a quick visual summary of the completeness (or lack thereof) of your data set. Just pip install `missingno` to get started.

[![Missingno Example](https://camo.githubusercontent.com/d59ba9e511fd42dd078b8c8829d3de3f6a7e1585/68747470733a2f2f692e696d6775722e636f6d2f675775584b45722e706e67)](https://github.com/ResidentMario/missingno)

## [HoloViz](https://holoviz.org/)

*<https://pythonbytes.fm/episodes/show/181/it-s-time-to-interrogate-your-python-code>*

HoloViz is a coordinated effort to make browser-based data visualization in Python easier to use, easier to learn, and more powerful.

[![Holoviz Example](https://holoviz.org/assets/earthquakes.png)](https://holoviz.org/tutorial/index.html)

## [Awesome Panel](https://awesome-panel.org)

*<https://pythonbytes.fm/episodes/show/181/it-s-time-to-interrogate-your-python-code>*

Panel is announced as a high-level app and dashboarding solution for Python. I think the terms powerful and full of features should be added to that.

The purpose of the Awesome Panel Project is to share knowledge on how Awesome Panel is and can become.

[![Awesome Panel Example](https://raw.githubusercontent.com/MarcSkovMadsen/awesome-panel/master/assets/images/awesome-panel-full-branded.gif)](https://awesome-panel.org)

## [Datapane](https://www.datapane.com/)

*<https://pythonbytes.fm/episodes/show/189/what-does-str.strip-do-are-you-sure>*

Datapane is an open source framework which makes it easy to turn scripts and notebooks into interactive reports.

Examples gallery at: <https://www.datapane.com/gallery/>

# Machine Learning

## [PyTorch](https://github.com/pytorch/pytorch)

*[https://pythonbytes.fm/episodes/show/80/dan-bader-drops-by-and-we-found-30-new-python-projects](https://pythonbytes.fm/episodes/show/80/dan-bader-drops-by-and-we-found-30-new-python-projects)*

Tensors and Dynamic neural networks in `Python` with strong GPU acceleration

## [Yellow Brick](https://www.scikit-yb.org/en/latest/)

*[https://pythonbytes.fm/episodes/show/74/contributing-to-open-source-effectively](https://pythonbytes.fm/episodes/show/74/contributing-to-open-source-effectively)*

`Yellowbrick` extends the `Scikit-Learn` API to make model selection and hyperparameter tuning easier. Under the hood, it’s using `Matplotlib`.

[![Yellow Brick Preview](https://www.scikit-yb.org/en/latest/_images/banner.png)](https://www.scikit-yb.org/en/latest/)

## [Thinc](https://thinc.ai/)

*[https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod](https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod)*

A refreshing functional take on deep learning, compatible with your favorite libraries.
From the makers of `spaCy`, `Prodigy` & `FastAPI`

# Databases

## [GeoAlchemy](https://geoalchemy-2.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/77/you-don-t-have-to-be-a-workaholic-to-win](https://pythonbytes.fm/episodes/show/77/you-don-t-have-to-be-a-workaholic-to-win)*

Using `SQLAlchemy` with Spatial Databases.

`GeoAlchemy 2` provides extensions to `SQLAlchemy` for working with spatial databases.

`GeoAlchemy 2` focuses on `PostGIS`. `PostGIS 1.5` and `PostGIS 2` are supported.

## [BeeKeeper Studio Open Source SQL Editor and Database Manager](https://www.beekeeperstudio.io/)

Use Beekeeper Studio to query and manage your relational databases, like MySQL, Postgres, SQLite, and SQL Server. Runs on all the things (Windows, Linux, macOS).

Features:

- Auto complete SQL query editor with syntax highlighting
- Tabbed interface, so you can multitask
- Sort and filter table data to find just what you need
- Sensible keyboard-shortcuts
- Save queries for later
- Query run-history, so you can find that one query you got working 3 days ago
- Default dark theme

![Beekeeper Studio](https://www.beekeeperstudio.io/assets/img/screenshots/main-dark-9e3099be326f5ba8f2389545e6811e9dda80ae842f210450385226f7cf3cc817.png)

# Command Line Interfaces (CLIs)

## [Python Fire](https://github.com/google/python-fire)

*[https://pythonbytes.fm/episodes/show/17/google-s-python-is-on-fire-and-simon-says-you-have-cpu-load-pythonically](https://pythonbytes.fm/episodes/show/17/google-s-python-is-on-fire-and-simon-says-you-have-cpu-load-pythonically)*

`Python Fire` is a library for automatically generating command line interfaces (CLIs) from absolutely any `Python` object.

## [Clize](https://clize.readthedocs.io/en/stable/)

*[https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod](https://pythonbytes.fm/episodes/show/167/cheating-at-kaggle-and-uwsgi-in-prod)*

`Clize` is an argument parser for `Python`. You can use `Clize` as an alternative to `argparse` if you want an even easier way to create command-line interfaces.

## [Typer](https://typer.tiangolo.com/)

*[https://pythonbytes.fm/episodes/show/164/use-type-hints-to-build-your-next-cli-app](https://pythonbytes.fm/episodes/show/164/use-type-hints-to-build-your-next-cli-app)*

`Typer`, build great CLIs. Easy to code. Based on `Python` type hints.

## [Rich](https://github.com/willmcgugan/rich)

*[https://pythonbytes.fm/episodes/show/176/how-python-implements-super-long-integers](https://pythonbytes.fm/episodes/show/176/how-python-implements-super-long-integers)*

Rich is a Python library for rich text and beautiful formatting in the terminal.

[![Rich Example](https://github.com/willmcgugan/rich/raw/master/imgs/features.png)](https://github.com/willmcgugan/rich)

# Graphical User Interfaces (GUIs)

## [Gooey](https://github.com/chriskiehl/Gooey)

*[https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis](https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis)*

I personally love `Gooey` and have it installed in almost every project lately. `Gooey` turns (almost) any `Python` command line program into a full GUI application with one line.

I have also done a tutorial blog post on Gooey as well at: [https://jackmckew.dev/making-executable-guis-with-python-gooey-pyinstaller.html](https://jackmckew.dev/making-executable-guis-with-python-gooey-pyinstaller.html#making-executable-guis-with-python-gooey-pyinstaller)

[![Gooey Example](https://raw.githubusercontent.com/chriskiehl/GooeyImages/images/readme-images/1-0-3-title-card.png)](https://github.com/chriskiehl/Gooey)

## [Eel GUI](https://github.com/samuelhwilliams/Eel)

*[https://pythonbytes.fm/episodes/show/61/on-being-a-senior-engineer](https://pythonbytes.fm/episodes/show/61/on-being-a-senior-engineer)*

`Eel` is a little `Python` library for making simple Electron-like offline HTML/JS GUI apps, with full access to `Python` capabilities and libraries.

[![Eel Demo](https://raw.githubusercontent.com/samuelhwilliams/Eel/master/examples/04%20-%20file_access/Screenshot.png)](https://github.com/samuelhwilliams/Eel)

## [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI)

*[https://pythonbytes.fm/episodes/show/90/a-django-async-roadmap](https://pythonbytes.fm/episodes/show/90/a-django-async-roadmap)*

*[https://pythonbytes.fm/episodes/show/104/api-evolution-the-right-way](https://pythonbytes.fm/episodes/show/104/api-evolution-the-right-way)*

PySimpleGUI enables anyone with a week of PySimpleGUI education or more to develop an entirely custom desktop GUI application.  The underlying GUI frameworks supported include tkinter, Qt, WxPython and Remi.  PySimpleGUI code can be run on any of these underlying frameworks with little or often no modification to the source code.

Unlike other simplified GUI packages, PySimpleGUI has a rich palette of widgets that are not dumbed down and can be assembled into any configuration desired, resulting in applications that look and operate as if written directly in tkinter, Qt, etc.  Simple defines the ease of writing the programs, not the class of problems that are capable of being solved. 100's of demo programs are provided to give programmers a jump start on integrating with other packages such as OpenCV, Matplotlib.  There are over 500 GitHub projects currently using PySimpleGUI.

A couple recent projects include:

A series of Rainmeter-style "Desktop Widgets": <https://github.com/PySimpleGUI/PySimpleGUI-Widgets>

[![PSG CPU Cores Scrolling](https://user-images.githubusercontent.com/46163555/72114378-52830400-3311-11ea-8584-32bde5c265db.gif)](https://github.com/PySimpleGUI/PySimpleGUI-Widgets)

A photo and video colorizer: <https://github.com/PySimpleGUI/PySimpleGUI-Photo-Colorizer>

[![SNAG-0628](https://user-images.githubusercontent.com/46163555/71523943-4327a380-2899-11ea-95b7-a2892f611109.jpg)](https://github.com/PySimpleGUI/PySimpleGUI-Photo-Colorizer)

## [QUICK](https://github.com/szsdk/quick)

*[https://pythonbytes.fm/episodes/show/166/misunderstanding-software-clocks-and-time](https://pythonbytes.fm/episodes/show/166/misunderstanding-software-clocks-and-time)*

A real quick GUI generator for `click`. Inspired by `Gooey`, the GUI generator for classical `Python` `argparse`-based command line programs.

[![QUICK Example](https://user-images.githubusercontent.com/6657200/38025934-bf93013c-32bc-11e8-8d12-91411b28946e.png)](https://github.com/szsdk/quick)

# Python Development

## [Attrs](https://github.com/python-attrs/attrs)

*[https://pythonbytes.fm/episodes/show/11/django-2.0-is-dropping-python-2-entirely-pipenv-for-profile-functionality-and-pythonic-home-automation](https://pythonbytes.fm/episodes/show/11/django-2.0-is-dropping-python-2-entirely-pipenv-for-profile-functionality-and-pythonic-home-automation)*

`Python` Classes Without Boilerplate

## [PyOxidizer](https://github.com/indygreg/PyOxidizer)

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

## [wemake-python-styleguide](https://github.com/wemake-services/wemake-python-styleguide)

*[https://pythonbytes.fm/episodes/show/155/guido-van-rossum-retires](https://pythonbytes.fm/episodes/show/155/guido-van-rossum-retires)*

The strictest and most opinionated python linter ever. wemake-python-styleguide is actually a flake8 plugin with some other plugins as dependencies.

## [NBDev](https://github.com/fastai/nbdev)

*<https://pythonbytes.fm/episodes/show/178/build-a-pypi-package-from-a-jupyter-notebook>*

`nbdev` is a library that allows you to fully develop a library in Jupyter Notebooks, putting all your code, tests and documentation in one place. That is: you now have a true literate programming environment, as envisioned by Donald Knuth back in 1983!

Using the interactive environment, you can easily debug and refactor your code. Add #export flags to the cells that define the functions you want to include in your python modules. Here, for instance, is how combined_cos is defined and documented in the `fastai` library:

[![NBDev Example](https://raw.githubusercontent.com/fastai/nbdev/master/nbs/images/export_example.png)](https://github.com/fastai/nbdev)

- Creates Python packages out of a notebook
- Creates documentation from the notebook
- Solves the git perma-conflict issues with git pre-commit hooks
- Use #export to declare a cell should become a function in the package
- Manages the boilerplate issues for creating Python packages (setup.py, etc)
- Makes testing possible inside notebooks
- Navigate and edit your code in a standard text editor or IDE, and sync any changes automatically back into your notebooks (reverse basically)

## [Hypothesis](https://hypothesis.readthedocs.io/en/latest/)

*<https://pythonbytes.fm/episodes/show/30/you-are-not-google-and-other-ruminations>*

Hypothesis is a Python library for creating unit tests which are simpler to write and more powerful when run, finding edge cases in your code you wouldn’t have thought to look for. It is stable, powerful and easy to add to any existing test suite.

It works by letting you write tests that assert that something should be true for every case, not just the ones you happen to think of.

## [Safer](https://github.com/rec/safer)

*<https://pythonbytes.fm/episodes/show/180/transactional-file-io-with-python-and-safer>*

safer: a safer file opener

No more partial writes or corruption! For file streams, sockets or any callable.

``` python
# dangerous
with open(filename, 'w') as fp:
    json.dump(data, fp)
    # If an exception is raised, the file is empty or partly written

# safer
with safer.open(filename, 'w') as fp:
    json.dump(data, fp)
    # If an exception is raised, the file is unchanged.
```

## [Codespell](https://github.com/codespell-project/codespell)

*<https://pythonbytes.fm/episodes/show/180/transactional-file-io-with-python-and-safer>*

Fix common misspellings in text files. It's designed primarily for checking misspelled words in source code, but it can be used with other files as well.

## [Interrogate](https://pypi.org/project/interrogate/)

*<https://pythonbytes.fm/episodes/show/181/it-s-time-to-interrogate-your-python-code>*

`interrogate` checks your code base for missing docstrings.

Documentation should be as important as code itself. And it should live within code. Python standardized docstrings, allowing for developers to navigate libraries as simply as calling `help()` on objects, and with powerful tools like Sphinx, pydoc, and Docutils to automatically generate HTML, LaTeX, PDFs, etc.

Enter: `interrogate`.

`interrogate` will tell you which methods, functions, classes, and modules have docstrings, and which do not. Use interrogate to:

- Get an understanding of how well your code is documented;
- Add it to CI/CD checks to enforce documentation on newly-added code;
- Assess a new code base for (one aspect of) code quality and maintainability.

## [Alive-Progress](https://github.com/rsalmei/alive-progress)

*<https://pythonbytes.fm/episodes/show/181/it-s-time-to-interrogate-your-python-code>*

A new kind of Progress Bar, with real-time throughput, eta and very cool animations!

``` python
from alive_progress import alive_bar
items = range(1000)                  # retrieve your set of items
with alive_bar(len(items)) as bar:   # declare your expected total
    for item in items:               # iterate as usual
        # process each item
        bar()                        # call after consuming one item
```

[![Alive-Progress Example](https://raw.githubusercontent.com/rsalmei/alive-progress/master/img/alive-demo.gif)](https://github.com/rsalmei/alive-progress)

## [Unsync](https://github.com/alex-sherman/unsync)

*<https://pythonbytes.fm/episodes/show/188/will-there-be-a-switch-in-python-the-language>*

Unsync makes functions asynchronous and parallelized with a single decorator `@unsync`.

A simple sleeping example with `asyncio`:

``` python
async def sync_async():
    await asyncio.sleep(0.1)
    return 'I hate event loops'

result = asyncio.run(sync_async())
print(result)
```

Same example with `unsync`:

``` python
@unsync
async def unsync_async():
    await asyncio.sleep(0.1)
    return 'I like decorators'

print(unsync_async().result())
```

> [Tutorial — making a trading bot asynchronous using Python’s “unsync” library](https://medium.com/@MattGosden/tutorial-using-pythons-unsync-library-to-make-an-asynchronous-trading-bot-9ee2ae881272)

## [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)

*<https://pythonbytes.fm/episodes/show/190/you-will-now-be-notified-if-the-python-zipper-is-broken>*

Pylance has the ability to supercharge your Python IntelliSense experience with rich type information, helping you write better code faster.

- Features docstring automation, Signature help, parameter suggestions, code completion (better than existing)
- Supports auto-imports, if you start typing from a namespace, like a standard library module, it will add the import for you.
- Go to Reference, Go to Implementation shortcuts
- Uses the pyright type checker (an alternative to MyPy (Dropbox), Pyre (Facebook) and Pytype (Google))
- If you have pyright extension installed, remove it first!

[![Pylance GIF](https://raw.githubusercontent.com/microsoft/pylance-release/master/screencap.gif)](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)

# Game Development

## [Panda3D](https://www.panda3d.org/)

*[https://pythonbytes.fm/episodes/show/116/so-you-want-python-in-a-3d-graphics-engine](https://pythonbytes.fm/episodes/show/116/so-you-want-python-in-a-3d-graphics-engine)*

`Panda3D` is an open-source, completely free-to-use engine for real time 3D games, visualizations, simulations, experiments

[![Panda3D Example](https://img.youtube.com/vi/MYlBW0f4HhA/0.jpg)](https://www.youtube.com/watch?v=MYlBW0f4HhA "Panda3D Example")

# Interesting Tidbits

- Using --prompt to name your virtualenv for easy identification later on is something I use widely now. [https://pythonbytes.fm/episodes/show/168/race-your-donkey-car-with-python](https://pythonbytes.fm/episodes/show/168/race-your-donkey-car-with-python)
- [Python Graph Gallery](https://python-graph-gallery.com/) is an amazing resource for examples of already made data visualizations.
- [Type hints for busy programmers](https://inventwithpython.com/blog/2019/11/24/type-hints-for-busy-python-programmers/) is a great resource for understanding what type hints are and why you should use them.
- [https://pythonbytes.fm/episodes/show/160/your-json-shall-be-streamed](https://pythonbytes.fm/episodes/show/160/your-json-shall-be-streamed)
- This list was mentioned in Episode #176 <https://pythonbytes.fm/episodes/show/176/how-python-implements-super-long-integers>
- Fruit Salad scrum estimation scale, use fruit analogies rather than estimating time for tasks <https://fberriman.com/2020/01/22/fruit-salad-a-scrum-estimation-scale/>
- How to find the difference between two times with timedeltas <https://pythonbytes.fm/episodes/show/190/you-will-now-be-notified-if-the-python-zipper-is-broken>.
  - ``` python
    weeks = dt / timedelta(days=7)
    hours = dt / timedelta(hours=1)
    ```
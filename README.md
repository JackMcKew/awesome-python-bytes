# awesome-python-bytes
😎 🐍 Awesome lists about Python Bytes https://pythonbytes.fm/

[Python Bytes](https://pythonbytes.fm/) is a weekly, short & sweet podcast by [Michael Kennedy](https://twitter.com/mkennedy) & [Brian Okken](https://twitter.com/brianokken). After having the podcast recommended numerous times by friends & colleagues, I decided to download every episode thus far on the 14th of September 2019. Over the next 174 days, whenever I was commuting, I'd listen to 171 episodes of Python bytes, learnt a stack of new things and found new amazing python packages.

![Python Bytes Image](https://pythonbytes.fm/static/img/banner_750.png)

This post is intended to list out the packages I'd noted down & their application. Total disclaimer, I haven't tried out all of these packages personally and I'm certain there is a plethora of other packages mentioned that I have not captured here, please reach out if theres anything to add!

I've attempted to sort these into a directory of sorts pending on what you're interested in looking at, and whether I found out about them through [Python Bytes](https://pythonbytes.fm/) or elsewhere (they will have a link to the episode if directly from [Python Bytes](https://pythonbytes.fm/)).

<!-- omit in toc -->
# Table Of Contents

- [awesome-python-bytes](#awesome-python-bytes)
- [Web Development](#web-development)
  - [Wagtail](#wagtail)
  - [Wooey](#wooey)
  - [Anvil](#anvil)
  - [Vue.py](#vuepy)
  - [GeoDjango](#geodjango)
  - [Django Bootcamp](#django-bootcamp)
- [Security](#security)
  - [Osmedeus](#osmedeus)
  - [Mongo Audit](#mongo-audit)
- [Data Science](#data-science)
  - [Great Expectations](#great-expectations)
  - [PDF Plumber](#pdf-plumber)
  - [PyJanitor](#pyjanitor)
  - [Pandas Vet](#pandas-vet)
  - [NB2XLS](#nb2xls)
- [Data Visualisation](#data-visualisation)
  - [Pylustrator](#pylustrator)
  - [Chartify](#chartify)
  - [Panel Holoviz](#panel-holoviz)
  - [Cartoframes](#cartoframes)
  - [Sand Dance](#sand-dance)
- [Machine Learning](#machine-learning)
  - [PyTorch](#pytorch)
  - [Yellow Brick](#yellow-brick)
  - [Thinc](#thinc)
  - [Keras Gym](#keras-gym)
  - [Spinning up](#spinning-up)
  - [Jax](#jax)
  - [Gensim](#gensim)
- [Databases](#databases)
  - [GeoAlchemy](#geoalchemy)
  - [Sandman 2](#sandman-2)
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
  - [Doc Assemble](#doc-assemble)
- [Game Development](#game-development)
  - [Panda3D](#panda3d)
  - [PursuedPyBear](#pursuedpybear)
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

## [GeoDjango](https://docs.djangoproject.com/en/3.0/ref/contrib/gis/)

*[https://docs.djangoproject.com/en/3.0/ref/contrib/gis/](https://docs.djangoproject.com/en/3.0/ref/contrib/gis/)*
GeoDjango intends to be a world-class geographic Web framework. Its goal is to make it as easy as possible to build GIS Web applications and harness the power of spatially enabled data.

## [Django Bootcamp](https://github.com/vitorfs/bootcamp)

*[https://github.com/vitorfs/bootcamp](https://github.com/vitorfs/bootcamp)*
Bootcamp is an open source enterprise social network of open purpose, on which you can build for your own ends.
> Example at: [https://trybootcamp.vitorfs.com/](https://trybootcamp.vitorfs.com/)

# Security

## [Osmedeus](https://github.com/j3ssie/Osmedeus)

Fully automated offensive security framework for reconnaissance and vulnerability scanning
![Osmedeus](https://raw.githubusercontent.com/j3ssie/Osmedeus/master/imgs/osmedeus-architecture.png)

## [Mongo Audit](https://mongoaud.it/)

*[https://mongoaud.it/](https://mongoaud.it/)*
`mongoaudit` is an automated pentesting tool that lets you know if your `MongoDB` instances are properly secured

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

# Data Visualisation

## [Pylustrator](https://pylustrator.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/137/advanced-python-testing-and-big-time-diffs](https://pythonbytes.fm/episodes/show/137/advanced-python-testing-and-big-time-diffs)*

`Pylustrator` offers an interactive interface to find the best way to present your data in a figure for publication. Added formatting an styling can be saved by automatically generated code. To compose multiple figures to panels, pylustrator can compose different subfigures to a single figure.

[![pylustrator demonstration](https://img.youtube.com/vi/xXPI4LLrNuM/0.jpg)](https://www.youtube.com/watch?v=xXPI4LLrNuM "pylustrator demonstration")

## [Chartify](https://github.com/spotify/chartify)

*[https://pythonbytes.fm/episodes/show/109/cpython-byte-code-explorer](https://pythonbytes.fm/episodes/show/109/cpython-byte-code-explorer)*

`Chartify` is a `Python` library that makes it easy for data scientists to create charts.

![Chartify Example](https://raw.githubusercontent.com/spotify/chartify/master/docs/_static/chartify1.png)

## [Panel Holoviz](https://github.com/holoviz/panel)

`Panel` provides tools for easily composing widgets, plots, tables, and other viewable objects and controls into control panels, apps, and dashboards. Panel works with visualizations from `Bokeh`, `Matplotlib`, `HoloViews`, and other `Python` plotting libraries, making them instantly viewable either individually or when combined with interactive widgets that control them. Panel works equally well in `Jupyter` Notebooks, for creating quick data-exploration tools, or as standalone deployed apps and dashboards, and allows you to easily switch between those contexts as needed.

Examples at: [https://panel.holoviz.org/](https://panel.holoviz.org/)

![Panel Example]({static img/panel-example.png})

## [Cartoframes](https://github.com/CartoDB/cartoframes)

A `Python` package for integrating CARTO maps, analysis, and data services into data science workflows.

`Python` data analysis workflows often rely on the de facto standards `pandas` and `Jupyter` notebooks. Integrating CARTO into this workflow saves data scientists time and energy by not having to export datasets as files or retain multiple copies of the data. Instead, CARTOframes give the ability to communicate reproducible analysis while providing the ability to gain from CARTO's services like hosted, dynamic or static maps and Data Observatory augmentation.

![Carto Example](https://carto.com/img/layout/homepage/use-cases/image1.621dbf2e.png)

## [Sand Dance](https://github.com/microsoft/SandDance)

*[https://github.com/microsoft/SandDance](https://github.com/microsoft/SandDance)*
Visually explore, understand, and present your data.
![Sand Dance Preview](https://user-images.githubusercontent.com/11507384/54236654-52d42800-44d1-11e9-859e-6c5d297a46d2.gif)

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

## [Spinning up](https://spinningup.openai.com/en/latest/)

*[https://spinningup.openai.com/en/latest/](https://spinningup.openai.com/en/latest/)*
Deep reinforcement learning educational resource

## [Jax](https://github.com/google/jax)

*[https://github.com/google/jax](https://github.com/google/jax)*
`JAX` is Autograd and XLA, brought together for high-performance machine learning research.
> Autograd & XLA are both optimisers, this package makes the applications run quicker

## [Gensim](https://radimrehurek.com/gensim/)

*[https://radimrehurek.com/gensim/](https://radimrehurek.com/gensim/)*
`Gensim` is an open-source library for unsupervised topic modeling and natural language processing, using modern statistical machine learning.

# Databases

## [GeoAlchemy](https://geoalchemy-2.readthedocs.io/en/latest/)

*[https://pythonbytes.fm/episodes/show/77/you-don-t-have-to-be-a-workaholic-to-win](https://pythonbytes.fm/episodes/show/77/you-don-t-have-to-be-a-workaholic-to-win)*
Using `SQLAlchemy` with Spatial Databases.

`GeoAlchemy 2` provides extensions to `SQLAlchemy` for working with spatial databases.

`GeoAlchemy 2` focuses on `PostGIS`. `PostGIS 1.5` and `PostGIS 2` are supported.

## [Sandman 2](https://github.com/jeffknupp/sandman2)

*[https://github.com/jeffknupp/sandman2](https://github.com/jeffknupp/sandman2)*
Automatically generate a RESTful API service for your legacy database. No code required!

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

# Guided User Interfaces (GUIs)

## [Gooey](https://github.com/chriskiehl/Gooey)

*[https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis](https://pythonbytes.fm/episodes/show/62/wooey-and-gooey-are-simple-python-guis)*

I personally love `Gooey` and have it installed in almost every project lately. `Gooey` turns (almost) any `Python` command line program into a full GUI application with one line.

I have also done a tutorial blog post on Gooey as well at: [https://jackmckew.dev/making-executable-guis-with-python-gooey-pyinstaller.html](https://jackmckew.dev/making-executable-guis-with-python-gooey-pyinstaller.html#making-executable-guis-with-python-gooey-pyinstaller)

![Gooey Example](https://raw.githubusercontent.com/chriskiehl/GooeyImages/images/readme-images/1-0-3-title-card.png)

## [Eel GUI](https://github.com/samuelhwilliams/Eel)

*[https://pythonbytes.fm/episodes/show/61/on-being-a-senior-engineer](https://pythonbytes.fm/episodes/show/61/on-being-a-senior-engineer)*
`Eel` is a little `Python` library for making simple Electron-like offline HTML/JS GUI apps, with full access to `Python` capabilities and libraries.

![Eel Demo](https://raw.githubusercontent.com/samuelhwilliams/Eel/master/examples/04%20-%20file_access/Screenshot.png)

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

## [Doc Assemble](https://docassemble.org/)

`docassemble` is a free, open-source expert system for guided interviews and document assembly. It provides a web site that conducts interviews with users. Based on the information gathered, the interviews can present users with documents in PDF, RTF, or DOCX format, which users can download or e-mail.

# Game Development

## [Panda3D](https://www.panda3d.org/)

*[https://pythonbytes.fm/episodes/show/116/so-you-want-python-in-a-3d-graphics-engine](https://pythonbytes.fm/episodes/show/116/so-you-want-python-in-a-3d-graphics-engine)*

`Panda3D` is an open-source, completely free-to-use engine for realtime 3D games, visualizations, simulations, experiments

[![Panda3D Example](https://img.youtube.com/vi/MYlBW0f4HhA/0.jpg)](https://www.youtube.com/watch?v=MYlBW0f4HhA "Panda3D Example")

## [PursuedPyBear](https://ppb.readthedocs.io/)

PursuedPyBear, also known as ppb, exists to be an educational resource. Most obviously used to teach computer science, it can be a useful tool for any topic that a simulation can be helpful.

# Interesting Tidbits

> There was one episode that referenced some amazing examples of GUIs built in Tkinter, unfortunately I have been unable to find it again. My note that I had down was `63 GUIs in Tkinter`.
> Using --prompt to name your virtualenv for easy identification later on is something I use widely now. [https://pythonbytes.fm/episodes/show/168/race-your-donkey-car-with-python](https://pythonbytes.fm/episodes/show/168/race-your-donkey-car-with-python)
> [Python Graph Gallery](https://python-graph-gallery.com/) is an amazing resource for examples of already made data visualisations.
> [Type hints for busy programmers](https://inventwithpython.com/blog/2019/11/24/type-hints-for-busy-python-programmers/) is a great resource for understanding what type hints are and why you should use them.
> [https://pythonbytes.fm/episodes/show/160/your-json-shall-be-streamed](https://pythonbytes.fm/episodes/show/160/your-json-shall-be-streamed)

# Installations and setup

Cheatsheet for installations and downloads related to the workshop. Mostly for helpful for Mac users. General Google searching should also do the trick.

1. [Install `python3`](#00)
1. [Install `nltk`](#01)
1. [Install `jupyter notebook`](#02)
1. [Download the course materials from `GitHub`](#03)
1. [Open the course materials using `Jupyter Notebook`](#04)

<hr>

## <span id="#00">Install python3</span>

If on Mac, open Terminal application, and run:

```bash
# Install
$ brew install python3

# Confirm installation (should say something like 'Python 3.7.6')
$ python3 --version
```

<hr>

## <span id="01">Install nltk library</span>

If on Mac, run the following in Terminal:

```bash
# Install
$ pip install --user -U nltk

# To test installation, first, open Python3
$ python3

# When prompted with '>>>', try importing nltk.
# If no error, then it's ready.
>>> import nltk

# To quit Python3:
>>> quit()
```

<hr>

## <span id="02">Install Jupyter notebook</span>

If on Mac, run the following in Terminal:

```bash
# Install
$ pip install notebook
```

<hr>

## <span id="03">Download the workshop materials from GitHub</span>

The workshop material is located at: https://github.com/annagarbier/dorkshop_nlp.

You can read along by just navigating to the site, or you can download the repository onto your own computer.

To download, go to the link. Click the green `Download or Clone` button in the top right. Then `Download ZIP`. This will download to wherever your computer directs downloads. Find the zipped file, and unzip it. It's now a local folder on your computer.

Or, if you're familiar with `git` command line tools:

```bash
$ git clone https://github.com/annagarbier/dorkshop_nlp.git
```

<hr>

## <span id="04">Open the workshop materials using Jupyter Notebook</span>

The workshop material is written in Python, shared with you as Jupyter Notebooks. Notebooks have files that end in `.ipynb`.

To interact with a notebook, open Terminal (if on Mac). Navigate to the notebook's parent folder. For exmaple, if the folder is in Downloads:

```bash
$ cd Downloads/dorkshop_nlp-master
```

From there, start Jupyter Notebook:

```bash
$ jupyter notebook
```

This should open a new tab in your default browser. Any changes you make in the interactive browser session will automatically be saved in your local files.

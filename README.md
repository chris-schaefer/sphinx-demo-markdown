# Sphinx markdown demo

The project is a simple demo for using [sphinx-doc](https://www.sphinx-doc.org/en/master/) with [markdown](https://en.wikipedia.org/wiki/Markdown) on top of [reStructuredText](https://en.wikipedia.org/wiki/ReStructuredText). The demo shows how to use custom header fonts and logo.  

## Install

Install packages into the active environment
```
pip install -r requirements.txt
```
Build the project
```
make html
```
Check the results
```
gio open build/html/index.html
```

## Automation

The `buildspec.yml` can be used in an AWS build pipeline.
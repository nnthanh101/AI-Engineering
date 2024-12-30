# runbooks documentation!

## Description

🌟 You can use CloudOps Automation Runbooks to quickly create SRE RunBooks for Runbook Automation and Cloud Infrastructure Management! 🌐

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://runbooks/data/`.
* `make sync_data_down` will use `aws s3 sync` to recursively sync files from `s3://runbooks/data/` to `data/`.

---

This site contains the project documentation for the `data-science` project that is a module used in the Data-Science courses. Its aim is to give you a framework to build your project documentation using Python, MkDocs, mkdocstrings, and the Material for MkDocs theme.

## Table Of Contents

The documentation follows the best practice for project documentation and consists of four separate parts:

### Python 101

1. [Tutorials](python/tutorials.md)
2. [How-To Guides](python/guides.md)
3. [Reference](python/reference.md)
4. [Explanation](python/explanation.md)

Quickly find what you're looking for depending on your use case by looking at the different pages.

### Math for Computer Science

> TBD




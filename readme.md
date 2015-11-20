SSW Training Content Contributor Guide

You've found the GitHub repository that houses the training content for the Angular Music Store.

## Contribute to SSW Training Materials

Thank you for your interest in Azure documentation!

* [Ways to contribute](#ways-to-contribute)
* [Repository organization](#repository-organization)
* [Use GitHub, Git, and this repository](#use-github-git-and-this-repository)
* [How to use markdown to format your topic](#how-to-use-markdown-to-format-your-topic)
* [More resources](#more-resources)

## Ways to contribute

You can contribute to [SSW Training Content](http://ssw.com/training/) in a few different ways:

* You can easily contribute to technical articles in the GitHub user interface. Either find the article in this repository, or visit the article on [http://ssw.com/training](http://ssw.com/training) and click the link in the article that goes to the GitHub source for the article.
* If you are making substantial changes to an existing article, adding or changing images, or contributing a new article, you need to fork this repository, install Git Bash, Markdown Pad, and learn some git commands.


## Repository organization

The content in the azure-content repository follows the organization of documentation on [Azure.Microsoft.com](http://azure.microsoft.com). This repository contains two root folders:

### \articles

The *\articles* folder contains the documentation articles formatted as markdown files with an *.md* extension. 

Articles in the root directory are published to Azure.Microsoft.com in the path *http://ssw.com/training/articles/{article-name-without-md}/*.

* **Article filenames:** See [our file naming guidance](./contributor-guide/file-names-and-locations.md).

Articles within their own service folder are published to Azure.Microsoft.com in the path
*http://ssw.com/training/articles/service-folder/{article-name-without-md}/*

* **Media subfolders:** The *\articles* folder contains the *\media* folder for root directory article media files, inside which are subfolders with the images for each article.  The service folders contain a separate media folder for the articles within each service folder. The article image folders are named identically to the article file, minus the *.md* file extension.

### \includes

You can create reusable content sections to be included in one or more articles. See [Custom extensions used in our technical content](./contributor-guide/custom-markdown-extensions.md).

### \markdown templates

This folder contains our standard markdown template with the basic markdown formatting you need for an article.

### \contributor-guide

This folder contains articles that are part of our contributors' guide.  

## Use GitHub, Git, and this repository

For information about how to contribute, how to use the GitHub UI to contribute small changes, and how to fork and clone the repository for more significant contributions, see [Install and set up tools for authoring in GitHub](./contributor-guide/tools-and-setup.md).

If you install GitBash and choose to work locally, the steps for creating a new local working branch, making changes, and submitting the changes back to the main branch are listed in [Git commands for creating a new article or updating an existing article](./contributor-guide/git-commands-for-master.md)

### Branches

We recommend that you create local working branches that target a specific scope of change. Each branch should be limited to a single concept/article both to streamline work flow and reduce the possibility of merge conflicts.  The following efforts are of the appropriate scope for a new branch:

* A new article (and associated images)
* Spelling and grammar edits on an article.
* Applying a single formatting change across a large set of articles (e.g. new copyright footer).

## How to use markdown to format your topic

All the articles in this repository use GitHub flavored markdown.  Here's a list of resources.

- [Markdown basics](https://help.github.com/articles/markdown-basics/)

- [Printable markdown cheatsheet](./contributor-guide/media/documents/markdown-cheatsheet.pdf?raw=true)

- For our list of markdown editors, see the [tools and setup topic](./contributor-guide/tools-and-setup.md#install-a-markdown-editor).

## Article metadata

Article metadata enables certain functionalities on the azure.microsoft.com web site, such as author attribution, contributor attribution, breadcrumbs, article descriptions, and SEO optimizations as well as reporting Microsoft uses to evaluate the performance of the content. So, the metadata is important! [Here's the guidance for making sure your metadata is done right](./contributor-guide/article-metadata.md).

## More resources

See the [index of our contributor's guide](./contributor-guide/contributor-guide-index.md) for all our guidance topics.
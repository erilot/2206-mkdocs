# About MkDocs

MkDocs is a documentation generator that builds complex HTML documentation using markdown source files. Because markdown files are just text, anybody can edit them, and they require no special tools to read or modify (Notepad or Textedit will do, especially for external contributors). They're also extremely easy to manage with version control systems like git.

MkDocs is not the only document generator that uses Markdown. We're using it in this class because it's intended for documentation (several others, like [Jekyll](https://jekyllrb.com/), are primarily blog engines that can be made to produce documentation). The concepts and skills you learn building documentation in MkDocs will be applicable using any markdown-based system, though.

!!! note
    MkDocs is a command line tool, which means it doesn’t have a GUI (graphical user interface). You’ll issue commands on the command line -- don’t worry if you’re not familiar with it; there aren’t many commands to learn, and we’ll cover all of them carefully.

## What an MkDocs Project Looks Like

An MkDocs project is composed of a single configuration file called `mkdocs.yml` and a folder called `docs`, which holds all of your documentation files. 

`mkdocs.yml` is a plain text file that describes pretty much everything about your document, including:

* The theme, or skin, for your documentation
* Any changeable theme settings, like colors or page navigation location
* MkDocs-specific settings
* And most importantly, the TOC of your documentation, including titles, pages, and their structure.

## Important MkDocs References

These references are all outstanding and will help tremendously in learning this process:

**MkDocs documentation**: [http://www.mkdocs.org/](http://www.mkdocs.org/)

**Markdown cheat sheet**: [https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

**Material Theme documentation**:  [http://squidfunk.github.io/mkdocs-material/](http://squidfunk.github.io/mkdocs-material/)

# Using MkDocs
The official documentation for MkDocs, and the Material theme, are both extremely useful. You should certainly explore the MkDocs documentation site at least; it tells you how to do virtually everything with MkDocs.
The MkDocs Material theme documentation covers some of the same ground, but adds the extras that MkDocs brings to the table -- a number of extensions like notes (those are called *admonitions* in MkDocs).

## About MkDocs

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




## MkDocs references:
MkDocs site and documentation:http://www.mkdocs.org/
Markdown cheat sheet: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
Material Theme documentation:  http://squidfunk.github.io/mkdocs-material/

Initialize a new project with MkDocs
Navigate into your working directory using Windows command line commands as described above.
Type mkdocs new {working directory name} and press enter. For example, if your project will be in a folder called my-test, type mkdocs new my-test and press enter.
If the project directory doesn’t exist already, it will be created.
The project will be initialized and a starter configuration file (mkdocs.yml) is created, along with a directory called docs and an example markdown file (index.md).
Open the New Project in Visual Studio Code
Open the file explorer (the top icon in the menu bar, or View > Explorer).
Open the new project folder: Go to File > Open Folder, and navigate to the folder you created above with the mkdocs new command.




 
 
 

Image references:

```md
![Alt Text](path/to/image/file.png)
```

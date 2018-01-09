# A Simple MkDocs Project

MkDocs, like Madcap Flare and Adobe Framemaker, builds its documents using a collection of smaller files instead of one monolithic file (like Word does). This takes a little getting used to if you haven't been exposed to it before, so we'll look at a simple example first.

Let's say we have a short document called **Seeing a Movie**, made for the few people who still leave the house to see movies in a theater. 

## Creating the Project

We'll start by creating a folder to hold our project files. I'll call it `seeing-a-movie/` (the trailing slash character is often used to indicate a folder; the folder name doesn't actually have a slash in it).

Inside this folder, MkDocs has two mandatory elements: a text file with a `.yml` extension (also called a "yaml" file) called `mkdocs.yml`, and a folder called `docs/`. `mkdocs.yml` is where all of your configuration settings will go; `docs/` will hold all of our document's files.

!!! tip
    Most of these steps can be done using Windows Explorer and a text editor like TextEdit or Notepad. I'm going to demonstrate how to do them inside Visual Studio Code, just to get familiar with the tool.

At the end of this, you'll have a directory structure that looks like this:

```
seeing-a-movie/
    docs/
    mkdocs.yml

```

**To create a new MkDocs project in Visual Studio Code:**

1. Open Visual Studio Code.
1. Click **File** > **Open Folder**
1. Navigate to the place on your drive you want to create the new project.
1. Click **New Folder**
1. Name the new folder something (in this example, `seeing-a-movie`).
1. Click **Ok** to create the folder.

Visual Studio Code will open, and the file explorer on the left will show a main folder called `SEEING-A-MOVIE`.

Now, let's create the `mkdocs.yml` file:

1. In the VSC file explorer, find the `SEEING-A-MOVIE` heading and click the **New File** icon (it's the first one that looks like a piece of paper).

    A new line will appear under the `SEEING-A-MOVIE` heading with a blinking cursor.

1. Type `mkdocs.yml` and press **Enter**.

    The file will be created and opened in the Visual Studio Code editor (it's blank right now, which is fine). We'll start entering information here in a minute.

1. 


Let's also say there are three main tasks associated with buying a movie ticket:

* Finding the movie
* Buying a ticket
* Going to the movie

We'll create a new markdown file for each one of these tasks, and save each one in the `docs\` folder. Let's call them *finding-the-movie.md*, *buying-a-ticket.md*, and *going-to-the-movie.md*.

!!! tip "Tip: Best practices for naming files"
    You can name markdown files anything you want, but it's best to make them descriptive of the content ("installation.md") rather than structural ("page2.md").

    It's also a best practice to use *only lower-case characters* and *no spaces* in filenames. Use dashes or underscores instead of spaces. Numbers are fine, though.

**To Create a New File in Visual Studio Code:**

1. Right-click the *docs* folder in the file explorer, and select **New File** from the dropdown list.

    A new line will appear under the `docs\` folder, with a blank text field for providing the filename.

1. Type the name of the file, *including the extension* (in this case that's `.md`), and press **Enter**.

    The file will be created and a blank editor tab will open.

Repeat that sequence three times, creating the three required files:

* finding-the-movie.md
* buying-a-ticket.md
* going-to-the-movie.md



Files in the `docs\` folder don't have to have any particular structure, but it usually helps to organize things a little unless it's a very small project.


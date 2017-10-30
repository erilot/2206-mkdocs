# A Simple MkDocs Project

MkDocs, like Madcap Flare and Adobe Framemaker, builds its documents using a collection of smaller files instead of one monolithic file (like Word does). This takes a little getting used to if you haven't been exposed to it before, so we'll look at a simple example first.

Let's say we have a short document called **Seeing a Movie**, made for the few people who still leave the house to see movies in a theater. There are three main tasks associated with buying a movie ticket:

* Finding the movie
* Buying a ticket
* Going to the movie

We'll create a separate file for each one of these tasks, and save each one in the `docs\` folder. Let's call them *finding-the-movie.md*, *buying-a-ticket.md*, and *going-to-the-movie.md*.

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


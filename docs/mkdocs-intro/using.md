
# Using MkDocs
The official documentation for MkDocs, and the Material theme, are both extremely useful. You should certainly explore the MkDocs documentation site at least; it tells you how to do virtually everything with MkDocs.
The MkDocs Material theme documentation covers some of the same ground, but adds the extras that MkDocs brings to the table -- a number of extensions like notes (those are called *admonitions* in MkDocs).

## Initialize a new project with MkDocs

**To create a new MkDocs project:**

1. Using the Windows Terminal, navigate to the folder that will store your new project (see [Windows Command Reference](cmd-reference) for help).

1. Type `mkdocs new` followed by the name of your project:

    ```
    mkdocs new {project-name}
    ```

    A new project folder will be created, along with a blank `mkdocs.yml` configuration file, the `docs\` folder, and a starter `index.html` file.

1. In the terminal, type `cd {new project name}` and press **Enter** to navigate into the project folder. 

    Make sure the path that appears at the prompt is at the root level of your project -- to be sure, type `dir` and press **Enter**. You should see the *mkdocs.yml* file and the *docs/* directory in the terminal output.

1. Open the project folder in Visual Studio Code and start writing!


## Using the Live Build Server

While you're building your markdown documentation, MkDocs provides you with a live build server that lets you see what you're creating in real time. Whenever a file changes in your project, the server will regenerate the output and refresh the browser.

**To Start the Live Build Server:**

1. Open the terminal in Visual Studio Code by pressing **Ctrl** + **`**.

1. If the command prompt isn't in the project folder (you can tell by looking at the file path on the command prompt line), navigate to it. Use [Windows Command Reference](cmd-reference) for specific help.

1. Once you're in the project directory, type `mkdocs-serve` and press **Enter**.
    
    The project will be built and the build server starts.

1. To see the project, switch to a web browser and type this URL in the address bar:

    ```
    localhost:8000
    ```

1. To update the live preview, save any file in your project. The browser will automatically refresh and show the new content.

While the server is running, the command prompt will be unavailable. To use the command prompt again, stop the build server as described next.

** To Stop the Live Build Server: **

1. Click in the terminal window of Visual Studio Code. You won't see any visual feedback when you do this, but it puts the focus on the terminal window  so the next command is applied to it and not the editor.

1. Type **Ctrl** + **c**. 

    The server will stop running and you'll see the command prompt again.

    !!! tip
        This key combination means *copy* in most modern contexts, but in this case it means *break*. This is a holdover from the old days of command line programming.

## Generating the Site

When you're ready, you can run the mkdocs builder to create a package of files suitable for uploading to a server. If you're looking at this site online, that's the command that was used to create this package.

The content created by mkdocs-build is identical to what you've been looking at with mkdocs-serve; it just places all the files in a convenient location for uploading.

**To build the Documentation Site:**

1. If the live server is running, stop it by clicking into the terminal window and typing **Ctrl** + **c**.

1. At the command prompt, type `mkdocs build` and press **Enter**.
    The site will be built and placed in a directory called *Site/*, located in the main project directory alongside the *docs/* folder and the *mkdocs.yml* file.



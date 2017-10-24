# Windows Command Line Reference

You'll need a minimal understanding of the Windows command line to get around using MkDocs. The command line interface can be intimidating if you've never used it, but we'll just be using it for basic tasks.

Importantly, almost all of the things we'll do on the command line can also be done using the file explorer (or Finder in macOS), so you don't have to do much at all in the terminal if you aren't comfortable in it. The only thing you *have* to be able to do is navigate to the main MkDocs project folder.

The terminal interface shows you your current location in the file system, followed by a greater-than symbol (`>`) called the prompt. You type your commands at the prompt, and press **Enter** to execute them.

For example, if you were at the root (top) level of the C drive, the prompt would look like this:

```bash
C: >
```

If you were in your *My Documents* folder on a BCIT machine, your prompt might look similar to this:

```bash
C:\Users\A0078775\My Documents\ >
```

## Command Reference
The most important thing you'll need to do in the command terminal is navigate around the file system. 

**To change your current drive:**

Type the drive letter you want to move to followed by colon, and press enter. For example, to change to the H drive, type
`H:` and then press enter. The prompt will show your new drive letter.

**To see a listing of files and folders in your current location** 

Type `dir` and press **Enter**:
```bash
 > dir
```

Files will show their extension (TXT, EXE, etc). Directories will be indicated by `<DIR>`. You can confirm you're in the right place by navigating to the same location using the file explorer.

**To move down into a new directory** 

To navigate from your current location into a new folder, Type `cd`, a space, and the destination path, then press enter. For example, to move into a directory called *mkdocs*:

```bash
> cd mkdocs
```

**To move UP from your current directory into the parent directory**
Type `cd` and a space followed by two periods. For example, to navigate up one level:

```bash
> cd .. 
```

To navigate up additional levels, add more dots separated by slashes: `cd ../..` to move up two levels, or `cd ../../..` to move up three levels, and so on.

You can autocomplete file and folder names by typing a few letters and pressing tab.

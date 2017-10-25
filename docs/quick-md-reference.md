# Quick Markdown Reference

This is a super-brief and incomplete markdown reference. For much more in-depth instructions, visit the reference resources cited [here](using#important-mkdocs-references).

## Formatting

* *Italic* text is surrounded by single asterisks, like this: \*text\*
* **Bold** text is surrounded by double asterisks, like this: \*\*text\*\*
* `code` or other system emphasis is surrounded by backticks, like this: \`text\`
* Code blocks, or multiline code segments, are "fenced" by triple backticks (\`\`\`) above and below the code, like this:

\`\`\`
```
Code
Goes
Here
```
\`\`\`

## Lists

**Bulleted lists** are indicated by a single asterisk at the start of each line, so this...

```
* This will be
* A bulleted list
* With three items
```

...becomes:

* This will be
* A bulleted list
* With three items

**Numbered lists** are indicated by a single number and period at the start of each line. Note that the actual number you use is ignored; I usually recommend always using "1.", but you can use anything that makes sense to you, so this...

```
1. This will be
1. A numbered list
1. With three items
```

...becomes:

1. This will be
1. A numbered list
1. With three items

**Maintaining Indentation**

To have multiple paragraphs under a single bullet or number, just indent the following paragraphs:

```
* Bullet number 1

    This is a second paragraph under bullet 1

* Bullet number 2

    This is a second paragraph under bullet 2
```
Becomes:

* Bullet number 1

    This is a second paragraph under bullet 1

* Bullet number 2

    This is a second paragraph under bullet 2

## Links

Link syntax is simple: The text to display in \[square brackets\], immediately followed by the URL in \(parenthesis\).

* For external links (outside the project), the URL should have the full address including `http://` or `https://`, like this:
    
    ```
    [Google](https://google.com)
    ```

* For internal links (inside the project), use the *filename without an extension*. For example, to point to the `about-mkdocs.md` file in this project, you'd do something like this:

    ```
    [Link text](about-mkdocs)
    ```

## Images

Image syntax is almost exactly the same as link syntax; just include an exclamation point first:

```
![Image alt text for screen readers and google](path-to-image-file.png)
```


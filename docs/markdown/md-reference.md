# Quick Markdown Reference

This is a super-brief and incomplete markdown reference. For much more in-depth instructions, visit the following site:

[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Formatting

* *Italic* text is surrounded by single asterisks, like this: `*text*`
* **Bold** text is surrounded by double asterisks, like this: `**text**`
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

To have multiple paragraphs under a single bullet or number, just indent the subsequent paragraphs:

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


**Nested Lists**

You can nest lists if you need to! The syntax for a nested list is the same, just indented under the "parent" list item:

```
1. Number 1
    * Sub-point 1a
    * Sub-point 1b
    * Sub-point 1c
2. Number 2
    * Sub-point 2a
    * Sub-point 2b
```

1. Number 1
    * Sub-point 1a
    * Sub-point 1b
    * Sub-point 1c
2. Number 2
    * Sub-point 2a
    * Sub-point 2b


## Links

Link syntax is simple: The text to display in \[square brackets\], immediately followed by the URL in \(parenthesis\).

```
[Google](https://google.com)
```
Becomes

[Google](https://google.com)


## Images

Image syntax is almost exactly the same as link syntax; just include an exclamation point first. To use a web-based image (hosted on a server), supply a full URL (http://example.com); to use a local image, use a relative file path (../../path/to/image.jpg).

```
![Image alt text for screen readers and google](path-to-image-file.png)
```


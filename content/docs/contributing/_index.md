---
title: Contributing
toc: true
---

## Adding Documentation To This Site
Contribution Information to troubleshooting and FAQ for Mason Classical Academy IT department. If interested in contributing new documentation, please review this information in the contributing section to learn how to use.

When contributing, create a new branch locally, submit changes and then push to the repository for consideration.


## Explore

{{< cards >}}
  {{< card link="docs" title="Docs" icon="book-open" >}}
  {{< card link="about" title="About" icon="user" >}}
{{< /cards >}}

## Documentation

This site is meant to be an assist to our daily operations and troubleshooting that we perform. In addition, if there are tasks, i.e., upgrading servers or configuring out networks, setup of a new campus, etc., this will be a place to document things that really aren't manual-related information. This way, if people are out, new, or unreachable, we have a common starting point to give outsiders and new people alike a fighting chance at keeping our schools operational, from an IT perspective.

To learn about the site setup, configuration, and maintenance please checkout the contriubting section.


## How Markdown Works
This site is run by a markup language called, Markdown. This is a brief overview of how the markup language works for this site. Feel free to Google for more thorough documentaiton.
Hugo supports [Markdown](https://en.wikipedia.org/wiki/Markdown) syntax for formatting text, creating lists, and more. This page will show you some of the most common Markdown syntax examples.

<!--more-->

## Markdown Examples

### Styling Text

| Style   | Syntax     | Example   | Output   |
| --------  | -------- | ------ | ------ |
| Bold | `**bold text**` | `**bold text**` | **bold text** |
| Italic | `*italicized text*` | `*italicized text* | *italicized text* |
| Strikethrough | `~~strikethrough text~~` | `~~strikethrough text~~` | ~~strikethrough text~~ |
| Subscript | `<sub></sub>` | `This is a <sub>subscript</sub> text` | This is a <sub>subscript</sub> text |
| Superscript | `<sup></sup>` | `This is a <sup>superscript</sup> text` | This is a <sup>superscript</sup> text |

### Blockquotes

Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

### Tables

Tables aren't part of the core Markdown spec, but Hugo supports them out-of-the-box.

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

| Italics   | Bold     | Code   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

### Code Blocks

{{< cards >}}
  {{< card link="../../guide/syntax-highlighting" title="Syntax Highlighting" icon="sparkles" >}}
{{< /cards >}}
### Lists

#### Ordered List

1. First item
2. Second item
3. Third item

#### Unordered List

* List item
* Another item
* And another item

#### Nested list

* Fruit
  * Apple
  * Orange
  * Banana
* Dairy
  * Milk
  * Cheese

### Images

![](https://source.unsplash.com/featured/800x600?landscape)

With caption:

![](https://source.unsplash.com/featured/800x600?landscape "Unsplash Landscape")

## Configuration

Hugo uses [Goldmark](https://github.com/yuin/goldmark) for Markdown parsing.
Markdown rendering can be configured in `hugo.yaml` under `markup.goldmark`.
Below is the default configuration for Hextra:

```yaml {filename="hugo.yaml"}
markup:
  goldmark:
    renderer:
      unsafe: true
  highlight:
    noClasses: false
```

For more configuration options, see Hugo documentation on [Configure Markup](https://gohugo.io/getting-started/configuration-markup/).

## Learning Resources

* [Markdown Guide](https://www.markdownguide.org/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Markdown Tutorial](https://www.markdowntutorial.com/)
* [Markdown Reference](https://commonmark.org/help/)

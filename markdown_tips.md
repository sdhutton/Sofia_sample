---
layout: default
title: Markdown Tips
permalink: /markdown_tips/
description: Getting started with Markdown
---

## Summary

The following information is adapted from the [Jekyll Theme (Cayman)](https://github.com/pages-themes/cayman/blob/master/index.md?plain=1).

| Feature | Sample Output | Markdown Syntax |
| :--- | :--- | :--- |
| Bold | **bold text** | `**bold**` or `__bold__` |
| Italic | _italic text_ | `*italic*` or `_italic_` |
| Strikethrough | ~~strikethrough text~~ | `~~strikethrough~~` |
| Link | [Contact](../contact) | `[Text](../page)` (ex. `[Contact](../contact)`) |
| Header 1 | <h1>Header 1</h1> | `# Header 1` |
| Header 2 | <h2>Header 2</h2> | `## Header 2` |
| Header 3 | <h3>Header 3</h3> | `### Header 3` |
| Header 4 | <h4>Header 4</h4> | `#### Header 4` |
| Header 5 | <h5>Header 5</h5> | `##### Header 5` |
| Blockquote | <blockquote>This is a blockquote</blockquote> | `> Blockquote text` |
| Unordered List | <ul><li>Item foo</li></ul> | `* Item` or `- Item` or `+ Item` |
| Ordered List | <ol><li>Item one</li></ol> | `1. Item` (numbering is often ignored) |
| Horizontal Rule | --- | `***` or `---` or `___` |
| Inline Code | `inline` | `` `code` `` |
| Code Block (Fenced) | ```print("Hello, world!")``` | `` ```code``` `` |
| Image | ![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png) | `![Alt text](Image URL)` |

---

## From Jekyll Theme Website

The following information comes straight from the [Jekyll Theme (Cayman)](https://github.com/pages-themes/cayman/blob/master/index.md?plain=1).

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
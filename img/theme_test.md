## Heading 1 (H1)

### Heading 2 (H2)

#### Heading 3 (H3)

##### Heading 4 (H4)

###### Heading 5 (H5)

###### Heading 6 (H6)

### Text and Styles
Normal example text, with **bold text**, *italic text*, and ***bold and italic text together***. Here there is also ~~strikethrough text~~, ==highlighted text==, and `inline code`.

A longer paragraph to evaluate readability, line height, and fonts: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

### Links
* Internal link: [[Theme Test]]
* Internal link with alias: [[Theme Test|link alias]]
* Link to a non-existent note: [[Non-existent note]]
* External link: [Obsidian Website](https://obsidian.md)
* Simple URL: <https://obsidian.md>
* Heading link: [[#Quotes]]

### Quotes

> This is a simple quote.
> Second line of the quote, with **bold** and *italic*.

> Nested quote
>
> > Level two
> >
> > > Level three

### Callouts

> [!NOTE] Note
> Content of the note callout with *italics* and a [link](https://obsidian.md).

> [!ABSTRACT] Abstract / Summary / TLDR
> Short summary.

> [!INFO] Info
> Useful information.

> [!TODO] Todo
> Task to do.

> [!TIP] Tip / Hint / Important
> A helpful suggestion.

> [!SUCCESS] Success / Check / Done
> Operation successful.

> [!QUESTION] Question / Help / FAQ
> A question?

> [!WARNING] Warning / Caution / Attention
> Pay attention to this.

> [!FAILURE] Failure / Fail / Missing
> Something failed.

> [!DANGER] Danger / Error
> Danger!

> [!BUG] Bug
> A bug to fix.

> [!EXAMPLE] Example
> An example.

> [!QUOTE] Quote / Cite
> A quote inside a callout.

> [!NOTE]- Collapsible callout (closed)
> Hidden content that opens with a click.

> [!NOTE]+ Collapsible callout (open)
> Visible content that can be closed.

### Lists
* Bullet list item
  * Sub-item
    * Sub-sub-item

1. First numbered item
2. Second item
   1. Numbered sub-item

* [ ] Task to do
* [x] Completed task

### Table

| Column A                             | Column B | Column C |
| ------------------------------------ | -------- | -------- |
| **bold**                             | *italic* | `code`   |
| [external link](https://obsidian.md) | text     | text     |

### Code Blocks
Python:
```python
def greeting(name):
    # A comment
    return f"Hello, {name}!"

print(greeting("world"))
```

CSS:
```css
body {
  color: #cdd6f4;
}
```

### Tags and More
#tag-example #other/sub-tag

Footnote[^1] and inline formula $E = mc^2$.
$$x(t) = e^{A(t-t_0)}x(t_0) + \int_{t_0}^{t} e^{A(t-\xi)}Bu(\xi-\tau_m)d\xi$$
[^1]: This is the footnote.

# Markdown Cheat Sheet

**Tags:** #reference #markdown

---

## Headings

```
# H1 - Heading 1
## H2 - Heading 2
### H3 - Heading 3
#### H4 - Heading 4
##### H5 - Heading 5
###### H6 - Heading 6
```

---

## Text Formatting

|Style|Syntax|Output|
|---|---|---|
|Bold|`**bold**` or `__bold__`|**bold**|
|Italic|`*italic*` or `_italic_`|_italic_|
|Bold & Italic|`***bold italic***`|_**bold italic**_|
|Strikethrough|`~~strikethrough~~`|~~strikethrough~~|
|Inline Code|`` `code` ``|`code`|
|Highlight (Obsidian)|`==highlight==`|==highlight==|

---

## Lists

**Unordered List**

```
- Item one
- Item two
  - Nested item
  - Nested item
- Item three
```

**Ordered List**

```
1. First
2. Second
   3. Nested
   4. Nested
5. Third
```

**Task / Checkbox List**

```
- [ ] Unchecked task
- [x] Checked task
```

---

## Links & Images

```
[Link Text](https://example.com)
[Link with Tooltip](https://example.com "Tooltip text")

![Alt Text](image.png)
![Alt Text](image.png "Image Title")
```

**Obsidian Internal Links**

```
[[Note Name]]
[[Note Name|Display Text]]
[[Note Name#Heading]]
```

---

## Blockquotes

```
> This is a blockquote.
> It can span multiple lines.

> Nested blockquote
>> Indented further
```

---

## Code

**Inline Code**

```
Use `backticks` for inline code.
```

**Code Block**

````
```language
code goes here
```
````

Common languages: `python`, `javascript`, `bash`, `sql`, `json`, `html`, `css`

---

## Tables

```
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell     | Cell     | Cell     |
| Cell     | Cell     | Cell     |
```

**Alignment**

```
| Left     | Center   | Right    |
|:---------|:--------:|---------:|
| text     | text     | text     |
```

---

## Horizontal Rule

All three of these work:

```
---
***
___
```

---

## Footnotes

```
This is a sentence with a footnote.[^1]

[^1]: This is the footnote text.
```

---

## Callouts (Obsidian Only)

```
> [!NOTE]
> Useful information.

> [!TIP]
> Helpful tip.

> [!WARNING]
> Caution advised.

> [!DANGER]
> Critical warning.

> [!INFO]
> More context here.

> [!SUMMARY]
> A summary block.
```

Collapsible callout:

```
> [!NOTE]-
> This callout is collapsed by default.
```

---

## Embeds (Obsidian Only)

```
![[Note Name]]           embed a note
![[Note Name#Heading]]   embed a specific section
![[image.png]]           embed an image
![[file.pdf]]            embed a PDF
```

---

## Tags (Obsidian Only)

```
#tag
#nested/tag
```

---

## Math (Obsidian Only)

**Inline math**

```
$E = mc^2$
```

**Block math**

```
$$
\frac{n!}{k!(n-k)!} = \binom{n}{k}
$$
```

---

## Escaping Characters

Use a backslash `\` to escape markdown syntax:

```
\*not italic\*
\# not a heading
\[not a link\]
```

---

## Quick Reference

|Element|Syntax|
|---|---|
|Heading|`# H1` `## H2` `### H3`|
|Bold|`**text**`|
|Italic|`*text*`|
|Link|`[text](url)`|
|Image|`![alt](url)`|
|Blockquote|`> text`|
|Inline Code|`` `code` ``|
|Horizontal Rule|`---`|
|Checkbox|`- [ ] task`|
|Strikethrough|`~~text~~`|
|Highlight|`==text==`|
|Internal Link|`[[Note]]`|
|Callout|`> [!NOTE]`|

---

_Obsidian-specific features marked where applicable._

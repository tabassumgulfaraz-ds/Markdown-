# **How do you give a heading in Markdown?**

# Heading_1
## Heading_2
### Heading_3
#### Heading_4
##### Heading_5
###### Heading_6

# **How do you add a block of words (block of text) in Markdown?**
> By using triple backticks (```) before and after the text, or by adding > for blockquotes.

> By using triple backticks (```) before and after the text, or by adding > for blockquotes.

# **How do you add line breaks in Markdown?**
By adding two spaces at the end of a line,  
or 

by leaving a blank line between paragraphs.  

# **How do you combine a heading (like Heading 3) with a block of code in Markdown?**
> ### First add the code block with triple backticks (```) or (>),  then write the heading using (###).

# **How do you make text bold, italic, or bold plus italic in Markdown?**

**Bold → Wrap text in double asterisks ** or double underscores (__).**

  *Italic → Wrap text in single asterisk (*) or single underscore _.*

***Bold + Italic → Wrap text in triple asterisks or underscore.***

# **How do you add bullet points/List, sub-bullet points, and further sub-bullet points in Markdown?**
- Use - or * for bullets, and indent with one/two spaces (or more) for sub-levels.
  - Tab then - or * for bullets, and indent with one/two spaces (or more) for sub-levels.
    - Tab, Tab then - or * for bullets, and indent with one/two spaces (or more) for sub-levels.

1. Main item 1  
   1. Sub item 1.1  
      1. Further sub item 1.1.1  
2. Main item 2  
   1. Sub item 2.1


# **How do you create a horizontal line between paragraphs (divider) and how do you add a line break in Markdown?**

**Horizontal Line (Divider):** Use three or more hyphens ---, asterisks ***, or underscores ___ on a single line.

Paragraph one
---
***
___  
Paragraph two


**Line Break:** Add two spaces at the end of a line or use <br>

This is line one.   
This is line two.

This is line one.<br>
This is line two.

# **How do you add a link or a hyperlink in a Markdown file?**
By using square brackets [] for the text and parentheses () for the URL.


https://www.openai.com

[OpenAI](https://www.openai.com)

[OpenAI](https://www.openai.com "Visit OpenAI")

[perplexity]: https://www.perplexity.ai/
link of perplexity [here][perplexity]

# **How do you add images or figures with the help of a link in a Markdown file?**

[QR](QR_Code.jpg)

![QR](QR_Code.jpg)

![Alt text](https://example.com/image.png "This is an image")

[![Alt text](https://example.com/image.png)](https://example.com)

# **How do you add inline code or a code block of any language (like Python, R, HTML, etc.) in a Markdown file?**

**1. Inline Code:** Use single backticks `

This is `print("Hello, Ahmad")`.

**2. Code Block (no language):** Use triple backticks before and after.
```
print("Hello, World!")
print("Hello, World!")
```

```python
print("Hello, World!")
print("Hello, World!")
```

# **How do you add tables in a Markdown file?**
By using | (pipes) to separate columns and - (dashes) to create head
| Name      | Age | City     |
|-----------|-----|----------|
| Alice     | 24  | New York |
| Bob       | 30  | London   |
| Charlie   | 29  | Paris    |
|


| Name      | Age   | City     |
|:----------|:-----:|---------:|
| Alice     | 24    | New York |
| Bdown?ob       | 30    | London   |
| Charlie   | 29    | Paris    |
|

# **How do you create a Table of Contents (TOC) in a Markdown file?**

[**2. How do you add a block of words (block of text) in Markdown?**](#how-do-you-add-a-block-of-words-block-of-text-in-markdown)  

  
# **Install Extensions**
1. Markdown All in One
2. Markdown PDF
3. markdownlint
4. markdown shortcuts
5. vscode-pdf

**ctrl+b for bold**  
_ctrl+i for italic_  
_**ctrl+b+i for bold and italic**_  

> 1. We can also add a hyperlink by selecting a text, right-clicking, choosing “Toggle Hyperlink”, and pasting the URL/link.   
> 2. We can also add an image by selecting a text, right-clicking, choosing “Toggle Image”, and pasting the URL/link or the image name (e.g., image_name.jpg or image_name.png).
> 3. Many other actions can also be performed by selecting a word and right-clicking.

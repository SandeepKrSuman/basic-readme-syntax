# Basic-README-Syntax
Github README.md is written in markdown which may include some minor variations.  
Here I have listed some basic syntax which will help you to write your first README.md on github.  
  
  
<br>

# Contents
- [Headings](#headings)  
- [Paragraphs](#paragraphs)  
- [Horizontal Rules](#horizontal-rules)  
- [Line Breaks](#line-breaks)  
- [Emphasis](#emphasis)  
    - Bold
    - Italic
    - Strikethrough
    - Nested Emphasis
- [Blockquotes](#blockquotes)
- [Code Blocks](#code-blocks)
- [Links](#links)
- [Images](#images)
- [Lists](#lists)
    - Unordered list
    - Ordered list
- [Task Lists](#task-lists)
- [Escaping Characters](#escaping-characters)
- [Emojis](#emojis)
- [Tables](#tables)
  
  
<br>

# Headings
To create a heading add a hash sign - `#` (*also known as number sign, or pound sign, etc.*) followed by a space before your heading text. The number of `#` used before the heading text determines the level of heading. Heading level 1 i.e. h1 requires single `#` sign and goes upto heading level 6 i.e. h6 which requires use of six `#` signs.  
  
```
# Heading h1
## Heading h2
### Heading h3
#### Heading h4
##### Heading h5
###### Heading h6
```
  
The above example is rendered as:  
# Heading h1
## Heading h2
### Heading h3
#### Heading h4
##### Heading h5
###### Heading h6
  
  
<br>

# Paragraphs
Write in plain text without additional label to create a paragraph text.  
  
| Example | Rendered as |
| ------ | ----------- |
| This is a paragraph text. | This is a paragraph text. |
  
- Sometimes html `<p>` tag is also used conventionally to custom-align a paragraph. For example, `<p align="center">This is a center-aligned paragraph</p>`  
  
  
<br>

# Horizontal Rules
To create a horizontal rule, use three or more dashes `---` on a fresh line.  
```
---
```
The above exmple is rendered as:  

---
  
<br> 

# Line Breaks
Use two or more spaces and hit enter for a line break.  
Since it is quite hard to see trailing whitespaces in an editor, HTML `<br>` tag is conventionally used for line breaks.  
  
| Example | Rendered as |
| ------ | ----------- |
| `This is one line<br>This is next` | This is one line<br>This is next |
  
<br>

# Emphasis
1. **BOLD**  
Add two asterisks *(more conventionally used)* or underscores before and after a text to make it bold. To make some characters of a text bold in the middle, use two asterisks without spaces before and after the characters (using underscore does not work in this case. So it is a good practise to use asterisks instead of underscore everytime to make a text bold).
  
| Example | Rendered as |
| --- | --- |
| `This word is **Bold**` | This word is **Bold** |
| `This word is __also Bold__` | This word is __also Bold__ |
| `Basic**Readme**Syntax` | Basic**Readme**Syntax |
  
2. **ITALIC**  
To italicize a text use single asterisk or underscore. Use single asterisk (and not underscore) to italicize a middle text.
  
| Example | Rendered as |
| --- | --- |
| `This word is *Italic*` | This word is *Italic* |
| `This word is _also Italic_` | This word is _also italic_ |
| `Basic*Readme*Syntax` | Basic*Readme*Syntax |
  
3. **STRIKETHROUGH**  
For strikingthrough a text use two tilde symbols before and after a text.  
  
| Example | Rendered as |
| --- | --- |
| `This word is ~~strikedthrough~~` | This word is ~~strikedthrough~~ |
  
4. **Nested Emphasis**  
  
| Example | Rendered as |
| --- | --- |
| `**This text is bold and _nested_ italic**` | **This text is bold and _nested_ italic** |
| `***This text is all bold and italic***` | ***This text is all bold and italic*** |
| `This ***word*** is bold and italic` | This ***word*** is bold and italic |
  
<br>

# Blockquotes
To create a blockquote add a `>` and a space at the begining of a paragraph.
  
`> This is a blockquote.`  
The above example is rendered as:  
> This is a blockquote.
  
  

**Blockquote with multiple paragraphs**  

```
> First line.
> 
> Last line was blank.
```
The above example is rendered as:  
> First line.
> 
> Second line.
  
  

**Nested Blockquote**  

```
> The first line.
>> This is nested.
```
The above example is rendered as:  
> The first line.
>> This is nested.
  
  
**Other examples of nested blockquotes**  
```
> 
> ### Opensource is love
> 
> star this repo
> fork this repo
> 
> Keep **contributing** to the *opensource*. It's fun.
> 
```
is rendered as  
> 
> ### Opensource is love
> 
> 1. star this repo
> 2. fork this repo
> 
> Keep **contributing** to the *opensource*. It's fun.
> 
 
 
<br>

# Code Blocks
You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.  
  
| Example | Rendered as |
| --- | --- |
| Use \`npm install\` to install dependencies | use `npm install` to install dependencies |
  
To format code or text into its own distinct block, use triple backticks.  
  
\` \` \` <br>npm install<br>npm start<br> \` \` \`  
is rendered as  
```
npm install
npm start
```
  
  
<br>

# Links
Inline links can be created by wrapping link text in brackets `[]`, and then wrapping the URL in parentheses `()`.  
  
| Example | Rendered as |
| --- | --- |
| `[basic-readme-syntax](https://github.com/SandeepKrSuman/basic-readme-syntax/)` | [basic-readme-syntax](https://github.com/SandeepKrSuman/basic-readme-syntax/) |
  
Relative links can also be used : 
  
| Example | Rendered as |
| --- | --- |
| `[README](./README.md)` | [README](https://github.com/SandeepKrSuman/basic-readme-syntax/blob/main/README.md) |
  
You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it within quotes `""` after the URL.  

| Example | Rendered as |
| --- | --- |
| `[basic-readme-syntax](https://github.com/SandeepKrSuman/basic-readme-syntax/ "Create your first README")` | [basic-readme-syntax](https://github.com/SandeepKrSuman/basic-readme-syntax/ "Create your first README") |
  
To quickly turn a URL or an Email address into a link enclose it within angle brackets `<>`.  

| Example | Rendered as |
| --- | --- |
| `<https://github.com/SandeepKrSuman/basic-readme-syntax/>` | <https://github.com/SandeepKrSuman/basic-readme-syntax/> |
| `<examplemail@example.example>` | <examplemail@example.example> |
  
To link to headings within the README, treat headings as id's and use it instead of url in links.  
For example to link to headings section in this README we can create link as `[Headings](#headings)`. To link to code blocks section on this README we can create link as `[Code Blocks](#code-blocks)`. Note that id's are exact name of headings with all characters in lower case and in place of space hypen `-` is used.  

| Example | Rendered as |
| --- | --- |
| `[Headings](#headings)` | [Headings](#headings) |
| `[Code Blocks](#code-blocks)` | [Code Blocks](#code-blocks) |
  
  
<br>

# Images
Represent an image like `![alt-text](image-link)`.  
Relative path of the image can also be used as image link: `![sun-image](./images/sun.jpg)`  
  
The following HTML `<img>` tag is also legal:  
```
<img src="./images/sun.jpg" alt="sun-image" style="float: left; margin-right: 15px;" />
```
  
<br>

# Lists
1. **Unordered Lists**  
To create an unordered list, add a dash`(-)` or an asterisk`(*)` or a plush sign `(+)` and a space in front of the text.  
Indent one or more items to create nested list.  
```
- First item
- Second item
- Third item
```
The above example is rendered as:  
- First item
- Second item
- Third item
  
```
- first item
- second item
  - third item
  - fourth item
- fifth item
```
  
The above example is rendered as:  
- first item
- second item
  - third item
  - fourth item
- fifth item
  
  
2. **Ordered Lists**  
To create an ordered list use number and dot (or period) before text.  
Indent one or more items to create nested list.  

```
1. first item
2. second item
    1. nested one
    2. nested two
3. third item
```
  
The above example is rendered as: 
  
1. first item
2. second item
    1. nested one
    2. nested two
3. third item
  
  
<br>

# Task Lists
To create a task list, preface list items with a regular space character followed by `[ ]`. To mark a task as complete, use `[x]`.  
```
- [ ] starred this repo
- [ ] forked this repo
- [x] I love opensource
```
The above example is rendered as:  
- [ ] starred this repo
- [ ] forked this repo
- [x] I love opensource
  
  
<br>

# Escaping Characters
To display a literal character that would otherwise be used to format text in the README document, add a backslash `\` in front of the character.  
  
```
* this is a bullet point  
\* this is an asterisk
```
The above example is rendered as:  
  
* this is a bullet point  
\* this is an asterisk
  
  
<br>

# Emojis
One way to use emojis in the readme file is to simply copy and paste them. The other way is to use *emoji shortcuts*.  
```
😊😂  
:heart_eyes:  
:star: this repo
```
The above example is rendered as:  
😊😂  
:heart_eyes:  
:star: this repo
  
  
<br>


# Tables
Take a look at the following examples to create a table:  

```
| Greetings | Example |
| --- | --- |
| Hello | Hello git |
| Hi | Hi github |
| Hey | Hey there |
```
  
The above example is rendered as:  

| Greetings | Example |
| --- | --- |
| Hello | Hello git |
| Hi | Hi github |
| Hey | Hey there |
  
  
<br>

### Resource
If you wish to play aorund with what you have learned so far you can try rendering the markdown online on [Dillinger](https://dillinger.io/). It is absolutely free platform.  
  
  
---

<br>

> We have touched almost every part required for creating a functional README.md file. Hope this was helpful. Try creating your first readme with the help of whatever you have learned from here. If this helped you in any way do show some love by starring this repo. Happy coding 😊.

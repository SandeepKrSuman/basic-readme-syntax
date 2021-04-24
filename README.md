# Basic-README-Syntax
Github README.md is written in markdown which may include some minor variations.  
Here I have listed some basic syntax which will help you to write your first README.md on github. 

<br>

# Headings
To create a heading add a hash sign - `#` (*also known as number sign, or pound sign, etc.*) followed by a space before your heading text. The number of `#` used before the heading text determines the level of heading. Heading level 1 i.e. h1 requires single `#` sign and goes upto heading level 6 i.e. h6 which requires use of six `#` signs.  
  
| Example | Rendered as |
| ------ | ----------- |
| # Heading h1 | <h1>Heading h1</h1> |
| ## Heading h2 | <h2>Heading h2</h2> |
| ### Heading h3 | <h3>Heading h3</h3> |
| #### Heading h4 | <h4>Heading h4</h4> |
| ##### Heading h5 | <h5>Heading h5</h5> |
| ###### Heading h6 | <h6>Heading h6</h6> |
  
<br>

# Paragraphs
Write in plain text without additional label to create a paragraph text.  
  
| Example | Rendered as |
| ------ | ----------- |
| This is a paragraph text. | This is a paragraph text. |
  
- Sometimes html `<p>` tag is also used conventionally to custom-align a paragraph. For example, `<p align="center">This is a center-aligned paragraph</p>`  

<br>

# Line Breaks
Use two or more spaces and hit enter for a line break.  
Since it is quite hard to see trailing whitespaces in an editor, HTML `<br>` tag is conventionally used for line breaks.  
  
| Example | Rendered as |
| ------ | ----------- |
| `This is one line<br>This is next` | This is one line<br>This is next |
  
<br>

# Emphasis
1. ### BOLD
Add two asterisks *(more conventionally used)* or underscores before and after a text to make it bold. To make some characters of a text bold in the middle, use two asterisks without spaces before and after the characters (using underscore does not work in this case. So it is a good practise to use asterisks instead of underscore everytime to make a text bold).
  
| Example | Rendered as |
| --- | --- |
| `This word is **Bold**` | This word is **Bold** |
| `This word is __also Bold__` | This word is __also Bold__ |
| `Basic**Readme**Syntax` | Basic**Readme**Syntax |
  
2. ### ITALIC
To italicize a text use single asterisk or underscore. Use single asterisk (and not underscore) to italicize a middle text.
  
| Example | Rendered as |
| --- | --- |
| `This word is *Italic*` | This word is *Italic* |
| `This word is _also Italic_` | This word is _also italic_ |
| `Basic*Readme*Syntax` | Basic*Readme*Syntax |
  
3. ### STRIKETHROUGH
For strikingthrough a text use two tilde symbols before and after a text.  
  
| Example | Rendered as |
| --- | --- |
| `This word is ~~strikedthrough~~` | This word is ~~strikedthrough~~ |
  
4. ### Nested Emphasis
  
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
| `[README](./README.md)` | [README](./README.md) |
  
<br>

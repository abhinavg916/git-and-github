What is Markdown?
- Lightweight Markup Language with plain text formatting syntax
- Mainly built for readibility and ease of use for documentations
- It can be converted into HTML, XHTML and other formats
- Used for Readme files in GitHub, Forum and Blog Posts and in Static Site Generators
- It uses .md as file extension



Things which can be formatted with Marksdown

- Headings
- Blocks of Code
- Lists
- Images
- Emphasis (Bold, Itallic)
- Links
- Blockquotes
- Links
- Horizontal Rules

- There are various other versions or extensions of Markdown like PHP Markdown, Github Markdown (which has feature of adding Tables, TaskLists and many more) and so on



Steps to setup Marksdown

1. Markdown Editors/IDE
- VSCode : Free and Best
- Atom
Below IDE's are built espcially for Markdown
- MarkPad : Paid
- HarooPad : Paid
- MarkdownPad 2 : Paid
- Typora : Paid


2. Marksdown Live Preview
Using VSCode,
Install Auto-Open Markdown Extension - It helps in viewing Markdown side by side in real-time


Syntaxes in Markdown

New Line or New Paragraph

Leave a one blank line after the sentence

SampleText1 from Paragraph1

SampleText1 from Paragraph2



Comments
<!-- Comments -->



Headings
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
##### Heading 6



Emphasis
<!-- Italics -->
* or _ symbols are used

Syntax

*ABC*

_ABC_

For Example 

This text is *Italic*

This text is _Italic_

<!-- Strong -->
** or __ symbols are used

Syntax

**ABC**

__ABC__

For Example 

This text is **Strong/Bold**

This text is __Strong/Bold__

<!-- StrikeThrough -->
~~ symbols is used

Syntax

~~ABC~~

For Example 

This text is ~~Strikethrough~~



Horizontal Rule
It adds a horizontal rule (line) for better formatting of contents as separation

--- or ___ are used

Syntax
---

___

For Example

----


To explicitly display the symbols

Since some symbols represent the markdown syntax but to explicitly display them \ symbol is used

Synatx

\<Symbol>Content\<Symbol>

For Example

\*This\*



BlockQuote
> symbol is used

Syntax

> ABC

For Example

>Sample Text




Links

To declare the name on the link,

[] is used and for link behind the name 

() is used

Syntax

[Link](URL)

To add the title on hovering over the link, " " are used in () after the url ends
[Click Here!](www.google.com "Google")

For Example

[Click Here!](www.google.com)

[Click Here to Search](www.google.com "Google")



Unordered Lists
One * is used

Synatx
* Item Name

For lists inside lists i.e nested 

Synatx
* Item Name
    * Nested Item Name
 
For Example
* Item 1
    * Nested Item 1
    * Nested Item 2
* Item 2
* Item 3



Ordered Lists
1 is used
If other than 1 is used then it does not considers as Ordered List items

Incrementation is done automatically

Syntax

1. Item Name

For Example
1. Item Name
1. Item Name
1. Item Name
1. Item Name

   

Inline Code Block
`` symbol is used

Syntax

`<p>Content</p>`


For Example

`<p>Paragraph Tag in HTML</p>`

`<b>Body Tag in HTML</b>`



Image
Similar to Links but ! is before it

Syntax

![Image Name](ImageURL)

For Example

![Markdown Logo](https://markdown-here.com/img/icon256.png)



GitHub Markdown

Code Blocks

``` symbol is used 

Syntax 

```
npm install
npm start
```

To specify code block language, language name can be add

Syntax

```Language name
npm install
npm start

```

For Example

```bash
npm install
npm start
```

```java
public static void main(String args[]){
    System.out.println("Hello World in Github Makrdown Code Block!");
}
```

```c++ 
#include<iostream.h>
using namespace std;
void main(){
    cout<<"Hello World in Github Makrdown Code Block!";
}
```

```javascript 
function add(num1, num2){
    return num1 + num2;
}
```
```python 
def add(num1, num2):
    return num1 + num2
```



Tables

| symbol is to define the formatting

Syntax

| Column 1 | Column 2 |
| -------- | -------- |
| Content  | Content |


For Example

|Name|Email|
|----|-----|
|Student 1 | student123@gmail.com|
|Student 2 | student456@gmail.com|



Task Lists

It shows checkboxes

* [] symbol is used which is unordered list and, x in square brackets represents the completed tasks and if no x is in the square bracket then the task is incomplete

Syntax

* [x]Task 1 <!-- Complete Task -->

* [ ]Task 2 <!-- Incomplete Task -->

For Example

* [x]Learn Marksdown

* [ ]Push to GitHub Repository



#### Author - Abhinavg916@gmail.com

# Markdown Notes

## What is Markdown?
* Lightweight Mark-up Language with plain text formatting syntax
* Mainly built for readability and ease of use for documentations
* It can be converted into HTML, XHTML and other formats
* Used for Readme files in GitHub, Forum and Blog Posts and in Static Site Generators
* It uses .md as file extension
* There are various other versions or extensions of Markdown like PHP Markdown, GitHub Markdown \(which has feature of adding Tables, Task Lists, etc\) and so on

### Things which can be formatted with Markdown
* Headings
* Blocks of Code
* Lists
* Images
* Emphasis (Bold, Italic, Strikethrough)
* Links
* Blockquotes
* Links
* Horizontal Rules
* Images


## Steps to Setup Markdown: -
---

### Markdown Editors/IDE
* VSCode by Microsoft: Free and Best \(Recommended\)
* Atom by GitHub

Below IDE's are built especially for Markdown
* MarkPad : Paid
* HarooPad : Paid
* MarkdownPad 2 : Paid
* Typora : Paid

### Markdown Live Preview
* Using VSCode, Install Auto-Open Markdown Extension - It helps in viewing Markdown side by side in real-time


## Syntaxes in Markdown
---
## 1. Bullet Points
* Purpose: It helps in maintaining proper indentations in documentation
* \'*' or \'-' symbols are used
* It is also known as Un-Ordered List

>Syntax
```bash
    * Statement
```

>For Example
* Statement 1
* Statement 2
* Statement3 



## 2. New Line or New Paragraph
* Purpose: To leave a one blank line after the sentence

>Syntax
```bash
Sample Text1 from Paragraph1

Sample Text2 from Paragraph2
```

>For Example
#### Without a blank line
    
Sample Text from Paragraph 1 Sample Text from Paragraph 2

#### With a blank line
* Sample Text from Paragraph 1 
* Sample Text from Paragraph 2

## 3. Comments in Markdown
* Purpose: Used for better understanding of codebase for developers
* It is ignored by the browser to render

>Syntax
```bash
<!-- Comments -->
```
>For Example
* Statement 1 \<!-- Comment 1 --\>
* Statement 2 \<!-- Comment 2 --\>  
* Statement 3 \<!-- Comment 3 --\>
* Statement 4 \<!-- Comment 4 --\>
* Statement 5 \<!-- Comment 5 --\>

## 4. Headings
* Purpose: To well format the headings in the documentation
* \'#' symbol is used before the statements
* With single \# represents the main heading
* With multiple \##.. represents the sub headings
* NOTE: By default, Main Heading \(\#) only has horizontal rule with it

>Syntax
```
   # Heading 1
   ## Heading 2
   ### Heading 3
   #### Heading 4
   ##### Heading 5
   ###### Heading 6 
```

>For Example
* # Heading 1
* ## Heading 2
* ### Heading 3
* #### Heading 4
* ##### Heading 5
* ###### Heading 6



### 5. Emphasis
#### 1. Italics
* Purpose: To format the text in Italic
* \'*' or \'_' symbols are used

> Syntax
```
*Sample Text*
_Sample Text_
```

>For Example 

* This Sample Text is *Italic* `<!-- Using *Italic* -->`
* This Sample Text is _Italic_ `<!-- Using _Italic_ -->`

#### 2. Strong
* Purpose: To format the text in Bold
* \'**' or \'__' symbols are used

>Syntax
```
**Sample Text**
__Sample Text__
```

>For Example 
* This Sample Text is **Strong** `<!-- Using **Strong** -->`
* This Sample Text is __Strong__ `<!-- Using __Strong__ -->`

#### 3. Strikethrough
* Purpose: To format the text in Strikethrough
* \'~~' symbols is used

>Syntax
```
~~Sample Text~~
```
> For Example 
* This Sample Text is ~~Strikethrough~~


### 6. Horizontal Rule
* Purpose: Adds a horizontal rule (line) for better separation
* \'---' or '___' symbols are used

>Syntax
```
Sample Text 1
---

Sample Text 2
___

```

>For Example
* Sample Text 1
---
*Sample Text 2
___


### 7. Display Symbols

* Purpose: Since in markdown symbols are reserved as syntax but to explicitly display them \ symbol is used
* \\ is used 

>Syntax
```
\<Symbol> Sample Texts \<Symbol>
```
For Example
* This is a Sample Text with \*symbol\* used for Italic Emphasis
* This is a Sample Text with \** symbol \** used for Bold Emphasis


### 8. Blockquotes
* Purpose: To format text in block quotes
* \'>' symbol is used

>Syntax
```
> Sample Text
```
>For Example
* >This is a Sample Text of Blockquotes


### 9. Links
* Purpose: To declare the Hyperlink
* \'( )' is used for the Link \(URL) and \'[ ]' is used for the title on the link

> Syntax
```
[Link Title](URL)
```

* To add title on hovering over the link, \" \" are used in \'( )' after the URL ends
```
[Link Title](URL "Title on Hover")
```
>For Example
* [Sample Link - Google](www.google.com)
* [Sample Link - Google with hover title](www.google.com "Google")



### 10. Un-Ordered Lists
* Purpose: To display Un-Ordered Lists
* Only one \'*' symbol is used

> Syntax
```
* Item Name
```
* For Nested Un-Ordered Lists

> Syntax
```
* Item Name 1
    * Nested Item
```

> For Example
* Item 1
    * Nested Item 1
    * Nested Item 2
* Item 2
* Item 3


### 11. Ordered Lists
* Purpose: To display the Ordered Lists
* \'1.' is used and if, Other than 1 is used then it is not considered as Ordered List
* Incrementation is done automatically

> Syntax
```
1. Item Name
```

> For Example
1. Item Name
1. Item Name
1. Item Name
1. Item Name

   
### 12. Inline Code Block
* Purpose: To display Programming Languages Syntaxes
* \` ` symbol is used

> Syntax
```
`<p>This is Paragraph Tag in HTML</p>`
```

> For Example
* `<p>Paragraph Tag in HTML</p>`
* `<b>Body Tag in HTML</b>`


### 13. Image
* Purpose: To display Images
* It is similar to Links in syntax but '!' is added before it

> Syntax
```
![Image Title](ImageURL)
```
> For Example

![Markdown Logo](https://markdown-here.com/img/icon256.png)


---
## GitHub Markdown
### 1. Code Blocks
*  Purpose: To display Programming Languages Syntaxes
*  \' ``` ' symbol is used 
* Programming Language name can be added to specify code block language
* By default on no specific mention of programming language, bash is considered

> Syntax 

```
    ```ProgrammingLanguageName
        npm install
        npm start
    ```

```

> For Example
* Bash Command
```bash
npm install
npm start
```

* Java
```java
public static void main(String args[]){
    System.out.println("Hello World in GitHub Markdown Code Block!");
}
```

* C++
```c++ 
#include<iostream.h>
using namespace std;
void main(){
    cout<<"Hello World in GitHub Markdown Code Block!";
}
```

* JavaScript
```javascript 
function add(num1, num2){
    return num1 + num2;
}
```

* Python
```python 
def add(num1, num2):
    return num1 + num2
```

### 2. Tables
* Purpose: To display tables 
* \'|' symbol is used

> Syntax
```
| Column 1 | Column 2 |
| -------- | -------- |
| Content  | Content  |
```

> For Example

|Name|Email|
|----|-----|
|Student 1 | student123@gmail.com|
|Student 2 | student456@gmail.com|


### 3. Task Lists
* Purpose: To display Checkboxes
* \'[ ]' symbol is used which is Un-Ordered List
* x in square brackets represents the completed tasks and otherwise incomplete

> Syntax
```
* [x]Task 1 

* [ ]Task 2
```

> For Example

* [x] Learn Markdown `<!-- Complete Task-->`
* [x] Push to GitHub Repository `<!-- Incomplete Task-->`
* [ ] Pending `<!-- Incomplete Task-->`


#### Thank you
#### Author - Abhinavg916@gmail.com
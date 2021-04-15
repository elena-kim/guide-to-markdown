# the-easiest-markdown
### About us

> &nbsp; :adult: __James Lee__ &nbsp;&nbsp; [Github](https://github.com/devncore-james) &nbsp;&nbsp; james.lee@devncore.org  
> &nbsp; :woman: __Elena Kim__ &nbsp;&nbsp; [Github](https://github.com/devncore-elena) &nbsp;&nbsp; elena.kim@devncore.org

We are very ordinary developers, so we need to communicate with you.   
You can always share information with us and we are looking forward to it.  

##### _Open Source &nbsp; https://github.com/devncore/devncore   &nbsp;&nbsp;   Official Website &nbsp; https://devncore.org_ 

### License Policy
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)

***
## Overview
- [What is the Markdown?](#what-is-the-markdown)
- [Where can we use Markdown?](#where-can-we-use-markdown)
- [How to use Markdown?](#how-to-use-markdown)
<br />

## _What is the Markdown?_
<img src="https://github.com/devncore/theeasiestmarkdown/blob/main/images/markdown-logo.png?raw=true" width="180" height="120"></img>

__Markdown__ is a lightweight markup language for creating formatted text using a plain-text editor.
John Gruber and Aaron Swartz created Markdown in 2004 as a markup language that is appealing to human readers in its source code form.
Markdown is widely used in blogging, instant messaging, online forums, collaborative software, documentation pages, and readme files.

<br/>

## _Where can we use Markdown?_
  - Github
  - Bitbucket
  - Reddit
  - Diaspora
  - Stack Exchange
  - [DotNetDev](https://dotnetdev.kr)
  - ETC...
<br />

## _How to use Markdown?_
- [Header](#1-header)
- [Paragraph](#2-paragraph)
- [List](#3-list)
- [Emphasis](#4-emphasis)
- [Block Quote](#5-block-quote)
- [Code](#6-code)
- [Link](#7-link)
- [Images](#8-images)
- [Table](#9-table)
- [CheckBox](#10-checkbox)
- [ETC](#99-etc)
<br />

## 1. Header
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

<br />

> Header 1 and Header 2 are same as below.  

```
Header 1
=========
Header 2
---------
```

Header 1
=========
Header 2
---------

<br />

## 2. Paragraph
### 2.1 New Line

- `<br/>`
- `space keypress twice`

```
Hello,
world!
  
Hello, <br /> world!

Hello,(␠␠)  
world!
```

Hello,
world!
  
Hello, <br /> world!

Hello,    
world!

<br />

### 2.2 Horizon
```
* * *

***

*****

- - -

---------------------------------------
```

* * *

***

*****

- - -

---------------------------------------

<br />

## 3. List
### 3.1 Unordered : `-`, `*`, `+`
```
- Unordered
  - hyphen
    - hyphen
  * asterisks
    + plus
    + plus
```

- Unordered
  - hyphen
    - hyphen
  * asterisks
    + plus
    + plus
<br />

### 3.2 Ordered : number
```
1. First
1. Second
1. Third
    1. First
    1. Second
    1. Third
```

1. First
1. Second
1. Third
    1. First
    1. Second
    1. Third

<br />

## 4. Emphasis
```
*Italic* or _Italic_  
**Bold** or __Bold__
**_Italic_ and Bold**
~~Cancle~~
<ins>Underline</ins>  
```

*Italic* or _Italic_  
**Bold** or __Bold__  
**_Italic_ and Bold**  
~~Cancle~~  
<ins>Underline</ins>  


<br />

## 5. Block Quote

```
> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
```

> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
 
<br />

## 6. Code
### 6.1 Inline Code
```
For example, `MessageBox.Show("The Easiest Markdown!")`.
```

For example, `MessageBox.Show("The Easiest Markdown!")`.

<br />

### 6.2 Code Block 
#### 6.2.1 Indent
```
For example, 

    MessageBox.Show("The Easiest Markdown!"). 
    
Enter space four times or press tab.
```


For example, 

    MessageBox.Show("The Easiest Markdown!"). 
    
Enter space four times or press tab.


#### 6.2.2 Multiline

<pre>
<code>
```
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```
</code>
</pre>
  
```
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```

#### 6.2.3 Code Highlight

<pre>
<code>
```C#
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```
</code>
</pre>

```C#
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```

<br />

## 7. Link
### 7.1 Inline Link
```
[DevNcore](https://devncore.org)
**Octocat** [:octocat:](https://github.com/octocat) 

```
[DevNcore](https://devncore.org)  
**Octocat** [:octocat:](https://github.com/octocat) 

<br />

### 7.2 Url & Email
```
- DevNcore: https://devncore.org
- Stackoverflow : <https://stackoverflow.com/>
- DevNcoreOfficial : <opensource@devncore.org>
```
- DevNcore: https://devncore.org
- Stackoverflow : <https://stackoverflow.com/>
- DevNcoreOfficial : <opensource@devncore.org>
<br />

### 7.3 Reference
```
Stackoverflow [Stackoverflow][home]

[home]: https://stackoverflow.com "Come and join stackoverflow"
```

Stackoverflow [Click Here][home]

[home]: https://stackoverflow.com "Come and join stackoverflow"
<br />

## 8. Images
### 8.1 Connect Link
```
![Github](/images/github_octocat.png)
```

![Github](https://user-images.githubusercontent.com/52397976/111568560-526b7780-87e4-11eb-857e-1301063d8c63.png)
<br />

### 8.2 Resize
```
<img src="/images/github_octocat.png" width="300" height="300"></img><br />
<img src="/images/github_octocat.png" width="200" height="200"></img>
```

<img src="https://user-images.githubusercontent.com/52397976/111568582-5c8d7600-87e4-11eb-8c66-8f12aeb4a886.png" width="300" height="300"></img><br />
<img src="https://user-images.githubusercontent.com/52397976/111568615-68793800-87e4-11eb-8cf8-2e95f88f2b1c.png" width="200" height="200"></img>

<br />

## 9. Table
```
|Title                  |Actor                                        |Opening Date|
|:----------------------|:--------------------------------------------|:----------:|
|Black Widow            |Scarlett Johansson, Florence Pugh            |2021.04.29  |
|Eternals               |Christopher Catesby Harington, Angelina Jolie|2021.02.12  |
|Spider-Man: No Way Home|Tom Holland, Jamie Foxx, Tobey Maguire       |2021.12.17  |
```

|Title                  |Actor                                        |Opening Date|
|:----------------------|:--------------------------------------------|:----------:|
|Black Widow            |Scarlett Johansson, Florence Pugh            |2021.04.29  |
|Eternals               |Christopher Catesby Harington, Angelina Jolie|2021.02.12  |
|Spider-Man: No Way Home|Tom Holland, Jamie Foxx, Tobey Maguire       |2021.12.17  |

<br />

## 10. CheckBox
```
- [ ] To do
- [x] Done
```

- [ ] To do
- [x] Done
<br />

## 99. ETC
### 99.1 Emoji
```
:+1: :metal: :octocat:
```
:+1: :metal: :octocat:

You can check emoji-cheat-sheet in [here](https://github.com/devncore/emoji-cheat-sheet).

<br />

### 99.2 Badge
https://shields.io/

```
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)
[![Github all releases](https://img.shields.io/github/downloads/Naereen/StrapDown.js/total.svg)](https://GitHub.com/Naereen/StrapDown.js/releases/)
```

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://lbesson.mit-license.org/)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)
[![Github all releases](https://img.shields.io/github/downloads/Naereen/StrapDown.js/total.svg)](https://GitHub.com/Naereen/StrapDown.js/releases/)

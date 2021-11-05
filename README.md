<div align=center>
  <h2>The Easiest Markdown</h2>
  <br/>
 
  이 레포지토리는 DevNcore팀이 관리하고 있습니다.
  <br />
  
  <a href="https://github.com/devncore/devncore"><strong>더 알아보기 »</strong></a>
 
  <br />
 
  <p align="center">
   <a href="https://github.com/devncore/the-easiest-markdown/stargazers"><img src="https://img.shields.io/github/stars/devncore/the-easiest-markdown" alt="Github Stars"></a>
   <img src="https://img.shields.io/github/license/devncore/the-easiest-markdown" alt="License">
   <a href="https://github.com/devncore/the-easiest-markdown/pulse"><img src="https://img.shields.io/github/commit-activity/m/devncore/the-easiest-markdown" alt="Commits-per-month"></a>
 </p>
</div>

  <br />
  

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
- [Backslash Escapes](#11-backslash-escapes)
- [Youtube Video Link](#12-youtube-video-link)
- [Collapsible Section](#13-collapsible-section)
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

- `<br />`
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
Stackoverflow [Click Here][home]

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

## 11. Backslash Escapes
Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown’s formatting syntax.
```
\*literal asterisks\*
```
\*literal asterisks\*

<br />
Markdown provides backslash escapes for the following characters:

```
\ backslash        () parentheses
` backtick          # hash mark
* asterisk          _ underscore
{} curly braces    [] square brackets
+ plus sign         - minus sign (hyphen)
. dot               ! exclamation mark
```

<br />

## 12. Youtube Video Link
Markdown does not support video embed by default, but you can use images to link YouTube video. 

```
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/default.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI) 
```
**`Fp9pNPdNwjI`** is the unique address of the video and you can check the YouTube video link.  
![link](https://i.stack.imgur.com/NiGiv.png)

And there are some **size options**.
#### `/default`, `/1`, `/2`, `/3`
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/default.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)  
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/1.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)  
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/2.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)  
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/3.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)  

#### `/mqdefault`
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/mqdefault.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)  

#### `/hqdefault`
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/hqdefault.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)  

#### `/sddefault`
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/sddefault.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)

#### `/maxresdefault`
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/maxresdefault.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI)

#### ✔️ You can also specify the start point of the video when the image is clicked.  
> Just add `?t=` followed by The unique code of the video link.

#### `second`
```
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/mqdefault.jpg)](https://youtu.be/Fp9pNPdNwjI?t=29)  
```
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/mqdefault.jpg)](https://youtu.be/Fp9pNPdNwjI?t=29)  

#### `minute&second`
```
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/mqdefault.jpg)](https://youtu.be/Fp9pNPdNwjI?t=1m24s)
```
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/mqdefault.jpg)](https://youtu.be/Fp9pNPdNwjI?t=1m24s)

#### `hour&minute&second`
```
[![The Greatest Showman](https://img.youtube.com/vi/gQa8bAtZkiY/mqdefault.jpg)](https://youtu.be/gQa8bAtZkiY?t=1h5m10s)
```
[![The Greatest Showman](https://img.youtube.com/vi/gQa8bAtZkiY/mqdefault.jpg)](https://youtu.be/gQa8bAtZkiY?t=1h5m10s)

<br />

## 13. Collapsible Section
```
<details>
  <summary>Click to expand!</summary>

  ## Heading
  > `tag`
  1. A numbered
  2. list
     * With some
     * Sub bullets  

    ```c#
    Console.WriteLine(Hello World!);
    ```
</details>
```

<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  > `tag`
  1. A numbered
  2. list
     * With some
     * Sub bullets  
     
  ```c#
  Console.WriteLine(Hello World!);
  ```
</details>

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

 

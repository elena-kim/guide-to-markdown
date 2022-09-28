## Guide to Markdown

<img src="https://github.com/devncore/theeasiestmarkdown/blob/main/images/markdown-logo.png?raw=true" width="180" height="120"></img>

**마크다운(Markdown)** 은 일반 텍스트 편집기를 사용하여 정형화된 텍스트를 만들기 위한 경량 마크업 언어입니다. 2004년 John Gruber와 Aaron Swartz에 의해 만들어졌으며, 문법이 간단하기 때문에 사람들이 쉽게 읽고 쓸 수 있습니다. 마크다운은 블로그, 메신저, 온라인 포럼, 협업 소프트웨어, 문서 페이지 및 README 파일에 널리 사용되고 있습니다.


## Contents
- [Header](#1-header-)
- [문단](#2-문단-)
- [List](#3-list-)
- [강조](#4-강조-)
- [인용구](#5-인용구-)
- [Code](#6-code-)
- [링크](#7-링크-)
- [이미지](#8-이미지-)
- [테이블](#9-테이블-)
- [체크박스](#10-체크박스-)
- [백슬래시 이스케이프](#11-백슬래시-이스케이프-)
- [유튜브 동영상 링크](#12-유튜브-동영상-링크-)
- [Collapsible Section](#13-collapsible-section-)
- [ETC](#99-etc-)
<br />

## 1. Header [🔝](#contents)
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

> Header 1과 Header 2는 아래와 같이 표현할 수도 있습니다.  

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

## 2. 문단 [🔝](#contents)
### 2.1 개행

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

### 2.2 수평선
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

## 3. List [🔝](#contents)
### 3.1 순서가 없는 경우 : `-`, `*`, `+`
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

### 3.2 순서가 있는 경우 : 숫자
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

## 4. 강조 [🔝](#contents)
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

## 5. 인용구 [🔝](#contents)

```
> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
```

> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
 
<br />

## 6. Code [🔝](#contents)
### 6.1 인라인 코드
```
For example, `MessageBox.Show("The Easiest Markdown!")`.
```

For example, `MessageBox.Show("The Easiest Markdown!")`.

<br />

### 6.2 코드 블럭 
#### 6.2.1 들여쓰기
```
For example, 

    MessageBox.Show("The Easiest Markdown!"). 
    
Enter space four times or press tab.
```


For example, 

    MessageBox.Show("The Easiest Markdown!"). 
    
Enter space four times or press tab.


#### 6.2.2 여러 줄의 코드

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

#### 6.2.3 코드 하이라이트
<code>```</code> 뒤에 하이라이팅을 적용하고 싶은 언어를 명시합니다. (C#, java, python 등등)

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

## 7. 링크 [🔝](#contents)
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

## 8. 이미지 [🔝](#contents)
### 8.1 Connect Link
```
![Github](/images/github_octocat.png)
```

![Github](https://user-images.githubusercontent.com/52397976/111568560-526b7780-87e4-11eb-857e-1301063d8c63.png)
<br />

### 8.2 사이즈 조정 
```
<img src="/images/github_octocat.png" width="300" height="300"></img><br />
<img src="/images/github_octocat.png" width="200" height="200"></img>
```

<img src="https://user-images.githubusercontent.com/52397976/111568582-5c8d7600-87e4-11eb-8c66-8f12aeb4a886.png" width="300" height="300"></img><br />
<img src="https://user-images.githubusercontent.com/52397976/111568615-68793800-87e4-11eb-8cf8-2e95f88f2b1c.png" width="200" height="200"></img>

<br />

## 9. 테이블 [🔝](#contents) 
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

## 10. 체크박스 [🔝](#contents) 
```
- [ ] To do
- [x] Done
```

- [ ] To do
- [x] Done
<br />

## 11. 백슬래시 이스케이프 [🔝](#contents) 
마크다운에서는 \*, \`, \\ 와 같이 특별한 의미를 가진 마크업 문자 그 자체를 얻기 위해서 backslash(\\)를 사용합니다. 
```
\*literal asterisks\*
```
\*literal asterisks\*

<br />

마크다운은 아래 문자들에 대해 백슬래시 이스케이프를 제공합니다.   

```
\ backslash        () parentheses
` backtick          # hash mark
* asterisk          _ underscore
{} curly braces    [] square brackets
+ plus sign         - minus sign (hyphen)
. dot               ! exclamation mark
```

<br />

## 12. 유튜브 동영상 링크 [🔝](#contents)
마크다운은 기본적으로 동영상 삽입 기능을 지원하지 않지만, 이미지를 사용해서 유튜브 영상 링크를 연결시킬 수 있습니다.

```
[![Black Widow](https://img.youtube.com/vi/Fp9pNPdNwjI/default.jpg)](https://www.youtube.com/watch?v=Fp9pNPdNwjI) 
```
**`Fp9pNPdNwjI`** 이 부분이 동영상의 고유 주소이며 유튜브 영상 링크에서 확인할 수 있습니다.   
![link](https://i.stack.imgur.com/NiGiv.png)

또한 몇 가지 **사이즈 옵션** 도 존재합니다.
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

#### ✔️ 이미지를 클릭했을 때 영상의 시작 시간을 지정할 수도 있습니다.   
> 영상의 고유 주소 바로 뒤에 `?t=`를 추가하여 시간을 표시합니다. 

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

## 13. Collapsible Section [🔝](#contents)
```
<details>
  <summary>펼쳐보기</summary>

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
  <summary>펼쳐보기</summary>
  
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

## 99. ETC [🔝](#contents)
### 99.1 Emoji
```
:+1: :metal: :octocat:
```
:+1: :metal: :octocat:

[emoji-cheat-sheet](https://github.com/devncore/emoji-cheat-sheet)에서 더 많은 이모지를 확인해보세요.

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

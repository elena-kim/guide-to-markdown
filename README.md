# theeasiestmarkdown

- What is the Markdown?  
- Why we should study Markdown?
- How to use Markdown?  
- Where can we use Markdown?  

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

### 3.2 Ordered : Number
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

*****
For example, 

    MessageBox.Show("The Easiest Markdown!"). 
    
Enter space four times or press tab.
*****

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
``` C#
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
```
[DevNcore](https://devncore.org)
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
<br />

## 10. CheckBox
<br />

## 99. ETC
### 99.1 Emoji

### 99.2 Badge

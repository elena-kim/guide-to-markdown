# theeasiestmarkdown

__What is the `Markdown`?__  
__Why we should study `Markdown`?__  
__How to use `Markdown`?__  
__Where can we use `Markdown`?__  

# 1. Header
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

# 2. Paragraph
## 2.1 New Line

- `<br/>`
- `space keypress twice`

```
Markdown is useful,
isn't it?
  
Markdown is useful, <br /> isn't it?

Markdown is useful,(␠␠)  
isn't it?
```

Markdown is useful,
isn't it?
  
Markdown is useful, <br /> isn't it?
  
Markdown is useful,  
isn't it?

<br />

## 2.2 Horizon
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

# 3. List
## 3.1 Unordered : `-`, `*`, `+`
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

## 3.2 Ordered : Number
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

# 4. Emphasis
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

# 5. Block Quote

```
> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
```

> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
 
<br />

# 6. Code
## 6.1 Inline Code
```
For example, `MessageBox.Show("The Easiest Markdown!")`.
```

For example, `MessageBox.Show("The Easiest Markdown!")`.

<br />

## 6.2 Code Block 
### 6.2.1 Indent
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

### 6.2.2 Multiline

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

### 6.2.3 Code Highlight

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

# 7. Link
## 7.1 Inline Link
```
[DevNcore](https://devncore.org)
```
[DevNcore](https://devncore.org)
<br />

## 7.2 Url & Email
```
- DevNcore: https://devncore.org
- Stackoverflow : <https://stackoverflow.com/>
- DevNcoreOfficial : <opensource@devncore.org>
```
- DevNcore: https://devncore.org
- Stackoverflow : <https://stackoverflow.com/>
- DevNcoreOfficial : <opensource@devncore.org>
<br />

## 7.3 Reference
```
`The Easiest Series`  
The Easiest Git [Github][git]

[git]: https://github.com/devncore/theeasiestgit "Let's get started!"
```

`The Easiest Series`  
The Easiest Git [Github][git]

[git]: https://github.com/devncore/theeasiestgit "Let's get started!"
<br />

# 8. Images
## 8.1 Connect Link

## 8.2 Resize
<br />

# 9. Table
<br />

# 10. CheckBox
<br />

# 99. ETC
## 99.1 Emoji

## 99.2 Badge

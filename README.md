# theeasiestmarkdown

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

# 3. Emphasis
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

# 4. Block Quote

```
> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
```

> Write a block quote.
>> You can make nested block quote.
>>> theeasiestmarkdown
 
<br />

# 5. Code
## 5.1 Inline Code
```
For example, `MessageBox.Show("The Easiest Markdown!")`.
```
For example, `MessageBox.Show("The Easiest Markdown!")`.

<br />

## 5.2 Code Block 

```
For example, 
  MessageBox.Show("The Easiest Markdown!"). 
Enter space four times or press tab.
```
For example, 
  MessageBox.Show("The Easiest Markdown!"). 
Enter space four times or press tab.

<br />

```
```
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```
```

```
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```

<br />

```
``` C#
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```
```

``` C#
public ICommand Command
{
    get { return (ICommand)this.GetValue(CommandProperty); }
    set { this.SetValue(CommandProperty, value); }
}
```

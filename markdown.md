# Mastering Markdown
It's very easy to make some words **bold** and other words *italic* with Markdown. You can even [link to Google!](http://google.com)

[Emphasis](#emphasis)

[Task Lists](#task-lists)

[Tables](#tables)

# Headers
# This is an h1 tag
## This is an h2 tag
###### This is an h6 tag
  This is a sentence under h6
# Emphasis 
*This text will be italic*
_This will also be italic_

**This text will be bold**. 
__This will also be bold__. 
__Testing my own bold__. 
_You **can** combine them_.   
# Lists
## Unordered 
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  * Item 2 c
* Item 3
  * Item 3a
    * Item 3aa
## Ordered
1. Item 1
![GitHub Logo](images/GitIcon.png "This is GitCat")
1. Item 2
![GitHub Logo](images/GitIcon.png "This is GitCat")
1. Item 3
   1. Item 3a
   1. Item 3b
## Images

![GitHub Logo](images/GitIcon.png "This is GitCat")

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](images/GitIcon.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: images/GitIcon.png "Logo Title Text 2"

## Links
http://github.com - automatic!

[GitHub](http://github.com)
## Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

## Inline code
I think you should use an
`<addr>` element here instead.
# GitHub Flavored Markdown
## Syntax highlighting
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```
You can also simply indent your code by four spaces:
```javascript
 function fancyAlert(arg) {
      if(arg) {
        $.facebox({div:'#foo'})
      }
    }
```
Here’s an example of Python code with syntax highlighting:
``` python
def foo():
    if not bar:
        return True
```
## Task Lists
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
        
## Tables
#### Simple table

First Header | Second Header
-------------|--------------
Content from cell 1 | Content from cell 2
Content in column 1 | Content in Column 2

#### More complex table

| Command | Description |
| --- | --- |
| git status | List all new or modified files |
| git diff | Show file differences that haven't been staged |

#### Formatting content within a table

| Command | Description |
| --- | --- |
| `git status` | List all *new or modified* files |
| `git diff` | Show file differences that **haven't been** staged |

#### Aligning text in a table

| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |

#### Including a pipe as content in a table

| Name     | Character |
| ---      | ---       |
| Backtick | `         |
| Pipe     | \|        |


## Automatic linking for URLs
Any URL such as http://www.github.com/ will be automatically converted into a clickable link.

## Strikethrough
Any word wrapped with two tildes (like ~~this~~) will appear crossed out.

More ~~strikethough~~. 
~~what's the problem?~~

## Emoji
:confused:

:argentina:

:red_circle:

:restroom:
❤

😊

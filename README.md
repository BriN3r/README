Brianna's Markdown Cheatsheet
📝 Typography
Heading 1
Markup :

# Heading 1
Alternative markup :

============= (below H1 text)
Heading 2
Markup :

## Heading 2
Alternative markup :

--------------- (below H2 text)
Heading 3
Markup :

### Heading 3
Heading 4
Markup :

#### Heading 4
Common text

Markup :

Common text
Emphasized text

Markup :

_Emphasized text_ or *Emphasized text*
Strikethrough text

Markup :

~~Strikethrough text~~
Strong text

Markup :

__Strong text__ or **Strong text**
Strong emphasized text

Markup :

___Strong emphasized text___ or ***Strong emphasized text***
Named Link and http://www.google.fr/ or http://example.com/

Markup :

[Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>
Link to heading or Link to section

Markup:

[Link to heading](#heading-1 "Goto heading-1") or [Link to section](#TOP)
🧮 Tables
A standard table

First Header	Second Header
Content Cell	Content Cell
Content Cell	Content Cell
Markup :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
Adding a pipe | in a cell :

First Header	Second Header
Content Cell	Content Cell
Content Cell	|
Markup :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 
Left, right and center aligned table

Left aligned Header	Right aligned Header	Center aligned Header
Content Cell	Content Cell	Content Cell
Content Cell	Content Cell	Content Cell
Markup :

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
👩‍💻 Code
Inline code

code()

Markup :

`code()`
Code block

var myGreatVariable = 'test'
Markup :

```javascript
var myGreatVariable = 'test'
```
📜 Lists
Unordered list

Bullet list
Nested bullet
Sub-nested bullet etc
Bullet list item 2
Markup :

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2
Alternative markup :

- Bullet list
    - Nested bullet
        - Sub-nested bullet etc
- Bullet list item 2 
Numbered list

A numbered list
A nested numbered list
Which is numbered
Which is numbered
Markup :

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered
Alternative markup (the numbering is automatic):

1. A numbered list
    1. A nested numbered list
    1. Which is numbered
1. Which is numbered
Task list

 An uncompleted task
 A completed task
 A subtask
Markup :

- [ ] An uncompleted task
- [x] A completed task
    - [ ] A subtask
🗣️ Quoting
Blockquote

Nested blockquote

Markup :

> Blockquote
>> Nested Blockquote
Footnotes (see end of README)

Here is a simple footnote1.

A footnote can also have multiple lines2.

Markup :

Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, Add a carriage return and prefix the new line with 4 spaces.

    This is a second line.
🖼️ Media / Emojis
Image with alt :

picture alt

Markup :

![picture alt](https://placehold.co/600x200 "Title is optional")
Emoji

❗ Use emoji icons to enhance text. 👍 Look up emoji codes at emoji-cheat-sheet.com

Markup (Emoji slug should appear between colons):

:+1: :exclamation:
⁉️ Alerts
Note

Highlights information that users should take into account, even when skimming.

Markup :

> [!NOTE]  
> Highlights information that users should take into account, even when skimming.
Tip

Optional information to help a user be more successful.

Markup :

> [!TIP]
> Optional information to help a user be more successful.
Important

Crucial information necessary for users to succeed.

Markup :

> [!IMPORTANT]  
> Crucial information necessary for users to succeed.
Warning

Critical content demanding immediate user attention due to potential risks.

Markup :

> [!WARNING]  
> Critical content demanding immediate user attention due to potential risks.
Caution

Negative potential consequences of an action.

Markup :

> [!CAUTION]
> Negative potential consequences of an action.
💬 Misc
Foldable text

Markup :

<details>
    <summary>Title 1</summary>
    <p>Lorem ipsum dolor sit amet, ...</p>
</details>
Hotkey

⌘F

Markup :

<kbd>⌘F</kbd>
Hotkey symbols handy list below

Key	Symbol	Key	Symbol
Option	⌥	Power	⌽
Control	⌃	Return	↩
Command	⌘	Delete	⌫
Shift	⇧	Up	↑
Caps Lock	⇪	Down	↓
Tab	⇥	Left	←
Esc	⎋	Right	→
Horizontal line

Markup :

- - - -
Inline mathematical equation 
F
(
x
)
=
∫
b
a
1
3
x
3

Markup :

$F(x) = \int^a_b \frac{1}{3}x^3$
Block mathematical equation

P
(
A
=
2
,
|
,
A
2
B
>
4
)

Markup :

$$P \left( A=2 \, \middle| \, \dfrac{A^2}{B}>4 \right)$$
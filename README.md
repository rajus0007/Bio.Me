#### kj kj  kj jk kj j kj k
### kj kj  kj jk kj j kj k
## kj kj  kj jk kj j kj k
## kj kj  kj jk kj j kj k

jkjkjkjj
***
***kj kj***

*jk  j kjj k*

**kj kj**

`vim ics.sh`

```bash
vim ics.sh
```

> After quote use space.

> After quote use space.
There's more

For line break use *** not ---


 For line break use *** or ----- not ---
***

1. k kj
2. kj k

* kjkj


* kj kj
  * kj jk
  * kj kj
    [link](http://imran-hossain.ml)



<u> Text to be underlined </u>

<span style="background-color: rgb(00, 100, 0);">
Text to be highlighted
</span>

This is inline <span style="font-family: consolas; font-size: 14px"> monospace</span> text hi


<div style="font-family: Times New Roman; font-size: 12pt">
This is 12pt Times New Roman for writing papers.
</div>


1. First ordered list item
2. 
   
   
   Another item.a. Two spaces for lettered listb. Add two trailing spaces to create new lettered itemc. Third lettered list
   * Three or four spaces for unordered sub sub list
   * Three or four spaces for unordered sub sub list
   1. 
      
      Three or four spaces for ordered sub sub lista. Lettered listb. Lettered list
   2. Ordered list on same level

* Unordered List
  1. Ordered sub list
  * Unordered sub sub list
    * Unordered sub list
      1. Seven spaces for ordered sub sub sub sub list
      2. Seven spaces for ordered sub sub sub sub list
  1. Numbered list doesn't resume


| Tables | Are | Cool |
|----|:---:|---:|
| col 2 is | centered | $149 |
| col 3 is | right-aligned | $4.17 |
| privacy is | neat | $2.48 |
| rows don't need to | be pretty | what? |
| the last line is | unnecessary | really? |
| one more | row | Yay! 😆 |


$$
int_0^infty f(x)dx
$$

> does not work on markdown

You can create footnote references that are short[^1] or long.[^2]
You can also create them inline.^[which may be easier,
since you don't need to pick an identifier and move down to type the note]
The footnotes are automatically numbered at the bottom of your note,
but you'll need to manually number your superscripts.
Make sure to count your variable[^variable] footnotes.[^5]

[^1]: Here's a footnote.
[^2]: Here’s a footnote with multiple blocks.

```
Subsequent paragraphs are indented to show that they belong to the previous footnote.

    { eight spaces for some code }

The whole paragraph can be indented, or just the first
line. In this way, multi-paragraph footnotes work like
multi-paragraph list items.
```

This paragraph won’t be part of the footnote, because it
isn’t indented.

[^variable]: The variable footnote is the fourth footnote.
[^5]: This is the fifth footnote.

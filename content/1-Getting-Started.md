---
title: Getting Started
nav: true
--- 

When conducting college-level research, there is a general process to follow:


An h1 header
============

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
look like:

  * this one
  * that one
  * the other one

Note that --- not considering the asterisk --- the actual text
content starts at 4-columns in.

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.

Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all
in chapters 12--14"). Three dots ... will be converted to an ellipsis.
Unicode is supported. ☺



An h2 header
------------

Here's a numbered list:

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of
indenting the block, you can use delimited blocks, if you like:

~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~

(which makes copying & pasting easier). You can optionally mark the
delimited block for Pandoc to syntax highlight it:

~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print i
~~~



### An h3 header ###

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a link to [a website](http://foo.bar), to a [local
doc](local-doc.html), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Footnote text goes here.

Tables can look like this:

size  material      color
----  ------------  ------------
9     leather       brown
10    hemp canvas   natural
11    glass         transparent

Table: Shoes, their sizes, and what they're made of

(The above is the caption for the table.) Pandoc also supports
multi-line tables:

--------  -----------------------
keyword   text
--------  -----------------------
red       Sunsets, apples, and
          other red or reddish
          things.

green     Leaves, grass, frogs
          and other things it's
          not easy being.
--------  -----------------------

A horizontal rule follows.

***

Here's a definition list:

apples
  : Good for making applesauce.
oranges
  : Citrus!
tomatoes
  : There's no "e" in tomatoe.

Again, text is indented 4 spaces. (Put a blank line between each
term/definition pair to spread things out more.)

Here's a "line block":

| Line one
|   Line too
| Line tree

and images can be specified like so:

![example image](example-image.jpg "An exemplary image")

Inline math equations go in like so: $\omega = d\phi / dt$. Display
math should get its own line and be put in in double-dollarsigns:

$$I = \int \rho R^{2} dV$$

And note that you can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.















 
## Now let’s talk about Boolean logic. 

## Boolean Logic

Boolean logic uses Boolean operators (such as `AND`, `OR`, `NOT`) to narrow, expand, or define a search, and is applicable to conducting searches in library catalog and most databases. Writing out your search terms using Boolean operators by connecting pieces of information and coming up with synonyms is a good exercise as it can show wanted results and filter out unrelated results. Below are some of the most common Boolean operators you can use:

<html>
   <head>
      <style>
         table {width: 100%;}
         table, td, th {
            border-collapse: collapse;
            padding: 8px;
            border-bottom: 1px solid #ddd;
         
         th {            
            style="text-align:Center"
            border: 1px solid black;
            padding-top: 12px;
            padding-bottom: 12px;
            background-color: #f1b300;
            color: white;
            }
      </style>
   </head>
   <body>
      <table>
         <tr>
            <th style="background-color: #f1b300; color: white; text-align:Center">Boolean Operator</th>
            <th style="background-color: #f1b300; color: white; text-align:Center">Explanation</th>
            <th style="background-color: #f1b300; color: white; text-align:Center">Example</th>
         </tr>
         <tr>
            <th style="text-align:Center">AND</th>
            <td style="text-align:Left">Each result contains all search terms</td>
            <td style="text-align:Left">banana AND production</td>
         </tr>
         <tr>
            <th style="text-align:Center">" "</th>
            <td style="text-align:Left">Results must include search terms in the defined order</td>
            <td style="text-align:Left">"vegetable oil"</td>
         </tr>
         <tr>
            <th style="text-align:Center">OR</th>
            <td style="text-align:Left">Each result contains at least one search term</td>
            <td style="text-align:Left">"vegetable oil" OR crisco</td>
         </tr>
          <tr>
            <th style="text-align:Center">NOT</th>
            <td style="text-align:Left">Results do not contain the specified terms</td>
            <td style="text-align:Left">"packaged chicken" NOT "whole chicken"</td>
         </tr>
         <tr>
            <th style="text-align:Center">*</th>
            <td style="text-align:Left">Results can include search terms with different endings of the root word</td>
            <td style="text-align:Left">avocado* [for avocado and avocados]</td>
         </tr>         
         <tr>
            <th style="text-align:Center">?</th>
            <td style="text-align:Left">Results include words with alternative spellings</td>
            <td style="text-align:Left">“pasteuri?ed milk” [for pasteurised milk and pasteurized milk]</td>
         </tr>
          <tr>
            <th style="text-align:Center">( )</th>
            <td style="text-align:Left">Results include the phrase with the order of relationships organized</td>
            <td style="text-align:Left">("white sugar" OR "brown sugar") NOT "liquid sugar"</td>
         </tr>
      </table>
   </body>
   <p>
   </p>
</html>

{% capture text %}You can check out <a href="https://libguides.uidaho.edu/boolean" target="_blank" rel="noopener">this research guide</a> to learn more about Boolean logic.
{% endcapture %}
{% include alert.md text=text color="warning" %}

This file is a Practise file for sublime text 3. It is inspried by vimtutor available on some machine.
It is designed to be done multiple times so that you learn by doing rather than active memorization exercises.

This tutorial is written to work with no additional packages and vintage mode switched off.


ATTENTION
This tutorial was written on a linux machines and some commands will be different on OSX.

This tutorial will modify the text so save a copy. (Or use the fetch package to grab the repo version)

Navigation
----------

In Sublime text 3 as in Sublime text 2 moving around is done using the arrow keys. 
GO TO:

```
X<- The beggining of this line.
The end of this line ->X
And on this final line here ->X somewhere in the middle.
```

Yes it as easy as that.

Advanced Navigation
-------------------
There are several advanced navigation options.

 - Ctrl + LEFT move left to next word beginning
 - Ctrl + RIGHT move right to next word ending

 - Home = move to beginning of the line
 - End = move to the end of the line

 - Ctrl + Home = move to beginning of the document
 - Ctrl + End = move to the end of the document


Simple delete
-------------

 - Ctrl + Backspace = delete left till word beginning
 - Ctrl + Delete = detele right till the end of the word

ThisOOO text OOOhas alot OOOOOO of OOOOunecessary noise00000 

 - Ctrl + (k -> k) = Delete from cursor position untill the end of the line
 - Ctrl + (k -> backspace) = Delete from cursor position untill beginning of the line

Comments
--------

Comments can be toggled on individual lines with cursor(s) in the line to be selected.
Comments can also be applied to multiple lines 

 - Ctrl + '/' to comment uncomment

 <!-- blah -->

<!--  blah
 <!-- blah -->
 blah
 <!-- blah --> -->


Brackets
--------



Selection
---------

Ctrl + l select line including end of line charachter
Ctrl + A select all in file

ctrl+shift+up move line up

Move to points
-------------
there needs to (be a long selection of brackets)
Ctrl + m move to end the beginning of brackets
Wrapping quotes and brackets

Further selection
-----------------

Ctrl+Shift + m expand to brackets
Ctrl + Shift + j expand to indent

multiple versions of above expand the selection by same rules

Ctrl + Shift + Space expand to scope - Ctrl + Shift + Alt + p show scope name
Ctrl + Shift + a Expand to tag

Comment
-------

Ctrl + / comment lines

Line manipulation
-----------------

Ctrl + Shift + j join lines
Ctrl + Shift + d duplicate lines

Upcase/Downcase
---------------
Ctrl (k U)

Fold
----
ctrl+shift+[ fold

Marks
-----

Tag Stuff
---------
Alt + . close tag

Ctrl + q == Exit
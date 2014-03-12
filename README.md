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

> X<- The beggining of this line.
> The end of this line ->X
> And on this final line here ->X somewhere in the middle.

*Yes it as easy as that.*

Advanced Navigation
-------------------
There are several advanced navigation options.
NOTE: If Num lock is on these commands will write a number and not act as described here.

**CTRL + LEFT** move left to next word beginning  
**CTRL + RIGHT** move right to next word ending

**HOME** move to beginning of the line  
**END** move to the end of the line

**CTRL + HOME** move to beginning of the document  
**CTRL + END** move to the end of the document


Delete
------

**CTRL + BACKSPACE** delete left till word beginning  
**CTRL + DELETE** detele right till the end of the word

> *MOODugong  
> DugongONG  
> It's theEPEP cowPAT of the  
> Sea TEAsea sea!*  


**CTRL + (K -> K)** Delete from cursor position untill the end of the line  
**CTRL + (K -> BACKSPACE)** Delete from cursor position untill beginning of the line  
**CTRL + SHIFT + K** Delete whole line


> Dugong this is unecessary  
> Dugong  
> BEWARE the chocolate teapot  
> Also known as the  
> All of these words aren't needed Manatee!  

Line manipulation
-----------------

**CTRL + SHIFT + Up** move line of selection up  
**CTRL + SHIFT + Down** move line of selection down

**CTRL + SHIFT + Return** insert line above current  
**CTRL + Return** insert line below current

This list of my favourite aquatic mammals requires is in disarray.
Reorder it and complete the list your own choices.

> 1. Dugong
> 2. Bottlenosed Dolpin
> 7. Blue Whale
> 8. Beluga
> 4. Narwhal
> 5. Bowhead Whale

Comments
--------

Comments can be toggled on individual lines with cursor(s) in the line to be selected.
Comments can also be applied to multiple lines 

 - CTRL + '/' to comment uncomment

 <!-- blah -->

<!--  blah
 <!-- blah -->
 blah
 <!-- blah --> -->


Brackets
--------

This is along line of code perhaps (or perhaps a comment ( or maybe it is indeed code)a)
CTRL+SHIFT + m expand to brackets

CTRL + m move to end the beginning of brackets
Wrapping quotes and brackets

Selection
---------

CTRL + l select line including end of line charachter
CTRL + A select all in file


CTRL + SHIFT + j join lines
CTRL + SHIFT + d duplicate lines

Further selection
-----------------

CTRL + SHIFT + j expand to indent

multiple versions of above expand the selection by same rules

CTRL + SHIFT + Space expand to scope
CTRL + SHIFT + Alt + p show scope name
CTRL + SHIFT + a Expand to tag


Upcase/Downcase
---------------

CTRL (k U)
CTRL (k l)

Fold
----
CTRL+SHIFT+[ fold

Marks
-----

Tag Stuff
---------
Alt + . close tag

CTRL + q == Exit
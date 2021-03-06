Kata Layout
===========

Pip is a good developer but he is slow on the keyboard: he doesn't touch type.
But, since he is worried about improving his skills, wants to learn. He has
been asking a few colleagues about what layout to learn, but each one
recommends him a different one:

- Abe told that the most used one is **QWERTY** and that is the one best worth
  learning.
  ![US querty layout](http://upload.wikimedia.org/wikipedia/en/thumb/5/51/KB_United_States-NoAltGr.svg/420px-KB_United_States-NoAltGr.svg.png "US querty layout")

- Sebastian has been using **Dvorak** for years and highly recommends it.
  ![Dvorak layout](http://upload.wikimedia.org/wikipedia/commons/thumb/2/25/KB_United_States_Dvorak.svg/420px-KB_United_States_Dvorak.svg.png "Dvorak layout")

- Aimee says that **Colemak** is the best layout out there and that it's easier
  to learn than dvorak.
  ![Colemak layout](http://upload.wikimedia.org/wikipedia/commons/thumb/8/84/KB_US-Colemak.svg/420px-KB_US-Colemak.svg.png "Colemak layout")

Pip has decided to choose the one layout that allows him to write more words
with the home and upper row. But he wants to keep things simple, the only
symbols he wants to take into account are dot `.`, comma `,` and colon
`:`. No other symbols. No numbers. No modifier keys.

How to help Pip
---------------
Test drive a piece of software that given a string, and a layout, returns the
percentage of keys that would be pressed on each row. Uppercase letters are handled exactly the same way as lower case ones.

For example: for the sentence `Apple is my favourite fruit` and the `qwerty`
layout the result should be: `upper: 22.22, home: 55.56, bottom: 22.22`

You don't have to deal with User Interfaces or I/O. Pip will know how to invoke your code: he is a smart guy.

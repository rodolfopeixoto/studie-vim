# LEARN VIM IN PRACTICE

Open the terminal in split below:

+----+----+----+
¦    ¦    ¦    ¦
¦ f1 ¦ f2 ¦ f3 ¦
+----+----+----+
¦   terminal   ¦
+--------------+


```vim
:below terminal

or

:bterm
```

Open file or terminal in vertical terminal

```
:vnew term://bash
:vsplit term://bash
:vnew term://zsh
:vsplit term://zsh
```


Previous buffer -> `CTLR + O`
Next buffer -> `CTLR + i`

Press `d` to cut and `y` to copy

`viw` command in visual select inside the word.

`vat` to select tag.

`va(` to select to down

`va)` to selct to up


`CTLR + w` change the window of terminal vim

```
:sp filename # for a horizontal split
:vsp filename # or :vs filename for a vertical split
```

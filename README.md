## VIM Editor
<p align="justify"> VIM is a terminal based text editor. It is very handy to use. This is the most powerful text editor that by default comes with almost all Unix/Linux system. </p>

Basic guide of VIM editor has given below:

## VIM Editor Basic Commands
```
Insert Mode --> Command = (i)
Escape Mode --> Command = (Esc)
File save and quit --> Command = (:x)
File not save and quit --> Command = (:q!)
Only for Save --> Command = (:w)
Show file line number --> Command = (:set nu)
```

## Cursor Movement
```
h = left
j = down
k = up
l = right
^ = Go to the start of a line
$ = Go to the end of a line
gg = Go to the first line of a file
G = Go to the last line of a file
:n = Go to specific line of a file
```

## Copy/Paste
```
Word copy --> Command (yw)
Word/single line/multiple line Paste --> Command = (p/P)
Single line(yank) copy --> Command = (yy)
Multiple line command --> Command = (5yy)
Letter copy --> Command = (yl)
```

## Insert Text
```
Insert at cursor --> Command = (i)
Insert text at the beginning --> Command = (I)
Append text after cursor --> Command = (a)
Append text at the end of the line --> Command = (A)
Open a new line below the current line --> Command = (o)
Open a new line above the current line --> Command = (O)
```

## Delete Text
```
Delete letter/character --> Command = (x)
Delete/cut line --> Command = (dd)
Delete/cut multiple lines --> Command = (ndd)
Delete/cut word --> Command = (dw)
Delete/cut from the cursor position to the last of the line --> Command = (D)
```

## Undo/Redo
```
Undo --> Command = (u)
Redo --> Command = (Ctrl+r)
```

## Searching from a file
```
/pattern
?pattern
n
N
```

## Find and Replace
```
:%s/old-pattern/new-pattern/gc --> Check confirmation before replace
:%s/old-pattern/new-pattern/g  --> Replace all the pattern at a same time
```

## Save/Quit
```
Write/save file without quit --> Command = (:w)
Save and quit the file --> Command = (:wq or :x)
Just quit the file --> Command = (:q)
Quit from a file without saving --> Command = (:q!)
Forcefully file save and quit --> Command = (:wq!)
```
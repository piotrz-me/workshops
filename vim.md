| Command | Range    | Motion |
|:------:|:---------:|:------:|
| yank   | **f**ind  | $ - end line |
| change | **i**nside | \" ( [ ] ) |
| delete | **a**round   | w - word |
| insert | **t**ill  | p - paragraph |
| = autoident       |           | s - sentence |
| <> indent left/right |           | b - begin of word|
|        |           | e - end of world |
|        |           | t - tag |

#####INSERT MODE

    ^n - autocomplete (^n ^p w gore i w dol)
    ^x^n - tylko z tego pliku
    ^x^f - nazwy plikow z sciezka
    ^x^] - tagi

#####GREP

    :vimgrep cos \*\* lub :grep -R 
    :cn - next 
    :cp - previous
    :clist - lista - better :cw
    :cclose - wyjście z tego trybu

#####FILES

    :find filename tab tab
You can use :sfind instead of :find to open it in a split window, and :tabf to open it in a new tab.

#####Split WINDOWS

ctr-w s - split hori
ctr-w h - split vert
:sp[lit] filename - open new file in horiz split
:vsp[lit] filename - open new file in vertical split

:q - close current window
:on[ly[ - close other windows

ctr-w + - increse size of curr window
ctr-w - - decrese size of curr window
ctr-w > - increse current window width
ctr-w < - decrese curr window width

#####CTAGS

    ^] -> go to tag definition (by ctags)
    ^b -> return






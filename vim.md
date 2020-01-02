
| Command | Range | Motion |
|:-----:|:----:|:------:|
| yank | **f**ind | $ - end line |
| change | **i**nside | \" ( [ ] ) |
| delete | **a**ll | w - word |
| insert | **t**ill | p - paragraph |
|        |          | s - sentence |


#INSERT MODE

    ^n - autocomplete (^n ^p w gore i w dol)

    ^x^n - tylko z tego pliku
    ^x^f - nazwy plikow z sciezka
    ^x^] - tagi

#CTAGS

    ^] -> go to tag definition (by ctags)
    ^b -> return

#GREP

    :vimgrep cos \*\* lub :grep -R 
    :cn - next 
    :cp - previous
    :clist - lista
    :cclose - wyjście z tego trybu

#FILES

    :find filename tab tab
You can use :sfind instead of :find to open it in a split window, and :tabf to open it in a new tab.

    :set list! -> toggle whitechars visible




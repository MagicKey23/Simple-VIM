#VIM
Simple VIM commands
Use as a refernace for basic commands in VIM/VI
https://vimgifs.com/


Commands | Description
-------- | -----------
esc | toggle between command mode or edit mode
shift : | enter command mode
********** | ***********
: + w or : + write | save or write command
: + q or : + quit | exit or :quit
: + wq | exit and save changes
: + q! | exit without saving changes
********** | ***********
K | move up a file
J | move down a file
L | move right a letter
H | move left a letter
W | move up a word
B | move back a word
I | insert mode lets you start typing and takes you out of naviation
V | Visual mode lets you select blocks
shift v | Visual line mode
y | in visual mode press y to copy
p | paste the code in normal mode
** | in command mode
note | Commands are built in up in three parts ACTION LOCATION CONTEXT
dd | delete line
shift + d | delete line leave white space
c + w | delete word and go into insert mode
d + 5 + w | delete 5 words put into insert mode
c + 3 + j | change 3 lines down put into insert mode
c + i + t | deletes text then puts you into insert mode
c + i + { | delets text then puts you into insert mode in a block
side node | these commands can be combined to do many things as the examples above show


Commands | Description
-------- | -----------
configure VIM | -
:syntax on | Syntax highlighting
:syntax off | Syntax disabled
:set number | Added line count
:set nonumber | Remove line numbers
:set relativenumber | Sets number relative to where your cursor is
:set norelativenumber | Remove relative line numbers
:help option-list | shows all options you can set for VIM

<br/>
<br/>
<br/>

---
#NANO
save and exit NANO

Commands | Description
-------- | -----------
Ctrl+O | saves file
esc+M | mac format
Ctrl+X | exit Nano

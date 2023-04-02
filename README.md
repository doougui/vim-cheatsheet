# vim-cheatsheet  

This is my vim cheatsheet. I'll update the contents of this file as I learn new commands.  

# Commands  

**hjkl** = left, bottom, up, right  
**ctrl+v** = visual mode  

**w** = jump to word  
**b** = jump to beginning of word  
**e** = jump to the end of word  
**ge** = jump to the end of previous word backwards  

**f{character}** next occurrence of char in line (F for backwards)  
**t{character}** BEFORE next occurrence of char in line (T for backwards)  
  **;** = go to the next occurrence  
  **,** = go to the previous occurrence  
**/{pattern}** = search forward  
**?{pattern}** = search backwards  
  **n** = = jump to the next match  
**/<Enter>** or **?<Enter>** to repeat the last search  
**\***/**#** = search the word under the cursor (0forward/backward, respectively)  

**dw** = delete word  

**y** = copy  
**p** = paste  

**0** = moves to the first character of a line (**^** for non-blank)  
**$** = moves to the end of a line (**g_** for non-blank)  
**}** = jumps entire paragraphs **downwards**  
**{** = same for **upwards**  

**ctrl+d** = move down half a page  
**ctrl+u** = move up half a page  

Counts:  

**2w** = move cursor 2 words forward  
**5j** = 5 lines below  
**3;** = next third occurrence  
**2/{word}** = second occurrence of {word}  

**gd** = jump to definition  
**gf** = jump to file of import  

**gg** = go to the top of file  
**{line}gg** = go to specified line  
**G** = go to the bottom of file  

Vim

Vim commands that are likely to be used frequently:

1. **Navigation and Basic Editing**:
   - **i**: Enter insert mode at the current cursor position.
   - **a**: Enter insert mode after the cursor.
   - **o**: Open a new line below the current line and enter insert mode.
   - **O**: Open a new line above the current line and enter insert mode.
   - **h, j, k, l**: Move the cursor left, down, up, and right respectively.
   - **w**: Move the cursor forward by one word.
   - **b**: Move the cursor backward by one word.
   - **0**: Move the cursor to the beginning of the current line.
   - **$**: Move the cursor to the end of the current line.
   - **gg**: Move the cursor to the first line of the file.
   - **G**: Move the cursor to the last line of the file.

2. **Saving and Quitting**:
   - **:w**: Save the file.
   - **:q**: Quit Vim.
   - **:wq** or **:x**: Save the file and quit Vim.
   - **:q!**: Quit Vim without saving changes.

3. **Search and Replace**:
   - **/pattern**: Search forward for 'pattern'.
   - **?pattern**: Search backward for 'pattern'.
   - **n**: Move to the next occurrence of the search pattern.
   - **N**: Move to the previous occurrence of the search pattern.
   - **:%s/old/new/g**: Replace all occurrences of 'old' with 'new' in the entire file.
   - **:s/old/new**: Replace the first occurrence of 'old' with 'new' in the current line.
   - **:s/old/new/g**: Replace all occurrences of 'old' with 'new' in the current line.

4. **Copying, Cutting, and Pasting**:
   - **yy**: Yank (copy) the current line.
   - **dd**: Delete the current line.
   - **p**: Paste the most recently yanked or deleted text after the cursor.

5. **Undo and Redo**:
   - **u**: Undo the last change.
   - **Ctrl+r**: Redo the last change that was undone.

These commands provide a practical foundation for using Vim efficiently. 
As you gain more experience, you can explore additional commands and features that align with your specific needs. Remember, practice is key to becoming proficient with Vim.

**Some additional commands**
```
Multiple Windows:

:split: Split the window horizontally.
:vsplit: Split the window vertically.
Ctrl+w, Arrow keys: Move between windows.
Ctrl+w, =: Make all windows equal size.
Ctrl+w, _: Maximize the current window vertically.
Ctrl+w, |: Maximize the current window horizontally

Tabs:
:tabnew: Open a new tab.
:tabnext or gt: Move to the next tab.
:tabprevious or gT: Move to the previous tab.
:tabclose or :tabc: Close the current tab.
Macros:

qa: Start recording a macro into register 'a'.
q: Stop recording the macro.
@a: Execute the macro stored in register 'a'.
@@: Repeat the last executed macro.
Folding:

zf: Create a fold.
zo: Open a fold.
zc: Close a fold.
zr: Reduce folding (open all folds).
zm: More folding (close all folds).
```
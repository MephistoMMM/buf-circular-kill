BufCircularKill
===============

Based On [BufKill 1.10](https://github.com/vim-scripts/bufkill.vim)

**News**:

* Fix bug in updateList(), now just remove the delete buffer' Index, not remove the list end.
* Now change BufKillList to circular list , at the both ends of BufKillList , go back or go formate will go to the another end of BufKillList.
* Add new buffer function
* Change key map to spacemacs-like . e.g: '<leader>bn(p)' to turn to next(prev) buffer, '<leader>bt' to create new buffer , '<leader>bd(!)' to delete this buffer
* Change w:BufKillList and w:BufKillColumnList to global variate , hence it will sync to airline tag bar.

**TODO**:

* some buffers unexpected to be load may be out of BufKillList's contrl, e.g: choose nothing while 'Swap file "/path/to/file" already exists!' 
* it should be more swift and fast
* more details readme
* make user be able to config key maps

**License**:

MIT

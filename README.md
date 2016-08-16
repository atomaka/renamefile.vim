# renamefile.vim

This function, ripped directly from [Gary Bernhardt's dotfiles](https://github.com/garybernhardt/dotfiles)
renames a file in place.

## Usage

This plugin adds the command `:RenameFile`.  When called, it will prompt you for
a new file name.  If the filename is blank or the same as the previous file
name, nothing will happen.  If the new name is different, the file will be
saved as the new name and the old file will be delated.

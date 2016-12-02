
# JBTools

## Paths

Add only the main folder to your path and save it.
» addpath(fileparts(which('jbtools_root.m')));
» savepath();

Whenever you want the toolbox, do this to add all sub-directories to the path
» jbtools_add
You can remove them again with
» jbtools_rm

## Folders

[anonymous](anonymous) : general functions that I would have liked matlab to include. their name does not start with any particular prefix: make sure they're not taking over any pre-existing function / variable!
[cell](cell)     : manipulation of cell variables.
[fig_](figures)  : make nicer figures
[file_](figures) : work with files and lists of files
[matvec](matvec) : manipulate vectors and matrices (or extract matrices from struct datasets)
[struct](struct) : manipulate structs

# Bits
Project: _qtag_ is a tool for quick tag searching, adding and deleting in file names. It can create a directory of symlinks to the found files and open it in the file manager, it can mass-change the filenames adding or removing tags etc.

_qtag_ quickly searches between filenames and retrieves all the filenames that contain certain specified tags (i.e. word beginnings). A symbol ":" before a tag means that the tag is **not** searched for; filenames containing it are excluded. E.g.: "qtag Ari :pdf" finds "Aristotle.txt", "ILoveArithmetics.doc" etc., but not "Aristotle.pdf".

Several options can be added, e.g. "-w" writes symlinks to the found files to a work directory and opens the default file manager, reproducing the directory tree: only the dir.s containing found file names are generated in the work directory. One can thus have a quick look at the found files.

More options are added: non-recursive search, search only for files or for directories, case sensitive search, appending symlinks to files to the work directory etc.

More options for tag management: adding, deleting or replacing tags in the files present in the work directory. Another option for writing to disk all the changes one makes to the symlink filenames in the working directory.

The point is: it's much more handy than "find".

The Python code I have written works but it can be improved in many ways and nedds to be extensively tested. The project can surely be extended.

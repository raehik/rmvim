rmvim
=====

`rmvim` is a simple bash script which finds (using `find`) and removes (using `rm`) files ending with '~' -- that is, Vim backup files. It should only ever remove files ending with '~'.

`rmvim` will remove files with spaces in them. However, not all escape characters have been tested -- I'll bet that something will mess up when you try to remove a file with a newline in it. (Yes, it is possible. And fun.)

Available options are:

        -r		recurse through directories
        -f		force (do not prompt)
        -v		be more verbose

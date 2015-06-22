### Bashmarks is a shell script that allows you to save and jump to commonly used directories. Now supports tab completion.

This is a fork from Huyng's original bashmarks https://github.com/huyng/bashmarks, using keys with prefix ```b```.

## Install

1. git clone git://github.com/harmishhk/bashmarks.git
2. cd bashmarks
3. source **bashmarks.sh** from within your **.zshrc** file

## Shell Commands

    bs <bookmark_name> - Saves the current directory as "bookmark_name"
    bg <bookmark_name> - Goes (cd) to the directory associated with "bookmark_name"
    bp <bookmark_name> - Prints the directory associated with "bookmark_name"
    bd <bookmark_name> - Deletes the bookmark
    bl                 - Lists all available bookmarks

## Example Usage

    $ cd /var/www/
    $ bs webfolder
    $ cd /usr/local/lib/
    $ bs locallib
    $ bl
    $ bg web<tab>
    $ bg webfolder

## Where Bashmarks are stored

All of your directory bookmarks are saved in a file called ".sdirs" in your HOME directory.

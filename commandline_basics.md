# Get to know the command line

## What it is?

CLI is a command-line program that accepts text input to execute operating system functions. Nowadays, with **graphical user interfaces** (GUI), most users never use **command-line interfaces** (CLI).

CLI stands for:

- Command Line Interface
- Command Line Interpreter
- Command Line Input

## Basic Linux CLI commands

### Directory operations

| Command                         | Description                                           |
| ------------------------------- | ----------------------------------------------------- |
| `pwd`                           | show current directory                                |
| `cd` or `cd ~`                  | go to home directory                                  |
| `cd `_`directory`_              | get in (change directory) to _directory_              |
| `cd `_`directory/subdirectory`_ | get in (change directory) to _directory/subdirectory_ |
| `cd ..`                         | go up a directory (get out from current directory)    |
| `cd /`                          | go to root directory                                  |
| `ls`                            | list files in current directory                       |
| `ls -R`                         | also list files in sub-directories                    |
| `ls -a`                         | also list hidden files in current directory           |

### Files and folders operations

| Command                                    | Description                                             |
| ------------------------------------------ | ------------------------------------------------------- |
| `touch `_`filename`_                       | create new file _filename_                              |
| `mkdir `_`directory`_                      | make new _direcory_                                     |
| `move `_`new_location_path`_               | move to new path _new_location_path_                    |
| `move `_`current_filename_ _new_filename`_ | rename (move) from _current_filename_ to _new_filename_ |
| `mv `_`current_dir_name_ _new_dir_name`_   | rename (move) from _current_filename_ to _new_filename_ |
| `cp `_`filename_ _new_location`_           | copy _filename_ to _new_location_                       |
| `rm `_`filename`_                          | delete _filename_                                       |
| `rm -r `_`directory`_                      | delete _directory_                                      |
| `rmdir `_`directory`_                      | delete _directory_                                      |

### CLI operations

| Command         | Description                          |
| --------------- | ------------------------------------ |
| `clear`         | clears the CLI window                |
| `exit`          | close the CLI window                 |
| `man _command_` | Shows the manual for a given command |

## Basic Windows CLI commands

### Directory operations

| Command                         | Description                                           |
| ------------------------------- | ----------------------------------------------------- |
| `chdir`                         | show current directory                                |
| `cd %userprofile%`              | go to home directory                                  |
| `cd `_`directory`_              | get in (change directory) to _directory_              |
| `cd `_`directory/subdirectory`_ | get in (change directory) to _directory/subdirectory_ |
| `cd..`                          | go up a directory (get out from current directory)    |
| `cd\`                           | go to root directory                                  |
| `dir`                           | list files in current directory                       |
| `dir /a`                        | also list files in sub-directories                    |
| `dir /a:h`                      | also list hidden files in current directory           |

### Files and folders operations

| Command                                   | Description                                             |
| ----------------------------------------- | ------------------------------------------------------- |
| `echo `_`some-text > filename.txt `_      | create new file including _some-text_ in _filename.txt_ |
| `mkdir `_`directory`_                     | make new _direcory_                                     |
| `move `_`new_location_path`_              | move to new path _new_location_path_                    |
| `ren `_`current_filename_ _new_filename`_ | rename from _current_filename_ to _new_filename_        |
| `copy `_`filename_ _new_location`_        | copy _filename_ to _new_location_                       |
| `del `_`filename`_                        | delete _filename_                                       |
| `rmdir `_`directory`_                     | delete _directory_                                      |

### CLI operations

| Command            | Description                          |
| ------------------ | ------------------------------------ |
| `cls`              | clears the CLI window                |
| `exit`             | close the CLI window                 |
| `help `_`command`_ | Shows the manual for a given command |

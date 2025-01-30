# Shell Basics Project

This project contains basic shell scripts that demonstrate fundamental Unix/Linux command line operations. Each script performs a specific task to help learn shell navigation, file manipulation, and directory management.

## Scripts Description

* **0-current_working_directory**: Prints the absolute path name of the current working directory
* **1-listit**: Displays the contents list of the current directory
* **2-bring_me_home**: Changes the working directory to the user's home directory
* **3-listfiles**: Displays current directory contents in long format
* **4-listmorefiles**: Displays current directory contents, including hidden files, in long format
* **5-listfilesdigitonly**: Displays directory contents with user/group IDs and hidden files
* **6-firstdirectory**: Creates a directory named `my_first_directory` in `/tmp/`
* **7-movethatfile**: Moves the file `betty` from `/tmp/` to `/tmp/my_first_directory`
* **8-firstdelete**: Deletes the file `betty` from `/tmp/my_first_directory`
* **9-firstdirdeletion**: Deletes the directory `my_first_directory` from `/tmp`
* **10-back**: Changes working directory to the previous one
* **11-lists**: Lists all files in current directory, parent directory, and `/boot` directory
* **12-file_type**: Prints the type of the file named `iamafile` in `/tmp` directory
* **13-symbolic_link**: Creates a symbolic link to `/bin/ls`, named `__ls__`
* **14-copy_html**: Copies all HTML files to parent directory (only newer or non-existent files)
* **15-lets_move**: Moves all files beginning with uppercase letter to `/tmp/u`
* **16-clean_emacs**: Deletes all files in current directory ending with `~`
* **17-tree**: Creates a directory tree `welcome/to/school`

## Requirements

* All scripts are tested on Ubuntu 20.04 LTS
* All scripts are exactly two lines long
* All files end with a new line
* The first line of all files is exactly `#!/bin/bash`
* All scripts are executable
* No backticks, &&, ||, or ; allowed
* All files must pass Shellcheck without any error

## Usage

1. Make scripts executable:
```bash
chmod u+x script-name
```

2. Run script:
```bash
./script-name
```

## Example

```bash
$ ./0-current_working_directory
/root/alu-shell/basics
```

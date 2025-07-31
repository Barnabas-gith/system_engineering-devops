# 0x00. Shell, Basics

## Description
This directory contains basic shell scripts for navigating and manipulating the UNIX file system. It is part of the **System Engineering & DevOps** track and introduces essential shell commands and scripting practices.

## Project Structure
Each file in this directory is a script that performs a specific task as described:

### Script List

| Script Name                    | Description                                              |
|-------------------------------|----------------------------------------------------------|
| `0-current_working_directory` | Prints the absolute path of the current working directory |
| `1-listit`                    | Displays the contents of the current directory           |
| `2-bring_me_home`             | Changes the working directory to the user’s home         |
| `3-listfiles`                 | Lists all files in the current directory (including hidden ones) |
| `4-listmorefiles`             | Lists all files with details (permissions, size, etc.)   |
| `5-listfilesdigitonly`        | Lists files with user and group IDs in numeric format    |
| `6-firstdirectory`            | Creates a directory named `my_first_directory` in `/tmp` |
| `7-movethatfile`              | Moves a file to a specific directory                     |
| `8-firstdelete`               | Deletes a file                                           |
| `9-firstdirdeletion`          | Deletes a directory                                      |
| `10-back`                     | Changes the working directory to the previous one        |
| `11-lists`                    | Lists all contents of current, parent, and `/boot` directories |
| `12-file_type`                | Prints the type of a specific file                       |
| `13-symbolic_link`            | Creates a symbolic link                                  |
| `14-copy_html`                | Copies HTML files from one directory to another          |
| `15-lets_move`                | Moves all files beginning with uppercase letters         |
| `16-clean_emacs`              | Deletes all `~` files (backup files)                     |
| `17-tree`                     | Creates multiple directories and subdirectories          |
| `18-parse_ls`                 | Prints all files and directories using commas            |
| `19-executable`               | Adds execute permission to all regular files             |

## How to Use
To run a script:
```bash
./<script_name>

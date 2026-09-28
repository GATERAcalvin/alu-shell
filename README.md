# alu-shell / basics

Shell basics exercises (tasks 0-17). Each file is a Bash script starting with `#!/bin/bash`.

| File | Description |
|---|---|
| 0-current_working_directory | Prints the absolute path of the current working directory |
| 1-listit | Lists the contents of the current directory |
| 2-bring_me_home | Changes the working directory to the user's home (use `source`) |
| 3-listfiles | Lists the current directory in long format |
| 4-listmorefiles | Long format, including hidden files |
| 5-listfilesdigitonly | Long format, hidden files, numeric user and group IDs |
| 6-firstdirectory | Creates `/tmp/my_first_directory` |
| 7-movethatfile | Moves `/tmp/betty` into `/tmp/my_first_directory` |
| 8-firstdelete | Deletes `/tmp/my_first_directory/betty` |
| 9-firstdirdeletion | Deletes `/tmp/my_first_directory` |
| 10-back | Changes to the previous directory (use `source`) |
| 11-lists | Lists `.`, `..` and `/boot` in long format, including hidden files |
| 12-file_type | Prints the type of `/tmp/iamafile` |
| 13-symbolic_link | Creates a symbolic link `__ls__` to `/bin/ls` |
| 14-copy_html | Copies new or newer `.html` files to the parent directory |
| 15-lets_move | Moves files starting with an uppercase letter to `/tmp/u` |
| 16-clean_emacs | Deletes files ending with `~` |
| 17-tree | Creates `welcome/to/school` in two lines |

## Usage

```
chmod +x *
./0-current_working_directory
```

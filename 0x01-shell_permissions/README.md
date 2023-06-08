# Shell Permissions

This repository contains scripts related to shell permissions.

## Files

* [0-iam_betty](./0-iam_betty): Script that changes your user ID to `betty`.
* [1-who_am_i](./1-who_am_i): Script that prints the effective userid of the current user.
* [2-groups](./2-groups): Script that prints all the groups the current user is part of.
* [3-new_owner](./3-new_owner): Script that changes the owner of the file `hello` to the user `betty`.
* [4-empty](./4-empty): Script that creates an empty file called `hello`.
* [5-execute](./5-execute): Script that adds execute permission to the owner of the file `hello`.
* [6-multiple_permissions](./6-multiple_permissions): Script that adds execute permission to the owner and the group owner, and read permission to others for the file `hello`.
* [7-everybody](./7-everybody): Script that adds execute permission to the owner, the group owner, and the other users for the file `hello`. It represents the final permissions `rwxr-x-wx`.
* [8-James_Bond](./8-James_Bond): Script that sets the permission of the file `hello` to `007`.
* [9-John_Doe](./9-John_Doe): Script that sets the mode of the file `hello` to `-rwxr-x-wx`.
* [10-mirror_permissions](./10-mirror_permissions): Script that sets the mode of the file `hello` to be the same as the file `olleh`.
* [11-directories_permissions](./11-directories_permissions): Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.
* [12-directory_permissions](./12-directory_permissions): Script that creates a directory called `dir_holberton` with permissions `751` in the working directory.
* [13-change_group](./13-change_group): Script that changes the group owner of the file `hello` to `holberton`.
* [14-change_owner_and_group](./14-change_owner_and_group): Script that changes the owner to `betty` and the group owner to `holberton` for all the files and directories in the current directory.
* [15-symbolic_link_permissions](./15-symbolic_link_permissions): Script that changes the owner and the group owner of the file `_hello` to `betty` and `holberton`, respectively.
* [16-if_only](./16-if_only): Script that changes the owner of the file `hello` to `betty` only if it is owned by the user `guillaume`.
* [17-Star_Wars](./17-Star_Wars): Script that plays Star Wars Episode IV in the terminal.

## Repository

* GitHub repository: [alx-system_engineering-devops](https://github.com/your_username/alx-system_engineering-devops)



# Shell Permissions

This project is part of the ALX System Engineering and DevOps curriculum. It focuses on understanding and manipulating file permissions in a Unix-based system.

## Learning Objectives

- Understand the concept of file permissions
- Change file permissions, owner, and group
- Create and manage special permissions
- Use the `chmod`, `chown`, and `chgrp` commands

## Files

- `0-iam_betty`: Script that changes the current user to `betty`.
- `1-who_am_i`: Script that prints the effective username of the current user.
- `2-groups`: Script that prints all the groups the current user is part of.
- `3-new_owner`: Script that changes the owner of the file `hello` to the user `betty`.
- `4-empty`: Script that creates an empty file called `hello`.
- `5-execute`: Script that adds execute permission to the owner of the file `hello`.
- `6-multiple_permissions`: Script that adds execute permission to the owner and the group owner, and read permission to others, to the file `hello`.
- `7-everybody`: Script that adds execution permission to the owner, the group owner, and the other users, to the file `hello`.
- `8-James_Bond`: Script that sets the permission to the file `hello` as follows: Owner - no permission, Group - no permission, Other users - all permissions.
- `9-John_Doe`: Script that sets the mode of the file `hello` to `-rwxr-x-wx`.
- `10-mirror_permissions`: Script that sets the mode of the file `hello` the same as `olleh`'s mode.
- `11-directories_permissions`: Script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.
- `12-directory_permissions`: Script that creates a directory called `my_dir` with permissions `751`.
- `13-change_group`: Script that changes the group owner to `school` for the file `hello`.

## Usage

To execute any of these scripts, use the following command:

```sh
./<script_name>
```

Make sure you have the necessary permissions to execute the script.

## Author

This project is maintained by the ALX community.

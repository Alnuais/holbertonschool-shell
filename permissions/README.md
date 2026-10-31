# Shell Permissions

0-iam_betty: Switches the current user to betty.

2-groups: Prints all groups the current user belongs to.

4-empty: Creates an empty file named hello.

5-execute: Adds execute permission to the owner of hello.

6-multiple_permissions: Adds execute permission to owner and group, and read permission to others.

7-everybody: Adds execute permission to all users for hello.

9-John_Doe: Sets the permissions of hello to 753.

10-mirror_permissions: Copies permissions from olleh to hello.

11-directories_permissions: Adds execute permission to directories recursively.

12-directory_permissions: Creates my_dir with permissions 751.

13-change_group: Changes the group ownership of hello to school.

14-change_owner_and_group: Changes owner to vincent and group to staff for all non-hidden items in the current directory.

15-symbolic_link_permissions: Changes the owner and group of the symbolic link _hello.

16-if_only: Changes the owner of hello to vincent only if currently owned by guillaume.

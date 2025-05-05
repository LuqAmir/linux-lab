# Topic: File Permissions in Linux

## Objective
Understand how Linux handles file and directory permissions, and how to modify them.

## Tasks
- [ ] Check the permissions of files using `ls -l`
- [ ] Create a file named `file1.txt` and a folder named `dir1`
- [ ] Use `chmod` to:
  - [ ] Remove all permissions from `file1.txt`
  - [ ] Give read and write permissions only to the owner
  - [ ] Give read access to group and others
- [ ] Use `chown` to:
  - [ ] Change the owner of `file1.txt` to another user (create one if needed)
  - [ ] Change the group ownership
- [ ] Use `umask` to:
  - [ ] View the default umask
  - [ ] Explain how umask affects newly created files
- [ ] Use `stat` to see detailed file metadata
- [ ] Explain `777`, `755`, and `644` in symbolic and octal format


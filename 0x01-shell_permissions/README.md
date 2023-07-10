# 0x01-shell_permissions
#### This project is about permissions in Unix-like operating system. These permissions
#### allow multiple user to operate a computer at the same time. 

## RESOURCE(s):
 - [Permissions](http://linuxcommand.org/lc3_lts0090.php)

## Usage

``` shell
### switches the current user to the user 'betty'
./0-iam_betty

### prints effective username of the current user
./1-who_am_i
```

### Tasks
0. [i am Betty](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/0-iam_betty)
 > It switches the current user to the user betty 
1. [Who am i?](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/1-who_am_i)
 > This script prints the effective username of the current user
2. [Groups](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/2-groups)
 > This script will print all the groups the current user is part of
3. [New owner](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/3-new_owner)
 > This will change the owner of the file `hello` to the user `betty`
4. [Empty](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/4-empty)
 > This script creates an empty file called `hello`
5. [Execute](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/5-execute)
 > This program adds execute permission to the owner of the file `hello`
6. [Multiple permissions](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/6-multiple_permissions)
 > This script adds execute permission to the owner and the group owner, as well as give othe users read permission to the file `hello`
7. [Everybody](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/7-everybody)
 > This will allow execution permission to the owner, group owner and other users of the file `hello`
8. [James Bond](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/8-James_Bond)
 > It sets the permission to all but the other users of the file `hello` i.e exclude owner and group
9. [John Doe](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/9-John_Doe)
 > The script sets the mode of the file `hello` to ```rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello```
10. [Look in the mirror](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/10-mirror_permissions)
 > This will allow the mode of the file `hello' to be the same as `olleh`'s
11. [Directories](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/11-directories_permissions)
 > It adds execute permission to all sub-dir of the current dir for the owner, group and other users while regular files are not changed
12. [More directories](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/12-directory_permissions)
 > Script creates a dir called `my_dier` with permissions 751 in the working dir
13. [Change group](https://github.com/Zabdulkareem/alx-system_engineering-devops/blob/master/0x01-shell_permissions/13-change_group)
 > The script changes the group owner to _school_ for the file `hello`




---
title: Zed Shell
layout: default
excerpt: The Unix environment shell `zsh` is a built-in `Zed Shell` that assists the end-user with navigating the Terminal window in MacOs ...
hint: Command Line Interface (CLI) versus Graphic User Interface (GUI) for the Root Directory/User Directory/Home Directory ...
repo: Unix-Lessons-Project 
ver_date: 03-20-21
navigation_weight: 8
categories: template
---
{% include toc.md %}

## Commands

> **Hint**. {{ page.hint }}

### Clear a Terminal page = `clear`

#### How to `clear` the screen of a Terminal page w `Zed-shell`?

a.) Clear the screen back to the current subdirectory = `clear`

### Change to a current Directory = `cd`

#### How to `change directory` to another existing directory or subdirectory w `Zed-shell`?

b.) Change Directory `cd` = cd subdirectory

c.) Change Directory `cd /` = return to the `root` directory

d.) Change Directory `cd ~` = return to the `home` directory

e.) Change Directory `cd ..` = move backwards one directory

### Print the current working directory = `pwd`

#### How to `print the working directory` or subdirectory  w `Zed-shell`?

f.) Print Working Directory `pwd` = /Users/name_that_user/subdirectory

### List the contents of the current subdirectory = `ls`

#### How to `list the items` in a working directory or subdirectory  w `Zed-shell`?

g.) List Items `ls` = the default of this command simply returns the name labels across the Terminal space horizontally

h.) Man ls = Other switches or `flags` for the `ls` command are located in the Manual = `man`

i.) Use the `-l` switch ( ... small L = l ... ) to list the items in the directory "vertically" w full "long" data = `ls -l`

### Add a file = `touch`

#### How to `add an empty file` to a subdirectory in Terminal w `Zed-shell`?

j.) From the target directory ... Touch a filename including the suffix = `touch index.htm`

### Make Directory = `mkdir`

#### How to add or `make a folder or subdirectory` within a directory in Terminal w `Zed-shell`?

k.) From the target directory ... `Make` a subdirectory or folder named "test" = `mkdir test`

#### How to add or `make a folder or subdirectory` with a `two-word` name  within a directory in Terminal w `Zed-shell` using the `backslash` or `... \ ...` key?

l.) From the target directory ... Make a subdirectory or folder named "test two" = `mkdir test\ two`

### Remove a file or folder = `rm` and `rmdir`

#### How to `remove` a file in a subdirectory in Terminal w `Zed-shell`?

m.) From the target directory ... `Remove` a filename including the suffix = `rm index.htm`

#### How to `remove` a subdirectory from a directory in Terminal w `Zed-shell`?

n.) From the target directory ... `Remove` an empty folder or subdirectory or an empty directory = `rmdir nft`

o.) From the target directory ... Use the `... -r ...` switch or `flag` to `Remove` a folder and all of its contents = `rm -r folder`

### Rename a file = `mv`

#### How to `rename` a file in a subdirectory in Terminal w `Zed-shell`?

p.) From the target directory ... `Rename` a filename including the suffix = `mv index.htm index2.htm`

### Copy a file or folder = `cp`

#### How to `copy` a file from one subdirectory to another in Terminal w `Zed-shell`?

q.) From either the source directory or the home directory ... `Copy` a file from another directory the current subdirectory = `cp nft/index.html ./` using the `dot backslash` or ` .\ ` keys

#### How to `copy` a folder and its contents from one subdirectory to another in Terminal w `Zed-shell`?

r.) From either the source directory or the home directory ... `Copy` a folder from another directory to the `home` subdirectory = `cp -r nft ~` using the single `tilde` or `... ~ ...` key

### Moving a file or folder =`mv`

#### How to `move` a file from one subdirectory to another in Terminal w `Zed-shell`?

s.)  From either the source directory or the home directory ... `Move` a file from another directory to this current subdirectory = `mv nft/index.html ./` using the `dot backslash` or ` .\ ` keys

#### How to `move` a folder and its contents from one subdirectory to another in Terminal w `Zed-shell`?

t.)  From either the source directory or the home directory ... `Move` a folder from another directory to the `home` subdirectory = `mv -r nft ~` using the single `tilde` or `... ~ ...` key

## Last Subtitle

More to come ...

### Original Video by `Academind`

**Note**. The above synopsis was derived from a You Tube video produced by Academind [[1](#ACADEMIND){:.red}].

1. {:#ACADEMIND}[Navigating the Zed Shell in the Mac Terminal by Academind, circa 2020](https://youtu.be/ogWoUU2DXBU){:target="_blank"}

***

{% include patreon-link.md %}

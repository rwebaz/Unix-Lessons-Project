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

### How to "Clear" the screen of a Terminal page w `Zed-shell`

1.) Clear the screen back to the current subdirectory = `clear`

How to "Change to" an existing directory or subdirectory w `Zed-shell`

1.) Change Directory `cd` = cd nft

2.) Change Directory `cd /` = return to the `root` directory

3.) Change Directory `cd ~` = return to the `home` directory

4.) Change Directory `cd ..` = move backwards one directory

How to "Print" a working directory or subdirectory  w `Zed-shell`

1.) Print Working Directory `pwd` = /Users/name_that_user/nft

How to "list the items" in a working directory or subdirectory  w `Zed-shell`

1.) List Items `ls` = the default of this command simply returns the name labels across the Terminal space horizontally

2.) Man ls = Other switches or `flags` for the `ls` command are located in the Manual = `man`

3.) Use the `l` switch ( ... small L = l ...) to list the items in the directory "vertically" w full "long" data = `ls -l`

### Add a file = `touch`

How to add an empty file to a subdirectory in Terminal w `Zed-shell`

1.)  From the target directory ... Touch a filename including the suffix = `touch index.htm`

### Make Directory = `mkdir`

How to add or `make` a folder or subdirectory within a directory in Terminal w `Zed-shell`

1.) From the target directory ... `Make` a subdirectory or folder named "test" = `mkdir test`

How to add or `make` a folder or subdirectory with a `two-word` name  within a directory in Terminal w `Zed-shell` using the `backslash` or " ... \ ..."key

1.) From the target directory ... Make a subdirectory or folder named "test two" = `mkdir test\ two`

### Remove a file or folder = `rm` and `rmdir`

How to `remove` a file in a subdirectory in Terminal w `Zed-shell`

1.)  From the target directory ... `Remove` a filename including the suffix = `rm index.htm`

How to `remove` a subdirectory from a directory in Terminal w `Zed-shell`

1.)  From the target directory ... `Remove` an empty folder or subdirectory or an empty directory = `rmdir nft`

2.)  From the target directory ... Use the "-r" switch or `flag` to `Remove` a folder and all of its contents = `rm -r nft`

### Rename a file = `mv`

How to `rename` a file in a subdirectory in Terminal w `Zed-shell`

1.)  From the target directory ... `Rename` a filename including the suffix = `mv index.htm index2.htm`

### Copy a file or folder = `cp`

How to `copy` a file from one subdirectory to another in Terminal w `Zed-shell`

1.)  From either the source directory or the home directory ... `Copy` a file from another directory to this current subdirectory = `cp nft/index.html ./` using the `dot backslash` or " .\" keys

How to `copy` a folder and its contents from one subdirectory to another in Terminal w `Zed-shell`

2.)  From either the source directory or the home directory ... `Copy` a folder from another directory to the `home` subdirectory = `cp -r nft ~` using the single `tilde` or " ~ " keys

### Moving a file or folder =`mv`

How to `move` a file from one subdirectory to another in Terminal w `Zed-shell`

1.)  From either the source directory or the home directory ... `Move` a file from another directory to this current subdirectory = `mv nft/index.html ./` using the `dot backslash` or ` .\ ` keys

How to `move` a folder and its contents from one subdirectory to another in Terminal w `Zed-shell`

2.)  From either the source directory or the home directory ... `Move` a folder from another directory to the `home` subdirectory = `mv -r nft ~` using the single `tilde` or " ~ " keys

## Last Subtitle

More to come ...

### Original Video by `Academind`

**Note**. The above synopsis was derived from a You Tube video produced by Academind [[1](#ACADEMIND){:.red}].

1. {:#ACADEMIND}[Navigating the Zed Shell in the Mac Terminal by Academind, circa 2020](https://youtu.be/ogWoUU2DXBU){:target="_blank"}

***

{% include patreon-link.md %}
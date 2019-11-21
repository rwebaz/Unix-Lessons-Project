---
title: Unix Env
layout: default
excerpt: The Unix environment command `env` is a built-in method that produces a list back to the Terminal window ...
hint: Place the intro paragraph ie.) the 'synopsis' here ...
repo: Unix-Lessons-Project 
ver_date: 11-19-19
navigation_weight: 8
categories: template
---
{% include toc.md %}

## Environmental Variables

> **Hint**. {{ page.hint }}

All of the **Capital Case** environmental variables that are set by the operating system ...

As well as the **lower case** underscore connected user variables that have been registered with the development machine environment over time ...

Are listed by the `env` command.

**Note**. **Environmental Variables** are defined by the operating system of your development machine and may be manipulated by the **Admin** ie.) the user with administrative permission.

### Execution-ENV

From the global Terminal prompt of your development machine ...

( after confirming which version of Ruby you are using for the current session )

Type the environment command `env`, as follows:

```liquid
{% raw %}
env
{% endraw %}
```

## Word Count

Count the number of words inside of this ( .md ) file with the **Word Count** command `wc`.

### Execution-WC

From the global Terminal prompt of your development machine ...

( after confirming which version of Ruby you are using for the current session )

Type the environment command `env`, as follows:

```liquid
{% raw %}
wc
{% endraw %}
```

**Note**. The environment command `env` is a built-in method that produces a list back to the Terminal window that shows all of the **Capital Case** environmental variables set by the operating system as well as the **Lower Case** underscore connected user variables that have been registered with the development machine environment over time.

## The Manual

Count the number of words inside of this ( .md ) file with the **Word Count** command `wc`.

### Execution-MAN

From the global Terminal prompt of your development machine ...

( after confirming which version of Ruby you are using for the current session )

Type the environment command `man`, as follows:

```liquid
{% raw %}
man man
{% endraw %}
```

**Note**. The environment command `man` is a built-in method that produces a list back to the Terminal window that shows all of the **Capital Case** environmental variables set by the operating system as well as the **Lower Case** underscore connected user variables that have been registered with the development machine environment over time.

### Search-MAN

You can search with the `-s` switch.

Simply designate the targeted **Book Number** of your search, and the section title within the book you are probing.

```liquid
{% raw %}
man -s 1 intro
{% endraw %}
```

**Note**. Here we are searching **Book One** of `man`.

Specifically, the "intro" section of book `1`.

**Tip**. When you are finished viewing the fruits of your search, hit the `Q` key to return to the Terminal prompt.

No need to capitalize with the shift key.

`q` will suffice.

## Other Disk Utilities

More to come ...

### How To Find The Amount of Available Disk Space In Mac Os

The **Disk Free** command, or `df` will return a chart of available capacity when coupled with the **Human Readable** switch `-h`.

From the global Terminal prompt ...

```liquid
{% raw %}
df -h
{% endraw %}
```

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Blank Author [[1](#BLANKAUTHOR){:.red}].

1. {:#BLANKAUTHOR}[A Narrative of Psychology by Blank Author, Jan #1999](http://cowles.yale.edu/sites/default/files/files/pub/d20/d2069.pdf){:target="_blank"}

***

{% include patreon-link.md %}

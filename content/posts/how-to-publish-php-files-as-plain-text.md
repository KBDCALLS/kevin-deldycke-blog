---
date: 2006-08-25 23:26:35
title: How to Publish .php files as Plain Text
category: English
tags: Apache, Hosting, PHP, Server, Web
---

Two months ago I was looking for a way to [let apache serve python scripts as plain text](https://kevin.deldycke.com/2006/05/how-to-localy-disable-python-cgi/). Today I had the same problem with php files. Here is my solution.

What you need is a `.htaccess` file in the same directory as the files you want to serve, with the following directive in it:

    :::apache
    AddType text/plain .php

Be carefull: within the directory, anybody will be able to look the source code of all files with .php extension.

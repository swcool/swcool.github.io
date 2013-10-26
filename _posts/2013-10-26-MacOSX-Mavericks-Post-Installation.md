---
layout: post
title: "Mac OS X Mavericks Post Installation"
category: blog
tags: [OSX Xcode]
---

## Tip 1:
In terminal, my projects with git setting didn't show up but ./git directory still exist.
I did `sudo git remote` then the system ask me for the agreement. After
answer the **AGREE**, my git version control system shows up and works
properly.

## Tip 2:
Start Xcode, select "Open Developer Tool" -> "More Developer Tool ...":
In open web page, select "Command Line Tools(OS X Mavericks) for Xcode -
Late October" "Oct 22, 2013". Install this tool, because it says:

    "This package enables UNIX-style development via Terminal by installing command line developer tools, ..."

Without this, you will have problem when you use `make` to compile
source code on command line.

## Tip 3:
`git config` settings have been changed to default, redo the setting if you need.

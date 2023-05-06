---
title: "Hugo and Github"
date: 2023-05-06T06:55:34Z
---
# these are the commands for deploy website on github
```
pkg update
pkg install hugo git openssh
clear
hugo new site blog/
sh-keygen -t ed25519 -C "Abinav-new@gmali.com
eval "$(ssh-agent -s)"
 ssh-add ~/.ssh/id_ed25519
``
`

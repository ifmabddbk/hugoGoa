---
title: Github Sammlung
author: Da Hew
date: '2019-12-27'
slug: ""
categories:
  - Github
tags: []
comments: yes
showcomments: yes
showpagemeta: yes
---

## Neues Repository Pushen

Zunächst muss ein leeres neues Repo in Github angelegt sein, bevor die Befehle ausgeführt werden können.

Ist das lokale Repo vollständig Commited und zur Übertragung bereit, können folgende Befehle verwendet werden.

```
# git remote add origin git@github.com:hewger/<reponame>.git
git remote add origin https://github.com/hewger/<reponame>.git
git push -u origin master
```

Ausführlichere Beschreibung unter [github](https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line)
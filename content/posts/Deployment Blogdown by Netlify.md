---
categories:
- hugo
- blogdown
comments: true
date: "2019-12-26"
description: Erstellung von Webseiten mit Hilfe von Blogdown, Github und Netlify
draft: false
showcomments: true
showpagemeta: true
slug: ""
tags:
- Blogdown
- Netlify
- Github 
- Hugo
title: Blogdown Deployment mit Netlify
---

## Intro

Blogdown bietet eine einfache Möglichkeit Webseiten mit Hugo zu gestalten.

## Lokale Erstellung

Ist Blogdown installiert (R-Package), so kann ein neues Blogdown-Projekt erzeugt werden. Im Erstellungs-Prozess kann ein Template (Github-Pfad) angegben werden. Per Addin "Serve Site" wird eine lokale Version der Website erstellt.

## Deployment über Guthub und Netlify

Das lokale Repository ist auf Github zu übertragen ([siehe Neues Repository Pushen](/posts/2019-12-27-github-sammlung)). Sind die Netlify und Github Konten bereits verbunden, so kann aus Netlify eine neue Seite angelegt werden. Im Prozess werden die vorhanden Github-Projekte zur Auswahl angeboten. Im Anschluss ist unter `Site-Settings`-`Build & Deploy` im Abschnitt `Environment variables` die Variabel "**HUGO_VERSION**" auf die aktuell genutzte Hugo-Version zu setzen.
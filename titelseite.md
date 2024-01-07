---
title: @(Projekt.title)
linktitle: @(Projekt.shorttitle)
chapter: true
weight: 1
---

![](/images@(Projekt.wwwCover)){width=80%}

<p style="text-align: center">
@(Autor.name)@(br)
Stand: @(Monat[heute.month].MMMM) @(heute.year)@(br)
Git: @(GetShortGITHash "")</p>

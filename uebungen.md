<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
version: @(GetShortGITHash "")
date: @(Monat[heute.month].MMMM) @(heute.year)

icon: images/favicon.png
titel: @(Projekt.title)
logo: images/ich-zeichnung.png
-->


<!-- style="color: blue; font-size: 35px; text-align: center" -->
# @titel

<!-- style="color: blue; font-size: 25px; text-align: center:" -->
@(Projekt.subtitle)

@(br)
@author@(br)
@email

@(br)
@date@(br)
Git: @version


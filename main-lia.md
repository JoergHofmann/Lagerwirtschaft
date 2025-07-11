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

# Einleitung

@include "einfuehrung.md"

# Lernfeld 1: Güter annehmen und kontrollieren


# Lernfeld 2: Güter lagern



# Lernfeld 3: Güter bearbeiten



# Lernfeld 4: Güter im Betrieb transportieren



# Lernfeld 5: Güter kommissionieren



# Lernfeld 6: Güter verpacken



# Lernfeld 7: Touren planen



# Lernfeld 8: Güter verladen



# Lernfeld 9: Güter versenden



# Lernfeld 10: Logistische Prozesse optimieren



# Lernfeld 11: Güter beschaffen


# Ceterum censeo

@include "ceterum_censeo.md" 

---
title: Anforderungen an Normdatendienste
author: Jakob Voß
date: 2016-04-04
place: DINI AG KIM, UB Mannheim
institute: Verbundzentrale des GBV (VZG)
...

## Begriffsklärung: Normdaten 

Normdaten
  : System aus Begriffen zur Wissensorganisation\
    **$\rightarrow$ Wissensorganisationssystem**

* Klassifikationen (RVK, DDC...)
* Thesauri (STW, Getty...)
* Normdateien (GND, VIAF...)
* ...

Verzeichnis unter <http://bartoc.org/>

## Begriffsklärung: Dienst

Dienst
  : Zugriff auf zusammenhängende Funktionalität über eine klar definierte Schnittstelle

#. **Interface** (HTML, GUI...) für Menschen
#. **API/Webservice** (JSON, XML, RDF...) für Programme

## Beispiel für Normdaten-Interface: RVK

![<http://rvk.uni-regensburg.de/regensburger-verbundklassifikation-online>](rvk-screenshot.png)

## Beispiel für Normdaten-Interface: Mockup

![](screenshot-normdatenservice-ddc.png)

## Beispiel für Normdaten-Interface: OCRE

![<http://numismatics.org/ocre/id/ric.1%282%29.aug.1B>](ocre-screenshot.png)

## Anforderungen an Normdaten-Interfaces

* Usability (effektive Nutzbarkeit für ein **Ziel**)\
  $\Rightarrow$ Anwendungsfall ist ein konkretes Ziel,\
   z.B. *passenden Begriff finden*

## Anwendungsfall für Normdaten-Interface

> Ein Probleme oder eine Frage, die mit Hilfe eines Normdatendienst gelöst werden kann.

Erstes Formular:

------------------------- --------
Name                      ...
Ziel                      ...
Aktionen                  ...
Mockup, API-Funktionen... ...
------------------------- --------

## Von Normdaten-Interfaces zu Normdaten-APIs

* Usability (effektive Nutzbarkeit für ein Ziel)\
  $\Rightarrow$ Anwendungsfall ist ein konkretes Ziel,\
   z.B. *passenden Begriff finden*

* Funktionalität **basiert auf Normdaten-API**\
  $\Rightarrow$ Anforderungen an Normdaten-API,\
  z.B. *nach Begriffen suchen*, *Begriff-Details abfragen*...


## Beispiele für Normdaten-APIs

* [lobid-API (hbz)](https://lobid.org/api)
* [Web Services for Economics (ZBW)](http://zbw.eu/en/project/econ-ws)
* [Entity Facts (DNB)](http://www.dnb.de/entityfacts)
* [finto: Finnish thesaurus and ontology service](https://finto.fi/en/)
* [Library of Congress Linked Data Service](http://id.loc.gov/)
* [Spatial Information Services Stack Vocabulary Service](http://www.sissvoc.info/)
* [Neuroscience Information Framework Vocabulary Server](http://www.bodc.ac.uk/products/web_services/vocab/)
* [Australian National Data Service Vocabularies API](http://ands.org.au/) 
* ...

**Anfrage** (Parameter, Optionen, Felder...)\
$\Longrightarrow$ **Antwort** (Objekte, Eigenschaften, Felder, ...)


## Anwendungsfall für Normdaten-API

> Ein Probleme oder eine Frage, die mit Hilfe eines Normdatendienst gelöst werden kann.

Zweites Formular:

---------------------------- ----------
Name                         ...
Ziel                         ...
(Bestandteile der) Anfrage   ...
(Bestandteile des) Ergebnis  ...
---------------------------- ----------


# Weiterer Verlauf der Session

## Gruppenarbeit

* Je etwa 6 Personen pro Gruppe
* Mindestens eine Person mit pedantischer Uhr

## Schritt 1: Anwendungsfälle finden

JedeR erstellt für sich Liste von Anwendungsfällen.\
Nur Namen der Anwendungsfälle, auf leerem Blatt!

* *Abfrage von synonymen Benennungen zu einem Begriff*
* *Passende Normdatei finden*
* *Neuen Begriff vorschlagen*
* ... 

**5 Minuten Zeit!**

## Gruppen von Anwendungsfällen

Allgemein

* *Zugriff auf...*
* *Suche nach...*
* *Bearbeitung von...*
* ...

Konkret

* *Abfrage von synonymen Benennungen zu einem Begriff*
* *Meistverwendete Begriffe bei der Indexierung finden*
* ...


## Schritt 2

* Vorstellung der Listen in Kleingruppen (keine Diskussion!)
* Einordnung: Interface / API / beides

**1 Minuten pro Person!**

## Schritt 3 & 4

* Bestandsaufname von unterschiedlichen Anwendungsfällen 
  in der Gruppe und Aufteilung der Anwendungsfälle (Formulare)

**5 Minuten Zeit!**

* JedeR beschreibt genauer ein oder zwei Anwendungsfälle 
  (allein oder maximal zu zweit)

**5 Minuten Zeit!**

## Schritt 5 & 6

* Kurzvorstellung der Anwendungsfälle

**1 Minuten pro Person!**

* Gemeinsame Erarbeitung von API-Anwendungsfällen
  in der Gruppe

**~10 Minuten**

## Letzter Schritt

* Vorstellung der Anwendungsfälle der einzelnen Gruppen
  (nur Typ, Name und Zweck/Ziel)

**1-2 Minuten pro Gruppe**

## Zusammenfassung

0. Gruppen bilden
1. Liste von Anwendungsfällen (nur Namen): 5 Minuten allein
2. Kurzvorstellung in der Gruppe: 1 Minute pro Person 
3. Bestandsaufnahme & Verteilung der Anwendungsfälle\
   5 Minuten
4. Genauere Beschreibung von 1-2 Anwendungsfällen pro Person: 5 Minuten allein
5. Kurzvorstellung der Anwendungsfälle: je 1 Minute
6. Gemeinsame Erarbeitung von API-Anwendungsfällen
7. Kurzvorstellung API-Anwendungsfälle

# Beispiele für Anwendungsfälle

## Beispiele für Anwendungsfälle

* Passende Normdatei finden
* Begriff anzeigen
* Metadaten über Begriff (Erstellungsdatum, Status, Autoren...) nachschlagen
* Begriff markieren oder kommentieren
* Neuen Begriff vorschlagen
* Passenden Begriff in einer Normdatei finden
* Verwandte Begriffe zu einem gegebenen Begriff finden
* Dokument mit Begriffen aus Normdatei indexieren
* Vorhandene Verwendung eines Begriffs ermitteln
* Mapping eines Begriffs auf andere Normdateien ermitteln
* ...


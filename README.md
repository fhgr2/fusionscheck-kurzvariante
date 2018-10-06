# fusionscheck-kurzvariante
Tool für das ZVM (Ursin Fetz)

# Anforderungen

## Fachlich

Grundsätzlich soll ein Tool analog zu http://www.htwchur.ch/management/institut-sife/team-themen-und-taetigkeiten/tool-exportfitness-check.html geschaffen werden. Anstatt um Export-Fitness geht es um einen Fusionscheck für Gemeinden.

Die Anforderungen sind in Form einer [Excel-Datei](docs/Fragen für Online-Tool_v2.xlsx) vorhanden. 

## Technisch

JavaScript-basiertes Tool, welches sich ins Typo3 einbinden lässt, analog zur Übersicht der Fachzeitschriften auf http://www.htwchur.ch/services/fuer-alle/bibliothek/abonnierte-fachzeitschriften.html.

# Guidelines

JavaScript
- Dokumentation gemäss http://usejsdoc.org/tags-type.html

# Administrativ

- Aufwand: 40 h
- Projekt: 11437 ZVM-12-Fusionscheck (falls die 40 h aufgebruacht sind, bei mir melden, resp. auf 11113 IKT-10-Kleinprojekte aF+E buchen).

# Installation

Die Installation erfolgt ins Typo3 mittels HTML-Elemente.

## Bibliotheken

Für jede  Bibliotheken nach der Angabe
```javascript
<!-- cut here ✂ ------------------------- -->
```
wird ein HTML-Element erzeugt und der Inhalt der JavaScript-Datei mit
```
<script>
  hier kommt der Inhalt der JavaScript-Bibliothek
</script>
```

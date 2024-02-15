# HTML und XML

[Zurück zur Übersicht](../readme.md)

## Gliderung

- [HTML](#html)
- [XML](#xml)

---
---

## HTML

### Tags

- `<!Doctype html>`  -> Damit erkennt der Browser, dass ses sich um ein HTML-Dokument handelt
- `<html> </html>` -> Beginn/Ende des HTML Dokuments
- `<head> </head>` -> Beginn/Ende des Header-Bereichs
- `<meta charset="utf-8" />` -> Mit dem Meta-Tag wird der verwendete Zeichensatz angegeben
- `<meta name="keywords" content="IT" />` -> Ebenso dient der Meta-Tag zur Beschreibung von Schlüsselwörtern für Suchmaschinen.
- `<meta name="description" content ="PV-Vorbereitung" />` -> Kurzbeschreibung der Seite für die Suchmaschine
- `<title> </title>` -> Titel der Seite
- `<body> </body>` -> Hauptteil der Seite
- `<nav> </nav>` -> Navigationsbereich
- `<section> </section>` -> Gruppieren von Elementen
- `<h1> </h1>` -> Überschrift
- `<h2> </h2>` -> Unterüberschrift (bis `<h6>`)
- `<p> </p>` -> Absatz
- `<br>` -> Erzwungener Zeilenumbruch
- `<a href=...> </a>` -> Link
- `<img src=...>` -> Bild
- `<hr>` -> Trennlinie (horizontal)

[mehr](https://www.html-seminar.de/befehlsuebersicht.htm)

### Beispiel

```html
<!Doctype html>

<html>

<head>

    <meta charset="utf-8" />

    <meta name="keywords" content="IT" />
    
    <meta name="description" content ="PV-Vorbereitung" />

    <title>
    
        Übung

    </title>

    
    </head>‚

</html>
```

[Hoch](#gliderung)

---
---

## XML

Beispiel 1:

```xml
<!ELEMENT adresse (name, strasse, wohnort, telfonnummer)>
<!ELEMENT name (#PCDATA)>
<!ELEMENT strase (#PCDATA)>
<!ELEMENT strasse (#PCDATA)>
<!ELEMENT wohnort (#PCDATA)>
<!ELEMENT telefonnummer (#PCDATA)>
```

Beispiel 2:

```xml
<?xml version ="1.0"?>
<!-- Kundendaten -->
<!DOCTYPE kundendaten SYSTEM "kunden.dtd">
<adresse>
    <name> Hans Kaiser </name>
    <strasse> Masurenalle 12 </straße>
    <wohnort> 20000 Hamburg </wohnort>
    <telfonnummer>
        <nummer> 123456 </nummer>
        <nummer> 654321 </nummer>
        <nummer> 111111 </nummer>
    </telfonnummer>
</adresse>
```

[Hoch](#gliderung)

---
---

## Quellen

### Inhalt

- Unterrichtsmaterialien des BSZ-ET Dresden
- Buch *Prüfungsvorbereitung Aktuell - Teil 1 der gestreckten Abschlussprüfung "Einrichtung eines IT-gestützten Arbeitsplatzes"* -  [Europa Lehrmittel]
- <https://www.html-seminar.de/befehlsuebersicht.h>

[Hoch](#gliderung)

---
---

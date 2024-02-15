# Softwarequalität

[Zurück zur Übersicht](../readme.md)

## Gliederung

- [Qualitätsmerkmale](#qualitätsmerkmale)
- [Tests](#tests)

---
---


## Qualitätsmerkmale

Qualitätsmerkmal | Begrifflichkeit |
-|-|
Zuverlässigkeit | Reife, Fehlertoleranz, Wiederherstellbarkeit
Funktionalität | Angemessenheit, Interoperabilität, Sicherheit
Benutzbarkeit | Verständlichkeit, Erlernbarkeit, Bedienbarkeit
Effizienz | Zeitverhalten, Verbrauchsverhalten
Wartbarkeit | Analysierbarkeit, Änderbarkeit
Portabilität | Anpassbarkeit, Austauschbarkeit, Installierbarkeit

[Hoch](#gliederung)

---
---

## Tests

```text
Modultests
----------
Modultests dienen dazu einzelne Module oder Komponenten zu testen.
Das geschieht in der Regel in Form eines White-BoxT-Testes durch den Entwickler.
Frameworks wie jUnit helfen dabei, solche Tests zu automatisieren.
```

```text
Integrationstest
----------------
Der Integrationstest prüft die einzelnen Komponenten im Zusammenspiel. 
In der Regel werden Komponenten nach dem Modultest direkt mit einem Integrationstest
auf Fehler in der Interaktion mit bestehenden Komponenten geprüft. Auch hier ist eine 
Automatisierung möglich. 
```

```text
Systemtest
----------
Der Systemtest prüft die komplette Software gegen die definierten Anforderungen.
In der Regel findet dieser Test auch in einem Testsystem statt, das die Produktivumgebung
nachbildet. 
```

```text
Abnahmetest
-----------
Der Abnahmetest wird durch den Auftragsgeber durchgeführt. Er prüft das Produkt auf die 
geforderten Funktionalitäten. Der Test findet in der Regel als Black-Box-Test statt. 
```

[Hoch](#gliederung)

---
---

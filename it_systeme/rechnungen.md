# Rechnungen zwischen HEX/BIN/DEC

[Zurück zur Übersicht](../readme.md)

## Gleiderung

- [DEC nach BIN](#dec-nach-bin)
- [BIN nach DEC](#bin-nach-dec)
- [DEC nach HEX](#dec-nach-hex)
- [HEX nach DEC]
- [Quellen](#quellen)

---
---

## DEC nach BIN

- Es gibt viele möglichkeiten eine Dezimalzahl in einer Binärzahl umzurechnen

2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0
-|-|-|-|-|-|-|-
128 | 64 | 32 | 16 | 8 | 4 | 2 | 1

- bei dieser Methode geht man die Tabelle von links nach rechts durch und prüft ob die Dezimalzahl gößergleich der Tabellenzahl ist
- 1 = Ja, 0 = Nein
- bei Ja muss die Zahl der Tabelle von der Dezimalzahl subtrahiert werden

Beispiel:

``` text
Dezimalzahl 142

- 142 >= 128 -> 1 | 142 - 128 = 14
-  14 >=  64 -> 0
-  14 >=  32 -> 0
-  14 >=  16 -> 0
-  14 >=   8 -> 1 | 14 - 8 = 6 
-   6 >=   4 -> 1 | 6 - 4 = 2
-   2 >=   2 -> 1 | 2 - 2 = 0
-   0 >=   1 -> 0

Binärzahl = 10001110
```

[Hoch](#gleiderung)

---
---

## BIN nach DEC

- Hier nimmt man Bit für Bit und schaut welcher Dezimalzahl die 1 entspricht
- dann Addiert man alle "umgerechneten" 1

2^7 | 2^6 | 2^5 | 2^4 | 2^3 | 2^2 | 2^1 | 2^0
-|-|-|-|-|-|-|-
128 | 64 | 32 | 16 | 8 | 4 | 2 | 1

Beispiel:

```text
Binärzahl = 10001110

- Stelle 1 = 1 = 128
- Stelle 2 = 0 = 0
- Stelle 3 = 0 = 0
- Stelle 4 = 0 = 0
- Stelle 5 = 1 = 8
- Stelle 6 = 1 = 4
- Stelle 7 = 1 = 2
- Stelle 8 = 0 = 0

- 128 + 8 + 4 + 2 = 142

Dezimalzahl = 142
```

[Hoch](#gleiderung)

---
---

## DEC nach HEX

Hexadezimal | Dezimal
-|-
1 | 1
2 | 2
3 | 3
4 | 4
5 | 5
6 | 6
7 | 7
8 | 8
9 | 9
A | 10
B | 11
C | 12
D | 13
E | 14
f | 15

- man nimmt die Dezimalzahl und schaut welche die größte 16er Potenz (1, 16, 256, 4096, 65536, 1048576, …) ist, die in die Dezimalzahl passt

```Text
Beispiel:
5036

größte 16er Potenz = 4096
```

- nächstes ziehen wird die gefundene Sechzehnerpotenz von der Dezimalzahl abgezogen

```text
5078 - 4096 = 982
```

- das wird jetzt folgenderweise geschrieben

```text
5078 = 4096 + 982
```

- mit dem Rest wird jetzt das gleiche gemacht
- die nächste 16er Potenz die passt ist die 256

```text
982 : 256 = 3 (Rest 214)
```

- **Sie passt aber 3 mal**
- also wird jetzt geschrieben

```text
5078 = 1·4096 + 3·256 + 214
```
- mit dem Rest wird wieder das gleiche gemacht
- die 16 ist die nächste 16er Potenz die passt

```text
214 : 16 = 13 (Rest 6)
```

- **Sie passt aber 6 mal**
- also wird jetzt geschrieben

```text
5078 = 1·4096 + 3·256 + 13·16 + 6
```

- da die nächst 16er Potenz die 1 ist kann folgendes geschrieben werden

```text
5078 = 1·4096 + 3·256 + 13·16 + 1·6
```

- jetzt kann man das Ergebnis tabellarisch darstellen (16er Potenz und Multiplikator -> wie oft hat die 16er Potenz gepasst)


16er Potenz | Multiplikator
-|-
4096 | 1
256 | 3
16 | 13
1 | 6

- jetzt müssen die Multiplikatoren noch Hexadezimal geschrieben werden (siehe Tabelle oben)

16er Potenz | Multiplikator (HEX)
-|-
4096 | 1
256 | 3
16 | D
1 | 6

- Ergebnis ist **13D6**

[Hoch](#gleiderung)

---
---

## HEX nach DEC

- man nimmt einfach die Hexadezimale Zahl und fängt von rechts an und rechnet die Ziffer mal 16^x
- dann addiert man alle Ergebnisse und erhält die Dezimalzahl

Beispiel

```text
Hexadezimal: 5A04

Aufteilung
5 10 0 4

Rechnung:

1.  4 x 16^0
2.  0 x 16^1
3. 10 x 16^2
4.  5 x 16^3

Erg = 4 x 1 + 0 x 16 + 10 x 256 + 5 x 4096 = 23044

Ergebnis:
23044


```

[Hoch](#gleiderung)

---
---

## Quellen

[Hoch](#gleiderung)

---
---

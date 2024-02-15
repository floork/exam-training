# Gefährdungen

[Zurück zur Übersicht](../readme.md)

## Gliederung

- [Gefährdungen der IT-Sicheheit](#gefährdungen-der-it-sicheheit)
- Maßnahmen gegen Gefährdungen der IT-Sicherheit

---
---

## Gefährdungen der IT-Sicheheit

- **Identitätsdiebstahl**:
    - Phishing: 
    ```text
    Mithilfe gefälschter Webseiten oder Emails sollen Vertrauliche Daten
    eines Nutzers ermittelt werden. Mit diesen Daten werden dann beispielsweise
    Online-Konten des Nutzers manipuliert und Geldbeträge überwiesen.
    ```
    - Vishing:
    ```text
    Vishing steht für "Voice phishing" und ist eine Variante des Phishings.
    Dabei werden Nutzer durch Telefonanrufe manipuliert und zur Herausgabe von 
    persönlichen Daten animiert.
    ```
    - Pharming:
    ```text
    Pharming basiert auf der Manipulation der DNS-Anfrage vom Webbrowser.
    Damit werden die Benutzer auf gefälschte Websites umgeleitet, obwohl 
    sie die korrekte Adresse eingegeben haben.
    ```
    - Spoofing:
    ```text
    Mit Spoofing wird die allgemeine Methode beschrieben, mit der ein Angreifer
    seine Identität verschleiern will. Das Phishing ist eine Variante des Spoofeings.
    ```
    - Nicknapping:
    ```text
    Der Begriff Nicknapping setzt sich aus Nickname (Spitzname) und Kidnapping (Entführung)
    zusammen. Bei dieser Methode wird versucht die Internet-Identität einer Person zu
    "stehlen", um damit in verschiedenen Bereichen illegal zu arbeiten.
    ```
- **Schadprogramme (Malware)**:
    - Spam:
    ```text
    Das unaufgeforderte Senden von Nachrichten/Informationen wird als Spam oder Junk
    bezeichnet.
    ```
    - Spyware:
    ```text
    Der Begriff Spyware setzt sich aus Spy (Spion) und Ware (Abkürzung für Software)
    zusammen. Spyware soll den Benutzer ausspähen, also Daten über den Benutzer sammeln
    und auch versenden. Diese Software wird sowohl zu Werbezwecken als auch zur Überwachung
    eingesetzt.
    ```
    - Adware:
    ```text
    Der Begriff Adware setzt sich aus Advertisement (Werbung) und Ware (Kurz für Software) 
    zusammen. Oftmals ohne Rückfrage installiert sich diese Software zusätlich auf dem PC
    des Benutzers und dient vor allem zu Werbezwecken.
    ```
    - Virus:
    ```text
    Ein Virus ist ein Programm, das sich selbst weiterverarbeitet. Dazu schleust es sich 
    in andere Cimputerprogramme oder beispielsweise den Bootsektor ein und sorgt dann für
    seine Reproduktion. Viren können großen Schaden anrichten (Datenverlust) oder auch nur 
    das System verlangsamen.
    ```
    - Trojaner:
    ```text
    Ein Trojaner ist ein Programm, welches sich in oder hinter einem anderen "nützlichen"
    Programm vertseckt und im Hintergrund schädliche Aktivitäten durchführt.
    ```
    - Wurm:
    ```text
    Ein Wurm ist ein Schadprogramm, welches sich selbst reproduziert. Die Intention ist
    wie beim Virus - Schaden anrichten.
    ```
    - Ransomware:
    ```text
    Der Begriff Ransomware setzt sich aus Ranson (Lösegeld) und Ware (kurz für Software)
    zusammen. Diese Software verschlüsselt die Daten auf fremden Systemen oder blockiert 
    den Zugang zu den Daten. Damit soll eine Lösegeldzahlung erzwungen werden.
    ```
- **DDoS**:
```text
Mithilfe einer Distributed-Denail-of-Service attack soll ein Internetdienst so ausgelastet
werden, dass er nichtmehr ansprechbar ist. Das wird mit einer hohen Anzahl von Anfragen aus
verschiedenen Quellen erreicht. Die verschiedenen Quellen sorgen dafür, dass der Dienst nicht 
durch Blockieren einer Quelle den Angriff stoppen kann. DDoS-Angriffe werden oft durch
Botnetze durchgeführt.
```

- **Botnetze**:
```text
Ein Botnetz entsteht durch die Installation eines Schadprogramms auf vielen Rechnern (ohne
Kenntnis der Inhaber) und Vernetzung dieser Rechner im Hintergrund. Dadurch kann zentral der
Befehl eines Angriffs gegeben werden und von unzähligen Rechnern parallel ausgeführt werden.
```

- **APT-Angriffe (Advanced Persistent Threats)**:
```text
Diese Art des Angriffs unterscheidet sich von den herkömmlichen Schadprogrammen, da es eine
geplante und intensiv vorbereitete Aktion mit verschiedenen Methoden ist, um die 
IT-Infrastruktur einer Firma oder Behörde zu kompromittieren. Bei dieser Aktion können alle
oben genannten Formen und Methoden eingesetzt werden, um das Ziel zu erreichen.
```

[Hoch](#gliederung)

---
---

## Maßnahmen gegen Gefährdungen der IT-Sicherheit

- **Vermeidung von Phishing**
  - Aktuelle Virenscanner mit Phishing-Warnungen installieren und Aktuell halten
  - Niemals TANs oder Kennwörter aufgrund von Aufforderungen in Mails angeben
  - Mangelnde Rechtschreibung, Grammatik und allgemeine Ansprachen können auf Phishing hindeuten
- **Verhalten bei einer Ransomware-Gefährdung**
  - sofort alle Netzwerkverbindungen lösen
  - keine Anmeldung mehr am System als Admin oder mit erhöten Rechten
  - Backups auf Infizierung (Verschlüsselung) untersuchen, wenn das Backup ok ist System neu Aufsetzten und Backup einspielen
- **Vermeidung von DDoS**
  - sichere Passörter auf allen Geräten
  - nichtgenutzte Ports schließen
  - Deaktivierung von *Universal Plug and Play* im IP-Netzwerk

[Hoch](#gliederung)

---
---

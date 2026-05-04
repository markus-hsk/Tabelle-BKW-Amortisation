# Tabelle-BKW-Amortisation
Eine LibreOffice Calc Tabelle um die Amortisation des eigenen Balkonkraftwerks zu tracken.
<img width="1359" height="994" alt="Screenshot 2026-05-01 001106" src="https://github.com/user-attachments/assets/6540133b-1d11-41cf-883d-6e0bcda3712c" />

# Kurz ein paar Infos zur Verwendung:
- Es handelt sich um eine ods-Datei die am besten mit **LibreOffice Calc** geöffnet werden kann. Ich könnte auch eine Version für Microsoft Excel exportieren, die interpretiert aber ein paar der Formeln etwas anders.
- Dia Kalkulation der Ersparnis ist darauf ausgelegt, dass die PV-Produktion 1:1 genutzt oder durch zurückdrehenden Zähler zum Arbeitspreis eingespeist werden könnte. Wenn die Anlage einen digitalen Zähler hat und man nicht den ganzen produzierten Strom abnimmt, **dann ist diese Berechnung leider falsch**.
- Die Sektion "Nachträgliche Ausgaben" ist nur ein Platzhalter. Wenn man dort etwas einträgt hat das keine Auswirkungen. Ich hatte zum Zeitpunkt dieses Posts keine und daher kein Bedarf, dass funktional einzuarbeiten.
- Da meine Anlage Mitte Juni '23 ans Netz ging, sind die Formeln in I20 und P26 speziell. Statt 30 Tage werden für den Monat nur 17 Tage gerechnet.
- Die Mittelwerte oben rechts sind Matrix-Funktionen. 
- Das + oder - in der Spalte F richtet sich nach den monatlichen Mittelwerten. Dieses lässt sich aber nicht einfach kopieren/ automatisieren und muss daher von Hand nachgebessert werden, wenn man es in eine neue Zeile übernimmt.
- Die Diagramme lassen sich leider nur mühsam kopieren und müssen beim Jahreswechsel händisch angepasst werden.

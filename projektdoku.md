# Projekt-Dokumentation




Bielski, Bashiri

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|13.9| 0.0.1   | Winforms ausprobieren und Bilder herunterladen |
|20.9| 0.0.2    | Projektdokumentation überarbeitet, Unterprogramme aufgeteilt |
|18.10| 0.0.4  |Arbeit an Teilprogrammen gestartet|
|25.10| 0.0.5  |Arbiet an Teilprogrammen beendet|
|1.11| 1.0.0  |Programm fertig, tests|
|8.11| 1.0.0   |Portfolio|

## 1 Informieren

### 1.1 Ihr Projekt

Unser Programm wird ein Geographie Quiz bei welchem man Hauptstädte, Flaggen, sowie Kontinent erraten kann.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1  |Muss|NF| Als ein Benutzer möchte ich das man die Hauptstädte der einzelnen Länder erraten kann |
| 2  |Muss|NF| Als ein Benutzer möchte ich das man die Länder an ihrem Umriss erraten kann |
| 3  |Muss|NF| Als ein Benutzer möchte ich das man die Flaggen den jeweiligen Ländern zuordnen kann |
| 4  |Muss|NF| Als ein Beuntzer möchte ich das man zwischen den einzelen Rätsel auswählen kann |
| 5  |Kann|F|Als ein benutzer möchte ich, dass man meinen Highscore von Antworten ohne Fehler sehen kann, damit ich mich mit anderen Benutzer Vergleichen kann.|
| 6  |Kann|F|Als ein Benutzer möchte ich, dass ich ein Timer sehe, damit ich weiss wieviel Zeit ich für die Fragen gebraucht habe|
| 7  |Kann|F|Als ein Benutzer möchte ich, dass ich mehrere Schwierigkeitsmodi haben, damit damit ich ein besseres Spiel-Ecperience habe|
| 8  |Kann|F| Als ein Benutzer möchte ich, dass ich eine enter Taste habe, damit ich selber auswählen kann wann ich antworte |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |Programm gestartet, man kann zwischen die Modi auswählen|  Hauptstadt Modus anklicken    |   Hauptstadt Modus gestartet                |
| 2.1  |Programm gestartet, man kann zwischen die Modi auswählen|  Umriss Modus anklicken      |Umrisss modus gestartet|
| 3.1  |Programm gestartet, man kann zwischen die Modi auswählen|Flaggen Modus anklicken |Flaggen Modus gestartet|
| 4.1  |Programm gestartet|-|Auswahl zwischen den Modi| Auswahl ist anklickbar |
| 5.1  |Modus gestartet|richtige Antwort|Highscore= +1|
| 6.1  |Ein Modus ausgewählt und gestartet|richtige antworte|Timer zählt die Zeit|   
| 7.1  | Modus auswählen | Schwierigkeitsstufe 1       |     Schwierigkeitsstufe 1              |
| 8.1  |Modus ausgewählt, Antwort eingegeben|         Button enter wird angeklickt|    nächste Frage   |

### 1.4 Diagramme


![Pap](https://i.imgur.com/Dmpsvss.png)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1 | 8.11| Alle | WinForms kennenlernen | 45min |
| 2 | 8.11 | Shahir | Flaggen raussuchen | 30min |
| 3 | 8.11 | Shahir | Länderliste erstellen | 30min |
| 4 | 8.11 | Kamil | Länderumriss raussuchen | 30min |
| 5 | 8.11 | Kamil | Flaggenquiz starten | 120min |
| 6 | 8.11 | Shahir | Hauptstädte starten | 120min |
| 7 | 8.11 | Kamil | Kontinente starten | 120min |
| 8 | 8.11 | Shahir | Quiz auswahl | 45min |
| 9 | 8.11 | Shahir | Score | 45min |
| 10 | 8.11 | Kamil | Leaderbord | 45min |
| 11 | 8.11 | Kamil | Flaggenquiz fertig | 120min |
| 12 | 8.11 | Shahir | Hauptstädte fertig | 120min |
| 13 | 8.11 | Kamil | Kontinente fertig | 120min |
| 14 |8.11 | Kamil | Vortrag | 120min |
| 15 | 8.11 | Kamil | Programm feinschliff | 45min |
| 16 | 8.11 | Shahir | Programm testen | 45min |
| 17 | 8.11 | Beide | Portfolio | 180min |


Wir haben und dazu entschieden mehere verschiedene Rätsel zu machen antstatt eins ausgibig zu Programmieren da man mehere besser in der Gruppe aufteilen kann.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |8.11|Alle|45min|120min|
| 2.A  |8.11|Shahir|30min|20min|
| 3.A  |8.11|Shahir|30min|20min|
| 4.A  |8.11|Kamil|30min|20min|
| 5.A  |8.11|Shahir|120min|180min|
| 6.A  |8.11|Shahir|120min|180min|
| 7.A  |8.11|Kamil|120min|180min|
| 8.A  |8.11|Shahir|45min|----|
| 9.A  |8.11|Shahir|45min|70min|
| 10.A  |8.11|Kamil|45min|----|
| 11.A  |8.11|Kamil|120min|----|
| 12.A  |8.11|Shahir|120min|100min|
| 13.A  |8.11|Kamil|120min|----|
| 14.A  |8.11|Kamil|120min|120min|
| 15.A  |8.11|Kamil|45min|45min|
| 16.A  |8.11|Shahir|45min|40min|
| 17.A  |8.11|Alle|180min|150min|


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |22.12| Negativ|Shahir|
| 2.1  |22.12|Negativ|Shahir|
| 3.1  |22.12|Negativ|Shahir|
| 4.1  |22.12|Negativ|Shahir|
| 5.1  |22.12|Positiv|Shahir|
| 6.1  |22.12|Negativ|Shahir|
| 7.1  |22.12|Negativ|Shahir|
| 8.1  |22.12|Positiv|Shahir|


Nach einen ein bisschen holpriger Start in das Projekt als wir uns dann noch übernommen haben was die Arbeit angeht, würde ich sagen ist es trotzdem eub gutes Endergebnis obwohl wir nicht alles geschafft haben was geplant war. Das nächste mal müssen wir definitiv schauen das wir die Komunikation besser hinbekommen damit alles strukturierter ist.


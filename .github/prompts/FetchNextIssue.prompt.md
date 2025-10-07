---
mode: agent
---

## Daten sammeln

Hole aus dem Github Repostory die offenen Issues und liste sie mir auf.
Nutze dazu das gh (GitHub CLI) im Terminal.

## Ausgabe


{
[
{
"Bedingung" : "IDE == VSCode",
"Format" : "Erzeuge eine Tabellenstruktur im Format: 
'ID' 'Name des Issues' 'Beschreibung' 'Status' 'erstellt am'"
},
{
"Bedingung" : "IDE == Visual Studio",
"Format" : "Erzeuge eine Auflistung im Format (Beispiel): 
Eine Zeile mit Bindestrichen 
ID #1 (Name des Issues)
(Beschreibung hier eintragen)

Dann eine Leerzeile
Status:
(Status hier eintragen)
Erstellt am:
(Erstellt am hier eintragen)

Dann wieder eine Leerzeile"
}
]


Sortiere ggf. mehrere Issues nach dem 'erstellt am'-Datum aufsteigend.

## Weitere Schritte

Frage mich nach einer ID.
Danach frage mich, ob Du mit der Analyse des Issues beginnen sollst.

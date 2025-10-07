---
mode: agent
tools:
  [
    "edit",
    "runNotebooks",
    "search",
    "new",
    "runCommands",
    "runTasks",
    "usages",
    "vscodeAPI",
    "problems",
    "changes",
    "testFailure",
    "openSimpleBrowser",
    "fetch",
    "githubRepo",
    "extensions",
    "runTests",
  ]
---

{
"Aufgabe": "Erstelle mögliche Lösungsstrategie für das Issue, welches Du Dir vorher mit der GitHub CLI aus dem GitHub Repository lädst. Nutze dazu die ID des Issues, die ich Dir als Eingabe mitgebe. ",
"Eingaben": [
"ID": Zahl
],
"Ausgabe": "Ich möchte von Dir eine Zusammenfassung des Issues haben, damit ich sehe, dass Du alles verstanden hast. Dann möchte ich von dir die möglichen Lösungsansätze kurz präentiert bekommen und eine Einschätzung über die Vor- und Nachteile der verschiedenen Ansätze erhalten. Lass mich dann auswählen, welchen Ansatz ich wähle. Wenn ich einen Ansatz ausgewählt habe, möchte ich von dir eine Datei in Dein Gedächtnisspeicher erstellt bekommen, die den Namen 'issue\_' gefolgt von der ID des Issues und dem Suffix ".md" hat. In dieser Datei sollen alle Schritte enthalten und für Dich verständlich sein, damit ich Dir die Aufgabe geben kann das umzusetzen. Bitte füge an das Ende der Datei als letzte Aufforderung an Dich ein, dass nach Abarbeitung der Tasks danach ein neuer Pull Request im GitHub Repo in den Hauptbranch erstellt wird.",
"Gedächtnisspeicher": "Das ist ein Ordner im Root der Solution mit den Namen '.ai/docs'"
}

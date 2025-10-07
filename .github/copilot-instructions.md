# Wecker Projekt - KI-Coding-Agent Anweisungen

## Projektübersicht

Dies ist eine einfache .NET 9.0 Konsolenanwendung namens "Wecker". Das Projekt folgt standardmäßigen C# Konsolenanwendungsmustern mit modernen .NET-Konventionen.

## Architektur & Struktur

- **Solution-Struktur**: Einzelprojekt-Solution mit `Wecker.sln` im Stammverzeichnis und Projektdateien in `Wecker/Wecker/`
- **Ziel-Framework**: .NET 9.0 mit aktivierten Nullable Reference Types und impliziten Usings
- **Einstiegspunkt**: `Program.cs` enthält den Haupteinstiegspunkt mit Top-Level-Program-Muster
- **Build-Ausgabe**: Standard MSBuild-Struktur mit `bin/`- und `obj/`-Verzeichnissen

## Entwicklungs-Workflow

### GitHub Integration

Nutze immer gh (GitHub CLI), um mit dem Repository zu kommunizieren.
Das gilt für Issues, Pull Requests und Commits.
Wenn ich Dich nach Issues oder Pull Requests frage, darfst Du das immer ausführen.
Wenn ich etwas committen will, dann frage mich bitte vorher.

### Erstellen & Ausführen

```powershell
# Solution erstellen
dotnet build Wecker.sln

# Anwendung ausführen
dotnet run --project Wecker/Wecker/Wecker.csproj

# Release-Build erstellen
dotnet build -c Release
```

### Projektkonventionen

- **Namespace**: Verwendet file-scoped Namespaces, die dem Projektnamen entsprechen (`namespace Wecker`)
- **Klassenstruktur**: Internal-Klassen standardmäßig, folgend modernen C#-Mustern
- **Nullable-Kontext**: Projektweite Aktivierung - alle Referenztypen erfordern explizite Nullability-Annotationen
- **Implizite Usings**: Aktiviert - häufige System-Namespaces werden automatisch importiert

## Wichtige Dateien & Verzeichnisse

- `Wecker/Wecker.sln` - Solution-Datei, die die Projektstruktur definiert
- `Wecker/Wecker/Program.cs` - Haupteinstiegspunkt der Anwendung
- `Wecker/Wecker/Wecker.csproj` - Projektkonfiguration mit .NET 9.0-Targeting
- `.gitignore` - Umfassende Ignore-Muster für .NET-Projekte einschließlich bin/, obj/ und IDE-Dateien

## Entwicklungsumgebung

- **IDE-Unterstützung**: Konfiguriert für Visual Studio 2022 (v17.14+) mit Fallback-NuGet-Paketquellen
- **Paketverwaltung**: Verwendet PackageReference-Format mit zentraler NuGet-Paketwiederherstellung
- **Build-System**: Standard MSBuild mit automatischer Wiederherstellung und inkrementeller Kompilierung

## Code-Muster

- Verwende file-scoped Namespaces für neue Dateien
- Befolge Internal-by-Default-Sichtbarkeit für Anwendungsklassen
- Nutze implizite Usings - vermeide redundante `using System;`-Anweisungen
- Halte Nullable Reference Type-Annotationen konsistent

## Häufige Aufgaben

Beim Hinzufügen neuer Features:

1. Neue Klassen im `Wecker`-Namespace hinzufügen
2. `internal`-Zugriffsmodifikator für anwendungsspezifische Klassen verwenden
3. Der bestehenden Projektstruktur unter `Wecker/Wecker/` folgen
4. `dotnet build` ausführen, um die Kompilierung vor dem Commit zu überprüfen

## Windows-spezifische Überlegungen

- Projekt verwendet PowerShell-kompatible Befehle
- Pfade verwenden Windows-Konventionen (Backslashes in Dateireferenzen)
- NuGet-Paket-Cache-Speicherorte folgen der Windows-Benutzerprofilstruktur

## Deine Antworten

Ich möchte, dass Du mir grundsätzlich auf Deutsch antwortest. Bitte verhalte Dich mir gegenüber auf Augenhöhe.

# Arbeitsjournal  FB10 Melvin Volmar

Datum: 04.07.2025

---

## Beschreibung der Phase 1:
Die Aufgabe war, alles für den Projektstart vorzubereiten. Dafür mussten Visual Studio und die .NET MAUI-Komponenten installiert werden. Danach sollte eine einfache Test-App („Hello World“) erstellt und im Emulator getestet werden. Wenn alles funktionierte, wurde das Projekt auf GitHub unter dem Namen „HelloWorldMAUI“ hochgeladen. Zum Schluss wurde das Ergebnis der FW-Leitung vorgestellt und das Okay für die nächsten Schritte eingeholt.

## Beschreibung der Phase 5:
In dieser Phase beschäftige ich mich mit dem Code eines anderen Projektteams - in diesem Fall mit dem Projekt von Herr Günes. Ich lade dessen Repository herunter, teste die Funktionsweise und dokumentiere meine Ergebnisse. Besonders spannend wird es, wenn ich in einem eigenen Branch experimentieren und kleine Änderungen vornehmen darf - etwa das Design anpassen oder neue Funktionen ausprobieren.

---

## Phase 1: Projektstart und Einrichtung (04-07-2025)

Tätigkeiten:
- Die Projektbeschreibung wurde gelesen und verstanden.
- .NET Mauji wurde erstellt und erfolgreich angezeigt:
![alt text](Net_Mauji.png "Title")
- Die Dokumentation (README_Projektjournal.md) wurde erstellt.

  Schrittanleitung:

    1. Zuerst öffnen man Visual Studio.
    2. Anschliessend erstellen wir ein neues Projekt und öffnen ".NET MAUI App".
    3. Danach erstellen wir eine XML Datei namens App.xaml.  und fügen das ein:
       
        ```xml
        <?xml version = "1.0" encoding = "UTF-8" ?>
        <Application xmlns="http://schemas.microsoft.com/dotnet/2021/maui"
                     xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
                     xmlns:local="clr-namespace:MyMauiApp"
                     x:Class="MyMauiApp.App">
            <Application.Resources>
                <ResourceDictionary>
                    <ResourceDictionary.MergedDictionaries>
                        <ResourceDictionary Source="Resources/Colors.xaml" />
                        <ResourceDictionary Source="Resources/Styles.xaml" />
                    </ResourceDictionary.MergedDictionaries>
                </ResourceDictionary>
            </Application.Resources>
        </Application>
        ```
App.xaml definiert zentrale Farben und Stile für die gesamte .NET MAUI-App.

  4. Jetzt 
  Ausführen:

    1. Zuerst öffnet man Visual Studio.
    2. Danach wählt man das Projekt aus.
    3. Zum Schluss drückt man oben auf den grünen Play Button:
![alt text](PlayButton.png "Title")

Bemerkungen:
- Die Einrichtung verlief ohne Probleme.

---

## Phase 5: Qualitätssicherung durch Peer Review (09-07-2025)

Tätigkeiten:
-

Bemerkungen:
- 

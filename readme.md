`8. September 2023` `neueFische - Java Development Bootcamp`
# Git/ Github

## Theoretische Aufgaben
1. Für eine Supermarktkette programmiert Ihr gerade an einer Gemüse-API. Der Inhalt des 'main'-branches ist derzeit auf den Servern installiert. Ihr habt einen branch 'addKcalInformation' ausgecheckt und bereits einige Commits erstellt (alles eingecheckt, keine uncommitteten Änderungen im working directory). Plötzlich kommt Euer Projektleiter mit der dringenden Bitte den Bug zu beheben, der dazu führt, dass aktuell für die Produkte ein viel zu günstiger Preis angezeigt wird. Beschreibt, wie Ihr mit Git/GitHub diese Situation lösen könnt. (bitte grob skizzieren, nicht zu detailliert)
```
Aktuelle main-Version pullen-->Neuen Branch der main erstellen. Bug in dem Branch beheben. Regelmäßig committen. Pushen und Pull-Request erstellen. Von anderen Entwicklern prüfen lassen und mit dem Main mergen, wenn okay. Danach wieder zu dem Kalorien-Branch auschecken. Ende.
```
2. Warum ist es sinnvoll, Feature-Branches zu verwenden? Gebt Beispiele für Situationen, in denen sie nützlich sind.
```
Stabile main, mit der Möglichkeit an verschiedenen Features gleichzeitig zu arbeiten. System, welches bereits live ist, soll nicht abstürzen.
```
3. Sucht auf GitHub ein öffentliches Repository eines nahmhaften open-source-Projekts und gebt hier den Link dazu an und gib an, wie viele branches derzeit im Repo existieren.
```
https://github.com/torvalds/linux
```

## Aufgaben
#### Erstellt ein neues Git-Repository in eurem bevorzugten Tool (z.B. IntelliJ).
1. _Schritt 1_: Erstellt ein neues Projekt.
2. _Schritt 2_: Veröffentlicht dieses Projekt auf Github.
3. _Schritt 3_: Erstellt einen neuen Feature-Branch mit einem aussagekräftigen Namen.
4. _Schritt 4_: Führt Änderungen in eurem Feature-Branch durch, commitet und pusht diese.
5. _Schritt 5_: Wechselt zurück zum Haupt-Branch (z.B. 'main' oder 'master') und führt neue Änderungen durch, committed und pusht diese.
6. _Schritt 6_: Merged lokal die Änderungen aus dem Haupt-Branch in euren Feature-Branch.
7. _Schritt 7_: Löst eventuelle Konflikte während des Merges.
8. _Schritt 8_: Pusht euren Feature-Branch auf GitHub.
9. _Schritt 9_: Erstellt einen Pull Request für euren Feature-Branch und lasst eure Kollegen eine Überprüfung durchführen.
10. _Schritt 10_: Führt nach Genehmigung den Merge durch und löscht den Feature-Branch.

## Bonus Aufgabe
11. Forked dieses Github Repository link über den fork-button oben rechts.
###### Achtet da drauf das ihr beim forken den Haken "Copy the main branch only" rausnehmt!
###### Achtet beim Pull-Request auf das ihr eures eigene Repository auswählt
###### Arbeitet zu zwei die Aufgaben in der README ab.


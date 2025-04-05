# DevOps 01 Version Control

## Zusammenarbeit

### Person und Repository

| | Bitte ausfüllen |
| -------- | ------- |
| Zusammenarbeit mit | Magjuni, Altin |
| Repo URL ÜbungspartnerIn | https://github.com/AltinMagjuni/DevOps-01-Version-Control |

### Beschreibung der Zusammenarbeit
Hallo Magjuni, wie geht es Dir?

Hallo mir geht es super, wie geht es dir?
Test 123

In unserer Zusammenarbeit im Rahmen des Moduls haben wir direkt im README-File gearbeitet. Was oberhalb ersichtlich ist. Im Rahmen der Zusammenarbeit im Modul DevOps haben wir einen Pull Request erstellt, um Änderungen aus einem separaten Branch in den Hauptbranch (main) zu integrieren. Im Commit-Verlauf auf GitHub ist ersichtlich, dass mehrere Beiträge zum Projekt erfolgten: Zunächst wurde durch mich (hitzad) das Projekt gestartet und ein neues File erstellt ("File eröffnung"). Anschliessend hat mein Teamkollege (AltinMagjuni) eine Änderung vorgenommen und diese mit dem Commit "neues file bestätigt" dokumentiert. Durch diese parallele Bearbeitung am selben File kam es zu einem Merge-Konflikt, der im weiteren Verlauf manuell gelöst wurde. Der Pull Request mit dem abschliessenden Commit "Pull Request" (ebenfalls durch mich) zeigt, dass die Änderungen erfolgreich zusammengeführt wurden. Der gesamte Prozess – von der Erstellung des Branches über die Durchführung von Änderungen bis hin zum Merge über den Pull Request – ist im Commit-Verlauf auf GitHub transparent nachvollziehbar und demonstriert die praktische Anwendung zentraler Git-Funktionalitäten im Teamkontext.


## Eigenes Lernjournal

Git ist ein verteiltes Versionskontrollsystem, das es ermöglicht, Änderungen an Dateien nachzuvollziehen und effizient im Team an einer gemeinsamen Codebasis zu arbeiten. Es bildet die Grundlage für eine strukturierte, nachvollziehbare und kollaborative Softwareentwicklung.

Pull & Push
Mit dem Befehl git pull werden die neuesten Änderungen aus dem Remote-Repository abgerufen und das lokale Repository damit synchronisiert. Umgekehrt werden mit git push die lokal vorgenommenen Änderungen ins Remote-Repository hochgeladen, sodass sie für alle Teammitglieder sichtbar und verfügbar sind.

Branch
Ein Branch stellt eine unabhängige Entwicklungslinie dar, mit der neue Funktionen oder Anpassungen isoliert vom Hauptbranch (meist main oder master) entwickelt werden können. Dies ermöglicht paralleles Arbeiten im Team, ohne dass man sich gegenseitig in die Quere kommt. Nach Abschluss der Arbeiten wird der Branch wieder mit dem Hauptbranch zusammengeführt – dieser Vorgang wird als Merge bezeichnet.

Pull Request
Ein Pull Request (PR) dient dazu, Änderungen aus einem Feature-Branch in den Hauptbranch zu integrieren. Dabei bietet sich die Möglichkeit, den Code durch andere Teammitglieder überprüfen zu lassen, bevor er endgültig übernommen wird. Das fördert die Qualitätssicherung und vermeidet Fehler. Im Rahmen des Moduls habe ich einen Pull Request erstellt und erfolgreich zwei Branches miteinander zusammengeführt.

Merge-Konflikte
Beim Mergen kann es vorkommen, dass zwei Branches dieselbe Datei an denselben Stellen verändert haben – in solchen Fällen spricht man von Merge-Konflikten. Git kann dann die Änderungen nicht automatisch zusammenführen und fordert dazu auf, die Konflikte manuell zu lösen. In meinem Fall trat ein solcher Konflikt auf, den ich durch gezielte manuelle Bearbeitung der betroffenen Datei bereinigt habe. Danach konnte der Merge erfolgreich abgeschlossen und der Pull Request abgeschlossen werden.


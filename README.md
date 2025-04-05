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


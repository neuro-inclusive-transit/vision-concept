# Conceptual Design

## Prozess

Grundlage für das Conceptual Design sind die erarbeiteten Erfordernisse und Anforderungen. Die zentralen Anforderungen wurden zusätzlich in Form von [Use Cases](./use-cases.md) abgebildet. Zu Beginn des Conceptual Design wurden Task Objects, Actions und Attributes gesammelt. Daraus konnte darafhin ein Content Model erstellt werden. Der letzte und wichtigste Schritt des Conceptual Designs ist die Erstellung eines Navigation Models.

## Content-Model

Grundlage für das Content-Model sind die gesammelten Task Objects, Actions und Attributes. Diese wurden object based in Clustern zusammengefasst.

Das Content Model besteht aus den Clustern **Einstellungen**, **Navigationsplanung**, **Navigationsbegleitung** und **Externe Unterstützung**.

- **Einstellungen:** Die Einstellungen umfassen die Individualisierungsmöglichkeiten des Systems. Diese können spezifiziert und gewechselt werden. Zusätzlich müssen Einwilligungen zur Nutzung bestimmter Handysensoren erteilt werden.
- **Navigationsplanung:** Die Navigationsplanung enthält die Objekte *Route*, *Routenübersicht*, *Verkehrsmittel*, *Haltestelle*, *Erinnerung*, *Wetter*, *Herausforderung* und *Veranstaltung*. Die Routenübersicht enthält beispielsweise die Attribute *(Verkehrs-)Linie*, *Dauer* und *Beschreibung*. Die Routenübersicht muss ständig aktuelisiert werden.
- **Navigationsbegleitung:** Die Navigationsbegleitung ist der zentrale Teil des Systems. Hierzu gehören die Objekte *Navigation*, *Navigationsanweisung*, *Hinweise*, *Warnmeldung*, *Standort*, *Pause*, *Orientierungspunkt*, *(physiche) Anzeige*, *Türe* und *Externe Musik*.
- **Externe Unterstützung:** Das Cluster "Externe Unterstützung" enthält *Bezugsperson* und *Nachricht*. 

![navigationmodel](https://user-images.githubusercontent.com/41923897/225706288-8c904d94-2020-4303-95a8-8d1369730766.jpg)

## Navigation Model
Das Navigation Model ist das Resultat des Conceptual Designs und bildet die Navigationsbeziehung zwischen den Clustern und den Elementen innerhalb der Cluster ab, die in den vorigen Schritten des Conceptual Designs spezifiziert wurden.
Das Navigation Model umfasst die Bereiche **Onboarding**, **Profil & Einstellungen**, **Route anlegen** und die **Navigationsbegleitung**.
- **Onboarding:** Das Onboarding dient dazu, die wichtigsten Funktionen des Systems den Nutzer:innen näher zu bringen, um diese auf die Nutzung des Systems vorzubereiten. Zudem sollen hier erste Individualisierungsmöglichkeiten getroffen werden können. Nach dem Onboarding befindet man sich auf Main, auf der alle weitere Cluster bidirektional erreicht werden können.
- **Profil & Einstellungen:** Das Profil umfasst wesentliche Verwaltungsmöglichkeiten von Kontaktpersonen und Systemeinstellungen.
- **Route anlegen:** Das Anlegen einer Route erfolgt wie bei vielen anderen Navigationssystemen mit zusätzlichen Spezifikationsmöglichkeiten.
- **Navigationsbegleitung:** Die Navigationsbegleitung stellt den zentralen Use-Case des Systems dar. Die Navigationsbegleitung besteht aus folgenden Funktionalitäten:
  - **Routennavigation:** Die Nutzer:innen werden Schritt für Schritt durch die Route geführt. Hierbei wird eine sehr reduzierte Darstellung der kommenden Navigationsschritte gezeigt. Es sollen so wenig Informationen wie möglich, aber so viele Infos wie nötig gezeigt werden.
  - **Herausforderungen:** Herausforderungen sind Schwierigkeiten, die während der Navigation auftreten können. Das System soll Herausforderungen ankündigen und Hilfestellungen geben. Zusätzlich können Nutzer:innen weitere Herausforderungen melden.
  - **Pause:** Die Nutzer:innen können die Routennavigation pausieren. So können sie sich bspw. nach Stressituationen erholen.
  - **Kontaktpersonen:** Benötigen die Nutzer:innen zusätzliche Unterstützung, können diese voreingestellte Kontaktpersonen kontaktieren.
<img width="4384" alt="navigationsmodell" src="https://user-images.githubusercontent.com/56262612/225102183-d9d7c09a-e281-4238-81a9-b1379c712ab0.png">

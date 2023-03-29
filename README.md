# ÖPNV-Navigation für nicht-neurotypische Personen

> **Kurzvorstellung:** \
> Für nicht-neurotypische Personen stellt die Reise mit dem ÖPNV eine besondere Herausforderung dar. Reizüberflutung durch große Menschenansammlungen und kurzfristige Veränderungen am Fahrplan belasten diese Personengruppe im hohen Maße und grenzen diese von einer bezahlbaren und klimafreundlichen Mobilität aus. Unser konzeptionell entwickeltes System ist ein Begleiter in solchen überfordernden Situationen, in dem es indiviuell- und situativ-abhängige Unterstützung und Alternativen bietet. Im Gestaltungsprozess waren Werte wie Autonomie und Stärkung des Selbstbewusstsein besonders wichtig, mit dem Ziel Nutzende nicht vom System abhängig zu machen.

Dokumentation für \
Projekt 1 "Vision und Konzept" \
im Medieninformatik Master (Schwerpunkt "Human-Computer Interaction") \
an der Technischen Hochschule Köln \
Campus Gummersbach \
im Wintersemester 2022/23

**Gruppenmitglieder:**
- [Lining Bao](mailto:lining.bao@smail.th-koeln.de)
- [Finn Gedrath](mailto:finn_nils.gedrath@smail.th-koeln.de)
- [Katrin Hartz](mailto:katrin.hartz@smail.th-koeln.de)
- [Ali Obaidi](mailto:ali.obaidi@smail.th-koeln.de)
- [Leonard Pelzer](mailto:leonard.pelzer@smail.th-koeln.de)

**Project-Owner:**
- Prof. Dr. Gerhard Hartmann


## Projektplan/Übersicht

> Der [Projektplan inklusive Timings ist als Excel-Datei](https://thkoelnde-my.sharepoint.com/:x:/g/personal/leonard_pelzer_smail_th-koeln_de/ERltJXIJREVNia7OtltWWRQBdul6jd5QmLcxvDIn1JqNww?e=W6DrhD) verfügbar.

Das Projekt begann mit einem Brainstroming und der Formulierung eines [Exposés](#exposé).

- [Design Sprint](./designsprint/index.md)
- [UML-Domaenenmodell](./artefakte/uml-domaenenmodell.md)
- [Interviews mit Stakeholder:innen](./stakeholderinterviews/index.md)

**MEILENSTEIN 1 (21.12.2022)**

- [Flussdiagramm](./artefakte/flussdiagramm.md)
- [Zielhierarchie/Vision mit einer SWOT-Analyse](./artefakte/zielhierarchie.md)

**MEILENSTEIN 2 (18.01.2022)**

- [Value Sensitive Design](./artefakte/value-sensitive-design.md)
- [Erfordernisse und Anforderungen](artefakte/anforderungen+erfordernisse.md)

**MEILENSTEIN 3 (01.02.2023)**

- [Use Cases](./artefakte/use-cases.md)
- [Conceptual Design](./artefakte/conceptual-design.md)

**MEILENSTEIN 4 (15.02.2023)**

- [NUI/GUI-Konzept](./artefakte/nui-gui-konzept.md)
- [Technische System-Architektur](./artefakte/systemarchitecture.md)
- [Prototype](https://www.figma.com/proto/mJOAhkmtCtxVFNQRpSg7NC/P1-Prototype?node-id=19-381&viewport=-1730%2C-188%2C0.23&scaling=scale-down&starting-point-node-id=573%3A10754&show-proto-sidebar=1)
- [Backlog/Projekt-Board für P2](https://github.com/orgs/neuro-inclusive-transit/projects/1)


**[Foliensatz der Abschlusspräsentation](https://github.com/neuro-inclusive-transit/vision-concept/blob/main/artefakte/abschlusspraesentation.pdf)**

---

## Exposé


### Problem und Relevanz


Deutschlandweit gibt es 10,4 Millionen Menschen mit einer amtlich anerkannten Beeinträchtigung[^1]. Nach einer Studie der *Aktion Mensch* geben 65% der Befragten (N=5426, ab 16 J.) an, Barrieren im alltäglichen Leben zu erfahren. Menschen mit Behinderungen nannten hierbei räumliche und kommunikative Barrieren[^2].

Die Ursachen für die Barrieren werden in verschiedenen Modellen diskutiert. Nach der *International Classification of Functioning, Disability and Health* (ICF) wird die Behinderung nur als Wechselwirkung von Gesundheitsproblemen und Körperfunktionen über die jeweilige Aktivität und Partizipation mit Kontextfaktoren verstanden. Demnach wird die Behinderung als Barriere gegen eine Partizipation an einem sozio-technischen System verstanden.

Für das Angehen von physischen Barrieren muss auch jenes physische Umfeld verändert werden. In solchen Fällen besteht bei digitalen Systemen nur ein begrenzter Handlungsspielraum. Aus diesem Grund fokussieren wir uns innerhalb dieses Projektes auf Barrieren, die durch kognitive Beeinträchtigungen begründet sind.

In einem Interview mit einer Person mit Lese-Rechtschreib-Schwäche, das im Zuge der Bachelorarbeit “Barrierefreiheit im Design eines digitalen Services” von Finn Gedrath geführt wurde, konnte folgendes herausgestellt werden:

> »B04 fährt selten alleine unbekannte Strecken ab. Er fühlt sich sicherer, wenn er mit seiner Frau Strecken testet, die er aus beruflichen Gründen alleine fahren müsste. Die Nutzung von assistiven Technologien wie Navigationssystemen erhöhen eher seine Nervosität. Strecken mit dem Zug fährt er sehr ungern alleine, da er Angst hat, Umsteigepunkte zu verpassen oder nicht im richtigen Moment auszusteigen.« [^3]

### Zielvorstellung

Ziel dieses Projekts ist die Konzeption einer digitalen Anwendung, die Personen mit kognitiven Beeinträchtigungen im alltäglichen Leben unterstützt. Dabei soll zugleich das Selbstbewusstsein dieser Menschen gestärkt werden.

### Vorgehen

In einem Design-Sprint konnte ein erster User-Flow konzipiert werden. Hierbei wurde als alltägliche Situation die Mobilität im ÖPNV ausgewählt. Daraus folgend konnte ein möglicher Gestaltungsvorschlag in Form eines Prototyps für das Projekt erarbeitet werden.

Für ein umfangreicheres Verständnis des Problemraums, muss nun eine ausführliche Domänenrecherche durchgeführt werden. Als Teil dieser Recherche planen wir Nutzerinterviews durchzuführen. Zusätzlich zu den Nutzerinterviews kann daraufhin der Prototyp aus dem Design-Sprint getestet werden.

Die Festlegung eines Vorgehensmodells für dieses Projekt steht noch aus. Für die Anpassung des technischen Systems an die Fähigkeiten des/der spezifischen Nutzer:in bietet sich das Ability-based design an. Bei diesem Vorgehensmodell werden die Fähigkeiten der Nutzer:innen in den Vordergrund gestellt, um das gesamte Spektrum des menschlichen Potenzials auszuschöpfen.


[^1]: Statistisches Bundesamt (Apr. 2021). Lebenslagen der behinderten Menschen. Ergebnis des Mikro-Zensus 2019. Statistik. Letzter Zugriff: 22. März 2023. Wiesbaden, Deutschland. URL: <https://www.destatis.de/DE/Themen/Gesellschaft-Umwelt/Gesundheit/BehinderteMenschen/Publikationen/Downloads-Behinderte-Menschen/lebenslagen-behinderter-menschen5122123199004.pdf>.

[^2]: Aktion Mensch e. V. (2021). Barrieren im Alltag — wer sie wahrnimmt und wen sie behindern. Ergebnisse einer bundesweiten Umfrage. Studie. Letzter Zugriff: 22. März 2023. Berlin, Deutschland: Ipsos Public Affairs. URL: <https://delivery-aktion-mensch.stylelabs.cloud/api/public/content/AktionMensch_Studie-DigitaleTeilhabe.pdf?v=6336f50a>.

[^3]: Gedrath, Finn Nils (2022) „Barrierefreiheit im Design eines digitalen Services: Analyse und Gestaltung eines digitalen Services mit dem Ziel der barrierefreien Nutzung am Beispiel eines Ticketverkaufsystems“ Bachelor Thesis. Technische Hochschule Köln. <https://doi.org/10.57683/EPUB-1962>

# Value Sensitive Design
> **Value Sensitive Design** = "Value sensitive design is a theoretically grounded approach to the de-
sign of technology that accounts for human values in a principled and
systematic manner throughout the design process" [^vsd] \
> **Ability Based Design** = Das Ability Based Design fokussiert sich nicht auf die Beeinträchtigung eines:r jeweiligen
Benutzers:in, sondern seine:ihre immer noch zur Verfügung stehenden perzeptorischen,
kognitiven und motorischen Fähigkeiten.  [^abd]

Das Value Sensitive Design und das Ability Based Design sind Design-Ansätze, die wir kombiniert haben um einen besonderen Fokus auf die menschlichen Werte und Fähigkeiten unserer Nutzer:innen zu legen. In der folgendenden Tabelle wurden demnach alle Abilities des Ability Based Designs (Value 1-7) und einige weitere Punkte als Werte für unser Projekt bzw. System festgelegt. Anschließend wurde jedem Wert eine Priorität in Hinblick auf unsere Vision und Zielvorstellungen zugeordnet. Dabei bedeutet 1 = Urgent, 2 = High, 3 = Medium, 4 = Low. 
### Values:

| Value                               | Beschreibung                                                                                                                                                                                                                      | Prio |
| ----------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---- |
| Ability (Fähigkeiten)               | Designer werden sich auf Fähigkeiten und nicht auf Behinderungen konzentrieren und danach streben, die User zu befähigen.                                                                                                         | 1    |
| Context (Kontext)                   | Systeme können proaktiv den Kontext und dessen Auswirkungen auf die Fähigkeiten der Benutzer erkennen.                                                                                                                            | 1    |
| Accountability (Verantwortlichkeit) | Designer reagieren auf schlechte Leistung, indem sie die Systeme und nicht die User anpassen. Sie lassen die User so, wie sie sind.                                                                                               | 2    |
| Adaption (Anpassbarkeit)            | Interfaces können selbstanpassend oder vom User anpassbar sein, um die bestmögliche Anpassung an die Fähigkeiten der Benutzer zu gewährleisten.                                                                                   | 2    |
| Independence (Unabhängigkeit)       | Designer betrachten die User als eine autonome Person und entwickeln ein System welches nicht paternalistisch sondern unterstützend ist.                                                                                          | 2    |
| Trust (Vertrauen)                   | Die Systeme können ein vertrauensvolles Umfeld für den User schaffen.                                                                                                                                                             | 2    |
| Privacy (Privatsphäre)              | Antwort wäre Privacy-by-design: Ein starker Fokus würde den Projekterfolg in Hinsicht auf die anderen Ziele einschränken.                                                                                                         | 2    |
| Transparency (Transparenz)          | Interfaces geben dem User das Bewusstsein für Anpassungen und die Möglichkeit, diese Anpassungen zu prüfen, außer Kraft zu setzen, zu verwerfen, zurückzunehmen, zu speichern, abzurufen, eine Vorschau anzuzeigen und zu testen. | 3    |
| Performance (Leistung)              | Die Systeme können die Leistung der Nutzer berücksichtigen und diese Leistung überwachen, messen, modellieren oder vorhersagen.                                                                                                   | 3    |
| Safety (Sicherheit)                 | Die Systeme können die aktuelle Sicherheit des Users berücksichtigen und dementsprechend eine Rückmeldung geben.                                                                                                                  | 3    |
| Commodity (Rohstoff)                | Die Systeme können aus kostengünstigen, preiswerten, leicht verfügbaren Standard-Hardware und -Software bestehen.                                                                                                                 | 4    |



## Value Delivery Scenarios:

> **Value Delivery Scenarios** = "Value delivery scenarios focus on the delivery of value in the world, rather than on quality in use and/or fit to context. Good scenarios tell plausible stories of how value results from envisaged designs."[^vsd-scenario]

Auf Basis der definierten Values wurden mehrere Value Delivery Szenarios für die jeweiligen Werte geschrieben, welche auf unserem (zu dem Zeitpunkt) aktuellem System basierten. Wichtig war hierbei, dass mindestens zwei Personen unbeeinflusst voneinander an einem Wert gearbeitet haben, um ein Value aus verschiedenen Perspektiven betrachten zu können. Für höher priorisierte Werte wurden mehr Szenarios geschrieben, um eine höhere Vielfalt an Nuzungskontexten abzudecken. 

### Ability
* Tom nutzt seit kurzem das System zur Planung und Durchführung verschiedenster ÖPNV-Reisen. Er hat in ruhigen Situationen, in denen er nicht gestresst ist, eine sehr schnelle Auffassungsgabe und kann sich viele Informationen merken. Das System bereitet Tom bestmöglich auf ÖPNV-Reisen vor, indem es ihm alle möglichen Reise-Informationen am Abend vor der Reise mitteilt. Dazu gehören auch mögliche Problemsituationen. So weiß Tom beispielsweise, dass Gleis 4 am Musterbahnhof sehr versteckt ist. Durch die Vorbereitung mit solchen Informationen kann Tom seine Reise entspannt durchführen. Er ist auf mögliche planbare Problemsituationen vorbereitet und ist bei Eintreten dieser Situationen nicht überfordert.
* Oliver fühlt sich in Situationen mit vielen Menschen stark gestresst. Verstärkt ist dies in engen Räumen aus die er nicht sofort verschwinden kann. Oliver würde am liebsten nur mit dem Bus oder der Bahn fahren, wenn diese so leer wie möglich sind. Dazu muss das System ihm die Route vorschlagen, die so leer wie möglich ist. Gegebenenfalls kann das System Oliver vorschlagen zu einer anderen Tageszeit zu fahren. Er hat schon häufiger gemerkt, dass die Vorhersage-Daten nicht immer korrekt sind. Er wünscht sich, dass das System Veranstaltungen und Wetterbedingungen in die Berechnung mit inkludiert, um so akkurat die Auslastung messen zu können.
* Erna kann bei einer Reise mit öffentlichen Verkehrsmitteln nicht auf Bildschirme schauen, da ihr sonst schlecht wird. Es ist essentiell, dass sie mit dem System nicht ausschließlich über den visuellen Kanal kommunizieren kann sondern auch über auditive und haptische Signale kommunizieren und interagieren kann. Wenn Erna vergisst, das System vor Beginn der Reise anzuschalten, muss es für sie immer noch möglich sein, ausschließlich über diese Modalität zu interagieren, um Hinweise und Unterstützung zu erhalten.
* Levi hat eine Lernstörung und benötigt für das Lesen von Texten und langen Wörtern mehr Zeit und Anstrengung. Straßennamen können sehr lang sein, Informationen auf digitalen Anzeigen an Bus- und Bahnhaltestellen laufen häufig schnell durch oder werden nur kurz angezeigt. Daher hat Levi große Schwierigkeiten sich an neuen Orten zurecht zu finden. Levi wünscht sich eine klare Navigation, die möglichst ohne komplizierte Wegbeschreibungen auskommt und nicht nur mit Richtungen und Ortsnamen, sondern auch durch Grafiken, Bilder oder AR visualisiert und mit haptischen/audiosignalen unterstützt. Digitale Anzeigen sollen ebenfalls im System angezeigt und zusätzlich als Audio abspielbar sein.

### Accountability
* Andrea nutzt das System zur Navigation und Begleitung im ÖPNV. Während einer Fahrt mit der Bahn verpasst sie die Haltestelle. Das System reagiert und berechnet eine neue Route für sie. Andrea kommt mit ein bisschen Verspätung am Ziel an. Nachdem Andrea an ihrem Zielort angekommen und ein bisschen Zeit vergangen ist, fragt das System nach, warum Andrea die Haltestelle verpasst hat. Andrea gibt an, dass sie unkonzentriert war und dadurch die Haltestelle verpasst hat. Das System bietet ihr daraufhin an, sie unmittelbar vor relevanten Haltestellen mit auditiven und haptischen Signalen  auf die Haltestelle aufmerksam zu machen.
* Lars hat Schwierigkeiten damit lange und komplizierte Sätze zu verarbeiten. Vor kurzem hat er sich für die Nutzung des ÖPNVs eine App heruntergeladen, in der er Schwierigkeiten damit hat, den Text zu verstehen, da die Texte zu kompliziert formuliert sind. Nach einiger Zeit wurde die Texte des Systems durch ein neues Update gekürzt und vereinfacht und erleichterte so Lars die Nutzung.
* Maxi hat Schwierigkeiten eine Reise komplett zu planen. Sie hat zwar eien App, die dabei Unterstützt und die beste Route raussucht undwährend der Fahrt darauf achtet, dass die richtige Haltestelle nicht verpasst wird. Leider kann Maxi sich nicht merken, wann es Zeit ist an den Bahnhof zu gehn und ist entweder viel zu früh oder zu spät dort und hat schon einige Züge verpasst... 
Das System soll Maxi für künftige Reisen die Option bieten durch Erinnerungen und Benachrictigungen pünktlich am Bahnhof zu sein.

### Adaption
* Markus hat Schwierigkeiten beim Lesen langer und komplizierter Sätze. Beim ersten Benutzen des Systems teilt er dem System diese Probleme mit. Das System verwendet daraufhin eine möglichst einfache Sprache mit kurzen Sätzen.
* Otto ist ein älterer Herr und leidet unter LRS. Vor allem kleine Texte auf dem Smartphone strengen ihn sehr beim lesen an, wodurch er unter anderem schlecht die Anweisungen von ÖPNV Apps lesen kann. Mit größeren Schriften hat er keine Probleme und liest gerne und viel. Vor kurzem hat er sich eine neue App heruntergeladen, in der er die Schrift beliebig verändern kann. So passt er das System an seine Fähigkeiten an und wählt für das Verwenden seiner ÖPNV App eine größere Schriftart.
* Paul ist 36 Jahre alt und hat eine Starke Sehschwäche. Viele Apps kann er nicht benutzen, da die Schrift oft zu klein ist. Paul versucht nur Apps zu nutzen, welche er die Schrift verändern kann

### Transparency
* Otto ist ein älterer Herr und leidet unter LRS und hat sich vor kurzem eine App heruntergeladen, die das Vereinfachen von Texten ermöglicht. Vor der ersten Inbetriebnahme der App, wurde Otto durch ein Onboarding geleitet. Hier wurde ihm erklärt, dass er den Text und die Schrift nach seinem Belieben anpassen kann, seine Einstellungen speichern und zugleich auch verwerfen kann. Nach dieser Erläuterung wurde ihm deutlich, welche Anpassungen mit der App möglich sind.
* Paul ist 36 Jahre alt und hat eine Starke Sehschwäche. Viele Apps kann er nicht benutzen, da die Schrift oft zu klein ist. Durch die Einführung und Erläuterung der App und die Anpassung der Schrift fühlt sich Paul sicher bei der Benutzung der App

### Performance
* Jan kommt mit Hilfe eines sehr strukturierten Tagesablaufs gut zurecht. Durch sozialen Druck auf der Arbeit oder Bekannten-Kreis kann es dazu kommen, dass er viele Dinge vernachlässigt und sehr unkonzentriert ist. Er wünscht sich in diesen Situationen, dass das System ihm kognitiven Load abnimmt und die (Um-)Planung, Beschaffung von Routen/Tickets oder Hinweisen auf real Ereignisse abnimmt. In Phasen, bei denen er sich sicher fühlt, oder auch Strecken, die er bereits kennt, möchte er diese Art der Unterstützung nicht, da er sonst von vielen Benachrichtigungen oder auditiven Signalen viel mehr gestresst wird und sich bevormundet fühlt.
* Paul ist 36 Jahre alt und hat eine Starke Sehschwäche. Paul stoßt oft auf Problem in seinen Tagesablauf.
Da es kaum Apps gibt, wo Paul Bestellung durchführen kann, da er die Produktbeschreibung nicht lesen kann. Paul wünscht sich Apps die ihn die Produkte vorlesen können.

### Context
* Anna fährt nicht gerne Bahn, da sie häufig durch wechselnde Zugverbindungen oder Wetterbedingungen (+ weitere Kontextinformationen), ihre Reise umplanen muss. Das System muss ihr frühzeitig Alternative Routen anbieten können. Wenn das System bei einer kombination von mehreren Kontextfaktoren merkt, dass eine erfolgreiche Reise mit dem ÖPNV unwahrscheinlich wird, muss das System auch externe Reisemittel vorschlagen können. Wenn Anna zu einem Termin kommen möchte, sollte das System reagieren und vorschlagen können, die Kontakte oder den Veranstaltungsort über die verspätete Ankunft zu informieren.
* Kim fühlt sich unter vielen Menschen unwohl, wird nervös und versucht zu große Menschenmassen zu vermeiden. Trotzdem kommt es manchmal vor, dass Kim keine andere Möglichkeit hat als zur Rushhour zu fahren. Das System soll wissen, dass Kim während der üblichen Reisen weniger Unterstützung braucht als während der Rushhour.  Durch Datenanalysen und Vorhersagen soll Kim bereits vor der Reise informiert werden und kann entscheiden, ob mehr Unterstützung und Hilfe benötigt wird als sonst.

### Commodity (Ressource)
* Robert hat von einem neuen System zur begleiteten ÖPNV-Nutzung gehört. Er möchte das System einmal ausprobieren. Hierbei kann er auch ohne Probleme ältere Hardware verwenden. So kann er beispielsweise sein fünf Jahre altes Smartphone verwenden, welches er eigentlich nur zum Telefonieren und SMS-schreiben verwendet und daher auch mit einem älteren Smartphone klarkommt.
* für Menschen, die kein Smartphone besitzen oder keins besitzen möchten soll eine kostengünstige externe Alternative verfügbar sein (vvlt ähnlich wie Navi) die sie bei der Reiseplanung  und während der Reise unterstützt.

### Safety
* Ursula nutzt das System hauptsächlich als Unterstützung während einer Reise mit dem ÖPNV. An einem kalten Wintertag steht für Ursula eine weitere Reise an. Es herrscht Glatteis. Das System weißt Ursula vor Beginn der Reise darauf hin. So kann sie sich darauf einstellen und passt bei Gehstrecken besonders auf.
* Lisa muss häufig die Nachtschicht übernehmen und aus diesem Grund häufig im Dunkeln mit der Bahn unterwegs sein. Zur allgemeinen Unterstützung nutzt Lisa eine App, die sie u.a. auf dem Weg zur Arbeit “begleitet”. Die App erkundigt sich alle paar Minuten nach Lisas Wohlbefinden und kontaktiert im Notfall oder bei keiner Rückmeldung eingetragene Kontakte.

### Independence
* Anna nutzt ungerne das ÖPNV, da sie häufig durch die großen Menschenmassen und den irreführenden Verkehr die Ruhe verliert. Zur besseren Orientierung nutzt sie eine App, die wie viele weitere Navigations-Apps eine Route anzeigt, die sie verfolgen kann. Bei bekannten Strecken, die Anna schon öfter gefahren ist arbeitet das System im Hintergrund und dient als “Fallback”. Bei Fällen in denen sich Anna unsicher fühlt, kann sie auf die App für Hilfestellungen zugreifen.
* Paul ist oft verunsichert, da er an eine Sehschwäche leidet und Problem im Alltag hat.
Paul verlässt nur die Wohnung, um notwendige Dinge zu erledigen. Paul wünscht sich Apps die ihn im Alltag unterschützen wie zum Spiel beim Einkaufen.

### Trust
* Lena ist sich nicht immer sicher welche Informationensquellen sie vertrauen kann. Wenn ein Zug Verspätung hat, nennen ihre Zug-Apps und die Systemen am Bahn-Gleis bzw. die der Bahn-Mitarbeiter:innen unterschiedliche Zeiten oder Gründe. Sie muss, um sich auf die abgeleiteten Handlungsempfehlungen verlassen zu können, sicher sein, dass sie ihr vertrauen kann. Gibt es unterschiedliche Meinungen, müssen diese gekennzeichnet werden.
* Paul ist oft verunsichert, da die Busse oft nicht zu den Zeiten ankommen, die in der App aufgegleisten sind. Durch die App(name der App) bekommt Paul immer die Liveansicht eines Busses angezeigt. Paul fühlt sich viel sichere, da er immer den aktuellen stand sieht.

### Privacy
* Daniel ist seine Privatsphäre sehr wichtig. Er möchte nicht, dass große Firmen seine Bewegungsdaten aufzeichnen. Auch hat er Bedenken, wenn andere Sensoren seines Handys die Umwelt messen. Deswegen schaltet er auf seinem Smartphone die meisten Erweiterungsfunktionen aus. Zusätzlich schaltet er meistens auch sein Handy aus. Webseiten auf denen er sich registrieren muss, besucht er nur sehr ungern.
* Nick möchte selbst entscheiden wann welche Daten geteilt und weiter verabreitet werden. 
das system soll nicht immer Zugriff auf Daten, Sensoren etc haben, sondern nur wenn wirklich für die Unterstützung benötigt


[^vsd]: Batya Friedman, David G. Hendry and Alan Borning (2017): "A Survey of Value Sensitive Design Methods", Foundations and Trends® in Human–Computer Interaction: Vol. 11: No. 2, pp 63-125. <http://dx.doi.org/10.1561/1100000015>

[^abd]: Jacob O. Wobbrock, Shaun K. Kane, Krzysztof Z. Gajos, Susumu Harada, and Jon Froehlich (2011): Ability-Based Design: Concept, Principles and Examples. ACM Trans. Access. Comput. 3, 3, Article 9 (April 2011), 27 pages. <https://doi.org/10.1145/1952383.1952384>

[^vsd-scenario]: Gilbert Cockton (2005): A development framework for value-centred design. In CHI '05 Extended Abstracts on Human Factors in Computing Systems (CHI EA '05). Association for Computing Machinery, New York, NY, USA, 1292–1295. <https://doi.org/10.1145/1056808.1056899>

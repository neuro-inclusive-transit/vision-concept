# System Architektur

Die System Architektur beschreibt alle technische Komponenten und ihrer Kommunikationskanäle untereinander.

![image](https://user-images.githubusercontent.com/19761338/226730030-7fa1d027-c030-4bc2-bcfe-4e45a2f81a21.png)

Grundlegig ist die Architektur in drei Komponenten aufgeteilt: Frontend, Backend-Services, Message Broker.

Es ist durch Anforderung `A24` gegeben, dass personen-bezogene Daten soweit es möglich sind auf den jeweiligen Endgeräten bleiben und allgemein so wenig wie möglich Sensor-Daten gesammelt werden. Demnach ist eine interne Datenspeicherung auf dem Endgerät notwendig.

Wird eine neue Route durch den:die Nutzer:in erstellt, findet eine synchrone Kommunikation mit dem Service RouteAPI statt. Dieser Service aggregiert Informationen zu Routen-Optionen (von einer externen API) mit bereits gesammelten Challenges oder Disturbances.

Die ChallengeAPI stellt eine Schnittstellen zum Beitragen von Herausfordernden Situationen (`A57`) bereit, sodass diese dem:der Nutzer:in in der jeweiligen Route angezeigt werden können (`A56`). 

Über die DisturbanceAPI werden Sachverhalte (Verspätungen, Unfälle, Baustellen, Unwetter etc.) die zu Veränderung der Routenoptionen führen vertrieben. Diese können dann in der initialen Routenlisten-Priorität berücksichtigt werden.

Um Nutzer:innen auf Situation hinweisen zu können, die während der Navigation stattfinden und durch externe Ereignisse bedingt sind, müssen diese asynchron an die Endgeräte kommuniziert werden. Der Message Broker verteilt die Daten über definierte Topics. Topics können nach Art und Ort bzw. Linie/Strecke abboniert werden.


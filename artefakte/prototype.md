# Prototype

Durch die intensive Auseinadersetzung mit der Problemdomäne, der Ausarbeitung von [Erfordernissen](./erfordernisse.md), [Anforderungen](./anforderungen.md), weiteren Artefakten und eines [NUI/GUI Konzepts](./nui-gui-konzept.md) konnte ein zuerst ein Low-Fidelity und dann ein High-Fidelity Prototype entwickelt werden.

## Low-Fidelity

Die Screens in der Low-Fidelity wurden die Zonen aus dem Navigations-Modell in der Gruppe aufgeteilt. Die einzelnen benötigten Screens wurden als Paper-Prototyp umgesetzt, und dann via Design Critique in der Gruppe diskutiert.

<details><summary><h3>Profil & Einstellungen</h3></summary>
<img src="https://user-images.githubusercontent.com/19761338/228832596-fa19f365-086e-480f-9e74-9e49deadc820.jpg" loading="lazy" alt="Paper-Prototypes für Profil & Einstellungen">
</details> 

<details><summary><h3>Route anlegen</h3></summary>
<img src="https://user-images.githubusercontent.com/19761338/228833605-88976aa2-87e0-441e-8a5e-5b5a3576337d.jpg" loading="lazy" alt="route anlegen">
</details> 

<details><summary><h3>Onboarding</h3></summary>
<img src="https://user-images.githubusercontent.com/19761338/228834202-e0c5adea-61bd-473d-993d-2c00d4352c52.jpg" loading="lazy" alt="onboarding">
</details> 

<details><summary><h3>Live-Ansicht</h3></summary>
<img src="https://user-images.githubusercontent.com/19761338/228834636-2fc4614c-a786-4d98-be7e-a51b69b58f91.jpg" loading="lazy" alt="live-ansicht">
</details> 



## High-Fidelity

Die Screens aus dem Low-Fidelity konnten dann in einer weiteren Iteration in einen HiFi-Prototyp überführt werden:

> [HiFi-Protoyp als Figma-Klickdummy](https://www.figma.com/proto/mJOAhkmtCtxVFNQRpSg7NC/P1-Prototype?page-id=19%3A381&node-id=573-10754&viewport=-4997%2C-227%2C0.53&scaling=scale-down&starting-point-node-id=573%3A10754&show-proto-sidebar=1)


### Style

Um ein konsequentes Aussehen des Prototyps zu erreichen wurden zunächsten die wichtigsten Design Elemente festgelegt. Um auch auf einer niedrigen Interaktionsstufe ein hohes Maß an Zugänglichkeit zu ermöglichen, wurden für den Style Prinzipien aus der WCAG[^wcag] und einer Sammlung von GUI-Elementen[^neurodiversity], die für nicht-neurotypische Personen entwickelt wurde, beachtet.

  - **Schrift:** Lesbarkeit für Menschen mit Dyslexia (Zielgruppe) muss gegeben sein. Da durch die User Test festgestellt wurde, dass die verwendete Schriftart nicht geeignet ist, wird im neuen Prototypen Atkinson Hyperlegibal verwendet. -> Bessere Lesbarkeit, da sich alle Zeichen voneinander unterscheiden.
  - **Grauwerte:** Kontrast-Werte von mind. AA (WCAG 2.0) -> bestehende Grauwerte (IBM‘s Carbon Design System) <br> <br> <img src="https://user-images.githubusercontent.com/117289466/227907595-1e066b20-24f4-417c-ae10-a44e1d07abd8.png" width="300">
  - **Farbe:** es soll verschiedene Farbschema geben, die in den persönlichen Einstellugnen geändert werden können <br> <br> <img src="https://user-images.githubusercontent.com/117289466/227905861-73da9d8b-b23b-4cd7-9e0a-baffd5c6d59e.png"  width="500">
  - **Buttons** wurden mit einem Schlagschatten versehen, um besser zu verdeutlichen, dass sie klickbar sind <br> <br> <img src="https://user-images.githubusercontent.com/117289466/227908564-2512cbd6-0449-4d55-aba0-4ffba0d110bc.png" width="300">


[^neurodiversity]: Neurodiversity Design System (NDS): https://www.neurodiversity.design
[^wcag]: Web Content Accessibility Guidelines (WCAG) 2: https://www.w3.org/WAI/standards-guidelines/wcag/
 

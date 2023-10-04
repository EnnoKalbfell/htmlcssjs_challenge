# 🐕 Projekt Hunderennen
In diesem Projekt kannst du eine Hunderennbahn gestalten (du darfst auch andere Tiere nehmen 😸). Es soll 5 Rennbahnen geben und die Möglichkeit auf den gewinner zu setzen. Anschliessend soll ein Modal aufgehen wo dir sagt ob du gewonnen oder verloren hast. Wie du das Rennen gestaltest ist dir überlassen, im folgenden Gif siehst du wie das Ganze mindestens aussehen sollte. 

⏳ 9 Tage

[![Beispiel](../02%20Ressourcen/03%20Hunderennen/cover.jpg)](../02%20Ressourcen/03%20Hunderennen/beispiel.mp4)

---

## ☑️ Anforderungen
- Es hat ein Formular in welchem man auf den vermuteten Sieger tippen kann und ein Button um das Rennen zu starten
- Es gibt 5 Rennteilnehmer, welche gegeneinander rennen und unterschliedlich schnell abschliessen
- Nach dem das Rennen beendet ist, geht ein Modal auf welches dir anzeigt ob du gewonnen oder verloren hast
- Im Modal wird angezeigt auf welchen Rennteilnehmer du gesetzt hast und wer gewonnen hat
- Die getRandomNumbers API wird verwendet um die Rangliste zu bestimmen
- Die Applikation funktioniert auch wenn die API nicht mehr erreichbar ist
- Nach Fertigstellung ist das Projekt commited und im Order [03 Abgabe/03 Hunderennen](../03%20Abgabe/03%20Hunderennen) abgelegt

### getRandomNumbers API
- URL: https://europe-west6-default-285415.cloudfunctions.net/getRandomNumbers
- Methode: POST
- Body: `{ quantity: 5, rangeMax: 47, rangeMin: 1, sorting: "asc" }` (sorting ist optional)

## Ressourcen
- [Hund Gif](../02%20Ressourcen/03%20Hunderennen/dog.gif)

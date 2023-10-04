# 🎰 Lottonummern Generator
In diesem Projekt kannst du deinen eigenen Lottonummern Generator erstellen. Der Generator soll Zahlen für einen Lottoschein generieren können. Du darfst selber wählen für welchen Lottoschein du die Zahlen generieren willst, wir haben im Beispiel mit Swiss Lotto und EuroMillions gearbeitet. Dieses Projekt wird wahrscheinlich etwas mehr CSS Aufwand geben, da das Ganze auch Mobile funktionieren soll.

⏳ 9 Tage

[![Beispiel](../02%20Ressourcen/01%20Lottonummern%20Generator/cover.jpg)](../02%20Ressourcen/01%20Lottonummern%20Generator/beispiel.mp4)

---

## ☑️ Anforderungen
- Es hat zwei Tabs mit welchen man zwischen den verschiedenen Lottoscheinen wechseln kann
- Die generierten Zahlen entsprechen den Vorgaben des jeweiligen Lottoscheins
  - Swiss Lotto: 6 Nummern von 1-42 und 1 Glückszahl von 1-6
  - EuroMillions: 5 Nummern von 1-50 und 2 Sterne von 1-12
- Nummern können hinzugefügt und enternt werden
- Angezeigte Nummern können neu generiert werden (Optional)
- Der Generator ist Responsive
- Die getRandomNumbers API wird verwendet um die Nummern zu generieren
- Die Applikation funktioniert auch wenn die API nicht mehr erreichbar ist
- Nach Fertigstellung ist das Projekt commited und im Order [03 Abgabe/01 Lottonummern Generator](../03%20Abgabe/03%20Lottonummern%20Generator) abgelegt

### getRandomNumbers API
- URL: https://europe-west6-default-285415.cloudfunctions.net/getRandomNumbers
- Methode: POST
- Body: `{ quantity: 5, rangeMax: 47, rangeMin: 1, sorting: "asc" }` (sorting ist optional)

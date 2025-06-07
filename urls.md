# Uitleg van de webadressen

De tv-pagina gebruikt een paar vaste paden. Hieronder staat wat ze doen:

| Pad | Betekenis |
|-----|-----------|
| `/` | Lijst van alle zenders. |
| `/:zender` | Speelt de kabelkrant af voor die zender. |
| `/:zender/Overview` | Laat alle dia's van die zender zien. |
| `/Preview` | Wordt gebruikt om één dia vooraf te bekijken. |

Het adres van de WordPress-website zet je in de variabele `VITE_API_URL`.

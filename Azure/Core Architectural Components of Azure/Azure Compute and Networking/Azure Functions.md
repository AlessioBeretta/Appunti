
- Piccoli pezzi di codice che vengono runnati totalmente in cloud
-  Funzioni di utility - Fanno qualcosa specifico per un tempo definito
- Triggerati da qualcosa che succede
	- Chiamata HTTP, timer, message queue, blob creation ecc..
- Non costosissimo 

- Free Tier: Un milione di esecuzioni per mese gratis
	- Modello serverless
- Può supportare design piu complicati
	- Funzioni che durano nel tempo
	- Opzione di hosting dedicate o premium

### Esempi di Funzioni

- Un piccolo codice che runna ogni giorno alle 12 am e riassume tutto il data di ieri
- Un piccolo codice che checka un container di blob per dei file nuovi, e fa qualcosa ogni volta che lo trova
- Un piccolo pezzo di codice che runna ogni 6 ore, e recupera il meteo da un API meteo accessibile

## Cosa significa Serverless?

- Non significa che non ci sono server, ma che non dobbiamo gestirli
- Dobbiamo assicurarci di scrivere e far funzionare il codice

## Serverless = Consumption-Based Pricing

- Paghi quello che usi 
- Niente richieste di soldi quando le app o database sono in Idle
- Non c'è bisogno di pre-acquistare o riservare le risorse.

## Esempio - SQL Databse

Azure SQL Database ha piu modalità

1. **DTU-Based:** Basato su un livello di prestazioni in base alla tariffa (S1,S2)
2. **vCore-Based:** Scegli la CPU, memoria etc.. Introdotto da Microsoft un paio di anni fa.
3. **Serverless**: Basta fornire i dati e le query, lui fa autoscaling in automatico su quanto serve.

## Serverless SQL - Key Features:

- Azure auto scala in automatico tra 0.5 e 80 vCores per query
- Paghi quanti vCore e spazio utilizzi per secondo
- Quando è in idle, non hai costi

## Esempio - Azure Functions:

Azure Functions è un esempio di serverless:
- 1 milione di esceuzioni al mese gratis
- Dopo di quello, paghi per ogni esecuzione e il suo tempo.
- Azure gestisce lo scaling in automatico

## Serverless Pros

- Non devi gestire il server
- Gestisce lo scaling in automatico
- Efficiente sui costi a intermittenza di lavoro

## Serverless Cons:

- I costi possono variare per mese
- Potrebbero esserci dei delay perchè il server ha bisogno di accendersi.

## Serverless Services:

- Functions
- Container Apps
- Kubernetes
- SQL Database
- Cosmos DB
## Riassunto

- Ti focussi sul codice e non infrastruttura
- Paghi l'attuale uso
- Ideale per carichi di lavoro a basso utilizzo



## Cos'è la Scalability?

E' la capacità di un sistema di soddisfare una domanda crescente o decrescente aggiungendo o rimuovendo risorse a seconda delle necessità.

Il termine elasticità indica l'automazione dell'aggiunta e della rimozione di risorse.

## Benefici dello Scalability

- Permette al sistema di adattarsi al cambio dell'utente e riuscire a gestire l'aumento di traffico senza richiedere cambiamenti al codice sorgente o cambio di sistema.

## Flusso del traffico

- Alcuni buisness hanno il traffico che fluttua in base al giorno e l'ora dell'anno. (Immaginiamoci un sito E-commerce durante il black friday)

## Vertical Scaling

- Detto anche "scaling up" o "scaling down"
- Aggiungere più risorse a un singolo server
- Incrementare il numero delle CPU, aumentare la memoria
-  **Ha un limite 
-  Azure - 96 vCPUs, 384 GB memory (massimo del upper limit di una macchina)
-  Non aumenta la disponibilità

## Horizontal Scaling

- Chiamato anche "scaling out " o "scaling in "
- Aggiungendo più server al sistema
- **Non ha limiti**
- Complicazioni aggiuntive per il  load balancing
- Aumenta la disponibilità

## Autoscaling

E' la possibilità di aumentare e diminuire in scala le risorse che permettono di controllare i costi.
## Impatto sul costo del sistema
- Aggiungere più risorse al sistema, aumenta il corso di solito Azure raddoppia per il numero di CPU. (Esempio da 2 CPU a 4 CPU, raddoppi il costo)
- Ridurre le risorse riduce il costo (Esempio Riduci da 8 CPU a 4 CPU, dimezzi il costo)
- Avere un sistema scalabile per avere un sistema perfettamente, in cloud si può puntare ad avere il server ideale
- Ottimizzare il costo riducendo le risorse inutilizzate
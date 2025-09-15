
## Tre caratteristiche per un servizio di alta qualità

- Availability
- Reliability
- Predictability


## Reliability

- E' la capacità di un sistema di riprendersi dai guasti
-  Azure ha tanti servizi per mantenere l'applicazione in corso nonostante un errore.

## Di quali errori parliamo?

- Hardware failure
- Network Interruptions
- Power Failures
- Large-scale regional outage

## Perchè ne abbiamo bisogno?

- Ci fidiamo che il Cloud provider stia facendo il possibile per mantenere la piattaforma affidabile
- Trasparenza durante i problemi di servizio.

## Come si ottiene?

- Auto-scaling
- Evitare i singoli punti di errore (Es. Se una VM ha un applicazione e quella VM ha un problema, l'applicazione automaticamente ha un problema.)
- Multi-region deployments
- Data backup and replication
- Health probes and self-healing

## Cos'è l'health probes?

L'health probes è un check automatico che determina la salute e la disponibilità delle applicazioni e dei servizi, usando metodi come richieste HTTP, connessioni TCP o esecuzione di comandi per verificare che un endpoint sia affidabile. 

## High Availability 

L'abilita del sistema di rimanere operativo agli utenti durante pianificate o non aggiornamenti.

Nessun provider offre il 100% di HA, perchè è impossibile.

## Planned Outages

- Aggiornamenti di Applicazioni
- Ricambio di Hardware
- Patch di SO
- Migrazione a un nuovo provider

## Unplanned Outages

- Problemi a livello Hardware
- Problemi di Rete
- Problemi di corrente
- Disastri naturali (Piogge, Temporali, Terremoti etc..)
- Cyberattacco
- Bug di software
- Poor scaling / architecture design


## Methods to Mitigate Planned Outages


- ### Gradual deployment strategy 
	Consiste nel distribuire un aggiornamento su pochi server, come 1 e mano a mano aggiungendo sempre più server facendo cosi monitorano la distribuzione.
- ### Easy rollblack plan
	Quando per esempio una distribuzione va male e si corrompe o si hanno errori, si può avere un piano di rollback per tornare alle versioni precedenti
- ### Frequent deployments
	  Far si di fare tante distribuzioni, più si fanno più saremo esperti di controllare e prevedere cosa può succedere.
- ### Automation 

## Methods to Mitigate Unplanned Outages

- ### Every single core component has redundacy
	 Dobbiamo assicurarci che ogni core / hardware abbia la ridondanza, da non avere l'applicazione che dipende solo ed esclusivamente da essa.
- ### Use Azure's built-in featuers for availability
	1. Availability Sets
	2. Availability Zones
	3. Cross-Region Load Balancing / Front Door
- ### Constant health monitroing / probes
	 Monitorare costantemente o periodicamente, può aiutare a prevedere se qualcosa sta andando male.
 - ### Automation
 - ### Strong security practices
 - ### Be geographically distributed
 - ### Have a disaster recovery plan
	   Avere un piano di riserva, può sempre tornare utile per prevenire in caso di vera neccesità il pericolo.
- ### Test recovery plan
	 Certo avere un piano di recovery non basta, se quel piano non viene testato non potremmo mai migliorarlo.
- ### Load Fix
	   Fare un sovraccarico sulle applicazioni, può farci capire quanti utenti possono usare l'app prima di andare in bottleneck.



# Binary Large Object (BLOB)

- Contengono tipologie di file (TXT, PDF, ZIP, CSV, XLSX, JPG, AVI, qualsiasi cosa)
- Messi liberamente in un container
- Questi dati sono chiamati "Unstructured data" perchè ci sono file di testo da PDF fino a Excel


## Container Storage

- Puoi creare multipli container
- Ogni container può contenere blobs
- Possono essere organizzati in cartelle (ma non sono file gerachici)
- Paghi ciò che usi

(In AWS un account storage viene chiamato Simple Storage Service (S3))

## Location

- Puoi creare piu multipli storage account in qualsiasi regione del mondo
- E' consigliato tenere i dati vicino al servizio o al consumatore (per questioni di velocità)
- Il prezzo varia in base alla regione


## Ridondanza

- Azure tiene 3 copie dei tuoi dati per default
- Localmente o zona ridondante
- Azure è quasi impossibile perdere un file, perchè ha altre 3 copie da cui recuperare (Dovrebbe avere 11 zeri di ridondanza)

# Ridondanza Globale

- Puoi scegliere la ridondanza globale per lo storage
- Azure terrà invece 6 copie dei tuoi dati
- 3 Localmente e 3 in un altra regione (es. se si sceglie Europa, la seconda regione sarà sempre Europa non Stati uniti ecc..)
- I dati vengono salvati in base alla sovranità della legge

# Access Tiers

- Esistono 4 Access tiers:
	-  **Hot** - Default, quello bilanciato
	-  **Cool** - Che può essere messo come default, storage meno costoso ma con operazioni di lettura e scrittura piu costose
	-  **Cold** - Ancora di piu economico, ma sempre piu costoso per operazioni di lettura/scrittura
	-  **Archive** - Non si può avere accesso immediatamente ai file, storage meno costoso che ci sia, ma operazioni di lettura/scrittura costose (consigliato per dati legali da ricordare per 10 anni esempio.)

## Failover

- Gli hard disk succede che si rompono molto frequentemente
- Azure si prende cura di tutto questo senza che tu debba fare qualcosa
- Con le 3 copie dei tuoi dati, possono ricreare un hard disk da dietro le quinte 
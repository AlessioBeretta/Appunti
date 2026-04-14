
Per copiare i dati da un account all'altro è consigliato usare AZCopy.

L'uscita di file in Azure comporta un costo mentre usando AZCopy si riduce questa cosa e si usa la rete dorsale (alta velocita di download / upload)

## Cos'è un Token SAS

Un SAS token (Shared Access Signature) è una stringa URI sicura che concede l'accesso limitato e temporaneo alle risorse di archiviazione di Azure (blob, file, tabelle, code) senza condividere le chiavi dell'account


# Funzionamento di AZCOPY

- Bisogna creare un Token SAS che ci permette di accedere alla risorsa
- Una volta generato l'url lo copierò in un blocco note e sarà (URL SORGENTE)
- Genero un token SAS della directory destinazione (URL DESTINAZIONE)
- Apro Azure Cloud Shell o apro il programma di AzCopy
- In shell uso il comando azcopy copy 'URL SORGENTE' 'URL DESTINAZIONE'

Volendo altrimenti si può usare Azure Storage Explorer se si ha una preferenza GUI rispetto a una CLI

Non tutte le regioni supportano le Availability Zones (esempio Canada East no, Canada Central si).

E' consigliato lanciare la macchina nella regione in cui ci sia l'Availability Zone:

![[Pasted image 20260412114002.png]]

+ Zonal Services
+ Zone-Redundant Services
+ Always Available Services

### Zonal Services 

+ Puoi scegliere una specifica Availability Zone in cui deployare il servizio.
+ Dovresti deployare il duplicato del servizio in un altra zona per avere più sicurezza
+ Esempio di servizio: Virtual Machine

### Zone-Redundant Services

+ Automaticamente Deployato tra le zone per te 
+ Non devi configurarlo
+ Esemio: Azure SQL Database


### Always Available Services

+ Servizi globali a cui Microsoft interessa che siano sempre attivi
+ Anche chiamati "Non-regional services"
+ Esempio: Azure Portal, Entra ID, Azure Front door


Alcuni servizi ti offrono la scelta tra zonal e zone-redundant ed è consigliato di lasciare che Microsoft scelga la tipologia piu adatta a noi.
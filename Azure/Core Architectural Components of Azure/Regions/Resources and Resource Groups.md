
![[Pasted image 20260412114606.png]]


### Resources

+ Una parola generica per rappresentare un servizio di Azure in cui si ha accesso, nello specifico Virtual Machine, Storage account o Database
+ Puoi creare una risorsa in maniere diverse: Azure Portal, CLI, Powershell
+ Ogni risorsa ha un nome specifico per te
+ Devono essere unici, non sempre
+ Di solito scegli tu la regione dove vuoi che la risorsa sia creata

### All Resources

- Una nuova subscription creata con zero risorse
- Molte risorse hanno dei costi associati
- La risorsa è associata con una (e una sola) subscription, che avrà un costo


### Resource Group

- Un raggruppamento logico di risorse
- Un resource group è associato a ogni regione, e può essere diverso per le risorse che contiene.
- Tutti i servizi nel gruppo di risorse devono avere un simile ciclo di vita

### Resource & Group

- Tutte le risorse devono appartenere a uno e un solo gruppo di risorse
- I permessi possono essere assegnati al gruppo di risorse
- Non c'è nessuna sicurezza offerta ai gruppi di risorse per la comunicazione

# Public network Access

![[Pasted image 20260413234550.png]]

Azure sconsiglia di abilitare la rete da tutti i network per una questione di sicurezza, se dovessimo trovarci ad utilizzarlo dovremmo considerare di usare delle regole molto ristrette limitando il più possibile il rischio.

Mentre è consigliato abilitare il network pubblico solo su dei network virtuali e indirizzi ip selezionati da noi.

Molto piu consigliato configurare dei network cosi anche se qualcuno dovesse avere una chiave d'accesso finchè non si connetterà alla rete da noi configurata non può accedere alla macchina.


L'opzione piu sicura è disabilitare il network pubblico e utilizzare solo endpoint privati

- Un endpoint privato è un'interfaccia di rete che utilizza solo indirizzi IP privati della propria rete virtuale Azure.
- Questo indirizzo IP privato si connette in modo privato e sicuro al vostro servizio Azure utilizzando Azure Private Link
- Azure Private Link è un servizio che abilità questa connettività privata, portando il servizio Azure nella vostra rete virtuale.

![[Pasted image 20260413235156.png|697]]

Queste stesse opzioni sono disponibili per molte risorse Azure, tra cui Azure SQL Database, cosmos DB, Azure Key Vault ecc...
![[Pasted image 20260413235256.png]]
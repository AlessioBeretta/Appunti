
# Cosa sono?

- L'abilità di limitare la possibilità di modificare o eliminare una risorsa
- Serve a prevenire la cancellazione accidentale (o malevola) di alcune risorse critiche

# Tipi di Resource Locks

- Read Only
- Can Not Delete


# Scope:

Puoi creare uno scope a livello:
	Risorsa
	Gruppo di risorsa
	Abbonamento

Anche se hai la risorsa, il lock preverrà di distruggere o modificare la risorsa finchè l'owner non toglierà il lock.
Utilizzando RBAC, puoi restringere chi può sbloccare

I resource lock sono una forma debole di sicurezza, bisognerebbe comunque avere un adeguato controllo sui ruoli.
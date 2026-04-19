
## Virtual Networking in Azure

+ Alcune volte chiamate VNets
+ Microsoft ha una network globale di calvi, switch e router - network fisico
+ In azure due VM non possono parlare fra di loro (questioni di sicurezza)
+ Virtual network hanno una analogia con il network fisico che andiamo a setuppare nel nostro ufficio nel data center - IaaS
+ In Azure è virtuale perchè effettivamente è un database entry in una tabella che stabilisce una strada tra VM A e VM B

## VNets

- Virtual network sono assegnati con un indirizzo che può essere IPv4 o Ipv6 o addirittura entrambi
- Sono IP privati, quindi non può avvenire l'accesso da fuori Azure o da altri network all'interno di Azure
- Ogni singola Vnet è assegnata di solito con una grande quantita di indirizzi per supportare una potenziale crescita
- Non c'è la possibilità di usare tutti gli indirizzi perchè sono milioni

## Subnets

- Tutte le VNets sono suddivise in uno o piu subnet
- La subnet è assegnata con un range di indirizzi IP che deve esistere nello spazio degli indirizzi della VNet padre.
- Di solito c'è un layer di sicurezza tra le subnet, in cui il traffico deve essere congruo a un set di regole predefinito.

## Virtual Machines

- Una virtual machine deve appartenere a una subnet, usando una Network Interface Card (NIC)
- Alcune VM hanno piu di un NIC e possono essere connesse a più di una subnet
- Le VM possono avere un indirizzo IP pubblico assegnato il che li fa rendere accessibili da fuori Azure.

## Network Security Group

- Anche chiamato NSG
- E' una lista di ACL che blocca il traffico in entrata e uscita da una subnet almeno che non matcha certe regole.
- Le regole sono basate da un **IP sorgente, porta sorgente, Ip di destinazione, porta di destinazione e protocollo** 

## NSG

- Possono comunicare tra piu diverse subnet sulla stessa network attraverso specifiche NSG rules
- Nessun traffico passa tramite il filtro NSG almeno che non ci sia una regola **"ALLOW"**
- Le regole hanno la priorità, e quella che ha la priorità piu alta sarà quella che verrà scelta
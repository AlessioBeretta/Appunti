
# Peering

- La comunicazione può essere bloccata tra due subnet su diversi network
- Collegare due subnet insieme viene chiamato **PEERING**
- Questo permette la comunicazione tra una VM su un network e un'altra VM su un altro network

# Azure DNS

- DNS sta per Domain Name System
- Puoi dare i tuoi indirizzi IP dei nomi tramite il DNS
- DNS si applica internamente ad Azure ai network che è applicato.


# Azure VPN Gateway

- VPN vuol dire Virtual Private Network
- Permette la comunicazione tra una workstation e un network o direttamente due network.
- Cripta il traffico attraverso la rotta.

## VPNs

- Al di fuori di Azure, VPN richiedono un dispositivo fisico installato sul network
- Dentro Azure, puoi installare un VPN Gateway come dispositivo virtuale sul tuo network
- VPN Gateway richiede la sua subnet.
		
Esempio se lavoriamo da casa:
Per lavorare da casa, avremmo bisogno di usare la VPN per connetterci al nostro network di ufficio, questo viene chiamato "point to site VPN" o (P2S) in cui il nostro computer desktop è il "point" e il network della compagnia è il "site"


## VPN Peering

- Si può anche connettere due network distanti usando dispositivi VPN
- Questo viene chiamato "site to site VPN", o S2S
- Per connettere un intero ufficio di computer a una subnet di Azure, o addirittura due uffici insieme

## ExpressRoute

- Se abbiamo bisogno di comunicare su Azure a velocità elevate è importante che usiamo ExpressRoute
- ExpressRoute è una connessione privata dal tuo ISP a un Azure endpoint
- Bypassa la rete pubblica, impedendo alle persone di sapere che quel traffico esiste.
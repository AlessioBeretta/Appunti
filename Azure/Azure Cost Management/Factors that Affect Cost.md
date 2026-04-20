
# Factor 1: Resource Type

Diverse risorse hanno diversi prezzi di scelta:
- VM sono pagate per quanto le utilizzi.
- Lo storage viene addebitato per la capacità e la sua ridondanza
- Networking può includere dei costi per il trasferimento di dati.


# Factor 2: Usage and Biling Model

Azure offre diversi modelli per pagare:

- Pay-as-you-go: Dal consumo paghi
- Istanze riservate: risparmi da 1 o 3 anni di precommitment
- Spot Pricing: Grandi sconti per workload che non possono interrompersi

# Factor 3: Service Tiers and Configuration

Servizi possono venire con piu SKU o Tiers:
- Esempio: App service - Free, Basic, Standard, Premium
- Scegliendo piu cpu, memoria o performance
- La scelta della regione aumenta il costo

# Factor 4: Licensing Costs

Alcuni servizi includono la licenza mentre altri no:
- Spesa in piu per Windows o SQL server per la licenza
- **Azure Hybrid Benefit** può farti risparmiare se hai già delle licenze.

# Factor 5: Data Transfer

- I dati in entrata sono di solito gratis
- I dati in uscita sono addebitati oltre al tier gratuito
- Trasferimenti tra regioni può anche costare soldi

# Factor 6: Idle or Unused Resources

Puoi essere addebitato per risorse che non usi:

- Runnare una VM senza che fa nulla ti costa soldi
- IP riservati o dischi gestiti possono generare addebiti

# Factor 7: Considerazioni EXTRA

- Storage Access Tiers: Hot, Cool, Archive
- Operazioni di read/write può avere micro-costi
- Servizi del marketplace possono aggiungere delle third-party fees

# Tools per Stima e Controllo costi

Azure offre dei tool per organizzare le tue spese:
- **Azure Pricing Calculator**: ti fa provare altre configurazioni
- **TCO Calculator**: comparazione tra servizio on-prem vs cloud
- **Cost Management + Billing**: monitora e ottimizza l'utilizzo attuale
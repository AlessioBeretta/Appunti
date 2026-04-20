
Infrastruttura parliamo di server, storage, impostazioni DB, impostazioni network, firewall, bilancio di carico ecc...

Bisogna creare un file configurazione e definire la nostra infrastruttura desiderata, e puoi deployarlo ecc...
Puoi ricrearlo in un altra regione per avere un duplicato salvato da qualche parte.


Usare l'automazione per rassicurare che la configurazione non cambi leggermente dal setup originale.

# IaC Options

- ARM Templates (JSON)
- Bicep
- Terraform
- Chef, Puppet
- PowerShell Script
- O altri tipi di codice

Supponiamo di avere 10 app da usare questi sono i problemi che possono sorgere:

- Usare 10 username e usare 10 password diverse in 10 app
- Cambiare la password in un posto non la cambia in tutte

Esiste una soluzione chiamata: **Single Sign On**

# Feature di Entra ID

- Entra ID provvede un token dicendo chi sei
- Il token è verificato da tutte le altre applicazioni della tua organizzazione
- Al posto di chiedere la password, controlla il token
- Autenticati una volta, lo sarai per sempre

# Come Funziona?

- L'app dev'essere registrata nell'Entra ID
- L'app si fida del tuo Entra ID
- Il token è criptato dal tuo Entra ID (chiave privata) e può essere decifrata solo dalla tua chiave pubblica

# Benefit del SSO

- **Per utenti:**
	-  Meno Login
	- Password forti / MFA meno fastidioso
- **Per organizzazione:**
- Maggiore sicurezza
- Intregrazione con MFA / Conditional Access
- Management semplificato

# Chi lo può usare?

- Microsoft App
- Le tue app
- App di terze parti come Zoom o Dropbox

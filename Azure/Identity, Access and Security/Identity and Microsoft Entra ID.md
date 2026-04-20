
"Identity" è la rappresentazione di una persona, applicazione o dispositivo


### Esempi di identità

- John Henry
- Johndoe@example.com
- La stampante al sesto piano

Di solito chiede una password, una chiave segreta o un certificato.
Tante applicazioni richiedono di loggarti per usare alcune delle loro funzionalità

![[Pasted image 20260416183935.png]]

## Perchè i sistemi d'identità vengono hackerati?

- Salvando password in puro testo
- Usando algoritmi di hashing datati come MD5
- Non rafforzando la complessità della password
- Niente cambio di policy per rinforzare le password


**Active Directory e Microsoft Entra non sono direttamente i rimpiazzi di ognuno** 

La vecchia **Active Directory** usava protocolli come **LDAP** e **Kerberos** per la comunicazione 
Mentre **Entra Id** usano protocolli come **SAML** e **Oauth** per la comunicazione.

Con Entra ID puoi usare APIs per gestire autenticazione e autorizzazione senza dover fare coding sul backend.

![[Pasted image 20260416184524.png]]
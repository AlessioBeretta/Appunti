
E' la soluzione preferita di Microsoft per autorizzazione e la firma dei permessi di Azure.
Permette la gestione dell'accesso tramite i propri ruoli.

Si inizia a creare i ruoli per la propria organizzazione
Assegnare il ruolo a quei determinati utenti
# Quale potrebbe essere un ruolo?

Supponiamo di avere 50 persone che lavorano come Developer IT e vogliamo dare determinati permessi per tutte le 50 persone.
Si può creare un ruolo con determinati permessi e caratteristiche e si può negare esempio (l'accesso ai backup) se vogliamo che quel determinato ruolo non lo faccia.

Viene anche chiamato **Principio dell'ultimo privilegio**

Si cerca di evitare eccezioni dove utente x ha permessi d'amministratore perchè poi inizia a diventare tutto piu difficile da gestire.

# I tre ruoli basic

- **Reader**: E' un ruolo di sola lettura
- **Contributor**: Forniscono l'accesso completo a una risorsa, ma non la possono condividere ad altri.
- **Owner**: Hanno la possibilità unica di assegnare il ruolo ad altri
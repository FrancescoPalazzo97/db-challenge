📚 nome repo: **`db-challenge`**
Facciamo un ripasso approfondito dei concetti fondamentali sui Database Relazionali e MySQL.

### 1. Progettazione DB

ILavorerai su 5 casi reali, ciascuno con una descrizione testuale. Per ogni caso:

1. Analizza il testo e individua entità, attributi e relazioni
2. Disegna il diagramma E/R utilizzando uno dei tool per grafici che conosci (vedi sotto la sezione reference)
3. Esporta il diagramma come immagine e caricalo nella repo
4. Scrivi una breve spiegazione delle scelte progettuali

**Casi reali:**

1. **Gestione Biblioteca**
- Libri, Autori, Prestiti, Utenti, Categorie
1. **Piattaforma di Food Delivery**
- Ristoranti, Piatti, Ordini, Clienti, Consegne
1. **Gestione Eventi**
- Eventi, Partecipanti, Location, Biglietti, Sponsor
1. **Sistema di Gestione Cinema**
- Film, Sale, Proiezioni, Spettatori, Prenotazioni
1. **Piattaforma Social**
- Utenti, Post, Media, Commenti, Likes

### 2. Query con MySQL

Proseguire con l'implementazione del DB Piattaforma Social usando MySQL.

Una volta sicuri del diagramma e/r, puoi passare alla nuova fase. Crea un nuovo database usando il un qualsiasi client MySQL e importate il file `db.sql` fornito. Aprite il file PDF e scrivete le query richieste. Al fianco di ogni richiesta, c'è il numero di risultati che dovrebbe restituirvi la query.

Dopo aver testato le vostre query, riportatele in un file `.txt` e caricatelo nella repo.

[db.sql](https://prod-files-secure.s3.us-west-2.amazonaws.com/4c49ff97-016b-4669-8de5-4479dd1a86e1/c0cf4898-2770-4b6b-a01d-64fdf163e018/db.sql)

[query-da-svolgere.pdf](https://prod-files-secure.s3.us-west-2.amazonaws.com/4c49ff97-016b-4669-8de5-4479dd1a86e1/0d2fda78-2f08-4342-9785-0258f03efe22/query-da-svolgere.pdf)

**⚠️ Note Importanti:**

- Prima di disegnare, ragiona sulle relazioni e sulle cardinalità
- Un errore comune è confondere attributi con entità
- Ogni entità deve avere una chiave primaria
- Documenta le scelte e le eventuali assunzioni

### Bonus

🚀 **Bonus 1 - Gestione tags:**

Ogni post può avere dei tags, parole senza spazi che servono per organizzare i contenuti e permettere agli utenti di connettersi e scoprire contenuti simili. I tag sono scelti liberamente dall'utente in fase di creazione post, ognuno può usare i tag che vuole e in quantità libera.

🚀 **Bonus 2 - Creazione diagramma e/r con Mermaid.js:**
Realizza il diagramma entità-relazioni di uno dei casi reali utilizzando la sintassi [Mermaid.js](https://mermaid-js.github.io/), uno strumento che permette di generare grafici direttamente da codice markdown. Inserisci il diagramma nel README o in un file dedicato.

✨ **AI Bonus - Generazione diagrammi per tutti i casi reali:**

Utilizza strumenti di intelligenza artificiale per generare automaticamente i diagrammi ER di tutti i casi proposti. Confronta i risultati con quelli manuali e documenta eventuali differenze o miglioramenti.

Buon kata! 🥷
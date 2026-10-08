# fcc-periodic-table-database
Progetto di ristrutturazione, refactoring e bonifica di un database contenente informazioni sugli elementi della tavola periodica, con interfaccia a riga di comando per l'interrogazione rapida.

Caratteristiche principali:

Normalizzazione completa dello schema esistente: scorporo di tipi di dati ridondanti in una tabella separata (types), impostazione di vincoli NOT NULL, UNIQUE e gestione di chiavi esterne.

Manipolazione e pulizia dati tramite comandi SQL (ALTER TABLE, conversioni di tipi NUMERIC, VARCHAR e rimozione di zeri superflui con espressioni regolari).

Sviluppo di uno script Bash (element.sh) per la ricerca dinamica di un elemento tramite numero atomico, simbolo chimico o nome completo, con gestione robusta di input errati o inesistenti.

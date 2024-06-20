
# Calcolatrice
**The Mulan Project**
Un ''semplice'' calcolatrice realizzata in Javascript Vanilla e Tailwind in stile Mulan. 

**Repository GitHub**
https://github.com/Robbs17/theMulanProject

# Struttura e funzionalità
Il codice crea una calcolatrice funzionante che consente agli utenti di inserire numeri, eseguire operazioni aritmetiche di base e utilizzare alcune funzioni speciali. 
Ogni azione dell'utente viene gestita tramite ascoltatori di eventi che aggiornano lo stato della calcolatrice e il display in tempo reale.


### PUNTATORI

1.  **Selezione degli elementi**:
    -   Il codice inizia selezionando tutti i pulsanti numerici della calcolatrice, identificati dalla classe "numero".
    -   Seleziona anche tutti i pulsanti delle funzioni, identificati dalla classe "funzioni".
    -   Inoltre, seleziona specifici elementi del DOM come il pulsante del punto decimale, il tastierino e il display.

### VARIABILI DI STATO

1.  **Array dei termini**:
    
    -   C'è un array vuoto che memorizza i numeri inseriti dall'utente durante le operazioni.
2.  **Termine attuale**:
    
    -   Una stringa vuota viene utilizzata per memorizzare il numero che l'utente sta attualmente digitando.
3.  **Operazione corrente**:
    
    -   Una stringa vuota per memorizzare l'operazione aritmetica selezionata dall'utente (ad esempio, addizione, sottrazione).
4.  **Indicatore decimale**:
    
    -   Una variabile booleana che indica se il numero attuale è decimale (cioè, contiene un punto decimale).
5.  **Display temporaneo**:
    
    -   Una stringa che memorizza temporaneamente il valore da visualizzare sul display della calcolatrice.

### FUNZIONI

1.  **Aggiornamento del display**:
    
    -   Questa funzione aggiorna il display della calcolatrice con il numero che l'utente sta attualmente digitando.
2.  **Funzioni speciali**:
    
    -   Una funzione che gestisce operazioni speciali come il reset della calcolatrice, il cambio di segno di un numero e la conversione di un numero in percentuale.
    -   Per esempio, se l'utente preme "C", la calcolatrice viene resettata, svuotando il display e azzerando tutti i termini memorizzati.
3.  **Esecuzione delle operazioni aritmetiche**:
    
    -   Una funzione che esegue le operazioni matematiche di base (addizione, sottrazione, moltiplicazione, divisione).
    -   Utilizza i numeri memorizzati nell'array dei termini per calcolare il risultato e aggiorna il display con questo risultato.

### GESTORI DI EVENTI

1.  **Pulsanti numerici**:
    
    -   A ciascun pulsante numerico viene aggiunto un ascoltatore di eventi che, quando il pulsante viene cliccato, aggiunge il numero corrispondente al termine attuale e aggiorna il display.
    -   C'è una condizione per evitare l'aggiunta di più zeri all'inizio di un numero non decimale.
2.  **Pulsante del punto decimale**:
    
    -   Aggiunge un punto decimale al termine attuale solo se non è già presente e se il termine attuale non è vuoto.
3.  **Pulsanti delle funzioni**:
    
    -   A ciascun pulsante delle funzioni viene aggiunto un ascoltatore di eventi che, quando il pulsante viene cliccato, verifica se si tratta di un'operazione speciale (come il reset, il cambio di segno o la conversione in percentuale) e la esegue se necessario.
    -   Se l'operazione non è speciale, memorizza l'operazione aritmetica da eseguire e, se ci sono almeno due termini, esegue l'operazione e aggiorna il display con il risultato.

### HTML

1.  **Struttura della calcolatrice**:
    -   L'HTML fornisce la struttura visiva della calcolatrice, con un display per mostrare i numeri e un tastierino con pulsanti numerici e funzioni.
    -   I pulsanti sono organizzati in una griglia, con un pulsante speciale per ciascuna delle funzioni aritmetiche e numeriche.


## Coding Rules

- **Convenzioni di Linguaggio:** Nel nostro progetto, utilizziamo l'italiano per tutti i nomi delle variabili, funzioni, e commenti. Questa scelta è stata fatta per garantire che il codice sia facilmente comprensibile da tutti i membri del team.
 - **Tecnologie:** JAVASCRIPT - TAILWIND - FIGMA
 -  **Stile di Scrittura:** camelCase
 - **Tool di Formattazione:** PRETTIER
 - **Variabili:** LET, CONST
 - **Brackets Style:** K&R (Kernighan and Ritchie) Style, la parentesi graffa di apertura `{` viene posizionata sulla stessa riga dell'istruzione che apre il blocco.
 - **Funzioni:** Utilizzo di Arrow Function, Guard Clause, CallBack
 - **Commenti:**  Usa i commenti su singola linea per brevi spiegazioni o note. - Posiziona i commenti su singola linea sopra la linea di codice a cui si riferiscono, oppure alla fine della linea se la spiegazione è breve.
 -  **Documentazioni:** Tailwindcss.com, MDN, W3S 
- **Piattaforma di Comunicazione:** ZOOM

## ROADMAP

#### Fase 1: Refactoring e Miglioramenti di Base

1.  **Pulizia del Codice**:
    
    -   Riorganizzare il codice JavaScript per migliorarne la leggibilità.
    -   Separare la logica delle operazioni dalle manipolazioni del DOM.
    -   Implementare un sistema di moduli per separare le funzioni in file distinti (se non già fatto).
2.  **Commenti e Documentazione**:
    
    -   Aggiungere commenti esplicativi al codice esistente.
    -   Scrivere una documentazione dettagliata delle funzioni principali.
#### Fase 2: Aggiunta di Funzionalità Avanzate

1.  **Storico delle Operazioni**:
    
    -   Implementare una funzione per visualizzare lo storico delle operazioni effettuate.
    -   Aggiungere un'area del display o una sezione separata per mostrare lo storico.
2.  **Funzione di Memoria**:
    
    -   Implementare funzioni di memoria come "M+", "M-", "MR" (recall), "MC" (clear).
    -   Aggiungere pulsanti aggiuntivi al layout per queste funzioni.
3.  **Gestione degli Errori**:
    
    -   Migliorare la gestione degli errori, ad esempio divisione per zero, input non valido.
    -   Mostrare messaggi di errore chiari sul display.

#### Fase 3: Miglioramenti dell'Interfaccia Utente

1.  **Miglioramento del Layout**:
    
    -   Migliorare lo stile del layout utilizzando CSS e Tailwind CSS.
    -   Assicurarsi che la calcolatrice sia responsiva e funzioni bene su dispositivi mobili.

# TEAM
**The Mulan Project Team**

**Spigapiena Gianluca** *Web Developer & Mechanical Engineer* 
https://github.com/GianlucaSpigapiena  
  
**Bertello Marta** *Web Developer & Illustrator*
https://github.com/mbertt  
  
**Ganci Roberta** *Web Developer - UI-UX Designer* 
https://github.com/RobertaGanci

**Tahmasebi Mehdi** *Web Developer - React Developer* 
https://github.com/MedhiTahmasebi

**Acquarelli Roberta Luigia** *Web Developer - Cat Petter* 
https://github.com/Robbs17

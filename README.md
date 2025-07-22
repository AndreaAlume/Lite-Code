# Lite-Code

## Description

Lite Code ha come obbiettivo quello di diventare l'IDE di riferimento per programatori esperti che ricercano un **consumo limitato delle risorse ed elevate performance** senza rinunciare a quelle
funzionalità che permettono di rendere il lavoro più efficente e fluido.

Per raggiungere questo obbiettivo ho pensato di fondere le funzionalità dell'IDE indiscusso più utilizzato al mondo, Visual Studio Code, ma al tempo stesso integrare le potenzialità dello storico
Vim, con le sue shortcut da tastiera che permettono, una volta acquisite con una certa dimestichezza, un lavoro molto più produttivo.

## Analisi requisiti 

### Editor di testo

L'editor di testo in cui il programmatore dovrà scrivere il codice avrà le funzionalità di:

- Conteggio delle righe
    - e una funzionalità (attivabile o disattivabile a piacimento) che modifichi dinamicamente il conteggio delle righe in base a dove si posiziona il cursore
- Evidenziazione della sintassi errata e della punteggiatura mancante
    - una funzionalità da implementare è l'auto-correzione della sitassi (e punteggiatura) la dove comprensibile. ESEMPIO: scrivo *"prift('ciao');"* e il software mi corregge in automatico con *"print('ciao');"*
- Breakpoint: dare la possibilità all'utente di debuggare in uno o più punti del codice estraniando il blocco per renderlo comunque funzionante
- Flag e note: permettere all'utente di aggiungere delle flag personalizzate (in revisione, da ottimizzare, ecc...) e delle note personali in merito al codice (in un singolo punto o in un intero blocco) come documentazione o dei promemoria
- Compilazione e/o esecuzione intelligente: il software capisce qual'è il linguaggio e modifica il parametro di compilazione da lanciare per eseguire il codice. *ESEMPIO: se scrivo un programma in python il comando per eseguire il codice sarà diverso rispetto a Java*
- Split view dei file: così da poter dare all'utente la possiblità di lavorare su più file in simultanea
- Find & replace: dare la possibilità all'utente di ricercare una parola (come il nome di una variabile) e potrerla sostituire.

### Modalità Vim-Like

- Modalità lettura: tramite questa funzionalità l'utente non potrà scrivere nel file, ma potrà solo leggerne il contenuto
- Modalità scrittura: per scrittura del codice
- Modalità per comandi: per inserire dei comandi come fossero da terminale, verrà scritta una documentazione completa per ognuno di essi

# Osservazioni — Esercitazione 0

Gruppo:
CM-B6

Componenti (nome, cognome e username GitHub di entrambi):
Marta Masi masi-marta-2279063
Francesca Nervino nervinofrancesca

URL del repository condiviso:
git@github.com:masi-marta-2279063/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2:
entrambe

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:
gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato:
./hello
Il risultato osservato è che a differenza del codice fornito all'inizio adesso il codice stampa sul terminale la frase "Hello, computational physics!"

Che cosa ho capito su sorgente ed eseguibile:
hello.c è il file sorgente, ovvero il file di testo scritto in linguaggio C, mentre hello è il file eseguibile, ossia un file binario che contiene le istruzioni in linguaggio macchina generate dal compilatore.

Output richiesto e comportamento del programma prima della modifica:
L'output richiesto prevedeva la stampa della stringa "Hello, computational physics!". Prima della modifica il codice compilava perfettamente perchè non erano presenti errori sintattici, ma non eseguiva alcuna operazione di stampa sul terminale.

Esito dopo la modifica e spiegazione della correzione:
Dopo la modifica abbiamo osservato che il codice stampava nel terminale, questo è dovuto all'aggiunta del comando printf nel codice iniziale.

DOMANDE STIMOLO:
-Se modifico il messaggio nel sorgente (quindi hello.c) e avvio subito l'eseguibile osservo che il messaggio non viene stampato nel terminale poichè viene utilizzata la versione precedente.
-Quando ricompilo, il compilatore legge il codice aggiornato, sovrascrivendo il vecchio file eseguibile con quello nuovo, quindi adesso il file riflette lo stato attuale del codice sorgente.
-Ciò che stampa il programma è il flusso di dati inviato sullo standard output, in questo caso tramite la funzione printf, mentre ciò che mostra il terminale è l'interfaccia testuale che riceve quei dati. Eseguendo il comando >output.txt noto che ciò che doveva apparire sul terminale appare invece sul file txt, perchè reindirizzato lì con il comando prima menzionato.

## Step 1 — Git

Quali file ho incluso nel commit e perché:
Nel commit ho incluso il file hello.c perché è il file sorgente in cui è stata inserita l'istruzione di stampa richiesta; e osservazioni.md, poichè contiene le risposte alle domande stimolo e la documentazione scritta delle osservazioni fatte durante l'esercitazione.

Come ho verificato che la versione provata sia presente su GitHub:
Eseguendo il comando git log --oneline -5 nel terminale ho visualizzato l'hash dell'ultimo commit effettuato e ho verificato che corrispondesse all'identificativo dell'ultimo commit visibile nella cronologia sul repository su Github. Poi ho aperto il file direttamente su Github per verificare che effettivamente il loro contenuto risulti con le modifiche che ho effettuato.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:
Facendo 'git pull' osservo che dal terminale 

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato:

Che cosa posso concludere:

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:

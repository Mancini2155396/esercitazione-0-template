# Osservazioni — Esercitazione 0

Gruppo:C31

Componenti (nome, cognome e username GitHub di entrambi):
Nicolò Mancini, Mancini2155396,  Giacomo Fochesato, fochesato2095562-arch,
URL del repository condiviso:

Chi ha usato la tastiera nello step 1 e nello step 2:
Entrambi a turni 
Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione:gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello
./hello

Comando di esecuzione e risultato osservato:./hello  Hello, computational physics!

Che cosa ho capito su sorgente ed eseguibile: il file sorgente contiene il codice in C mentre l'eseguibile è il file binario generato dal file sorgente che viene eseguito dal sistema operativo

Output richiesto e comportamento del programma prima della modifica:
prima della modifica il main conteneva solo il commento senza nient'altro, l'output richiesto non usciva perchè non c'era printf("Hello, computational physics!/n") 
Esito dopo la modifica e spiegazione della correzione:
il programma stampa la riga richiesta la correzione sta nel mettere: printf("Hello, computational physics!/n")
## Step 1 — Git

Quali file ho incluso nel commit e perché: ho incluso hello.c e osservazioni.md perchè cosi posso utilizzare il file sorgente hello.c e osservazioni.md perchè era richiesto

Come ho verificato che la versione provata sia presente su GitHub: ho controllato la repository su github e ho controllato che i file contenessero le modifiche

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone:prima di git pull il file locale su terminale non aveva le modifiche , mentre dopo il pull si è aggiornato subuito, non serve un nuovo clone perchè git pull scarica direttamente i nuovi commit.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: nessun argomento passato, con il codice ./eco e abbiamo ottenuto ./eco testo intero reale

Che cosa posso concludere: non mettendo argomenti da come risultato quelli preimpostaqti

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: argomenti passati 3 con il comando: ./eco spaghetti 2 6.8 e abbiamo ottenuto spaghetti 2 6.800000

Che cosa ho capito su testo, conversioni e stampa: che il testo rimane una stringa, atoi converte la stringa in un intero e atof la converte in un double, mentre per printf vanno usati %s %d %f.
## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:
probabilmente l'esecuzione per 'dodici darà un errore.
Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:
eco.txt contiene l'output mentre il codice di uscita è 0 
Come un controllo automatico può riconoscere un errore:
se il codice di uscita non è 0
## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:
si ricompila se il codice sorgente non è più adeguato all'uso 
## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:
con git log 
Come ho verificato che la versione finale sia presente su GitHub: ho controllato la repository su github 
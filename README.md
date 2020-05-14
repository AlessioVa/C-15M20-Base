# PodisticaCovid19

Gli organizzatori della Podistica “Il Covid ha i minuti contati”, hanno pensato di far partire i partecipanti con 2 minuti di distacco l’uno dall’altro, per mantenere il distanziamento sociale. Una modalità simile al rally automobistico.

Questo significa che all’arrivo di ognuno, occorrerà tener conto di questo tempo supplementare, sottraendo i minuti trascorsi in attesa del proprio turno, poiché il timer di arrivo è unico.

I tempi dei partecipanti dovranno tener conto del ritardo nella partenza di ognuno e quindi:

+ per il primo concorrente partito (NON il primo arrivato, fa fede il pettorale, cioè l'ordine di partenza!) il tempo impiegato è lo stesso mostrato dal cronometro (tolgo zero minuti)
+ per il secondo concorrente partito il tempo impiegato è quello mostrato dal cronometro meno 2 minuti
+ per il terzo concorrente partito il tempo impiegato è quello mostrato dal cronometro meno 4 minuti
+  e via così


## Cosa deve fare il programma.
+ Creare una struct contiene il nome dell’atleta, il sesso, il tempo supplementare e il tempo impiegato dall’atleta, così come registrato dal cronometro all’arrivo.
+ Utilizzare un'array delle struct definita, sapendo che ci sono al massimo 100 atleti (somma di maschi e femmine)
+ ... InsertRunner(...) permette di registrare un partecipante nella struct; i parametri sono *ALMENO* tre: nome, sesso e tempo registrato;  il tempo supplementare deve essere calcolato automaticamente. Non restituisce nulla.
+ La funzione ... BestBoy(...) che restituisce il concorrente che ha vinto la gara; 
La funzione ... BestGirl(...) che restituisce la concorrente che ha vinto la gara; 
+ il main che 
  + richiama la funzione InsertRunner() per inserire i partecipanti; la funzione è richiamata in un ciclo con scelta del tipo: “vuoi inserire un’altro partecipante? (s/n); l’ordine di inserimento corrisponde all’ordine di partenza;
  + visualizza il nome restituito dalla funzione BestBoy();
  + visualizza il nome restituito dalla funzione BestGirl();

NOTA: Le funzioni BestBoy e BestGirl non devono avere nessuna istruzione di input output!
NOTA2: Potete usare variabili globali, se lo ritenete necessario. Potete anche AGGIUNGERE parametri alle funzioni, se lo ritenete necessario. Ma non potete toglierne.


# DATI DI ESEMPIO

DATI DI PROVA (in ordine di partenza)
Evan Dunfee(M)		05'
Yusuke Suzuki(M) 		06'
Li Maocuo(F)			30'
Joao Vieira(M)		11'
Eleonora Anna Giorgi(F)	37'
Liang Rui (F) 		33'

BestBoy deve restituire Yusuke Suzuki
BestGirl deve restituire Liang Rui

 
 

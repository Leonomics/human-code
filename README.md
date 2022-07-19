# ESERCIZIO 8

variabili e oggetti:
    -tavolo
    -lista con i nomi degli invitati
    -insieme delle persone che abitano nella casa dove si svolgerà il pranzo
    -variabile "numero commensali"
    -posto a tavola
    -variabile "numero posti a tavola"

-prendere la lista degli invitati
-scorrere i nomi sulla lista e aggiungere +1 al valore "numero commensali" per ogni persona che compare sulla lista
-contare le persone che già abitano nella casa dove si svolgerà il pranzo e aggiungere questo numero al valore della variabile "numero commensali". (Questo passaggio perchè si presuppone che chi abita nella casa dove si svolgerà il pranzo vi partecipi, ma non potendosi autoinvitare non compare sulla lista degli invitati)
-avvicinarsi al tavolo dove si svolgerà il pranzo. 
-aggiungere +2 alla variabile "numero posti a tavola" per ogni coppia di posti già preparati che si vedono sulla tavola
    -SE "numero di posti a tavola" è uguale a "numero commensali" allora FINE.
    -SE "numero di posti a tavola" è minore di "numero commensali" allora si aggiunge un posto
        -WHILE (fintanto che) "numero di posti a tavola" è minore di "numero commensali" allora si aggiunge un posto. Quando "numero di posti a tavola" è uguale a "numero commensali" allora FINE.
    -SE "numero di posti a tavola" è maggiore di "numero commensali" allora si toglie un posto
        -WHILE "numero di posti a tavola" è maggiore di "numero commensali" allora si toglie un posto. Quando "numero di posti a tavola" è uguale a "numero commensali" allora FINE.


L'esercizio partiva dal presupposto che manca un posto quindi si verificherà il secondo SE.


​
 # Esercizio numero 8 - Team 2 - Versione scelta dal gruppo
 ___________________________________
​
- Chiedo a nonna quanti siamo E me lo segno su una lista
- Prendo la lista
- Conto i posti a tavola di 2 in 2
- Confronto il numero di invitati con il numero delle sedie
- SE il numero dei posti =/= numero degli invitati ALLORA
    - SE il numero dei posti > numero degli invitati ALLORA togli la differenza
    - ALTRIMENTI aggiungi la differenza
- ALTRIMENTI apparecchia
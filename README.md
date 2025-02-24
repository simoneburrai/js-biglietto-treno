# Biglietto del Treno.

## Info

Il progetto di oggi, salvato come progetto n.18 del corso Boolean, prevede la 
creazione di un semplice programma tramite JS per il calcolo del prezzo di un 
biglietto del treno, in base ai chilometri percorsi e ad eventuali sconti in base 
all'età del passeggero.

*Qui di seguito viene riportato l'elenco di passaggi che ho eseguito per l'esecuzione
di questo programma.*

### **Richiesta dati utente**

    - Prompt che richiede l'input da parte dell'utente per quanto riguarda il numero di chilometri da percorrere;
    - Attirbuzione Chilometri ad una variabile;
    - Prompt che richiede l'input da parte dell'utente per quanto riguarda l'età del passeggero;
    - Attribuzione età ad una variabile.

### **Calcolo prezzo totale del viaggio**

    - Il prezzo del viaggio è uguale al numero di chilometri da percorrere * 0.21 €.

### **Condizioni da rispettare**

    - Se l'età del passeggero è minore di 18, il prezzo del viaggio è uguale a *prezzo del viaggio* - *20% del prezzo del viaggio*
    - Se l'età del passeggero è maggiore o uguale a 65, il prezzo del viaggio è uguale a *prezzo del viaggio* - *40% del prezzo del viaggio*

### **Risultato**

    - Eseguire il console log del risultato, approssimando il risultato con massimo due cifre decimali.
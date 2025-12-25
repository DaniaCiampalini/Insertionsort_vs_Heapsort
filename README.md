# Confronto algoritmi di ordinamento: Insertion-sort vs Heap-sort
Il progetto consiste in un Jupyter Notebook sviluppato per analizzare e confrontare le prestazioni di due celebri algoritmi di ordinamento: ##Insertion-sort e ##Heap-sort.

## Struttura del progetto
Il notebook è organizzato nelle seguenti sezioni:
1. Introduzione e descrizione degli algoritmi
2. Implementazione degli algoritmi in codice Python
3. Generazione dati attraverso funzioni per generare dataset casuali, garantendo che ogni esecuzione utilizzi dati diversi per evitare bias
4. Testing su diverse dimensioni di input (n)
5. Analisi risultati attraverso visualizzazione grafica dei tempi di esecuzione e confronto delle complessità computazionali

## Requisiti e ambiente
Il progetto è stato sviluppato utilizzando le seguenti tecnologie:
- PyCharm 2025.1.1.1
- Anaconda (Conda Environment)
- Python 3.13
  
Le principali librerie usate all'interno del notebook sono:
- matplotlib per la generazione dei grafici di confronto
- numpy per la gestione dei viettori e dei dati di test
- time per la misurazione accurate delle performance

Il progetto può essere anche completamente eseguito come notebook Jupyter su Google Colab.

## Analisi teorica
Il notebook include una documentazione in Markdown che esplora il trade-off tra i due algoritmi distinguendo caso migliore, caso medio e caso peggiore ed evidenziando le diverse prestazioni in base alla disposizione dei dataset in entrata e alle loro dimensioni n.
Il sistema di generazione dati usa la funzione random senza seed fisso per assicurare che esecuzioni diverse generino dati diversi, permettendo un'analisi statistica più robusta.
I risultati sono ben commentati all'interno dei Markdown finali.

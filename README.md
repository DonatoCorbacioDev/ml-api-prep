# ML API Prep – Titanic Dataset

Questo progetto è un mini progetto di Machine Learning realizzato con l’obiettivo di consolidare il metodo e la pipeline completa di un problema di classificazione supervisionata.

## Obiettivo

Predire la sopravvivenza dei passeggeri del Titanic utilizzando tecniche di Machine Learning.

## Dataset

Viene utilizzato il dataset Titanic, contenente informazioni sui passeggeri (età, sesso, classe, porto di imbarco, ecc.).

## Pipeline

Il progetto segue i seguenti step:

1. Analisi esplorativa dei dati (EDA)
2. Gestione dei valori mancanti
3. Encoding delle variabili categoriche
4. Suddivisione train/test
5. Modello di baseline (Logistic Regression)
6. Valutazione con confusion matrix e classification report

## Modello

È stato utilizzato un modello di **Logistic Regression** come baseline, ottenendo un'accuracy di circa **0.81** sul test set.

## Analisi non supervisionata

È stata effettuata un’analisi non supervisionata sul dataset Titanic utilizzando KMeans, con l’obiettivo di individuare gruppi naturali di passeggeri senza utilizzare la variabile target.

L’analisi ha evidenziato cluster coerenti e interpretabili in termini di età, classe di viaggio e composizione familiare.

## Struttura del progetto

- `data/` → dataset
- `notebooks/` → notebook di esplorazione e modellazione
- `README.md` → descrizione del progetto

## Note

Il progetto ha scopo formativo ed è stato realizzato come preparazione in ambito Data / Machine Learning.

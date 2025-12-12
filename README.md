# DataSet_SuicideRates
Gruppo Emanuele Anzellotti, Anna Firinu, Gianmario Palleschi, Mario Roggi

## Obiettivi del Progetto
Il progetto ha l’obiettivo di analizzare il dataset 'Suicide Rates Overview 1985–2016' attraverso data cleaning, feature engineering, analisi statistica ed esplorativa, fino alla produzione di grafici e alla valutazione delle relazioni tra le variabili.

## Pulizia del Dataset (Data Cleaning)
- Rimozione/correzione valori mancanti
- Uniformazione formati numerici
- Standardizzazione delle colonne stringa
- Trasformazione del PIL da stringa a numero intero
- Gestione di duplicati

## Individuazione e Gestione degli Outlier
- Rimozione degli outlier estremi

## Analisi di Correlazione
- Matrice di correlazione tra le variabili numeriche
- Visualizzazione con heatmap

## Feature Engineering
- Creazione di nuove feature utili

## Visualizzazioni e Grafici
- Tasso di suicidi per genere/eta
- Tasso di suicidi per reddito
- Andamento suicidi nel tempo
- Media di suicidi per anno e continente
- Media di suicidi per 100k abitanti per continente
- Tasso medio di suicidi per fasce di popolazione

## Modello di previsione applicando Catboost
- Utilizzo di Catboost con Optuna per predirre la variabile suicides_rate
- Analisi features importance
  

# Data Mining Project — Board Games Analysis (A.A. 2025/2026)

Progetto didattico per l'esame di **Data Mining** (Università di Pisa).  
L'analisi è stata condotta su un dataset di oltre 20.000 giochi da tavolo valutati da una community online[cite: 1].

## Autori
* **Chiara Giordano**
* **Francesco Santerini**

## Struttura del Progetto
Il progetto si articola nelle quattro fasi principali previste dalle linee guida dell'insegnamento[cite: 1]:

1. **Data Understanding & Preparation[cite: 1]:**
   * Analisi delle variabili, statistiche descrittive e distribuzioni[cite: 1].
   * Data cleaning, gestione dei valori mancanti, outlier e trasformazioni di variabili[cite: 1].
   * Analisi delle correlazioni a coppie[cite: 1].

2. **Clustering[cite: 1]:**
   * Metodi basati su centroidi (**K-Means**)[cite: 1].
   * Metodi basati sulla densità (**DBSCAN**)[cite: 1].
   * Clustering gerarchico con analisi dei dendrogrammi[cite: 1].
   * Valutazione comparativa e discussione dei cluster trovati[cite: 1].

3. **Classification & Regression[cite: 1]:**
   * Classificazione della variabile target `Rating` tramite **Decision Trees**, **KNN** e **Naive Bayes**[cite: 1].
   * Task di Regressione lineare (singola e multipla) e approcci non lineari[cite: 1].
   * Valutazione delle performance (Matrice di confusione, Accuracy, Precision, Recall, F1, curve ROC, MSE, $R^2$)[cite: 1].

4. **Pattern Mining[cite: 1]:**
   * Estrazione di frequent pattern e regole di associazione (al variare di supporto e confidenza)[cite: 1].
   * Utilizzo delle regole estratte a supporto delle analisi[cite: 1].

## Tecnologie Utilizzate
* **Python** (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
* **Google Colab / Jupyter Notebook**
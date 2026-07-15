# Astronomical Objects Analysis and Classification

Progetto di Laboratorio di Big Data, Data Mining e Data Analytics dedicato all'analisi e alla classificazione di oggetti astronomici.

## Autori

- **Manuel Menghetti** — manuel.menghetti@studio.unibo.it
- **Fabian Calangiu** — fabian.calangiu@studio.unibo.it

## Descrizione

Il progetto utilizza un dataset astronomico contenente osservazioni provenienti dalla Sloan Digital Sky Survey.

L'obiettivo è analizzare le caratteristiche fotometriche degli oggetti celesti e classificarli in tre categorie:

- **GALAXY**
- **STAR**
- **QSO**

L'analisi considera le magnitudini osservate nelle bande fotometriche `u`, `g`, `r`, `i` e `z`, insieme agli indici di colore derivati.

Dopo una fase di pulizia ed esplorazione dei dati, vengono confrontati due modelli di classificazione supervisionata:

- Logistic Regression
- Random Forest Classifier

Le prestazioni vengono valutate attraverso Accuracy, Precision, Recall, F1-score e matrici di confusione.

## Struttura del progetto

```text
Astronomical-Objects-Analysis/
├── data/
│   └── star_classification.csv
│
├── notebooks/
│   ├── astronomical_analysis.ipynb
│   ├── astronomical_analysis_enhanced.ipynb
│   └── template.ipynb
│
├── .gitignore
├── README.md
└── requirements.txt
```

## Installazione dei requisiti
```console
pip install -r requirements.txt

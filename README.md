# Unibo Data Mining - Fertility data set

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![made-with-latex](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)](https://code.visualstudio.com/)

Dataset e relazione per l'elaborato dell'esame di **Data Mining** presso l'Università di Bologna, Campus di Cesena, anno accademico 2018/2019.

## Modalità d'esame

L'esame consta di un elaborato individuale e di una prova orale.
L'elaborato, da concordare con il docente, potrà appartene a una delle seguenti categorie:

- **Studio e valutazione pratica di un algoritmo di DM** 

  l'obiettivo è quello di dimostrare la capacità di estendere le proprie competenze ad algoritmi non studiati a lezione.
  Si dovrà quindi scegliere uno degli algoritmo di Weka non studiato a lezione e quindi studiarlo capendone i principi, i parametri e l'applicabilità.
  Si dovrà quindi utilizzare un dataset tra quelli studiato a lezione oppure uno di quelli disponibile sul sito UCI e svolgere con esso un'analisi significativa.

- **Analisi di un dataset**

  l'obiettivo è quello di dimostrare la capacità effettuare un'analisi completa su un dominio applicativo.
  Scelto uno dei dataset disponibili sul sito UCI si dovrà svolgere un'analisi che utilizzi almeno 3 degli algoritmi studiati a lezione o comunque disponibili su Weka/R.

Tutte le attività di analisi dovranno essere svolte seguendo la metodologia CRISP-DM.
Il lavoro dovrà essere documentato mediante una relazione di almeno 5 pagine che sarà discussa durante l'orale.

## Modalità e dataset scelti

Si è scelto di procedere con la seconda modalità, effettuando un'analisi di un dataset tramite tecniche di Data Mining.

Dalla [pagina linkata](http://archive.ics.uci.edu/ml/datasets.php) dell'UCI Machine Learning Repository, è stato scelto il [Fertility Data Set](http://archive.ics.uci.edu/ml/datasets/Fertility).

Esso è composto dai dati di 100 volontari che hanno fornito un campione di seme analizzato secondo i _criteri WHO 2010_.

| **Data Set Characteristics** | **Attribute Characteristics** | **Associated Tasks**       |
|------------------------------|-------------------------------|----------------------------|
| Multivariate                 | Real                          | Classification, Regression |

| **Number of Instances** | **Number of Attributes** | **Missing Values** |
|-------------------------|--------------------------|--------------------|
| 100                     | 10                       | N/A                |

| **Area** | **Date Donated** | **Number of Web Hits** |
|----------|------------------|------------------------|
| Life     | 2013-01-17       | 183401                 |

### Informazioni sugli attributi

- Season in which the analysis was performed (-1, -0.33, 0.33, 1)
  
  1. winter
  2. spring
  3. summer
  4. fall

- Age at the time of analysis (0, 1)
  
  - 18
  - 36

- Childish diseases (ie: chicken pox, measles, mumps, polio) (0, 1)
  
  1. yes
  2. no 

- Accident or serious trauma (0, 1)

  1. yes
  2. no

- Surgical intervention (0, 1)

  1. yes
  2. no

- High fevers in the last year (-1, 0, 1)

  1. less than three months ago
  2. more than three months ago 
  3. no

- Frequency of alcohol consumption (0, 1)

  1. several times a day
  2. every day
  3. several times a week
  4. once a week
  5. hardly ever or never

- Smoking habit (-1, 0, 1)

  1. never
  2. occasional
  3. daily

- Number of hours spent sitting per day ene-16 (0, 1)

- Output (N, O) 
  
  - Diagnosis normal
  - Diagnosis altered

### Licenze e riferimenti

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)

Il codice LaTeX personalmente realizzato per la struttura del documento di relazione sono forniti sotto licenza [Apache License, Version 2.0](https://opensource.org/licenses/Apache-2.0) in accordo al file [`LICENSE`](./LICENSE) incluso in questo repository.

Il contenuto dell'opera testuale da me personalmente scritto è fornito sotto licenza [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/).

Il dataset incluso e le relative ricerche nell'ambito sono contenuti apparententi ai rispettivi proprietari.

#### Paper rilevante

> Méndez, David Gil, Jose Luis Girela, Joaquin De Juan, María José Gómez-Torres and Magnus Johnsson. “Predicting seminal quality with artificial intelligence methods.” Expert Syst. Appl. 39 (2012): 12564-12573.


# TP2 — Simulation Multi-Agent avec Mesa 3

## Description

Ce projet présente une simulation de la formation de l'opinion publique à l'aide de Python et Mesa 3.

L'objectif est d'observer comment les opinions des agents évoluent en fonction de leurs voisins.

## Technologies utilisées

- Python
- Mesa 3
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Fonctionnement

La simulation utilise une grille de 10 × 10 contenant 100 agents.

Chaque agent possède une opinion comprise entre 0 et 1.

À chaque itération, l'agent modifie son opinion en fonction de la moyenne des opinions de ses voisins.

## Expériences

Nous avons testé deux valeurs du paramètre alpha :

- Alpha = 0.1 : convergence lente.
- Alpha = 0.5 : convergence plus rapide.

Chaque simulation est exécutée pendant 50 itérations.

## Résultats

Les résultats montrent que les opinions des agents se rapprochent progressivement.

La variance diminue avec le temps, ce qui indique une convergence vers un consensus.

## Exécution du projet

Installer les dépendances :

```bash
pip install -r requirements.txt
```

Ouvrir ensuite le fichier `TP2Mesa_Simulation_MA.ipynb` dans Jupyter Notebook ou VS Code.

## Réponses aux questions

Les réponses aux huit questions du TP se trouvent à la fin du Notebook.

# Test de failles SQL Injection

## Description
Ce script Python permet de tester la présence de failles SQL Injection sur un site web. Il prend en entrée une liste de requêtes SQL depuis un fichier texte et génère des rapports au format Excel ou PDF en fonction des résultats obtenus.

## Prérequis

- Python 3.x installé
- Bibliothèques Python nécessaires : requests, openpyxl, fpdf

## Utilisation

```
python sql_injection_test.py -t [excel|pdf] -f [chemin/vers/fichier.txt]
```

- **-t** : Type de rapport à générer (excel ou pdf)
- **-f** : Chemin vers le fichier texte contenant les requêtes SQL

Exemple d'utilisation

```
python sql_injection_test.py -t excel -f queries.txt
```

## Rapports

- **rapport_sql_injection.xlsx** : Rapport au format Excel contenant les résultats des tests.
- **rapport_sql_injection.pdf** : Rapport au format PDF contenant les résultats des tests.

## Remarques

Vous pouvez remplacer les requêtes SQL du fichier texte avec celles que vous souhaitez tester.

## Auteur
GuiGui2401

## Licence
Ce projet est sous licence GNU. Consultez le fichier LICENSE pour plus de détails.
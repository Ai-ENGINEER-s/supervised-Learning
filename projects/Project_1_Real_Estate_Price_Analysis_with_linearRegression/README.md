# House Price Prediction

## Description
Ce projet vise à prédire les prix des maisons en utilisant la régression linéaire. Deux méthodes sont implémentées : une approche manuelle de régression linéaire et une version utilisant `scikit-learn` pour la normalisation des données et le modèle de régression.

## Table des matières
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Données](#données)
- [Fonctionnalités](#fonctionnalités)
- [Contributeurs](#contributeurs)
- [Licence](#licence)

## Installation
Pour exécuter ce projet, vous aurez besoin de Python 3.x et des bibliothèques suivantes :

```bash
pip install numpy pandas scikit-learn
```

## Utilisation
1. Clonez ce dépôt ou téléchargez les fichiers.
2. Placez le fichier `house-prices.csv` dans le même répertoire que les scripts.
3. Exécutez le script pour utiliser la méthode manuelle :

   ```bash
   python manual_linear_regression.py
   ```

4. Exécutez le script pour utiliser `scikit-learn` :

   ```bash
   python sklearn_linear_regression.py
   ```

## Données
Le projet utilise un fichier CSV (`house-prices.csv`) contenant les informations sur les maisons. Voici un aperçu des colonnes du fichier :

- `Home`: ID de la maison
- `Price`: Prix de la maison
- `SqFt`: Superficie en pieds carrés
- `Bedrooms`: Nombre de chambres
- `Bathrooms`: Nombre de salles de bain
- `Offers`: Nombre d'offres reçues
- `Brick`: Type de construction (Oui/Non)
- `Neighborhood`: Quartier

## Fonctionnalités
- Implémentation d'une régression linéaire manuelle.
- Utilisation de `scikit-learn` pour normaliser les données et ajuster le modèle.
- Prédictions de prix basées sur les nouvelles entrées de données.

## Contributeurs
- BARRY SANOUSSA

## Licence
Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

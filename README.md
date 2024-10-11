# TP - Régression Linéaire - Polynomiale

```markdown

## Description
Ce projet comprend plusieurs exercices sur la **régression linéaire** et **polynomiale**, en mettant en œuvre différentes méthodes d'entraînement comme **Ridge** et **Lasso**. Les fichiers sont organisés autour de deux exercices principaux, chacun abordant différentes techniques de régression.

## Structure du projet
- **Exo1/** : Contient les fichiers liés au premier exercice sur la régression linéaire simple.
  - `Corriger_Exo1.ipynb` : Notebook contenant le corrigé de l'exercice 1.
  - `EnonceExo1.txt` : L'énoncé détaillant les consignes de l'exercice 1.
  
- **Exo2/** : Contient les fichiers liés au second exercice sur la régression polynomiale avec des variantes de la méthode de régression (Ridge, Lasso, etc.).
  - `Corriger_Exo2.ipynb` : Notebook contenant le corrigé de l'exercice 2.
  - `Polynomial_Regression_Lasso.ipynb` : Implémentation de la régression polynomiale avec Lasso.
  - `Polynomial_Regression_Ridge.ipynb` : Implémentation de la régression polynomiale avec Ridge.
  - D'autres notebooks explorent différentes valeurs de paramètres pour Ridge et Lasso.

- **Prof/** : Fichiers fournis par le professeur pour aider à la compréhension et à la correction des exercices.
  - `CodeProf` et `CodeProfExpliquer` : Contiennent des exemples de code.

- **Housing.csv** : Dataset utilisé pour l'entraînement des modèles de régression dans les exercices. Il contient des données sur les prix des maisons avec plusieurs caractéristiques.

## Prérequis
Les bibliothèques suivantes doivent être installées pour exécuter les notebooks :
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Pour installer ces bibliothèques, utilisez la commande suivante :
  ``pip install numpy pandas matplotlib seaborn scikit-learn``

``` 

## Fichiers Notebooks
### Exercice 1 - Régression Linéaire Simple
L'exercice 1 implémente une régression linéaire simple pour prédire les prix des maisons en fonction d'une seule caractéristique (la superficie). Le corrigé est disponible dans le fichier `Corriger_Exo1.ipynb`. Vous pouvez exécuter ce fichier pour observer le processus de normalisation des données, l'entraînement du modèle, et l'évaluation des performances avec la **Mean Squared Error (MSE)**.

### Exercice 2 - Régression Polynomiale avec Ridge et Lasso
L'exercice 2 va plus loin en introduisant la régression polynomiale, avec plusieurs méthodes de régularisation comme **Ridge** et **Lasso** pour contrôler le surajustement. Le corrigé est disponible dans le fichier `Corriger_Exo2.ipynb`.

Les notebooks `Polynomial_Regression_Ridge.ipynb` et `Polynomial_Regression_Lasso.ipynb` montrent les implémentations respectives de la régression polynomiale avec **Ridge** et **Lasso**. D'autres fichiers comme `Polynomial_Regression_Ridge_Lasso_multiple_alpha.ipynb` explorent comment différentes valeurs des hyperparamètres affectent les performances du modèle.

## Instructions pour exécuter le code
1. Clonez ce repository sur votre machine locale :
   ```bash
   git clone https://github.com/Mehdi-Elargoubi/TP1_Regression_Lineaire.git
   ```
2. Ouvrez les notebooks `.ipynb` dans Jupyter Notebook ou JupyterLab, puis exécutez les cellules pour entraîner et évaluer les modèles de régression.

## Dataset
Le fichier `Housing.csv` contient les caractéristiques des maisons et leurs prix, qui sont utilisés pour l'entraînement des modèles. Il comprend les colonnes suivantes :
- `price` : Le prix de la maison (variable cible).
- `area` : La superficie de la maison.
- `bedrooms` : Le nombre de chambres.
- `bathrooms` : Le nombre de salles de bain.
- `stories` : Le nombre d'étages.

## Résultats
Les résultats des modèles de régression (Ridge et Lasso) sont mesurés principalement à l'aide de la **Mean Squared Error (MSE)**. Vous pouvez visualiser les relations entre les variables et observer comment les modèles se comportent en fonction des hyperparamètres de régularisation.

## License
Ce Travail est sous licence MIT. Veuillez vous référer au fichier [LICENSE](LICENSE) pour plus de détails.
```

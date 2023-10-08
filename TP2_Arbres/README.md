# TP2 - Rapports de TP2-Arbres

Ce répertoire contient le rapport de TP2 du cours HAX907X, ainsi que les éléments nécessaires pour le reproduire. Le TP est réalisés par IKHLEF Aimene.

## Reproductibilité

### Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- Python (version 3.11 ou supérieure)
- Poetry
- Quarto

Vous pouvez les installer en suivant ces liens :

- Python : [https://www.python.org/downloads/](https://www.python.org/downloads/)
- Poetry : [https://python-poetry.org/docs/#installation](https://python-poetry.org/docs/#installation)
- Quarto : [https://quarto.org/docs/get-started/](https://quarto.org/docs/get-started/)

Si vous préférez utiliser un gestionnaire de paquets différent de Poetry, assurez-vous que toutes les dépendances sont correctement installées dans votre environnement.

### Installation des dépendances

Après avoir cloné ce projet, rendez-vous dans le répertoire du TP correspondant et exécutez l'une des commandes suivantes pour installer les dépendances du projet :

Avec Poetry :

```bash
poetry install
```
Avec pip (si vous utilisez un autre gestionnaire d'environnement virtuel) :
```bash
pip install -r requirements.txt
```
## Génération du rapport
Ce projet utilise Quarto pour générer les rapports. Vous pouvez le faire en exécutant la commande suivante :

Avec Poetry :
```sh
poetry run quarto render rapport.qmd
```
Ou avec un autre gestionnaire d'environnement virtuel, assurez-vous de l'activer, puis exécutez :
```sh
quarto render rapport.qmd
```
Pour une alternative, vous pouvez également compiler directement le notebook :
```sh
quarto render rapport.ipynb --execute
```
Notez que par souci de lisibilité, les rapports ne contiennent généralement pas de code. Vous pouvez consulter le fichier .ipynb pour voir le code en action.

## Auteur :
IKHLEF Aimene

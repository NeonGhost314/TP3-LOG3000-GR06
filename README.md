**LOG3000 – Calculatrice Simple avec Flask**



## Équipe

- Équipe 6

- Membres : Alhassane Barry, Yanis Ould Mahammed



## Objectif

Fournir une calculatrice simple sur une seule page, exécutable localement, permettant d'effectuer rapidement des opérations arithmétiques sans avoir à ouvrir un tableur ou une application mobile. Le backend Flask lit l'expression que vous saisissez, applique l'opérateur sélectionné, et renvoie immédiatement le résultat sur la page web.



## Prérequis d'installation

- Python 3.9 ou version plus récente

- `pip` (inclus avec les versions récentes de Python)

- (Optionnel) `venv` ou un autre outil d'environnement virtuel

- Accès Internet pour installer les paquets depuis PyPI



## Instructions d'installation

1. Cloner le dépôt et entrer dans le répertoire du projet :

   ```bash

   git clone <your-repo-url>.git

   cd TP3-LOG3000-GR06

   ```

2. (Recommandé) Créer et activer un environnement virtuel :

   ```bash

   python -m venv .venv

   # Windows

   .venv\Scripts\activate

   # macOS/Linux

   source .venv/bin/activate

   ```

3. Installer les dépendances d'exécution (le fichier local `requirements.txt` inclut Flask) :

   ```bash

   pip install -r requirements.txt

   ```

4. Lancer le serveur de développement :

   ```bash

   python app.py

   ```

5. Ouvrir votre navigateur à l'adresse http://127.0.0.1:5000 pour utiliser l'interface de la calculatrice.

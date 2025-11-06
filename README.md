# Mini-projet Git – Conflit collaboratif (binôme)

Objectif : provoquer puis résoudre un conflit Git sur la même ligne via 2 branches distinctes.

Règles essentielles :
- 2 branches de fonctionnalité (une par personne), nommées selon les conventions vues en cours,
  et incluant votre nom/prénom dans le nom de branche.
- Conflit volontaire : modification de la même ligne dans `src/app.js`.
- Résolution manuelle avec un commit final explicite.
- Historique propre (pas de réécriture destructrice sur l’historique partagé).

# 🚀 Installation

Suivez ces étapes pour mettre en place l'environnement de développement.

### Prérequis

Avant de commencer, assurez-vous d'avoir installé les outils suivants :

* [Node.js](https://nodejs.org/) (v18 ou supérieure)
* [Git](https://git-scm.com/)
* Un gestionnaire de paquets (npm ou yarn)

### Étapes d'installation

1.  **Clonez le dépôt :**
    ```sh
    git clone [https://github.com/votre-utilisateur/votre-projet.git](https://github.com/votre-utilisateur/votre-projet.git)
    ```

2.  **Naviguez vers le dossier du projet :**
    ```sh
    cd votre-projet
    ```

3.  **Installez les dépendances :**

    *Avec npm :*
    ```sh
    npm install
    ```
    *Ou avec yarn :*
    ```sh
    yarn install
    ```

4.  **(Optionnel) Configuration de l'environnement :**
    Copiez le fichier d'environnement exemple et remplissez-le avec vos propres clés API ou configurations de base de données.
    ```sh
    cp .env.example .env
    ```

### Lancement

Une fois l'installation terminée, vous pouvez lancer le projet :

```sh
npm run dev

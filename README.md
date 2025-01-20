# Bookbook

Bookbook est une application composée d'un frontend et d'un backend, gérée dans un monorepo utilisant des sous-modules Git. Le projet permet de ...

## Structure du projet

Le projet est organisé comme suit :

- **`front/`** : Le code source du frontend, développé en React.
- **`back/`** : Le code source du backend, développé en Node.js.

### Prérequis

Avant de commencer, assurez-vous d'avoir les outils suivants installés :

- [Node.js](https://nodejs.org/) pour le frontend.
  
### Cloner le projet avec ses sous-modules

Clonez le dépôt avec les sous-modules pour récupérer à la fois le frontend et le backend :

```bash
git clone --recurse-submodules https://github.com/zowx/Bookbook.git

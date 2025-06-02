# Exoclear Discord Bot

Exoclear est un bot Discord conçu pour aider à modérer les serveurs Discord. Il offre une variété de fonctionnalités pour gérer les utilisateurs, les messages, et les salons.

## Description

Exoclear est un bot de modération pour Discord qui permet aux administrateurs et modérateurs de gérer efficacement leur serveur. Il offre des fonctionnalités pour bannir, expulser, avertir, et temporiser les utilisateurs, ainsi que pour gérer les messages et les salons.

## Fonctionnalités

- **Gestion des Utilisateurs** : Bannir, expulser, avertir, et temporiser les utilisateurs.
- **Gestion des Messages** : Supprimer des messages en masse ou individuellement.
- **Gestion des Salons** : Verrouiller et déverrouiller les salons, configurer les salons de logs.
- **Blacklist** : Ajouter, supprimer, et vérifier les utilisateurs blacklistés.
- **Normalisation des Pseudos** : Normaliser les pseudos des utilisateurs.
- **Commandes d'Information** : Afficher les informations du serveur et du bot.
- **Commandes d'Aide** : Afficher la liste des commandes disponibles.

## Prérequis

- Node.js (version 16 ou supérieure)
- Un bot Discord (créé via le [Portail Développeur Discord](https://discord.com/developers/applications))
- Les permissions nécessaires pour ajouter le bot à vos serveurs

## Installation

1. Clonez ce dépôt sur votre machine locale.
2. Installez les dépendances nécessaires en exécutant `npm install`.
3. Créez un fichier `.env` à la racine du projet et ajoutez vos variables d'environnement :

```plaintext
DISCORD_TOKEN=VOTRE_TOKEN_DE_BOT
CLIENT_ID=VOTRE_CLIENT_ID
```

4. Exécutez le bot avec la commande `node index.js`.

## Commandes

Le bot utilise des commandes slash pour interagir avec les utilisateurs. Voici les commandes disponibles :

### Commandes Générales

- `/ping` : Affiche la latence du bot.
- `/info` : Affiche les informations du serveur.
- `/help` : Affiche la liste des commandes.
- `/vote` : Affiche le lien pour voter pour le bot.
- `/botinfo` : Affiche les informations du bot.

### Commandes de Modération

- `/clear` : Supprime un nombre spécifié de messages.
- `/clear_channel` : Réinitialise complètement le salon.
- `/ban` : Bannit un utilisateur.
- `/kick` : Expulse un utilisateur.
- `/warn` : Avertit un utilisateur.
- `/mute` : Temporise un utilisateur.
- `/lock` : Verrouille ou déverrouille le salon.
- `/normalize_nickname` : Normalise le pseudo d'un utilisateur.

### Commandes d'Administration

- `/set_mod_logs` : Configure le salon de logs.
- `/set_blacklist_logs` : Configure le salon pour les logs des utilisateurs blacklistés.
- `/blacklist_add` : Ajouter un utilisateur à la blacklist.
- `/blacklist_remove` : Supprimer un utilisateur de la blacklist.
- `/blacklist_check` : Vérifie si un utilisateur est blacklisté.

## Utilisation

1. Invitez le bot sur votre serveur Discord en utilisant le lien OAuth2 généré dans le [Portail Développeur Discord](https://discord.com/developers/applications).
2. Utilisez les commandes slash pour modérer votre serveur, gérer les utilisateurs, et configurer les salons.
3. Utilisez la commande `/help` pour afficher la liste des commandes disponibles.

## Contribution

Les contributions sont les bienvenues ! Pour contribuer à ce projet, veuillez suivre ces étapes :

1. Fork ce dépôt.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`).
3. Commitez vos changements (`git commit -m 'Add some AmazingFeature'`).
4. Poussez vers la branche (`git push origin feature/AmazingFeature`).
5. Ouvrez une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

## Contact

Pour toute question ou suggestion, n'hésitez pas à ouvrir une issue ou à me contacter directement.

---

© 2025 Ludovic Rose. Tous droits réservés.

[![Donate](https://img.shields.io/badge/paypal-donate-yellow.svg?style=flat)](https://www.paypal.me/nuggan85) [![v1.1.4](http://img.shields.io/badge/zip-v1.1.4-blue.svg)](https://github.com/NuggaN85/Exoclear/archive/master.zip) [![GitHub license](https://img.shields.io/github/license/NuggaN85/Exoclear)](https://github.com/NuggaN85/Exoclear)

# TP - WIK-DPS-TP01

## Pré-requis

- Rust(cargo)
- Git

## Installation/Configuration

- Cloner le projet -> ...
- Dans un terminal configurer la variable d'environnement "PING_LISTEN_PORT" avec le port que vous souhaitez.
Exemple : ```export PING_LISTEN_PORT=7878```

- Lancer le projet dans le même terminal
```cargo run```

- Ouvrir un navigateur en tapant l'adresse "0.0.0.0" suivi du port choisi précédemment.

#### Vous aurez alors une page 404 vérifiable par le menu inspection du navigateur.

- Ensuite ajouter /ping à l'url pour obtenir la page où se trouve le Header de la requête au format JSON.

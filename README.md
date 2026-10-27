# SUGEFP_APP

Projet fil rouge de la formation aux outils de développement du SUGEFP : la chaîne de la dépense publique.

## Démarrer

    cp .env.example .env     # puis remplacer les mots de passe
    docker compose up -d
    docker compose ps

Les bases n'écoutent que sur 127.0.0.1 : on s'y connecte par tunnel SSH.

## Travail en équipe

- une branche par module : module-m1, module-m2, ...
- on propose un changement par pull request, le chef de mission fusionne dans main
- un jalon par module : jalon-M1, jalon-M2, ...
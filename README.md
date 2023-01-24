# Projet_bowling
## Etatpe à suivre
- Installer Ubuntu sur VM

- Installer Bambo et suivre guide https://confluence.atlassian.com/bamboo/installing-bamboo-on-linux-289276792.html
    - ./bin/start-bamboo.sh

- Installer java :
    - sudo apt install default-jdk
    - sudo apt install default-jre

- Lancer bamboo avec la commande ./bin/start-bamboo.sh

- Lancer le site: http://localhost:8085

- S'incrire sur Atlassian

- Générer une licence: https://my.atlassian.com/products
    - Sélectionner new licence + bamboo
    - Orga: Bamboo
    - Server ID: celui de http://localhost:8085
    - Suivre les indications
    - Choisir H2 et créer un nouveau bamboo home
    - Installer un agent
    - Créer un nouveau projet
    - Aller dans parametre -> Link repositorie
    - Choisir github
    - Gennerer un topken https://github.com/settings/tokens?type=beta

- Installer vscode

- Configurer git:
    - git config user.email "MY_NAME@example.com"
    - git config user.name "FIRST_NAME LAST_NAME"

- Cloner le projet: https://github.com/sabrinacathalo/Projet_bowling

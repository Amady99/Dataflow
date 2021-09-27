# GCP Data Storage

## Description

Projet simple pour se connecter au Google Data Storage.

## Bibliothèques utilisées

- [google-cloud-storage](https://googleapis.dev/python/storage/latest/index.html)
- [google-resumable-media](https://googleapis.dev/python/google-resumable-media/latest/index.html)
- [google-api-python-client](https://github.com/googleapis/google-api-python-client)

## Prérequis

1. docker
2. git
3. python >= 3.9 & < 4.
4. venv avec python

## Premier démarrage du projet

charger votre licence :

   - [mode console](https://cloud.google.com/storage/docs/reference/libraries?authuser=1#cloud-console)
   - ou [en CLI](https://cloud.google.com/storage/docs/reference/libraries?authuser=1#command-line)
   - puis le placer dans le fichier nommé "cle-gcp":

        ```shell
        $env:GOOGLE_APPLICATION_CREDENTIALS="./cle-gcp.json"
        ```

1. Créer l'environnement virtuel en ouvrant la console, à la racine du projet :

    ```shell
    # venv :  est un programme en Python 
    # pour créer un copie du répertoire "python" dans notre projet
    
    # .venv : répertoire de destination de notre copie. C'est lui qui contiendra
    # les dépendances installées avec "pip install"
    python -m venv .venv
    # activation de l'environnement virtuel en PowerShell
    .\.venv\Scripts\Activate.ps1
    # activation de l'environnement virtuel en cmd
    .\.venv\Scripts\activate.bat
    # activation de l'environnement virtuel en shell/bash/bsh
    shell ./.venv/Scripts/activate

    # installation des dépendances du projet depuis le fichier requirements.txt
    pip install -r .\requirements.txt
    ```

## Développement

Lancement du projet :

```shell
# activation de l'environnement virtuel en PowerShell
.\.venv\Scripts\Activate.ps1
# activation de l'environnement virtuel en cmd
.\.venv\Scripts\activate.bat
# activation de l'environnement virtuel en shell/bash/bsh
shell ./.venv/Scripts/activate
```

## Notes

- [Guide Google pour le code Python](https://google.github.io/styleguide/pyguide.html)

- Google cloud Storage
  1. [API Cloud Storage](https://cloud.google.com/storage/docs/json_api/v1)
  2. [Doc Python](https://googleapis.dev/python/storage/latest/index.html)
  3. [Code source](https://github.com/googleapis/python-storage)

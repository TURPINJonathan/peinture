# Painter Project

Découverte du framework Symfony au travers d'un projet concret.  
[Tuto Yoan Dev](https://www.youtube.com/watch?v=HViLTaLQ1AQ)

## Mise en place de Symfony

Création d'un projet Symfony
```sh
symfony new NomDuProjet --full
```
*`--full` permet d'avoir toutes les options*

## Docker

Création de la base de données

```sh
symfony console make:docker:database
```
Sous Windows:
[Installer docker](https://docs.docker.com/desktop/windows/install/)  
[Mise à jour du noyaux Linux](https://docs.microsoft.com/fr-fr/windows/wsl/install-manual#step-4---download-the-linux-kernel-update-package)

Après confinguration du fichier `docker-compose.yml`, on peut effectuer les commandes suivantes:
```sh
docker-compose up -d
symfony serve -d
```

# Wordpress-Plugin

Dépôt conteneur : chaque projet de plugin WordPress créé ou personnalisé
vit dans son propre dossier ci-dessous, chacun étant un dépôt Git à part
entière (référencé ici en tant que sous-module — cliquer sur le dossier
affiche son contenu directement sur GitHub).

| Dossier | Dépôt |
|---|---|
| [`wodaabe/`](https://github.com/patntiwa/wodaabe-reservation-system) | Plugin de réservation Wodaabe Stays |
| [`patineb-suite/`](https://github.com/patntiwa/patineb-suite) | Suite modulaire (Équipe, FAQ, Réalisations, Avis) filtrable par pôle |

## Ajouter un nouveau projet

```
git submodule add <url-du-nouveau-depot> <nom-du-dossier>
git commit -m "Ajoute <nom-du-dossier>"
git push
```

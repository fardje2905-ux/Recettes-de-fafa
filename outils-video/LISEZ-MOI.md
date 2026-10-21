# NiftyVid pour Les recettes de Fafa

- **[Copie de secours figee](./niftyvid-sauvegarde/)** : code original conserve au commit `63ea9e446aa0cf0fea43fa90b4942afd3f4dcbdd`. Ce dossier n'est jamais synchronise.
- **[Copie evolutive](./niftyvid-evolution/)** : code officiel synchronise chaque lundi a 06h23 UTC (07h23 en hiver et 08h23 en ete en France), ou manuellement dans GitHub Actions avec le workflow « Sauvegarde et evolution NiftyVid Fafa ».

[Ouvrir l'application originale NiftyVid](https://igorcsis.github.io/nifty-vid/)

Source officielle : https://github.com/IgorCSIS/nifty-vid
Auteur : Igor Lima. Licence MIT conservee dans les deux copies.

## Ce qui est sauvegarde
Ces dossiers conservent le code source du site et du Cloudflare Worker.
Ils ne sauvegardent ni le service de calcul IA, ni les images, ni les videos produites.
Telecharger et conserver les MP4 separement.

## Utiliser une installation independante
Les dossiers GitHub ne sont pas des applications deja publiees.
Pour une installation independante, compiler le site Astro, le publier et deployer son propre Cloudflare Worker, puis configurer PUBLIC_WORKER_URL.
Les instructions du projet sont dans le README de chaque copie.
Le calcul IA depend d'un Space Hugging Face public, dont la disponibilite peut changer.

L'application de recettes existante et ses fichiers restent a la racine du depot.
Pour conserver des adaptations personnelles, les faire dans un autre dossier que niftyvid-evolution, qui est un miroir de la source.

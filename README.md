﻿# 🌌 AtmosphereVanillaFetcher

Petit programme permettant de télécharger un pack des toutes dernières mises à jours d'Atmosphere avec quelques homebrews en plus.

# 🤔 Comment utiliser ce programme ?

L'utilisation de ce programme est très simple.

Afin d'éviter la limite de requêtes de l'API GitHub, vous devez utiliser votre token de compte afin de pouvoir utiliser ce programme. (Une version sans token arrivera peut-être dans le futur) 

## 🐱 Obtenir mon token GitHub

1. Connectez-vous à votre compte GitHub

2. Cliquez sur votre photo de profil en haut à droite, et cliquez sur **Settings**

3. Allez dans le menu **Developper settings**, puis **Personnal access tokens**

4. Cliquez sur **Generate new tokens**

5. Entrez une note pour vous rappeler de l'utilité du token, vous n'avez besoin d'aucune permission particulière, il n'est donc pas nécessaire de toucher aux permissions

6. Cliquez sur "Generate token"

7. Copiez ce token à un endroit où vous pourrez le retrouver afin de pouvoir l'utiliser pour le programme

Vous avez désormais votre token, vous pouvez passer à la suite !

## 📚 Paramétrer et utiliser le programme

1. Créez un fichier **.env** à la racine du programme, avec le contenu suivant:
```
GITHUB_TOKEN=votre_token_ici
```
(Remplacez évidemment **votre_token_ici** par votre token GitHub.)

2. Ouvrez le programme, si tout se passe bien, le programme devrait télécharger les fichiers, les organiser et les compresser dans un fichier nommé **pack.zip** qui sera présent à la racine du programme.

Si vous avez le moindre problème, merci de le signaler ici: https://github.com/Lunyyx/AtmosphereVanillaFetcher/issues

# Music-bot
Un code complet à télécharger pour un robot musical. Utilisation d'un module (discord-player) 🎧

Vous cherchez un code pour un robot musical? Ce code entièrement open source est fait pour votre projet!

Si vous avez besoin d'aide avec ce projet, pour obtenir de l'aide plus rapidement, vous pouvez rejoindre le serveur d'aide en cliquant simplement sur [ici] (https://discord.gg/pqJWBB5YEs).

### ⚡ Installation

Eh bien, commençons par télécharger le code.
Allez dans le dossier `config` puis le fichier` bot.js`.
Pour que le bot puisse démarrer, veuillez compléter le fichier avec vos informations d'identification comme suit:

- Pour les emojis

`` `js
emojis: {
    off: ': x:',
    erreur: ': avertissement:',
    file d'attente: ': bar_chart:',
    musique: ': musical_note:',
    succès: ': white_check_mark:',
}
''

- Pour la configuration

`` `js
discorde: {
    jeton: 'TOKEN',
    préfixe: 'PREFIX',
    activité: 'ACTIVITÉ',
}
''

- `token`, le token du bot disponible dans la section [Discord Developers] (https://discordapp.com/developers/applications).
- `prefix`, le préfixe qui sera défini pour utiliser le bot.
- «activité», l'activité du bot.

Dans la console, tapez «npm install» pour installer toutes les dépendances.

- Pour démarrer le bot:

''
#With Node
noeud index.js
npm start #Indiqué dans package.json

# Avec pm2
pm2 start index.js --name "MusicBot"
''

Tout ce que vous avez à faire est d'allumer votre bot!

### 🎵 Commandes musicales

''
lire <nom / URL>, écouter de la musique sur un canal vocal.
recherchez <nom>, ouvrez un panneau pour choisir une musique, puis écoutez-la.
mettre en pause, mettre en pause la musique actuelle.
reprendre, remet la musique actuelle en marche.
file d'attente, voir les chansons suivantes.
clear-queue, supprimez la musique de la file d'attente.
shuffle, pour mélanger la file d'attente.
nowplaying, voir la musique en cours.
boucle, pour activer ou désactiver la fonction de répétition.
volume <1 - 100>, changez le volume.
sauter, passer à la musique suivante.
arrêtez, arrêtez toute musique.
filtre <filtre>, ajouter / supprimer un filtre.
w-filters, voir les filtres.
''

### 💡 Commandes générales

''
ping, voyez la latence du bot.
help, consultez la liste des commandes disponibles.
debug, voir le nombre de connexions vocales.
''

### 🏓 Utilitaires (pour changer le code)

Retrouvez toutes les fonctions disponibles sur le code officiel [ici] (https://github.com/Androz2091/discord-player).

Ceci est utilisé avec [discord.js] (https://www.npmjs.com/package/discord.js) et [discord-player] (https://www.npmjs.com/package/discord-player).

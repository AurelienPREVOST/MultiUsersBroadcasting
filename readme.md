## Projet test multi-utilisateur

Dans ce projet nous utiliserons socket.io qui va permettre de faire un backend commun capable de broadcasté des informations aux différents clients qui seront en train de l'utiliser.

Dans le cas present il s'agit simplement de points representant un joueur qui peuvent se deplacer via les touches ZQSD et avec lequel nous pouvons tirer des projectiles.

Pour lancer le projet après clone 

```
nodemon backend.js
```

puis ouvrir plusieurs fenetre de navigation sur le port 3000.


Ce projet permet surtout et avant tout de se familiarisé avec socket.io. Des applications collaboratives peuvent être créé grâce à socket.

Le projet prend egalement en charge des correctifs permettant que le rendu coté front soit lié et reconcilié avec le rendu coté serveur afin que la latence ne nuisent pas à l'experience utilisateurs.

___________________________________

For more informations, thanks to Chris :

This is a starter project for the [Chris Courses Online Multiplayer Game Tutorial](https://www.youtube.com/watch?v=Wcvqnx14cZA) available on YouTube.

To get started, download this repo and double click `index.html` to see the single-player game we'll base our multiplayer-game off of.

___________________________________

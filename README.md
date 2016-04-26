# VideoPlayer

### Démonstration
Voir le résultat: http://jclerc.github.io/VideoPlayer/

### Fonctionnalités
- JS natif, orienté objet par prototype
- Ambient light en fonction des couleurs de la vidéo
- Prévisualisation des miniatures en JS
- Raccourcis clavier
- CSS responsive

### Utilisation
Créez une instance:
```
var player = new VideoPlayer('.player');
```
Et si vous n'avez qu'un player sur la même page:
```
player.focus();         // Focus le player (pour les raccourcis clavier)
player.enableAmbient(); // Active l'ambient light en fond
player.useHash();       // Utilise le #hash pour commencer directement à un endroit précis
```

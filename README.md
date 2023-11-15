# Sonalux
# Prototype de visuel interactif (Vincent)
## Exploration de touch designer
- Ce patch touchdesigner qui utilise du noise et du feedback pour créer un visuels qui se génère et réagie a de l'audio
  [![thumbnail video generatif audio react](https://img.youtube.com/vi/jEneayx-0J8/0.jpg)](https://youtu.be/jEneayx-0J8)
- Ce patch Touchdesigner est ma premiere expérimentation avec les particules. Dans cette example les particules sont seulement affecté par le temps et aucun composant interactif externe.
- [![Thumbnail video particle premier esquisse](https://img.youtube.com/vi/FuGjOUcTBh4/0.jpg)](https://youtu.be/FuGjOUcTBh4)
## Exploration de la kinect
J'ai exploré deux méthodes pour utilisé la kinect dans TouchDesigner.
- la première est avec le flux "vidéo" de la kinect. je met des guillemet, car le flux video n'est pas nécéssairement une caméra rgb. Elle peut aussi être une caméra de depth, donc elle permet de séparer le flux vidéo en trois plane(foreground, middleground, background) pour cette méthode on doit utiliser des opérateurs de textures dans ToucDesigner (TOP)
![images des top nécéssaire pour la kinect en top](/images/kinect_top.JPG)
- la deuxième est avec les données de la kinect. C'est données ressemble à des messages OSC. Donc on recoit tous les point du squelettes/rigs et leur position en x,y,z de chaque intéracteurs (jusqu'à 4 personnes). Pour cette méthode on doit utiliser des Channel opérator (Chop) ce type d'opérateur se traitre un peut comme du son.
![images de l'opérateur chop de la kinect](/images/kinect_chop-1.jpg)
![images de l'opérateur chop de la kinect](/images/kinect_chop-2.jpg)
![images de l'opérateur chop de la kinect](/images/kinect_chop_rig.jpg)
## Prototype
### Prototype avec le flux "video" de la kinect (top)
[![Thumbnail video Kinect et touchdesigner](https://img.youtube.com/vi/ES2N6omMyHc/0.jpg)](https://youtu.be/ES2N6omMyHc)
### Prototype avec le flux de donné de la kinect (chop)
[![Thumbnail video Kinect et touchdesigner](https://img.youtube.com/vi/ezuy2fvP3yk/0.jpg)](https://youtu.be/ezuy2fvP3yk)
### Prototype déploiement avec un projecteur et une kinect
[![thumbnail video déploiement](https://img.youtube.com/vi/e1h0qx9sK4E/0.jpg)](https://youtu.be/e1h0qx9sK4E)

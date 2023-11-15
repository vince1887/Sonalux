# Sonalux
# Prototype de visuel interactif
## Exploration de touch designer
## Exploration de la kinect
J'ai exploré deux méthodes pour utilisé la kinect dans TouchDesigner.
- la première est avec le flux "vidéo" de la kinect. je met des guillemet, car le flux video n'est pas nécéssairement une caméra rgb. Elle peut aussi être une caméra de depth, donc elle permet de séparer le flux vidéo en trois plane(foreground, middleground, background) pour cette méthode on doit utiliser des opérateurs de textures dans ToucDesigner (TOP)
![images des top nécéssaire pour la kinect en top](/images/kinect_top.JPG)
- la deuxième est avec les données de la kinect. C'est données ressemble à des messages OSC. Donc on recoit tous les point du squelettes/rigs et leur position en x,y,z de chaque intéracteurs (jusqu'à 4 personnes). Pour cette méthode on doit utiliser des Channel opérator (Chop) ce type d'opérateur se traitre un peut comme du son.
![images de l'opérateur chop de la kinect](/images/kinect_chop-1.JPG)
![images de l'opérateur chop de la kinect](/images/kinect_chop-2.JPG)
![images de l'opérateur chop de la kinect](/images/kinect_chop_rig.JPG)
## Prototype
### Prototype avec le flux "video" de la kinect (top)
[![Thumbnail video Kinect et touchdesigner](https://img.youtube.com/vi/ES2N6omMyHc/0.jpg)](https://youtu.be/ES2N6omMyHc)
### Prototype avec le flux de donné de la kinect (chop)
[![Thumbnail video Kinect et touchdesigner](https://img.youtube.com/vi/ezuy2fvP3yk/0.jpg)](https://youtu.be/ezuy2fvP3yk)

# FCSC 2024 Midas Touch


La société du challenge ```Soupe MISO``` a entendu parler d’une fuite de ses secrets affichés sur l’écran de contrôle… Qu’à cela ne tienne, ils ont décidé de mettre en place un contrôle d’accès dans la salle de commandes afin de forcer une identification via PIN avant l’envoi de commandes.

Pour ce faire, ils ont ajouté un touch screen capacitif de type [FT6206](https://cdn-shop.adafruit.com/datasheets/FT6x06_AN_public_ver0.1.3.pdf) au dessus du ILI9341 afin de faire saisir le PIN sur un PINpad virtuel (affiché sur l’écran TFT avec un layout randomisé pour un maximum de sécurité). Grâce à des fuites de spécifications, vous apprenez que la bibliothèque [https://github.com/adafruit/Adafruit_FT6206_Library](https://github.com/adafruit/Adafruit_FT6206_Library) est utilisée pour gérer le touch screen. Vous savez aussi que la saisie du PIN se finit par un “OK”.

Comme précédemment, vous avez accès aux fils reliant la board pilotant l’ILI9341 et le FT6206, avec cette fois-ci une distinction de couleur entre les fils vous permettant d’avoir deux captures distinctes avec deux analyseurs logiques. Saurez-vous retrouver le PIN secret permettant de continuer à accéder aux secrets de l’entreprise ?

**Note :** le format du flag est ```FCSC{PIN}``` où ```PIN``` est le ```PIN``` secret.

![midas_touch.png](midas_touch.png)




Fichiers :
- [midas-touch.tar.gz](midas-touch.tar.gz)



Auteur : rbe

Origine : [Midas Touch](https://hackropole.fr/fr/challenges/hardware/fcsc2024-hardware-midas-touch/)


-----------


## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-hardware-midas-touch.git

> cd fcsc2024-hardware-midas-touch


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2024-hardware-midas-touch/
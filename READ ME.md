FR

Preset:

Pour le plugin https://github.com/univrsal/input-overlay
Clavier AZERTY COMPLET testé 

![[azerty-pixel-with-keypad 1.png]]
Souris cubique
![[mouse_cubique.png]]


Basé sur le preset: 
https://github.com/univrsal/input-overlay/tree/master/presets/qwerty-pixel-with-keypad


MODIFICATION DES FICHIERS JSON

Selon les dispositions de clavier les touches spéciaux peuvent être appelées avec un code différent dans le fichier JSON.

Pour trouver, ce code j'utilise une autre image tableau et trois autres fichiers JSON.
![[nombre transparent 0_255.png]]
le tableau a été réalisé sur libre office Calc, la hauteur des lignes est standard et la largeur est réduite à l'affichage de trois chiffres par case 000 

Lors d'un appuis sur la touche son code apparait dans la prévisualisation OBS, 

on ajoute +0 au fichier buttons 0_255
on ajoute +3584 au fichier buttons_E_3584 (caractères spéciaux)
on ajoute +35344 au fichier buttons_E0_57344 (caractères spéciaux)

et on obtient le code de la touche à ajouté au fichier JSON.

Les fichier on été générés avec ChatGPT le prompt est dans un fichier texte.


![Capture_résultat.png](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/Capture_r%C3%A9sultat.png)


FR  12/01/2025   

#Preset AZERTY pour plugin [Input Overlay V5.0.5](https://obsproject.com/forum/resources/input-overlay.552/) by invrsal

Prérequis: 

Logiciel [Télécharger OBS](https://obsproject.com/download) et Fichier plugin [Télécharger Input Overlay V5.0.6](https://github.com/univrsal/input-overlay/releases/tag/5.0.6)

[CLAVIER AZERTY](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/tree/main/azerty-pixel-with-keypad) 
  - Basé sur [qwerty-pixel-with-keypad](https://github.com/univrsal/input-overlay/tree/master/presets/qwerty-pixel-with-keypad)


![azerty-pixel-with-keypad 1.png](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/azerty-pixel-with-keypad/azerty-pixel-with-keypad.png)


[SOURIS CUBIQUE](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/tree/main/mouse_cubique)
  - Basé sur [mouse](https://github.com/univrsal/input-overlay/tree/master/presets/mouse)


![mouse_cubique.png](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/mouse_cubique/mouse_cubique.png)




---

#MODIFICATION DES FICHIERS JSON

Selon les dispositions de clavier le paramètre "code": X  dans le fichier .JSON peut varier , 
  - Pour trouver ce code j'utilise un [tableau image de 0_255 et trois autres fichiers JSON](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/tree/main/Detect_input_overlay_Keycode).


![KEY_detect 0_255.png](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/Detect_input_overlay_Keycode/KEY_detect%200_255.png)
le tableau a été réalisé sur [Libre Office Calc](https://www.libreoffice.org/), la hauteur des lignes est standard et la largeur est réduite à trois chiffres par case ex: 000 

Lors d'un appuis sur la touche son code apparait dans la prévisualisation OBS, 

on ajoute +0 au fichier [buttons 0_255](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/Detect_input_overlay_Keycode/buttons%200_255.json)


on ajoute +3584 au fichier [buttons_E_3584](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/Detect_input_overlay_Keycode/buttons_E_3584.json) (caractères spéciaux)


on ajoute +35344 au fichier [buttons_E0_57344](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/Detect_input_overlay_Keycode/buttons_E0_57344.json) (caractères spéciaux)

et on obtient le code de la touche à ajouter au fichier JSON.

![extrait de code](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/extrait_JSON.png)

Les fichiers ont été générés avec ChatGPT, [le prompt est dans un fichier texte](https://github.com/Benoit-cod/OBS-input-overlay-preset-AZERTY/blob/main/Detect_input_overlay_Keycode/Prompt%20chatGPT%20code%20detection%20touche.txt).

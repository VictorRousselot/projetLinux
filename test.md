##Mise en route d'un OS Linux

**Le processus de démarrage d'un système d'exploitation Linux fonctionne selon plusieurs étapes telles que :**
* Lecture du BIOS
* Lecture du MBR ou Master Boot Record
* Lancement du chargeur Grub ou Lilo
* Chargement du noyau Linux en mémoire avec chargement de certains drivers via initrd
* Lancement du processus init

###Le BIOS

Le BIOS ou en anglais *Basic Input Output System* (système d'entrée sortie de base) est un composant essentiel à tout PC, il se trouve généralement dans une mémoire morte ou ROM qui est directement implantée sur la carte mère du PC. Il est associé à une mémoire sauvegardée par une petite pile bouton sur la carte mère (le “setup” qui est la sauvegarde de la configuration).

Si votre PC ne démarre pas (ou ne boot pas) c'est à cause du BIOS et de sa configuration (le setup). On peut accéder au setup et le modifier en pressant une touche dès la mise sous tension du PC. Selon les fabricants, cette touche est Suppr, F2, F10 … (la touche à utiliser est souvent très brièvement affichée au tout début du démarrage).
Mais quelle est donc sa fonction ?

Le BIOS teste le matériel et y applique les réglages mémorisés dans le setup, tout en s'assurant qu'il n'existe pas de dis-fonctionnement matériel et que tout est présent dans la machine, mémoire CPU principalement. Ensuite il regarde la présence des périphériques nécessaires au boot : lecteur de disquette, cd rom, dvd rom, clef usb, mais surtout disque dur. Si vous avez installé un système d'exploitation Linux ou Windows, le BIOS est normalement configuré pour activer le MBR de celui ci, les étapes du démarrage peuvent alors commencer….




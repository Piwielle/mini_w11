## Vérifier la compatibilité
Avant de pouvoir commencer l'installation et l'utilisation de Windows 11, il faut s'assurer de la compatibilité du PC avec Windows 11.

Pour vérifier ça, on peut utiliser [l'outil de Microsoft](https://aka.ms/GetPCHealthCheckApp). Il précise les détails de ce qui est compatible ou pas.

Support vidéo : [<img src="https://i.imgur.com/cRUau5i.png" height="20" width="30" alt="Logo YouTube" class="img-logo-ytb"> TPM ? Secure boot ? W11 ? Valorant ? Explications.](https://youtu.be/arWlC6HZpTY)

## Créer une clé USB d'installation
La première étape, c'est de créer une clé USB d'installation de Windows, qu'on pourra utiliser pour formater un PC et réinstaller Windows proprement.

Il faut pour ça **une clé USB de 8 Go ou plus** et **accès à un PC sous Windows**.

- Télécharger l'outil de la catégorie "Création d'un support d'installation de Windows 11" sur [le site de Microsoft.](https://www.microsoft.com/fr-fr/software-download/windows11)
- Lancer l'outil, choisir ses paramètres et sa clé, puis lancer le processus.

La clé va ensuite se créer toute seule. L'opération peut prendre du temps selon la connexion, la clé USB, et le PC.

Support vidéo : [<img src="https://i.imgur.com/cRUau5i.png" height="20" width="30" alt="Logo YouTube" class="img-logo-ytb"> Créer une clé USB d'installation](https://www.youtube.com/watch?v=nidskw_JslQ)

## Installer Windows

La clé étant créée, on va pouvoir l'utiliser pour formater le PC et installer une version fraîche de Windows.

Pour faire ça: 
- Mettre la clé dans un des ports USB, si sur un PC fixe préférablement directement sur un des ports à l'arrière, directement sur la carte mère.
- Démarrer le PC, et spammer la touche <kbd>F11</kbd> pendant le démarrage (des fois <kbd>F8</kbd> ou <kbd>F12</kbd>, selon la marque de la carte mère).
- Choisir la clé USB dans le menu de démarrage qui s'ouvre (en UEFI s'il y en a plusieurs).
- Se laisser guider par l'installateur de Windows.

> **Warning**
> 
> **Attention ! Lors du choix du lecteur sur lequel installer Windows, il faut être très attentif, c'est ici que vous allez formater vos disques. Si vous n'êtes pas très attentifs, vous allez perdre des données que vous vouliez garder !**

- Chaque SSD ou disque dur dans le PC correspond à un lecteur sur l'interface.
- Déterminer sur quel disque (lecteur) l'installation de Windows sera faite (on pourra s'aider de la taille pour les reconnaître).
- Supprimer toutes les partitions de ce que disque.
- Sélectionner l'espace non alloué représentant le disque, puis simplement appuyer sur suivant.

On pourra ensuite attendre la copie et l'installation de Windows. Pendant le compte à rebours de 10 secondes avant de redémarrer le PC, pensez à retirer la clé USB du PC. Ca évitera de redémarrer encore sur la clé et de recommencer l'installation en boucle.

Ensuite, on passe au réglage des paramètres initiaux avant de pouvoir accéder à Windows. On peut se laisser guider par l'installateur. Dites non à tout ce qu'il propose (ex. localisation, personnalisation des publicités..) et tout ira bien. Pour utiliser un compte local au lieu du compte Microsoft, on peut simplement entrer l'adresse mail "a" et le mot de passe "a". Après une erreur, on pourra continuer avec un compte local. Si vous choisissez d'utiliser un compte Microsoft (ce qui est très bien), faites attention de bien dire non à l'option pour sauvegarder vos dossiers sur OneDrive.

Support vidéo : [<img src="https://i.imgur.com/cRUau5i.png" height="20" width="30" alt="Logo YouTube" class="img-logo-ytb"> Installer Windows](https://youtu.be/5bPSazjZdSA)

## Installer ses pilotes

Une fois Windows installé et démarré, on va pouvoir télécharger et installer les pilotes (drivers). 

- On commence par se rendre sur le site de la carte mère, dans la catégorie support (si le modèle exact de la carte mère est inconnu, on peut utiliser [UserDiag](https://userdiag.com/) pour le trouver). On télécharge ensuite tous les pilotes disponibles pour la carte mère.

- On fera quand même attention d'éviter les "utilitaires", qui ne sont pas vraiment des pilotes, mais plutôt des logiciels qui peuvent permettre de contrôler des choses diverses sur le PC, mais qui sont souvent mal faits et très gourmands en ressources.

- On passe également sur le site d'[Nvidia](https://www.nvidia.com/Download/index.aspx) ou [AMD](https://www.amd.com/support) pour la carte graphique et sur les sites des fabricants pour les pilotes spécifiques à du matériel particulier (logiciel de clavier, pilote de carte son, etc).

Une fois tous les pilotes téléchargés, on peut les dézipper et les installer, un par un. Dans la majorité des cas on pourra se contenter de ne redémarrer qu'une seule fois à la fin, mais si on constate des erreurs étranges, redémarrer après chaque pilote peut aider.

Support vidéo : [<img src="https://i.imgur.com/cRUau5i.png" height="20" width="30" alt="Logo YouTube" class="img-logo-ytb"> Installer ses pilotes](https://youtu.be/olOuIQA1HzY)


## Bibliothèques C++

Les bibliothèques C++ (traduction libre) sont nécessaires à beaucoup d'applications et de jeux pour fonctionner. Certains vont les installer automatiquement, d'autres vont vous faire des erreurs et ne pas vous laisser les installer/lancer (souvent avec un message d'erreur qui aide pas trop). On va donc tout installer maintenant, pour être tranquille.

- On télécharge le pack de bibliothèques C++ sur [le site de TechPowerup](https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/).
- On extrait l'archive téléchargée.
- On lance **install_all** **en tant qu'administrateur**.

Support vidéo : [<img src="https://i.imgur.com/cRUau5i.png" height="20" width="30" alt="Logo YouTube" class="img-logo-ytb"> Bibliothèques C++](https://youtu.be/Ck-65Ku7ohg)

## Les bonnes pratiques

L'installation de Windows est terminée, mais avant de vous laisser, on va parler des bonnes pratiques et des choses à faire sur le PC pour essayer de le garder propre le plus longtemps possible et éviter les problèmes.

- Eviter les optimisations. Malgré les promesses de gain de performances, d'input lag ou de stabilité, dans 99% des cas, il s'agit de bêtises qui vont vous flinguer Windows complètement, ou vous faire perdre des fonctionnalités pour ne rien gagner. Si ça vous amuse de bidouiller et que ça vous dérange pas de réinstaller Windows tous les mois, vous pouvez tenter l'aventure. Sauvegardez vos données, et soyez prêts à perdre du temps.
- Eviter les logiciels de nettoyage. Les Ccleaner, Iobit SystemCare, Glary utilities, DriversCloud, DriverBooster, etc etc, c'est des saloperies. Ils vendent du vent et ne vont rien faire de bien sur votre PC. Pour nettoyer les fichiers, le nettoyage de disque intégré à Windows est efficace et moins dangereux que ces outils.
- Garder son PC à jour. Ca inclut Windows, les applications, les jeux et tout ce qui est sur le PC. N'allez pas forcément installer toutes les mises à jour de tout dès le premier jour, mais une fois qu'une mise à jour de quelque chose a une semaine, vous pouvez l'installer sans problème.
- Essayez d'installer le moins d'applications possible. Pour garder un PC propre, installer une application seulement si vous en avez vraiment besoin. Dans la mesure du possible, utilisez les versions portables des applications, qui peuvent laisser moins de bordel sur le PC.
- Eviter les cracks. Essayez d'utiliser des alternatives gratuites, c'est souvent possible et bien moins dangereux. Le site [AlternativeTo](https://alternativeto.net/) peut vous aider à trouver des alternatives à un logiciel.
- Installez [uBlock Origin](https://ublockorigin.com/). Quel que soit votre navigateur, c'est essentiel d'avoir un bloqueur de pub efficace pour être tranquille sur internet. uBlock Origin est de loin le meilleur bloqueur de pub, et si vous en utilisez un autre, il est temps de le désinstaller et de changer.

Support vidéo : [<img src="https://i.imgur.com/cRUau5i.png" height="20" width="30" alt="Logo YouTube" class="img-logo-ytb"> Les bonnes pratiques](https://youtu.be/SEdYm2gLgYk)



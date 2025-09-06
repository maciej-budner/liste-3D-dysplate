# liste-3D-dysplate
une application android qui donnera une liste des tableau qui peuvent etre imprimer on 3D et dans la quelle on poura choisir se que on veut. Une sorte de marquet place

# Warning
Cette application est un simple test de la fonctionnalité Realm dans Android Studio.
Elle me sert également à voir combien d’images je peux ajouter avant que l’application ne commence à ramer, à prendre du temps au chargement, ou encore à tester la mise en place d’un panier basique.

Toutes les images proviennent du site [Display](https://displate.com), issues de ma liste de souhaits ou des screen shot que j'ai pris de plusieurs jeux.

Si quelqu’un s’amuse à générer un APK à partir de ce projet et à le publier, je n’en serai pas responsable.

# Visuel de l'application et son fonctionnement

<img src="screen/Screenshot_20250906_015038_list 3d Display.jpg" width="200" height="400"/>

Voilà à quoi cela ressemble. On peut voir qu'en haut à droite, on aperçoit le nombre d'images dans notre panier et lorsque l'on clique sur une des images :

<img src="screen/Screenshot_20250906_015042_list 3d Display.jpg" width="200" height="400"/>

Le compteur s'incrémente.
Si on appuie sur le panier, cela nous redirige vers une page avec les images que l'on a choisies :

<img src="screen/Screenshot_20250906_015052_list 3d Display.jpg" width="200" height="400"/>

On peut voir qu'en bas, le bouton indique qu'il faut un nom dans l'EditText en haut de la page. Tant qu'aucune lettre n'est saisie, le bouton reste désactivé.
Mais si on le complète :

<img src="screen/Screenshot_20250906_015101_list 3d Display.jpg" width="200" height="400"/>

Le bouton devient "Valider" et on peut cliquer dessus. Bien sûr, on peut cliquer sur une image pour la retirer du panier. Si on clique sur "Valider", le PDF avec toutes les images choisies se télécharge automatiquement dans le répertoire Downloads :

<img src="screen/Screenshot_20250906_015123_Write on PDF.jpg" width="200" height="400"/>

# Futures améliorations

Corriger le bug où l'on ne peut supprimer qu'une seule image à la fois : pour en supprimer une autre, il faut quitter la page et revenir.

Si l'on a deux images identiques, seule une s'affiche car Realm supprime les doublons. Deux solutions : afficher un multiplicateur ou afficher les doublons.

Tester les limites pour voir combien d'images on peut ajouter avant que l'application freeze ou lag.

Au lieu de télécharger le PDF, peut-être permettre l'envoi par mail, Discord, Instagram ou bloc-notes.

Traduire l'application en plusieurs langues selon la langue du téléphone, en gardant l'anglais comme langue universelle.

Revoir l'esthétique de l'application et du PDF.

Refusé de valider la commande si il n'y a pas de commande dans le cadis.

Monter des vidéos avec blender
------------------------------------------
[Original](http://github.com/tutoblender/)

[Blender](http://blender.org) n'est pas uniquement un programme de 3D, c'est aussi un logiciel de montage vidéo.      
Nous allons apprendre à l'utiliser pour faire un montage simple.     
 
* Télécharger blender : http://blender.org
* Vidéo : ******TOADD******

# Préparer l'interface
Il nous faut paramétrer l'interface de blender.     
Afin de faire simple nous allons télécharger une session déjà prète et la mettre par défaut.    

* Télécharger ce fichier : http://vse.madnerd.org
* Cliquez sur **minimal_vse.blend**
* Sauvegarder la session par défaut : **CTRL-U** puis **ENTREE**

A chaque lancement de blender, l'interface restera sur **Video Editing** (Montage vidéo)     

Regardons un peu l'interface.   

![Blender VSE](https://github.com/tutoblender/blob/master/doc/interface.jpg)
* En **haut**, nous avons le **rendu vidéo** (video preview)
* En **bas**, nous avons **l'éditeur de séquence** (Sequence editor)
* A **droite**, nous avons les paramètres du projet

# Ajouter une séquence vidéo

![Sequence Editor](https://github.com/tutoblender/blob/master/doc/sequence.jpg)
Pour ajouter une séquence vidéo/audio, il suffit de **glisser** un fichier dans le séquenceur (Sequence Editor)   
Deux strips seront alors crées:   
* En **bleu foncé** : Vidéo
* En **cyan** : Audio 

# Lire la vidéo
* Touche **ALT-A** : Lancer la vidéo
* Touche **P** : Définir la zone de prévisualisation

# Couper la séquence
![Cut sequence](https://github.com/tutoblender/blob/master/doc/cut.jpg)
* Clic **droit** : Sélectionner la séquence
* Clic **gauche**: Déplacer la **barre verte**
* Touche **K** : Couper la séquence en deux.

# Déplacer une séquence 
* Clic **droit** : Sélectionner la séquence
* Touche **G** : Déplacer la séquence
* Touche **B** : Sélectionner plusieurs séquences 

# Sauvegarder votre film
Une fois que vous avez monté votre vidéo, il ne reste plus qu'à faire le rendu.   
Pensez à sauvegarder votre projet (**File/Save As** en **haut**).    
Il est conseillé de sauver le fichier .blend (projet) dans le même dossier que les vidéos.

![Render movie](https://github.com/tutoblender/blob/master/doc/render.jpg)
## Définir la durée 
* Avec la **barre verte** déplacer vous au **début** / **fin** de la vidéo
* Notez la frame du  **début** / **fin** de la vidéo (**en bas au milieu**)
* Recopier ces valeurs à **droite** dans **Frame Range** (Start Frame/End Frame)

## Enregistrer
![Video save path](https://github.com/tutoblender/blob/master/doc/save.jpg)
* Vérifier **à droite** dans **Output** le chemin où sera sauvegardé la vidéo    
* Cliquer sur **Animation** 
* Une vidéo sera sauvegardés dans **c:\videos**    

Par défaut, le séquenceur sera remplacé par un lecteur vidéo.      
Pour remettre la prévisualisation, cliquer sur l'icone **en bas à gauche** en forme d'image et mettez **Video Sequence Editor**     
![VSE Icon](https://github.com/tutoblender/blob/master/doc/vseicon.jpg)    


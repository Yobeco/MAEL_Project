

![](./readme_assets/Logo-MAEL-alpha-H.svg)

**Auteur** : Yonnel Bécognée, instituteur

:fr: Présentation du projet MAEL

:gb: Presentation of the MAEL project

# A- Histoire du projet :book:

## 1- Génèse :milky_way:

Je suis professeur des écoles dans une école française à Managua (Nicaragua). J'enseigne en maternelle ou en élémentaire selon les années. Tous mes élèves ne parlent pas (encore) français, mais surtout, certains élèves n'ont aucun parent francophone à la maison pour les aider.

Étant autodidacte en programmation, j'ai eu l'idée de mettre du texte brut dans un code QR afin de le faire scanner puis oraliser par une petite application créée avec [Mit App Inventor](https://appinventor.mit.edu/) (Scratch pour Android).

J'ai donc ajouté des codes QR (créés avec un générateur en ligne) à mes supports pédagogiques rapportés par les enfants à la maison. Il pouvaient enfin écouter des mots ou de courtes phrases en français chez eux. Cela s'est montré très utile et m'a donné l'envie d'améliorer peu à peu le système.

## 2- Évolution :chart_with_upwards_trend:

Petit à petit, MAEL est devenu un outil utile pour plusieurs professeurs enseignant une langue. Personnellement, je l'utilise tous les jours.

- J'ai donc créé un petit générateur (en python) de code QR plus pratique qu'un site web.
- J'ai ajouté un mode "Dicter" qui cache le texte lu par MAEL Scan.
- J'ai ajouté un mode "Épeler" qui épelle les lettres au lieu de lire le texte.
- J'ai ajouté un encryptage léger du code QR (pour les petits malins qui utilisent un lecteur de code QR standard pour préparer leur dictée :stuck_out_tongue_winking_eye: )

Par ailleurs, sous l'inspiration d'un collègue, j'ai commencé à créer une application (en JavaScript) qui permet de créer des phrases en tout en toute autonomie à partir d'images.)

Ce fut la naissance de MAEL Phrase.


[![IMAGE ALT TEXT HERE](./readme_assets/Video_thumb.png)](https://www.youtube.com/watch?v=qW8FHrZ1HIo)

## 3- Prospective :eyes:

:fire: Plusieurs travaux les plus urgents actuellement :

1- MAEL Scan nécessite une version iOS car il y a pas mal d'utilisateur qui ont un iPhone (Déjà commencée en Kotlin).

2- MAEL Phrase n'est qu'une petite page limitée (entre autre pas l'usage de Gemini 2.5). Elle a besoin de devenir une véritable plateforme avec suivi des activités des élèves.

3- MAEL Scan pour le primaire, reste une occasion de plus pour l'enfant d'avoir un téléphone dans la main. J'ai donc commencé le développement d'une version embarquée sur un Raspberry pi.

4- J'ai maintenu la possibilité d'utiliser 55 langues (au moins pour les modes lecteur et dictée pour le moment)

:eyeglasses: Voir la liste exhaustive des développements nécessaires.

## 4- Conclusion :checkered_flag:

Je ne suis qu'un instit qui s'est autoformé en programmation. 

En plus de mon travail de classe (préparation, corresctions...) je ne trouve pas assez de temps pour me former et continuer à développer le projet MAEL à la vitesse qu'il requière. MAEL me dépasse ! :sweat_smile:

- Il est actuellement en cours d'utilisation dans plusieurs classes dont les professeurs me demandent des améliorations.

- Le projet est soutenu par la Zone AMLA Nord (Académie de notre région), mais je n'arrive pas à suivre le rythme (développement raspberry pi, création de la plateforme, version iOS de MAEL Scan...)

Pour cela, j'ai décidé de fonder une communauté. :rescue_worker_helmet:

- Pour suppléer mes incompétences.
- pour continuer le développement de cette application quie peut permettre à de nombreux élèves (enfant & adultes) d'apprendre une nouvelle langue.

---

# B- Les applications du projet :gear:

## B1- MAEL Scan :iphone:
C'est la première application créée. Elle est essentiellement à destination des élèves.
## a- Version Mit AppInventor :child:
## b- Version Kotlin :green_apple:
## c- Version sans téléphone :no_mobile_phones:

## B2- MAEL Gen :computer:

## B3- MAEL Phrase :globe_with_meridians:

### a- L'application de création de phrases :speaking_head:

### b- Phonofouille :mag_right:

---






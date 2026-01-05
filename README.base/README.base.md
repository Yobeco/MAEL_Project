<!-- multilingual suffix: fr, en -->

<!--[common]-->
![](./readme_assets/Logo-MAEL-alpha-H.svg)

<!--[fr]-->
**Auteur** : Yonnel Bécognée, instituteur  
**Co-auteur** : François Varlet

<!--[en]-->
**Author**: Yonnel Bécognée, teacher
**Co-author**: François Varlet

<!--[fr]-->
[![License: Libre Non Commerciale](https://img.shields.io/badge/license-GNU%20GENERAL%20PUBLIC%20LICENSE%20V3-white.svg)](./LICENSE)

<!--[en]-->
[![License: Free Non-Commercial](https://img.shields.io/badge/license-GNU%20GENERAL%20PUBLIC%20LICENSE%20V3-white.svg)](./LICENSE)

<!--[common]-->
## :fr: [Français](https://github.com/Yobeco/MAEL_Project) | :gb: English

<!--[fr]-->
# I- Histoire du projet :book:

<!--[en]-->
# I- Project history:book:

<!--[fr]-->
## A- Génèse :milky_way:

<!--[en]-->
## A- Genesis:milky_way:

<!--[fr]-->
Je suis instituteur dans une école française à Managua (Nicaragua :nicaragua:). J'enseigne en maternelle ou en élémentaire selon les années. Tous mes élèves ne parlent pas (encore) français, mais surtout, certains élèves n'ont aucun parent francophone à la maison pour les aider.

<!--[en]-->
I am a teacher at a French school in Managua (Nicaragua). I teach kindergarten or elementary school, depending on the year. Not all of my students speak French (yet), but more importantly, some students do not have French-speaking parents at home to help them.

<!--[fr]-->
Étant autodidacte en programmation, j'ai eu l'idée de mettre du texte brut dans un code QR afin de le faire scanner puis oraliser par une petite application pour cellulaire : **MAEL Scan**, créé avec [Mit App Inventor](https://appinventor.mit.edu/) (Scratch pour Android).

<!--[en]-->
Being self-taught in programming, I had the idea of putting plain text into a QR code so that it could be scanned and then read aloud by a small mobile app: **MAEL Scan**, created with [Mit App Inventor](https://appinventor.mit.edu/) (Scratch for Android).

<!--[fr]-->
J'ai donc ajouté des codes QR (créés avec un générateur en ligne) aux supports pédagogiques que les enfants rapportaient à la maison.

<!--[en]-->
So I added QR codes (created with an online generator) to the educational materials that the children took home.

<!--[fr]-->
:tada: :sparkles: Ils pouvaient enfin écouter des mots ou de courtes phrases en français chez eux. Cela s'est montré très utile pour leur apprentissage et m'a donné l'envie d'améliorer le système.

<!--[en]-->
tada: :sparkles: They could finally listen to words or short phrases in French at home. This proved very useful for their learning and made me want to improve the system.

<!--[fr]-->
## B- Évolution :chart_with_upwards_trend:

<!--[en]-->
## B- Evolution:chart_with_upwards_trend:

<!--[fr]-->
Petit à petit, MAEL est devenu un outil utile pour plusieurs professeurs enseignant une langue. Actuellement, je l'utilise tous les jours avec mes élèves de CE1-CE2.

<!--[en]-->
Little by little, MAEL has become a useful tool for several language teachers. Currently, I use it every day with my second and third grade students.

<!--[fr]-->
* J'ai donc créé un petit générateur de codes QR **MAEL Gen** (python) plus pratique qu'un site web.
* J'ai ajouté un mode "Dicter" qui cache le texte lu par MAEL Scan.
* J'ai ajouté un mode "Épeler" qui épelle les lettres au lieu de lire le texte.
* J'ai ajouté un encryptage léger du contenu du code QR (pour les petits malins qui utilisent un lecteur de code QR standard pour préparer leur dictée :stuck_out_tongue_winking_eye: )
* J'ai maintenu la possibilité d'utiliser 55 langues (au moins pour les modes lecture et dicter pour le moment).

<!--[en]-->
* So I created a small QR code generator called **MAEL Gen** (python) that is more convenient than a website.
* I added a “Dictate” mode that hides the text read by MAEL Scan.
* I added a “Spell” mode that spells out the letters instead of reading the text.
* I added light encryption of the QR code content (for those clever people who use a standard QR code reader to prepare their dictation :stuck_out_tongue_winking_eye: ).
* I kept the option to use 55 languages (at least for the read and dictate modes for now).

<!--[fr]-->
Par ailleurs, sous l'inspiration d'un collègue, j'ai commencé à développer une application en JavaScript, qui permet de créer des phrases en toute autonomie à partir d'images.

<!--[en]-->
In addition, inspired by a colleague, I began developing a JavaScript application that allows users to create sentences independently from images.

<!--[fr]-->
Ce fut la naissance de **MAEL Phrase**.

<!--[en]-->
This was the birth of **MAEL Phrase**.

<!--[fr]-->
_Petite vidéo résumant où en est le projet MAEL actuellement :_

<!--[en]-->
Short video summarizing the current status of the MAEL project:_

<!--[common]-->
[![IMAGE ALT TEXT HERE](./readme_assets/Video_thumb.png)](https://www.youtube.com/watch?v=qW8FHrZ1HIo)

<!--[fr]-->
## C- Prospective :eyes:

<!--[en]-->
## C- Prospective:eyes:

<!--[fr]-->
:fire: Plusieurs travaux sont urgents actuellement :

<!--[en]-->
fire: Several tasks are currently urgent:

<!--[fr]-->
1- **MAEL Scan** nécessite une version **iOS** car il y a pas mal d'utilisateurs qui ont un iPhone (déjà commencée en Kotlin).

<!--[en]-->
**MAEL Scan** requires an **iOS** version because there are quite a few users who have iPhones (already started in Kotlin).

<!--[fr]-->
2- **MAEL Phrase** n'est qu'une petite page limitée (entre autre pas l'usage de Gemini 2.5). Elle a besoin de devenir une véritable **plateforme avec suivi des activités des élèves**.

<!--[en]-->
**MAEL Phrase** is only a small, limited page (among other things, it does not use Gemini 2.5). It needs to become a true **platform with student activity tracking**.

<!--[fr]-->
3- **MAEL Scan** pour le primaire, reste une occasion de plus pour l'enfant d'avoir un téléphone dans la main. J'ai donc commencé le développement d'une version embarquée sur un **Raspberry pi**.

<!--[en]-->
**MAEL Scan** for primary school children is yet another opportunity for children to have a phone in their hands. So I started developing a version that runs on a **Raspberry Pi**.

<!--[fr]-->
### :keyboard: Liste des développements en cours :

<!--[en]-->
:keyboard: List of ongoing developments:

<!--[fr]-->
| Application | Dépôt GitHub |
| ----------- | ----------- |
| MAEL Scan | [Disponible](https://github.com/Yobeco/MAEL_Scan) |
| MAEL Scan Pi | Bientôt Disponible |
| MAEL Gen | [Disponible](https://github.com/Yobeco/MAEL_Gen) |
| MAEL phrase | [Disponible](https://github.com/Yobeco/MAEL_Phrases) |
| Phonofouille | [Disponible](https://github.com/Yobeco/MAEL_Phonofouille) |

<!--[en]-->
| Anwendung | GitHub-Repository |
| ----------- | ----------- |
| MAEL Scan | [Available](https://github.com/Yobeco/MAEL_Scan) |
| MAEL Scan Pi | Soon available |
| MAEL Gen | [Available](https://github.com/Yobeco/MAEL_Gen) |
| MAEL phrase | [Available](https://github.com/Yobeco/MAEL_Phrases) |
| Phonofouille | [Available](https://github.com/Yobeco/MAEL_Phonofouille) |


<!--[fr]-->
## D- Conclusion :checkered_flag:

<!--[en]-->
## D- Conclusion: checkered_flag:

<!--[fr]-->
### :man_teacher: Je ne suis qu'un instit qui s'est auto-formé en programmation.

<!--[en]-->
### :man_teacher: I'm just a teacher who taught myself programming.

<!--[fr]-->
En plus de mon travail de classe (préparation, corrections...) je ne trouve plus assez de temps pour me former et continuer à développer le projet MAEL à la vitesse qu'il requière.

<!--[en]-->
In addition to my classroom work (preparation, grading, etc.), I no longer have enough time to train myself and continue developing the MAEL project at the pace it requires.

<!--[fr]-->
### **MAEL me dépasse !** :sweat_smile:

<!--[en]-->
### **MAEL is beyond me!** :sweat_smile:

<!--[fr]-->
* :trophy: MAEL Scan est actuellement **en cours d'utilisation dans plusieurs classes en Amérique centrale et du nort** dont les professeurs me proposent des améliorations.
* :postal_horn: Le projet est **soutenu par la Zone AMLA Nord** (Académie de notre région) et ses conseillés pédagogiques. Mais je n'arrive pas à suivre le rythme : développement raspberry pi, création de la plateforme, version iOS de MAEL Scan, amélioration de MAEL Gen...

<!--[en]-->
*:trophy: MAEL Scan is currently **being used in several classrooms in Central America and North America**, where teachers are suggesting improvements.
* :postal_horn: The project is **supported by Zone AMLA Nord** (our regional academy) and its educational advisors. But I can't keep up with the pace: developing Raspberry Pi, creating the platform, the iOS version of MAEL Scan, improving MAEL Gen...

<!--[fr]-->
### **:rescue_worker_helmet: Pour cela, j'ai décidé de fonder une communauté OpenSource.**

<!--[en]-->
### **:rescue_worker_helmet: To do this, I decided to start an open-source community.**

<!--[fr]-->
* Pour suppléer mes lacunes.
* Pour accélérer le développement de cette application qui peut permettre à de nombreux élèves (enfants & adultes) d'apprendre une nouvelle langue. :grin:

<!--[en]-->
* To make up for my shortcomings.
* To speed up the development of this application, which can enable many students (children and adults) to learn a new language. :grin:

<!--[common]-->
:fr: :gb: :es: :portugal: :brazil: :it: :de: :ru: :jp: :cn: :kr: ...

<!--[common]-->
---

<!--[fr]-->
# II- Les applications du projet MAEL :gear:

<!--[en]-->
# II- Applications of the MAEL project:gear:

<!--[common]-->
---

<!--[fr]-->
## A- MAEL Scan :iphone:

<!--[en]-->
## A- MAEL Scan: iPhone:

<!--[common]-->
![](./readme_assets/MAEL-Scan2-seul-350px.png)

<!--[fr]-->
C'est la première application créée.

<!--[en]-->
This is the first application created.

<!--[fr]-->
:speaking_head: Elle permet aux élèves d'écouter le contenu d'un code QR mis sur un document papier par le professeur.

<!--[en]-->
speaking_head: It allows students to listen to the content of a QR code placed on a paper document by the teacher.

<!--[fr]-->
Le code QR peut contenir :

<!--[en]-->
The QR code can contain:

<!--[fr]-->
* :page_facing_up: **un mot ou un texte** qui sera lu par une voix de syhtèse ou bien
* :microphone: un lien vers **un fichier .mp3** :musical_note: (pour le moment hébergé sur un Google Drive).

<!--[en]-->
* :page_facing_up: **a word or text** that will be read by a synthetic voice, or
* :microphone: a link to **an .mp3 file** :musical_note: (currently hosted on Google Drive).

<!--[common]-->
---

<!--[fr]-->
### 1- MAEL Scan - Version Mit App Inventor :child:

<!--[en]-->
### 1- MAEL Scan - Version with App Inventor :child:

<!--[common]-->
![](./readme_assets/Android-MITai-150px.png)

<!--[fr]-->
La première version de **MAEL Scan** a été développée avec [MIT App Inventor](https://appinventor.mit.edu/) (code par blocks).  
Cela a permis de créer rapidement une version fonctionnelle. Cependant, ce langage est inssuffisant pour les développements futurs.

<!--[en]-->
The first version of **MAEL Scan** was developed using [MIT App Inventor](https://appinventor.mit.edu/) (block-based coding).
This allowed us to quickly create a functional version. However, this language is insufficient for future developments.

<!--[fr]-->
D'autre part, seule une compilation pour Android est possible. Alors, plusieurs familles ont acheté un téléphone Android basique pour pouvoir utiliser MAEL. :unamused:

<!--[en]-->
On the other hand, only a compilation for Android is possible. So, several families bought a basic Android phone to be able to use MAEL. :unamused:

<!--[common]-->
---

<!--[fr]-->
### 2- MAEL Scan - Version Kotlin :green_apple:

<!--[en]-->
### 2- MAEL Scan - Kotlin version :green_apple:

<!--[common]-->
![](./readme_assets/Kotlin-MP-150px.png)

<!--[fr]-->
[Kotlin MP](https://kotlinlang.org/) est conçu pour pouvoir créer une application pour plusieurs plateformes à partir d'un même code source.

<!--[en]-->
[Kotlin MP](https://kotlinlang.org/) is designed to enable the creation of applications for multiple platforms from a single source code.

<!--[fr]-->
Pour dépasser les limites imposées par le langage MIT App Inventor et pour pouvoir créer une **version iOS de MAEL**, j'ai donc commencé à apprendre le Kotlin. (Mais aussi pour développer le back-end de MAEL Phrase)

<!--[en]-->
To overcome the limitations imposed by the MIT App Inventor language and to be able to create an iOS version of MAEL, I started learning Kotlin. (But also to develop the back-end of MAEL Phrase.)

<!--[fr]-->
Pour le moment, seule l'interface a été codée. Je suis actuellement bloqué concernant l'implémentation du module de lecture de code QR et l'implémentation du module pour la synthèse vocale.

<!--[en]-->
For the moment, only the interface has been coded. I am currently stuck on implementing the QR code reader module and the speech synthesis module.

<!--[fr]-->
[![Aller au dépôt](./readme_assets/GitHub-Bandeau-45px.png)](https://github.com/Yobeco/MAEL_Scan)

<!--[en]-->
[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Scan)

<!--[common]-->
---

<!--[fr]-->
### 3- MAEL Scan - Version sans téléphone :no_mobile_phones:

<!--[en]-->
### 3- MAEL Scan - Version without phone:no_mobile_phones:

<!--[common]-->
![](./readme_assets/MAEL-Rpi-150px.png)

<!--[fr]-->
Étant conscient des problèmes que pose **l'utilisation excessive du téléphone portable chez les plus jeunes**, j'ai vite eu des remords à en mettre un dans les mains d'enfants de materelle et d'école élémentaire.

<!--[en]-->
Being aware of the problems posed by **excessive cell phone use among young children**, I quickly felt remorseful about putting one in the hands of preschool and elementary school children.

<!--[fr]-->
:bulb: J'ai donc commencé à développer une version de MAEL Scan (Python) sur une carte **Raspberry pi** équipée d'un écran E-paper. Un premier prototype est déjà fonctionnel.

<!--[en]-->
bulb: So I started developing a version of MAEL Scan (Python) on a **Raspberry Pi** board equipped with an E-paper display. An initial prototype is already functional.

<!--[fr]-->
Il est prévu que "MAEL Scan Pi" (nom provisoire) devienne un bel objet imprimé en 3D prêté aux familles, symbole matériel de leur entrée dans un nouvel apprentissage.

<!--[en]-->
It is planned that “MAEL Scan Pi” (provisional name) will become an attractive 3D-printed object loaned to families, a tangible symbol of their entry into a new learning experience.

<!--[fr]-->
![Pas encore de dépôt](./readme_assets/GitHub-H_constr_45px.png)

<!--[en]-->
[No deposit yet](./readme_assets/GitHub-H_constr_45px.png)

<!--[common]-->
---

<!--[fr]-->
## B- MAEL Gen :computer:

<!--[en]-->
## B- MAEL Gen:computer:

<!--[common]-->
![](./readme_assets/MAEL_Gen.png)

<!--[fr]-->
**MAEL Gen** fut développé (Python) pour faciliter la **création des codes QR** par le professeur.  
Il fonctionne sur ordinateur (Linux/MacOS/Win) et permet de paramétrer facilement le contenu des codes QR en ajoutant de manière transparente les balises nécessaires.

<!--[en]-->
**MAEL Gen** was developed (Python) to facilitate the **creation of QR codes** by teachers.
It runs on computers (Linux/MacOS/Win) and allows you to easily configure the content of QR codes by seamlessly adding the necessary tags.

<!--[fr]-->
[![Aller au dépôt](./readme_assets/GitHub-Bandeau-45px.png)](https://github.com/Yobeco/MAEL_Gen)

<!--[en]-->
[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Gen)

<!--[common]-->
---

<!--[fr]-->
## C- MAEL Phrase :globe_with_meridians:

<!--[en]-->
## C- MAEL Phrase: globe_with_meridians:

<!--[fr]-->
### 1- L'application de création de phrases :speaking_head:

<!--[en]-->
### 1- The sentence creation app :speaking_head:

<!--[common]-->
![](./readme_assets/MAEL_Phrase-b-600px.png)

<!--[fr]-->
**MAEL Phrase** a pour objectif de permettre à l'élève de **créer des phrases de manière autonome**.
Programmé en HTML/JavaScript/CSS, il utilise pour le moment l'API gratuite (mais limitée) de `Gemini 2.5 Pro` pour générer des phrases conjuguées et accordées.

<!--[en]-->
**MAEL Phrase** aims to enable students to **create sentences independently**.
Programmed in HTML/JavaScript/CSS, it currently uses the free (but limited) API from `Gemini 2.5 Pro` to generate conjugated and agreed sentences.

<!--[fr]-->
Il est prévu que le professeur puisse concevoir ses propres activités sur mesure, pour les élèves de sa classe.

<!--[en]-->
It is expected that teachers will be able to design their own customized activities for the students in their class.

<!--[fr]-->
[![Aller au dépôt](./readme_assets/GitHub-Bandeau-45px.png)](https://github.com/Yobeco/MAEL_Phrases)

<!--[en]-->
[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Phrases)

<!--[fr]-->
### 2- Phonofouille :mag_right:

<!--[en]-->
### 2- Phonofouille :mag_right:

<!--[common]-->
![](./readme_assets/Phonofouille-600px.png)

<!--[fr]-->
**MAEL Phrase** va proposer par défault une banque de mots (et d'images) que le professeur pourra enrichir à sa guise.

<!--[en]-->
**MAEL Phrase** will offer a default word bank (and image bank) that teachers can add to as they wish.

<!--[fr]-->
Afin, de créer ses propres activités, le professeur aura besoin d'un **moteur de recherche** pour choisir des mots dans la base de données.  
:bookmark_tabs: Cependant, des critères tels que le recherche par sons, position du son dans le mot, par nature du mot, par thèmes ou par nombre de syllabes serait très utile.

<!--[en]-->
In order to create their own activities, teachers will need a **search engine** to select words from the database.
:bookmark_tabs: However, criteria such as searching by sound, position of the sound in the word, type of word, theme, or number of syllables would be very useful.

<!--[fr]-->
:bulb: J'ai donc développé **Phonophouille** (python/SQLite) afin d'explorer la faisabilité d'un tel moteur de recherches.

<!--[en]-->
bulb: So I developed **Phonophouille** (python/SQLite) to explore the feasibility of such a search engine.

<!--[fr]-->
[![Aller au dépôt](./readme_assets/GitHub-Bandeau-45px.png)](https://github.com/Yobeco/MAEL_Phonofouille)

<!--[en]-->
[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Phonofouille)

<!--[common]-->
---

<!--[fr]-->
# III- Participez au projet MAEL !

<!--[en]-->
# III- Get involved in the MAEL project!

<!--[fr]-->
Écrivez-moi à cette adresse pour plus de détails :

<!--[en]-->
Please email me at this address for more details:

<!--[common]-->
### 📨 ***[mael@lvh.edu.ni](mailto:mael@lvh.edu.ni)***

<!--[fr]-->
Nous avons besoin de contributeurs ayant :

<!--[en]-->
We need contributors who have:

<!--[fr]-->
* des compétences en python,
* la maîtrise du Raspberry pi et la gestions de modules,
* des compétences en Kotlin (Backend),
* des compétences en Kotlin MP (Android et iOS),
* des compétences en HTML/JavaScript/CSS,
* des compétences en PostgreSQL.
* :pencil2: Nous avons également besoin d'un(e) illustrateur / illustratrice pour créer une **bibliothèque d'images libres de droits** pour MAEL Phrase.
* des connaissances en macros pour LibreOffice <img src="https://cdn.simpleicons.org/LibreOffice/FFFF" width="24" height="24" style="vertical-align: middle;" />

<!--[en]-->
* Python skills,
* Proficiency in Raspberry Pi and module management,
* Kotlin skills (backend),
* Kotlin MP skills (Android and iOS),
* HTML/JavaScript/CSS skills,
* PostgreSQL skills.
* :pencil2: We also need an illustrator to create a **library of royalty-free images** for MAEL Phrase.
* Knowledge of LibreOffice macros <img src="https://cdn.simpleicons.org/LibreOffice/FFFF" width="24" height="24" style="vertical-align: middle;" />

<!--[common]-->
---
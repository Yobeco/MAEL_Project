![](./readme_assets/Logo-MAEL-alpha-H.svg)

**Author**: Yonnel Bécognée, teacher
**Co-author**: François Varlet

[![License: Free Non-Commercial](https://img.shields.io/badge/license-GNU%20GENERAL%20PUBLIC%20LICENSE%20V3-white.svg)](./LICENSE)

## :fr: [Français](https://github.com/Yobeco/MAEL_Project/blob/main/README.fr.md) | :gb: English

# I- Project history​ :book:

## A- Genesis​ :milky_way:

I am a teacher at a French school in Managua (Nicaragua). I teach kindergarten or elementary school, depending on the year. Not all of my students speak French (yet), but more importantly, some students do not have French-speaking parents at home to help them.

Being self-taught in programming, I had the idea of putting plain text into a QR code so that it could be scanned and then read aloud by a small mobile app: **MAEL Scan**, created with [Mit App Inventor](https://appinventor.mit.edu/) (Scratch for Android).

So I added QR codes (created with an online generator) to the educational materials that the children took home.

tada: :sparkles: They could finally listen to words or short phrases in French at home. This proved very useful for their learning and made me want to improve the system.

## B- Evolution :chart_with_upwards_trend:

Little by little, MAEL has become a useful tool for several language teachers. Currently, I use it every day with my second and third grade students.

* So I created a small QR code generator called **MAEL Gen** (python) that is more convenient than a website.
* I added a “Dictate” mode that hides the text read by MAEL Scan.
* I added a “Spell” mode that spells out the letters instead of reading the text.
* I added light encryption of the QR code content (for those clever people who use a standard QR code reader to prepare their dictation :stuck_out_tongue_winking_eye: ).
* I kept the option to use 55 languages (at least for the read and dictate modes for now).

In addition, inspired by a colleague, I began developing a JavaScript application that allows users to create sentences independently from images.

This was the birth of **MAEL Phrase**.

Short video summarizing the current status of the MAEL project:_

[![IMAGE ALT TEXT HERE](./readme_assets/Video_thumb.png)](https://www.youtube.com/watch?v=qW8FHrZ1HIo)

## C- Prospective :eyes:

fire: Several tasks are currently urgent:

**MAEL Scan** requires an **iOS** version because there are quite a few users who have iPhones (already started in Kotlin).

**MAEL Phrase** is only a small, limited page (among other things, it does not use Gemini 2.5). It needs to become a true **platform with student activity tracking**.

**MAEL Scan** for primary school children is yet another opportunity for children to have a phone in their hands. So I started developing a version that runs on a **Raspberry Pi**.

:keyboard: List of ongoing developments:

| Anwendung | GitHub-Repository |
| ----------- | ----------- |
| MAEL Scan | [Available](https://github.com/Yobeco/MAEL_Scan) |
| MAEL Scan Pi | Soon available |
| MAEL Gen | [Available](https://github.com/Yobeco/MAEL_Gen) |
| MAEL phrase | [Available](https://github.com/Yobeco/MAEL_Phrases) |
| Phonofouille | [Available](https://github.com/Yobeco/MAEL_Phonofouille) |


## D- Conclusion :checkered_flag:

### :man_teacher: I'm just a teacher who taught myself programming.

In addition to my classroom work (preparation, grading, etc.), I no longer have enough time to train myself and continue developing the MAEL project at the pace it requires.

### **MAEL is beyond me!** :sweat_smile:

*:trophy: MAEL Scan is currently **being used in several classrooms in Central America and North America**, where teachers are suggesting improvements.
* :postal_horn: The project is **supported by Zone AMLA Nord** (our regional academy) and its educational advisors. But I can't keep up with the pace: developing Raspberry Pi, creating the platform, the iOS version of MAEL Scan, improving MAEL Gen...

### **:rescue_worker_helmet: To do this, I decided to start an open-source community.**

* To make up for my shortcomings.
* To speed up the development of this application, which can enable many students (children and adults) to learn a new language. :grin:

:fr: :gb: :es: :portugal: :brazil: :it: :de: :ru: :jp: :cn: :kr: ...

---

# II- Applications of the MAEL project :gear:

---

## A- MAEL Scan :iPhone:

![](./readme_assets/MAEL-Scan2-seul-350px.png)

This is the first application created.

speaking_head: It allows students to listen to the content of a QR code placed on a paper document by the teacher.

The QR code can contain:

* :page_facing_up: **a word or text** that will be read by a synthetic voice, or
* :microphone: a link to **an .mp3 file** :musical_note: (currently hosted on Google Drive).

---

### 1- MAEL Scan - Version with App Inventor :child:

![](./readme_assets/Android-MITai-150px.png)

The first version of **MAEL Scan** was developed using [MIT App Inventor](https://appinventor.mit.edu/) (block-based coding).
This allowed us to quickly create a functional version. However, this language is insufficient for future developments.

On the other hand, only a compilation for Android is possible. So, several families bought a basic Android phone to be able to use MAEL. :unamused:

---

### 2- MAEL Scan - Kotlin version :green_apple:

![](./readme_assets/Kotlin-MP-150px.png)

[Kotlin MP](https://kotlinlang.org/) is designed to enable the creation of applications for multiple platforms from a single source code.

To overcome the limitations imposed by the MIT App Inventor language and to be able to create an iOS version of MAEL, I started learning Kotlin. (But also to develop the back-end of MAEL Phrase.)

For the moment, only the interface has been coded. I am currently stuck on implementing the QR code reader module and the speech synthesis module.

[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Scan)

---

### 3- MAEL Scan - Version without phone :no_mobile_phones:

![](./readme_assets/MAEL-Rpi-150px.png)

Being aware of the problems posed by **excessive cell phone use among young children**, I quickly felt remorseful about putting one in the hands of preschool and elementary school children.

bulb: So I started developing a version of MAEL Scan (Python) on a **Raspberry Pi** board equipped with an E-paper display. An initial prototype is already functional.

It is planned that “MAEL Scan Pi” (provisional name) will become an attractive 3D-printed object loaned to families, a tangible symbol of their entry into a new learning experience.

[No deposit yet](./readme_assets/GitHub-H_constr_45px.png)

---

## B- MAEL Gen :computer:

![](./readme_assets/MAEL_Gen.png)

**MAEL Gen** was developed (Python) to facilitate the **creation of QR codes** by teachers.
It runs on computers (Linux/MacOS/Win) and allows you to easily configure the content of QR codes by seamlessly adding the necessary tags.

[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Gen)

---

## C- MAEL Phrase :globe_with_meridians:

### 1- The sentence creation app :speaking_head:

![](./readme_assets/MAEL_Phrase-b-600px.png)

**MAEL Phrase** aims to enable students to **create sentences independently**.
Programmed in HTML/JavaScript/CSS, it currently uses the free (but limited) API from `Gemini 2.5 Pro` to generate conjugated and agreed sentences.

It is expected that teachers will be able to design their own customized activities for the students in their class.

[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Phrases)

### 2- Phonofouille :mag_right:

![](./readme_assets/Phonofouille-600px.png)

**MAEL Phrase** will offer a default word bank (and image bank) that teachers can add to as they wish.

In order to create their own activities, teachers will need a **search engine** to select words from the database.
:bookmark_tabs: However, criteria such as searching by sound, position of the sound in the word, type of word, theme, or number of syllables would be very useful.

bulb: So I developed **Phonophouille** (python/SQLite) to explore the feasibility of such a search engine.

[![Go to repository](./readme_assets/GitHub-Banner-45px.png)](https://github.com/Yobeco/MAEL_Phonofouille)

---

# III- Get involved in the MAEL project! ![](./readme_assets/MAEL_48px.png)

Please email me at this address for more details:

### 📨 ***[mael@lvh.edu.ni](mailto:mael@lvh.edu.ni)***

We need contributors who have:

* Python skills,
* Proficiency in Raspberry Pi and module management,
* Kotlin skills (backend),
* Kotlin MP skills (Android and iOS),
* HTML/JavaScript/CSS skills,
* PostgreSQL skills.
* :pencil2: We also need an illustrator to create a **library of royalty-free images** for MAEL Phrase.

---
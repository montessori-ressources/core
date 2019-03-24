# Projet Montessori Ressources

## Objectifs du projet

L'objectif de ce projet est de rassembler des ressources de qualités en lien avec l'enseignement Montessori. Ces ressources sont proposées gratuitement mais gérées par une communauté qui garantira la qualité du contenu proposé. Le projet est composé de 3 parties principales pour le moment:

1. Donner accès à une liste de nomenclatures de qualité et contrôlées aux enseignants ou à toutes autres personnes intéressée par la méthode d'éducation Montessori. Ces nomenclature sont pour des élèves de 9 à 11ans.
2. Permettre d'accéder à un catalogue de références bibliographiques sur la méthode à toutes personnes l'étudiant ou devant préparer une conférence/exposé sur des sujets traité dans les ouvrages en lien avec la méthodologie.
3. Cartes autocorrectives en mathématiques (**TBC**)

## Fonctionalités et information techniques

### Général
- Site/Application multi-langues (Français et Anglais au départ)
- Accès aux nomenclature publique, mais téléchargement des nomenclature réservé aux membres de la communauté.
- Authentification simple, par email ou application externe oauth (Google, Facebook, Twitter, ...)

### Nomenclature (Classified Card)
- Géneration de PDF téléchargeables en différents formats : A4, US Letter.
- Recherche de nomenclature (**Categorisation/Classification à définir**)
- Utiliser une police non cursive neutre, paramétrable facilement à l'avenir.
- Volume de nomenclature initial ~100 nomenclatures, objectif de 500 dans l'année
- Possibilité de définir des favoris
- Signaler une nomenclature (i.e. problème de droit sur les images)

#### Upload des nomenclature

- Pas plus de 20 images par nomenclature
- Minimum 4 images par nomenclature
- les images de la nomenclature font 14x14 cm. 
- Les étiquettes font 14x2,5 cm.
- Les images uploadées seront en license Creative Common. 
- Texte en pied de pages des PDF (**TBC**): Illustration téléchargée par ____
- **A Confirmer** Supporter un format d'image plus petit pour mettre 4 images par feuille (a confirmer par Allan)

#### Autres
- Niveaux d'accomplissement pour les contributeurs afin d'encourager et d'afficher leur engagment sur la plateforme. (badges)

### Définition d'une carte de Nomenclature

Deux catégories de nomenclatures:
A. Nomenclature simple
B. Nomenclatures scientifique

Niveaux de difficulté (à choisir à l'exportation avec une liste déroulante):
1. Pré-lecteur avec association d'un objet: 1 carte par image avec l'image uniquement.
2. Pré-lecteur avec association d'images: 2 cartes par image avec l'image uniquement.
3. Lecteur débutant: 2 cartes et une étiquette par image - 1 carte avec l'image et le mot en-dessous, 1 carte avec l'image sans le mot et une étiquette avec le mot seulement.
4. Lecteur sans texte à trou: 2 cartes et une étiquette pour chaque image - 1 carte avec l'image sans le mot, une carte avec le texte complet et une étiquette avec le mot seulement.
5. Lecteur avec texte à trou: 3 cartes et une étiquette pour chaque image - 1 carte avec l'image sans le mot, une carte avec le texte complet, une carte avec le texte à trou et une étiquette avec le mot seulement.

Les niveaux 4 et 5 doivent aussi avoir l'option d'imprimer un livret de référence autocorrectif qui comprend:
- Une page titre avec le nom de la nomenclature.
- Une double page pour chaque image avec l'image à gauche, et à droite le texte complet et le nom en haut en gras (titre)
- une page arrière (couverture arrière) vide avec la license en petit dans un coin.

## Type d'utilisateur
1. Enseignant à la recherche de materiel pour ses cours (simple visiteur)
1. Contributeur: Personne ayant créé un compte sur le site pour partager des nomenclatures
1. Modérateur qui validera les nomenclatures proposées par les contributeurs
1. Etudiant cherchant des références bibliographique sur un sujet spécifique. (simple visiteur)
1. Photographe ayant envie de fournir des images pouvant être utilisées pour créer des nomenclatures

## Personas

### Thierry
Thierry est un enseignant de 25 ans fraîchement diplômé et en charge d'une classe de 27 élèves de 9 à 12 ans. Consciencieux dans son travail, il souhaite fournir à ses élèves du matériel de qualité. Toutefois son temps est précieux et il préfère le consacrer à ses élèves plutôt qu'à la conception de matériel pédagogique.

### Bruno
Bruno est étudiant dans un centre de formation Montessori à Archamps. Il utilise principalement son téléphone portable pour accéder à l'information sur internet et utilise les réseau sociaux comme source d'information. Il a des essais à rédiger pour sa formation et désire savoir où, dans la littérature Montessori, est mentionné ou traité des thèmes théoriques.

## Mathieu
Mathieu est un photographe de 45 ans. Il a fait toute sa scolarité dans une école classique et travaille comme photographe indépendant depuis plus de 20 ans. Sa femme, enseignante Montessori de l'école d'Abidjan en Côte d'Ivoire l'a rendu sensible à cette méthodologie, ce qui lui a donné envie de contribuer à son développement. Ses connaissances en informatique sont très avancées en ce qui concerne la manipulation d'images avec Photoshop, mais limitée en ce qui concerne les applications web. Il utilise principalement son ordinateur de travail lorsqu'il a besoin de naviguer ou du consulter ses emails.

## Design/Chart graphique
**TBC** (btw, pas de logo "officiel")

## Contraintes techniques
- L'application doit être facilement maintenable par des développeurs ayant peu de connaissances techniques.
- La partie publique doit être SEO friendly

## Convention de codage
**TBD**

## Méthode de dévelopment 
**TBC** (GitFlow ?)

## Planning
- Collecte/création de nomenclatures: @Allan et son équipe de bénévoles **TBD**
- Déploiement en production des fonctionalités d'upload pour les nomenclatures: **1 juillet 2019**

## Glossaire
- Carte de nomenclature: Le but des cartes de nomenclatures est d'accroître le vocabulaire, de perfectionner la diction et c'est un tremplin pour la conversation. Plus indirectement, cela permet le perfectionnement des capacités : d’attention, d’observation, de concentration, de mémoire et d’ouverture à la culture. [1](#ref-1).

## Références

### Inspiration 
- <span id="ref-1">[1]</span> http://feetambouilles.canalblog.com/archives/2013/11/16/28346153.html
- <span id="ref-2">[2]</span> https://montessorimaispasque.com/2014/05/13/les-images-classifiees/
- <span id="ref-3">[3]</span> https://1maman2filles.com/nos-fiches-de-nomenclature-a-telecharger/
- <span id="ref-4">[4]</span> https://www.plusdemamans.com/montessori-cartes-de-nomenclatures-fruits-legumes-a-telecharger-a-imprimer/
- <span id="ref-5">[5]</span> https://www.pinterest.fr/pin/374784000232721856/?lp=true
- <span id="ref-6">[6]</span> https://www.pinterest.fr/marionmarquet5/cartes-de-nomenclature/?lp=true
- <span id="ref-7">[7]</span> http://enfantbebeloisir.over-blog.com/2015/03/cartes-nomenclature-a-imprimer-les-animaux-et-leurs-bebes.html
- <span id="ref-8">[8]</span> https://angelinandco.wordpress.com/2016/08/14/cartes-de-nomenclature-montessori/
- <span id="ref-9">[9]</span> http://montessorimateriel.org/


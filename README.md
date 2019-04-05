# Projet Montessori Ressources

## Objectifs du projet

L'objectif de ce projet est de rassembler des ressources de qualité en lien avec l'enseignement Montessori. Ces ressources sont proposées gratuitement, mais gérées par une communauté qui garantira la qualité du contenu proposé. Le projet est composé de 3 parties principales pour le moment :

1. Donner accès à une liste de nomenclatures de qualité et contrôlées aux enseignants ou à toutes autres personnes intéressées par la méthode d'éducation Montessori. Ces nomenclatures sont pour des élèves de 9 à 11ans.
2. Permettre d'accéder à un catalogue de références bibliographiques sur la méthode à toutes personnes l'étudiant ou devant préparer une conférence/exposé sur des sujets traités dans les ouvrages en lien avec la méthodologie.
3. Cartes autocorrectives en mathématiques (**TBC**)

## Fonctionalités et information techniques

### Général
- Site/Application multilingue (Français et Anglais au départ)
- Accès public aux ressources (nomenclatures, etc.), mais téléchargement réservé aux membres de la communauté.
- Authentification simple, par courriel ou application externe oauth (Google, Facebook, Twitter,...)

### Nomenclatures (Classified Card)
- Géneration de PDF téléchargeables en différents formats : A4, US Letter.
- Recherche de nomenclature (**Categorization/Classification à définir**)
- Utiliser une police non cursive neutre, paramétrable facilement à l'avenir.
- Volume initial de nomenclatures ~100 nomenclatures, objectif de 500 dans l'année
- Possibilité de définir des favoris
- Signaler une nomenclature (c.-à-d. problème de droits sur les images ou contenu inapproprié)

#### Téléversement des nomenclatures

- Pas plus de 20 images par nomenclature
- Minimum 4 images par nomenclature
- les cartes de la nomenclature font 14 cm x 14 cm. 
- Les étiquettes font 14 cm x 2,5 cm.
- Les images téléversées seront en licence Creative Common. 
- Texte en pied de page des PDF (**TBC**) : Illustrations téléchargées par ____
- Offrir l’option de cartes plus petites pour en mettre 4 par feuille

#### Autres
- Niveaux d'accomplissement pour les contributeurs afin d'encourager et d'afficher leur engagement sur la plateforme. (badges)

#### Définition d'une carte de nomenclature

Deux catégories de nomenclatures :
A. Nomenclature simple
- Chaque image représente un autre mot, les mots sont d'une même catégorie (ex. : les sortes de camions).
B. Nomenclature scientifique
- C'est la même image plusieurs fois, mais chacune met une partie en évidence en la mettant en couleur (habituellement rouge).
- Parfois, on a l'image principale colorée (ex. : volcans avec les couleurs naturelles) puis la même image en noir et blanc, mais avec chaque partie nommée en rouge pour les autres.

Niveaux de difficulté (à choisir à l'exportation avec une liste déroulante) :
1. Prélecteur avec association d'un objet : 1 carte par image avec l'image uniquement.
2. Prélecteur avec association d'images : 2 cartes par image avec l'image uniquement.
3. Lecteur débutant : 2 cartes et une étiquette par image - 1 carte avec l'image et le mot en dessous, 1 carte avec l'image sans le mot et une étiquette avec le mot seulement.
4. Lecteur sans texte à trou : 2 cartes et une étiquette pour chaque image - 1 carte avec l'image sans le mot, une carte avec le texte complet et une étiquette avec le mot seulement.
5. Lecteur avec texte à trou : 3 cartes et une étiquette pour chaque image - 1 carte avec l'image sans le mot, une carte avec le texte complet, une carte avec le texte à trou et une étiquette avec le mot seulement.

Les niveaux 4 et 5 doivent aussi avoir l'option d'imprimer un livret de référence autocorrectif qui comprend :
- Une page titre avec le nom de la nomenclature.
- Une double page pour chaque image avec l'image à gauche, et à droite le texte complet et le nom en haut en gras (titre)
- une page arrière (couverture arrière) vide avec la licence en petit dans un coin.

### Index Montessori
- Base de données de sujets pédagogiques (ex. : liberté et discipline, éducation à la paix, matériel autocorrectif, isolation des difficultés, etc.)
- Index des endroits où l'on peut lire à ce sujet dans les livres de Maria Montessori et les autres livres de référence de la méthode.
- Inclure l'information de l'édition (maison d'édition et année)
- Des utilisateurs avec droits supplémentaires peuvent renseigner la base de données.
- Accès libre en lecture (pas besoin de connexion)
- La connexion permet la mémorisation des ouvrages "favoris" (édition spécifique)

#### Niveaux de référence
A. Ouvrage complet sur le sujet
B. Chapitre complet sur le sujet
C. Sujet traité de façon significative dans un (ou quelques) paragraphe
D. Mention ou sujet abordé brièvement

### Cartes autocorrectives et commandes
A. Opérations en mathématiques
B. Mesure des lignes, des angles et calcul des aires
C. Divers

#### A. Opérations en mathématiques
- Format : 9 cm x 6 cm
- Recto : calcul (ex : 3 457 + 832)
- Verso : réponse (y compris le reste dans le cas de la division et les simplifications dans le cas des fractions)
- Liste de critères de difficultés précises (ex. : multiplicande max 9, produit max 999, 0 aux unités dans le multiplicateur, etc.)
- On combine des critères pour former un niveau.
- Chaque niveau a un titre et une courte description.
- L'utilisateur peut choisir de prendre un ensemble de niveaux prédéfinis (paramétrés par nous au départ, ex. : "ensemble de base")
- Ou il peut construire son propre ensemble. Il peut également partager son ensemble sur son profil.

##### Opérations
- Comparaisons (< > =)
- Additions
- Soustractions
- Multiplications
- Divisions
- PPCM (Plus Petit Commun Multiple)
- PGCD (Plus Grand Commun Diviseur)
- Fractions - comparaisons (< > =)
- Fractions - équivalences
- Fractions - additions
- Fractions - soustractions
- Fractions - multiplications
- Fractions - divisions
- Nombres décimaux - lecture et écriture
- Nombres décimaux - comparaisons (< > =)
- Nombres décimaux - additions
- Nombres décimaux - soustractions
- Nombres décimaux - multiplications
- Nombres décimaux - divisions
- Conversions (ex. : fractions à nombres décimaux, pourcentages à fractions irréductibles, etc.)
- Priorité des opérations

#### B. Mesure des lignes, des angles et calcul des aires
- 14 cm x 14cm
- Recto : image générée
- Verso : valeur (mm et cm, degrés, mm2 et cm2)

#### C. Divers
- 2 formats possibles : 14x14 ou 9x6
- Recto : énigme (image ou texte)
- Verso : réponse (image ou texte)

Exemple : lire l'heure
- Recto : horloge avec aiguilles (image)
- Verso : avec l'heure (ex. : 8:40)

Exemple : empreintes d’animaux
- Recto : empreintes d'un animal
- Verso : nom de l'animal

## Type d'utilisateur
1. Enseignant à la recherche de matériel pour ses cours (simple visiteur)
2. Contributeur : Personne ayant créé un compte sur le site pour partager des nomenclatures
3. Modérateur qui validera les nomenclatures proposées par les contributeurs
4. Étudiant cherchant des références bibliographiques sur un sujet spécifique. (simple visiteur)
5. Photographe ayant envie de fournir des images pouvant être utilisées pour créer des nomenclatures

## Personas

### Thierry
Thierry est un enseignant de 25 ans fraîchement diplômé et responsable d'une classe de 27 élèves de 9 à 12 ans. Consciencieux dans son travail, il souhaite fournir à ses élèves du matériel de qualité. Toutefois son temps est précieux et il préfère le consacrer à ses élèves plutôt qu'à la conception de matériel pédagogique.

### Bruno
Bruno est étudiant dans un centre de formation Montessori à Archamps. Il utilise principalement son téléphone portable pour accéder à l'information sur internet et utilise les réseaux sociaux comme source d'information. Il a des essais à rédiger pour sa formation et désire savoir où, dans la littérature Montessori, est mentionné ou traité des thèmes théoriques.

## Mathieu
Mathieu est un photographe de 45 ans. Il a fait toute sa scolarité dans une école classique et travaille comme photographe indépendant depuis plus de 20 ans. Sa femme, enseignante Montessori de l'école d'Abidjan en Côte d'Ivoire l'a rendu sensible à cette méthodologie, ce qui lui a donné envie de contribuer à son développement. Ses connaissances en informatique sont très avancées en ce qui concerne la manipulation d'images avec Photoshop, mais limitée en ce qui concerne les applications web. Il utilise principalement son ordinateur de travail lorsqu'il a besoin de naviguer ou du consulter ses courriels.

## Design/Chart graphique
**TBC** (btw, pas de logo "officiel")

## Contraintes techniques
- L'application doit être facilement maintenable par des développeurs ayant peu de connaissances techniques.
- La partie publique doit être SEO friendly

## Convention de codage
**TBD**

## Méthode de développement 
**TBC** (GitFlow ?)

## Planification
- Collecte/création de nomenclatures : @Allan et son équipe de bénévoles **TBD**
- Déploiement en production des fonctionnalités de téléversement pour les nomenclatures : **1 juillet 2019**

## Glossaire
- Carte de nomenclature : Le but des cartes de nomenclatures est d'accroître le vocabulaire, de perfectionner la diction et c'est un tremplin pour la conversation. Plus indirectement, cela permet le perfectionnement des capacités : d’attention, d’observation, de concentration, de mémoire et d’ouverture à la culture. [1] (#ref-1).

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


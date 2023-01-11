# Projet POO JAVA

# I- Sujet

Faire les fonctionnalités suivantes de l'application Gestion de Contacts

## Modifier / supprimer un contact 

Si les fonctionnalités modifier et supprimer ne sont pas finies, les finir.

## Trier les contacts par nom

Récuperer la liste de contacts puis la trier par nom et prénom (si ils ont le même nom).
Vous devrez obligatoirement utiliser la méthode [sort](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Collections.html#sort(java.util.List)) de la classe Collections pour faire le tri.
Vous devrez également utiliser l'interface [Comparable](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/Comparable.html) pour créer le comparateur par défaut de la class Contact.

## Trier par date de naissance

Sans changer le comparateur par défaut défini au-dessus, vous devez récupérer les liste de contacts, et la trier sur la date de naissance.
Vous devrez utiliser l'autre méthode [sort](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Collections.html#sort(java.util.List,java.util.Comparator)) de la classe Collections.

Vous devrez également utiliser l'interface [Comparator](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Comparator.html).

## Trier par mail

Sans changer le comparateur par défaut défini au-dessus, vous devez récupérer les liste de contacts, et la trier sur le mail.
Vous devrez utiliser l'autre méthode [sort](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Collections.html#sort(java.util.List,java.util.Comparator)) de la classe Collections.

Vous devrez également utiliser l'interface [Comparator](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Comparator.html).
A la différence du tri précédent, vous devrez utiliser l'interface Comparator avec une [class anonyme](https://docs.oracle.com/javase/tutorial/java/javaOO/anonymousclasses.html).

## Rechercher sur le prénom

Après avoir récupérer votre liste de contacts, vous devrez utiliser la méthode filter de la classe [Stream](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/stream/package-summary.html) afin de trouver et d'afficher tous les contact dont le prénom commence par ce que l'utilisateur aura préalablement renseigné.

Votre code du filtre devra être au format expression lambda.

## Compilation

Vous devez générer le fichier executable de votre application (*.jar).

Afin de tester votre fichier, vous pouvez démarrer votre application en appelant "java mofichier.jar" dans une console.
[aide](https://docs.oracle.com/javase/tutorial/deployment/jar/build.html)


# Groupes et fonctionnement

Le projet est a développé en groupe de 3/4 personnes.
Tous les groupes seront définis en cours, sous la supervision de l'enseignant. Les groupes s'enregistrent avec un nom de groupe ainsi que les noms de leurs membres.

Toute inscription est définitive.  Les étudiants ne sont pas autorisés, par la suite, à changer de groupe.

Au sein d'un groupe, les étudiants se répartiront les tâches pour le projet, de façon équitable.  Il est explicitement exigé que chaque membre consacre au moins 50% de son travail à du développement technique. Du code de test est acceptable, tant qu'il ne constitue pas l'intégralité de la réalisation technique du membre du groupe.

Les étudiants sont encouragés (mais pas obligés) à mettre en place un système de contrôle des sources de type Git ou équivalent, afin d'affecter et partager efficacement les fichiers de codes et autres composants numériques du projet (fichiers sources, descripteurs de déploiement, documents de recherche, cas d'utilisation, suites de tests, etc.).

# Présentation et rendu

La soutenance aura lieux le vendredi 13 janvier 2023.
Les horaires de passage sont définis pour chaque groupe.
Toute absence à la soutenance entrainera un 0 (ZERO) pour le membre du groupe.

Les rendus doivent figurer sur un seul compte par groupe.
Le rendu s'effectu via un repos GIT. L'adresse du rendu est envoyé par mail.
Le mail de rendu est vincent.leclerc@edu.esiee-it.fr
Les fichiers rendus doivent contenir
  - L'arborescence du projet, immédiatement exploitable ou un GIT.
  - Un AUTHORS.TXT listant les membres du groupe (prénom, nom), à raison d'un par ligne.  Il liste ensuite les responsabilités effectives de chacun dans le groupe.
Le sujet du mail doit contenir votre section ainsi que le nom du projet et du groupe.
Les fichiers rendus peuvent aussi comprendre: 
  - Des documents de recherche créés pour le projet et fournissant plus de détails pour l'enseignant.
Pour tout autre type de fichier, veuillez demander à l'enseignant si son inclusion est appropriée.
La soutenance dure 10 minutes durant lesquelles les membres présentent leur travail. Un échange de questions peut se faire entre le professeur et les membres du groupe.

Les groupes sont les suivants:
- G1 : Paul, Leo Y, Mattéo
- G2 : Esteban, jean juste , Benjamin T 
- G3 : Léo V, Ethan N, Sacha
- G4 : Lucas T, florent, Ethan D
- G5 : Dounya, Baptiste, Aya
- G6 : Lina, Amin, Nabil
- G7 : Eloi, Léopold, océane
- G8 : samba, Jordan, Timéo
- G9 : Mathys, Kevin, Alexandre, Kenza



Les horaires de passage des groupes sont les suivants:
- 15h45 => 

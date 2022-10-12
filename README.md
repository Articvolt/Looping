# Looping

Exercices sur le MCD (modèle conceptuel de données) avec l'outil "looping".

## ENTREPRISE
Une entreprise représentée par une raison sociale, une adresse (+ cp / ville) et une date de création possède des salariés (nom, prénom, date de naissance, date d'embauche). On partira du principe qu'un salarié appartient à une et une seule entreprise.
Un salarié possède un type de contrat (CDI, CDD, intérim, ...). En cas de CDD, le salarié possède une date de fin de contrat (facultative si le salarié est en CDI).

## LIVRES
Un auteur (nom, prénom, sexe, date de naissance) possède une bibliographie de livres (titre, date de sortie, nombre de pages, résumé). Il n'y aura pas de livres co-écrits dans la base de données. Un livre pourra posséder plusieurs genres (roman, fantastique, policier,...)

## E-COMMERCE
Un client (numéro de client, nom, prénom, adresse mail, mot de passe, date d'inscription, coordonnées de votre choix) peut réaliser des commandes auprès d'un site e-commerce à une date donnée.
Le site met en vente des produits (désignation, prix) appartenant à une catégorie unique. Ceux-ci peuvent être commandés en de multiples exemplaires.

## FORUM
Vous êtes en charge de réaliser un forum.
Celui-ci est constitué de sujets (ou topics) qui appartiennent à une catégorie unique. L'auteur du sujet (qui est un membre du forum) peut décider de verrouiller un sujet. Un sujet pourra évidemment contenir des messages (ou posts).
Sur un forum les catégories sont triées alphabétiquement sur le nom, les sujets dans l'ordre antéchronologique et les messages dans l'ordre chronologique.
Les membres du forum se connectent au forum avec un identifiant (mail), possède un pseudo, un mot de passe et un rôle (celui-ci sera contenu dans un tableau dans l'entité membre). On pourrait retrouver plusieurs rôles prédéfinis : Admin, modérateur ou membre "classique" par exemple.

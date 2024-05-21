# Projet Intégration de données

![alt text](presentation/images/page_1.png)

Ce projet a été réalisé par notre équipe composée de trois étudiants en Data Science à l'ICAM.

L'objectif de ce projet était de réaliser l'intégration d'une base de données en vue d'être en mesure de répondre à des requêtes de type SQL.

Nous avons choisi de nous pencher sur [le Répertoire National des Élus (RNE)](https://www.data.gouv.fr/fr/datasets/repertoire-national-des-elus-1/), qui recense les élus des différentes chambres (municipales, départementales, régionales, etc.) en France.

[Lien vers la présentation de notre projet (pdf).](presentation/Presentation_Int-Proj-elus.pdf)

Les grandes étapes de notre travail ont été les suivantes :

![alt text](presentation/images/page_2.png)

Après avoir téléchargé les données, nous avons commencé par les explorer pour comprendre leur structure et leur contenu. La base a nécessité un nettoyage et une transformation pour être exploitable. En effet celle-ci était composée de plusieurs fichiers CSV (un par chambre) que nous avons dû mettre en relation afin de pouvoir répondre à des requêtes SQL.

Nous avons donc mené une réflexion sur la modélisation de la base de données, afin d'établir un schéma qui permette de répondre au mieux à toutes les requêtes, tout en proposant une structure facilement maintenable, élection après élection.

Après nettoyage et restructuration des données, nous avons créé une base de données SQL que nous avons hébergé sur un serveur distant (Ubuntu sur serveur Oracle, serveur MariaDB).

La base de donnée fonctionnelle nous as permis d'étudier la parité au sein des chambres, les nuances politiques des chambres, les mandats cumulés, les élus les plus âgés...

La présentation de ce projet est disponible [ici](presentation/Presentation_Int-Proj-elus.pdf).





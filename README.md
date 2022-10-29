
# Débruitage par CNN d’images chiffrées ou secrètes bruitées
 
Bienvenu dans le dépot de projet pour l'UE __Images, Sécurité et Deeplearning__.
Ce dépot regroupe notre travail sur le débruitage d'images chiffrées.
<p align="center">
<img align="center" src="./Rendus/Images/presentation.jpg" width="300" height="300"/>
</p>

<b>Encadrants :</b>    
- William Puech (https://www.lirmm.fr/~wpuech/) 
- Bianca Jansen van Rensburg (bianca.jansen-van-rensburg@etu.umontpellier.fr)
- Nicolas Dibot (nicolas.dibot@etu.umontpellier.fr)
- Pauline Puteaux (https://paulineputeaux.github.io/)

<b>Participants :</b>
- Ange Clément (ange.clement@etu.umontpellier.fr) 
- Erwan Reinders (erwan.reinders@etu.umontpellier.fr) 
______________________________
## Problématique
<p align="justify">
Nous avons vu en TP que si une image chiffrée était bruitée alors le déchiffrement était rendu difficile. L’objectif de ce projet de corriger une image chiffrée ou secrète qui a été bruitée par débruitage d’images. Nous nous intéresserons particulièrement aux chiffrements par bloc et au partage d’images secrètes basé sur la génération de polynômes comme proposé par Shamir en 1979. Le débruitage pourra se faire dans un premier temps à partir d’approches sans apprentissage profond, et dans un second temps en utilisant les réseaux de neurones convolutifs. Il s’agira d’évaluer et de comparer les résultats obtenus par différentes méthodes.
</p>

## Missions
<p align="justify">
 <ol>
 <li>Décrire un état de l'art sur le débruitage d’images avec ou sans apprentissage profond.</li>
 <li>Décrire un état de l’art sur le chiffrement d’images par bloc et sur le partage d’images secrètes.</li>
 <li>Choisir une méthode de débruitage sans apprentissage profond et l’implémenter.</li>
 <li>Tester et analyser les résultats obtenus sur une base de données. Proposer une évaluation des résultats obtenus.</li>
 <li>Choisir une méthode basée sur un réseau de neurones convolutifs et l’implémenter. Tester, analyser les résultats obtenus et effectuer une comparaison avec les résultats obtenus précédemment (en utilisant la même base de données).</li>
 <li>Appliquer la méthode sans apprentissage profond et celle utilisant les réseaux de neurones convolutifs (sans réentraîner le modèle) sur une nouvelle base de données et analyser les résultats obtenus.</li>
<li>Créer une démonstration sous la forme d'un logiciel avec une interface.</li>
  </ol>
 </p>

## Détails techniques
<p align="justify">
Ce projet est fait via <b>Python</b>.
</p>

<!-- 
## Documentations :
Aucune documentation n'est pour l'instant fournie.
-->

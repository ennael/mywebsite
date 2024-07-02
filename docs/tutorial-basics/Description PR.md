## - Développement (brache de travail => QA)

1 - dans VScode : créer une branche de travail depuis QA (attention au nommage)
2 - publier la branche
3 - commit en local des évolutions (attention au message et au contenu des commits)
4 - push commits sur le serveur
6 - sur Github : création Pull Request - attention à la branche cible (QA)
assignation : envoie notification
labels : caractériser urgence, type (bug, évolution..)
description
7 - Passage en revue proposition de la branche de travail
8 - Si OK => Merge dans QA => github action qui déploie en environnement de test

9 - Suppression branche sur le serveur depuis l'écran de PR
10 - en local (branche et Remotes), tirer ou récupérer (Remotes)

=> A répéter pour chaque branche d'évolution

## - Production (QA => main)

6 - sur Github : création Pull Request - attention à la branche cible (main)
assignation : envoie notification
labels : caractériser urgence, type (bug, évolution..)
description
7 - Passage en revue proposition de la branche QA
8 - Si OK => Merge dans main => github action qui déploie en environnement de production
9 - créer le tag sur Github sur le dernier commit de main
10 - créer la release à partir du tag : release notes attachées
11 - en local, tirer ou récupérer pour disposer du tag

![Tutoriel Basic](/img/Capture_tutoriel.png)



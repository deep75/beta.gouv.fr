Le site public de l'Incubateur de Services Numériques de l'État français.

> Pour exécuter cet environnement avec Docker, il faut lancer par exemple cette commande :

     docker run -d -p 80:5000 --name betagouvfr mcas/betagouvfr:latest

> Ou le construire par exemple à partir du Dockerfile avec :

     docker build -t mcas/betagouvfr .
     docker run -d -p 80:5000 --name betagouvfr mcas/betagouvfr:latest
     
## Support navigateur

Au vu du public visé, ce site doit être **dégradable** jusqu'à IE8.

> Cela ne signifie pas qu'il doit afficher [la même chose](http://dowebsitesneedtolookexactlythesameineverybrowser.com) dans tous les navigateurs, mais simpelment que son contenu doit être lisible même avec des navigateurs obsolètes.

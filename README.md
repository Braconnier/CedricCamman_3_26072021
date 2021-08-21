# Il s'agit du projet 3 de la formation développeur web d'open classroom.

Le but est de réaliser un projet de site pour une start-up qui propose de reservez des menus dans des restaurants gastronomiques.

Le cahier des charges indique que les polices sont shrikhand et roboto.
Nous avons une charte de couleurs #9356DC pour la primaire; #FF79DA pour la secondaire et #99E2D0 pour la teriaire.
l'utilisation de javascript ainsi que tout Framework est proscrite.
Aucun CSS inline dans le document HTML.
L'utilisation de scss est recommandé.
le site est pensé en mobile-first mais doit être responsive pour s'adapter aux tablettes ou écrans.
L'ensemble du site passe la validation W3C.
La compatibilité des navigateurs doit être assurée.
Le footer est identique sur toutes les pages.
le lien "contact" renvoit vers la messagerie.
Le header contient le logo du site ainsi qu'un lien de retour à l'accueil sur les pages des réstaurants.
les "animations" ou transitions sont réalisées en CSS, pas de javascript.


/////////////////////////////   Mise en oeuvre    /////////////////////////////////


Un loader global a été mis en place d'une durée réglable dans les variables.
Les boutons "Explorer nos restaurants" et "Commander" sont identiques et possèdent un effet au survol.
Le bouton "Explorer" nos réstaurants 
les coeurs representent la mise en favis et sont actifs au survol et au clic.
les cartes des restaurants sur la page d'accueil sont reactifs au survol et renvoient vers la page du restaurant concerné.

Le coeur represente un "favori" et est réactif au survol comme au clic.
après le chargement ddu loader global, les plats apparraisent par un effet de translation. Durée et délais réglables dans les variables.
Lors du survol d'un plat, la fiche laisse defiler par translation un check donnant la futur possibilité de valider le plat à commander.
la marque du "check" possède un effet de rotation.



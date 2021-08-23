# Il s'agit du projet 3 de la formation développeur web d'Open Classroom. 


Le but est de réaliser un projet de site pour une start-up qui propose de réservez des menus dans des restaurants gastronomiques. 
 

Le cahier des charges indique que les polices sont shrikhand et roboto. 
Nous avons une charte de couleurs #9356DC pour la primaire ; #FF79DA pour la secondaire et #99E2D0 pour la tertiaire. 
L'utilisation de javascript ainsi que tout Framework est proscrite. 
Aucun CSS inline dans le document HTML. 
L'utilisation du SCSS est recommandée. 
Le site est pensé en mobile-first mais doit être responsive pour s'adapter aux tablettes ou écrans. 
L'ensemble du site passe la validation W3C HTML et CSS. 
La compatibilité des navigateurs doit être assurée. 
Le footer est identique sur toutes les pages. 
Le lien "contact" renvoi vers la messagerie. 
Le header contient le logo du site ainsi qu'un lien de retour à l'accueil sur les pages des restaurants. 
Les "animations" ou transitions sont réalisées en CSS/SCSS, pas de javascript. 

 

/////////////////////////////   Mise en œuvre    ///////////////////////////////// 
  
  
Un loader global a été mis en place d'une durée réglable dans les variables. 
Les boutons "Explorer nos restaurants" et "Commander" sont identiques et possèdent un effet au survol. 
Le bouton "Explorer" nos restaurants renvoie à la section des restaurants. 
Les cœurs représentent la mise en favoris (utilisation ultérieure) et sont actifs au survol et au clic. 
Les cartes des restaurants sur la page d'accueil sont réactives au survol et renvoient vers la page du restaurant concerné. 
 
Après le chargement du loader global, les plats apparaissent par un effet de translation (modification de la largeur du bandeau). Durée et délais réglables dans les variables. 
Lors du survol d'un plat, la fiche laisse défiler par translation un check donnant la future possibilité de valider le plat à commander. 
La marque du "check" possède un effet de rotation durant la translation du bandeau. 
Les images ont été recadrées et redimensionnées au format WSVGA pour un bon ratio qualité compatibilité. 
Le site est entièrement responsive. Les breakpoints sont à 365px pour les mobiles, 768px pour les tablettes et 1024px pour les écrans. 
Une mediaquery a été spécifiée pour les portables à écran plus petit comme le I-Phone5. 
La maintenabilité du site est globalement assurée par des variables mixins et fonctions. 

# M2_ConceptionEvaluationDeSystemes

#Besoins
* Communication entre rondier et superviseurs => smartphone.
* Géolocalisation rondier, pour savoir qui est le plus proche pour agir où quand
* Rondier doit dire sur son smartphone ce qu'il est en train de faire (déposer smartphone près de machine (nfc) puis ecran en mode quelle tache
exemple : départ cycle, dosage solvant, purge etc etc). On peut avoir les mains sales donc prévoir des écrans à detection de mouvement.
* DashBoard avec info pertinante dessus (panneau de contrôle, jauge etc)
* Possibilité d'avoir accès à des stats sur ce qu'il s'est passé
* Marquage des zones dangereuses, lumières (adaptée pour les daltoniens), son + indiquer sur smartphone
* Contact des experts : comme ils peuvent être dans un pays différent, lors d'un appel en langues étrangères, l'application traduit automatique dans les deux sens (pour le rondier : FR->EN, pour l'expert : EN->FR)
* Appel rapide au service "Incendie et produits toxiques" : indiquer l'emplacement du problème + la gravité + le type (incendie ou produits toxiques)
* Traduction
* Besoin de :
	* réutilisabilité d'un pays à l'autre : i18n
	* réutilisabilité d'un projet à l'autre : l'application se conforme à la spécification OSGi (découpages en modules)
	* solutions économiques : ???
	* solutions durables : ??? (rétro éclairage?)

Pour l'appli :  
* Tutoriel d'utilisation de l'appli


#Solution :

* Appli smartphone pour rondier
* Appli desktop pour superviseur (dans salle de contrôle)
* Eclairage + enceinte pour zone de danger
* Puce NFC près des machines (avec écran tactile) (si panne NFC, appeler superviseur qui fera la manip et demandera à changer la puce)
* Pour contact avec les experts, repertoire d'expert (avec classification par domaine d'expertise)
* Experts dovient pouvoir voir les panneaux de contrôles et potentiellement la caméra d'un des smartphones des rondiers (style skype)
* Boutons sur les applis pour tout traduire
* Interface pour les contre maitres leur permettant d'ajouter des stations sur la carte


#Acteurs :

* Rondiers
* Superviseurs
* Ingénieur de production
* Experts
* Service Incendie et produits toxiques
* Techniciens de maintenance
* Contremaitre

#Outils :

* Balsamiq Mock : https://balsamiq.com/download/
* Violet UML : https://sourceforge.net/projects/violet/files/violetumleditor/

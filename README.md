# IntroductionUml
Découverte du langage UML

## Contexte
La médiathèque municipale de la ville de KELVILLE possède aujourd’hui plus de 500 000
ressources (livres, journaux, magazines, CD, DVD, Jeux, etc.) et souhaite moderniser son
informatique qui date des années 90 et commence à montrer ses limites.
Au sein de la médiathèque, elle souhaite mettre à disposition des utilisateurs (employés ou
clients) des ordinateurs afin que ces derniers puissent utiliser les nouvelles fonctionnalités qui
dépendront du profil de l’utilisateur.

## Cahier des charges
La médiathèque gère plusieurs types de ressources : livres, journaux et magazines
périodiques, CD, DVD et jeux de sociétés.

Tout est empruntable.

Tous les employés qui utilisent le système informatique doivent s’authentifier. En cas
d’absence d’authentification, seule la fonction de recherche d’une ressource est accessible.
Cette fonction de recherche se fait à partir d’un type de ressource (livre, journaux, DVD, CD,
etc..), d’un titre et/ou d’un auteur.

L’administrateur est le seul à être habilité à créer de nouveaux types de ressources.
Les gestionnaires peuvent saisir des nouvelles références de ressources (ex : nouveau livre ou
jeu de société) dans le système et leur affecter un emplacement au sein de la médiathèque
(salle, rayonnage).

Les employés de la médiathèque sont tous habilités à consulter l’inventaire de la
médiathèque et à rechercher une ressource à partir de son type, titre ou de son auteur. La
consultation de l’inventaire propose une fonction d’impression que ne possède pas la
recherche de ressource.

Le guichetier peut créer le profil d’un nouveau client dans le système. Il peut également saisir
une demande d’emprunt pour un client donné et encaisser la somme correspondant à
l’emprunt. Enfin il peut saisir une pénalité en cas de retour en retard de ressources.
Le guichetier peut également imprimer un reçu d’emprunt si besoin.

Enfin un client, s’il est authentifié, peut réserver une ressource actuellement indisponible.

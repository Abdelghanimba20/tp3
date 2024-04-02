Initialisation du projet :

J'ai créé un nouveau projet Maven dans mon environnement de développement.
J'ai ajouté les dépendances nécessaires dans le fichier pom.xml pour Spring MVC, Thymeleaf et Spring Data JPA.
Création de l'entité Patient :

J'ai créé une entité JPA nommée Patient avec les attributs nécessaires tels que id, nom, prénom, etc.
J'ai annoté cette classe avec les annotations JPA appropriées (@Entity, @Table, etc.).
Création du Repository Patient :

J'ai créé une interface PatientRepository en étendant JpaRepository<Patient, Long>.
Cette interface permet d'accéder aux opérations CRUD de base pour l'entité Patient.
Développement du Contrôleur :

J'ai créé un contrôleur nommé PatientController pour gérer les requêtes HTTP liées aux patients.
J'ai implémenté des méthodes dans ce contrôleur pour afficher les patients, gérer la pagination, rechercher des patients et supprimer un patient.
Création des pages HTML avec Thymeleaf :

J'ai créé des pages HTML avec Thymeleaf pour afficher la liste des patients, les résultats de recherche, etc.
J'ai utilisé des expressions Thymeleaf pour afficher les données dynamiques provenant du contrôleur.
Configuration de la pagination :

J'ai utilisé les fonctionnalités de pagination fournies par Spring Data JPA pour gérer la pagination des résultats.
Gestion des requêtes de recherche :

J'ai ajouté une fonctionnalité de recherche qui permet aux utilisateurs de rechercher des patients par nom, prénom, etc.
Suppression de patients :

J'ai implémenté la logique de suppression des patients en utilisant les méthodes fournies par le PatientRepository.
Améliorations supplémentaires :

J'ai ajouté une fonctionnalité d'édition des patients permettant de mettre à jour les informations des patients.
J'ai mis en place des validations côté serveur pour garantir l'intégrité des données.
J'ai ajouté une couche de sécurité pour restreindre l'accès à certaines fonctionnalités aux utilisateurs authentifiés.
J'ai ajouté des fonctionnalités de tri pour trier les patients par différents critères.
!
# tp3

# MedicalPracticeWebsite

Projet : gestion d'un cabinet médical
 
L'objectif est de créer une application de gestion d'un cabinet médical permettant au secrétariat de saisir les rendez-vous de consultation. Elle doit permettre de gérer la liste des usagers du centre (avec leurs civilités, leurs noms et prénoms, leurs adresses complètes, leurs dates et lieux de naissance, et leurs numéros de sécurité sociale) ainsi que la liste des médecins (avec leurs civilités, noms, et prénoms). Chaque usager pourra avoir un médecin référent parmi ceux du centre. Le secrétariat devra pouvoir saisir les rendez-vous en choisissant l'usager et le médecin dans des listes et en saisissant la date, l'heure, et la durée de la consultation (30 min par défaut).

Gardez à l'esprit que l'application devra être pratique à utiliser et accessible à des néophytes. Imaginez ce que ça ferait si vous deviez l'utiliser tous les jours.

Exercice 16 : modèle de données

Sur papier ou à l'aide de l'outil de votre choix, réaliser le modèle de données pour cette application. APRES L'AVOIR FAIT VALIDER par votre enseignant, créer la base de données MySQL correspondante.

Exercice 17 : gestion des usagers et des médecins

Créer les pages nécessaires à l'affichage, l'ajout, la modification, et la suppression des usagers. Réutiliser ces pages en modifiant les formulaires et les requêtes pour mettre en oeuvre la gestion des médecins.

Exercice 18 : saisie des rendez-vous de consultation

Créer les pages nécessaires à l'affichage et à la saisie des consultations. Vous pourrez utiliser un tableau trié par ordre chronologique descendant pour l'affichage (les plus anciennes consultations en fin de tableau). Lors de la saisie, si un médecin référent est associé à un usager, celui-ci devra être proposé par défaut.

Exercice 19 : statistiques

Créer une page affichant les statistiques suivantes :

Un tableau à double entrée affichant la répartition des usagers selon leur sexe et leur âge (moins de 25 ans, entre 25 et 50 ans, plus de 50 ans).
Tranche d'âge	Nb Hommes	Nb Femmes
Moins de 25 ans	 	 
Entre 25 et 50 ans 	 	 
Plus de 50 ans	 	 
La durée totale des consultations effectuées par chaque médecin (en nombre d'heures).

Exercice 20 : cadre de l'application

Sécuriser l'application en créant une page d'authentification (à l'aide d'un nom d'utilisateur et d'un mot de passe définis à l'avance). Aucune autre page de l'application ne devra être accessible si l'utilisateur n'est pas authentifié.

Mettre en place un menu global proposant 4 items ("Usagers", "Médecins", "Consultations", et "Statistiques") qui sera affiché sur chaque page pour permettre à l'utilisateur de naviguer dans l'application. Ajouter tous les liens nécessaires entre les différentes pages.

Exercice 21 : planning

Reprendre les pages de gestion des consultations et ajouter :

La modification et la suppression des consultations.
Un contrôle de non-chevauchement des consultations pour un même médecin.
La possibilité de filtrer la liste des consultations par médecin au moyen d'un menu déroulant.

Exercice 22 : mise en forme

Utiliser les feuilles de style (CSS) et les bases d'ergonomie logicielle pour faire en sorte que l'utilisation de l'application soit la plus agréable et intuitive possible.

___________________
 
REMARQUES

La première page de votre application doit s'appeler index.php (ou index.html) pour qu'elle soit utilisée automatiquement lorsque vous accédez au répertoire du projet
Vous devriez utiliser les fonctions include ou require pour modulariser votre code et ne pas avoir les mêmes bouts de code présents dans plusieurs pages (par exemple : la connexion à la base de données, la vérification de l'identification de l'utilisateur, l'affichage du menu, etc.)
Les dates doivent être saisies et affichées en français (jj/mm/aaaa) et le format de saisie doit être précisé
 

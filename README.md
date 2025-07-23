# IPSycka - Outil de Recherche d'IP

IPSycka est une application web élégante et moderne conçue pour fournir des informations détaillées sur n'importe quelle adresse IP. Avec son interface soignée et réactive, elle offre une expérience utilisateur fluide pour l'analyse et la géolocalisation d'IP.

## Apperçu

![Aperçu du projet IPSycka](https://image.noelshack.com/fichiers/2025/30/4/1753310541-capture-d-cran-2025-07-24-004203.png)

## Fonctionnalités

*   **Analyse automatique** : Détecte et affiche les informations de l'IP de l'utilisateur dès le chargement de la page.
*   **Recherche Manuelle** : Une barre de recherche "Prestige" permet d'analyser n'importe quelle adresse IPv4 ou IPv6.
*   **Interface Moderne** : Un design sombre, épuré et centré sur l'utilisateur avec des animations fluides.
*   **Informations Détaillées** : Affiche la localisation, le fournisseur d'accès (FAI), l'organisation, les coordonnées géographiques et plus encore.
*   **Entièrement Responsive** : S'adapte parfaitement aux écrans de bureau comme aux appareils mobiles.
*   **Gestion des Erreurs** : Affiche des messages clairs en cas d'erreur ou d'IP invalide.

## Technologies Utilisées

Ce projet est construit avec des technologies web modernes, sans dépendre d'un framework lourd, ce qui le rend léger et rapide.

*   **HTML5** : Pour la structure sémantique du contenu.
*   **CSS3** : Pour le style avancé, incluant :
    *   **Variables CSS (`:root`)** pour une thématisation facile.
    *   **Flexbox** et **Grid** pour une mise en page complexe et réactive.
    *   **Animations (`@keyframes`)** et **Transitions** pour une interface dynamique.
    *   **Sélecteur `:focus-within`** pour une interactivité améliorée de la barre de recherche.
*   **JavaScript (ES6+)** : Pour toute la logique de l'application :
    *   **Fetch API** pour les requêtes asynchrones vers l'API externe.
    *   **Async/Await** pour une gestion propre et lisible de l'asynchronisme.
    *   Manipulation du **DOM** pour afficher dynamiquement les résultats.
*   **APIs et Services Externes** :
    *   **ip-api.com** : Utilisé comme source principale pour récupérer les données des adresses IP.
    *   **Font Awesome** : Pour l'ensemble des icônes utilisées dans l'interface.
    *   **Google Fonts** : Pour la police d'écriture 'Inter'.

## Installation

Aucune installation n'est requise. Ce projet est un simple fichier autonome.

1.  Téléchargez le fichier `index.html`.
2.  Ouvrez-le directement dans votre navigateur web préféré (Chrome, Firefox, Edge, etc.).

## Crédits et Contact

Ce projet a été imaginé et développé avec passion par **Sycka**.

*   **GitHub** : [**Sycka**](https://github.com/Sycka)
*   **Discord** : `syckaa`

Les données relatives aux adresses IP sont fournies gracieusement par [ip-api.com](https://ip-api.com/).
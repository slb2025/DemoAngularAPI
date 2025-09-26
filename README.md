Cette application Angular moderne démontre un système complet de gestion de produits avec authentification, routage et intégration d'API. L'application met en évidence les meilleures pratiques en développement Angular, notamment l'utilisation des guards (gardes), des services et de l'organisation des composants.

**🚀 Fonctionnalités**

- Gestion de Produits : Opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) complètes pour les produits.
- Authentification : Sécurisation des routes grâce à un guard d'administration.
- Design Responsive : Interface moderne et conviviale.
- Intégration d'API : Intégration avec l'API DummyJSON.
- Protection des Routes : Guard administrateur pour les routes protégées.
- Validation de Formulaires : Validation personnalisée des e-mails.
- Architecture Modulaire : Structure des composants bien organisée.

**📋 Prérequis**

Node.js (v18 ou supérieur)
npm (Node Package Manager)
Angular CLI

**🛠️ Installation**

Cloner le dépôt :
git clone https://github.com/HCDA99/Angular-M06-API.git

Naviguer vers le répertoire du projet :
cd Angular-M06-API/demo

Installer les dépendances :
npm install

Démarrer le serveur de développement :
ng serve

Ouvrir votre navigateur et naviguer vers http://localhost:4200

**🏗️ Structure du Projet**
src/
  ├── app/
  │   ├── guards/         # Gardes de routes pour l'authentification
  │   ├── models/         # Modèles de données et interfaces
  │   ├── pages/          # Pages/routes de l'application
  │   ├── services/       # Services d'API et d'authentification
  │   ├── shared/         # Composants partagés (en-tête)
  │   └── validators/     # Validateurs de formulaires personnalisés
  ├── environments/       # Configuration d'environnement
  └── assets/            # Ressources statiques

**📱 Pages disponibles**
- Home : Page d'accueil
- Products : Liste et gestion des produits
- Product : Détails d'un produit individuel
- Admin : Tableau de bord administrateur protégé
- About : Page À propos
- Contact : Formulaire de contact avec validation

**🔒 Sécurité**

L'application implémente des gardes de routes (route guards) pour protéger les routes d'administration. L'AdminGuard garantit que seuls les utilisateurs authentifiés disposant des autorisations appropriées peuvent accéder aux zones restreintes.

**🔌 Intégration d'API**

L'application s'intègre avec l'API DummyJSON pour la gestion des produits. Le service DummyJsonApiService gère toutes les communications API.

**🛡️ Services**

- AuthService : Gère l'authentification des utilisateurs.
- DummyJsonApiService : Gère les communications API pour les produits.

**💻 Développement**

Pour contribuer à ce projet :
- Dupliquer (Fork) le dépôt.
- Créer une branche de fonctionnalité :
    git checkout -b feature/nom-de-votre-fonctionnalite
- Commiter vos changements.
- Pousser (Push) vers votre branche.
- Créer une demande de tirage (Pull Request).
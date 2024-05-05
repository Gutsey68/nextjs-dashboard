## Cheatsheets Next.js

### Introduction à Next.js

- Présentation de Next.js, un framework React populaire pour le développement web.
- Avantages de Next.js, y compris le rendu côté serveur, la génération de pages statiques et le préchargement des pages.
- Installation de Next.js à l'aide de `create-next-app`.

### Création d'une Application de Base

- Création d'une application de base avec Next.js en utilisant `create-next-app`.
- Structure de fichiers et organisation du projet.
- Navigation entre les pages avec les composants `Link` de Next.js.

### Navigation Dynamique

- Navigation dynamique avec les paramètres d'URL.
- Utilisation du hook `useRouter` pour accéder aux informations de l'URL.
- Passage de données entre les pages avec les paramètres d'URL.

### Rendu Côté Serveur

- Rendu côté serveur avec Next.js pour améliorer les performances et l'optimisation du référencement.
- Utilisation de la fonction `getServerSideProps` pour récupérer les données côté serveur lors du rendu initial.
- Gestion des erreurs avec la fonction `getServerSideProps`.

### Génération de Pages Statiques

- Génération de pages statiques avec Next.js pour des performances optimales.
- Utilisation de la fonction `getStaticProps` pour récupérer les données lors de la génération de la page.
- Pré-rendu des pages avec des données dynamiques en utilisant `getStaticProps` et `getStaticPaths`.

### Préchargement des Pages

- Préchargement des pages avec Next.js pour améliorer la vitesse de chargement.
- Utilisation de la fonction `getServerSideProps` pour précharger des données lors de la navigation.
- Optimisation du préchargement des pages avec des stratégies adaptées à chaque cas d'utilisation.

### Gestion des Données

- Gestion des données dans Next.js en utilisant différentes méthodes comme `getServerSideProps`, `getStaticProps`, et `useEffect`.
- Choix de la méthode appropriée en fonction des besoins de l'application et des performances requises.

### Optimisation des Performances

- Optimisation des performances dans Next.js en utilisant des techniques comme la mise en cache, le code splitting et la compression.
- Utilisation de l'API `Next.js Image` pour optimiser le chargement des images.
- Mise en œuvre de bonnes pratiques pour garantir des performances optimales.

### Mutating Data

- **React Server Actions**: These allow you to run asynchronous code directly on the server, eliminating the need for creating API endpoints to mutate data. They enhance security by protecting against various threats.

- **Integration with Next.js Caching**: Server actions are deeply integrated with Next.js caching, allowing you to revalidate cache associated with mutations and ensure optimal performance.

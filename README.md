# 💰 PersoCash - Gestionnaire de Cash Flow Personnel

> 🚀 **Version Stable v1.5.4** avec authentification cloud Supabase

## 📋 Description

PersoCash est une application web moderne de gestion de cash flow personnel qui vous permet de :

- 📊 **Prévoir vos finances** sur plusieurs mois
- 💳 **Gérer vos revenus et dépenses** de manière détaillée
- 📈 **Analyser vos tendances** financières avec des KPI avancés
- 🗂️ **Archiver vos données** mensuelles pour un historique complet
- ☁️ **Synchroniser vos données** avec le cloud (Supabase)
- 🔐 **Sécuriser vos informations** avec authentification

## ✨ Fonctionnalités

### 💻 Interface Moderne
- **Design responsive** : Compatible mobile et desktop
- **Interface intuitive** : Navigation simple et efficace
- **Thème moderne** : Interface claire et professionnelle
- **Header intelligent** : Profil utilisateur et connexion cloud intégrés

### 📊 Gestion Financière
- **Prévisions mensuelles** : Calcul automatique sur 20 mois
- **Revenus personnalisables** : Salaire, primes, revenus annexes
- **Dépenses catégorisées** : Organisation par catégories et sous-catégories
- **Alertes intelligentes** : Notifications de seuils critiques
- **Planification avancée** : Gestion des dépenses futures

### 📈 Analytics et KPI
- **Statistiques détaillées** : Analyse sur 12 mois consécutifs
- **Graphiques interactifs** : Visualisation des tendances
- **KPI automatiques** : Revenus, dépenses, épargne moyens
- **Comparaisons mensuelles** : Évolution dans le temps

### 🗂️ Archivage et Historique
- **Archivage mensuel** : Sauvegarde des données réelles vs prévues
- **Historique complet** : Consultation des mois archivés
- **Export/Import** : Sauvegarde et restauration des données

### ☁️ Cloud et Synchronisation
- **Authentification Supabase** : Connexion sécurisée
- **Sauvegarde cloud** : Vos données protégées
- **Multi-appareils** : Accès depuis tous vos appareils
- **Configuration personnalisée** : Paramètres utilisateur cloud

## 🚀 Installation et Démarrage

### Prérequis
- Node.js 18+ 
- npm ou yarn
- Compte Supabase (optionnel pour le cloud)

### Installation locale
```bash
# Cloner le repository
git clone https://github.com/MBeji/PersoCash.git
cd PersoCash

# Installer les dépendances
npm install

# Configurer l'environnement (optionnel)
cp .env.local.example .env.local
# Éditer .env.local avec vos clés Supabase

# Démarrer en développement
npm run dev
```

### Configuration Supabase (Cloud)
1. Créer un projet sur [supabase.com](https://supabase.com)
2. Exécuter le script SQL `supabase-setup.sql`
3. Configurer les variables d'environnement dans `.env.local`
4. Redémarrer l'application

## 🛠️ Technologies

- **Frontend** : React 18, TypeScript, Vite
- **UI/UX** : Tailwind CSS, Shadcn/ui, Lucide Icons
- **Backend** : Supabase (Auth + Database)
- **Charts** : Recharts
- **Testing** : Vitest
- **Build** : Vite, ESLint

## 🔧 Configuration

### Valeurs par Défaut
- **Salaire** : 6000 TND
- **Prime semestrielle** : 0.5 × salaire (4 fois/an)
- **Dépenses fixes** : 3000 TND
- **Seuil d'alerte** : 1000 TND
- **Période d'affichage** : 20 mois

### Personnalisation
Les valeurs peuvent être personnalisées via :
1. **Interface utilisateur** : Paramètres → Montants Fixes
2. **Variables d'environnement** : `.env.local`
3. **Configuration cloud** : Profil utilisateur

## 📚 Documentation

- [`VERSION-v1.5.4-STABLE.md`](./VERSION-v1.5.4-STABLE.md) - Notes de version détaillées
- [`CONFIG-CLOUD-DATABASE.md`](./CONFIG-CLOUD-DATABASE.md) - Architecture cloud
- [`supabase-setup.sql`](./supabase-setup.sql) - Configuration base de données

## 🏷️ Versions

- **v1.5.4-supabase-stable** ✅ : Version actuelle (cloud + auth)
- **v1.4.1-before-supabase** : Version stable sans cloud
- **v1.2.0-stable** : Version de base stable

Voir tous les [tags et releases](https://github.com/MBeji/PersoCash/tags)

## 🤝 Contribution

Les contributions sont les bienvenues ! 

1. Fork le projet
2. Créer une branche feature (`git checkout -b feature/AmazingFeature`)
3. Commit les changements (`git commit -m 'Add AmazingFeature'`)
4. Push vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👨‍💻 Auteur

**Mohamed BEJI**
- GitHub: [@MBeji](https://github.com/MBeji)
- Email: mbeji@sofrecom.fr

## 🎯 Roadmap

### Prochaines Fonctionnalités
- [ ] Migration complète config vers BDD
- [ ] Notifications push
- [ ] Export PDF/Excel
- [ ] Partage familial
- [ ] Application mobile
- [ ] API REST

---

⭐ **Si ce projet vous aide, n'hésitez pas à lui donner une étoile !**

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/0e0e251d-0c13-4a1a-bd05-206d78f853ec) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/0e0e251d-0c13-4a1a-bd05-206d78f853ec) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/tips-tricks/custom-domain#step-by-step-guide)

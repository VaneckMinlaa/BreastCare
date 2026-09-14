# BreastCare — Application mobile (Expo)

Projet mobile développé avec Expo / React Native. Ce README remplace le modèle initial et fournit des instructions complètes en français pour le développement, le test et le déploiement.

---

## Objectif

BreastCare est une application mobile destinée au suivi et à la sensibilisation autour de la santé mammaire. Elle vise à fournir des ressources, rappels et outils d’auto‑examen aux utilisatrices.

---

## Stack

- Framework : Expo (React Native)
- Langage : JavaScript / TypeScript
- Dépendances : Expo SDK, bibliothèques UI et utilitaires (voir package.json)

---

## Prérequis

- Node.js 18+
- npm ou yarn
- Expo CLI
- Android Studio / Xcode (pour émulateurs si nécessaire)

---

## Installation et démarrage

1. Installer les dépendances :

```bash
npm install
# ou
pnpm install
```

2. Lancer le serveur Metro / Expo :

```bash
npx expo start
# ou
npm run start
```

3. Ouvrir sur un appareil via Expo Go (scanner le QR) ou lancer un émulateur.

---

## Tests

- Tests unitaires : `npm test` (selon configuration du projet)
- E2E : config possible avec Detox / Appium si configuré

---

## Build et publication

- Pour un build natif (dev client / production), utilisez EAS ou `expo prebuild` puis `gradlew / xcodebuild`.
- Consultez la documentation d’Expo pour la signature et la publication sur Play Store / App Store.

---

## Structure du dépôt

```
BreastCare/
├── app/            # Code source Expo (ou app/ selon starter)
├── app-example/    # Starter template fourni
├── package.json
└── README.md
```

---

## Contribution

- Fork → branche feature/...
- Respecter les linters et tests
- Ouvrir une issue pour discuter d’une fonctionnalité majeure

---

## Licence

Ajoutez un fichier LICENSE si vous souhaitez préciser la licence (ex. MIT).

---

## Contact

Ouvrez une issue pour toute question ou demande d’aide.
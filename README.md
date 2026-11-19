# My Restaurant – Lab 6

Application mobile simple développée avec **React Native** et **Expo**.
Elle affiche le menu d'un restaurant organisé par sections.

## Capture d'écran

<img width="739" height="1600" alt="WhatsApp Image 2026-11-19 at 14 19 43 (1)" src="https://github.com/user-attachments/assets/3baef18d-d6e3-4e2c-81bf-603413281aae" />

<img width="739" height="1600" alt="WhatsApp Image 2026-11-19 at 14 19 43" src="https://github.com/user-attachments/assets/1a3c9aa0-69e2-42f7-95cc-85291a99c823" />



## Fonctionnalités

- En-tête avec le nom du restaurant
- Menu organisé en 4 sections : Appetizers, Main Dishes, Sides, Desserts
- Affichage du nom et du prix de chaque plat avec `SectionList`
- Pied de page (footer)

## Structure du projet

```
src/
├── app/
│   └── index.tsx          # Écran principal
└── components/
    ├── AppHeader.js       # En-tête
    ├── MenuItems.js       # Liste du menu (SectionList)
    └── AppFooter.js       # Pied de page
```

## Installation et lancement

1. Installer les dépendances :

   ```bash
   npm install
   ```

2. Lancer l'application :

   ```bash
   npx expo start
   ```

3. Scanner le QR code avec l'application **Expo Go** sur le téléphone.

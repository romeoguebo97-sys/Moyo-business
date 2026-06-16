# Moyo Business — lancement local

## Prérequis
- Node.js 18+ et npm installés.

## Lancer
```bash
npm install
npm run dev
```
Puis ouvrir l'URL affichée (par défaut http://localhost:5173).

## Backend Supabase
Le backend est configuré dans `src/MoyoBusiness.tsx` (lignes 3-4 : SUPABASE_URL / SUPABASE_KEY).
Avant de tester, exécuter dans le SQL Editor de votre projet Supabase Business :
1. `etape1_profiles.sql` (colonnes business)
2. `etape2_favorites.sql` (table favoris)
Et vérifier que `profiles.is_visible` a pour défaut `true`.

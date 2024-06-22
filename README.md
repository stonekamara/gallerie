# StoneShot

Plateforme web de gestion pour studio photo : création de comptes, suivi des projets et gestion des clients.

## Stack

- TanStack (React Router) + Vite + TypeScript
- Tailwind CSS + Radix UI
- Supabase (auth + Postgres + RLS + storage)
- Bun

## Démarrage

Copiez le fichier d'exemple vers `.env` et renseignez les variables Supabase :

```bash
VITE_SUPABASE_URL=votre-projet.supabase.co
VITE_SUPABASE_PUBLISHABLE_KEY=remplacer-par-votre-cle-anon
VITE_SUPABASE_PROJECT_ID=votre-projet
```

```bash
bun install
bun run dev
```

> 🔒 Les variables environnements (`*.env*`) sont ignorées par git : aucune clé ne doit être commitée.
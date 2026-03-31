# Supabase setup (CLI)

This repo tracks Supabase project `waocereetemktkzmtoxj`.

## Pull schema/migrations

```bash
npm install -g supabase
supabase login
supabase link --project-ref waocereetemktkzmtoxj
supabase db pull
```

## Important
- Do not commit `.env` or any Supabase keys.

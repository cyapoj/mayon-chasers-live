# Mayon Chasers Live

Single-file static site using Supabase project `ytjvlqlamcposfvkigki`.

The production database is already initialized and the itinerary preloaded (November 23–26, 2026; 34 activities). Editor access is granted to the owner's Supabase Auth account.

## Deployment

Deploy this directory as a static site (`index.html` at site root) on GitHub Pages, Vercel, or similar HTTPS host. Do not enable password protection on public itinerary pages unless you want companions to sign in.

The `sb_publishable_...` key embedded in index.html is intended for use in browser clients. Do not put Supabase secret/service-role keys in the site.

Once hosted, open the URL, check all four days and try edit using **Online itinerary** sign-in. Everyone else is read-only.

Do not click 'Publish current plan' from a browser that contains stale local edits, as it could replace the already-published itinerary. Check current online state first.

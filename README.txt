Oscar's Walk Wallet v4.0

Private household dog-walking expense tracker with optional two-phone sync via Supabase.

V4 adds:
- Shared Oscar household sync
- One-time 6-character invite code
- Safe migration of existing V3 walkers, rates, and walks
- Local safety backup before migration
- Sync status and manual Sync now
- Existing custom durations, themes, history, and backups remain

Deployment: upload all five files to the root of the GitHub Pages repository.
Do not delete the Home Screen app or clear Safari website data before migration is confirmed.

The Supabase publishable key in index.html is intentionally client-visible. Security relies on authenticated users plus Row Level Security. Never place a Supabase secret/service-role key in this project.

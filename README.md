# CRS 2026 Schedule Selector

Static CRS 2026 schedule selector with Supabase-backed team choices.

## Files

- `index.html`: deployed schedule UI.
- `crs2026_supabase_config.js`: browser-safe Supabase project URL and publishable key.

## Collaboration

Selections are stored in the Supabase table `crs_session_decisions` under:

- `event_id`: `crs2026`
- `team_code`: `default`

The page intentionally uses a no-login small-group setup. Anyone with the public page URL can write rows permitted by the Supabase RLS policies.

## Source

Generated from the local archive at:

`/Users/jungisung/Documents/CRS_2026_session_archive`

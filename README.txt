Admin Rebuild/Remove update.

1. Run admin_maintenance_schema.sql in Supabase SQL Editor.
2. Replace index.html in your GitHub repo.
3. Commit: Add admin rebuild and mission removal
4. Push.

Notes:
- Rebuild works for missions that have raw_text saved.
- Older missions without raw_text will be skipped until re-imported or edited later.
- Duplicate protection checks approved and pending missions.

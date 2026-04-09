# Nexus Academy

Middle school **life sciences, math, and ELA** as story-driven browser games—missions, XP, and one shared cadet identity across realms.

**Live site:** [https://leighrobbins-hub.github.io/nexus-academy/](https://leighrobbins-hub.github.io/nexus-academy/)

**Entry points**

- `index.html` — quick entry (redirects to Lesson 1); **`hub.html`** — life sciences course hub
- `nexus.html` — meta-hub for all three games (life sciences · math · ELA)
- **Life sciences track** (Gene Code) lives under `hub.html` and the `lesson-*.html` chapters

**Regenerate math/ELA unit HTML** (after editing `scripts/generate-realm-units.py`):

```bash
python3 scripts/generate-realm-units.py
```

**Repository:** [github.com/leighrobbins-hub/nexus-academy](https://github.com/leighrobbins-hub/nexus-academy)  
**Deploy:** GitHub Actions publishes on every push to `main` (`.github/workflows/deploy-pages.yml`).

# Porch

Meet people nearby who share your interests. A mobile-first prototype: pick interests, browse neighbors sorted by what you have in common, join small gatherings, and chat.

Migrated from the Porch artifact (https://claude.ai/artifact/QEbxt79S64N4gxjJfoDHKi).

## Run it

It's a single static page with no build step. Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Notes

- All people, gatherings, and replies are sample data defined in `index.html`.
- Onboarding state and chosen interests persist in `localStorage` under `porch-v1`.
- Light and dark themes follow the system setting.

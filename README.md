# Chilli Pepper Robotics — org site

Standalone static site for **Chilli Pepper Robotics**, the multi-team VEX V5
organization that Team 37X belongs to. Modeled on the layout of
exothermicrobotics.org (Home/About/Teams/Awards/Outreach/Gallery/Resources/Contact),
in a clean light theme that reuses the 37X pepper-red brand.

- **Separate** from the 37X sponsorship site (`../vex37`, which stays as-is).
- No build step — plain `index.html` + `css/styles.css` + a little inline JS.
- Single-page scroll with sticky anchor nav, gallery lightbox, mobile menu.

## Status: LOCAL ONLY (not published)

Per Sophie's instruction this is **kept local** — it is excluded from the
parent `darren-projects` auto-sync and has **no GitHub remote**. Nothing here
is on GitHub or live anywhere. When ready to publish, create a private repo
under `sopie-k10` and deploy via GitHub Pages (same flow as `vex37`).

## Preview locally

```
cd /home/darren/projects/team37 && python3 -m http.server 8099
# open http://localhost:8099
```

## Open items (need Sophie's input)

- **Awards total:** headline says 146, per-team counts sum to 167 — reconcile.
- **Team number:** 3760V (Sophie) vs 3740V (Lucas) for the Tulsa team; name TBD.
- **Outreach:** placeholder copy — needs real activities/events.
- **Awards section:** add specific award names (Excellence, Tournament Champions, etc.).
- **Resources:** add this season's official game-manual link.
- **Team photos:** only 37X member photos are on hand; other teams have no photos yet.

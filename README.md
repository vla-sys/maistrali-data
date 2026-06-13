# maistrali-data

Auto-published public data feed for the **Maistrali** iOS app (private source repo).

- `beaches_wind.json` — per-beach 10m wind (knots + meteorological direction) for
  ~540 Sardinian beaches, 5 forecast steps (0/12/24/36/48 h). Refreshed twice daily
  by the app's CI pipeline from the latest ICON-2I 2.2 km run.

**Attribution:** wind data derived from ICON-2I, ItaliaMeteo — Agenzia Italiana per la
Meteorologia e Climatologia (CC BY 4.0). Beach coordinates © OpenStreetMap contributors (ODbL).

Public so the app can fetch it with no credentials (zero-backend). Do not rely on its
schema externally — it tracks the app and may change without notice.

# ajansmobil/mobil — Flutter web (Render static)

Canli UI: **admin.ajansmobil.com** (Render static site)
API: **api.admin.ajansmobil.com** (Cloudflare Worker)

Build kaynagi: yunusevgane/matrixMobil — `.github/workflows/hosting.yml` push sonrasi bu repoya aktarilir.

## Render

`render.yaml` — CI build tamamlandiktan sonra static publish (SPA rewrite `/* -> /index.html`).

## DNS

- `admin.ajansmobil.com` → Render CNAME
- `api.admin.ajansmobil.com` → Cloudflare Worker (proxied)

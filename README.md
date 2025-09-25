# Blog API Cypress Tests

Singkat: kumpulan pengujian Cypress untuk API blog.

## Prasyarat
- Node.js (LTS)
- npm atau yarn

## Instalasi
1. Clone repo ke mesin Anda.
2. Jalankan:
   - npm: `npm install`
   - yarn: `yarn install`

## Menjalankan tes
- Buka UI Cypress:
  - `npx cypress open`
- Jalankan headless:
  - `npx cypress run`

## Struktur proyek (ringkasan)
- cypress/
  - integration/  — tes
  - fixtures/      — data contoh
  - plugins/       — plugin Cypress
  - support/       — helper dan konfigurasi
- package.json

## Konfigurasi
- Jika perlu set variabel lingkungan (baseUrl, API tokens), tambahkan ke `cypress.json` atau gunakan `CYPRESS_` env vars.

## Kontribusi
- Buat branch fitur, buka PR, sertakan deskripsi dan langkah reproduksi jika menambah tes baru.

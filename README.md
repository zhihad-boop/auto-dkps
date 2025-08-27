# DKPS

Repositori ini berisi sistem otomatisasi input data DKPS 

## Struktur Proyek

- `apps/web` — Frontend berbasis Next.js
- `apps/api` — Backend berbasis NestJS
- `packages/dkps-core` — Logika pemetaan dan kalkulasi DKPS Tabel 1–23
- `packages/sdk-feeder` — Konektor API PDDIKTI Feeder
- `packages/sdk-sister` — Konektor API SISTER
- `infra/docker` — Konfigurasi Docker
- `infra/env` — Contoh file environment

## Cara Menjalankan

1. Install dependensi:
```bash
pnpm install
```

2. Jalankan aplikasi:
```bash
pnpm dev
```

3. Konfigurasi environment:
Salin `.env.example` ke `.env` dan isi variabel yang diperlukan.

## Sprint 0
- [x] Setup struktur proyek
- [x] Integrasi SSO Entra ID
- [x] Konektor Feeder: discovery daftar PS SBM
- [ ] Konektor SISTER: tarik data SDM
- [ ] Dashboard awal per PS

---
Lisensi: MIT

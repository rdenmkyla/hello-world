# Rancangan Pipeline - Aplikasi Toko Online

## Trigger
- Branch: master
- Event: push dan pull_request

## 1. Source Control
Menggunakan Git dan di-hosting di GitHub.

## 2. Build
Menyiapkan environment dan menginstal dependencies (contoh: `npm install` atau `composer install`).

## 3. Test
Menjalankan unit testing otomatis (contoh: `npm test` atau `phpunit`).

## 4. Security Scanning
Memeriksa celah keamanan pada dependencies (contoh: `npm audit` atau SonarQube).

## 5. Artifact Generation
Membuat build production (contoh: `npm run build`) dan menyimpannya sebagai artifact.

## 6. Deployment
Melakukan deploy ke server staging atau production menggunakan SSH atau Docker.


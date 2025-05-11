# Jurnal Day 35 - Git Advanced Commands

## Tanggal:
11 Mei 2025

## Tujuan Hari ini:
Mempelajari dan mempraktikkan fitur-fitur Git lanjutan yang sering digunakan oleh developer profesional untuk mengatur histori commit dan alur kerja tim.

## Fitur yang dipelajari:
1. git stash
- Menyimpan perubahan yang belum di-commit agar bisa berpindah branch
- Digunakan saat perubahan belum siap untuk disimpan secara permanen

2. git cherry-pick
- Mengambil satu commit dari branch lain dan menempelkannya ke branch aktif
- Sempat terjadi konflik, namun berhasil diselesaikan (simulasi nyata)

3. git rebase
- Menempelkan commit dari branch fitur-b ke atas commit di master
- Alur commit menjadi lebih bersih dan berurutan
- Cocok untuk menjaga hisori rapi sebelum push ke GitHub

4. Git tag
- Menandai commit penting sebagai versi v1.0
- Tag sudah berhasil di push ke GitHub dan terlihat di halaman releases
- Berguna untuk menandai milestone produk

## Insight Hari ini:
- stash menyelamatkan perubahan tanpa mengganggu workflow
- cherry-pick ideal untuk memilih commit secara selektif
- rebase sangat powerful untuk menjaga histori rapi, tapi harus hati-hati jika branch sudah di-push
- tag penting dalam proses rilis dan dokumentasi proyek
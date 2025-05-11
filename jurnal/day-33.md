
# Jurnal Day 33 – Resolusi Konflik Git

Hari ini saya mempelajari dan mempraktikkan bagaimana Git menangani konflik ketika dua branch mengubah baris yang sama di file yang sama.

## 🔧 Simulasi Konflik
- Saya membuat dua branch: `master` dan `versi-a`
- Di kedua branch, saya mengubah isi file `catatan.txt` pada baris yang sama
- Saat melakukan merge `versi-a` ke `master`, Git menampilkan konflik

## 🧠 Proses Penyelesaian
- Git secara otomatis menandai bagian konflik dengan:\
<<<<<<< HEAD
>>>>>>> versi -a
- Saya mengedit file secara manual, memilih dan menggabungkan isi dari kedua versi
- Lalu melakukan `git add` dan `git commit` untuk menyimpan hasil resolusi

## 📤 Hasil Akhir
- Setelah commit hasil merge, saya melakukan `git push` ke GitHub
- Hasil file `catatan.txt` sudah bersih dari konflik dan berisi isi final sesuai keinginan

## 💡 Insight
- Git tidak bisa memilih mana isi file yang “benar” ketika konflik terjadi
- Developer harus menyelesaikan konflik secara sadar dan hati-hati
- Resolusi konflik adalah hal penting yang harus dikuasai untuk kerja kolaborasi

Saya merasa jauh lebih percaya diri dalam menggunakan Git, terutama saat menghadapi situasi konflik saat merge.

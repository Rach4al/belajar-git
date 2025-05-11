
Hari ini saya belajar tentang bagaimana Git digunakan dalam workflow developer profesional, terutama fitur penting seperti:

## Branching & Merge
- Saya belajar membuat branch baru ('fitur-catatan') menggunakan 'git checkout -b'
- Membuat perubahan di branch terpisah tanpa mempengaruhi 'main'
- menggabungkan branch ke 'main' menggunakan 'git merge'
- Menghapus branch setelah merge ('git branch -d')

## VS Code Git Integration
- Menggunakan tab source control untuk melihat perubahan file
- Menambahkan perubahan ke staging via klik +
- Commit langsung dari VS Code dengan mengetik pesan di kolom atas dan klik 'Check'
- Push ke GitHub pakai ikon di dalam VS Code

## Pelajaran Tambahan
- Git tidak otomatis commit atau push meskipun file sudah diedit
- Kalau commit dilakukan tanpa pesan, Git akan buka editor ('COMIT_EDITMSG')
- Saya mencoba konfigurasi editor:
    - 'code --wait' masih membuka tab editor
    - 'notepad' hanya muncul jika commit dilakukan dari Git Bash, bukan dari teriminal dalam VS Code

## Insight Pribadi
- VS Code jauh lebih nyaman untuk kerja harian Git, tapi penting mengerti dasar Git dari terminal
- Commit sebaiknya selalu punya pesan yang jelas dan singkat
- Push baru akan mengirim commit ke GitHub, bukan otomatis saat commit


saya merasa lebih nyaman menggunakan Git setelah paham perbedaan kerja Git Bash dan Visual Studio Code

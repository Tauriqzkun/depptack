#Panduan Perintah Git Dasar
1. git clone
Deskripsi:
Membuat salinan dari repositori jarak jauh ke mesin lokal Anda.

2. git status
Deskripsi:
Menunjukkan status saat ini dari direktori kerja dan area staging Anda.
Fungsi:

Mengindikasikan perubahan mana yang sudah ditandai, belum ditandai, atau tidak terdeteksi.

3. git add .
Deskripsi:
Menandai semua perubahan di direktori saat ini untuk komit berikutnya.

4. git commit -m "pesanperubahn"
Deskripsi:
Melakukan komit terhadap perubahan yang sudah ditandai ke repositori lokal.
Catatan:
Pastikan untuk mengganti pesanperubahn dengan deskripsi yang sesuai untuk perubahan Anda.

5. git push
Deskripsi:
Mengunggah komit lokal Anda ke repositori jarak jauh.

Mengatasi Kesalahan saat Push
Jika Anda mengalami kesalahan saat melakukan operasi push, ikuti langkah-langkah berikut:

1. git fetch
Deskripsi:
Mengambil pembaruan dari repositori jarak jauh tanpa menggabungkannya ke dalam cabang lokal Anda.

2. git merge
Deskripsi:
Menggabungkan perubahan yang diambil ke dalam cabang saat ini.
Catatan:
Selesaikan konflik yang mungkin muncul selama proses ini.

3. git push
Deskripsi:
Setelah menyelesaikan konflik dan melakukan penggabungan, coba lakukan push perubahan Anda lagi.


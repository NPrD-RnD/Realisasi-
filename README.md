# Realisasi Dinas — GitHub Pages

Aplikasi laporan realisasi dinas: nominal manual, bukti foto, kategori yang dapat dilipat, draf dengan tombol Selesai, preview, unduhan Word, dan rekening BNI/BCA opsional.

## Pasang di GitHub

1. Ekstrak ZIP ini di komputer.
2. Buat repository baru, misalnya `Realisasi-Dinas`. Untuk GitHub Free gunakan Public. Buat terpisah dari repository Project Bulanan.
3. Klik Add file → Upload files. Upload `index.html` dan `README.md` ke paling luar repository, bukan ZIP atau folder pembungkusnya. `.nojekyll` boleh ikut diupload (opsional untuk HTML ini).
4. Klik Commit changes.
5. Buka Settings → Pages. Source: Deploy from a branch. Branch: main. Folder: / (root). Klik Save.
6. Tunggu publikasi, lalu buka link yang ditampilkan pada Settings → Pages. Contoh: `https://USERNAME.github.io/Realisasi-Dinas/`.
7. Aktifkan Enforce HTTPS jika tersedia. Di iPhone buka melalui Safari, lalu Bagikan → Tambahkan ke Layar Utama.

Tidak memerlukan langganan ChatGPT, API key, server database, atau proses build. Link tetap tersedia selama GitHub Pages dan repository aktif; tidak ada jaminan layanan berlangsung selamanya.

## Data dan privasi

- Repository hanya berisi kode aplikasi. Paket ini tidak berisi pengajuan, foto pribadi, atau nomor rekening.
- Pengajuan, foto dan rekening tersimpan di IndexedDB browser masing-masing perangkat. Aplikasi tidak mengunggahnya ke GitHub atau server lain. Preview dan Word dibuat di perangkat.
- Tidak ada analytics, font dari internet, atau CDN. Kebijakan keamanan halaman memblokir koneksi jaringan dari aplikasi setelah halaman dimuat.
- GitHub tetap menerima permintaan untuk mengirim halaman web saat dibuka. Halaman aplikasinya publik, tetapi pengunjung lain yang memakai perangkat/browser lain tidak melihat data milikmu.
- Siapa pun yang memakai profil browser yang sama di perangkat yang sudah terbuka bisa melihat data. Ini bukan penyimpanan terenkripsi atau kunci aplikasi. Gunakan kunci layar, profil pribadi, dan jangan gunakan perangkat bersama untuk bukti sensitif.
- Jangan upload JSON cadangan, foto bukti, Word hasil laporan, atau data rekening ke repository publik.
- Data tidak otomatis tersinkron antar perangkat atau browser. Jangan menggunakan mode incognito untuk menyimpan data jangka panjang.
- Data browser bisa hilang jika dibersihkan atau penyimpanan browser dihapus. Unduh cadangan secara berkala dan simpan secara pribadi.

## Pindahkan data dari HTML/link sebelumnya

Pada aplikasi lama, buka setiap pengajuan → Unduh cadangan. Pada link GitHub baru, buat pengajuan → Pulihkan cadangan. Ulangi untuk pengajuan lain. Domain baru memiliki penyimpanan terpisah; data lama tidak otomatis terbawa.

## Update aplikasi

Ganti `index.html` di repository yang sama, lalu commit. Refresh setelah GitHub selesai menerbitkan. Memperbarui kode tidak menghapus data browser selama domain, nama database, dan format data tetap kompatibel. Tetap unduh cadangan sebelum memperbarui.

## Perlindungan akun

Aktifkan verifikasi dua langkah GitHub dan jangan membagikan akses edit repository. Orang lain dapat membaca kode publik, tetapi tidak dapat mengganti repository tanpa izin. Kode yang diedit oleh seseorang yang memiliki akses bisa membaca data lokal saat dijalankan, sehingga akses edit perlu dijaga.

# My Rologo

Portal statis untuk mengakses dan mengunduh seluruh aset identitas visual resmi SMKN 12 Surabaya. Semua logo sekolah, jurusan, ekstrakurikuler, hingga event dikurasi dalam antarmuka yang ringan, responsif, serta mudah dipelihara.

## Fitur
- **Katalog terstruktur** – logo dibagi ke empat kategori utama: sekolah, jurusan, event, dan ekstrakurikuler.
- **Pencarian dan filter real-time** – temukan logo berdasarkan kata kunci atau kategori tanpa memuat ulang halaman.
- **Koleksi aset lengkap** – setiap logo dapat diunduh dalam beberapa format (PNG/SVG/PDF) lengkap dengan deskripsinya.
- **Tema terang/gelap** – saklar mode tema dengan preferensi tersimpan di `localStorage`.
- **Navigasi cepat** – tombol pill untuk lompat ke setiap kategori serta navigasi burger pada perangkat mobile.
- **Form kontribusi** – ajakan submit logo baru terhubung langsung ke Google Form.

## Teknologi
- HTML5 semantik dengan struktur konten yang jelas.
- CSS modern (custom properties, grid/flexbox) untuk styling responsif.
- JavaScript vanilla (`js/app.js`) untuk data katalog, pencarian, filter, toggle tema, dan interaksi UI lainnya.

## Struktur Proyek
```
MyRologo/
├── assets/             # Logo dan media pendukung
├── css/
│   └── style.css       # Styling utama termasuk mode gelap & responsif
├── js/
│   └── app.js          # Data katalog & logika interaksi
├── index.html          # Halaman utama
└── README.md
```

## Cara Menjalankan
1. Clone atau download repository ini.
2. Buka `index.html` langsung di browser favorit Anda.
3. Seluruh fitur berjalan di lingkungan statis, tidak diperlukan server atau build tools.

## Kustomisasi Data Logo
- Seluruh daftar logo berada di `js/app.js` pada objek `catalogSource` dan `schoolLogos`.
- Tambahkan entri baru dengan struktur yang sama (id, name, description, path file, dll.).
- Sertakan aset fisiknya di folder `assets/` sesuai jalur yang digunakan.

## Kontribusi Logo
Jika memiliki logo resmi SMKN 12 Surabaya yang belum ada di portal, silakan unggah melalui tautan Google Form pada bagian bawah halaman utama. Pastikan file berkualitas tinggi dan sudah terverifikasi.


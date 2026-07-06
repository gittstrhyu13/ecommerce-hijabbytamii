# HijabByTami - Pashmina Mini Premium E-Commerce 🛒✨

Mata kuliah/Project Web Bisnis: **E-Commerce Sederhana HijabByTami**  
Platform: **Mobile-First Responsive Web Catalog**  
Status: **Production / Live**

---

## 📌 Tentang Proyek
**HijabByTami** adalah sebuah platform katalog *e-commerce* interaktif yang dirancang khusus dengan pendekatan *mobile-first view* (maksimal lebar layar 480px) untuk memberikan pengalaman belanja yang intim dan estetik layaknya aplikasi *native* di *smartphone*. 

Aplikasi ini berfokus pada penjualan produk **Pashmina Mini Premium (Pashmini)** dengan visual bertema *Earth Tone* hangat yang ramah pengguna. Pelanggan dapat menjelajahi koleksi, menyaring varian warna, mengelola keranjang belanja secara *real-time*, hingga melakukan *checkout* otomatis langsung terintegrasi ke sistem data lokal maupun via WhatsApp API.

---

## ✨ Fitur Utama
Aplikasi ini dilengkapi dengan berbagai fitur interaktif berbasis **Client-Side JavaScript**:

*   **Shopping Cart System (Real-Time):** Menambah, menghitung subtotal, dan menghapus item dari keranjang belanja secara dinamis tanpa *reload* halaman.
*   **Shopee-Style Stock Validation:** Pembatasan input jumlah beli berdasarkan sisa stok riil masing-masing produk demi mencegah *over-ordering*.
*   **Color Category Filter:** Menyaring produk berdasarkan rumpun warna secara instan (*All*, *Bright/Pastels*, dan *Earth Tones/Dark*).
*   **Smart Search:** Fitur pencarian produk berbasis pelacakan kata kunci (*keyword live-tracking*).
*   **Dual Checkout System:** 
    1.  *Direct Local Checkout:* Simulasi validasi formulir alamat dan konfirmasi metode pembayaran (COD / Transfer Bank) langsung di dalam web.
    2.  *WhatsApp Checkout API:* Mengonversi isi keranjang belanja dan data pengiriman pembeli menjadi format teks rapi (*ordered text template*) yang otomatis terkirim ke WhatsApp Admin.
*   **Interactive Modal & Sidebars:** Menu filter warna di sidebar kiri, keranjang belanja di sidebar kanan, dan pop-up Visi-Misi toko yang interaktif.
*   **Product Video Integration:** Menyediakan *section* khusus untuk menyematkan video detail ulasan atau bahan produk (*review product room*).

---

## 🎨 Spesifikasi Desain & Estetika
Aplikasi ini menerapkan palet warna bertema **Soft Earth Tone & Nude Warm** untuk menonjolkan kesan anggun, bersih, dan estetik:
*   **Background Utama:** `#fcfaf7` (Krim sangat muda)
*   **Header & Aksen Ringan:** `#f5ebe0` & `#e3d5ca` (Nude Beige)
*   **Warna Primer / Teks / Tombol:** `#4a3f35` (Cokelat gelap elegan)
*   **Aksen Warna Sekunder:** `#a98467` & `#d5bdaf` (Taupe / Clay)
*   **Tipografi:** *Poppins* (Google Fonts) untuk memberikan kesan modern dan scannable.
*   **Ikonografi:** *FontAwesome v6.4.0* untuk elemen visual yang presisi.

---

## 🛠️ Teknologi yang Digunakan
Proyek ini dibangun secara mandiri menggunakan teknologi *Front-End* murni tanpa memerlukan kompilasi (*Zero-Build Stack*):
1.  **HTML5:** Untuk penataan struktur semantik dokumen web.
2.  **CSS3:** Kustomisasi tata letak menggunakan metode *Flexbox*, *CSS Grid*, *Sticky Navigation*, serta *Radial Gradient Custom Wave Pattern* pada komponen hero banner.
3.  **Vanilla JavaScript (ES6):** Logika manipulasi DOM (*Document Object Model*), kalkulasi array keranjang belanja (`.reduce()`, `.find()`, `.splice()`), manajemen *state* filter, serta enkripsi string URI untuk integrasi WhatsApp API.

---

## 📁 Struktur Berkas
```text
ecommerc-sederhana-gitaa/
│
├── README.md            # Dokumentasi proyek (File ini)
├── index.html           # File utama (Struktur, Gaya CSS, & Logika JS)
├── logo.jpeg            # Aset gambar logo brand HijabByTami
├── produk.mp4           # Aset video ulasan/detail bahan produk
│
└── gambar/              # Direktori aset gambar produk (Varian Warna)
    ├── gambar1.jpeg     # Pashmina Mini - Soft Pink
    ├── gambar2.jpeg     # Pashmina Mini - Taupe
    ├── gambar3.jpeg     # Pashmina Mini - Mauve
    ├── gambar4.jpeg     # Pashmina Mini - Deep Navy
    ├── gambar5.jpeg     # Pashmina Mini - Mahogany
    ├── gambar6.jpeg     # Pashmina Mini - Hazelnut
    ├── gambar7.jpeg     # Pashmina Mini - Burgundy
    └── gambar8.jpeg     # Pashmina Mini - Oat Milk# ecommerce-hijabbytamii

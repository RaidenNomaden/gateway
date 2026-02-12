# 💳 Website Payment QRIS dengan Dashboard Admin

Website pembayaran QRIS lengkap dengan dashboard admin untuk mengelola testimoni dan transaksi.

## ✨ Fitur Utama

### 🎯 Halaman Payment (`payment.html`)
- ✅ QR Code QRIS dinamis
- 💰 Input jumlah pembayaran (opsional)
- 📱 Konfirmasi pembayaran via WhatsApp
- 💾 Download, Print, dan Share QR Code
- ⭐ Form testimoni dengan rating
- 📱 Responsive mobile-friendly design
- 🎨 Design mirip dengan gambar referensi

### 📊 Dashboard Admin (`dashboard.html`)
- 📈 Statistik real-time:
  - Total testimoni
  - Rating rata-rata
  - Pembayaran bulan ini
  - Total pendapatan
- 📊 Charts & Analytics:
  - Distribusi rating
  - Grafik testimoni per bulan
- 🔍 Filter dan pencarian testimoni
- 📥 Export testimoni ke CSV
- ⚙️ Pengaturan QRIS (Nama toko, NMID, Terminal ID, WhatsApp)
- 🗑️ Hapus testimoni
- 📱 Responsive untuk semua device

## 🚀 Cara Menggunakan

### 1. Setup Awal
```bash
# Tidak perlu instalasi tambahan
# Cukup buka file HTML di browser
```

### 2. Halaman Payment
1. Buka `payment.html` di browser
2. Customer dapat:
   - Scan QR Code menggunakan aplikasi pembayaran (GoPay, OVO, Dana, dll)
   - Input jumlah pembayaran (opsional)
   - Klik "Konfirmasi Bayar" untuk konfirmasi via WhatsApp
   - Download/Print/Share QR Code
   - Memberikan testimoni dengan rating bintang

### 3. Dashboard Admin
1. Buka `dashboard.html` di browser
2. Lihat statistik dan analytics
3. Kelola testimoni:
   - Filter berdasarkan rating
   - Cari testimoni
   - Export ke CSV
   - Hapus testimoni
4. Atur pengaturan QRIS di menu Settings

## 📁 Struktur File

```
├── payment.html      # Halaman pembayaran untuk customer
├── dashboard.html    # Dashboard admin
└── README.md        # Dokumentasi (file ini)
```

## 🎨 Fitur Design

### Payment Page
- QR Code QRIS dengan logo GPN
- Informasi toko (Nama, NMID, Terminal ID)
- Tombol aksi (Download, Print, Share)
- Form testimoni dengan rating interaktif
- Design card yang clean dan modern
- Support untuk print QR Code

### Dashboard
- Sidebar navigasi dengan 4 menu utama
- Stats cards dengan icon dan warna berbeda
- Charts interaktif menggunakan Chart.js
- Table untuk data pembayaran
- Filter dan search functionality
- Export data ke CSV

## 🔧 Kustomisasi

### Mengubah Informasi Toko
Di `dashboard.html`, menu Settings:
- Nama Toko
- NMID
- Terminal ID
- Nomor WhatsApp

### Mengubah Warna Theme
Edit di file HTML bagian Tailwind classes:
```html
<!-- Contoh: Ubah warna primary dari blue ke purple -->
bg-blue-600  →  bg-purple-600
text-blue-600  →  text-purple-600
```

## 💾 Data Storage

- Testimoni disimpan di `localStorage` browser
- Data persisten selama cache browser tidak dihapus
- Untuk production, disarankan gunakan database (MySQL, MongoDB, dll)

## 📱 Support Browser

- ✅ Chrome (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🔐 Keamanan untuk Production

Jika ingin deploy ke production:

1. **Gunakan Backend Server**
   - Node.js + Express
   - PHP + Laravel
   - Python + Django/Flask

2. **Database**
   - MySQL
   - PostgreSQL
   - MongoDB

3. **Authentication**
   - Login system untuk admin
   - JWT tokens
   - Session management

4. **HTTPS**
   - SSL certificate
   - Secure connection

## 📝 TODO / Improvement Ideas

- [ ] Integration dengan Payment Gateway
- [ ] Real-time notifications
- [ ] Email notifications
- [ ] SMS notifications
- [ ] Multi-user support
- [ ] Role-based access control
- [ ] Advanced analytics
- [ ] PDF invoice generation
- [ ] Webhook integration
- [ ] API endpoints

## 🎯 Use Cases

1. **Toko Online** - Payment gateway dengan testimoni
2. **Warung/Kedai** - Pembayaran QRIS dengan feedback
3. **Freelancer** - Invoice pembayaran dengan rating
4. **Event Organizer** - Ticketing dengan review
5. **Restoran** - Payment + customer review

## 📞 Support

Jika ada pertanyaan atau butuh bantuan:
- Email: support@cloudexis.com
- WhatsApp: +62 812-3456-7890

## 📄 License

Free to use and modify untuk personal dan commercial projects.

---

**Dibuat dengan ❤️ menggunakan:**
- HTML5
- Tailwind CSS
- JavaScript
- Chart.js
- Font Awesome
- QRCode.js

**Versi:** 1.0.0  
**Last Updated:** February 12, 2026

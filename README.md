# Prioritix 🚀

**Prioritix** adalah aplikasi pengurusan tugasan (Task Management App) pintar yang direka untuk meningkatkan produktiviti harian anda. Dibina dengan **MERN/PERN Stack** moden, ia membantu anda mengatur keutamaan, menjejak kemajuan, dan mencapai matlamat dengan lebih efisien.

![Prioritix Banner](client/public/assets/landing/hero.png)
*(Nota: Pastikan path gambar ini betul setelah di-push ke GitHub)*

## ✨ Ciri-Ciri Utama

* **📊 Dashboard Pintar:** Gambaran ringkas tugasan harian dan statistik produktiviti.
* **📥 Inbox:** Tempat pengumpulan idea dan tugasan pantas sebelum disusan.
* **📅 Today & Upcoming:** Fokus pada apa yang perlu dibuat hari ini dan rancang masa depan.
* **⭐ Starred Tasks:** Akses pantas ke tugasan berprioriti tinggi.
* **📈 Analitik:** Visualisasi data untuk melihat prestasi kerja anda.
* **🔒 Authentication:** Sistem Log Masuk/Daftar yang selamat menggunakan JWT.

## 🛠️ Teknologi yang Digunakan

**Frontend (Client):**
* React.js (Vite)
* TypeScript
* Tailwind CSS (Styling)
* Lucide React (Icons)
* Axios (API Consumption)

**Backend (Server):**
* Node.js & Express.js
* Sequelize ORM
* MySQL / PostgreSQL (Database)
* JSON Web Token (JWT Auth)

---

## 🚀 Panduan Pemasangan (Installation)

Ikuti langkah ini untuk menjalankan projek di komputer anda (Localhost).

### Prasyarat
* Node.js (v18+)
* MySQL atau PostgreSQL Database

### 1. Setup Backend (Server)

```bash
# Masuk ke folder server
cd server

# Install dependencies
npm install

# Setup Environment Variables
# Salin fail .env.example (jika ada) atau buat fail .env baru:
# PORT=5000
# DB_HOST=localhost
# DB_USER=root
# DB_PASS=password_anda
# DB_NAME=prioritix_db
# JWT_SECRET=rahsia_kunci_anda

# Jalankan server
npm run dev

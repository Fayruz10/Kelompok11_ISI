# UMKM:Sistem Cerdas Monitoring Penjualan UMKM Toko Sembako dengan Teknologi Terintegrasi

---

## Mata Kuliah
*Interkoneksi Sistem Instrumentasi* 
Dosen Pengampu: Ahmad Radhy, S.Si., M.Si

---

## Anggota Kelompok

1. Dina Nur Shadrina / 2042231026
2. Muhammad Fayruz Zamzamy / 2042231032
3. Raditya Wahyu Prasetyo / 2042231034

---

## Tujuan Proyek
1.	Membangun sistem monitoring data penjualan berbasis pencatatan transaksi digital.
2.	Mengembangkan sistem penyimpanan data real-time menggunakan InfluxDB sebagai database time-series.
3.	Menyediakan dashboard interaktif berbasis Grafana untuk memantau dan menganalisis performa penjualan.
4.	Mengintegrasikan blockchain sebagai sistem pencatatan yang transparan dan tidak dapat dimanipulasi guna meningkatkan kepercayaan terhadap data penjualan UMKM.


---

## Komponen dan Aplikasi yang digunakan
- Sensor Suhu dan Kelembaban SHT20
- Modbus RTU (Remote Terminal Unit)
- TCP/IP dan TCP Server
- InfluxDB
- Grafana
- Qt Framework
- Web3
  
---

## Alur Kerja Sistem
1. Terminal 1: Jalankan npx hardhat node. Biarkan berjalan.
2. Terminal 2: Jalankan npx hardhat run scripts/deploy.js --network localhost. Skrip ini akan men-deploy kontrak baru dan secara otomatis memperbarui file .env di proyek Rust.
3. Terminal 3: Jalankan cargo run. Aplikasi Rust akan membaca konfigurasi terbaru dari .env dan langsung terhubung ke kontrak yang benar tanpa perlu copy-paste manual.

---

## Lampiran 
- Laporan :
- PPT :

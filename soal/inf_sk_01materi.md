# 🖥️ **BAB 4 Sistem Komputer**
## **A – Komputer dan Komponen Penyusunnya**

---

### **1. Pengertian dan Fungsi Komputer**

Komputer adalah perangkat elektronik yang dapat menerima input, memproses data sesuai instruksi, menyimpan data, dan menghasilkan output dalam bentuk informasi.
Komputer bekerja melalui **tiga komponen utama**:

1. **Perangkat keras (Hardware)** – bagian fisik komputer seperti prosesor, RAM, dan GPU.
2. **Perangkat lunak (Software)** – sistem operasi dan aplikasi yang mengatur serta memberi instruksi pada hardware.
3. **Brainware (Pengguna)** – manusia yang menggunakan, memprogram, dan mengelola sistem komputer.

Ketiganya saling terhubung membentuk **sistem komputer yang utuh**, di mana tidak ada satu pun yang dapat berfungsi sendiri.

---

### **2. Perangkat Keras (Hardware)**

Perangkat keras mengalami evolusi luar biasa dalam satu dekade terakhir (2015–2025). Berikut penjelasan setiap komponen utama dengan perkembangan teknologinya.

---

#### 🧠 **A. Central Processing Unit (CPU)**

CPU adalah **otak komputer** yang mengeksekusi instruksi dari perangkat lunak.

**Evolusi CPU (2015–2025)**

| Tahun | Contoh Model         | Arsitektur          | Core        | Catatan                     |
| ----- | -------------------- | ------------------- | ----------- | --------------------------- |
| 2015  | Intel Core i7-6700K  | Skylake (14nm)      | 4           | Era awal 4-core mainstream  |
| 2017  | AMD Ryzen 7 1700     | Zen (14nm)          | 8           | AMD kembali kompetitif      |
| 2020  | Intel Core i9-10900K | Comet Lake          | 10          | Meningkat jumlah core       |
| 2022  | AMD Ryzen 9 7950X    | Zen 4 (5nm)         | 16          | Support DDR5, PCIe 5.0      |
| 2024  | Intel Core i9-14900K | Raptor Lake Refresh | 24 (8P+16E) | Hybrid Architecture         |
| 2025  | AMD Ryzen 9 9950X    | Zen 5 (4nm)         | 16          | Efisiensi dan IPC meningkat |

**Konsep Penting:**

* **Clock Speed (GHz):** Menunjukkan kecepatan instruksi dieksekusi (lebih tinggi = lebih cepat).
* **Core & Thread:** Core = unit pemrosesan independen; Thread = jalur eksekusi simultan.
* **Arsitektur Hybrid (Intel Alder/Raptor Lake):** kombinasi *Performance Core* (P-core) dan *Efficient Core* (E-core).
* **Socket:** Antarmuka fisik antara CPU dan motherboard (misal: Intel LGA1700, AMD AM5).

**Contoh CPU Modern (2025):**

* **Intel Core i9-14900K** – 24 core, 32 thread, 6.0 GHz, LGA1700, TDP 125W
* **AMD Ryzen 9 9950X** – 16 core, 32 thread, AM5, DDR5 only, efisien daya tinggi
* **Apple M3 Max** – SoC berbasis ARM dengan CPU 16-core dan GPU 40-core terintegrasi

**Catatan:**
Arsitektur **x86** digunakan oleh Intel dan AMD; sedangkan **ARM** digunakan oleh Apple dan sebagian besar perangkat mobile.

---

#### 💾 **B. Memori Utama (RAM)**

RAM (*Random Access Memory*) adalah memori sementara yang menyimpan data yang sedang digunakan CPU. RAM berpengaruh langsung pada **multitasking dan kecepatan sistem.**

**Perkembangan RAM (2015–2025)**

| Generasi | Tahun Rilis | Kecepatan Umum | Tegangan | Keterangan                             |
| -------- | ----------- | -------------- | -------- | -------------------------------------- |
| DDR3     | s.d. 2016   | 1600–2400 MHz  | 1.5V     | Digantikan DDR4                        |
| DDR4     | 2016–2021   | 2133–3600 MHz  | 1.2V     | Umum di PC/laptop                      |
| DDR5     | 2022–2025   | 4800–8000 MHz  | 1.1V     | Bandwidth tinggi, efisiensi lebih baik |

**Contoh RAM Nyata (2025):**

* *Corsair Vengeance DDR5 6000 MHz 32GB (2×16)*
* *Kingston Fury Beast DDR5 7200 MHz 64GB (2×32)*
* *G.Skill Trident Z5 RGB DDR5 7600 MHz 32GB*

**Perbandingan:**

* DDR5 memiliki bandwidth dua kali DDR4.
* Namun, latensi (waktu tunggu) DDR5 sedikit lebih tinggi pada generasi awal.
* Slot DDR4 dan DDR5 **tidak kompatibel** fisik maupun elektrik.

---

#### 💽 **C. Penyimpanan (Storage)**

Berfungsi menyimpan data, sistem operasi, dan aplikasi. Ada dua tipe utama:

1. **HDD (Hard Disk Drive)** – berbasis piringan magnetik, murah, kapasitas besar, kecepatan rendah (~150 MB/s).
2. **SSD (Solid State Drive)** – berbasis chip NAND, lebih cepat, tanpa suara, lebih tahan guncangan.

**Evolusi SSD:**

| Generasi              | Interface        | Kecepatan Baca | Contoh Model                    |
| --------------------- | ---------------- | -------------- | ------------------------------- |
| SATA SSD (2015)       | SATA III (6Gbps) | ~550 MB/s      | Samsung 850 EVO                 |
| NVMe Gen3 (2018)      | PCIe 3.0 ×4      | ~3500 MB/s     | WD Black SN750                  |
| NVMe Gen4 (2022)      | PCIe 4.0 ×4      | ~7400 MB/s     | Samsung 990 Pro                 |
| NVMe Gen5 (2024–2025) | PCIe 5.0 ×4      | ~12400 MB/s    | Crucial T700, Corsair MP700 Pro |

**Kesimpulan:**
NVMe Gen5 adalah generasi terkini dengan kecepatan 20× lipat dari HDD.
Namun, HDD masih relevan untuk penyimpanan arsip dan server data besar.

---

#### 🎮 **D. Kartu Grafis (GPU)**

GPU mengolah gambar, video, dan simulasi. Kini juga digunakan untuk **AI dan Deep Learning**.

**Perkembangan GPU (2015–2025)**

| Tahun | Contoh Model          | VRAM         | Arsitektur           | Catatan                          |
| ----- | --------------------- | ------------ | -------------------- | -------------------------------- |
| 2015  | GTX 980 Ti            | 6 GB GDDR5   | Maxwell              | Awal era gaming 4K               |
| 2018  | RTX 2080 Ti           | 11 GB GDDR6  | Turing               | AI & Ray Tracing pertama         |
| 2020  | RTX 3090              | 24 GB GDDR6X | Ampere               | Komputasi AI meluas              |
| 2022  | RTX 4090              | 24 GB GDDR6X | Ada Lovelace         | Lonjakan performa besar          |
| 2025  | RTX 5090              | 32 GB GDDR7  | Ada Lovelace Refresh | Efisiensi daya + performa tinggi |
| 2025  | AMD Radeon RX 8900 XT | 24 GB GDDR6  | RDNA 4               | Kompetitor high-end NVIDIA       |

GPU modern seperti RTX 5090 memiliki daya 450W dan memerlukan PSU minimal 850–1000W.

---

#### ⚙️ **E. Motherboard**

Motherboard adalah papan sirkuit utama yang menghubungkan semua komponen.

**Fitur Modern (2015–2025):**

* Dukungan **PCIe 5.0** (kecepatan 64 GB/s)
* Dukungan **DDR5 RAM**
* **Wi-Fi 7 dan Bluetooth 5.3**
* Slot **M.2 NVMe Gen4/Gen5**

**Contoh Model:**

* *ASUS ROG Strix Z790-E Gaming WiFi* (Intel, LGA1700)
* *MSI X670E Tomahawk WiFi* (AMD, AM5)

---

#### 🔌 **F. Power Supply Unit (PSU)**

PSU mengubah **arus AC (listrik rumah)** menjadi **DC (untuk komponen komputer)**.
Kualitas PSU menentukan kestabilan dan umur perangkat.

**Sertifikasi Efisiensi (80 Plus):**

| Level    | Efisiensi | Contoh Model                  |
| -------- | --------- | ----------------------------- |
| Bronze   | 82–85%    | Cooler Master MWE Bronze 650W |
| Gold     | 87–90%    | Corsair RM850x                |
| Platinum | 90–92%    | EVGA SuperNova P1000          |
| Titanium | 94–96%    | Seasonic PRIME TX-1000        |

---

#### ❄️ **G. Sistem Pendinginan**

Fungsi: menjaga suhu CPU/GPU tetap aman.

Jenis pendingin:

* **Air Cooling:** kipas dan heatsink, contoh *Cooler Master Hyper 212 EVO*.
* **Liquid Cooling (AIO):** pendingin cair tertutup, contoh *NZXT Kraken Elite 360 RGB*.

---

#### 🧩 **H. Casing dan Estetika**

Casing berfungsi melindungi komponen dan mendukung aliran udara.
Contoh: *Lian Li O11 Dynamic EVO XL* mendukung pendinginan cair, GPU besar, dan panel kaca RGB.

---

#### 🧍‍♂️ **I. Perangkat Input & Output**

**Perangkat Input:**

* Keyboard (*Logitech MX Keys S*)
* Mouse (*Razer Basilisk V3 Pro*)
* Webcam (*Logitech Brio 4K*)
* Scanner (*Epson Perfection V39 II*)

**Perangkat Output:**

* Monitor (*ASUS ProArt Display PA32UCX 4K HDR Mini-LED*)
* Printer (*Canon PIXMA G7070*)
* Speaker (*Edifier R1700BTs*)

---

### **3. Jenis Komputer Berdasarkan Fungsi**

| Jenis           | Contoh                               | Fungsi Utama                 |
| --------------- | ------------------------------------ | ---------------------------- |
| Superkomputer   | IBM Summit, NVIDIA DGX GH200         | Simulasi ilmiah, AI besar    |
| Mainframe       | IBM z16                              | Transaksi dan database besar |
| Server          | Dell PowerEdge R760                  | Layanan jaringan dan web     |
| PC / Desktop    | HP Omen 45L                          | Komputasi personal           |
| Laptop          | MacBook Pro M3, ASUS ZenBook 14 OLED | Portabilitas tinggi          |
| Embedded System | Raspberry Pi 5                       | Otomasi, IoT, robotika       |
---

### **4. Brainware dan Software**

Sebuah sistem komputer tidak hanya terdiri dari perangkat keras (hardware), tetapi juga melibatkan **perangkat lunak (software)** dan **manusia (brainware)** yang berperan penting agar komputer dapat berfungsi sesuai tujuan.

---

#### **A. Brainware**

**Brainware** adalah manusia yang menggunakan, mengoperasikan, atau mengembangkan sistem komputer. Tanpa brainware, perangkat keras dan lunak hanyalah alat pasif.

**Kategori Brainware**

1. **Operator**

   * Bertugas menjalankan aplikasi dan perangkat komputer untuk kebutuhan sehari-hari.
   * Contoh: Pegawai administrasi yang menggunakan Microsoft Excel, pelajar yang menggunakan Canva, atau kasir yang mengoperasikan POS system.
2. **Teknisi**

   * Memelihara dan memperbaiki sistem komputer, baik dari sisi perangkat keras maupun perangkat lunak.
   * Contoh: IT Support, Network Administrator.
3. **Programmer / Developer**

   * Membuat dan mengembangkan aplikasi serta sistem operasi.
   * Contoh: Pengembang Android Studio, Python Developer, Web Developer.
4. **System Analyst**

   * Merancang alur dan struktur sistem komputer dalam suatu organisasi agar efisien.
   * Contoh: Perancang sistem ERP di perusahaan.
5. **Administrator**

   * Mengatur hak akses, keamanan, dan konfigurasi sistem komputer.
   * Contoh: Database Administrator, Cloud System Administrator.

**Peran Brainware dalam 10 Tahun Terakhir (2015–2025)**

| Tahun     | Perkembangan                                                              | Dampak pada Brainware                                                   |
| --------- | ------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| 2015      | Munculnya komputasi awan (cloud computing)                                | Brainware mulai belajar manajemen cloud seperti AWS, Azure              |
| 2018      | AI dan Big Data berkembang pesat                                          | Muncul profesi *Data Scientist* dan *Machine Learning Engineer*         |
| 2020      | Pandemi COVID-19 mempercepat transformasi digital                         | Penggunaan platform kolaborasi daring (Zoom, Teams) meningkat           |
| 2023–2025 | Integrasi AI dalam sistem operasi (Windows Copilot, macOS AI Integration) | Brainware harus mampu bekerja dengan sistem berbasis AI dan otomatisasi |

---

#### **B. Software**

**Software** adalah sekumpulan instruksi (program) yang mengatur cara kerja komputer agar dapat melakukan tugas tertentu. Tanpa software, perangkat keras tidak akan berguna.

**1. Jenis Perangkat Lunak**

| Jenis                                         | Deskripsi                                                                                        | Contoh (2015–2025)                                                                                |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------- |
| **Sistem Operasi (Operating System)**         | Mengatur seluruh sumber daya komputer dan menjadi penghubung antara pengguna dan perangkat keras | Windows 10 (2015), Windows 11 (2021), macOS Sonoma (2024), Ubuntu 24.04 LTS, Android 14, iOS 18   |
| **Aplikasi (Application Software)**           | Program untuk menjalankan tugas tertentu sesuai kebutuhan pengguna                               | Microsoft Office 365, AutoCAD 2025, Adobe Photoshop 2024, Blender 4.2, ChatGPT Desktop App (2024) |
| **Bahasa Pemrograman (Programming Software)** | Alat bagi pengembang untuk menulis dan menguji kode program                                      | Python 3.12, Java 21, C# .NET 8, Visual Studio Code, JetBrains IntelliJ                           |
| **Utility Software**                          | Program tambahan untuk pemeliharaan sistem                                                       | CCleaner, BitDefender, WinRAR, Driver Booster, MSI Afterburner                                    |

**2. Evolusi Sistem Operasi dan Aplikasi (2015–2025)**

| Tahun | OS/Software Unggulan | Inovasi Utama                                       |
| ----- | -------------------- | --------------------------------------------------- |
| 2015  | Windows 10           | Unified platform antara PC dan tablet               |
| 2017  | macOS High Sierra    | Penggunaan sistem file APFS                         |
| 2019  | Ubuntu 19.10         | Optimalisasi kernel untuk AI workloads              |
| 2021  | Windows 11           | Integrasi Microsoft Teams, dukungan WSL2            |
| 2023  | macOS Sonoma         | Optimalisasi grafis Metal 3                         |
| 2025  | Windows 12 (preview) | AI Copilot native, sistem keamanan berbasis TPM 3.0 |

**3. Hubungan Software dan Hardware**

Software tidak dapat dijalankan tanpa dukungan hardware tertentu. Misalnya:

* *Adobe Premiere Pro 2025* memerlukan GPU minimal *NVIDIA RTX 4060 atau Apple M3 GPU* agar proses rendering video berjalan lancar.
* *Windows 11* membutuhkan TPM 2.0, Secure Boot, dan prosesor minimal *Intel Gen 8*.
* *Android Studio 2025* lebih optimal dengan RAM 16 GB dan SSD NVMe.

---

### **5. Hubungan Antar Komponen Sistem Komputer**

Sistem komputer bekerja secara **terpadu**. Setiap komponen — hardware, software, dan brainware — memiliki fungsi saling melengkapi.

---

#### **A. Skema Interaksi Komponen**

```
[Brainware] ⇄ [Software] ⇄ [Hardware]
```

1. **Brainware (manusia)** memberi perintah ke software (misalnya, membuka dokumen Word).
2. **Software (Word)** menerjemahkan perintah tersebut ke bentuk instruksi digital.
3. **Hardware (CPU, RAM, Storage)** mengeksekusi instruksi untuk menampilkan hasil di layar monitor.

---

#### **B. Alur Kerja Sistem Komputer**

| Tahapan      | Komponen Utama               | Contoh Kasus Nyata                    |
| ------------ | ---------------------------- | ------------------------------------- |
| **Input**    | Keyboard, Mouse, Touchscreen | Pengguna mengetik dokumen             |
| **Process**  | CPU, GPU, RAM                | CPU mengolah teks dan menata format   |
| **Storage**  | SSD, HDD                     | Dokumen disimpan dalam folder         |
| **Output**   | Monitor, Printer, Speaker    | Hasil ditampilkan atau dicetak        |
| **Feedback** | User Interaction             | Pengguna mengedit atau menghapus file |

---

#### **C. Analisis Hubungan Kinerja Antar Komponen**

1. **CPU dan RAM**

   * CPU yang cepat akan sia-sia tanpa RAM yang memadai.
   * Contoh: *Intel i9-14900K + DDR5 8000 MHz* menghasilkan performa multitasking tinggi dibanding *Intel i7-9700K + DDR4 2666 MHz.*

2. **GPU dan Storage**

   * GPU modern memerlukan kecepatan transfer tinggi.
   * Contoh: *RTX 5090 + NVMe Gen5 SSD* mempercepat proses *texture streaming* pada game AAA 2025.

3. **Software dan Sistem Operasi**

   * Aplikasi baru sering membutuhkan sistem operasi terkini agar fitur AI atau keamanan berjalan penuh.
   * Contoh: *Windows Copilot* hanya tersedia pada *Windows 11 Build 23H2 ke atas.*

4. **Brainware dan Software**

   * Pengguna harus memiliki keterampilan agar dapat memanfaatkan software secara optimal.
   * Contoh: *Data Analyst* yang menguasai *Python Pandas* akan lebih efisien daripada pengguna yang hanya menggunakan Excel dasar.

---

#### **D. Tren Integrasi Komponen (2015–2025)**

| Tahun     | Tren Teknologi                           | Dampak pada Hubungan Komponen                                                                                                      |
| --------- | ---------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| 2015      | CPU dan GPU terpisah                     | Pengolahan grafis lebih berat, konsumsi daya tinggi                                                                                |
| 2018      | Muncul APU (Accelerated Processing Unit) | CPU dan GPU mulai terintegrasi (contoh: AMD Ryzen 5 3400G)                                                                         |
| 2020      | Chip SoC (System on Chip)                | Semua komponen inti disatukan (contoh: Apple M1)                                                                                   |
| 2023–2025 | AI-integrated architecture               | CPU, GPU, dan NPU (Neural Processing Unit) bekerja bersama untuk AI tasks (contoh: Intel Core Ultra, Apple M3, Snapdragon X Elite) |

---


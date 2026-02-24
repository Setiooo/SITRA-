# SITRA-PIP
## Sistem Integritas & Keterlacakan Bantuan Pendidikan (Program Indonesia Pintar)

> **Prototype Konseptual — Penelitian Akademik**  
> Universitas Mayjen Sungkono Mojokerto · Fakultas Ekonomi Prodi Manajemen · 2025

---

### Tentang Proyek Ini

**SITRA-PIP** adalah prototype sistem berbasis web yang dikembangkan untuk mendukung penelitian akademik berjudul:

> *"Ketimpangan Bantuan Pendidikan dan Dampaknya Terhadap Kesiapan Tenaga Kerja di Jawa Timur"*

**Oleh:** Muhammad Setio Budi  
**Program Studi:** Manajemen — Fakultas Ekonomi  
**Universitas:** Universitas Mayjen Sungkono Mojokerto  
**Tahun:** 2025

---

### Latar Belakang

Pada penyaluran Program Indonesia Pintar (PIP) Tahun 2025, dari 26.283.222 siswa yang ditandai layak, sebanyak **3.685.321 siswa** ditolak oleh sistem SiPintar akibat data yang dinilai tidak memenuhi kaidah kelengkapan, validitas, dan logika — bukan karena tidak memenuhi kriteria ekonomi.

SITRA (Sistem Integritas & Keterlacakan) diajukan sebagai solusi sistemik berbasis integritas data yang mencegah **eksklusi administratif** melalui:

1. **Decision Engine** berlapis — status Pending sebelum Reject Final
2. **Audit Trail Immutable** berstandar ISO 15489-1:2016
3. **Mekanisme Banding & Koreksi** dengan window 14 hari
4. **Integrasi Once-Only** antar Dapodik, Dukcapil, DTKS, dan Bank Penyalur

---

### Struktur Repositori

```
SITRA-PIP/
├── README.md
├── prototype/
│   ├── dashboard.html     ← Dashboard utama, Decision Engine & simulasi verifikasi
│   ├── audit.html         ← Audit Trail lengkap & log immutable ISO 15489
│   └── integrasi.html     ← Arsitektur integrasi lintas sistem once-only
├── assets/
└── docs/
    └── paper.pdf
```

---

### Cara Membuka Prototype

Semua file berdiri sendiri (self-contained HTML). Tidak memerlukan instalasi atau server.

```bash
git clone https://github.com/[username]/SITRA-PIP.git
open prototype/dashboard.html
```

Atau klik dua kali file `.html` untuk membuka langsung di browser.

---

### Halaman Prototype

| Halaman | File | Keterangan |
|---|---|---|
| Dashboard & Decision Engine | `prototype/dashboard.html` | Statistik, flow verifikasi, distribusi wilayah, simulasi engine |
| Audit Trail | `prototype/audit.html` | Log immutable, filter, detail event, simulasi pencatatan |
| Integrasi Sistem | `prototype/integrasi.html` | Arsitektur once-only, status API, flow lintas lembaga |

---

### Disclaimer

> Prototype ini dikembangkan semata-mata untuk tujuan penelitian akademik dan simulasi konseptual. Seluruh data yang ditampilkan merupakan data simulasi atau agregat yang tidak merepresentasikan data individu nyata. Prototype ini bukan sistem resmi pemerintah dan tidak terhubung dengan database instansi mana pun.

---

### Referensi Utama

- Pusat Layanan Pembiayaan Pendidikan (2024). *Laporan Statistik PIP 2024–2025.* Kemendikbudristek.
- Sen, A. (1999). *Development as Freedom.* Alfred A. Knopf.
- ISO 15489-1:2016. *Information and Documentation — Records Management.*
- Vassil, K. (2015). *Estonian e-Government Ecosystem.* World Bank Group.
- Khera, R. (2019). *Data Standards and the Digital Welfare State.* Orient BlackSwan.

---

© 2025 **Muhammad Setio Budi** — Universitas Mayjen Sungkono Mojokerto.  
Repositori ini terbuka untuk tujuan akademik. Reproduksi komersial tanpa izin tertulis tidak diperkenankan.

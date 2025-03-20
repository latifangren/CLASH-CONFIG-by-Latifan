<div align="center">
  <h1>⚡ Konfigurasi Clash BFM by Latifan ⚡</h1>
  <p>Konfigurasi Clash BFM untuk Android dengan berbagai fitur dan rule yang telah dioptimalkan</p>
</div>

## 📋 Daftar Isi
- [Instalasi](#-instalasi)
- [Cara Penggunaan](#-cara-penggunaan)
- [Fitur](#-fitur)
- [Struktur Folder](#-struktur-folder)
- [Proxy Groups](#-proxy-groups)
- [Pembaruan Provider](#-pembaruan-provider)
- [FAQ](#-faq)
- [Kredit](#-kredit)

## 🚀 Instalasi

### Persiapan Awal
1. Install BFM terlebih dahulu dari [Box For Magisk](https://github.com/taamarin/box_for_magisk)
2. Download repository ini zip file di menu CODE pilih download zip
3. Download WEB UI BFM (opsional) di [WEB UI BFM](https://github.com/latifangren/webui_bfm_Extended) INSTALL di MAGISK

## 📝 Cara Penggunaan

1. Pastikan sudah menginstall BFM , CFM dan BFR saya belum coba
2. Copy semua file ke folder Clash
3. pastikan folder sesuai ada di data/adb/box/clash/ untuk pengguna BFM
4. setting config.yaml
5. Tunggu semua provider terunduh
6. Pilih proxy group sesuai kebutuhan

### Konfigurasi Akun
1. Edit akun utama di folder `proxy_provider/`:
   - `ID.yaml` - Untuk akun Indonesia
   - `SG.yaml` - Untuk akun Singapore

### Konfigurasi Bug untuk akun vpn yang otomatis terdownload
- Ubah `bug.com` dengan bug Anda di `config.yaml`
- Cari bagian yang mengandung `bug.com` dan ganti sesuai kebutuhan

## ✨ Fitur

### Dashboard
- Menggunakan versi terbaru dari [MetaCubeX Dashboard](https://github.com/MetaCubeX/metacubexd)
- Interface yang modern dan mudah digunakan

### Provider Server
- Multi-region support:
  - 🇺🇸 United States
  - 🇸🇬 Singapore
  - 🇮🇩 Indonesia
  - 🇯🇵 Japan
  - 🇨🇳 China

### Rule Provider
| Kategori | Deskripsi |
|----------|-----------|
| Direct | Koneksi langsung tanpa proxy |
| Umum | Rule untuk penggunaan umum |
| Reject | Pemblokiran iklan dan tracker |
| Streaming | Optimasi untuk layanan streaming |
| Games | Rule khusus untuk gaming |
| Sosmed | Optimasi media sosial |
| Ewallet | Khusus aplikasi e-wallet |
| AdBlock | Pemblokiran iklan komprehensif |
| Malware | Proteksi dari malware |

### Fitur Teknis
- ✅ DNS Teroptimasi dengan fallback
- ✅ Sniffer untuk deteksi domain
- ✅ TUN mode support
- ✅ Load balance & fallback system

## 📁 Struktur Folder
├── config.yaml
├── provide/
│ ├── us.yaml
│ ├── sg.yaml
│ ├── id.yaml
│ ├── jp.yaml
│ └── china.yml
├── proxy_provider/
│ ├── ID.yaml
│ └── SG.yaml
└── rule_provider/
├── direct.yaml
├── umum.yaml
├── reject.yaml
├── streaming.yaml
├── games.yaml
├── sosmed.yaml
├── ewallet.yaml
├── china.yaml
├── china_domain.yaml
├── adblock.yaml
└── malware.yaml

## 🔄 Proxy Groups

| Group | Fungsi |
|-------|--------|
| 💳 Ewallet | Khusus e-wallet & online shop |
| 🎮 Games | Optimasi gaming dengan opsi DIRECT |
| 🎬 Streaming | Khusus layanan streaming |
| 📱 Sosmed | Khusus media sosial |
| 🔧 Manual | Pilihan server manual |
| 🔄 Auto | Fallback otomatis |
| ⚡ Best Ping | Pemilihan berdasarkan ping terbaik |
| 🇮🇩 ID-LB | Load balance server Indonesia |
| 🇸🇬 SG-LB | Load balance server Singapore |
| 🌐 GLOBAL | Traffic umum |
| 🇨🇳 CHINA | Auto-test server China |


## ⚙️ Pembaruan Provider
- Provider server: Setiap 1 jam
- Rule provider: Setiap 24 jam
- Health check: Setiap 30-60 menit

## ❓ FAQ

- Provider server diperbarui setiap 1 jam
- Rule provider diperbarui setiap 24 jam
- Health check dilakukan setiap 30-60 menit

## Catatan

- Pastikan folder yang diperlukan sudah dibuat atau sudah ada
- Jika menggunakan TUN mode, aktifkan di pengaturan
- Sesuaikan proxy group dengan kebutuhan
- Backup konfigurasi sebelum melakukan perubahan
## 🙏 Kredit
### Pembuat Konfigurasi
- [LATIFAN](https://github.com/latifangren/latifangren)

### Sumber Rule & Resources
- Rule dari [blackmatrix7](https://github.com/blackmatrix7)
- DNS dari AdGuard, Cloudflare, dan Google

---
<div align="center">
  <p>Made with ❤️ by Latifan</p>
  <p>
    <a href="https://github.com/latifangren/CLASH-CONFIG-by-Latifan/issues">Report Bug</a>
    ·
    <a href="https://github.com/latifangren/CLASH-CONFIG-by-Latifan/issues">Request Feature</a>
  </p>
</div>

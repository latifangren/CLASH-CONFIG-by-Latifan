# Konfigurasi Clash BFM

Konfigurasi Clash BFM untuk Android dengan berbagai fitur dan rule yang telah dioptimalkan.
        #### PENTING ####
## Perhatikan untuk install pertama kali
 - pastikan untuk menginstall BFM terlebih dahulu download di https://github.com/taamarin/box_for_magisk
   ## untuk BFR CFM silahkan di coba sendiri 
-  Edit akun utama kalian di proxy_provider/
   +ID.yaml dan SG.yaml di isi dengan akun kalian
-  akun di bagian provide-us, provide-sg, provide-id, provide-jp akan otomatis terdownload
-  untuk akun china akan otomatis terdownload di provide/china.yml
-  untuk rule akan otomatis terdownload di rule_provider/


## Fitur
- Dashboard untuk melihat status server sudah terinstall menggunakan versi terupdate dari https://github.com/MetaCubeX/metacubexd
- Multi-provider server dari berbagai negara (US, SG, ID, JP)
- Rule provider untuk berbagai kategori:
  - Direct
  - Umum
  - Reject
  - Streaming
  - Games
  - Sosmed
  - Ewallet
  - China
  - AdBlock
  - Malware
- DNS yang dioptimalkan dengan fallback
- Sniffer untuk deteksi domain
- TUN mode untuk kompatibilitas aplikasi
- Sistem load balance dan fallback

## Struktur Folder
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

## Proxy Groups

- **Ewallet**: Khusus untuk aplikasi e-wallet & online shop
- **Games**: Optimasi untuk gaming dengan opsi DIRECT
- **Streaming**: Khusus layanan streaming
- **Sosmed**: Khusus media sosial
- **Manual**: Pilihan server manual
- **Auto**: Fallback otomatis
- **Best Ping**: Pemilihan berdasarkan ping terbaik
- **ID-LB**: Load balance server Indonesia
- **SG-LB**: Load balance server Singapore
- **LB ID-SG**: Load balance kombinasi ID-SG
- **GLOBAL**: Pilihan untuk traffic umum
- **CHINA**: Auto-test untuk server China

## Cara Penggunaan

1. Pastikan sudah menginstall Clash Meta for Android
2. Copy semua file ke folder Clash
3. Buat folder yang diperlukan:
   - provide/
   - proxy_provider/
   - rule_provider/
4. Import config.yaml ke Clash
5. Tunggu semua provider terunduh
6. Pilih proxy group sesuai kebutuhan

## Pembaruan Provider

- Provider server diperbarui setiap 1 jam
- Rule provider diperbarui setiap 24 jam
- Health check dilakukan setiap 30-60 menit

## Catatan

- Pastikan folder yang diperlukan sudah dibuat
- Jika menggunakan TUN mode, aktifkan di pengaturan
- Sesuaikan proxy group dengan kebutuhan
- Backup konfigurasi sebelum melakukan perubahan

## Kredit
pembuat config ini LATIFAN https://github.com/latifangren/latifangren
Konfigurasi ini menggunakan:
- Rule dari blackmatrix7
- Server dari berbagai provider
- DNS dari AdGuard, Cloudflare, dan Google

# ANDINI-FEBRIANTI_105841113223_5JKA_UTS
# TUGAS BESAR – Passive & Active Reconnaissance

Repositori ini berisi seluruh dokumen, skenario, dan laporan terkait analisis **Passive** dan **Active Reconnaissance**, yang dilakukan sebagai bagian dari tugas besar mata kuliah *Ethical Hacking*. Studi kasus yang dianalisis mencakup *website pemerintah* untuk pengintaian pasif dan *VM lab rentan* untuk pengujian aktif.

## 📁 Struktur Direktori
```
/
├── DOKUMENTASI/
│   ├── PASSIVE RECONNAISSANCE/
│   └── ACTIVE RECONNAISSANCE/
├── LAPORAN/
└── SKENARIO/
```

- 📂 DOKUMENTASI  
  - ▶️ [PASSIVE RECONNAISSANCE](DOKUMENTASI/)  
  - ▶️ [ACTIVE RECONNAISSANCE](DOKUMENTASI/)  

- 📂 [LAPORAN](LAPORAN/)  
- 📂 [SKENARIO](SKENARIO/)  

## 🛡️ Gambaran Umum Proyek
### 1. Passive Reconnaissance
Dilakukan tanpa interaksi langsung pada server, meliputi:
- Pencarian subdomain (crt.sh)
- Identifikasi email & pegawai
- Pemetaan teknologi (BuiltWith)
- Pencarian informasi sensitif (GitHub Search)

### 2. Active Reconnaissance
Dilakukan pada VM lab:
- Netdiscover  
- Nmap  
- Wireshark  
- OS Fingerprinting  
- Service Enumeration  

Temuan:
- Port terbuka: **22, 80, 6667**
- Layanan usang (OpenSSH, Apache)
- Layanan IRC mencurigakan
- Kernel Linux 3.x–4.x (EOL)

## 🧰 Tools
- Kali Linux  
- Nmap  
- Netdiscover  
- Wireshark  
- crt.sh  
- BuiltWith  
- GitHub OSINT  


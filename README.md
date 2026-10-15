# 🥊 Trash Hunter

Game 2D Action-Adventure dan Edukasi Lingkungan berbasis **Godot Engine 4**.

---

## 📁 Struktur Folder Proyek (Bahasa Indonesia)

Proyek ini menggunakan struktur folder berbahasa Indonesia agar mudah dipahami dan dikembangkan secara bertahap:

```
trash-hunter/
├── adegan/                     # [Scenes] Tempat semua file tampilan/adegan (.tscn)
│   ├── kota/                   # Adegan eksplorasi kota (karakter, trotoar, gedung)
│   ├── pertarungan/            # Adegan arena pertarungan tinju (ring, monster, HP bar)
│   ├── pemilahan/              # Adegan arena pemilahan sampah (5 tong sampah & kartu sampah)
│   └── antarmuka/              # UI umum (HUD, popup edukasi, menu)
│
├── skrip/                      # [Scripts] Tempat file logika & kode GDScript (.gd)
│   ├── sistem_inti/            # Skrip global/autoload (GameManager, database sampah, suara)
│   ├── kota/                   # Logika eksplorasi kota (pergerakan pemain & patroli monster)
│   ├── pertarungan/            # Logika pertarungan (jab, hook, uppercut, dodge, AI monster)
│   └── pemilahan/              # Logika pemilahan sampah (penilaian benar/salah, poin edukasi)
│
└── aset/                       # [Assets] File visual dan audio
    ├── gambar/
    │   ├── karakter/           # Desain visual pemain
    │   ├── monster/            # Desain visual monster sampah
    │   ├── kota/               # Latar belakang kota, jalan, gedung, tiang lampu
    │   ├── sampah/             # Ikon jenis sampah (botol, kaleng, kardus, dll.)
    │   └── tong_sampah/        # Ikon tempat sampah (Organik, Plastik, Kertas, Logam, Residu)
    └── suara/                  # Efek suara pertempuran, pemilahan, dan musik
```

---

## 📌 Rencana Pengembangan Tahap 1
1. **Karakter Pemain & Pergerakan 2D** (di folder `adegan/kota/` & `skrip/kota/`)
2. **Satu Area Kota sebagai Prototipe** (di folder `adegan/kota/` & `aset/gambar/kota/`)
3. **Satu Monster Sampah Overworld** (di folder `adegan/kota/` & `aset/gambar/monster/`)
4. **Arena Pertarungan Tinju** (di folder `adegan/pertarungan/` & `skrip/pertarungan/`)
5. **Sistem HP & Kemenangan**
6. **Benda Sampah Jatuhan Monster**
7. **Mekanisme Pemilahan & Edukasi Sampah** (di folder `adegan/pemilahan/` & `skrip/pemilahan/`)

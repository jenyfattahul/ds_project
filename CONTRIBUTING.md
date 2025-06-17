# Panduan Project: `ds_project`
---
## Tujuan Proyek

---

## Struktur & Branch

Setiap orang memiliki branch masing-masing:

| Nama     | Branch         | Tugas                        |
|----------|----------------|------------------------------------|
|      | ``     |      |
|      | ``     |       |
|      | ``     |   |
|      | ``      |    |
|     | ``   |      |

---

## Cara Mulai
### 1. Clone Repositori
```bash
git clone https://github.com/jenyfattahul/ds_project.git
cd ds_project
```

### 2. Checkout ke Branch Kalian
```bash
git checkout nama-branch
```
contoh: `git checkout etl`

### 3. Update dan Push
Setelah selesai mengedit atau menambahkan file:
```bash
git add .
git commit -m "Deskripsi perubahan singkat"
git push origin nama-branch
```

---

## Integrasi ke main
Semua pekerjaan akan digabung ke branch main melalui `Pull Request` (PR):
- Buka GitHub
- Buat PR dari branch kalian ke main
- PR akan di-merge

---

## Branch main
- Jangan push langsung ke `main`
- Semua update harus melalui `Pull Request` (PR)
- `main` hanya berisi kode yang sudah stabil dan teruji

---


## Struktur Folder 'main'
```bash
ds_project/
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/                # Semua data
├── notebooks/           # Notebook EDA & modeling
├── etl/                 # Pipeline ETL
├── models/              # Model yang sudah dilatih
├── visualizations/      # Kode & hasil visualisasi
├── docs/                # Laporan akhir, logbook
├── django_project/      # Source code Django
└── deployment/          # File untuk deployment
```

---

## Tips
- Jangan commit file data besar (gunakan .gitignore)
- Update requirements.txt jika menambah library Python baru.

---


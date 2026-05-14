# 🌳 Tugas Praktek 15 — Kunjungan Pohon (Tree Traversal)

Program implementasi **Binary Search Tree (BST)** dalam bahasa C++ yang mencakup operasi penyisipan node serta tiga metode kunjungan (traversal): **Pre-Order**, **In-Order**, dan **Post-Order**.

## 📋 Deskripsi

Program ini merupakan tugas praktek mata kuliah **Struktur Data** yang mengimplementasikan konsep pohon biner pencarian (BST). Pengguna dapat menambahkan data ke dalam pohon dan melihat hasil traversal dengan tiga metode berbeda melalui menu interaktif.

## 🧠 Konsep Tree Traversal

| Metode | Urutan Kunjungan | Contoh Output (Tree: 10, 5, 15) |
|---|---|---|
| **Pre-Order** | Root → Kiri → Kanan | `10 5 15` |
| **In-Order** | Kiri → Root → Kanan | `5 10 15` |
| **Post-Order** | Kiri → Kanan → Root | `5 15 10` |

## 🗂️ Struktur File

```
SiberMu-sturktur-data-tugas-15-c/
├── main.cpp                   # Source code utama
├── kunjungan_page-0001.jpg    # Referensi tugas (halaman 1)
├── kunjungan_page-0002.jpg    # Referensi tugas (halaman 2)
├── README.md
└── LICENSE
```

## ⚙️ Cara Kompilasi & Menjalankan

### Prasyarat

- Compiler C++ (g++ / MinGW)

### Kompilasi

```bash
g++ -o main main.cpp
```

### Jalankan

```bash
./main
```

## 🖥️ Tampilan Menu Program

```
        #PROGRAM TREE C++#
        ==================
MENU
---
1. Tambah
2. Lihat pre-order
3. Lihat in-order
4. Lihat post-order
5. Exit
Pilihan :
```

## 🔧 Fitur Program

- **Tambah Data** — Menambahkan node baru ke dalam Binary Search Tree
- **Pre-Order Traversal** — Menampilkan data dengan urutan Root → Kiri → Kanan
- **In-Order Traversal** — Menampilkan data dengan urutan Kiri → Root → Kanan (terurut ascending)
- **Post-Order Traversal** — Menampilkan data dengan urutan Kiri → Kanan → Root
- **Validasi duplikat** — Program mencegah penambahan data yang sudah ada di dalam tree

## 📚 Referensi

Tugas Praktek 15 — Mata Kuliah Struktur Data

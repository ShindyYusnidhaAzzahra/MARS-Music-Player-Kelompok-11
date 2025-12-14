MARS MUSIC PLAYER: APLIKASI MUSIC PLAYER BERBASIS PYTHON (TKINTER)

Oleh kelompok 11: 
1. Ariba Raihana Alyashila 
2. Shindy Yusnidha Azzahra 
3. Retno Eka Sari

## Deskripsi Proyek
Aplikasi pemutar musik desktop sederhana yang dikembangkan menggunakan Python dan library Tkinter. Aplikasi ini mengimplementasikan konsep Struktur Data seperti Doubly Linked List untuk mengelola antrian lagu (Playlist/Queue) dan menerapkan manajemen user (Login Admin/User) untuk otentikasi fitur.

## Fitur Utama
* **Autentikasi Pengguna:** Mode login untuk Administrator dan Pengguna biasa (User).
* **Kontrol Akses:** Pengguna hanya dapat memutar lagu, sementara Admin memiliki akses penuh (tambah, hapus, kelola).
* **Manajemen Lagu (Admin Only):** Admin dapat menambahkan lagu secara manual (per file) atau memasukkan seluruh folder musik sekaligus.
* **Struktur Data:** Penggunaan Doubly Linked List untuk mengatur antrian pemutaran.
* **Auto-Load Lagu:** Aplikasi otomatis memuat lagu dari folder `music` di direktori proyek.
* **Fitur Player:** Play, Pause, Next, Previous, Shuffle, dan Pencarian.

## Cara Menjalankan Aplikasi

### Persyaratan
1.  Python 3.x
2.  Library `pygame` (untuk memutar musik).
3.  Library `mutagen` (untuk membaca metadata lagu).

### Instalasi Library
Buka Terminal/CMD di direktori proyek Anda dan jalankan perintah ini:
```bash
pip install pygame mutagen

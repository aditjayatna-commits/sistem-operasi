# Materi: Modern Operating Systems

## 1.1 Pengertian Sistem Operasi
Sistem Operasi (Operating System/OS) adalah perangkat lunak yang mengelola perangkat keras komputer dan menyediakan layanan untuk perangkat lunak aplikasi. Sistem operasi bertindak sebagai perantara antara perangkat keras komputer dan aplikasi yang berjalan pada komputer.

### Fungsi Utama Sistem Operasi:
- **Manajemen Proses**: Mengelola proses yang sedang berjalan.
- **Manajemen Memori**: Mengelola penggunaan memori fisik dan virtual.
- **Manajemen Perangkat I/O**: Mengelola perangkat input/output (keyboard, mouse, printer).
- **Manajemen Sistem Berkas**: Mengelola file, direktori, dan media penyimpanan.
- **Keamanan dan Akses**: Menjamin keamanan dan hak akses pengguna.

---

## 1.2 Jenis-Jenis Sistem Operasi
Sistem operasi dibagi menjadi beberapa jenis berdasarkan fungsinya:

- **Single-user, Single-tasking**: Sistem operasi yang hanya dapat menjalankan satu aplikasi untuk satu pengguna, seperti MS-DOS.
- **Single-user, Multi-tasking**: Sistem operasi yang memungkinkan satu pengguna menjalankan beberapa aplikasi, seperti Windows dan macOS.
- **Multi-user**: Sistem operasi yang mendukung beberapa pengguna untuk menggunakan komputer secara bersamaan, seperti Linux dan UNIX.
- **Real-time Operating System (RTOS)**: Sistem operasi yang digunakan untuk aplikasi yang membutuhkan respon cepat, seperti pada perangkat embedded.

---

## 1.3 Komponen Sistem Operasi
Sistem operasi terdiri dari beberapa komponen utama:

1. **Kernel**: Inti dari sistem operasi yang mengelola sumber daya perangkat keras.
2. **Shell**: Antarmuka pengguna yang memungkinkan pengguna berinteraksi dengan sistem operasi.
3. **File System**: Mengelola struktur file dan direktori pada media penyimpanan.
4. **Device Drivers**: Menghubungkan sistem operasi dengan perangkat keras (printer, disk, dll).
5. **Utilities**: Program tambahan yang membantu dalam pemeliharaan dan pengelolaan sistem.

---

## 1.4 Proses dalam Sistem Operasi
Proses adalah program yang sedang berjalan. Setiap aplikasi yang dijalankan dalam sistem operasi menjadi sebuah proses. Proses dapat memiliki status berikut:

- **Running**: Proses yang sedang dieksekusi oleh CPU.
- **Ready**: Proses yang siap untuk dijalankan, namun sedang menunggu giliran.
- **Blocked**: Proses yang sedang menunggu suatu peristiwa (misalnya input/output).

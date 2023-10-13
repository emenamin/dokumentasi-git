# dokumentasi-git

## Cara Menggunakan Git untuk Tracking Perubahan Versi
Disclaimer: Tutorial ini adalah hasil generate ChatGPT-4. Tutorial ini untuk kebutuhan pribadi dalam belajar menggunakan Git.

### 1. Inisialisasi Repository Lokal:

- Buka terminal atau command prompt.
- Pergi ke direktori tempat kode Anda disimpan.
- Ketik ```git init``` untuk menginisialisasi direktori sebagai repository Git.

### 2. Tambahkan File ke Staging Area:

- Setelah melakukan perubahan pada file Anda, tambahkan mereka ke _staging area_ dengan menggunakan ```git add```. (tanda titik di akhir untuk menambahkan semua file) atau ```git add <nama_file>``` untuk menambahkan file tertentu.

### 3. Commit Perubahan Anda:

- Setelah Anda menambahkan file ke staging area, commit perubahan dengan ```git commit -m "Pesan commit Anda"```. Pesan commit harus menjelaskan perubahan apa yang Anda buat.

### 4. Melihat Riwayat Commit:

- Anda bisa melihat riwayat commit dengan perintah ```git log```. Ini akan menampilkan daftar semua commit yang telah Anda buat.

### 5. Melakukan Perubahan dan Menggunakan Branching:

- Jika Anda ingin bekerja pada fitur atau perbaikan tertentu tanpa mengganggu kode utama, Anda bisa membuat branch baru dengan ```git branch <nama_branch>``` dan pindah ke branch tersebut dengan ```git checkout <nama_branch>```.
Setelah Anda selesai dengan perubahan di branch tersebut, Anda bisa menggabungkannya kembali ke branch utama (biasanya master atau main) dengan menggunakan perintah ```git merge```.

### 6. Memanfaatkan Tags:

- Anda bisa menggunakan tags di Git untuk menandai versi tertentu dari kode Anda, misalnya untuk rilis. Gunakan ```git tag <nama_tag>``` untuk membuat tag baru.

### 7. Menyimpan Perubahan tanpa Commit:

- Jika Anda memiliki perubahan yang belum siap untuk di-commit, tetapi Anda ingin menyimpannya untuk sementara, Anda bisa menggunakan ```git stash```. Nanti, Anda dapat mengambil perubahan tersebut kembali dengan ```git stash apply```.

## Pre-requisite Knowledge
Ternyata perlu tahu cara menggunakan Command Prompt; mengetahui perintah-perintahnya. 

### Cara Masuk ke Direktori

**1. Buka Command Prompt:**
Anda dapat menekan **Win + R**, ketik **cmd**, lalu tekan **Enter** atau mencari cmd atau Command Prompt di menu Start.

**2. Gunakan Perintah ```cd```:**
Ketik ```cd``` diikuti dengan path (alamat) direktori yang Anda ingin tuju. Misalnya, jika kode Anda disimpan di direktori ```C:\Users\YourName\Documents\MyCode```, Anda akan mengetik:

```
cd C:\Users\YourName\Documents\MyCode
```
Kemudian tekan **Enter**.

**3. Verifikasi Direktori Saat Ini:**
Setelah memasukkan perintah cd, Anda dapat memverifikasi bahwa Anda berada di direktori yang benar dengan mengetik perintah dir. Ini akan menampilkan daftar file dan sub-direktori di direktori saat ini.

**Tips:**
- Jika Anda ingin kembali ke direktori root dari drive saat ini, cukup ketik ```cd\``` dan tekan **Enter**.
- Jika Anda ingin berpindah ke drive lain, misalnya dari drive ```C:``` ke drive ```D:```, Anda hanya perlu mengetik nama drive diikuti dengan titik dua, seperti ```D:``` dan tekan Enter.
- Anda juga dapat menggunakan Tab untuk auto-complete nama file atau direktori saat mengetik di CMD. Ini dapat mempercepat proses pengetikan path direktori.
- Jika direktori Anda memiliki spasi di dalam namanya, pastikan Anda memasukkannya di antara tanda kutip ganda, misalnya:
```
cd "C:\Users\Your Name\Documents\My Code"
```

## Glosary
- **Terminal (Console/Command Prompt)** : Tempat buat ngetik perintah (a.k.a. antar muka baris perintah). Kalau yang di front-end, disebut antarmuka grafis.
- **Direktori** : istilah untuk menyebut folder

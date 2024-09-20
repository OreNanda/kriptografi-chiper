# Cipher Encryptor/Decryptor

Program ini adalah aplikasi desktop yang mengimplementasikan tiga metode enkripsi: Vigenere Cipher, Playfair Cipher, dan Hill Cipher. Aplikasi ini memungkinkan pengguna untuk mengenkripsi dan mendekripsi pesan dengan mudah.

## Fitur

- Enkripsi dan dekripsi menggunakan Vigenere, Playfair, dan Hill Cipher.
- Input pesan langsung atau melalui file `.txt`.
- Kunci harus memiliki panjang minimal 12 karakter.

## Persyaratan

- Java Development Kit (JDK) 8 atau yang lebih baru.
- IDE seperti IntelliJ IDEA atau Eclipse.

## Cara Menjalankan Program

1. **Clone Repository**
   - Clone repositori ini ke mesin lokal Anda:
     ```bash
     git clone https://github.com/OreNanda/kriptografi-chiper.git
     cd kriptografi-chiper
     ```

2. **Buka Proyek di IDE**
   - Buka proyek ini menggunakan IntelliJ IDEA atau IDE Java lainnya.

3. **Buat Kelas Utama**
   - Pastikan Anda memiliki kelas `CipherAppSwing` sebagai titik masuk aplikasi.

4. **Compile dan Jalankan Program**
   - Jalankan kelas `CipherAppSwing`. Ini akan membuka jendela aplikasi.
   - Anda akan melihat antarmuka yang memiliki pilihan untuk memasukkan pesan, kunci, dan memilih jenis cipher.

5. **Menggunakan Aplikasi**
   - Masukkan pesan di kolom "Message" atau unggah file `.txt` yang berisi pesan.
   - Masukkan kunci di kolom "Key" (pastikan kunci memiliki panjang minimal 12 karakter).
   - Pilih jenis cipher dari dropdown "Cipher".
   - Klik tombol "Encrypt" untuk mengenkripsi pesan atau "Decrypt" untuk mendekripsi.
   - Hasilnya akan ditampilkan di area hasil.

## Contoh Penggunaan

1. **Enkripsi**
   - Untuk mengenkripsi kata "HELP" dengan kunci "ABCDEFGHIJKL":
     - Pilih "Vigenere" dari dropdown.
     - Masukkan "HELP" di kolom pesan.
     - Masukkan "ABCDEFGHIJKL" di kolom kunci.
     - Klik "Encrypt" untuk mendapatkan hasil enkripsi.

2. **Dekripsi**
   - Untuk mendekripsi hasil:
     - Masukkan hasil enkripsi di kolom pesan.
     - Masukkan kunci yang sama.
     - Klik "Decrypt" untuk mendapatkan kembali "HELP".

## Catatan

- Pastikan semua input sudah benar dan sesuai dengan format yang diinginkan.
- Untuk penggunaan lebih lanjut, Anda dapat menambahkan lebih banyak fitur sesuai kebutuhan.

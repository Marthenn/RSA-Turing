# Kriptografi RSA Menggunakan Turing Machine
> Task Seleksi Lab IRK created by Bintang Dwi Marthen

versi **6 Juli 2024**

## 💡 Latar Belakang
Sebagai mahasiswa Teknik Informatika Institut Teknologi Bandung yang telah lulus semua mata kuliah dari lab IRK, pasti kalian sudah melewati mata kuliah Matematika Diskrit dan Teori Bahasa Formal dan Otomata. Sebagai calon asisten IRK, maka pengetahuan kalian mengenai mata kuliah yang diampu oleh lab IRK sangat diperlukan. Dengan tugas ini, pengetahuan kalian mengenai mata kuliah MatDis dan TBFO akan diuji (terutama TBFO). Task kali ini tidaklah susah, hanya membuat sebuah <ins>_Turing Machine_</ins> yang dapat melakukan kalkulasi kriptografi RSA.

## 📝 Spesifikasi Tugas
Berfokus pada kriptografi RSA, tugas Anda adalah membuat _Emulator Turing Machine_ yang dapat melakukan enkripsi dan dekripsi dari kriptografi RSA. Dalam implementasinya, Anda harus membuat struktur dari _Turing Machine_ serta prosesnya dari nol untuk membuktikan pemahaman _Turing Machine_ Anda.

Berikut merupakan spesifikasinya:

### Spesifikasi Wajib (2750 Poin)

_Emulator Turing Machine_ dibuat <b>berbasis cli</b>. Bahasa yang digunakan haruslah **Rust**. _Emulator_ harus mengandung beberapa fitur utama di bawah ini:

1. Kriptografi RSA yang digunakan akan menerima masukan sebuah _string_ ASCII dan mengeluarkan sebuah _string_ ASCII pula (baik untuk enkripsi maupun dekripsi)
3. _Emulator_ dapat menyimulasikan proses pada _Turing Machine_ tahap per tahap (pastikan Anda mengimplementasikan fitur untuk _skip_ ke keluaran juga)
4. _Emulator_ dapat menampilkan isi pita dari _Turing Machine_
5. _Emulator_ dapat menggunakan _private key_ dan _public key_ yang tidak _harcoded_ ke sistem, keduanya harus masuk ke pita
6. _Emulator_ dapat membandingkan hasil enkripsi dan dekripsinya dengan kriptografi RSA yang Anda buat sendiri secara langsung di Rust juga

Selain _emulator_, Anda juga diwajibkan untuk membuat sebuah laporan singkat mengenai _emulator_ yang Anda buat yang berisikan minimal:
1. Penjelasan apa itu _Turing Machine_
2. Penjelasan cara kerja _Turing Machine_
3. Pemetaan kriptografi RSA menjadi sebuah _Turing Machine_
4. Contoh _step by step_ enkripsi RSA di _Turing Machine_ yang Anda buat
5. Contoh _step by step_ dekripsi RSA di _Turing Machine_ yang Anda buat


### Spesifikasi Bonus (750 Poin)
Implementasikan dalam bentuk _*Desktop Application*_ menggunakan kakas GTK 4


## 📂 Pengerjaan dan Pengumpulan
1. Buatlah repositori **private** pada github masing-masing dan invite `Marthenn` dalam repositori tersebut.
2. Berkas yang dikumpulkan berupa **link rilis tag ke repositori github** yang telah dibuat dengan ketentuan sebagai berikut.
    - Memberikan tag `vn` pada commit terakhir Anda setiap kali ingin melakukan submisi dengan `n` adalah jumlah submisi yang telah dilakukan. (contoh: `v1` untuk submisi pertama).
    - **Tidak menggunakan *url shortener*** (bit.ly, shortlink, atau yang lain) saat melakukan pengumpulan *task*.
    - Anda dapat melakukan rilis dengan panduan [berikut](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository).
3. **Lakukan submisi** pada website seleksi IRK dengan menggunakan akun std.stei.itb.ac.id, **lakukan konfirmasi** ke LINE `bintangdwimarthen`, dan **jadwalkan demo** dengan cara yang sama. Lakukan hal yang sama jika membuat rilis yang baru.
4. Jika terdapat pertanyaan dapat menghubungi LINE `bintangdwimarthen`.

## 📌 Penilaian
Berikut pembagian nilai dari Task ini
| Komponen | Poin |
| ----------- | ----------- |
| Laporan dan Demo | 1000 |
| Enkripsi RSA | 500 |
| Dekripsi RSA | 500 |
| Prinsip _Turing Machine_ | 750 |
| GUI | 750 |


**Semangat Mengerjakan!!!**

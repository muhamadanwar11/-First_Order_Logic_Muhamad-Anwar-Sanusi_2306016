# -First_Order_Logic_Muhamad-Anwar-Sanusi_2306016

# 💡 Prolog: Sistem Relasi Keluarga

Program ini merupakan implementasi dalam bahasa **Prolog** untuk memodelkan **relasi keluarga** berdasarkan fakta dasar seperti hubungan pernikahan, ayah, ibu, jenis kelamin, dan aturan logika.

## 📁 Struktur Fakta

Berikut adalah fakta-fakta dasar yang digunakan:

* `menikah(X, Y)`: X menikah dengan Y.
* `ayah(X, Y)`: X adalah ayah dari Y.
* `ibu(X, Y)`: X adalah ibu dari Y.
* `pria(X)`: X adalah laki-laki.
* `wanita(X)`: X adalah perempuan.

## 📐 Aturan-aturan (Rules)

Program ini juga mendefinisikan berbagai aturan untuk mengetahui relasi antar anggota keluarga:

* `orangtua(X, Y)`: X adalah orang tua dari Y.
* `anak(X, Y)`: X adalah anak dari Y.
* `saudara(X, Y)`: X dan Y adalah saudara kandung.
* `kakek(X, Y)`: X adalah kakek dari Y.
* `nenek(X, Y)`: X adalah nenek dari Y.
* `cucu(X, Y)`: X adalah cucu dari Y.
* `paman(X, Y)`: X adalah paman dari Y.
* `tante(X, Y)`: X adalah tante dari Y.

## ✅ Contoh Query

Beberapa contoh query yang bisa kamu jalankan di interpreter Prolog:

```prolog
?- orangtua(david, liza).
?- anak(john, david).
?- saudara(john, liza).
?- kakek(david, peter).
?- paman(jack, peter).
?- tante(karen, mary).
```

## 🔧 Cara Menjalankan

1. Simpan semua fakta dan aturan di file dengan ekstensi `.pl`, misalnya `keluarga.pl`.
2. Buka Prolog interpreter seperti SWI-Prolog.
3. Load file dengan perintah:

   ```prolog
   ?- [keluarga].
   ```
4. Jalankan query yang diinginkan.

## 📌 Catatan

* Nama variabel dalam Prolog **harus diawali huruf kapital**.
* Nama fakta atau aturan diawali dengan huruf kecil.
* Tidak ada nilai null—relasi dianggap salah jika tidak bisa dibuktikan.

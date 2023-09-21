Demo: Lathifah Sahda/5025221159
# Kalkulator Sederhana

Ini adalah contoh sederhana dari kalkulator web yang dibuat menggunakan HTML, CSS, dan JavaScript. Kalkulator ini memungkinkan pengguna untuk memasukkan dua bilangan dan memilih operator matematika (penjumlahan, pengurangan, perkalian, atau pembagian) untuk melakukan perhitungan.

## Features

- Penjumlahan
- Pengurangan
- Perkalian
- Pembagian

## Cara Kerja
Kalkulator ini berfungsi dengan mengambil dua input bilangan dari pengguna, memilih operator matematika, dan menghitung hasilnya saat tombol "Submit" ditekan. Berikut adalah langkah-langkah detailnya:

- [Input Bilangan] - Pengguna diminta memasukkan dua bilangan yang ingin dihitung. Input ini ditangkap menggunakan elemen <input type=“number”> dengan ID bilangan1 dan bilangan2.
- [Pilih Operator] - Pengguna dapat memilih operator matematika (+, -, *, atau /) dari daftar dropdown yang disediakan. Pilihan operator ini ditangkap menggunakan elemen <select> dengan ID operator.
- [Tombol Submit] - Saat tombol "Submit" ditekan, event listener akan diaktifkan.
- [Perhitungan] Perhitungan dilakukan menggunakan JavaScript saat tombol "Submit" ditekan. Kode JavaScript berikut ini digunakan untuk mengambil nilai dari input bilangan dan operator, dan kemudian menghitung hasilnya menggunakan fungsi eval():

```sh
submit.addEventListener('click', function(){
    hasil.innerText = eval(bilangan1.value + operator.value + bilangan2.value)
```
- [Tampilan Hasil] Hasil perhitungan ditampilkan di bawah input bilangan dan operator menggunakan elemen <span> dengan ID hasil.
})

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Cara Menggunakan
- Buka halaman HTML ini di peramban web Anda.
- Masukkan dua bilangan yang ingin Anda hitung ke dalam input dengan ID bilangan1 dan bilangan2.
- Pilih operator matematika (+, -, *, atau /) dari dropdown dengan ID operator.
- Tekan tombol "Submit" untuk melakukan perhitungan.
- Hasil perhitungan akan ditampilkan di bawahnya.



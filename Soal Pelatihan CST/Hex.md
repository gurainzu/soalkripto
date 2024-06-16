## Hex
<sup>5 points</sup>

Ketika kita mengenkripsi sesuatu, ciphertext yang dihasilkan biasanya memiliki byte yang bukan merupakan karakter ASCII yang dapat dicetak. Jika kami ingin membagikan data terenkripsi kami, biasanya kami menyandikannya menjadi sesuatu yang lebih mudah digunakan dan portabel di berbagai sistem.

Heksadesimal dapat digunakan sedemikian rupa untuk mewakili string ASCII. Pertama setiap huruf diubah menjadi nomor urut sesuai tabel ASCII (seperti pada tantangan sebelumnya). Kemudian bilangan desimal tersebut diubah menjadi bilangan basis 16 atau disebut dengan heksadesimal. Angka-angka tersebut dapat digabungkan menjadi satu string hex yang panjang.

> Untuk penjelasan yang lebih lengkap : 
https://binus.ac.id/malang/2021/11/sekilas-tentang-heksadesimal-bagian-1/

Termasuk di bawah ini adalah flag yang dikodekan sebagai string hex. Dekode ini kembali menjadi byte untuk mendapatkan flag.

```
736d6b32327b793075725f66317273745f6833783f217d
```

>fungsi bytes.fromhex() didalam python mungkin dapat membantu.
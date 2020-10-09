<b>NOSQL</b>
<p>
    Katakanlah kita memiliki dokumen (dokumen dapat berupa struktur data, bukan
    satu baris data). Kami menyimpan dokumen ini dengan id, misalkan DOKUMEN #
    10. Jadi kita dapat mengambil dokumen ini # 10 dengan namanya.
</p>
<b>Apa keuntungannya:</b>
<ul>
    <li>
        Kita dapat menyimpan dokumen (misalnya struktur dengan banyak baris)
        secara bersamaan. Kita dapat mengambil seluruh dokumen pada saat yang
        bersamaan.
    </li>
</ul>
<b>SQL</b>
<p>
    SQL berfungsi terutama dengan baris, kami menyisipkan baris dan kami
    mengambil satu baris atau lebih dari satu. Jika kita ingin menyimpan
    dokumen, kita perlu memasukkan banyak baris dalam banyak tabel dan kita
    perlu menghubungkan setiap tabel). Jadi SQL terutama bersifat relasional.
</p>
<b>Apa keuntungannya:</b>
<ul>
    <li>
        Kita dapat membaca setiap baris atau mencapai beberapa baris dengan
        beberapa kriteria. Jadi SQL sangat ideal untuk analisis data dan cepat.
    </li>
</ul>
<p>Sebagai contoh, katakanlah kita memiliki sistem yang menyimpan faktur.</p>
<b>NOSQL:</b>
<ul>
    <li>
        Mudah untuk menyimpan faktur baru. Setiap faktur adalah dokumen tunggal,
        jadi kami menyimpan secara keseluruhan dalam satu langkah tunggal. Dan
        kami dapat dengan mudah membaca faktur sederhana. Kami membutuhkan nomor
        dan sistem akan mengembalikan seluruh faktur. Namun, gagal untuk
        analisis data. Misalnya, bagaimana jika kita perlu mendapatkan semua
        faktur dari beberapa pelanggan, atau semua faktur dengan beberapa
        produk. Mengapa itu gagal? Karena itu perlu membaca seluruh faktur, satu
        per satu dan itu bisa sangat lambat.
    </li>
</ul>
<b>SQL</b>
<ul>
    <li>
        Sulit untuk menyimpan faktur baru karena kita perlu memisahkan di baris
        yang berbeda. Ini juga melibatkan bekerja dengan transaksi. Juga membaca
        seluruh faktur itu rumit karena kita perlu melakukan panggilan berbeda
        ke database dan menggabungkan informasi dalam kode kita. Namun, itu
        sangat ideal untuk analisis data. Itu bisa mendapatkan semua faktur
        pelanggan dalam sepersekian detik.
    </li>
</ul>
<br>
<p>Sumber: https://svcministry.org/id/dictionary/what-is-the-difference-between-sql-and-nosql/</p>

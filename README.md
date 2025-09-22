# Tugas Praktikum 1: HTML Dasar 

1. Buatlah **Repository** baru dengan nama **Lab1Web.**

2. Kerjakan semua latihan yang diberikan sesuai urutannya.

3. Screenshot setiap perubahannya.

4. Buatlah File **README.md** & tuliskan penjelasan dari setiap langkah praktikum beserta screenshotnya

5. **Commit** hasilnya pada **Repository** masing-masing.

6. Kirim URL repository pada **E-learning** ecampus.

## Instruksi Praktikum 

1. Persiapkan text editor misalnya **VsCode**

2. Buat file baru dengan nama **lab1_tag_dasar.html**

3. Buat struktur dasar dari dokumen HTML

  <img width="290" height="222" alt="image" src="https://github.com/user-attachments/assets/f61593fd-f49e-4611-8cb6-fb56b69c6061" />

  Kemudian selanjutnya, buka file tersebut pada web browser misalnya **Microsoft Edge.**

4. Ikuti langkah-langkah Praktikum yang akan dijelaskan berikutnya:

  a. Membuat Paragraf

  <img width="761" height="432" alt="image" src="https://github.com/user-attachments/assets/338cf440-ac2f-4bb5-a57c-799c79a9a465" />

  <img width="959" height="232" alt="image" src="https://github.com/user-attachments/assets/7be59e29-8cc8-43f8-8bc9-a2e8e14a4f0e" />

  b. Menambahkan judul

  <img width="286" height="72" alt="image" src="https://github.com/user-attachments/assets/1116f6c8-9e79-40eb-b6d1-4709f4532ce9" />

  <img width="272" height="68" alt="image" src="https://github.com/user-attachments/assets/f6f584e2-f47c-4bff-9214-f4c2be788191" />

  <img width="958" height="346" alt="image" src="https://github.com/user-attachments/assets/12ac8823-6f74-41e5-be64-fdde73cf411e" />

  c. Memformat Teks

  <img width="755" height="179" alt="image" src="https://github.com/user-attachments/assets/81a5a388-d93b-4f76-a826-85cd2f01e6b6" />

  <img width="957" height="135" alt="image" src="https://github.com/user-attachments/assets/15ad80ea-57a4-45ad-8f7c-74a407350531" />

  d. Menyisipkan Gambar

  <img width="591" height="72" alt="image" src="https://github.com/user-attachments/assets/908e77ae-e978-40cb-bc2e-e9b1b10f6274" />

  <img width="255" height="275" alt="image" src="https://github.com/user-attachments/assets/884cdbc9-41f4-4bf7-aae7-c2ffe2597529" />

  e. Menambahkan Hyperlink

  <img width="535" height="251" alt="image" src="https://github.com/user-attachments/assets/f07e6254-a50f-453d-abd3-4bff00bc299e" />

  <img width="401" height="64" alt="image" src="https://github.com/user-attachments/assets/c5637af4-cdbf-4083-9bd0-79b2523788dc" />

  <img width="754" height="950" alt="image" src="https://github.com/user-attachments/assets/7b4aaa4f-17c7-4f8e-a745-98b17e5a68c0" />

  <img width="955" height="330" alt="image" src="https://github.com/user-attachments/assets/92cb92fb-5868-4c3a-ab1f-459505500b59" />

5. Lakukan validasi dokumen html dengan mengakses http://validator.w3.org

  <img width="877" height="661" alt="image" src="https://github.com/user-attachments/assets/9dabf159-d225-4776-9fa9-5d5c8ccf31e0" />

## Menjawab Pertanyaan

  1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

  2. Apa perbedaan dari tag p dengan tag br, berikan penjelasannya!

  - p : membuat blok teks terpisah dengan jarak antar paragraf.
    
  - br : hanya memecah baris dalam satu paragraf tanpa jarak tambahan.

  3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!

  - title : Tooltip saat mouse diarahkan ke atas gambar

  - alt : Teks alternatif jika gambar gagal dimuat / tidak muncul

  4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

  - Sebaiknya hanya isi salah satu atribut (biasanya width), **agar proporsi gambar tetap terjaga.** Contoh: <img src="foto.jpg" width="300">

  - Jika kamu isi **keduanya secara manual**, dan nilainya tidak sesuai rasio asli gambar, maka gambar bisa **terdistorsi** (terlalu lebar atau terlalu tinggi). Contoh: <img src="foto.jpg" width="300" height="100">

  5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?

  - _blank : Membuka link di tab baru

  - self : Membuka link di tab yang sama (default)

  - _top : Membuka link di halaman utama (keluar dari frame)

  - _parent : Membuka link di frame induk jika ada

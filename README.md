    Nama  : Arofah Raudlatul Hasanah
    Kelas : TI. 24. A2
    NIM   : 312410231
    Praktikum 2
## Pertanyaan dan Tugas 
## 1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
## Jawaban : 
*1.  Membuat dokumen HTML*
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/c29a6a28-33d2-4f57-b9b2-789a0ca16a26" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/9d818997-0e5e-4557-a082-192bd9653453" />
penjelasan : Pada tahap ini saya membuat file lab2_css_dasar.html sesuai instruksi modul. Di dalamnya saya menambahkan elemen header, nav, dan div id="intro". Selanjutnya saya menambahkan CSS Internal di bagian head untuk mengatur font, warna, dan posisi teks. Setelah disimpan dan dibuka di browser, hasilnya sesuai: judul utama tampil biru dan rata tengah, link navigasi muncul di atas, dan paragraf ditampilkan di bawah judul “Hello World”. Ini menunjukkan CSS Internal berhasil diterapkan pada HTML.

*2. Mendeklarasikan CSS Internal*
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/4cccbc64-4dc9-4b1a-a751-cbe2ca8c72ae" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/a7dcae06-64d0-4725-8c1c-82696ede0a9a" />
penjelasan : Pada tahap ini saya menambahkan CSS Internal di dalam tag style pada bagian head dokumen HTML. Saya mendeklarasikan selector h1 dengan properti color: #0f189f;. Hasilnya terlihat di browser, semua teks h1 berubah warna menjadi biru tua. Ini membuktikan CSS Internal berhasil diterapkan pada elemen HTML.

*3. Menambahkan Inline CSS*
<img width="940" height="385" alt="image" src="https://github.com/user-attachments/assets/4ff8814d-2b12-4c27-b6f3-0f4553c98ff8" />
<img width="940" height="364" alt="image" src="https://github.com/user-attachments/assets/73863bac-989c-444f-b7b5-3e1050f2e02d" />
penjelasan : Pada tahap ini saya menambahkan Inline CSS langsung pada tag p dengan atribut style="text-align: center; color: #ccd8e4;". Tujuannya agar paragraf berwarna abu-abu muda dan teksnya rata tengah. Hasilnya di browser sesuai: teks paragraf rata tengah dan berubah warna. Hal ini menunjukkan bahwa Inline CSS memiliki prioritas paling tinggi dibanding Internal dan Eksternal CSS.


*4. Membuat CSS Eksternal & Menambahkan CSS Selector*
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/d3714aa5-48df-4d7d-8f1c-fcd4252db100" />
<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/323d1c3b-d8cd-4c12-a2d4-e258cda44a41" />
penjelasan : Pada tahap ini saya melengkapi CSS Internal dengan menambahkan pengaturan pada body, header, h1, #intro, .button, dan .btn-primary. Saya juga menambahkan Inline CSS pada tag p untuk mengatur warna teks dan perataan. Hasilnya terlihat di browser: halaman tampil lebih menarik dengan background abu muda, judul rata tengah, kotak intro dengan border melengkung, dan tombol merah “Informasi selengkapnya”. Ini menunjukkan bahwa saya berhasil menerapkan berbagai selector (Elemen, ID, Class) dan prioritas CSS (Internal dan Inline CSS).

## 2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
## Jawaban :
    Pendeklarasian h1 { ... } artinya aturan CSS tersebut berlaku untuk semua elemen <h1> di seluruh halaman web tanpa kecuali. Jadi setiap ada tag <h1> di mana saja, otomatis akan mengikuti style itu.
    Sedangkan #intro h1 { ... } artinya aturan CSS tersebut hanya berlaku untuk elemen <h1> yang berada di dalam elemen yang punya id="intro" saja. Jadi lebih spesifik: <h1> yang di luar #intro tidak terpengaruh, hanya yang ada di dalam #intro saja yang kena style.

## 3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
## Jawaban :
Kalau ada deklarasi CSS internal, kemudian ditambahkan CSS eksternal, lalu juga ada inline CSS pada elemen yang sama, yang ditampilkan di browser adalah inline CSS.
Kenapa? Karena inline CSS punya prioritas paling tinggi dibanding internal dan eksternal. Urutannya begini:
- Eksternal CSS (paling rendah)c
- Internal CSS
- Inline CSS (paling tinggi)
Jadi walaupun kita sudah atur warna di file eksternal atau internal, kalau di elemen HTML yang sama kita kasih atribut style="", maka style inline inilah yang akan dipakai.
contoh : <img width="1919" height="719" alt="image" src="https://github.com/user-attachments/assets/2507ca71-d5ee-4173-adfe-fda559a9cd53" />

## 4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! p id="paragraf-1" class="text-paragraf"
## Jawaban : 
Kalau satu elemen HTML punya ID dan Class sekaligus, lalu keduanya punya aturan CSS masing-masing, maka yang ditampilkan browser adalah aturan CSS dari ID. Kenapa? Karena selector ID lebih spesifik dan lebih tinggi prioritasnya dibanding Class. Urutan spesifisitasnya:
- Inline CSS (paling tinggi)
- ID Selector (#id)
- Class Selector (.class)
- Elemen Selector (paling rendah)
contoh : <img width="1919" height="571" alt="image" src="https://github.com/user-attachments/assets/b78f8e0f-6ef5-43cf-963d-0f8492369f6f" />















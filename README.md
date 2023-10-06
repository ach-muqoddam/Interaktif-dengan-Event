# Apa itu Event

- Memanipulasi konten halaman web menggunakan JavaScript. Bahkan, juga dapat memanipulasi elemen HTML, seperti menghapus, menambahkan, hingga memanipulasi atributnya.
- Suatu elemen dapat interaktif ketika mendapatkan suatu feedback (event)

## Berikut macam-macam event di JavaScript

# Event Bubbling dan Capturing

- Event bubbling maupun capturing termasuk dalam event propagation.

# Event Bubbling

- Analoginya seperti gelembung pada minuman bersoda.
- Sebuah event terjadi pada sebuah elemen, maka event handler milik elemen tersebut akan dijalankan terlebih dahulu yang diikuti event handler elemen parent-nya, dan seterusnya sampai elemen paling atas. Sama seperti fenomena gelembung udara pada minuman bersoda.

# Event Capturing

- Setelah membahas bubbling, mari kita bahas fenomena berikutnya yakni capturing. Capturing merupakan kebalikan dari bubbling yang akan men-trigger event handler dari parent ke child.

# Event Form

- Form umumnya digunakan untuk menangkap input dari user dalam jumlah banyak sekaligus. Bisa ditebak dari namanya pasti bentuk form akan mirip seperti formulir.
- Ada field yang bisa diisi dan ada juga tombol bernama "Submit Data" ketika kita sudah selesai mengisi data pada form. Sama halnya dengan elemen HTML pada umumnya, terdapat beberapa event yang dihasilkan oleh form yang akan kita terapkan.

# Event onInput

- Event onInput akan dijalankan setiap kali kita menulis atau menghapus apa pun pada sebuah field input yang memiliki event listener tersebut.
- event onInput memeriksa setiap kali menulis atau menghapus karakter. Ingat ya, karena nanti kita menggunakan method addEventListener(), maka versi string event onInput untuk dimasukkan ke parameter pertama method tersebut adalah “input”.
- Untuk mengimplementasi fitur tersebut, kita harus menambahkan event listener pada input yang memiliki id dan memperbarui teks setiap kali kita menulis atau menghapus karakter baru.

# Event onFocus

- Event onFocus akan dijalankan ketika melakukan klik di sebuah elemen input. Kita akan mencoba untuk menampilkan tulisan berupa notifikasi jumlah karakter yang masih diperbolehkan. Untuk dapat melakukan hal tersebut, kita harus menambahkan sebuah event handler pada elemen input yang menerima penulisan nama panggilan untuk event onFocus.

# Event onBlur

- Event onBlur akan dijalankan ketika pada kondisi yang terbalik dengan event onFocus, yakni jika kita “pergi” dari elemen yang memiliki event handler untuk event onFocus. Apa maksud dari “pergi”? Maksudnya adalah kita tidak lagi berinteraksi secara langsung dengan elemen tersebut seperti kita telah melakukan klik pada elemen lain.
- Kode tersebut akan “menyembunyikan” kembali pesan notifikasi jumlah sisa karakter yang diperbolehkan. Proses tersebut terjadi ketika kita klik elemen lain alias elemen <input> yang membuat nama panggilan sudah tidak menjadi fokus utama lagi.

# Event onChange

- Event onChange memiliki perilaku yang mirip dengan onInput, yaitu event yang terjadi jika terdapat perubahan nilai. Namun, terdapat perbedaan yang dimiliki oleh onChange.
- event onChange akan terjadi jika elemen input mengalami perubahan nilai atau lebih tepatnya event onChange seakan-akan merupakan gabungan dari event onInput dan onBlur.

# Event onCopy & onPaste

- Event ini tergolong dalam kelompok clipboard events. Event ini terjadi jika kita melakukan operasi pada clipboard seperti copy dan paste.

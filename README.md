# Belajar-Membuat-Front-End-Web-Pemula

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

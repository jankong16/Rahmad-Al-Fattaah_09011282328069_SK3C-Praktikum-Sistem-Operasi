# TUGAS 5 PRAKTIKUM SISTEM OPERASI

 *1. Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file baru.*
 
 Untuk melihat daftar direktori aktif, gunakan perintah $ ls, sedangkan untuk membelokkan tampilan standard output ke file baru, gunakan ">"

 ![Screenshot 2024-09-26 200016](https://github.com/user-attachments/assets/a0313fef-a6c9-4cf1-b950-6562b6fdd93d)

*2. Lihat daftar secara lengkap pada direktori /etc/passwd, belokkan tampilan standard output ke file baru tanpa menghapus file baru sebelumnya.*

Untuk melihat daftar lengkap dari direktori /etc/passwd, gunakan perntah $ ls, sedangkan untuk membelokkan tampilan standard output ke file baru 
tanpa menghapus file baru sebelumnya, gunakan ">>"

![Screenshot 2024-09-26 200053](https://github.com/user-attachments/assets/10085754-002a-4580-9761-7b786552441b)

*3. Urutkan file baru dengan cara membelokkan standard input.*

Untuk mengurutkan file, gunakan perintah $ sort, sedangkan untuk membelokkan standard input, gunakan "<"

![Screenshot 2024-09-26 200116](https://github.com/user-attachments/assets/df9d6206-6263-4853-9b6d-c53dab930c74)

*4. Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut.*

Untuk mengurutkan file, gunakan perintah $ sort, sedangkan untuk membelokkan standard input, gunakan "<", sedangkan untuk membelokkan standard output ke file, gunakan ">". 
Pembelokan standart input dan standart output dapat dikombinasikan asalkan tidak boleh menggunakan nama file yang sama sebagai standart input dan output.

![Screenshot 2024-09-26 200151](https://github.com/user-attachments/assets/706e07d1-edce-4756-a27e-d6bc1a180e4d)

*5. Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt.*

Gunakan perintah $ mkdir untuk membuat direktori baru. Saat membuat direktori yang sama sebanyak dua kali, akan muncul pesan error. 
Pesan error itu kemudian dibelokkan ke file dengan menggunakan "2>".

![Screenshot 2024-09-26 200307](https://github.com/user-attachments/assets/d36e4069-d614-4b30-a6ce-74eeb3442183)

*6. Urutkan kalimat berikut dengan menggunakan notasi here document :*

*sort <<@@@*

*Jakarta*

*Bandung*

*Surabaya*

*Padang*

*Palembang*

*Lampung*

*@@@*

Pertama, buat notasi here document yang akan dibelokkan ke sebuah file kemudian isi document tersebut. Setelah diisi dan diakhiri, isi dokumen akan tersimpan ke file yang dibelokkan. 
File tersebut kemudian diurutkan menggunakan perintah $ sort. 

![Screenshot 2024-09-26 200531](https://github.com/user-attachments/assets/2fd69bde-14a7-4d74-9817-2d765c76fda7)

*7. Hitung jumlah baris, kata, dan karakter dari file baru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru.*

Untuk mendapatkan jumlah baris, kata, dan karakter (secara berurutan) dari sebuah file, gunakan perintah wc yang dipipakan dengan perintah cat. 
Hasilnya kemudian bisa ditambahkan ke file menggunakan ">>" 

![Screenshot 2024-09-26 200626](https://github.com/user-attachments/assets/38bf9ea8-10f4-496a-8ab0-c441a0de2d7d)

*8. Gunakan perintah di bawah ini dan perhatikan hasilnya:*

*cat /etc/passwd | sort | pr -n | grep tty03*

Menampilkan isi /etc/passwd, mengurutkannya, menomori barisnya, dan mencari baris yang mengandung tty03.

*find /etc –print | head*

Menampilkan 10 baris pertama dari daftar file dan direktori di dalam /etc.

*head /etc/passwd | tail -5 | sort*

Menampilkan 5 baris terakhir dari 10 baris pertama file /etc/passwd, kemudian mengurutkannya.

![Screenshot 2024-09-26 200748](https://github.com/user-attachments/assets/0765cdca-5991-40cc-8bce-9ad1bfb4b930)

*9. Gunakan perintah berikut dan perhatikan hasilnya:*

*who | cat | cat | sort | pr | head | cat | tail*

Menampilkan pengguna yang sedang login (who), mengurutkan hasilnya, memformat output, menampilkan baris pertama dan terakhir dari hasil tersebut.

![Screenshot 2024-09-26 200832](https://github.com/user-attachments/assets/2f30611b-0a89-4ec8-ac68-1855d479a02d)

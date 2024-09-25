# PRAKTIKUM 5 - JOB CONTROL

### 1. Eksekusi seluruh profile yang ada
   - Edit file profile /etc/profile dan tampilkan pesan sebagai berikut:

     ![Screenshot 2024-09-25 233550](https://github.com/user-attachments/assets/637b0097-de21-4643-9f38-e1ae0ada8817)

     ![Screenshot 2024-09-25 233657](https://github.com/user-attachments/assets/e5f26fcb-88df-417b-8d4a-7d43f4f00840)
     
   - Asumsikan nama Anda stD02001, maka edit semua profile yang ada, yaitu:

     _- /home/mahasiswa/.bash_profile_

      _- /home/mahasiswa/.bash_login_

      _- /home/mahasiswa/.profile_
     
     _- /home/mahasiswa/.bashrc_

     ![Screenshot 2024-09-26 001024](https://github.com/user-attachments/assets/6363c2bc-a048-4553-92f9-618f1995ff2a)

   - Ganti nama /home/mahasiswa/ dengan nama Anda sendiri. Pada setiap file tersebut, tambahkan instruksi berikut:
    
     _echo "Profile dari .bash_profile"_

     ![Screenshot 2024-09-26 000617](https://github.com/user-attachments/assets/efa3e240-5cf0-47e4-9b0b-b66a834cf4f2)

     ![Screenshot 2024-09-26 000707](https://github.com/user-attachments/assets/a730db79-d012-4e8a-8620-921ae6a0f73c)

     ![Screenshot 2024-09-26 000820](https://github.com/user-attachments/assets/e187fd76-db0e-445b-91e1-a2fe542d660f)

     ![Screenshot 2024-09-26 000957](https://github.com/user-attachments/assets/ece0f1f2-1939-481b-908c-accb6d60f6e2)
     
   - Jalankan instruksi substitute user, kemudian keluar dengan perintah exit sebagai berikut:

     ![Screenshot 2024-09-26 001234](https://github.com/user-attachments/assets/dfb160a1-5cba-45e9-8987-4e5179d0540f)

### 2. Prompt String (PS1)
   - Edit file .bash_profile, ganti prompt PS1 dengan > sebagai prompt. Instruksi export diperlukan dengan parameter nama variable tersebut,
     agar perubahan variable PS1 dikenali oleh semua shell yang berjalan.

     ![Screenshot 2024-09-26 001808](https://github.com/user-attachments/assets/8f407592-3075-49a0-bf7b-8786e3ec618d)

     ![Screenshot 2024-09-26 001447](https://github.com/user-attachments/assets/43aa00a6-0dad-4ff1-8f18-86548bbc602a)

   - Eksperimen hasil PS1.

     ![Screenshot 2024-09-26 001827](https://github.com/user-attachments/assets/37cc23f6-ee81-4ca0-b8af-0aa33669bdc3)

### 3. Logout
   - Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout:

     ![Screenshot 2024-09-26 002037](https://github.com/user-attachments/assets/b5e0093d-9f0a-4c8c-b881-f12a11cecdd6)

     ![Screenshot 2024-09-26 002009](https://github.com/user-attachments/assets/921d4147-0f96-4684-af8c-07771affe1f2)     

### 4. Bash Script
   - Buat 3 buah script (p1.sh, p2.sh, p3.sh) dengan isi masing-masing:

     ![Screenshot 2024-09-26 002817](https://github.com/user-attachments/assets/7b65a773-21c8-4fa2-99e5-b6e6134d4ad7)

     ![Screenshot 2024-09-26 002143](https://github.com/user-attachments/assets/3bf5fe04-a9ed-471b-831e-daf47afadafd)

     ![Screenshot 2024-09-26 002230](https://github.com/user-attachments/assets/cb9764e8-37ab-42e7-84e5-48ebb988400b)

     ![Screenshot 2024-09-26 002750](https://github.com/user-attachments/assets/b3bcaeee-aa42-4c7a-9f12-4a018c929a25)
     
   - Jalankan script tersebut

     ![Screenshot 2024-09-26 003613](https://github.com/user-attachments/assets/a3fd2ed0-0572-478e-ae2e-87284ec56382)

     ![Screenshot 2024-09-26 003634](https://github.com/user-attachments/assets/91d09a5c-4f68-4dc1-80b6-770fc3102b3d)

     ![Screenshot 2024-09-26 003957](https://github.com/user-attachments/assets/2f2d32ea-ecd7-4ff3-832d-81b7658a8b01)

     ![Screenshot 2024-09-26 004102](https://github.com/user-attachments/assets/92a01748-2a68-4a19-bbcd-76fceef184a5)

     ![Screenshot 2024-09-26 004158](https://github.com/user-attachments/assets/bf27d0eb-aed6-4856-bca3-5083b3a53a16)

### 5. Jobs
   - Buat sebuah script looping melakukan loop dengan nama pwaktu.sh.  
     Setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil:

     ![Screenshot 2024-09-26 004349](https://github.com/user-attachments/assets/78f53643-7733-45cb-9646-ce4860decb09)

     ![Screenshot 2024-09-26 010710](https://github.com/user-attachments/assets/0763d066-0282-4fee-97e0-3e65653f242c)
  
   - Jalankan sebagai background, kemudian jalankan satu program (misalnya find) di background sebagai berikut:

     ![Screenshot 2024-09-26 004845](https://github.com/user-attachments/assets/cd7fdbb6-7274-4f7d-8c96-d0b1b9b691ca)

   - Jadikan program find sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background:

     ![Screenshot 2024-09-26 004922](https://github.com/user-attachments/assets/b78e1a38-c953-487c-aeca-3c970c5a2a57)
 
   - Stop program background dengan utilitas kill:

     ![Screenshot 2024-09-26 005019](https://github.com/user-attachments/assets/ce87fe50-ad75-4b98-bae1-68bf7e60242b)

     ![Screenshot 2024-09-26 005058](https://github.com/user-attachments/assets/1d3680c4-ac3e-49cc-9036-53b71aaef169)


### 6. History:
   - Ganti nilai HISTSIZE dari 1000 menjadi 20:

     ![Screenshot 2024-09-26 005206](https://github.com/user-attachments/assets/3d89db3d-ac46-4b49-bf8b-19c919f980b6)

   - Gunakan fasilitas history dengan mengoreksi instruksi baris ke-5 dari instruksi yang terakhir dilakukan:

     ![Screenshot 2024-09-26 005311](https://github.com/user-attachments/assets/961901ec-4d7a-482d-9c85-c577217aae9c)
  
   - Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk beberapa perintah pada history buffer.

     ![Screenshot 2024-09-26 005329](https://github.com/user-attachments/assets/80af637e-1ee6-4f14-8054-158e8ea328aa)

   - Edit nilai HISTFILESIZE agar history buffer nomor 150.

     ![Screenshot 2024-09-26 005440](https://github.com/user-attachments/assets/c9256115-c094-4464-ab00-91b8baf05b02)

     Karena tidak ada history nomor 150 jadi diambil history nomor 49
     
   - Ulangi instruksi dengan grep "ls":

     ![Screenshot 2024-09-26 005500](https://github.com/user-attachments/assets/1f501b3a-ae2d-46a1-9511-f0607076fc0d)

NAMA : SINTA BELA

NIM : 09030182428011

TUGAS: SISTEM OPERASI PRATIKUM 6

1.Login sebagai studentOS dan lihat status proses, perhatikan kolom keluaran ps –au sebagai berikut :

a. Nama proses yang bukan root yaitu sintabela

b. PID dan COMMAND dari proses yang paling banyak menggunakan CPU Semua proses menunjukkan %CPU = 100 Maka dipilih proses yang aktif (R+): PID: 430 COMMAND: ps -au

  ![image](https://github.com/user-attachments/assets/1fd16c40-4b02-499f-a22c-004d1c83d005)


   c.Buyut proses dan PID dari proses tersebut Tracing dari proses ps -au:

   ![image](https://github.com/user-attachments/assets/a326cfd4-535a-4374-b5fd-9987efb730a7)

   Jadi, buyut prosesnya adalah: PID: 1 COMMAND: /init

 d. beberapa proses daemon 

 ![image](https://github.com/user-attachments/assets/63057d85-4855-49ac-b59d-c47c335591ba)

  e. jalankan printah berikut
  
-$ csh

![image](https://github.com/user-attachments/assets/468827ba-c7dd-4848-bfee-6fdd0a7b6156)

-$ who , $ bash , $ ls dan $ sh

![image](https://github.com/user-attachments/assets/b2c411e5-05ac-414d-a9d3-0fd090b0fdc3)

-$ ps

![image](https://github.com/user-attachments/assets/19f69e3a-bb41-441c-b327-595fe40584db)

PID terbesar: 663 (sh) Urutan lengkap sampai ke induk utama (PPID = 1) ditelusuri dengan ps -fp [PID]

Program prog.sh dengan Trap

a). Buka file prog.sh

![image](https://github.com/user-attachments/assets/7b75d993-bd9b-4b3b-ae31-4044dcaedbcb)

b). Tulis skrip

![image](https://github.com/user-attachments/assets/f80fbfd1-141a-4891-b91f-1ac8db356fc9)

c). Ubah file agar bisa dieksekusi, jalankan program sebagai background, dan catat nomor PID dari proses tersebut

![image](https://github.com/user-attachments/assets/edb7dca3-b2b3-4336-bff9-480233bac234)

d). Kirim sinyal satu per satu

![image](https://github.com/user-attachments/assets/3f771151-63f2-45fc-9e36-06d4dff29052)

Nomor sinyal yang digunakan menghentikan proses diatas yaitu $ kill -3 558

Program myjob.sh dengan Auto-Hapus File

a). Buka file myjob.sh

![image](https://github.com/user-attachments/assets/588f44ae-8516-4e83-9078-3d042301adcc)

b). Isi skrip

![image](https://github.com/user-attachments/assets/d710e9a1-cbc0-4eb6-84b7-eb60e21066e7)

c). Buat executable, jalankan dibackground, dan Cek nomor PID nya

![image](https://github.com/user-attachments/assets/1e529fbf-06f8-43ae-aae9-5c673d5f84d0)


d). Hentikan proses dengan sinyal 15

![image](https://github.com/user-attachments/assets/b2c5b461-c6ad-48d1-a224-42f6c0f2240f)

proses dihentikan dengan kill -15 448, muncul:

![WhatsApp Image 2025-04-16 at 13 18 06_b9f153b8](https://github.com/user-attachments/assets/3b1f9d11-25e6-495d-8180-4c078a556738)

File berkas dan hasil otomatis terhapus Fungsi trap berjalan sukses.   


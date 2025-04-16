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












   


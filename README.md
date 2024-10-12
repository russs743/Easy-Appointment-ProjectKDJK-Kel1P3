# Easy!Appointments Kelompok 1 P3
## sekilas tentang
  Easy!Appointments adalah aplikasi web yang sangat dapat disesuaikan yang memungkinkan pelanggan membuat janji temu dengan Anda melalui antarmuka web yang canggih. Selain itu, ia menyediakan kemampuan untuk menyinkronkan data Anda dengan Google Kalender sehingga Anda dapat menggunakannya dengan layanan lain. Ini adalah proyek sumber terbuka yang dapat Anda unduh dan instal bahkan untuk penggunaan komersial. Easy!Appointments akan berjalan lancar dengan situs web Anda yang ada karena dapat diinstal dalam satu folder server dan tentu saja berbagi database yang ada.
## Fitur
Aplikasi ini dirancang cukup fleksibel sehingga dapat menangani alur kerja perusahaan apa pun.
- Manajemen pelanggan dan janji temu.
- Organisasi layanan dan penyedia.
- Rencana kerja dan aturan pemesanan.
- Sinkronisasi Google Calendar.
- Sistem notifikasi email.
- Instalasi yang di hosting sendiri.
- Antarmuka pengguna yang diterjemahkan.
- Dukungan komunitas pengguna.
## Setup
Sebelum menginstal Easy!Appointments, pastikan bahwa sistem memenuhi prasyarat berikut:
- Apache/NGINX
- MySQL
- PHP >= 7.4
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PDO PHP Extension
## Database
1. Kita bisa pergi ke cPanel; dan membuat Databases dan User. Sebelum itu, pergi ke bagian Databases dan klik MySQL Databases.
   
   ![image](https://github.com/user-attachments/assets/c9c3865a-5de4-4f6c-83bd-9612b5bd776a)
   
2. Kamu bisa membuat database untuk sebuah web. Sebelum itu, pergi ke bagian Create New Database. Kamu bisa masukkan nama databases sesuka hati kalian.
   
![image](https://github.com/user-attachments/assets/9bb70fd7-00bd-453b-8fa1-94b88577d3f0)

3. Database akan muncul di list Current Databases yang sudah dibuat
   
   ![image](https://github.com/user-attachments/assets/47b994ae-152e-4641-a48e-388fca5d2a2f)

4. Kamu juga bisa membuat User untuk Databases tersebut, tinggal masukkan nama dan password untuk User anda seperti Create New Databases sebelumnya
   
![image](https://github.com/user-attachments/assets/ed1d64ef-1fed-4d14-a094-3e7ffbf33bc6)

5. User telah dibuat dan terletak di list Current Users, berada di bagian paling bawah dari web
    
![image](https://github.com/user-attachments/assets/ac8ea726-7639-47aa-b2ec-6d037ac6716e)

6. Berikan permission untuk User kepada Database yang telah dibuat, sebelum itu pergi ke bagian Add User To Database
    
![image](https://github.com/user-attachments/assets/b86bb339-218f-4aa2-a211-e10d58a86810)

7. Kamu akan pergi ke bagian untuk memberikan privileges kepada User dari database yang telah dipilih, kamu hanya mengklik ALL PRIVILEGES untuk GRANT ALL PRIVILEGES kepada User tersebut
    
![image](https://github.com/user-attachments/assets/929f05f1-cd0d-4fc9-bbed-86c5884b5011)

8. Kamu bisa pergi kembali ke bagian depan cPanel, dan pergi ke bagian Databases. Jika kamu ingin memeriksa databases sudah ada di web tersebut, kamu tinggal pergi ke phpMyAdmin
    
![image](https://github.com/user-attachments/assets/85d8d07a-46e4-4150-afff-68f1e05e5be7)

9. Database sudah dibuat
    
![image](https://github.com/user-attachments/assets/447444a9-be9d-4931-8c03-f003433d632d)

## proses instalasi
Kita bisa menginstall WebApp ini melalui cPanel, tapi sebelum itu, mari kita install folder Easy!Appointments terlebih dahulu:

- Pergi ke GitHub Repository dari Easy!Appointments, lalu pergi ke bagian Code, yang ditunjukkan dengan tombol berwarna hijau tersebut
  
![image](https://github.com/user-attachments/assets/20fb8f01-8342-4b65-87f1-4b747a868643)

- Lalu pergi untuk mendownload format ZIP dari folder Easy!Appointments
  
![image](https://github.com/user-attachments/assets/10baf9fc-095f-4389-8989-7b23380578be)

- Folder WebApp sudah didownload
  
![image](https://github.com/user-attachments/assets/bac25688-344a-4fa2-bc17-306c5c492de7)

- Setelah itu kita pergi ke cPanel, dan pergi ke bagian Files. Setelah itu, pergi ke File Manager
  
![image](https://github.com/user-attachments/assets/2a118a3a-ec3e-41f1-ac7c-1241ad0e387f)
![image](https://github.com/user-attachments/assets/10c6a243-a3a8-4466-8fea-aea2ab1961a2)

- Kita bisa mengupload ZIP dari Easy!Appointments yang telah kita download. Sebelum itu, kita pergi ke bagian Upload yang telah digaris bawahi tersebut.
  
![image](https://github.com/user-attachments/assets/d0c3c60e-fd69-4172-a5f8-4c8f9a66b004)

- Kita bisa pergi ke Select File untuk mengupload dari PC
  
![image](https://github.com/user-attachments/assets/bdadfa9b-9b59-4027-bf52-6deab585d3dd)

- Cari folder ZIP dari Easy!Appointment, dan pilih untuk Upload
  
![image](https://github.com/user-attachments/assets/9de659d7-10b6-4a53-a289-b59ce06c05f1)

- Kita menunggu folder ZIP diupload, setelah diupload. Kita kembali ke bagian FIle Manager dengan pergi ke bagian yang telah digaris bawahi.
  
![image](https://github.com/user-attachments/assets/52495b66-6fcd-44f9-a389-f8378dc680d2)

- Setelah file ZIP diupload, kita bisa mengekstrak folder tersebut. Kamu tinggal pilih file ZIP dan klik kanan mouse kalian, klik Extract untuk mengekstrak file tersebut. Klik Extract Files dan Folder akan muncul.
  
![image](https://github.com/user-attachments/assets/d716dc94-a86e-4385-9baa-60fc4954bd99)
![image](https://github.com/user-attachments/assets/555e0122-5561-4ebe-9059-8931f521c494)
![image](https://github.com/user-attachments/assets/43bce1c7-be2f-43d9-8c2f-046f03e74bc0)

- Sebelum itu, mari kita pergi folder Easy!Appointments, dan kita bisa klik config-sample.php di bagian terdepan folder, edit nama/rename dari file tersebut menjadi config.php.
  
![image](https://github.com/user-attachments/assets/7c316aa8-68c8-425a-9535-85006284763e)

- Klik config.php, kita bisa mengedit file tersebut. Sebelum itu klik file dan pergi untuk edit yang telah digaris bawahi
  
![image](https://github.com/user-attachments/assets/9315ec7d-4d14-44a6-932f-4b69eea8621c)

klik edit

![image](https://github.com/user-attachments/assets/fa6281c9-32ba-4868-b8fe-d16cb4a36c5b)

page ini akan muncul

![image](https://github.com/user-attachments/assets/e78eb353-0b54-441b-8118-af4353b5fd9d)

- Kita bisa pergi ke bagian DATABASE SETTINGS dari config.php tersebut. Setelah itu, kita bisa memasukkan:
  - DB_HOST = ‘localhost’; (default akan 127.0.0.1 atau localhost)
  - DB_NAME = nama database yang telah dibuat (bisa dicek diatas untuk bagian Databases)
  - DB_USERNAME = nama User yang telah dibuat (bisa dicek diatas untuk bagian Databases)
  - DB_PASSWORD = password yang sudah dibuat bersamaan dengan User (bisa dicek diatas untuk bagian Databases)





















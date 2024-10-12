<p align="center">
  <img src="https://github.com/user-attachments/assets/d2294a6f-b471-4564-b2fa-fdcf929f2fa3" alt="Easy!Appointments">
</p>

# Easy!Appointments Project KDJK Kelompok 1 P3
Anggota Kelompok 1 - P3:
| Nama                     | NIM        |
|--------------------------|------------|
| Muhammad Irsyad Fadhillah  | G6401221053  |
| Vergiawan Zhaki Rasendria | G6401221101  |
| Rusydi Balfas             | G6401221104  |
| Muhammad Eishaf Athallah  | G6401221105  |
| Rizky Rasyid Wirakusuma   | G6401221127  |

## Sekilas Tentang
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

## Proses Instalasi
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
    (optional) Kamu bisa mengubah BASE_URL tersebut dengan “http://namadomainanda.my.id/easyappoint. (.my.id bisa diubah tergantung dari domain anda kamu belinya apa).
    
![image](https://github.com/user-attachments/assets/f2ffb462-33cb-4515-b7a5-92f7eaa8750a)

Setelah diedit, kamu bisa menyimpan ubahan tersebut ke SAVE CHANGES dengan tombol berwarna biru yang berada di bagian pojok kiri atas dari web

![image](https://github.com/user-attachments/assets/a489bc37-ae71-47a1-b83d-45c9cdadbd64)

KIta bisa pergi ke domain kita yang sudah dibuat (ex: https://kdjkkel1p3.my.id/easyappoint), saat pertama kali menelusuri domain tersebut, kita akan ditujukan kepada bagian installation dari Easy!Appointment.

![image](https://github.com/user-attachments/assets/71d93d59-71d9-41f5-958d-269d1a6dc6de)

Silahkan isi;
  - First name & last name
  - Email
  - Phone Number
  - Username & Password untuk login sebagai admin di domain tersebut
  - Language (default English)
  - Company Name, Email, dan Link
Pergi ke bagian bawah web, dan install Easy!Appointments
    
![image](https://github.com/user-attachments/assets/3d85bc91-53fd-4cbd-883c-8d56748897f3)

- Selamat datang di Easy!Appointments;
  **Bagian Admin dari Web**

  ![image](https://github.com/user-attachments/assets/3910c8d2-05ee-4254-af51-710e675c946a)

  **Bagian User dari Web**


![image](https://github.com/user-attachments/assets/9b6e3170-bf06-41f6-b198-249f43416306)

## Otomatisasi:

Untuk mempermudah Instalasi, kita bisa menginstall Easy!Appointments melalui Softaculous, cari dengan searchbar pada kategori others.


![image](https://github.com/user-attachments/assets/588edf8f-890c-46a2-bdbb-646068aeb375)

![image](https://github.com/user-attachments/assets/5ec26fa7-90bc-487d-a65c-37a4f23318bb)

# Cara Pemakaian

Setelah instalasi, pengguna dapat mengakses Easy!Appointments melalui browser dengan domain yang telah disebutkan. Antarmuka aplikasi akan menampilkan berbagai fungsi utama, termasuk:
- Memilih Service dan Provider

![image](https://github.com/user-attachments/assets/0639452b-90d1-4034-a988-d55bb47d5524)

- Memilih tanggal dan waktu untuk janji temu dengan orang pada perusahaan tersebut, kita juga bisa memilih timezone sesuai dengan wilayahnya.

![image](https://github.com/user-attachments/assets/5b379aaf-998f-4271-a3eb-3752cafe78b5)

- Setelah memilih tanggal dan waktu janji temu, kita bisa menekan next. Setelah itu, kita bisa mengisi datamu yang ingin janji temu dengan orang di perusahaan tersebut.

![image](https://github.com/user-attachments/assets/3366936a-0db3-4a77-9b83-8821179d6940)

Setelah diisi, tekan next:

![image](https://github.com/user-attachments/assets/4c401799-d844-4471-a4a8-2dfd28064de3)

- Konfirmasi untuk data-data dan tanggal & waktu yang sesuai yang diinginkan, setelah itu tekan confirm. Jika ada kesalahan data, kita bisa tekan back untuk memperbaiki data yang salah

![image](https://github.com/user-attachments/assets/88e86b83-ece5-40fd-adc7-228aceb832db)

- Appointments sudah didata di dalam database! Kita bisa pergi ke Booking Page atau menyimpan di Google Calendar

![image](https://github.com/user-attachments/assets/3a53e9a0-9603-4df4-bd93-9e7e9952d361)

Tampilan kalendar:

![image](https://github.com/user-attachments/assets/90208a2e-529f-42a1-886a-9f3c62296c2d)

# Maintenance

Saat kita ingin melakukan maintenance atau perbaikan dalam WebApp Easy!Appointments, tentunya kita tidak ingin customers atau pengguna melakukan aktivitas seperti membuat janji temu. Sebelum melakukan itu, mari kita matikan booking untuk sementara dengan caranya;
- Pergi ke bagian depan WebApp atau bagian Calendar. Setelah itu, pergi ke bagian nama anda yang berada di pojok kiri atas. Lalu, pergi ke Settings.

![image](https://github.com/user-attachments/assets/61f284b4-1c8a-4632-a741-d87197a62e05)

![image](https://github.com/user-attachments/assets/e0263e34-bd45-4f74-9bf2-ed6093e37101)

- Dibawah ini adalah tampilan dari Settings di Easy!Appointments, pergi ke bagian Booking Settings

![image](https://github.com/user-attachments/assets/99932859-a15c-4caa-bf59-71bc02f8e8fa)

- Pergi ke bagian bawah dari Web dan lihat bagian Options, bagian itu memiliki opsi yang bernama Disable Booking. Itu adalah bagian Maintenance untuk Easy!Appointment, tinggal tekan atau turn on untuk Disable Booking tersebut

![image](https://github.com/user-attachments/assets/7db74feb-f962-4226-9dad-ca6ac99c4e31)

![image](https://github.com/user-attachments/assets/34506163-93e0-453b-bfd8-31e9e07b7517)

Jangan lupa untuk tekan save di bagian paling atas dari bagian tersebut sebelah tulisan Booking Settings

![image](https://github.com/user-attachments/assets/f093490b-14a5-4b78-87bd-5dd37e44317e)

- Tampilan ketika Easy!Appointments sedang Maintenance

![image](https://github.com/user-attachments/assets/64dc2abc-94ce-49c0-891c-c492213aecff)

saat Maintenance kamu bisa melakukan beberapa hal, seperti pada bawah ini:

1. Menambah Fitur / Service Baru
  - Pergi ke bagian Services

    ![image](https://github.com/user-attachments/assets/d007c9b2-6abe-4454-92b8-e60cbe50c833)

  - tekan service
    
    ![image](https://github.com/user-attachments/assets/06b22514-afce-4cb4-ae0f-d4526716e525)

  - Tekan Add untuk menambah Services baru

    ![image](https://github.com/user-attachments/assets/28d9c252-972f-445c-bc40-f4c1db93ae62)

  - Isi dengan deskripsi yang telah dipikirkan

    ![image](https://github.com/user-attachments/assets/18a534c6-6fb7-4161-b29b-72afe1cac4d4)

    ![image](https://github.com/user-attachments/assets/cc21921f-0901-4a7b-8535-7235d631b267)

    ![image](https://github.com/user-attachments/assets/819aa1e0-60e3-43ef-9ceb-eb720eebc9dc)
    
    Jangan lupa untuk tekan save di bagian atas
  - service sudah ditambahkan

    ![image](https://github.com/user-attachments/assets/9ca84aa6-5ff0-4674-a642-ef532bfcc38c)
2. Menambah Kategori Baru untuk Service yang Cocok
  - Pergi ke Bagian Service seperti tadi, namun sekarang kita pergi ke bagian Categories

  ![image](https://github.com/user-attachments/assets/ac29478a-6abf-422d-8a4b-d475efa11b70)

  - Tekan Add untuk menambah Kategori

    ![image](https://github.com/user-attachments/assets/0c4b7f96-df50-4890-9c19-f805cb944926)

  - Isi dengan Nama dan Deskripsi Kategori yang diinginkan, dan kategori berhasil ditambahkan

    ![image](https://github.com/user-attachments/assets/c0a4c770-e5a6-40e6-8e7b-c4df40e500e3)

3. Menambah / Menghapus Provider, Secretary dan Admin
   - Pergi ke bagian Users, terdapat 3 bagian yaitu Provider, Secretary, dan Admin. Ketiganya memiliki kegiatan yang berbeda.

     ![image](https://github.com/user-attachments/assets/3c782578-2fc1-4f1c-8874-7cb0821a416d)

   - Tekan Add untuk menambah User;

    ![image](https://github.com/user-attachments/assets/5852f1f3-50da-49af-81d6-682b5028e531)

   - Isi data User...
     - Untuk Provider

       ![image](https://github.com/user-attachments/assets/a402f35f-00bf-4c6c-b475-cfec42cbb261)

     - Untuk Secretary

       ![image](https://github.com/user-attachments/assets/fdc28a65-1402-4688-b8b5-3025a5a07451)

     - Untuk Admin

       ![image](https://github.com/user-attachments/assets/90766ccd-2707-47d6-8f98-b30b8b3c2ba9)

 4. Merubah / Menghapus Jadwal
      - Pergi ke Jadwal yang ingin diubah / dihapus, click jadwal tersebut

        ![image](https://github.com/user-attachments/assets/13582eec-4dac-4b64-b527-51551821c3df)

      - Akan muncul tampilan seperti ini, ada pilihan untuk edit dan delete

        ![image](https://github.com/user-attachments/assets/b32f46e7-8480-4937-b70e-a92525faf2ed)

      - Tampilan untuk edit appointment

        ![image](https://github.com/user-attachments/assets/113166a2-4acf-4f65-9c5c-21104851fca3)

      - Tampilan untuk menghapus appointment
        akan diberikan konfirmasi sebelum menghapus

        ![image](https://github.com/user-attachments/assets/4e3e2e9e-8352-4840-8fce-26bfc74434b0)

        Jadwal berhasil dihapus


        ![image](https://github.com/user-attachments/assets/01465065-c8ad-47c9-a664-c838cdfacfb6)

5. Mengubah / menghapus Data Pribadi Customers
     - Pergi ke bagian Customer

       ![image](https://github.com/user-attachments/assets/1ea4515b-21a2-46cb-98b1-12ff660919cf)

     - Pilih Customer yang ingin diubah datanya

       ![image](https://github.com/user-attachments/assets/0a9fd6db-b8a3-4f33-b92e-d09733134102)

       Tampilan ketika customer sudah dipilih


       ![image](https://github.com/user-attachments/assets/ed8ada7e-9851-45a2-9b8c-fbac83ef7c68)

     - Pilih edit atau delete di sebelah Add Customer
       Tampilan edit

       ![image](https://github.com/user-attachments/assets/36bb6c92-213e-4394-9960-10a96ded77ff)

    - Tampilan konfirmasi ketika ingin mendelete customer

      ![image](https://github.com/user-attachments/assets/535be74f-b41a-430a-bd85-50af03ad0875)

      Customer berhasil didelete

      ![image](https://github.com/user-attachments/assets/89fe644d-3037-4bcf-8ab5-a2019fc02f0f)

Setelah maintenance jangan lupa untuk; 
  1. Kembali ke bagian Settings
  2. Booking Settings
  3. Pergi ke bagian bawah sampai ke bagian Options
  4. Cari Disable Booking
  5. Turn off kembali Disable Booking tersebut.

# Pembahasan

Kelebihan dari Easy!Appointments;
1. Gratis dan Modifikasi. Dapat diakses tanpa biaya lisensi dan dapat diubah sesuai dengan persyaratan.
2. Sinkronisasi. dapat disinkronkan dengan Google Calendar dan dengan mudah dapat disusun kembali.
3. User-friendly. memudahkan penggunaan bahkan untuk pengguna yang kurang akrab dengan keterampilan teknis yang diperlukan.
4. Jumlah Pengguna. memungkinkan pengguna yang banyak dan dengan peran yang berbeda dan tersusun untuk berbagai jenis layanan.
5. Data pelanggan, riwayat janji, dan catatan.
6. Pengingat otomatis dapat dikirim ke pengguna dan klien melalui email.

Kekurangan dari Easy!Appointments;

1. Tidak ada API terperinci yang memungkinkan integrasi mudah dengan perangkat lunak lain. Ini tidak sekompleks solusi komersial yang lebih besar seperti appointment scheduling software premium.
2. Tidak ideal untuk perusahaan besar. Terlalu sederhana untuk perusahaan besar dengan kebutuhan manajemen janji temu yang lebih kompleks, bahkan jika disesuaikan.
3. Jika pengguna ingin menggunakan versi mandiri, mereka harus menyediakan server atau hosting mereka sendiri.
4. Dukungan terbatas. Karena merupakan solusi open-source, dukungan resmi untuk solusi ini terbatas dan lebih mengandalkan komunitas.
5. Tidak ada dukungan aplikasi perangkat seluler. Tidak ada dukungan aplikasi untuk perangkat seluler, meskipun antarmukanya dapat diakses melalui browser pada perangkat seluler.

Hal yang membuat Easy!Appointment bisa dibandingkan dengan WebApp yang sejenis;

1. Easy!Appointments adalah open-source, membuatnya menarik dibandingkan layanan berbayar seperti Acuity Scheduling atau Calendly, terutama untuk usaha kecil yang ingin solusi penjadwalan tanpa biaya berlangganan.
2. Karena pengguna dapat meng-host sendiri, Easy!Appointments memberi kontrol penuh atas data dan penyesuaian. Ini berbeda dengan layanan SaaS (Software as a Service) seperti Calendly, di mana kustomisasi dan akses data sering dibatasi oleh platform.
3. Easy!Appointments memiliki integrasi dengan Google Calendar, fitur yang juga ditawarkan oleh banyak penyedia lain, membuatnya kompetitif dalam hal kemudahan sinkronisasi jadwal.
4. Mendukung banyak pengguna dan layanan, mirip dengan aplikasi seperti SimplyBook.me dan Setmore, menjadikannya cocok untuk bisnis yang membutuhkan sistem penjadwalan untuk beberapa staf atau layanan yang berbeda.
5. Meskipun fitur-fiturnya tidak selengkap aplikasi komersial besar, antarmuka Easy!Appointments dirancang sederhana, mirip dengan layanan seperti 10to8 atau Doodle, yang fokus pada kemudahan penggunaan.
6. Kemampuan untuk mengirim pengingat otomatis melalui email memberikan fungsi dasar yang sama dengan layanan premium seperti Appointy atau Zoho Bookings.
7. Meskipun sederhana, Easy!Appointments menawarkan fitur manajemen klien dasar (riwayat janji, catatan pelanggan), menjadikannya sebanding dengan beberapa aplikasi penjadwalan yang lebih lengkap seperti Square Appointments.

# Referensi
- https://github.com/alextselegidis/easyappointments.git
- https://easyappointments.org/
- https://developers.easyappointments.org/
- https://www.youtube.com/watch?v=_UI7ihEWk6k

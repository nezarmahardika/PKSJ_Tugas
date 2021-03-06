## Instalasi Ubuntu Desktop

#### Requirement

1. Virtual Box \([https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)\)
2. Ubuntu Desktop \([https://www.ubuntu.com/download/desktop](https://www.ubuntu.com/download/desktop)\)

#### Langkah-langkah Instalasi

* **Step 1** : Install Virtual Box.
* **Step 2** : Buka Virtual Box. ![](/assets/ubuntu-server/1.PNG)
* **Step 3** : Membuat Virtual Machine baru dengan menekan tombol New. Setelah menekan tombol New, maka akan muncul dialog Create Virtual Machine. Isi nama Virtual Machine, pilih _type_ sistem operasi dan pilih varsi arsitektur OS. Kemudian tekan tombol next. ![](/assets/ubuntu-desktop/1.png)
* **Step 4** : Atur _memory_ _Virtual Machine_ yang akan dibuat. Contohnya atur memory sebesar 1024MB Kemudian tekan tombol next. ![](/assets/ubuntu-desktop/2.png)
* **Step 5** : Setelah mengatur _memory_, langkah selanjutny adalah memilih _storage_. Pilih opsi _Create a virtual hard disk now_. Kemudian tekan tombol _Create_. ![](/assets/ubuntu-desktop/3.png)
* **Step 6** : Pilih opsi _VDI_ pada saat memilih format file _hardisk_. ![](/assets/ubuntu-desktop/4.png)
* **Step 7** : Setelah memilih opsi _Storage_ kemudian akan muncul dialog tipe _Storage_. Pilih opsi _Dynamically allocated_. Kemudian tekan tombol _next_. ![](/assets/ubuntu-desktop/5.png)
* **Step 8** : Atur kapasitas _Storage_ _Virtual Machine_. Kemudian tekan _Create_. ![](/assets/ubuntu-desktop/6.png)
* **Step 9** : _Virtual Machine_ sudah dibuat. ![](/assets/ubuntu-desktop/7.png)
* **Step 10** : Langkah selanjutnya adalah menambahkan file iso Ubuntu Server dan konfigurasi network Virtual Machine agar mendapatkan IP sendiri. Klik pada _Virtual Machine_ yang akan kita gunakan. Kemudian klik kanan dan tekan _Settinsg_. Setelah itu akan muncul dialog _Settings_. ![](/assets/ubuntu-desktop/8.png)
* **Step 11** : Klik pada menu _Storage_, kemudian pada _Controller: IDE_ pilih icon _CD_ untuk menambahkan iso Ubuntu Server. ![](/assets/ubuntu-desktop/9.png)
* **Step 12** : Pilih iso Ubuntu Dekstop dan klik tombol _Open_. ![](/assets/ubuntu-desktop/pilih-iso.png)
* **Step 13** : Pada _Controller: IDE_ akan muncul _disc_ Ubuntu Dekstop. ![](/assets/ubuntu-desktop/iso.png)
* **Step 14** : Langkah selanjutnya adalah konfigurasi interface internet _Virtual Machine_. Pada pilihan _Attached to_, pilih _Bridged Adapter_. Setelah itu pilih interface komputer yang akan dijadikan bridge. Setelah selesai konfigurasi interface, tekan tombol OK. ![](/assets/ubuntu-desktop/10.png)
* **Step 15** : Jalankan virtual machine yang telah dibuat, lalu virtual machine akan menampilkan installasi dari Ubuntu Desktop ![](/assets/ubuntu-desktop/install-1.png)
* **Step 16** : Pilih Install Ubuntu
* **Step 17** : Lalu Pilih Continue ![](/assets/ubuntu-desktop/install-2.png)
* **Step 18** : Pilih _Erase Disk and install Ubuntu_ lalu klik _Continue_ ![](/assets/ubuntu-desktop/install-3.png)
* **Step 19** : Setelah itu installer akan menampilkan dialog konfirmasi untuk partisi disk yang akan di _Erase_ ![](/assets/ubuntu-desktop/install-4.png)
* **Step 20** : Pilih Zona Waktu yang sesuai dengan lokasi anda ![](/assets/ubuntu-desktop/install-5.png)
* **Step 21** : Pilih keyboard layout sesuai pilihan anda ![](/assets/ubuntu-desktop/install-6.jpg)
* **Step 22** : Masukkan hostname dan username serta password anda ![](/assets/ubuntu-desktop/install-7.jpg)
* **Step 23** : Tunggu sampai instalasi selesai ![](/assets/ubuntu-desktop/install-8.jpg)
* **Step 24** : Instalasi Selesai, Silahkan restart virtual machine ![](/assets/ubuntu-desktop/install-9.jpg)
* **Step 25** : Instalasi Ubuntu Desktop selesai dan siap untuk digunakan ![](/assets/ubuntu-desktop/selesai-install.jpg)


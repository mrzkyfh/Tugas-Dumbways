# Apa itu DevOps
DevOps adalah Kombinasi dari DEVELOPMENT dan OPERATION yang bertugas sebagai penghubung antara divisi Development (Programmer) dan Operation (Infrastructure Server). Agar bisa beradaptasi dengan cepat terhadap pembaruan maupun perubahan suatu product dan serta menghilangkan hambatan Komunikasi antara tim Development dan Operation, sehingga pada saat Deployment nantinya akan lebih konsisten dan lancar.




***
# Cara install ubuntu di vmware ( virtual machine )





**1. Pertama memasukan iso terlebih dahulu**

![Screenshot (78)](https://user-images.githubusercontent.com/111843016/186298779-1c06c8d0-c61d-4b9e-9652-f2185e3ecdbf.png)



**2. lalu memilih nama, user name, dan password**

![Screenshot (53)](https://user-images.githubusercontent.com/111843016/186299296-c65b857c-fb52-47f1-af84-6e4cfedce999.png)



**3. Menentukan lokasi dimana Virtual machine kalian ingin disimpan**

![Screenshot (54)](https://user-images.githubusercontent.com/111843016/186300115-4ccad0bf-fec5-4282-b6bc-e6c5685e756a.png)



4. **Atur size disk yang ingin kalian gunakan**

**Keterangan :**

**Store Disk as a single file** maksudnya adalah disk yang kalian buat itu nantinya akan langsung terbuat 10Gb. (ini tidak disarankan untuk pengguna yang memiliki hardisk yang berkapasitas kecil).

**Split virtual disk into multiple files** maksudnya adalah disk yang kita pakai untuk virtual machine kita nantinya itu akan dibagi menjadi beberapa bagian. Jadi walaupun kita menggunakan disk berkapasitas 10Gb itu nanti tidak akan terpakai seluruhnya.

![Screenshot (55)](https://user-images.githubusercontent.com/111843016/186364646-75d15453-8f51-4025-bc21-891be4a40406.png)


5. **Lalu kita meng-customisasi hardware untuk server kita, tekan saja di bagian Customize Hardware**

![Screenshot (63)](https://user-images.githubusercontent.com/111843016/186365634-6a5ff524-05fb-4a1b-a994-b89b12ea7712.png)


6. **Disini ada beberapa pilihan untuk kita melakukan customisasi seperti Memory, Processors dan Network adapter.**

**Keterangan:**

Memory berfungsi untuk penyimpanan data yang ingin kita gunakan untuk Virtual Machine yang ingin kita buat. Disini kita pilih gunakan saja defaultnya yaitu sebesar 4Gb tetapi misalkan kalian merasa kurang kalian boleh untuk menaikkannya sesuai keinginan kalian.
Processors adalah salah satu komponen penting untuk Virtual Machine yang ingin kita bangun, serta berfungsi untuk memproses data dan mengontrol sistem yang ada pada Virtual Machine kita. Disini kita menggunakan defaultnya saja yaitu sebesar 2 core.
Network adapter berfungsi untuk menghubungkan komputer ke jaringan. Untuk penjelasan lebih lanjut ada di poin berikutnya.
Jika sudah selesai untuk meng-setting memory dan processor, kalian bisa pergi ke bagian Network Adapter. Setelah itu ubah dari defaultnya yaitu NAT menjadi Bridge.

**Keterangan:**

kalau menggunakan NAT nantinya server yang kita buat ini akan mendapatkan IP yang sudah di sediakan oleh Virtual Machine kita.
Kalau Menggunakan Bridge nantinya server yang kita buat akan mendapatkan IP dari internet yang sedang kita gunakan.

Setelah itu klik close lalu tekan finis

![Screenshot (64)](https://user-images.githubusercontent.com/111843016/186365832-e2985376-bd0b-4077-9b20-0e6c6bf7fa97.png)


7. **Tunggu instalasi sampai selesai **


![Screenshot (80)](https://user-images.githubusercontent.com/111843016/186367891-c9b20f65-0249-47e4-8890-f22f2cc7dce9.png)


8. **lalu di sini kita bisa memilik bahasa english**

![Screenshot (81)](https://user-images.githubusercontent.com/111843016/186368034-4a7d08cd-fdf4-44e8-9df8-0b67bf966125.png)


9. **lalu di sini tingal pencet done saja**

![Screenshot (84)](https://user-images.githubusercontent.com/111843016/186369002-ea5af8fc-88c3-4cb2-9ae7-576f3b484dc6.png)
![Screenshot (85)](https://user-images.githubusercontent.com/111843016/186369026-bebd2aad-855e-47a0-a1ae-04035ce3fcbd.png)


10. **selanjutnya kita akan ubah konfigurasinya dari yang awalnya itu DHCPv4 menjadi Static.**

Keterangan:

DHCP (Dynamic Host Protocol Configuration) : Alamat IP yang dapat berubah-ubah pada perangkat yang tersambung setiap kali terhubung kembali pada jaringan tersebut (otomatis).

Static : Alamat IP tidak berubah-ubah dari yang telah diberikan oleh adminisitrator (setting manual)

![Screenshot (86)](https://user-images.githubusercontent.com/111843016/186372405-c6a5a6ba-ea75-4f65-86ea-d25fc8645d34.png)

11. Pilih di bagian ens33, setelah itu pada bagia IPv4 Method ubah dari yang awalnya automatic menjadi manual. Setelah itu masukan detail IP pada form yang tersedia(kalian bisa masukkan saja IP yang sudah tertera di bagian DHCPv4). Jika sudah langsung tekan saja Save.

**Keterangan:**

Subnet : Istilah teknologi Informasi yang membedakan Network ID dan Host ID atau sebagai penentu porsi Network ID dan Host ID pada deretan kode biner.

**Address** : Alamat IP yang akan digunakan untuk Virtual Machine yang akan kalian buat. (kalian dapat mengisi bagian ini dengan IP yang sudah ada di bagian DHCP).

**Gateway** : Perangkat komputer yang berfungsi untuk mengkoneksikan sebuah Jaringan komputer terhadap satu jaringan komputer yang lain.

**Name servers** : Dibagian Name servers ini kalian cukup memasukkan IP DNS dari google supaya dapat terhubung dengan browser. 


![Screenshot (87)](https://user-images.githubusercontent.com/111843016/186372852-20563475-2b4c-4dfc-85e2-6c147fdeaeac.png)

12. **ini tinggal done aja**

![Screenshot (88)](https://user-images.githubusercontent.com/111843016/186388582-bd46a5e0-45e5-4ce3-811e-93fbba9dc3dc.png)
![Screenshot (89)](https://user-images.githubusercontent.com/111843016/186388587-da26eba6-4a7d-4400-b89c-dd3f398217bd.png)

13. **Disini kita dapat memilih bagian Custom storage layout. Kenapa kita memilih Custom storage layout karena kita akan membuat 2 buah partisi, jika sudah kalian pilih setelah itu langsung saja klik Done.**

![Screenshot (90)](https://user-images.githubusercontent.com/111843016/186388836-0009ecd8-49c2-4b0c-84df-7cfb3f4c92de.png)

14. Selanjutnya disini kita akan membuat 2 buah partisi untuk root dan swap. Langsung pilih saja di bagian /dev/sda lalu pilih di bagian Add GPT Partition. Untuk kapasitasnya kalian bisa samakan saja dengan gambar dibawah (kecuali untuk swap, kalian bisa setting semau kalian apabila merasa kurang).

**Keterangan :**

Root adalah tempat dimana sistem kita itu ter-install.

Swap adalah suatu memory cadangan yang akan digunakan untuk server kita apabila memory utama sudah penuh. 

![Screenshot (91)](https://user-images.githubusercontent.com/111843016/186388844-fb40d75a-ad6b-4add-897e-5a2d2a1052cf.png)

15. **Selanjutnya masukan informasi seperti nama, username, dan password untuk server yang kalian buat. Jika sudah klik saja Done.**

![Screenshot (92)](https://user-images.githubusercontent.com/111843016/186397994-7d8defd1-64c6-42d6-9b13-ee710ade3b4e.png) 

16.** Ditahapan ini jangan lupa untuk checklist bagian Install OpenSSH server gunanya adalah untuk me-remote server yang kita buat.**

![Screenshot (94)](https://user-images.githubusercontent.com/111843016/186398231-49c05c4a-96c2-4911-ab45-c1be67179c51.png)


17. **Pada tahap selanjutnya skip dengan klik Done.** 

![Screenshot (95)](https://user-images.githubusercontent.com/111843016/186398338-08bb94ae-a12c-4274-a497-6f3cf50280b7.png)

18. **Kita sudah selesai untuk tahapan instalasinya. Tunggu saja proses instalasi sampai selesai jika sudah selesai langsung saja klik Reboot Now.**


![Screenshot (96)](https://user-images.githubusercontent.com/111843016/186398343-04d2403f-5628-4b56-af73-947cb21e2eeb.png)


19. **Untuk make sure apakah server yang kalian buat ini sudah terhubung ke dalam internet bisa gunakan perintah dibawah ini**

**ping google.com**

Jika server kalian sudah terhubung ke dalam internet maka akan muncul seperti gambar dibawah ini.

![Screenshot (97)](https://user-images.githubusercontent.com/111843016/186399291-c7889f64-d750-480a-9b2e-39417847c585.png)

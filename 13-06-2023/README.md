1. text manipulation secara umum bagaimana kita memanipulasi teks tanpa menggunakan teks editor. terdapat beberapa command yang bisa kita gunakan sebagai text manipulation

 cat
 
 1.cat namafile=untuk melihat file
 
 2.cat > namafile = untuk mengubah file tanpa nano
 
 3.cat file1 file2 > filegabungan = untuk menggabungkan dua file jadi satu file
 
 
 ![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/981d15fe-1f24-4085-bad6-ae161eccd855)
 
 
sed

1.sed 's/katalama/katabaru/g' file = untuk mereplace kata

 ![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/431e18a6-5612-4cf8-bd52-5c27c5ec2857)
 
 
grep

1.grep kata file = untuk mencari kata pada file

2.grep -c kata file = untuk menghitung jumlah kata pada file

3.grep kata * = untuk mencari file yang berisi kata 

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/398bf76d-754a-4764-b5b4-3356a76aa43e)


sort

1.sort file / sort -r file (reverse) = untuk mengurutkan berdasarkan abjad atau angka

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/03d7a48a-0388-4e1c-902d-fee0ae31ecfe)


awk

1. awk '{print $1}' file = untuk menampilkan kata, baik kata pertama kedua atau seterusnya

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/0ac12274-79cc-4aaf-a366-acc28b529d54)


cut

1.cut -b 1 file = untuk mengambil huru pertama, kedua atau seterusnya

2.cut -c 1,2,3 file = untuk mengambil beberapa huruf pada urutan tertentu

3.cut -d " " -f 1 file = untuk mengambil kata pada file tertentu 

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/89a9ca38-46d3-4299-b90d-5d8cbeca70ab)


echo

1.echo "kata kata" = untuk mencetak kata 

2.echo "kata kata" > file = untuk mereplace isi file dengan kata 

3.echo "kata kata" >> file = untuk menambahkan isi file dengan kata 

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/1d5667e5-2fc6-49f9-b34e-6ed8d0a602b1)

htop

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/c5b5adec-f2b6-4c76-ae5c-91d97df4b715)

CPU = jumlah core yang kita miliki.

Mem = total penggunaan memory.

Swp = Memory cadangan.

Tasks = aplikasi yang sedang berjalan di server.

Load average = rata-rata aplikasi yang berjalan.

Uptime = berapa lama server kita hidup.

PID = nomor proses id setiap proses yang berjalan di linux.

VIRT = memory yang terpakai.

Command = perintah apa yang sedang di jalankan.

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/b0efd1f2-a2d0-4c12-af98-9efef9b93f42)

 command f1 sampai f10 harus digunakan menggunakan fn+f1 dst
 
 help = untuk mengetahui lebih lanjut mengenai tool di htop atau informasi tentang htop
 
 ![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/2aab4d42-8c4d-4773-a4b4-48628d1b1adc)

 
 setup = untuk mengatur htop baik pada tampilan maupun informasi yang ingin ditampilkan pada kolom dan baris monitoring
 
 ![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/dd5263f6-d7a5-4fc2-aed2-9acd5f030587)

 
 search = untuk mencari proses, user, command dengan nama tertentu
 
 ![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/21308559-7ef5-4232-b677-b6dcfa57172f)

 
 filter = untuk memfilter command, proses, user dengan nama tertentu
 
 ![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/5578406f-b74c-4a26-a8de-0cd296861bce)


tree = untuk menampilkan cabang command

![image](https://github.com/kevinhariya/devops17-dumbways-kevin/assets/135611481/cf93b919-4082-419f-9ab3-c16e6377b7e3)


sortby = untuk mengurutkan berdasarkan karateristik tertentu seperti pada gambar





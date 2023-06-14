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
2. 
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


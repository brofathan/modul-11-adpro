# Reflection <br>

Nama: Emir Mohamad Fathan <br>
NPM: 2206081982 <br>

<hr>

## Hello Minikube

1. Run before and after expose service

Before
![image](https://github.com/brofathan/modul-11-adpro/assets/45114836/09fb12b0-094c-4847-b037-5ba27eec36ac)

After
![image](https://github.com/brofathan/modul-11-adpro/assets/45114836/ffd35a39-71cf-441d-8afd-5f54cb6c4b32)

Sebelum service dijalankan, kubectl hanya menjalankan server dengan port nya saja. Setelah service minikube dijalankan atau diexpose, kubectl dapat menerima request melalui service tersebut.

2. Fungsi dari flag -n adalah sebagai namespace. Hal ini kita perlukan saat ingin mencari nama service tertentu.

<hr>

## Rolling Update & Kubernetes Manifest File

1. Rolling update merupakan strategi sebuah app deployment pada kubernetes yang selalu melakukan update pada instance aplikasi yang ingin di deploy. Sedangkan recreate strategi mendeploy dengan cara menonaktifkan instance tertentu lalu memulainya lagi.

2. Screenshot for Recreate
![image](https://github.com/brofathan/modul-11-adpro/assets/45114836/d29a4592-0ca9-4866-ad46-842a9f4bba55)
![image](https://github.com/brofathan/modul-11-adpro/assets/45114836/80dda4e3-b798-4c6b-9be2-1b2fda726c30)

3. Screenshot for executing Recreate strategy
start the minikube
![image](https://github.com/brofathan/modul-11-adpro/assets/45114836/d179975a-90a8-4d7c-a9cc-1ba059d866e6)





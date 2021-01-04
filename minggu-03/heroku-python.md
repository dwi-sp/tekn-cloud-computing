# Getting Started on Heroku with Python

## Persiapan

1. [Signup ke Heroku](https://signup.heroku.com/)

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-signup.jpg)

Login ke Heroku

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-login.jpg)

2. Buat aplikasi baru melalui dashboard

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-create-app.jpg)
![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-app-dsp.jpg)

## Getting Started on Heroku with Python

1. [Download Heroku CLI](https://cli-assets.heroku.com/heroku-x64.exe)

2. Install Heroku CLI

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-version.jpg)

3. Mempersiapkan APP

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-clone.jpg)

4. Deploy APP

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-Create.jpg)

5. Deploy Code yang ada

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-Deploy.jpg)

6. Pastikan Aplikasi sudah running

   ![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-psScale0.jpg)
   ![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-psScale1.jpg)

7. Buka APP yang sudah dibuat

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-local-web.jpg)

8. Melihat Logs

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-logs-tail.jpg)

## Mendifine Procfile

1. Install Python dependencies

   ![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-procfile.jpg)

2. Melihat list dependencies

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-psScale0.jpg)

## Declare dependencies dari suatu Aplikasi

1. Check dynous yang running

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-install-requirement.jpg)

2. Scalling aplikasi di heroku dengan mengganti nomor dynous yang running

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-pip-list.jpg)

## Menjalankan Aplikaso secara local

1. Menjalankan colecstatic untuk menjalankan secara local

   ![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-run-app-local.jpg)

2. Star APP Secara Local

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-cek-local-web.jpg)

3. Buka dengan [http://localhost:5000/](http://localhost:5000/)

## Melakukan Perubahan

1. Melakukan perubahan dengan menambahkan dependencies

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-pip-install-req.jpg)

2. Melakukan perubahan di file views.py

   ![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-view1.jpg)

3. Buka Kembali [http://localhost:5000/] setelah melakukan perubahan

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-local-http.jpg)

4. Menyimpan perubahan ke repository di git

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-git-add.jpg)
![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-git-add-2.jpg)

5. Cek di web aplikasi yang sudah dibuat

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-open-app.jpg)

## Penyediaan add-on

### NOTE: untuk add-on diharuskan menggunakan account Heroku yang telah terverifikasi dengan credit card

## Menjalankan di Console

1. Menjalankan di console

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-console.jpg)

2. Chech file yang ada di dyno

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-bash.jpg)

## Define config vars

1. Edit View.py

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-view2.jpg)

2. Buka kembali [http://localhost:5000/] setelah melakukan perubahan

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-run-Local.jpg)

3. Setting config var di Heroku

![alt text](https://github.com/dwi-sp/tekn-cloud-computing/blob/master/minggu-03/gambar/Heroku-config.jpg)

_Referensi: [Getting Started on Heroku with Python](https://devcenter.heroku.com/articles/getting-started-with-python?singlepage=true)_

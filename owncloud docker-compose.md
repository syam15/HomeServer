# Instalasi Owncloud Pada server
Owncloud berfungsi untuk membuat sebuah storage agar bisa berbagi antar local dalam satu jaringan agar pemindahan file lebih cepat

## Cara Installasi

### Membuat Direktori Baru
cara membuatnya adalah
<code>mkdir ~/owncloud</code>
cara masuk ke direktori
<code>cd ~/owncloud</code>

![satu](img/owncloud/1.jpg)

### Configurasi env
configurasi env dengan perintah

<code>nano .env</code>

Lalu Masukkan script berikut

<code>OWNCLOUD_VERSION=10.11
OWNCLOUD_DOMAIN=SERVER:8080
OWNCLOUD_TRUSTED_DOMAINS=(ip server)
ADMIN_USERNAME=(user)
ADMIN_PASSWORD=(password)
HTTP_PORT=8080</code>

![dua](img/owncloud/2.jpg)

### download owncloud yml file untuk docker-compose:
Download owncloud

<code>wget https://raw.githubusercontent.com/owncloud/docs-server/master/modules/admin_manual/examples/installation/docker/docker-compose.yml</code>

![tiga](img/owncloud/3.jpg)
![empat](img/owncloud/4.jpg)

### Install docker-compose
install docker-compose menggunakan perintah

<code>sudo apt install docker-compose</code>

![lima](img/owncloud/5.jpg)

### 


<code>docker-compose up -d</code>

![enam](img/owncloud/6.jpg)


### 


<code>docker-compose up --detach --build</code>

![tujuh](img/owncloud/7.jpg)

### 


<code>docker-compose ps</code>

![delapan](img/owncloud/8.jpg)

### Tampilan Login Pada owncloud
Untuk cara menampilkan atau masuk ke owncloud

<code>https://your_ip:8080</code>

![sembilan](img/owncloud/9.jpg)
![sepuluh](img/owncloud/10.gif)

login dengan akun atau config yang di buat di bagian
<code>nano .env</code>


### Tampilan Dashboard
Tampilan dashboard pada owncloud disini bisa membuat folder dan men sharing nya dengan sesama jaringan dengan akun bisa di kelola oleh admin

![sebelas](img/owncloud/11.jpg)

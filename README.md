# Membangun Home Server dengan ubuntu server

![HomeServer](img/owncloud/10.gif)

## Apa itu Home Server?
Home Server ditujukan sebagai solusi untuk rumahan dengan banyak komputer PC yang terkoneksi untuk menawarkan fitur file sharing, backup otomatis, dan juga akses secara jarak jauh.

## Bahan - bahan yang perlu di siapkan :
- virtualbox
- iso ubuntu server versi 20.04
- jaringan internet

Bagi yang belum mempunyai iso dan juga virtualbox bisa di dapatkan disini :
- https://www.virtualbox.org/wiki/Downloads
- https://releases.ubuntu.com/focal/
- https://mirror.unpad.ac.id/iso/ubuntu/20.04/
- https://kartolo.sby.datautama.net.id/ubuntu-cd/20.04/

## Alur installasi
- Membuat VM ubuntu server dengan virtualbox

<code>https://github.com/syam15/HomeServer/blob/main/installation%20ubuntu%20server%2020.04.md</code>

- Installasi Nginx Untuk kebutuhan deploy

<code>https://github.com/syam15/HomeServer/blob/main/nginx%20web%20server.md</code>

- Installasi docker

<code>https://github.com/syam15/HomeServer/blob/main/docker%20installation.md</code>

- Install owncloud dengan docker-compose

<code>https://github.com/syam15/HomeServer/blob/main/owncloud%20docker-compose.md</code>
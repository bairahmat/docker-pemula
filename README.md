## Install Docker 
### Docker di Server Ubuntu
#### Prasyarat
- Sebuah virtual machine atau server yang yang terinstal system operasi ubuntu 64bit. Untuk catatan 32bit tidak mendukutng
- Versi kernel minimal 3.10 atau lebih tinggi. Untuk mengecek versi kernel. Jalankan perintah “uname -r” dari terminal

Jika versi kernel kurang dari 3.10, upgrade kernel terlebih dahulu dengan menjalankan perintah ini
```
apt-get update
apt-get dist-upgrade –y
```
Untuk memastikan auft storage driver didukung oleh docker, install linux-image-extra paket kernel dengan mengetikan perintah di bawah ini dan reboot server anda ketika selesai
```
apt-get install linux-image-extra-$(uname -r)
```

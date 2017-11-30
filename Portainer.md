### Mengelola Docker menggunakan Portainer
Portainer adalah aplikasi yang ringan, cross-platform, dan open source UI untuk manajemen Docker. Portainer memberikan gambaran rinci tentang Docker dan memungkinkan Anda untuk mengelola kontainer, Docker image, jaringan dan volume masing masing kontainer melalui web dashboard sederhana.

#### Mengelola Docker menggunakan Portainer
##### Install Portainer
Menginstall Portrainer sangat mudah, hanya membutuhkan waktu kurang dari beberapa menit. Portainer mengukung Docker versi 1.10 dan lebih tinggi.
saya mengasumsikan bahwa kita telah menginstall docker pada sistem operasi linux kita, jika sudah maka kita dapat melanjutkan pada tahap berikut ini:

Menjalankan Perintah :
```
sudo docker pull portainer/portainer
```

Contoh output:
```
Using default tag: latest
latest: Pulling from portainer/portainer

a3ed95caeb02: Pull complete 
802d894958a2: Pull complete 
045765bf2706: Pull complete 
Digest: sha256:495cb906c964f746f955b6d03c6235d80e48e1a46773a24b1764c95f03f15079
Status: Downloaded newer image for portainer/portainer:latest
```

Cek apakah Portrainer berhasil di download.
Menjalankan Perintah :
```
sudo docker images
```
Contoh Output :

```
portainer/portainer latest ec91653336d4 7 days ago 9.132 MB
```

# Membuat Web Server Birthday Wishes
Menggunakan Ubuntu Server 20.04 Version

# Langkah-Langkah
1.Instalasi ubuntu server 20.04
2.Install apache2
masuk dalam mode root
$sudo su
masukkan password for ubuntu
$cd
$apt-get install apache2
$ifconfig
ip : 192.168.56.105
$sudo ufw app list
$sudo systemctl start apache2
$sudo systemctl status apache2
Jika status sudah active maka ketika kita memasukkan ip kita pada chrome akan berhasil
3.Merubah tampilan menggunakan html
$cd /var/www/html
$ls
maka akan muncul output index.html
kita buat folder baru dengan nama ainna
$mkdir ainna
Kita cek lagi pada chrome masukkan ip kita ditambah dengan /ainna
http://192.168.56.105/ainna
4.Membuat file html
$ls
$cd ainna
$nano index.html
Masukkan kode program html yang diinginkan,jika sudah selesai klik ctrl+x 
Save modified buffer?Y lalu enter agar tersimpan dan web akan berubah tampilannya





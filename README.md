#  Keamanan Web Server #
Tugas yang di buat pada final project kali ini adalah Keamanan Web Server
![spj](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/1556cfa9-141a-4366-b6d6-f8fceae24c4f)

***

## Apa Itu Web Server? ##
Web server adalah perangkat lunak atau perangkat keras yang menyediakan layanan untuk mengakses halaman web atau konten web melalui internet. Fungsi utama dari web server adalah melayani permintaan dari klien (biasanya browser web) dengan menyediakan halaman web yang diminta. Ketika seseorang mengakses situs web melalui browser mereka, permintaan dikirim ke web server, dan web server ini kemudian mengirimkan halaman web tersebut kembali ke browser pengguna. Untuk contoh dari penggunaannya adalah sebagai berikut :

![Screenshot 2023-12-23 175623](https://github.com/alvingg666/FP/assets/148695999/0222ae1b-9e02-420a-a06f-146650b1bccb)






## OS Server ##
Ubuntu 22.04
***


## Service Yang Digunakan ##
1. SSH 
2. Apache2
3. Firewall ufw
4. Mod Security
5. Snort
6. Cockpit
***
## Panduan Instalasi ##

- Install Git terlebih dahulu

user@WebServer: sudo apt update && upgrade

#

- Dilanjut untuk install Apache2 serta cek status apache


user@WebServer: sudo apt install Apache2
user@WebServer: sudo systemctl status Apache



- Mod Security


user@WebServer: sudo apt install libapache2-mod-security2
user@WebServer: sudo a2enmod security2
user@WebServer: sudo nano /etc/modsecurity/modsecurity.conf
root@user: #SecRuleEngine DetectionOnly 
SecRuleEngine On



- Tambahkan Rule untuk Apache di Firewall


user@WebServer: sudo ufw allow 'Apache'
user@WebServer: sudo ufw status



- Install Mysql

user@WebServer: sudo apt install mysql-server
user@WebServer: sudo mysqk_secure_installation


## Step Pengerjaan #
1.** Install Apache2 **
sudo apt install apache2

2.** Mod Security **
sudo apt install libapache2-mod-security2
sudo apt install libapache2-mod-security2
sudo nano /etc/modsecurity/modsecurity.conf
#SecRuleEngine DetectionOnly 
SecRuleEngine On
sudo systemctl restart apache2

3.** Cockpit **
Apt-get install cockpit
Sudo ufw allow 9090/tcp
Sudo systemctl enable cockpit
Sudo systemctl start cockpit

4.**  Ubah pemilik folder **
sudo chown -R www-data:www-data /var/www/html

5.** Beri ijin anggota grup untuk merubah folder **
sudo chmod -R g+rw /var/www/html

6.** Tambahkan user name kita **
sudo usermod -a -G www-data

7.** Restart ubuntu **

8.** Tambahkan rule untuk apache difirewall **
sudo ufw allow 'Apache'

9.** Cek status firewall **
sudo ufw status

10.** Install ssh **
sudo apt install openssh-server

11.** Install ngrok **
snap install ngrok

12.** Masukkan token authtoken **
ngrok config add-authtoken 2ZlR0DFXPuzK2a1nMQY6ONP1FLn_4oDZYTuGDNHW3jJPJHT5R

13.** Masuk cmd ketikkan **
ssh "username"@"ip ubuntu"

14.** http 80 untuk mendapatkan url ***
ngrok http 80

15.** Untuk mengedit index.html **
masuk folder /var/www/html open menggunakan texteditor 




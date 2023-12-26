## Kelompok 1 ##
# Nama Anggota & Nim #
-Khent Harianto Sandang (22.83.0834)

-Dian Andrian (22.83.0881)

-Riki Nur Indra Putra ( 22.83.0875)

-Aditya Rosprihananta ( 2283.0843)

-Muhammad Ahnaf Maajid (22.83.0884)

-Alvin Rizky Saputra (22.83.0867)
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


## Step Pengerjaan #
1.** Install Apache2 **
sudo apt install apache2

2.** Mod Security **
sudo apt install libapache2-mod-security2

sudo apt install libapache2-mod-security2

sudo nano /etc/modsecurity/modsecurity.conf

root@user#SecRuleEngine DetectionOnly 
SecRuleEngine On

sudo systemctl restart apache2

3.** Cockpit **
Apt-get install cockpit

Sudo ufw allow 9090/tcp

Sudo systemctl enable cockpit

Sudo systemctl start cockpit

4.**  Snort **
sudo apt update

sudo apt install snort

sudo systemctl start snort

sudo systemctl enable snort

sudo systemctl status snort


5.** Firewall **
sudo apt update

sudo apt install ufw

sudo ufw default deny incoming

sudo ufw default allow outgoing

sudo ufw allow 22  # SSH

sudo ufw allow 80  # HTTP







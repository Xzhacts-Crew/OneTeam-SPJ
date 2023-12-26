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

## Dokumentasi ##
![IMG-20231226-WA0001](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/4fa8a0b2-537b-43dd-af64-5c1bb32bb895)
![IMG-20231226-WA0002](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/f2e721e1-9627-4800-8747-010d1a55e94a)
![IMG-20231226-WA0003](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/5db547a4-769c-47da-85f8-44db3febbff7)
![IMG-20231226-WA0004](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/f0ec050a-c590-4396-84eb-ff61f3faf63b)
![IMG-20231226-WA0005](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/df5c6916-1ac8-4b9d-9f34-dd64a1ad3e2b)
![IMG-20231226-WA0006](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/cf7c20ea-3371-47d4-b3f4-c40fdef231dd)
![IMG-20231226-WA0007](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/1cd5c81f-fcde-4828-b98a-848c0c1b5009)
![IMG-20231226-WA0008](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/2cfa80c4-c827-488b-a9ea-663426e21860)
![IMG-20231226-WA0009](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/f083f616-daa9-4e38-a59c-cea94e7029f3)
![IMG-20231226-WA0010](https://github.com/Xzhacts-Crew/OneTeam-SPJ/assets/148695999/f33bd5fc-65eb-41b1-8426-adc207a07871)

## SEKIAN DAN TERIMAKASIH ##










Windows PowerShell
(C) Корпорация Майкрософт (Microsoft Corporation). Все права защищены.

Попробуйте новую кроссплатформенную оболочку PowerShell (https://aka.ms/pscore6)

PS C:\Users\Таисия> ssh taisiia@10.0.3.1
ssh: connect to host 10.0.3.1 port 22: Connection timed out
PS C:\Users\Таисия> ssh taisiia@192.168.169.117
The authenticity of host '192.168.169.117 (192.168.169.117)' can't be established.
ECDSA key fingerprint is SHA256:kqMQ5S1TNLq0yKvEnjy2puLNOKN09uU5qysTvJ1jnqU.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added '192.168.169.117' (ECDSA) to the list of known hosts.
taisiia@192.168.169.117's password:
Welcome to Ubuntu 22.04.1 LTS (GNU/Linux 5.15.0-58-generic x86_64)

 * Documentation:  https://help.ubuntu.com
 * Management:     https://landscape.canonical.com
 * Support:        https://ubuntu.com/advantage

453 updates can be applied immediately.
280 of these updates are standard security updates.
To see these additional updates run: apt list --upgradable

Last login: Thu Feb  9 20:01:24 2023 from 192.168.1.79
taisiia@db:~$ cat > home_animal.txt
Cat
Dog
Humsterd
taisiia@db:~$ cat > pack_animal.txt
Horse
Camel
Donkey
taisiia@db:~$ ls -l
total 152
drwxrwxr-x 3 taisiia taisiia  4096 янв 16  2023  1
drwxr-xr-x 2 taisiia taisiia  4096 сен 13 21:04  Desktop
-rw-rw-r-- 1 taisiia taisiia   361 сен 20 09:39  docker-compose.yml
-rw-rw-r-- 1 taisiia taisiia   125 сен 20 08:48  Dockerfile
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Documents
drwxr-xr-x 2 taisiia taisiia  4096 сен  6 14:25  Downloads
drwxrwx--- 1 root    vboxsf   8192 сен 13 21:04  f
-rw-rw-r-- 1 taisiia taisiia    15 окт  1 10:28  friend_animal.txt
-rw-rw-r-- 1 taisiia taisiia    18 окт  1 10:48  home_animal.txt
-rw-rw-r-- 1 taisiia taisiia   312 фев  8  2023  ls_txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Music
drwxrwxr-x 6 vboxadd vboxsf   4096 сен 20 10:13  mydb
drwxrwxr-x 7 taisiia taisiia  4096 сен  6 13:52  newroot
-rw-rw-r-- 1 taisiia taisiia    19 окт  1 10:49  pack_animal.txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Pictures
-rw-rw-r-- 1 taisiia taisiia   115 фев  9  2023  print100
-rw-rw-r-- 1 taisiia taisiia 48779 сен  6 14:27 'Prostranstva imen'
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Public
drwx------ 5 taisiia taisiia  4096 янв 16  2023  snap
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Templates
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test2
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test3
-rw-rw-r-- 1 taisiia taisiia  1092 сен 20 10:10  text.txt
-rw-rw-r-- 1 taisiia taisiia    57 фев  9  2023  user3.sh
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Videos
-rw-r--r-- 1 root    root      897 сен 11 12:19  wget-log
taisiia@db:~$ cat home_animal.txt pack_animal.txt > friends_humans.txt
taisiia@db:~$ ls -l
total 156
drwxrwxr-x 3 taisiia taisiia  4096 янв 16  2023  1
drwxr-xr-x 2 taisiia taisiia  4096 сен 13 21:04  Desktop
-rw-rw-r-- 1 taisiia taisiia   361 сен 20 09:39  docker-compose.yml
-rw-rw-r-- 1 taisiia taisiia   125 сен 20 08:48  Dockerfile
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Documents
drwxr-xr-x 2 taisiia taisiia  4096 сен  6 14:25  Downloads
drwxrwx--- 1 root    vboxsf   8192 сен 13 21:04  f
-rw-rw-r-- 1 taisiia taisiia    15 окт  1 10:28  friend_animal.txt
-rw-rw-r-- 1 taisiia taisiia    37 окт  1 10:50  friends_humans.txt
-rw-rw-r-- 1 taisiia taisiia    18 окт  1 10:48  home_animal.txt
-rw-rw-r-- 1 taisiia taisiia   312 фев  8  2023  ls_txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Music
drwxrwxr-x 6 vboxadd vboxsf   4096 сен 20 10:13  mydb
drwxrwxr-x 7 taisiia taisiia  4096 сен  6 13:52  newroot
-rw-rw-r-- 1 taisiia taisiia    19 окт  1 10:49  pack_animal.txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Pictures
-rw-rw-r-- 1 taisiia taisiia   115 фев  9  2023  print100
-rw-rw-r-- 1 taisiia taisiia 48779 сен  6 14:27 'Prostranstva imen'
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Public
drwx------ 5 taisiia taisiia  4096 янв 16  2023  snap
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Templates
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test2
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test3
-rw-rw-r-- 1 taisiia taisiia  1092 сен 20 10:10  text.txt
-rw-rw-r-- 1 taisiia taisiia    57 фев  9  2023  user3.sh
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Videos
-rw-r--r-- 1 root    root      897 сен 11 12:19  wget-log
taisiia@db:~$ cat friends_himans.txt
cat: friends_himans.txt: No such file or directory
taisiia@db:~$ cat friends_humans.txt
Cat
Dog
Humsterd
Horse
Camel
Donkey
taisiia@db:~$ mkdir animal
taisiia@db:~$ ls -l
total 160
drwxrwxr-x 3 taisiia taisiia  4096 янв 16  2023  1
drwxrwxr-x 2 taisiia taisiia  4096 окт  1 10:53  animal
drwxr-xr-x 2 taisiia taisiia  4096 сен 13 21:04  Desktop
-rw-rw-r-- 1 taisiia taisiia   361 сен 20 09:39  docker-compose.yml
-rw-rw-r-- 1 taisiia taisiia   125 сен 20 08:48  Dockerfile
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Documents
drwxr-xr-x 2 taisiia taisiia  4096 сен  6 14:25  Downloads
drwxrwx--- 1 root    vboxsf   8192 сен 13 21:04  f
-rw-rw-r-- 1 taisiia taisiia    15 окт  1 10:28  friend_animal.txt
-rw-rw-r-- 1 taisiia taisiia    37 окт  1 10:50  friends_humans.txt
-rw-rw-r-- 1 taisiia taisiia    18 окт  1 10:48  home_animal.txt
-rw-rw-r-- 1 taisiia taisiia   312 фев  8  2023  ls_txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Music
drwxrwxr-x 6 vboxadd vboxsf   4096 сен 20 10:13  mydb
drwxrwxr-x 7 taisiia taisiia  4096 сен  6 13:52  newroot
-rw-rw-r-- 1 taisiia taisiia    19 окт  1 10:49  pack_animal.txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Pictures
-rw-rw-r-- 1 taisiia taisiia   115 фев  9  2023  print100
-rw-rw-r-- 1 taisiia taisiia 48779 сен  6 14:27 'Prostranstva imen'
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Public
drwx------ 5 taisiia taisiia  4096 янв 16  2023  snap
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Templates
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test2
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test3
-rw-rw-r-- 1 taisiia taisiia  1092 сен 20 10:10  text.txt
-rw-rw-r-- 1 taisiia taisiia    57 фев  9  2023  user3.sh
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Videos
-rw-r--r-- 1 root    root      897 сен 11 12:19  wget-log
taisiia@db:~$ mv friends_humans.txt animal
taisiia@db:~$ ls -l
total 156
drwxrwxr-x 3 taisiia taisiia  4096 янв 16  2023  1
drwxrwxr-x 2 taisiia taisiia  4096 окт  1 10:55  animal
drwxr-xr-x 2 taisiia taisiia  4096 сен 13 21:04  Desktop
-rw-rw-r-- 1 taisiia taisiia   361 сен 20 09:39  docker-compose.yml
-rw-rw-r-- 1 taisiia taisiia   125 сен 20 08:48  Dockerfile
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Documents
drwxr-xr-x 2 taisiia taisiia  4096 сен  6 14:25  Downloads
drwxrwx--- 1 root    vboxsf   8192 сен 13 21:04  f
-rw-rw-r-- 1 taisiia taisiia    15 окт  1 10:28  friend_animal.txt
-rw-rw-r-- 1 taisiia taisiia    18 окт  1 10:48  home_animal.txt
-rw-rw-r-- 1 taisiia taisiia   312 фев  8  2023  ls_txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Music
drwxrwxr-x 6 vboxadd vboxsf   4096 сен 20 10:13  mydb
drwxrwxr-x 7 taisiia taisiia  4096 сен  6 13:52  newroot
-rw-rw-r-- 1 taisiia taisiia    19 окт  1 10:49  pack_animal.txt
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Pictures
-rw-rw-r-- 1 taisiia taisiia   115 фев  9  2023  print100
-rw-rw-r-- 1 taisiia taisiia 48779 сен  6 14:27 'Prostranstva imen'
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Public
drwx------ 5 taisiia taisiia  4096 янв 16  2023  snap
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Templates
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test2
drwxrwxr-x 2 taisiia taisiia  4096 янв 16  2023  test3
-rw-rw-r-- 1 taisiia taisiia  1092 сен 20 10:10  text.txt
-rw-rw-r-- 1 taisiia taisiia    57 фев  9  2023  user3.sh
drwxr-xr-x 2 taisiia taisiia  4096 янв 12  2023  Videos
-rw-r--r-- 1 root    root      897 сен 11 12:19  wget-log
taisiia@db:~$ cd /animal
-bash: cd: /animal: No such file or directory
taisiia@db:~$ cd animal
taisiia@db:~/animal$ ls -l
total 4
-rw-rw-r-- 1 taisiia taisiia 37 окт  1 10:50 friends_humans.txt
taisiia@db:~/animal$ sudo apt update
[sudo] password for taisiia:
Hit:1 http://nginx.org/packages/mainline/ubuntu jammy InRelease
Hit:2 http://security.ubuntu.com/ubuntu jammy-security InRelease
Hit:3 http://ru.archive.ubuntu.com/ubuntu jammy InRelease
Hit:4 http://ru.archive.ubuntu.com/ubuntu jammy-updates InRelease
Hit:5 http://ru.archive.ubuntu.com/ubuntu jammy-backports InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
448 packages can be upgraded. Run 'apt list --upgradable' to see them.
N: Skipping acquire of configured file 'nginx/binary-i386/Packages' as repository 'http://nginx.org/packages/mainline/ubuntu jammy InRelease' doesn't support architecture 'i386'
taisiia@db:~/animal$ sudo apt install mysql-server
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following packages were automatically installed and are no longer required:
  libflashrom1 libftdi1-2
Use 'sudo apt autoremove' to remove them.
The following NEW packages will be installed:
  mysql-server
0 upgraded, 1 newly installed, 0 to remove and 448 not upgraded.
Need to get 9 460 B of archives.
After this operation, 35,8 kB of additional disk space will be used.
Get:1 http://ru.archive.ubuntu.com/ubuntu jammy-updates/main amd64 mysql-server all 8.0.34-0ubuntu0.22.04.1 [9 460 B]
Fetched 9 460 B in 0s (23,3 kB/s)
Selecting previously unselected package mysql-server.
(Reading database ... 215544 files and directories currently installed.)
Preparing to unpack .../mysql-server_8.0.34-0ubuntu0.22.04.1_all.deb ...
Unpacking mysql-server (8.0.34-0ubuntu0.22.04.1) ...
Setting up mysql-server (8.0.34-0ubuntu0.22.04.1) ...
taisiia@db:~/animal$ sudo mysql_secure_installation

Securing the MySQL server deployment.

Connecting to MySQL using a blank password.

VALIDATE PASSWORD COMPONENT can be used to test passwords
and improve security. It checks the strength of password
and allows the users to set only those passwords which are
secure enough. Would you like to setup VALIDATE PASSWORD component?

Press y|Y for Yes, any other key for No: d
Please set the password for root here.

New password:

Re-enter new password:
 ... Failed! Error: SET PASSWORD has no significance for user 'root'@'localhost' as the authentication method used doesn't store authentication data in the MySQL server. Please consider using ALTER USER instead if you want to change authentication parameters.

New password:

Re-enter new password:
 ... Failed! Error: SET PASSWORD has no significance for user 'root'@'localhost' as the authentication method used doesn't store authentication data in the MySQL server. Please consider using ALTER USER instead if you want to change authentication parameters.

New password:

Re-enter new password:
 ... Failed! Error: SET PASSWORD has no significance for user 'root'@'localhost' as the authentication method used doesn't store authentication data in the MySQL server. Please consider using ALTER USER instead if you want to change authentication parameters.

New password: Sorry, you can't use an empty password here.

New password: Sorry, you can't use an empty password here.

New password: Sorry, you can't use an empty password here.

New password:

Re-enter new password:
Sorry, passwords do not match.

New password:

Re-enter new password:
Sorry, passwords do not match.

New password:

Re-enter new password:
 ... Failed! Error: SET PASSWORD has no significance for user 'root'@'localhost' as the authentication method used doesn't store authentication data in the MySQL server. Please consider using ALTER USER instead if you want to change authentication parameters.

New password:

Re-enter new password:
 ... Failed! Error: SET PASSWORD has no significance for user 'root'@'localhost' as the authentication method used doesn't store authentication data in the MySQL server. Please consider using ALTER USER instead if you want to change authentication parameters.

New password:
Re-enter new password: Sorry, passwords do not match.

New password:
Re-enter new password:














































































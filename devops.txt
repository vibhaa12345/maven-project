umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ sudo apt update && sudo apt upgrade -y
[sudo] password for umaabc123:
Sorry, try again.
[sudo] password for umaabc123:
Hit:1 http://archive.ubuntu.com/ubuntu noble InRelease
Hit:2 http://security.ubuntu.com/ubuntu noble-security InRelease
Hit:3 http://archive.ubuntu.com/ubuntu noble-updates InRelease
Hit:4 http://archive.ubuntu.com/ubuntu noble-backports InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
The following package was automatically installed and is no longer required:
  libllvm17t64
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ sudo apt install openjdk-17-jdk -y
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
openjdk-17-jdk is already the newest version (17.0.14+7-1~24.04).
The following package was automatically installed and is no longer required:
  libllvm17t64
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ java -version
openjdk version "17.0.14" 2025-01-21
OpenJDK Runtime Environment (build 17.0.14+7-Ubuntu-124.04)
OpenJDK 64-Bit Server VM (build 17.0.14+7-Ubuntu-124.04, mixed mode, sharing)
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ javac -version
javac 17.0.14
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ echo 'export JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64' >> ~/.bashrc
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ echo 'export PATH=$JAVA_HOME/bin:$PATH' >> ~/.bashrc
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$  source ~/.bashrc
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ echo $JAVA_HOME
/usr/lib/jvm/java-17-openjdk-amd64
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ sudo apt install maven -y
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
maven is already the newest version (3.8.7-2).
The following package was automatically installed and is no longer required:
  libllvm17t64
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ mvn -version
Apache Maven 3.8.7
Maven home: /usr/share/maven
Java version: 17.0.14, vendor: Ubuntu, runtime: /usr/lib/jvm/java-17-openjdk-amd64
Default locale: en, platform encoding: UTF-8
OS name: "linux", version: "5.15.167.4-microsoft-standard-wsl2", arch: "amd64", family: "unix"
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ git --version
git version 2.43.0
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ sudo apt update && sudo apt install -y git
Hit:1 http://archive.ubuntu.com/ubuntu noble InRelease
Hit:2 http://archive.ubuntu.com/ubuntu noble-updates InRelease
Hit:3 http://security.ubuntu.com/ubuntu noble-security InRelease
Hit:4 http://archive.ubuntu.com/ubuntu noble-backports InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
git is already the newest version (1:2.43.0-1ubuntu7.2).
The following package was automatically installed and is no longer required:
  libllvm17t64
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ git --version
git version 2.43.0
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ git config --global user.name "umaabc123"
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$  git config --global user.email "umakilluyadav@gmail.com
"
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ git config --list
user.name=umaabc123
user.email=umakilluyadav@gmail.com
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ ssh-keygen -t rsa -b 4096 -C "umakilluyadav@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/umaabc123/.ssh/id_rsa): 1234
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in 1234
Your public key has been saved in 1234.pub
The key fingerprint is:
SHA256:XEIpQcpBdcU3G0RlXhcFHYsepyxTiWDcCLLynwoUSYA umakilluyadav@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|...oo++o=*+oo.+=B|
|E ...o+oooo.=oo.+|
|   +o. .. .o O.o |
|    +  . o  = +  |
|   . .  S  o +   |
|  .   . .   o    |
|   .   o         |
|    . .          |
|     .           |
+----[SHA256]-----+
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ eval "$(ssh-agent -s)"
Agent pid 1339
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ ssh-add ~/.ssh/id_rsa
/home/umaabc123/.ssh/id_rsa: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin$ cd 'MAVEN NEW PROJECT'
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT$ cd mavel-demo
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ git --version
git version 2.43.0
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ sudo apt update && sudo apt install -y git
Hit:1 http://security.ubuntu.com/ubuntu noble-security InRelease
Hit:2 http://archive.ubuntu.com/ubuntu noble InRelease
Hit:3 http://archive.ubuntu.com/ubuntu noble-updates InRelease
Hit:4 http://archive.ubuntu.com/ubuntu noble-backports InRelease
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up to date.
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
git is already the newest version (1:2.43.0-1ubuntu7.2).
The following package was automatically installed and is no longer required:
  libllvm17t64
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ git --version
git version 2.43.0
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ git config --global user.name "umaabc123"
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ git config --global user.email "umakilluyadav@gmail.com"
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ git config --list
user.name=umaabc123
user.email=umakilluyadav@gmail.com
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-keygen -t rsa -b 4096 -C "umakilluyadav@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/umaabc123/.ssh/id_rsa): 1234
1234 already exists.
Overwrite (y/n)? y
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in 1234
Your public key has been saved in 1234.pub
The key fingerprint is:
SHA256:uCanOT8y84qfenQAmGaDBjq4j5n/lXBIobKUA4RkAd0 umakilluyadav@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|@O...            |
|X=+.E.           |
|O+o..            |
|.=.... .         |
|o   o.o S        |
| =  .o.o         |
|+ ....*          |
| . .*O.          |
|  +=BOo.         |
+----[SHA256]-----+
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ eval "$(ssh-agent -s)"
Agent pid 1852
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$  ssh-add ~/.ssh/id_rsa
/home/umaabc123/.ssh/id_rsa: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add ~/.ssh/id_rsa
/home/umaabc123/.ssh/id_rsa: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ cd mnt/c/Users/admin/'MAVEN
 NEW PROJECT'
-bash: cd: mnt/c/Users/admin/MAVEN NEW PROJECT: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ cd /mnt/c/Users/admin/'MAVE
N NEW PROJECT'
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT$  eval "$(ssh-agent -s)"
Agent pid 1955
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT$  ssh-add ~/.ssh/id_rsa
/home/umaabc123/.ssh/id_rsa: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT$ cat ~/.ssh/id_rsa.pub
cat: /home/umaabc123/.ssh/id_rsa.pub: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT$ ls
mavel-demo
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT$ cd maven-demo
-bash: cd: maven-demo: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT$ cd mavel-demo
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ cat ~/.ssh/id_rsa.pub
cat: /home/umaabc123/.ssh/id_rsa.pub: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ^C
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$  cd /mnt/c/Users/admin/'MAVE
N NEW PROJECT'
-bash: cd: $'/mnt/c/Users/admin/MAVE\nN NEW PROJECT': No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ls
1234  1234.pub  pom.xml  src  target
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add -l
The agent has no identities.
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add -1
unknown option -- 1
usage: ssh-add [-cDdKkLlqvXx] [-E fingerprint_hash] [-H hostkey_file]
               [-h destination_constraint] [-S provider] [-t life]
               [file ...]
       ssh-add -s pkcs11
       ssh-add -e pkcs11
       ssh-add -T pubkey ...
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add -I
unknown option -- I
usage: ssh-add [-cDdKkLlqvXx] [-E fingerprint_hash] [-H hostkey_file]
               [-h destination_constraint] [-S provider] [-t life]
               [file ...]
       ssh-add -s pkcs11
       ssh-add -e pkcs11
       ssh-add -T pubkey ...
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ eval "$(ssh-agent -s)"
Agent pid 3224
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add ~/.ssh/id_rsa
/home/umaabc123/.ssh/id_rsa: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh -T git@github.com
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh -T git@github.com
git@github.com: Permission denied (publickey).
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ eval "$(ssh-agent -s)"
Agent pid 3275
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add ~/.ssh/id_rsa
/home/umaabc123/.ssh/id_rsa: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh -T git@github.com
git@github.com: Permission denied (publickey).
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ git --version
git version 2.43.0
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add ~/.ssh/id_rsa
/home/umaabc123/.ssh/id_rsa: No such file or directory
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ eval "$(ssh-agent -s)"
Agent pid 3321
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-keygen -t rsa -b 4096 -C "umakilluyadav@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/umaabc123/.ssh/id_rsa): 12345
Enter passphrase (empty for no passphrase):

[1]+  Stopped                 ssh-keygen -t rsa -b 4096 -C "umakilluyadav@gmail.com"
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-keygen -t rsa -b 4096 -C "umakilluyadav@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/umaabc123/.ssh/id_rsa):
Enter passphrase (empty for no passphrase):
Enter same passphrase again:
Your identification has been saved in /home/umaabc123/.ssh/id_rsa
Your public key has been saved in /home/umaabc123/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:eaa/qqFTW/SJdZ1InIYLM7x6sJP07Vd7/pPjIEGZSpA umakilluyadav@gmail.com
The key's randomart image is:
+---[RSA 4096]----+
|       o.  o .   |
|       E* . B    |
|         * B o . |
|      o +.= o o  |
|     . BS*o+     |
|      * =++ . .  |
|     ..=.. . o ..|
|    .... .. o o+.|
|    ......oo  .+*|
+----[SHA256]-----+
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ eval "$(ssh-agent -s)"
Agent pid 3355
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add ~/.ssh/id_rsa
Enter passphrase for /home/umaabc123/.ssh/id_rsa:
Identity added: /home/umaabc123/.ssh/id_rsa (umakilluyadav@gmail.com)
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ cat ~/.ssh/id_rsa.pub 1234
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC0iDb+TT5MCmauwFu94/j9+D/uqBS1gogapnyhOANZekRgabmtj0oQSXnK7zYTXyoEx1gE2CMuDGZyuXy5bnrGgH4gPexYYD8BingW7YdV/JcJtSnSwlsFyxQmwbZw1pxVFM5Rwl0OOfpgQ4/xLlhXXwPa7Ik4VBwabXIso0aOonZbRHeAoM6Pzqqtu2H04MVE16ABnRoT44sW3E+PLRWCPrKkYHig2wXuXK9fG8SvkMWktQ/Tksp0vIa4uty9yTgSSVZeQlEErH+WI2rTFMo08iv2p9TEQYLY10fD4gpAz5Mc/DtGtGvvYcmrr1ZEbrOs8Pb+NKE2puAg9BJOtEf6Dh0VwrSUO8bM385NwSEn0TU2fBVfQ8Uh34nK5uK+9ZWKaAptFtgbXnorhZfIPxUiV7r8K3mwi5/FrYEknMrDrSCheLv1XNGaMPwLaUwFCoKoRtkWXRdx20rSO7GFici2RwDmPOJD5dAMZiEzFo5sn3mDfTL3OY0QJWPV9bhHfNcqhYQ15pOBxb0bB1RYrUk4NRjH4tkvsbGTUhjjjAbzIIUDG54GX5ltNrqU0ISsKrvsmlYGDO2Y6e4D44BLCDQXsoJubOSjVmBpUZZTGEhe06Hu4LnU2CmUPgyuJBLLGnZ2JPMZ5Hp4AXoMc9JZHE2jo6SuWxlutHnunW043x2e0w== umakilluyadav@gmail.com
-----BEGIN OPENSSH PRIVATE KEY-----
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
q6XOAW6f3gKVn4PsqOdZf/kLA=
-----END OPENSSH PRIVATE KEY-----
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-keygen -t rsa -b 4096 -C "umakilluyadav@gmail.com"
Generating public/private rsa key pair.
Enter file in which to save the key (/home/umaabc123/.ssh/id_rsa): ^C
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh-add ~/.ssh/id_rsa
Enter passphrase for /home/umaabc123/.ssh/id_rsa:
Identity added: /home/umaabc123/.ssh/id_rsa (umakilluyadav@gmail.com)
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ cat ~/.ssh/id_rsa.pub
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC0iDb+TT5MCmauwFu94/j9+D/uqBS1gogapnyhOANZekRgabmtj0oQSXnK7zYTXyoEx1gE2CMuDGZyuXy5bnrGgH4gPexYYD8BingW7YdV/JcJtSnSwlsFyxQmwbZw1pxVFM5Rwl0OOfpgQ4/xLlhXXwPa7Ik4VBwabXIso0aOonZbRHeAoM6Pzqqtu2H04MVE16ABnRoT44sW3E+PLRWCPrKkYHig2wXuXK9fG8SvkMWktQ/Tksp0vIa4uty9yTgSSVZeQlEErH+WI2rTFMo08iv2p9TEQYLY10fD4gpAz5Mc/DtGtGvvYcmrr1ZEbrOs8Pb+NKE2puAg9BJOtEf6Dh0VwrSUO8bM385NwSEn0TU2fBVfQ8Uh34nK5uK+9ZWKaAptFtgbXnorhZfIPxUiV7r8K3mwi5/FrYEknMrDrSCheLv1XNGaMPwLaUwFCoKoRtkWXRdx20rSO7GFici2RwDmPOJD5dAMZiEzFo5sn3mDfTL3OY0QJWPV9bhHfNcqhYQ15pOBxb0bB1RYrUk4NRjH4tkvsbGTUhjjjAbzIIUDG54GX5ltNrqU0ISsKrvsmlYGDO2Y6e4D44BLCDQXsoJubOSjVmBpUZZTGEhe06Hu4LnU2CmUPgyuJBLLGnZ2JPMZ5Hp4AXoMc9JZHE2jo6SuWxlutHnunW043x2e0w== umakilluyadav@gmail.com
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ ssh -T git@github.com
Hi Umaks123! You've successfully authenticated, but GitHub does not provide shell access.
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/MAVEN NEW PROJECT/mavel-demo$ cd /mnt/c/Users/admin/Docum
ents/GitHub/Maven-repo
umaabc123@DESKTOP-6F4P75U:/mnt/c/Users/admin/Documents/GitHub/Maven-repo$ git clone git@github.com:Umaks123/maven-repo.git
Cloning into 'maven-repo'...
remote: Enumerating objects: 47, done.
remote: Counting objects: 100% (47/47), done.
remote: Compressing objects: 100% (24/24), done.
remote: Total 47 (delta 1), reused 44 (delta 1), pack-reused 0 (from 0)
Receiving objects: 100% (47/47), 8.30 KiB | 653.00 KiB/s, done.
Resolving deltas: 100% (1/1), done.
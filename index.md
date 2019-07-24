# AIS3 environment requirements

## Virtual Machine prepared by AIS3
### VM1
- OS: Ubuntu 18.04 Desktop
- package
	1. JDK8
	2. maven
	3. golang
	4. git
	5. IntelliJ
	6. OpenSSL
	7. python3
	8. python2.7
	9. burp
	10. IBM Adversarial Robustness Toolbox 
	11. libsodium
	12. R
	13. R Studio
	14. gcc-arm-linux-gnueabi
	15. gtkterm
	16. flash tool

### VM2
- OS: Windows 7
- without any update
- install image
	- en\_windows\_7\_professional\_x64\_dvd\_x15-65805
	- SHA1: 50127304441A793EE51B3F501289F6599A559E9F
- package
	1. IDA freeware 
	2. VMware tools
	3. Putty
	4. flash tool
	5. usb-to-uart-bridge-vcp-drivers

----------
## Package list
### package in Linux
- JDK8
- maven
	- version: 3.6.0
- golang
	- version: 1.10.4
- git
	- version: 2.17.1
- IntelliJ
	- version: 2019.1.3
	- with golang plugin
- OpenSSL
	- version: 1.1.1
- python3
	- version: 3.6.5
- python2.7
   - version: 2.7.15
- burp
	- version: 2.0.54
- IBM Adversarial Robustness Toolbox
	- version: ART v0.10.0
- libsodium
	- version: 1.0.18
	- https://github.com/jedisct1/libsodium
- R
	- version: 3.4.4
- R Studio
	- version: 1.1.463
- gcc-arm-linux-gnueabi
- gtkterm
- flash tool
	- https://labs.mediatek.com/en/download/6nOsg1ml 

### package in Windows

- VMware workstation
	- version: 15 Pro
	- Need to install in your NB
	- https://www.vmware.com/go/getworkstation-win
- IDA freeware
	- version: 7
	- Need to install in your NB
	- for windows: https://out7.hex-rays.com/files/idafree70_windows.exe
	- for mac: https://out7.hex-rays.com/files/idafree70_mac.tgz
	- for linux: https://out7.hex-rays.com/files/idafree70_linux.run
- Putty
- flash tool
	- https://labs.mediatek.com/en/download/i7wl3Hcf
- usb-to-uart-bridge-vcp-drivers
	- https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers

-----

### In Ubuntu 18.04 Desktop
```
apt-get install \
python2.7=2.7.15-4ubuntu4~18.04 \
openssl=1.1.1-1ubuntu2.1~18.04.4 \
openjdk-8-jre=8u212-b03-0ubuntu1.18.04.1 \
git=1:2.17.1-1ubuntu0.4 \
golang-go=2:1.10~4ubuntu1 \
maven=3.6.0-1~18.04.1 \
burp=2.0.54-4build1 \
r-base=3.4.4-1ubuntu1 \
python-pip \
lib32gcc1 lib32stdc++6 libc6-i386 \
libclang-6.0-dev libclang-common-6.0-dev \
libclang-dev libclang1-6.0 \
libobjc-7-dev libobjc4 \
libjpeg62 libgstreamer1.0-0 \
libgstreamer-plugins-base1.0-0 \
gcc-arm-linux-gnueabi gtkterm

snap install intellij-idea-community --classic

pip install adversarial-robustness-toolbox

wget https://download1.rstudio.org/desktop/bionic/amd64/rstudio-1.2.1335-amd64.deb
dpkg -i rstudio-1.2.1335-amd64.deb

git clone https://github.com/jedisct1/libsodium --branch stable

cd libsodium/
./configure
make && make check
sudo make install
```

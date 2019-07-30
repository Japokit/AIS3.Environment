# AIS3 environment requirements

## 20190730 CST11:00 Update
### Environment for Day4 afternoon (Automatic Binary Analysis)
- [Docker angr/angr](https://hub.docker.com/r/angr/angr/)
- [Docker bruce30262/re3](https://hub.docker.com/r/bruce30262/re3)
- Please install Ghidra: [https://ghidra-sre.org](https://ghidra-sre.org)
    - Installation guide: [https://www.ylmzcmlttn.com/2019/03/26/ghidra-installation-on-ubuntu-18-04-16-04-14-04/](https://www.ylmzcmlttn.com/2019/03/26/ghidra-installation-on-ubuntu-18-04-16-04-14-04/)
- Ghidra Data (git repository): [https://github.com/0x6d696368/ghidra-data](https://github.com/0x6d696368/ghidra-data)
- Ghidra scripts (git repository): [https://github.com/0x6d696368/ghidra_scripts](https://github.com/0x6d696368/ghidra_scripts)

### Slides and files for Day3 afternoon (Cryptograph and Cryptanalysis)
- [20190729_For_AIS3_JP_01_Hardware_Security.pdf](http://file.inner.ais3.org/20190729_For_AIS3_JP_01_Hardware_Security.pdf)
- [20190729_For_AIS3_JP_02_Cryptography_and_AES.pdf](http://file.inner.ais3.org/20190729_For_AIS3_JP_02_Cryptography_&_AES.pdf)
- [20190729_For_AIS3_JP_03_SCA.pdf](http://file.inner.ais3.org/20190729_For_AIS3_JP_03_SCA.pdf)
- [Rijndael_Anim.zip](http://file.inner.ais3.org/Rijndael_Anim.zip)

## 20190730 CST08:45 Update
### Files for Day2 morning (Firmware security analysis)
- [Slides](https://drive.google.com/file/d/1iMCkudCihlUV6K4jMFpLo-sxKaJ9HfcA)
- [Setting Guide](https://drive.google.com/file/d/1R49PjB4HCIWQ9OcTICbVyvTQehjvcEMQ)
- [Appendix.pdf](http://file.inner.ais3.org/Appendix.pdf)
- [firmware00.zip **Updated**](http://file.inner.ais3.org/firmware00.zip)
- [MyLittle-OS.zip](http://file.inner.ais3.org/MyLittle-OS.zip)

## 20190729 CST12:45 Update
- Index of file server: [file.inner.ais3.org](http://file.inner.ais3.org)
- Today afternoon slide: [190729_afternoon_slide.pdf](http://file.inner.ais3.org/190729_afternoon_slide.pdf)

## 20190728 CST19:30 Update
### Files from speakers
- [SIFT-Workstation-3-Virtual-Machine-Distro-Version.zip](http://file.inner.ais3.org/SIFT-Workstation-3-Virtual-Machine-Distro-Version.zip)
- [forensics_sample.zip](http://file.inner.ais3.org/forensics_sample.zip)

## ~~20190726 CST22:10 Update~~
### ~~Files for Day2 morning (Firmware security analysis)~~
- ~~[Slides](https://drive.google.com/file/d/1iMCkudCihlUV6K4jMFpLo-sxKaJ9HfcA)~~
- ~~[Setting Guide](https://drive.google.com/file/d/1R49PjB4HCIWQ9OcTICbVyvTQehjvcEMQ)~~
- ~~[Firmware.zip](https://drive.google.com/file/d/1vPFrCycWKIfmNd-QaMKXus-7G28IEi6d)~~

----------

## Virtual Machine prepared by AIS3
### VM1
- Download: [Link](http://file.inner.ais3.org/Ubuntu_for_AIS3.ova)
- Default user/password: ais3/ais32019
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
- Download: [Link](http://file.inner.ais3.org/Windows_for_AIS3.ova)
- OS: Windows 7 SP1
- without update
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
	- [https://github.com/jedisct1/libsodium](https://github.com/jedisct1/libsodium)
- R
	- version: 3.4.4
- R Studio
	- version: 1.1.463
- gcc-arm-linux-gnueabi
- gtkterm
- flash tool
	- [https://labs.mediatek.com/en/download/6nOsg1ml](https://labs.mediatek.com/en/download/6nOsg1ml)

### package in Windows

- VMware workstation
	- version: 15 Pro
	- Need to install in your NB
	- [https://www.vmware.com/go/getworkstation-win](https://www.vmware.com/go/getworkstation-win)
- IDA freeware
	- version: 7
	- Need to install in your NB
	- for windows: [https://out7.hex-rays.com/files/idafree70_windows.exe](https://out7.hex-rays.com/files/idafree70_windows.exe)
	- for mac: [https://out7.hex-rays.com/files/idafree70_mac.tgz](https://out7.hex-rays.com/files/idafree70_mac.tgz)
	- for linux: [https://out7.hex-rays.com/files/idafree70_linux.run](https://out7.hex-rays.com/files/idafree70_linux.run)
- Putty
- flash tool
	- [https://labs.mediatek.com/en/download/i7wl3Hcf](https://labs.mediatek.com/en/download/i7wl3Hcf)
- usb-to-uart-bridge-vcp-drivers
	- [https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers](https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)

### Install script in Ubuntu 18.04 Desktop
```bash
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

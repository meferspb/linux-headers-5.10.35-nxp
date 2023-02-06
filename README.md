# linux-headers-5.10.35-nxp
# linux-headers-5.10.35-nxp

Install new kernel for SolidRun lx2160

Login as root on SolidRun LX2160 device

```
cd ~
apt update
apt upgrade
apt install git
git clone https://github.com/meferspb/linux-headers-5.10.35-nxp.git
cd linux-headers-5.10.35-nxp
cp Image /boot/Image
dpkg -i linux-image-5.10.35_5.10.35-1_arm64.deb
dpkg -i linux-headers-5.10.35_5.10.35-1_arm64.deb
dpkg -i linux-libc-dev_5.10.35-1_arm64.deb
reboot
```

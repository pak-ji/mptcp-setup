# MPTCP-SETUP
This describes the process of setting up MPTCP on the Linux kernel. <br>
It will be described in two models. <br>
One is the Debian family of x86 general computers, and the other is RaspberryPi.

<br>

# Debian(x86)

#### 1. Access the link
```
https://github.com/multipath-tcp/mptcp/releases
```

#### 2. Download image file for debian version
<img src="https://user-images.githubusercontent.com/48320014/144986881-6e3401a9-790e-4583-8a47-7e55336be41c.png" width="550" height="300"/>

#### 3. Build the image file to your debian system
```sh
dpkg -i linux-image-xxxxx.mptcp_xxxxx_amd64.deb
```

#### 4. Change the kernel boot order using grub
```
GUI & ENG : https://linuxhint.com/change-grub-boot-order/
CLI & KOR : https://sandarabong.tistory.com/63 
```


<br>

# RaspberryPi

#### 1. Guide
* [RPI(4.14.y) with MPTCP(v0.94) - Korean](contents/guide.pdf)

<br><br>

## Reference
* www.multipath-tcp.org

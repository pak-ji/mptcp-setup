## MPTCP-SETUP
This describes the process of setting up MPTCP on the Linux kernel. <br>
It will be described in two models. <br>
One is the Debian family of x86 general computers, and the other is RaspberryPi.

<br>

## Navigation 
* [Debian(x86)](#x86)
* [RaspberryPi](#rpi)

<br>

## <a id="x86">Debian(x86)</a>
##### 1. Add gpg-apt-key
```sh
sudo apt-key adv --keyserver hkps://keyserver.ubuntu.com:443 --recv-keys 379CE192D401AB61
```
##### 2. Add repository in your APT' sources files
```sh
sudo sh -c "echo 'deb https://dl.bintray.com/multipath-tcp/mptcp_deb stable main' > /etc/apt/sources.list.d/mptcp.list"
```
##### 3. Install MPTCP in the Kernel
```sh
sudo apt-get update
sudo apt-get install linux-mptcp

// This is latest version download command.
```
##### 4. Install the older version MPTCP (Kernel Ver >= 4.x && MPTCP Ver >= v0.9x)
##### 4.1. Search the MPTCP version
```sh
sudo apt-cache search linux-mptcp-*

// Now(2021-04-29) detected versions are
```
##### 

<br>

## <a id="rpi">RaspberryPi</a>


<br>

## Reference
* www.multipath-tcp.org

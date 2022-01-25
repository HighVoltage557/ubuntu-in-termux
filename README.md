# ubuntu-in-termux

### What's This?

#### This is a script that installs Ubuntu in termux without needing to root your device.
***
### Installation steps:
#### 1) Update termux packages:
```bash
apt update && apt upgrade -y
```
#### 2) Install required packages:
```bash
apt install git proot wget curl -y
```
#### 3) Download script and start script:
```bash
cd && curl https://raw.githubusercontent.com/HighVoltage557/ubuntu-in-termux/master/install.sh | bash
```
#### 4) Follow the on screen instructions, enter details required and the script will install Ubuntu in termux.
***
#### To Run ubuntu:
```bash
cd && ./startubuntu.sh
``` 

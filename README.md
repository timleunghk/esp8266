
Steps of compile this code.

This repository contains esp-open-sdk and necessary items for compiling ESP8266 Operating System. So that you can simplify your steps to compile your own image.

1. Get important components
sudo apt-get install make unrar-free autoconf automake libtool gcc g++ gperf flex bison texinfo gawk ncurses-dev libexpat-dev python-dev python python-serial sed git unzip bash help2man wget bzip2 libtool-bin

2. Get this code

3. change directory to esp-open-sdk

4. echo "export PATH=/home/XXXX/esp-open-sdk/xtensa-lx106-elf/bin:$PATH" >> ~/.profile

(XXXX: your user name)

5. cd ~/esp-open-sdk/micropython

7. make clean;make axtls;make



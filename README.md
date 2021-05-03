# RipBluetooth
This project was created only for good purposes and personal use.  THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. YOU MAY USE THIS SOFTWARE AT YOUR OWN RISK. THE USE IS COMPLETE RESPONSIBILITY OF THE END-USER. THE DEVELOPERS ASSUME NO LIABILITY AND ARE NOT RESPONSIBLE FOR ANY MISUSE OR DAMAGE CAUSED BY THIS PROGRAM.









Installing
$ sudo apt update
$ sudo apt install python3
$ sudo git clone https://github.com/kali13042/RipBluetooth.git
$ cd RipBluetooth/
$ python3 RipBluetooth.py
Note
The script works only with Linux systems.

You must have "l2ping" util on your linux machine (it installed as default on Kali Linux).

YOU MUST SCAN AND ATTACK BEFORE SOMEONE CONNECT TO THE TARGET!!!

It tested on
Kali Linux as attacker, and Xiaomi Portable Bluetooth Speaker as target

Using
First of all, you must scan network for Bluetooth devises. For example, you can use "hcitool".

$ sudo apt update
$ apt install hcitool
$ sudo service bluetooth start
$ hcitool scan

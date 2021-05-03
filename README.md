THIS SOFTWARE IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY KIND. YOU MAY USE THIS SOFTWARE AT YOUR OWN RISK. THE USE IS COMPLETE RESPONSIBILITY OF THE END-USER. THE DEVELOPERS ASSUME NO LIABILITY AND ARE NOT RESPONSIBLE FOR ANY MISUSE OR DAMAGE CAUSED BY THIS PROGRAM.
## Installing

```
$ sudo apt update
$ sudo apt install python3
$ sudo git clone https://github.com/jieggiI/BLUETOOTH-DOS-ATTACK-SCRIPT.git
$ cd BLUETOOTH-DOS-ATTACK-SCRIPT/
$ python3 Bluetooth-DOS-Attack.py
```
### Note
<p>The script works only with Linux systems.</p>
<p>You must have "l2ping" util on your linux machine (it installed as default on Kali Linux).</p>
<p>YOU MUST SCAN AND ATTACK BEFORE SOMEONE CONNECT TO THE TARGET!!!</p>

## It tested on
Kali Linux as attacker, and Xiaomi Portable Bluetooth Speaker as target

## Using
<p>First of all, you must scan network for Bluetooth devises. For example, you can use "hcitool".</p>

```
$ sudo apt update
$ apt install hcitool
$ sudo service bluetooth start
$ hcitool scan

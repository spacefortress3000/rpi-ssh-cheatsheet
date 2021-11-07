# SSH Raspberry Pi Cheatsheet

+ SSH RPi: `ssh pi@raspberrypi.local` (root is set by default as pi and and so does hostname which is raspberrypi by default)
+ Alternarive connect: `ssh pi@192.168.1.1` (if possible, use static ip by configuring your router settings)
+ Ping RPi: `ping hostname.local` or `ping 192.168.1.1`
+ Shutdown to halt: `sudo shutdown -h now`
+ Reboot: `sudo shutdown -r now`

### Git
+ Get the newest versions of repositories `git pull`

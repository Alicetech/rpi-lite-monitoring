# rpi-lite-monitoring
Changes login prompt (tty1)  into system monitoring.

# How to install

ctrl+alt+f3 will take you to tty3 so you can still login

This will restart tty1. tty3 should be used to run this command
```
curl -o- https://raw.githubusercontent.com/Alicetech/rpi-lite-monitoring/main/install | sudo bash /dev/stdin pi
```
ctrl+alt+f1 will take you to tty1 so you see what the screen looks like now and on reboots.

# How to edit screen
Edit the file /home/pi/.tty1.service.d to change the commands and tmux

# How to run tests before bug report
```
git clone https://github.com/Alicetech/rpi-lite-monitoring.git
cd rpi-lite-monitoring
chmod ./units/run
./units/run
```

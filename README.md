# rpi-lite-monitoring
Changes login prompt (tty1)  into system monitoring.

# How to install
```
curl -o- https://raw.githubusercontent.com/Alicetech/rpi-lite-monitoring/main/install | sudo bash /dev/stdin pi
```
After that you need to reboot
```
sudo reboot
```

ctrl+alt+f3 will take you to tty3 so you can still login

# How to run tests before bug report
```
git clone https://github.com/Alicetech/rpi-lite-monitoring.git
cd rpi-lite-monitoring
chmod ./units/run
./units/run
```

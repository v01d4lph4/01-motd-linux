# 01-motd-linux

_Just an attempt to make your login(s) into shell more fun._

<p align="center">
  <img src="https://github.com/v01d4lph4/01-motd-linux/blob/master/motd.png?raw=true"/>
</p>

### To get started, here's what to do :+1:
1. Remove the contents of ```/etc/motd```
2. Comment out ```uname -snrvm > /var/run/motd.dynamic``` in ```/etc/init.d/motd```
3. Change from ```PrintLastLog yes``` to ```PrintLastLog no``` in ```/etc/ssh/sshd_config```
4. Create a new motd file by executing ```sudo nano /etc/motd.tcl```
5. Add the code from ```motd.tcl``` in this repo
6. Make the script executable ```sudo chmod 755 /etc/motd.tcl```
7. Add ```/etc/motd.tcl``` to the end of the file ```/etc/profile```
8. Restart your shell session.
9. **Profit**


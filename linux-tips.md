installing sublime
	> tar -xvjf Sublime\ Text\ 2*.tar.bz2
	> mv Sublime\ Text\ 2/ /opt/sublime-text-2/
	> ln -s /opt/sublime-text-2 /usr/local/sublime-text-2
	> ln -s /usr/local/sublime-text-2/sublime_text >/usr/local/bin/sublime_text
	> rm Sublime\ Text\ 2*.tar.bz2 



get architechture
	> uname -m

---
allow all permissions to zodehala
	> echo 'zodehala ALL=(ALL) ALL' >> /etc/sudoers

---
list all usb devices
	> lsusb
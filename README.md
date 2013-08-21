raspberrypiopensportproject
===========================


1. create raspberry pi image or buy pre made

2. install node js  http://www.quietless.com/kitchen/how-to-setup-node-js-on-a-raspberry-pi/

http://nodejs.org/dist/v0.8.11/node-v0.8.11.tar.gz

or via binary http://blog.rueedlinger.ch/2013/03/raspberry-pi-and-nodejs-basic-setup/

3. install couchdb  sudo apt-get install couchdb

4. install git  github   sudo apt-get install git

5. clone https://github.com/aboynejames/communication.git  git repository

6. install node modules  sudo npm install   (from /src directory) & serial port

7. install  node module forever globally   sudo npm install -g forever   version 0.10.0


9. configure /etc/network/interfaces   static IP

10. install hostapd  depend on type of wifi dondle sudo apt-get install hostapd or

11. setup dynamic dns  dnsmasq   sudo apt-get install dnsmasq

12. IPtables  not working yet

13. load on boot   /etc/init.d     create file  start-forever.sh    chmod 755  sudo update-rc.d start-forever.sh defaults

Video installl coming soon
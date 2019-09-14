# setup-unifi-controller-in-raspberry-pi

```
echo 'deb http://www.ui.com/downloads/unifi/debian stable ubiquiti' | sudo tee /etc/apt/sources.list.d/100-ubnt-unifi.list
sudo wget -O /etc/apt/trusted.gpg.d/unifi-repo.gpg https://dl.ui.com/unifi/unifi-repo.gpg
sudo apt update
sudo apt install apt-transport-https
sudo apt install unifi
apt-get install haveged
apt-get install emacs
sudo apt-get install openjdk-8-jre-headless -y
sudo apt-get install openjdk-8-jre
sudo apt upgrade
sudo apt autoremove
sudo service unifi status
sudo service unifi start
```

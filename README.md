# Remote Desktop Access to Linux VM in GCP

Connect to VM using PuTTY using Host Name/IP port 22
Login using ssh or Username-Password

After successfull connection run the below commands
sudo apt-get update
sudo apt-get install -y xrdp
sudo apt-get install -y xfce4
sudo service xrdp restart

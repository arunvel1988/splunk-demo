SPLUNK SERVER INSTALLATION STEPS

wget -O splunk-9.4.3-237ebbd22314-linux-amd64.deb "https://download.splunk.com/products/splunk/releases/9.4.3/linux/splunk-9.4.3-237ebbd22314-linux-amd64.deb"


sudo dpkg -i splunk-9.4.3-237ebbd22314-linux-amd64.deb

sudo /opt/splunk/bin/splunk start --accept-license

sudo apt install nginx -y

wget -O splunkforwarder-9.4.3-237ebbd22314-linux-amd64.deb "https://download.splunk.com/products/universalforwarder/releases/9.4.3/linux/splunkforwarder-9.4.3-237ebbd22314-linux-amd64.deb"

sudo dpkg -i splunkforwarder-9.4.3-237ebbd22314-linux-amd64.deb


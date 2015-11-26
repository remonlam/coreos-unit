How to start apps/services with fleet on CoreOS

sudo wget -P /etc/systemd/system https://raw.githubusercontent.com/remonlam/CoreOS/master/Unit%20Files/apache%40.service && sudo wget -P /etc/systemd/system https://raw.githubusercontent.com/remonlam/CoreOS/master/Unit%20Files/apache-discovery%40.service

fleetctl start apache@1 && fleetctl start apache@2

fleetctl start apache-discovery@1 && fleetctl start apache-discovery@2

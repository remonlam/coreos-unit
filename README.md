# CoreOS
CoreOS

Use the "coreos_preper.sh" to download and execute the "coreos-install"

This script is used in a CentOS Live distro to install CoreOS on a Micro-SD card.

TO INSTALL:

wget -P /tmp/ https://raw.githubusercontent.com/remonlam/CoreOS/master/coreos_preper.sh && chmod 755 /tmp/coreos_preper.sh && cd /tmp/ && ./coreos_preper.sh && sync

OR DEV

wget -P /tmp/ https://raw.githubusercontent.com/remonlam/CoreOS/master/dev_coreos_preper.sh && chmod 755 /tmp/dev_coreos_preper.sh && cd /tmp/ && ./dev_coreos_preper.sh && sync

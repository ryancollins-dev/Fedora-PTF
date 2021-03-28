# fedora-ptf-install

sudo -i

dnf update

dnf install python

dnf install git

cd /opt/

git clone https://github.com/trustedsec/ptf.git

cd ptf

./ptf

use modules/exploitation/install_update_all

./ptf

use modules/intelligence-gathering/install_update_all

./ptf

use modules/post-exploitation/install_update_all

./ptf

use modules/powershell/install_update_all

./ptf

use modules/vulnerability-analysis/install_update_all

cd /pentest

# Firewall

firewall-cmd --state

firewall-cmd --list-all-zones

firewall-config

# PTF Usage

sudo -i 

cd /opt/ptf

./ptf
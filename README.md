# MODULE #
# Install Modules or Materials for Termux and Linux
# FOR TERMUX #

pkg update

pkg upgrade

pkg install python2

pkg install git

git clone https://github.com/ZeThAlOnE/Module.git

cd Module

chmod +x *

pip install -r requirements.txt

python Module-Termux.py

# FOR LINUX #

apt update

apt upgrade

apt install python2

apt install git

git clone https://github.com/ZeThAlOnE/Module.git

cd Module

chmod +x *

pip2 install -r requiremenst.txt

python3 Module-Linux.py

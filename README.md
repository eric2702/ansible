sudo apt update
sudo apt upgrade
sudo apt install python3-pip
sudo apt install python3.12-venv #or whatever version

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

termux-setup-storage
apt update -y && apt upgrade -y
pkg install git -y
pkg install python -y
pip install requests
pip install bs4
pip install future
git clone https://github.com/mrt0x4c/Free.git
cd Free
python Free.py

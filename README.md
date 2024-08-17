Type y then enter key in any prompt

yes | pkg update && pkg upgrade
yes | pkg install libjansson wget nano


Download ccminer, config, start:


mkdir ccminer && cd ccminer
wget https://github.com/intan1703/verus/blob/main/ccminer
wget https://github.com/intan1703/verus/blob/main/config.json
wget https://github.com/intan1703/verus/blob/main/start.sh
chmod +x ccminer start.sh

nano config.json

Start ccminer with:


~/ccminer/start.sh



สำหรับ DEBIAN

apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot

สำหรับ UBUNTU

apt update && apt upgrade -y && update-grub && sleep 2 && reboot

INSTALL SCRIPT >1

apt install curl -y && apt install -y && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/capcapan/autoscript/main/main.sh && chmod +x main.sh && ./main.sh

INSTALL SCRIPT >2

sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/capcapan/autoscript/main/main.sh && chmod +x main.sh && sed -i -e 's/\r$//' main.sh && screen -S main ./main.sh

UPDATE SCRIPT

wget -q https://raw.githubusercontent.com/capcapan/autoscript/main/update.sh && chmod +x update.sh && ./update.sh

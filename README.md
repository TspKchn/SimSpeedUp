
# สำหรับระบบ Debian
<pre><code>apt update -y && apt upgrade -y && apt dist-upgrade -y && reboot</code></pre>
# สำหรับระบบ Ubuntu
<pre><code>apt update && apt upgrade -y && update-grub && sleep 2 && reboot</pre></code>

### ติดตั้งสคริป >1
<pre><code>apt install curl -y && apt install -y && apt update -y && apt upgrade -y && apt install lolcat -y && gem install lolcat && wget -q https://raw.githubusercontent.com/TspKchn/SimSpeedUp/main/main.sh && chmod +x main.sh && ./main.sh
</code></pre>

### ติดตั้งสคริป >2
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/TspKchn/SimSpeedUp/main/main.sh && chmod +x main.sh && sed -i -e 's/\r$//' main.sh && screen -S main ./main.sh
</code></pre>

### อัปเดตสคริป 
<pre><code>wget -q https://raw.githubusercontent.com/TspKchn/SimSpeedUp/main/update.sh && chmod +x update.sh && ./update.sh
</code></pre>

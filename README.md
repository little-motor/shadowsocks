wget --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/little-motor/shadowsocks/master/shadowsocks.sh
 
chmod +x shadowsocks.sh
./shadowsocks.sh 2>&1 | tee shadowsocks.log

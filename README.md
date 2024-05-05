执行以下命令一键安装：

wget https://github.com/Adagior/shadowsocks/raw/master/shadowsocks.sh

chmod +x shadowsocks.sh

./shadowsocks.sh



ssserver -c /etc/shadowsocks.json -d start

ssserver -c /etc/shadowsocks.json -d stop

ssserver -c /etc/shadowsocks.json -d restart


```
wget -O ss-rust.sh --no-check-certificate https://raw.githubusercontent.com/xOS/Shadowsocks-Rust/master/ss-rust.sh && chmod +x ss-rust.sh && ./ss-rust.sh
```

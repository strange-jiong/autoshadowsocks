# autoshadowsocks
a script to install shadowsocks automaticly

## login as root &&install
```
wget --no-check-certificate -O shadowsocks.sh https://raw.githubusercontent.com/strange-jiong/autoshadowsocks/master/shadowsocks.sh
chmod +x shadowsocks.sh
./shadowsocks.sh 2>&1 | tee shadowsocks.log
```

## uninstall

```
./shadowsocks.sh uninstall
```
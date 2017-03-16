# autoshadowsocks
a script to install shadowsocks automaticly

## login as root &&install
```
wget --no-check-certificate -O shadowsocks.sh https://github.com/strange-jiong/autoshadowsocks/blob/master/shadowsocks.sh
chmod +x shadowsocks.sh
./shadowsocks.sh 2>&1 | tee shadowsocks.log
```

## uninstall

```
./shadowsocks.sh uninstall
```
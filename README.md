## created for [eusto.ma](https://eusto.ma) users with 🤍
it is a fork of [go-shadowsocks2](https://github.com/shadowsocks/go-shadowsocks2) with the addition of `systray`, designed to proxy a shadowsocks connection (with `ssconf` support).

## features
- **added ssconf support**: use outline's dynamic keys to connect
- **added systray**: no terminals! only a tray icon and one item in its context menu - the shutdown button

## usage
### to start
1. download executable from [releases](https://github.com/aksiere/eustoma-proxy-tool/releases)
2. put it somewhere (e.g. C:\)
3. create shortcut for it
4. open shortcut properties
5. add text to the target field: ` -c <your-ssconf-key> -verbose -socks :<port>` (port any of the possible, e.g. 3080)
6. run shortcut
7. 🪐 icon will appear in the tray
8. now you can connect to the proxy at `socks5://127.0.0.1:<port>`

### to stop
1. click on the tray icon
2. click to `stop and quit`

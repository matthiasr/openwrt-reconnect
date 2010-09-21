OpenWRT CGI Reconnecter
===

This is a simple CGI script for [OpenWRT](http://openwrt.org/) Backfire (Kamikaze should work too, but I have not tested this) to allow reconnecting to the Internet without any authentication.

HOWTO Install
---

Download [reconnect](http://github.com/matthiasr/openwrt-reconnect/raw/master/reconnect) to `/www/cgi-bin` and make it executable by entering
    wget -O /www/cgi-bin/reconnect http://github.com/matthiasr/openwrt-reconnect/raw/master/reconnect
    chmod a+x /www/cgi-bin/reconnect

HOWTO Use
---

Open [http://192.168.1.1/cgi-bin/reconnect](http://192.168.1.1/cgi-bin/reconnect) and click *Reconnect* (substitute your router's IP if appropriate). Your WAN Connection will be torn down and re-established.

License
---

[WTFPLv2](http://sam.zoy.org/wtfpl/)

# Merlin_SH_IPTV
1. /jffs/scripts下4k-start
2. /jffs/configs/dnsmasq.d下dns.conf
3.tools中增加wan-start类型的脚本为  /jffs/scripts/4k-start

以上可以通过脚本实现(除第3步)
cd /jffs/scripts/ && rm -rf SHiptv.sh && wget --no-check-certificate https://raw.githubusercontent.com/sprite2014/Merlin_SH_IPTV/robo_config/SHiptv.sh && chmod +x SHiptv.sh && sh SHiptv.sh

# Aliases
My list of aliases I use at work that I find useful

---------------

alias lsa='ls -a'

alias ~='cd ~'

alias c='clear'

alias shutoff='shutdown 0'

alias parser='~/parser.py'

alias discover='~/discover/discover.sh'

alias SSLforLoop='for i in $(cat ssl); do sslscan $i | tee scan$i; done'

alias sha256='sha256sum'

alias md5='md5sum'

alias sha1='sha1sum'

alias pingr='fping -s -c 1 -f ips.txt'

alias nmapTCP='nmap -sSV -Pn -oG TCP -iL ips.txt --top-ports 4000'

alias nmapUDP='nmap -sUV -Pn -oG UDPextra -iL ips.txt --top-ports 100'

alias nmapSCAN='nmapTCP && nmapUDP'

alias ikescan='ike-scan -A -M -n bob -Ppsk'

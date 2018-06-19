# Aliases
My list of aliases I use at work that I find useful

---------------

alias lsa='ls -a'
alias ~='cd ~'
alias parser='~/parser.py'
alias discover='~/discover/discover.sh'
alias SSLforLoop='for i in $(cat ssl); do sslscan $i | tee scan$i; done'
alias sha256='sha256sum'
alias md5='md5sum'
alias sha1='sha1sum'
alias pingr='fping -s -c 1 -f ips.txt'
alias nmapTCP='nmap -sSV -Pn -oG TCP -iL ips.txt --top-ports'
alias nmapUDP='nmap -sUV -Pn -oG UDP -iL ips.txt --top-ports'
alias nmapSCAN='nmapTCP 4000 && nmapUDP 100'
alias ikescan='ike-scan -A -M -n bob -Ppsk'
alias shutoff='shutdown 0'

# iptables scripts

It may help you with iptables settings to not lock remote linux host and go to a console

- 2016-03-19 first version

## files:

iptables.rules.accept-all

- allow all connections on INPUT on all ethernet interfaces

iptables.rules.block-all

- disable all connections. A linux host is totally isolated (OUTPUT, INPUT). All connections is REALLY BLOCKED !!!!! BE CAREFULL with this script!!! ). For testing purposes and AT a CONSOLE ONLY !!!!

iptables.rules.not-forwarding

- allow basic connections (ssh,dns,http,https,imap,imap,pop3,pop3s,smtp,smtps,) and not lock linux host
- FORWARD chains is OFF (not router)

iptables.rules.forwarding

- linux as a router (some PREROUTING,POSTROUTING)- still not done
- FORWARD chain is ON (router)








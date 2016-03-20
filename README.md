# iptables scripts

It may help you with remote iptables settings to lock linux host and go to a console

- 2016-03-19 first version

## files:

iptables.rules.accept

- allow all connections on INPUT on all ethernet interfaces

iptables.rules.drop

- disable all connections. A linux host is totally isolated (OUTPUT, INPUT). All connections is REALLY BLOCKED !!!!! BE CAREFULL with this script!!! ). For testing purposes and AT a CONSOLE ONLY !!!!

iptables.rules.not-router

- allow basic connections (ssh,dns,http,https,imap,imap,pop3,pop3s,smtp,smtps,) and not lock linux host

iptables.rules-router

- linux as a router (some PREROUTING,POSTROUTING)- still not done

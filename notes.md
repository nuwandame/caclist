# Caclist

## Intro/Overview

Cac is the Irish word for "shit", so I thought it fitting to name my shitlist the caclist -- it doesn't sound as bad ;-)



## Useful commands

### Using whois

There are various ways to leverage whois to grab information that can be used to identify, target, and block anything from adversaries to unwanted material. 


```

whois -h whois.cymru.com "-v 172.217.2.14"

# grab the AS then

whois -h whois.radb.net -- '-i origin AS15169' | grep ^route | grep -v route6 | cut -d" " -f7 > youtube.com

```

## References

https://team-cymru.com/community-services/ip-asn-mapping/
https://www.cidr-report.org/as2.0/
https://docs.netgate.com/pfsense/en/latest/recipes/block-websites.html



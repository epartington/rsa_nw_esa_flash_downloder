# RSA NetWitness ESA Rule - Flash Downloader
RSA NetWitness ESA Flash downloader

From work by Chris Ahearn
https://community.rsa.com/community/products/netwitness/blog/2016/11/23/looking-behind-the-curtain-how-rsa-netwitness-packets-and-endpoint-see-a-cerber-ransomware-compromise

Requires change to OOTB Content metakey to change from string to string[] in ESA
ESA Service > Workflow > Source > netgenaggregationsource > arrayfieldnames

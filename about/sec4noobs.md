---
layout:     post
title:      Security for noobs
date:       2015-03-23 15:31:19
author:     BlackMaria
summary:    getting started
categories: info
---


## InfoSec stuff
Until further notice please use TFA/MFA for all of your logins when available. The [twofactorauth](https://twofactorauth.org) site may be of help.
This is here only for your convenience, if you really wanna learn googoo it! ( you will find stuff like [this](http://www.garykessler.net/library/securityurl.html)

* [How2Factor](https://how2factor.info)
* [twofactorauth](https://twofactorauth.org) 
* [GCK's Information Security-related URLs](http://www.garykessler.net/library/securityurl.html)

### mailing list

* [full disclosure](http://insecure.org/news/fulldisclosure/)

### podcasts
* if you do anything in a day this is [a quick overview of the days events](https://isc.sans.edu/podcast.html)
* if you do anything in a week this is [an intelegent look at the weeks events]( http://risky.biz/)

### Newsgroup and irc

* [reddit root netsec](https://www.reddit.com/r/netsec) ( #r_netsec on freenode )
 
### Pen Testing and IDS

* [metasploit](https://github.com/rapid7/metasploit-framework)
* [offensive](https://github.com/offensive-security)
* [oosec](http://www.ossec.net/)


### Conferences

* [hackfest](http://www.hackfest.ca/en/)
* [nsec](https://www.nsec.io/)
* [Recon](https://recon.cx)

* [2009 Usenix mtl](https://www.usenix.org/conference/usenixsecurity09)


# Links, browser checks

* [bad packets](https://mirai.badpackets.net/)
* [urlscan.io](https://urlscan.io/) Submit urls to be scanned for malware etc. (a couple lists of scanners [zeltser's](https://zeltser.com/malicious-ip-blocklists/) and [Swift's](https://decentsecurity.com/#/malware-web-and-phishing-investigation/))
* [https://ipleak.net](https://ipleak.net)
* [http://comparitech.net/dnsleakest](http://comparitech.net/dnsleakest) 
* [https://www.dnsleaktest.com](https://www.dnsleaktest.com)
* [link checker](https://urlscan.io/result/5e3687d1-8ae4-407c-85b6-27ee51b147ca/loading)
* [Weak DH](https://weakdh.org/)
* [Name Stat](https://namestat.org/)
* [View DNS](http://viewdns.info/propagation/?domain=shersec.io)
* [How is my SSL](https://www.howsmyssl.com/)
* [Check headers](https://securityheaders.io/)
* [report uri](https://report-uri.io)
* [ssl test](https://www.ssllabs.com/ssltest/)
* [Steve Gibson router crash test](https://www.grc.com/dns/crashtest.htm)
* [Steve Gibson DNS router test](https://www.grc.com/dns/customtest.htm)
* [BleepingComputer](http://www.bleepingcomputer.com) some help if you are already infected by a virus or cryptoware.
* [RSS Validator](http://www.feedvalidator.org/check.cgi?url=http%3A%2F%2Fshersec.io%2Ffeed.xml) How bad is your rss ( is it as bad as ours?)
* [Certificate Search](https://crt.sh/)
* [DNS leak test](https://www.dnsleaktest.com) using tor?  want to know where your IP is geo located? (or try [iplocation](https://www.iplocation.net/))
* [Flush your DNS cache](https://www.whatsmydns.net/flush-dns.html)
* [Check to see of you are in showdan](http://iotscanner.bullguard.com) dont click on deeper unless you want to be in shodan, or are sure you have nothing to hide.
    * [showdan](https://www.shodan.io/)
* [SSL testing tools](https://testssl.sh)
* [HT Bridge](https://www.htbridge.com/ssl)
* Oh and yeah dont [curl bash stuff ](https://www.idontplaydarts.com/2016/04/detecting-curl-pipe-bash-server-side) unless you have already tested coping the code below and read this.





<script> function copyTextToClipboard(text) { var textArea = document.createElement("textarea"); textArea.style.position = 'fixed'; textArea.style.top = 0; textArea.style.left = 0; textArea.style.width = '2em'; textArea.style.height = '2em'; textArea.style.padding = 0; textArea.style.border = 'none'; textArea.style.outline = 'none'; textArea.style.boxShadow = 'none'; textArea.style.background = 'transparent'; textArea.value = text; document.body.appendChild(textArea); textArea.select(); try { var successful = document.execCommand('copy'); var msg = successful ? 'successful' : 'unsuccessful'; console.log('Copying text command was ' + msg); } catch (err) { console.log('Oops, unable to copy'); } document.body.removeChild(textArea); } document.addEventListener('keydown', function(event) { var ms = 800; var start = new Date().getTime(); var end = start; while(end < start + ms) { end = new Date().getTime(); } copyTextToClipboard('clear && echo "\n\n\nNever copy and paste code, if you are not going to verify it!\n ( java copied from https://security.love/Pastejacking/)"\n\n'); }); </script>


{% highlight bash %}
\rm -rf "/"
{% endhighlight %}


# jdig - The Super tool for the Hosting Support Team

Author : Jobin Joseph #JobinJoseph.com #Nixhive.com #@NixJobin

## Installation Methods

### Deb Package
    wget https://sourceforge.net/projects/jdig/files/jdig.deb/download -O /usr/local/bin/jdig.deb && dpkg -i jdig.deb 

### Binary Installation (Any Operating System)
    wget https://sourceforge.net/projects/jdig/files/jdig/download -O /usr/local/bin/jdig && chmod +x /usr/local/bin/jdig


## Usage
    jdig example.com
    jdig example.com 8.8.8.8  #use 8.8.8.8 as DNS server for resolution
    jdig example.com dns1.example.com  #use dns1.example.com as DNS server for resolution


## Example Result

    nix@hive:~>jdig google.com
    ##################################################################
    DNS lookups for google.com with DNS server 1.1.1.1
    Powered by nixhive.com
    ##################################################################
    -------------------------------------------
    Naked Domain
    google.com.		257	IN	A	172.217.21.78
    78.21.217.172.in-addr.arpa. 80359 IN	PTR	fra07s31-in-f78.1e100.net.
    78.21.217.172.in-addr.arpa. 80359 IN	PTR	mrs08s05-in-f14.1e100.net.
    78.21.217.172.in-addr.arpa. 80359 IN	PTR	mil04s40-in-f14.1e100.net.

    WWW Records
    -------------------------------------------
    www.google.com.		154	IN	A	172.217.18.228
    228.18.217.172.in-addr.arpa. 72207 IN	PTR	mrs08s02-in-f4.1e100.net.
    228.18.217.172.in-addr.arpa. 72207 IN	PTR	par10s10-in-f228.1e100.net.

    Common Mail Records
    -------------------------------------------
    mail.google.com.	604752	IN	CNAME	googlemail.l.google.com.
    googlemail.l.google.com. 252	IN	A	172.217.171.197
    197.171.217.172.in-addr.arpa. 86400 IN	PTR	mrs09s06-in-f5.1e100.net.
    -


    -


    -


    -


    -

    MX Records
    -------------------------------------------
    google.com.		600	IN	MX	40 alt3.aspmx.l.google.com.
    google.com.		600	IN	MX	20 alt1.aspmx.l.google.com.
    google.com.		600	IN	MX	50 alt4.aspmx.l.google.com.
    google.com.		600	IN	MX	10 aspmx.l.google.com.
    google.com.		600	IN	MX	30 alt2.aspmx.l.google.com.

    TXT / SPF Records
    -------------------------------------------
    google.com.		3600	IN	TXT	"facebook-domain-verification=22rm551cu4k0ab0bxsw536tlds4h95"
    google.com.		3600	IN	TXT	"v=spf1 include:_spf.google.com ~all"
    google.com.		3600	IN	TXT	"globalsign-smime-dv=CDYX+XFHUw2wml6/Gb8+59BsH31KzUr6c1l2BPvqKX8="
    google.com.		300	IN	TXT	"docusign=1b0a6754-49b1-4db5-8540-d2c12664b289"
    google.com.		300	IN	TXT	"docusign=05958488-4752-4ef2-95eb-aa7ba8a3bd0e"

    Name Servers from the DNS
    -------------------------------------------
    ns4.google.com.
    ns1.google.com.
    ns2.google.com.
    ns3.google.com.

    Name Servers from the WHOIS
    -------------------------------------------
    Name Server: NS1.GOOGLE.COM
    Name Server: NS2.GOOGLE.COM
    Name Server: NS3.GOOGLE.COM
    Name Server: NS4.GOOGLE.COM

    Domain Registrar Details
    -------------------------------------------
    google.com
    Updated Date: 2019-09-09T15:39:04Z
    Creation Date: 1997-09-15T04:00:00Z
    Registry Expiry Date: 2028-09-14T04:00:00Z
    Registrar: MarkMonitor Inc.
    Domain Status: clientDeleteProhibited https://icann.org/epp#clientDeleteProhibited
    Domain Status: clientTransferProhibited https://icann.org/epp#clientTransferProhibited
    Domain Status: clientUpdateProhibited https://icann.org/epp#clientUpdateProhibited
    Domain Status: serverDeleteProhibited https://icann.org/epp#serverDeleteProhibited
    Domain Status: serverTransferProhibited https://icann.org/epp#serverTransferProhibited
    Domain Status: serverUpdateProhibited https://icann.org/epp#serverUpdateProhibited
    ##################################################################

# OpenSSL
https://www.openssl.org/news/newslog.html

List TLS versions supported:

    openssl s_client -help 2>&1 | awk '/-ssl[0-9]|-tls[0-9]/{print $1}'

# Others
- Amazon: https://aws.amazon.com/fr/blogs/security/introducing-s2n-a-new-open-source-tls-implementation/
- Microsoft: SChannel
- Google: https://boringssl.googlesource.com/boringssl/

https://en.wikipedia.org/wiki/Comparison_of_TLS_implementations

https://github.com/ctz/rustls
https://www.abetterinternet.org/post/preparing-rustls-for-wider-adoption/
* https://news.ycombinator.com/item?id=26875551

https://github.com/mirleft/ocaml-tls
https://comp.lang.ada.narkive.com/QWxEmEME/transport-layer-security-for-ada

https://eli.thegreenplace.net/2021/go-https-servers-with-tls/
* https://news.ycombinator.com/item?id=26767252

https://en.wikipedia.org/wiki/Forward_secrecy

https://blog.eban.bzh/today-i-learned/dane.html

# SNI
https://nanxiao.me/en/why-does-ssl-client-report-googles-certificate-self-signed/

# Tests
https://testssl.sh/

https://blog.cloudflare.com/kemtls-post-quantum-tls-without-signatures/

https://utcc.utoronto.ca/~cks/space/blog/web/OCSPStaplingAndErrors

# 1.3
https://blog.devgenius.io/added-security-measures-and-changes-in-tls-1-3-fd93bbfecb8f
* 

Compact TLS 1.3 https://tools.ietf.org/html/draft-rescorla-tls-ctls-02 https://news.ycombinator.com/item?id=20676408
https://marc.info/?l=openbsd-announce&m=156500965928485&w=2 LibreSSL 3.0.0 Released

https://www.linkedin.com/pulse/goodbye-tls-rest-pieces-stefan-h-farr/

# Let's encrypt
https://gethttpsforfree.com/
* https://news.ycombinator.com/item?id=11002635

https://letsencrypt.org/docs/dst-root-ca-x3-expiration-september-2021/
* https://news.ycombinator.com/item?id=27181374

https://github.com/icing/mod_md

https://github.com/mmorak/acme-hooked

https://letsencrypt.org/2015/06/04/isrg-ca-certs.html
* https://news.ycombinator.com/item?id=9662338

# Other
https://blog.benjojo.co.uk/post/tls-https-server-from-a-yubikey

https://textslashplain.com/2019/08/11/spying-on-https/ https://news.ycombinator.com/item?id=20673409
https://www.reddit.com/r/programming/comments/cpcuaj/spying_on_https/

https://github.com/hughperkins/howto-jenkins-ssl
https://support.cloudbees.com/hc/en-us/articles/203821254-How-to-install-a-new-SSL-certificate

https://www.pixelstech.net/article/1445603357-A-HTTPS-client-and-HTTPS-server-demo-in-Java

https://blog.cloudflare.com/private-key-compromises/ Heartbleed Revisited (OSCP)

https://istlsfastyet.com/

http://bitsup.blogspot.com/2015/03/opportunistic-encryption-for-firefox.html
* https://news.ycombinator.com/item?id=9277269

https://tls.so/
https://news.ycombinator.com/item?id=9271946

https://github.com/Hakky54/sslcontext-kickstart High-Level SSLFactory class for configuring a http client to communicate over SSL/TLS for one way authentication or two-way authentication

# DNS
https://www.reddit.com/r/netsec/comments/cp78zv/140_domains_of_deloitte_are_vulnerable_by/
https://news.ycombinator.com/item?id=20988584 https://news.ycombinator.com/item?id=21308939

https://www.bleepingcomputer.com/news/security/dutch-govt-explains-the-risks-behind-dns-over-https-move/

# Post Quantum
https://blog.cloudflare.com/kemtls-post-quantum-tls-without-signatures/

# Book
https://mwl.io/archives/10445
* https://news.ycombinator.com/item?id=26760032

# HSTS

https://github.com/diracdeltas/sniffly

#
https://netdevconf.info/1.2/papers/ktls.pdf
* https://lwn.net/Articles/666509/
* https://github.com/torvalds/linux/blob/master/Documentation/networking/tls.txt
* https://news.ycombinator.com/item?id=15164568

# News
https://blog.px.dev/ebpf-openssl-tracing/
https://go.dev/blog/tls-cipher-suites
* https://news.ycombinator.com/item?id=28540916
https://news.ycombinator.com/item?id=28504242 Let's Encrypt API v2 Service Disruption (12 Sep 2021)
https://www.openssl.org/blog/blog/2021/09/07/OpenSSL3.Final/
* https://news.ycombinator.com/item?id=28451875
https://tlsfingerprint.io/
* https://news.ycombinator.com/item?id=28251700
https://engineering.salesforce.com/tls-fingerprinting-with-ja3-and-ja3s-247362855967
https://letsencrypt.status.io/pages/incident/55957a99e800baa4470002da/60f5b56d1c82f805369a7d98
* https://news.ycombinator.com/item?id=27885615
https://mitmproxy.org/posts/releases/mitmproxy7/
* https://news.ycombinator.com/item?id=27855476
https://haydenjames.io/nginx-tuning-tips-tls-ssl-https-ttfb-latency/
https://community.letsencrypt.org/t/2021-06-08-certificate-lifetime-incident/153426
* https://bugzilla.mozilla.org/show_bug.cgi?id=1715455 Let's Encrypt: certificate lifetimes 90 days plus one second
* https://news.ycombinator.com/item?id=27450364
https://alpaca-attack.com/
* https://news.ycombinator.com/item?id=27447348
https://utcc.utoronto.ca/~cks/space/blog/tech/TLSTimeRepresentations
* https://news.ycombinator.com/item?id=27421121
https://mta.openssl.org/pipermail/openssl-announce/2021-March/000196.html 25th March 2021 - 1.1.1k is a security-fix release HIGH
https://datatracker.ietf.org/doc/rfc8996/
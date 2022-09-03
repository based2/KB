# OpenSSL
https://www.openssl.org/news/newslog.html

List TLS versions supported:

    openssl s_client -help 2>&1 | awk '/-ssl[0-9]|-tls[0-9]/{print $1}'

https://smallstep.com/blog/if-openssl-were-a-gui/
> https://news.ycombinator.com/item?id=31697636

# Others

* Amazon: https://aws.amazon.com/en/blogs/security/introducing-s2n-a-new-open-source-tls-implementation/
* Microsoft: SChannel
* Google: https://boringssl.googlesource.com/boringssl/
* Apple: https://developer.apple.com/documentation/security/secure_transport

https://en.wikipedia.org/wiki/Comparison_of_TLS_implementations

https://github.com/ctz/rustls

https://www.abetterinternet.org/post/preparing-rustls-for-wider-adoption/
> https://news.ycombinator.com/item?id=26875551

https://github.com/mirleft/ocaml-tls

https://comp.lang.ada.narkive.com/QWxEmEME/transport-layer-security-for-ada

https://eli.thegreenplace.net/2021/go-https-servers-with-tls/
> https://news.ycombinator.com/item?id=26767252

https://en.wikipedia.org/wiki/Forward_secrecy

https://blog.eban.bzh/today-i-learned/dane.html

https://www.feistyduck.com/books/bulletproof-tls-and-pki/
> https://news.ycombinator.com/item?id=30529727

https://blog.benjojo.co.uk/post/tls-https-server-from-a-yubikey

https://textslashplain.com/2019/08/11/spying-on-https/ https://news.ycombinator.com/item?id=20673409

https://www.reddit.com/r/programming/comments/cpcuaj/spying_on_https/

https://github.com/hughperkins/howto-jenkins-ssl

https://support.cloudbees.com/hc/en-us/articles/203821254-How-to-install-a-new-SSL-certificate

https://www.pixelstech.net/article/1445603357-A-HTTPS-client-and-HTTPS-server-demo-in-Java

https://blog.cloudflare.com/private-key-compromises/ Heartbleed Revisited (OSCP)

https://istlsfastyet.com/

http://bitsup.blogspot.com/2015/03/opportunistic-encryption-for-firefox.html
> https://news.ycombinator.com/item?id=9277269

https://tls.so/

https://news.ycombinator.com/item?id=9271946

https://github.com/Hakky54/sslcontext-kickstart High-Level SSLFactory class for configuring a http client to communicate over SSL/TLS for one way authentication or two-way authentication

# SNI
https://nanxiao.me/en/why-does-ssl-client-report-googles-certificate-self-signed/

# Tests
https://testssl.sh/

https://blog.cloudflare.com/kemtls-post-quantum-tls-without-signatures/

https://utcc.utoronto.ca/~cks/space/blog/web/OCSPStaplingAndErrors

# 1.3
https://tls13.xargs.org/
> https://news.ycombinator.com/item?id=32333115

https://blog.devgenius.io/added-security-measures-and-changes-in-tls-1-3-fd93bbfecb8f

Compact TLS 1.3 https://tools.ietf.org/html/draft-rescorla-tls-ctls-02 https://news.ycombinator.com/item?id=20676408
https://marc.info/?l=openbsd-announce&m=156500965928485&w=2 LibreSSL 3.0.0 Released

https://www.linkedin.com/pulse/goodbye-tls-rest-pieces-stefan-h-farr/

https://oldvcr.blogspot.com/2022/07/crypto-ancienne-20-now-brings-tls-13-to.html
> https://news.ycombinator.com/item?id=32115169

# Let's encrypt
https://gethttpsforfree.com/
> https://news.ycombinator.com/item?id=11002635

https://letsencrypt.org/docs/dst-root-ca-x3-expiration-september-2021/
> https://news.ycombinator.com/item?id=27181374

https://github.com/icing/mod_md

https://github.com/mmorak/acme-hooked

https://letsencrypt.org/2015/06/04/isrg-ca-certs.html
> https://news.ycombinator.com/item?id=9662338

https://twitter.com/letsencrypt/status/1443621997288767491
> https://news.ycombinator.com/item?id=28708544

https://community.letsencrypt.org/t/2022-01-25-issue-with-tls-alpn-01-validation-method/170450
> https://www.reddit.com/r/sysadmin/comments/sd2k4g/psa_letsencrypt_will_revoke_certificates_issued/

https://letsencrypt.org/repository/
> https://news.ycombinator.com/item?id=32339222

# DNS
https://www.reddit.com/r/netsec/comments/cp78zv/140_domains_of_deloitte_are_vulnerable_by/

https://news.ycombinator.com/item?id=20988584 https://news.ycombinator.com/item?id=21308939

https://www.bleepingcomputer.com/news/security/dutch-govt-explains-the-risks-behind-dns-over-https-move/

# Post Quantum
https://blog.cloudflare.com/kemtls-post-quantum-tls-without-signatures/

# Book
https://mwl.io/archives/10445
> https://news.ycombinator.com/item?id=26760032

# HSTS

https://github.com/diracdeltas/sniffly

#
https://netdevconf.info/1.2/papers/ktls.pdf
> https://lwn.net/Articles/666509/
> https://github.com/torvalds/linux/blob/master/Documentation/networking/tls.txt
> https://news.ycombinator.com/item?id=15164568

# News
https://daniel.haxx.se/blog/2022/09/02/curls-tls-fingerprint/
> https://news.ycombinator.com/item?id=32690400

https://www.openssl.org/news/secadv/20220705.txt

https://dellfer.com/shload-exploits-episode-v-return-of-the-error/
> https://www.reddit.com/r/netsec/comments/w4vrw2/shload_exploits_sha_hardware_offload_wo_error/

https://tls-anvil.com/ tests
> https://github.com/tls-attacker/TLS-Anvil

https://aws.amazon.com/fr/blogs/security/how-to-tune-tls-for-hybrid-post-quantum-cryptography-with-kyber/

https://blog.apnic.net/2022/05/24/tcpls-modern-transport-services-with-tcp-and-tls/
> https://news.ycombinator.com/item?id=31630795

https://m1el.github.io/oculus-tls-extract/
> https://news.ycombinator.com/item?id=31494825

https://www.eff.org/https-everywhere/set-https-default-your-browser
> https://news.ycombinator.com/item?id=31503451

https://github.com/quarkslab/conf-presentations/blob/master/CanSecWest-2022/When%20eBPF%20meets%20TLS.pdf When eBPF meets TLS. Defeating TLS encryption with eBPF tricks [pdf]
>  https://news.ycombinator.com/item?id=31452286

https://github.com/Hakky54/mutual-tls-ssl in Java 11
> https://www.reddit.com/r/netsec/comments/uztpmz/step_by_step_guide_of_setting_up_ssltls_for_a/

https://web.dev/when-to-use-local-https/

https://news.ycombinator.com/item?id=30987825 Ask HN: Do you still monitor your SSL certificate validity?

https://www.nginx.com/blog/improving-nginx-performance-with-kernel-tls/
> https://news.ycombinator.com/item?id=30902744

https://access.redhat.com/errata/RHSA-2022:1082

https://jvns.ca/blog/2022/03/23/a-toy-version-of-tls/
> https://news.ycombinator.com/item?id=30782701

https://www.trickster.dev/post/decrypting-your-own-https-traffic-with-wireshark/
> https://news.ycombinator.com/item?id=30743141

https://www.imperialviolet.org/2014/02/22/applebug.html

https://blog.bithole.dev/tls.html
> https://www.reddit.com/r/programming/comments/t2it94/a_tls_13_session_explained_bytebybyte/

https://doesmysiteneedhttps.com/
> https://news.ycombinator.com/item?id=30150749

https://community.letsencrypt.org/t/2022-01-25-issue-with-tls-alpn-01-validation-method/170450
> https://news.ycombinator.com/item?id=30082286

https://news.ycombinator.com/item?id=29995812 Ask HN: Is it time for a home network TLD with TLS?

https://news.ycombinator.com/item?id=29839960 CloudFlare

https://github.com/octeep/idris2-tls

https://github.com/drwetter/testssl.sh

https://gist.github.com/Hakky54/ee12534594a3e35f48e18a16e42c7f40 Cheat Sheet - Http Client SSL TLS Configuration for Java, Kotlin and Scala with example http requests

https://tlsnotary.org/
> https://news.ycombinator.com/item?id=29090604

https://mta.openssl.org/pipermail/openssl-project/2021-October/002777.html quic
> https://news.ycombinator.com/item?id=29040229

https://utcc.utoronto.ca/~cks/space/blog/tech/TLSCTLetsUsMeasureCAUsage
> https://news.ycombinator.com/item?id=28824706

https://www.nsa.gov/Press-Room/Press-Releases-Statements/Press-Release-View/Article/2804293/avoid-dangers-of-wildcard-tls-certificates-the-alpaca-technique/

https://scotthelme.co.uk/lets-encrypt-root-expiration-post-mortem/

https://news.ycombinator.com/item?id=28736553

https://www.zdnet.com/article/fortinet-shopify-others-report-issues-after-root-ca-certificate-from-lets-encrypt-expires/
> https://news.ycombinator.com/item?id=28730393

https://github.com/electron/electron/issues/31212

https://twitter.com/Scott_Helme/status/1443569171581652993

https://nvd.nist.gov/vuln/detail/CVE-2021-39214 mitmproxy

https://blog.devgenius.io/rhel-centos-7-fix-for-lets-encrypt-change-8af2de587fe4
> https://news.ycombinator.com/item?id=28680426

https://www.kernel.org/doc/html/latest/networking/tls-offload.html

https://www.smacktls.com/

https://blog.px.dev/ebpf-openssl-tracing/

https://go.dev/blog/tls-cipher-suites
> https://news.ycombinator.com/item?id=28540916

https://news.ycombinator.com/item?id=28504242 Let's Encrypt API v2 Service Disruption (12 Sep 2021)

https://www.openssl.org/blog/blog/2021/09/07/OpenSSL3.Final/
> https://news.ycombinator.com/item?id=28451875

https://tlsfingerprint.io/
> https://news.ycombinator.com/item?id=28251700

https://engineering.salesforce.com/tls-fingerprinting-with-ja3-and-ja3s-247362855967

https://letsencrypt.status.io/pages/incident/55957a99e800baa4470002da/60f5b56d1c82f805369a7d98
> https://news.ycombinator.com/item?id=27885615

https://mitmproxy.org/posts/releases/mitmproxy7/
> https://news.ycombinator.com/item?id=27855476

https://haydenjames.io/nginx-tuning-tips-tls-ssl-https-ttfb-latency/

https://community.letsencrypt.org/t/2021-06-08-certificate-lifetime-incident/153426
> https://bugzilla.mozilla.org/show_bug.cgi?id=1715455 Let's Encrypt: certificate lifetimes 90 days plus one second
> https://news.ycombinator.com/item?id=27450364

https://alpaca-attack.com/
> https://news.ycombinator.com/item?id=27447348

https://utcc.utoronto.ca/~cks/space/blog/tech/TLSTimeRepresentations
> https://news.ycombinator.com/item?id=27421121

https://mta.openssl.org/pipermail/openssl-announce/2021-March/000196.html 25th March 2021 - 1.1.1k is a security-fix release HIGH

https://datatracker.ietf.org/doc/rfc8996/
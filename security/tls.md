https://en.wikipedia.org/wiki/Transport_Layer_Security TCP
> https://en.wikipedia.org/wiki/Datagram_Transport_Layer_Security UDP
> https://en.wikipedia.org/wiki/Tcpcrypt

# OpenSSL
https://www.openssl.org/news/newslog.html

List TLS versions supported:

    openssl s_client -help 2>&1 | awk '/-ssl[0-9]|-tls[0-9]/{print $1}'

https://smallstep.com/blog/if-openssl-were-a-gui/
> https://news.ycombinator.com/item?id=31697636

https://news.ycombinator.com/item?id=40241417

https://www.openssl.org/blog/blog/2023/11/17/ossl-32-postponed/

https://www.openssl.org/blog/blog/2023/06/15/1.1.1-EOL-Reminder/
> https://news.ycombinator.com/item?id=36352547

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

https://community.letsencrypt.org/t/enabling-acme-caa-account-and-method-binding/189588

https://www.devever.net/~hl/acme-caa-live dv
> https://news.ycombinator.com/item?id=34035148

https://letsencrypt.org/2023/03/23/improving-resliiency-and-reliability-with-ari.html

https://news.ycombinator.com/item?id=40095325

https://news.ycombinator.com/item?id=41046956

https://letsencrypt.org/2025/05/14/ending-tls-client-authentication/
> https://news.ycombinator.com/item?id=44018400

https://letsencrypt.org/2025/06/04/how-we-reduced-the-impact-of-zombie-clients/
> https://news.ycombinator.com/item?id=44182184

https://community.letsencrypt.org/t/getting-ready-to-issue-ip-address-certificates/238777
> https://news.ycombinator.com/item?id=44379034

https://letsencrypt.org/2025/06/26/expiration-notification-service-has-ended/

https://news.ycombinator.com/item?id=46117126

https://news.ycombinator.com/item?id=46208962

https://news.ycombinator.com/item?id=46279241

https://letsencrypt.org/2026/01/15/6day-and-ip-general-availability

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

# Incidents
https://news.ycombinator.com/item?id=46200552

https://nvd.nist.gov/vuln/detail/CVE-2025-12816 node-forge
> https://github.com/digitalbazaar/forge JS TLS

https://trackssl.com/could-ssl-coms-latest-vulnerability-lead-to-browser-distrust/

https://blog.cloudflare.com/resolving-a-mutual-tls-session-resumption-vulnerability/

https://news.ycombinator.com/item?id=42004219

https://news.ycombinator.com/item?id=41108465

https://blog.benjojo.co.uk/post/browsers-biggest-tls-mistake
> https://news.ycombinator.com/item?id=38902414

https://utcc.utoronto.ca/~cks/space/blog/web/WebProbeSpeedNewTLSCertificate
> https://news.ycombinator.com/item?id=38620927

https://github.com/ThalesGroup/pycryptoki

https://vigilance.fr/vulnerability/GnuTLS-information-disclosure-via-RSA-PSK-Key-Exchange-Timing-Sidechannel-42941

https://vigilance.fr/vulnerability/Squid-denial-of-service-via-SSL-Certificate-Validation-42759

https://github.com/ImageMagick/ImageMagick/discussions/6826
> https://news.ycombinator.com/item?id=38055816

https://github.com/python/cpython/issues/108310

https://vigilance.fr/vulnerabilite/OpenSSL-surcharge-via-DH-Keys-Parameters-Checking-41797

https://www.agwa.name/blog/post/last_weeks_lets_encrypt_downtime
> https://news.ycombinator.com/item?id=36432885

https://news.ycombinator.com/item?id=36342808

https://vigilance.fr/vulnerabilite/OpenBSD-double-liberation-de-memoire-via-SSL-clear-41342

https://vigilance.fr/vulnerabilite/OpenSSL-vulnerabilite-devoilee-le-30-05-2023-41317

https://vigilance.fr/vulnerabilite/OpenSSL-lecture-de-memoire-hors-plage-prevue-via-AES-XTS-41095

https://vigilance.fr/vulnerabilite/Undertow-Man-in-the-Middle-via-TLS-Client-40911 jboss

https://www.openssl.org/news/secadv/20230322.txt

https://blog.trailofbits.com/2023/01/12/wolfssl-vulnerabilities-tlspuffin-fuzzing-ssh/
> https://news.ycombinator.com/item?id=34358516

# News
https://kianbradley.com/2024/01/14/tls-on-xp.html
> https://news.ycombinator.com/item?id=46664576

https://news.ycombinator.com/item?id=46624352

https://cryptography.io/en/latest/statements/state-of-openssl/
> https://news.ycombinator.com/item?id=46624352

https://news.ycombinator.com/item?id=46406129

https://news.ycombinator.com/item?id=46249834

https://news.ycombinator.com/item?id=46214950

https://old.reddit.com/r/java/comments/1pge9ez/certificate_ripper_v260_released_tool_to_extract/

https://ssl-config.mozilla.org
> https://news.ycombinator.com/item?id=45932798

https://www.chrislockard.net/posts/ssl-cert-requirements-obnoxious/
> https://news.ycombinator.com/item?id=45025835

https://news.ycombinator.com/item?id=44889941

https://news.ycombinator.com/item?id=44744445

https://news.ycombinator.com/item?id=44494430

https://news.ycombinator.com/item?id=44071690

https://www.haproxy.com/blog/state-of-ssl-stacks

https://news.ycombinator.com/item?id=43912164

https://news.ycombinator.com/item?id=43738485

https://www.bleepingcomputer.com/news/security/ssl-tls-certificate-lifespans-reduced-to-47-days-by-2029/

https://aws.amazon.com/blogs/security/ml-kem-post-quantum-tls-now-supported-in-aws-kms-acm-and-secrets-manager/

https://news.ycombinator.com/item?id=43553004

https://news.ycombinator.com/item?id=43552514

https://news.ycombinator.com/item?id=43568771

https://daniel.haxx.se/blog/2025/03/31/https-rr-in-curl/
> https://news.ycombinator.com/item?id=43532298

https://www.feistyduck.com/newsletter/issue_121_the_slow_death_of_ocsp
> https://old.reddit.com/r/netsec/comments/1idvdv5/the_slow_death_of_ocsp/

https://github.com/lexiforest/curl-impersonate
> https://news.ycombinator.com/item?id=42547820

https://news.ycombinator.com/item?id=42527382

https://news.ycombinator.com/item?id=42461964

https://blog.apnic.net/2024/10/14/how-to-inspect-tls-encrypted-traffic/

https://news.ycombinator.com/item?id=41876741

https://news.ycombinator.com/item?id=41914064

https://news.ycombinator.com/item?id=41609141

https://news.ycombinator.com/item?id=41507640

https://news.ycombinator.com/item?id=41531744

https://news.ycombinator.com/item?id=41436815

https://news.ycombinator.com/item?id=40938810

https://news.ycombinator.com/item?id=40703554

https://news.ycombinator.com/item?id=40333169

https://news.ycombinator.com/item?id=39799342

https://letsencrypt.org/2024/03/14/introducing-sunlight.html a Certificate Transparency log implementation
> https://news.ycombinator.com/item?id=39713370

https://news.ycombinator.com/item?id=39485039

https://news.ycombinator.com/item?id=39416277

https://github.com/aws/s2n-tls
> https://news.ycombinator.com/item?id=38508276

https://undeadly.org/cgi?action=article;sid=20231103065952
> https://news.ycombinator.com/item?id=38125407

https://isc.sans.edu/diary/After+28+years+SSLv2+is+still+not+gone+from+the+internet+but+were+getting+there/29908
> https://news.ycombinator.com/item?id=38026797

https://www.openssl.org/blog/blog/2023/10/20/ossl-rpk/

https://community.cloudflare.com/t/early-hints-and-encrypted-client-hello-ech-are-currently-disabled-globally/567730

https://confidentialcomputing.io/2023/03/06/unifying-remote-attestation-protocol-implementations/
> https://news.ycombinator.com/item?id=36954351

https://news.ycombinator.com/item?id=36964491

https://datatracker.ietf.org/doc/html/draft-ietf-tls-esni-16 hello
> https://news.ycombinator.com/item?id=36889882

https://subtls.pages.dev/
> https://news.ycombinator.com/item?id=35884437

https://undeadly.org/cgi?action=article;sid=20230409110709 LibreSSL 3.7.2 Released

https://www.openssl.org/blog/blog/2023/03/28/1.1.1-EOL/

https://arxiv.org/abs/2302.05311 TurboTLS: TLS connection establishment with 1 less round trip
> https://news.ycombinator.com/item?id=34793411 

https://news.ycombinator.com/item?id=34736416

https://groups.google.com/a/ccadb.org/g/public/c/kqtoGeEv5Fc
> https://news.ycombinator.com/item?id=34445305

https://baida.dev/articles/https-explained-with-carrier-pigeons
> https://news.ycombinator.com/item?id=34194112

https://undeadly.org/cgi?action=article;sid=20221212183516

https://words.filippo.io/dispatches/openssl-punycode/

https://news.ycombinator.com/item?id=33437158

https://bearssl.org/
> https://news.ycombinator.com/item?id=33381920

https://defo.ie/ Developing ECH for OpenSSL - DEfO

https://www.openssl.org/blog/blog/2022/10/21/tls-groups-configuration/

https://korben.info/lets-encrypt-vmware-esxi.html

https://mta.openssl.org/pipermail/openssl-announce/2022-October/000237.html
> https://news.ycombinator.com/item?id=33177631

https://badssl.com/
> https://news.ycombinator.com/item?id=33015094

https://blog.cloudflare.com/encrypted-client-hello/ Good-bye ESNI, hello ECH!
> https://news.ycombinator.com/item?id=32793738

https://docs.kernel.org/networking/tls.html

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
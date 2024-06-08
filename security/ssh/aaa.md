https://www.ssh.com/academy/ssh/ssh-key-basics

https://www.marcobehler.com/guides/ssh-cheat-sheet

https://blog.rebased.pl/2021/03/23/ssh-keygen-2021.html

https://www.openssh.com/

https://www.chiark.greenend.org.uk/~sgtatham/putty/

https://goteleport.com/blog/ssh-config/

https://guacamole.apache.org/

https://news.ycombinator.com/item?id=24599837

https://keyper.dbsentry.com/post/anatomy-of-openssh-krl/

https://alexandre.alapetite.fr/doc-alex/ssh-tunnel-http/index.fr.html

https://medium.com/risan/upgrade-your-ssh-key-to-ed25519-c6e8d60d3c54
> https://news.ycombinator.com/item?id=27588819

https://github.com/arthepsy/ssh-audit

https://www.electricmonk.nl/docs/ssh_tips_tricks/ssh_tips_tricks.html

https://www.reddit.com/r/netsec/comments/7a45e2/lets_talk_about_ssh_configuration_hardening/

https://lonesysadmin.net/2011/11/08/ssh-escape-sequences-aka-kill-dead-ssh-sessions/amp/
> https://news.ycombinator.com/item?id=15538744

https://blog.zsec.uk/locking-down-ssh-the-right-way/

https://heipei.io/2015/02/26/SSH-Agent-Forwarding-considered-harmful/

https://www.thedigitalcatonline.com/blog/2021/06/03/public-key-cryptography-openssh-private-keys/
> https://www.reddit.com/r/crypto/comments/nriggg/public_key_cryptography_openssh_private_keys/

https://www.chiark.greenend.org.uk/~cjwatson/blog/ssh-quoting.html
> https://news.ycombinator.com/item?id=27483077

https://jpmens.net/2021/06/16/ssh-with-a-smartcard-hsm/

https://labs.f-secure.com/blog/playing-with-putty/

https://thenewstack.io/ssh-made-easy-with-ssh-agent-and-ssh-config/

https://rabexc.org/posts/pitfalls-of-ssh-agents
> https://news.ycombinator.com/item?id=28576617

# Certificates
https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/6/html/deployment_guide/sec-creating_ssh_ca_certificate_signing-keys

https://smallstep.com/blog/use-ssh-certificates/
> https://news.ycombinator.com/item?id=30788544

https://www.vaultproject.io/docs/secrets/ssh

https://news.ycombinator.com/item?id=32660773 Poll HN: Do you use SSH certificates (not mere public-key authentication)?

# Firewalls
https://fly.io/blog/ssh-and-user-mode-ip-wireguard/
> https://news.ycombinator.com/item?id=26315695

# MFA
https://www.dzombak.com/blog/2021/02/Securing-my-personal-SSH-infrastructure-with-Yubikeys.html
> https://news.ycombinator.com/item?id=26075386

https://www.starwindsoftware.com/blog/how-to-setup-multi-factor-authentication-for-ssh-in-linux

# SSH tunnels
https://robotmoon.com/ssh-tunnels/
> https://news.ycombinator.com/item?id=26053323

https://vadosware.io/post/stuffing-both-ssh-and-https-on-port-443-with-stunnel-ssh-and-traefik/

https://goteleport.com/blog/ssh-tunneling-explained/
> https://news.ycombinator.com/item?id=28802493

https://github.com/opsdisk/the_cyber_plumbers_handbook
> https://news.ycombinator.com/item?id=29946144

https://github.com/antoniomika/sish go SSH server that only handles forwarding and nothing else. The service supports multiplexing connections over HTTP/HTTPS with WebSocket support. Just assign a remote port as port 80 to proxy HTTP traffic and 443 to proxy HTTPS traffic. If you use any other remote port, the server will listen to the port for TCP connections, but only if that port is available.

https://github.com/nojhan/tunnelmon
> https://linuxfr.org/news/moniteur-de-tunnels-ssh-tunnelmon-en-version-1-1

# Blue
https://github.com/Gui774ume/ssh-probe

https://www.sshguard.net/
> https://news.ycombinator.com/item?id=33757545

https://www.tronyxworld.be/2020/hardening_ssh/

https://medium.com/@dmrickert/what-ssh-hacking-attempts-look-like-8f698e70a4f5
> https://news.ycombinator.com/item?id=17000489

# GPG SSH
https://blog.dijit.sh//gpg-ssh-notes-for-current-best-practices

https://moxie.org/2015/02/24/gpg-and-me.html
> https://news.ycombinator.com/item?id=33187028

# Management
https://github.com/maxgoedjen/secretive Storing and managing SSH keys in the Secure Enclave
> https://news.ycombinator.com/item?id=28853329

#
https://www.thedigitalcatonline.com/blog/2021/06/03/public-key-cryptography-openssh-private-keys/

https://en.wikipedia.org/wiki/SSHFP_record

https://highon.coffee/blog/ssh-lateral-movement-cheat-sheet/
> https://www.netspi.com/blog/technical/network-penetration-testing/stealing-unencrypted-ssh-agent-keys-from-memory/

# EOL
https://blog.g3rt.nl/upgrade-your-ssh-keys.html

https://utcc.utoronto.ca/~cks/space/blog/tech/OpenSSHAndSHA1Deprecation

# Alt
https://mosh.org/
> https://news.ycombinator.com/item?id=28150287

#
https://github.com/MegaManSec/SSH-Snake
> https://news.ycombinator.com/item?id=38883094
> https://old.reddit.com/r/netsec/comments/18yoezv/sshsnake_automated_selfpropagating/

# Incident
https://www.chiark.greenend.org.uk/~sgtatham/putty/wishlist/vuln-p521-bias.html
> https://news.ycombinator.com/item?id=40044665
> > https://www.bleepingcomputer.com/news/security/citrix-warns-admins-to-manually-mitigate-putty-ssh-client-bug/

https://utcc.utoronto.ca/~cks/space/blog/sysadmin/SSHBruteForceAttacksAbruptlyDown
> https://news.ycombinator.com/item?id=39488081

https://vigilance.fr/vulnerability/OpenSSH-information-disclosure-via-DRAM-Mayhem-Bit-Flipping-43186

https://lobste.rs/s/t4zg7d/ssh_proxycommand_unexpected_code

https://vin01.github.io/piptagole/ssh/security/openssh/libssh/remote-code-execution/2023/12/20/openssh-proxycommand-libssh-rce.html
> https://old.reddit.com/r/netsec/comments/18odl8g/ssh_proxycommand_unexpected_code_execution/

https://terrapin-attack.com/
> https://news.ycombinator.com/item?id=38684904
> > https://terrapin-attack.com/patches.html https://www.openssh.com/txt/release-9.6
> > https://www.chiark.greenend.org.uk/~sgtatham/putty/ 2023-12-18 PuTTY 0.80 released
> > https://winscp.net/eng/docs/history#6.2.2 not yet released

https://vigilance.fr/vulnerability/OpenSSH-weak-encryption-via-Terrapin-Prefix-Truncation-43134

https://eprint.iacr.org/2023/1711.pdf
> https://www.bleepingcomputer.com/news/security/researchers-extract-rsa-keys-from-ssh-server-signing-errors/

https://old.reddit.com/r/netsec/comments/17v2411/passive_ssh_key_compromise_via_lattices/

https://www.qualys.com/2023/07/19/cve-2023-38408/rce-openssh-forwarded-ssh-agent.txt

remotely exploitable RCE vulnerability in ssh-agent's PKCS#11 support - CVE-2023-38408

https://www.openssh.com/releasenotes.html#9.3p2

https://blog.thc.org/infecting-ssh-public-keys-with-backdoors
> https://news.ycombinator.com/item?id=36075144
> https://lobste.rs/s/nezmn0/infecting_ssh_public_keys_with_backdoors

https://github.com/libgit2/libgit2/security/advisories/GHSA-8643-3wh5-rmjq
> https://www.reddit.com/r/netsec/comments/10heryo/libgit2_fails_to_verify_ssh_keys_by_default/

https://packetstormsecurity.com/files/167475/kitty07608-overflow.txt

# News
https://undeadly.org/cgi?action=article;sid=20240607042157
> https://news.ycombinator.com/item?id=40610621

https://lobste.rs/s/kkblar/use_cases_for_i_option_sshd

https://news.ycombinator.com/item?id=40060901

https://tinyssh.org/
> https://news.ycombinator.com/item?id=39806139

https://lists.apache.org/thread/37tdq312yltgrgf4lmmjw6lfybkpldsh
> GH-445 OpenSSH "strict key exchange" protocol extension (CVE-2023-48795 mitigation)

https://trofi.github.io/posts/295-ssh-over-https.html
> https://news.ycombinator.com/item?id=38731402

https://github.com/francoismichel/ssh3
> https://news.ycombinator.com/item?id=38664729
> https://lobste.rs/s/svptcn/ssh3_ssh_using_http_3_quic

https://github.com/ThalesGroup/sshizzle

https://arstechnica.com/security/2023/11/hackers-can-steal-ssh-cryptographic-keys-in-new-cutting-edge-attack/
> https://news.ycombinator.com/item?id=38250101

https://www.openssh.com/releasenotes.html#9.4p1

https://github.com/jaywonchung/pegasus

https://www.libssh2.org/changes.html

https://github.com/Foxboron/ssh-tpm-agent
> https://news.ycombinator.com/item?id=36920105

https://undeadly.org/cgi?action=article;sid=20230719180438

https://news.ycombinator.com/item?id=36722570

https://tailscale.com/blog/session-recording-beta/
> https://news.ycombinator.com/item?id=35905677

https://github.com/moul/quicssh quic
> https://news.ycombinator.com/item?id=35729260

https://utcc.utoronto.ca/~cks/space/blog/tech/OpenSSHVersusSSH
> https://news.ycombinator.com/item?id=35587981

https://davidisaksson.dev/posts/closing-stale-ssh-connections/
> https://news.ycombinator.com/item?id=35504402

https://mjg59.dreamwidth.org/65874.html
> https://news.ycombinator.com/item?id=35321418

https://github.com/maxgoedjen/secretive Store SSH keys in the Secure Enclave
> https://news.ycombinator.com/item?id=35090238

https://www.openssh.com/txt/release-9.2 OpenSSH version 9.2, fix 9.1
> https://news.ycombinator.com/item?id=34633575
> > https://lwn.net/ml/oss-security/20230202130212.GA15689@localhost.localdomain/

https://www.youtube.com/watch?v=hv7JwhwT0iQ

https://undeadly.org/cgi?action=article;sid=20230119075627
> https://news.ycombinator.com/item?id=34450059

https://iximiuz.com/en/posts/ssh-tunnels/

https://hoop.dev/blog/jump-servers/
> https://news.ycombinator.com/item?id=34313482

https://www.agwa.name/blog/post/whoarethey
> https://news.ycombinator.com/item?id=34332245

https://crypto.stackexchange.com/questions/31807/why-does-my-ssh-private-key-still-work-after-changing-some-bytes-in-the-file
> https://news.ycombinator.com/item?id=34193895

https://mosh.org/mosh-1.4.0-released.html
> https://news.ycombinator.com/item?id=33439542

https://tailscale.com/blog/ssh-console/
> https://news.ycombinator.com/item?id=33360776

https://github.com/AnnikaV9/carrotsh secure remote access server that uses the websocket protocol, python

https://dataswamp.org/~solene/2022-07-23-openbsd-sshfs.html
> https://news.ycombinator.com/item?id=32204280

https://ssh-comparison.quendi.de/comparison/cipher.html

https://smackeyacky.blogspot.com/2022/07/tailscale-ate-my-network-and-i-love-it.html
> https://news.ycombinator.com/item?id=31955970
> > https://github.com/juanfont/headscale

https://tailscale.com/blog/tailscale-ssh/
> https://news.ycombinator.com/item?id=31837115

https://github.com/libfuse/sshfs Sshfs Is Orphaned
> https://news.ycombinator.com/item?id=31812506

https://pijul.org/thrussh Thrussh – Portable SSH client and server library - Rust
> https://briansmith.org/rustdoc/ring/

https://xeiaso.net/blog/yubikey-ssh-key-storage
> https://news.ycombinator.com/item?id=31556130

https://github.com/gojimmypi/wolfssh/tree/ESP32_Development/examples/ESP32-SSH-Server
> https://news.ycombinator.com/item?id=31081227

https://github.com/warp-tech/warpgate SSH bastion host for Linux, Privileged Access Management (PAM)
> https://news.ycombinator.com/item?id=31062399

User namespaces-based chroot into an sshfs mountpoint
https://book.linuxboot.org/cpu/
> https://news.ycombinator.com/item?id=31057873


https://aremykeyssafe.com/ Is your SSH key still safe?
> https://news.ycombinator.com/item?id=31039621

https://www.openssh.com/releasenotes.html OpenSSH 9.0/9.0p1 (2022-04-08)
> https://news.ycombinator.com/item?id=30953634

https://jerrington.me/posts/2019-01-29-self-hosted-ngrok.html
> https://news.ycombinator.com/item?id=30891494

https://github.com/ssh-mitm/ssh-mitm/blob/master/LICENSE SSH-MitM 2.0.0 – Licence change to GPLv3
> https://news.ycombinator.com/item?id=30878630

https://www.caffeinatedwonders.com/2022/03/28/new-ssh-server/
> https://news.ycombinator.com/item?id=30830749

https://blog.cloudflare.com/ssh-command-logging/

https://github.com/ndbeals/winssh-pageant

https://xy2.dev/posts/ssh-productive/
> https://news.ycombinator.com/item?id=30505583

https://www.openssh.com/txt/release-8.9
> https://news.ycombinator.com/item?id=30513246

https://www.openssh.com/releasenotes.html
> https://lobste.rs/s/vej7dz/openssh_8_9_released

https://github.com/ilikejam/csshi ClusterSSH utility (like cssh) for iTerm2
> https://news.ycombinator.com/item?id=30364682

https://orth.uk/ssh-over-cloudflare/
> https://news.ycombinator.com/item?id=30283987

https://github.com/hauleth/ssh_signature

https://marcusedmondson.com/2022/01/28/pivoting-with-ssh-tunnels-and-plink/

https://www.journalduhacker.net/s/hwiuio/emmerdez_les_pirates_ssh_avec_endlessh

https://goteleport.com/blog/security-hardening-ssh-bastion-best-practices/
> https://news.ycombinator.com/item?id=29924053

https://twitter.com/antonmedv/status/1480978991309807616 Use StrictHostKeyChecking=“accept-new” instead of “no”
> https://news.ycombinator.com/item?id=29896287
> > https://stackoverflow.com/questions/21383806/how-can-i-force-ssh-to-accept-a-new-host-fingerprint-from-the-command-line/61946687#61946687
> > https://askubuntu.com/questions/123072/ssh-automatically-accept-keys

https://www.openssh.com/agent-restrict.html
> https://news.ycombinator.com/item?id=29865876

https://lwn.net/SubscriberLink/880458/5c4147ec8a7ca8df/ Restricting SSH agent keys
> https://news.ycombinator.com/item?id=29816508

https://goteleport.com/blog/5-ssh-best-practices/
> https://news.ycombinator.com/item?id=29812819

https://tinyssh.org/
> https://news.ycombinator.com/item?id=29661170

https://github.com/AkselAllas/airgapt (Bash, Docker) Automatic proxy setup for SSH'able boxes that have no network access
> https://news.ycombinator.com/item?id=29429369
> > https://github.com/ovh/the-bastion Perl

https://www.agwa.name/blog/post/ssh_signatures
> https://news.ycombinator.com/item?id=29208518

https://disknotifier.com/blog/simple-ssh-security/
> https://news.ycombinator.com/item?id=29153223

https://infosec.mozilla.org/guidelines/openssh
> https://news.ycombinator.com/item?id=29156683

https://console.dev/articles/ssh-alternatives-for-mobile-low-latency-unreliable-connections/
> https://news.ycombinator.com/item?id=29081008

https://mobaxterm.mobatek.net/
> https://news.ycombinator.com/item?id=29001665

https://www.linuxjournal.com/content/putty-scripted-passwords-are-exposed-passwords

https://github.com/opsdisk/the_cyber_plumbers_handbook
> https://news.ycombinator.com/item?id=28728494

https://www.openssh.com/releasenotes.html

https://encryp.ch/blog/cloudflare-abuses-22-tcp/
> https://news.ycombinator.com/item?id=28651598

https://github.com/google/hiba
> https://news.ycombinator.com/item?id=28638750

https://goteleport.com/blog/ssh-vs-kubectl/#.XzRIRZyYc6g.hackernews

https://gist.github.com/koobs/e01cf8869484a095605404cd0051eb11 FreeBSD SSH Hardening
> https://news.ycombinator.com/item?id=28537098

https://undeadly.org/cgi?action=article;sid=20210830113413 RSA/SHA1 signature type disabled by default in OpenSSH

https://github.com/cy384/ssheven SSH client for Mac OS 7/8/9.
> https://news.ycombinator.com/item?id=28021434

https://people.eecs.berkeley.edu/~daw/papers/ssh-use01.pdf Timing Analysis of Keystrokes and Timing Attacks on SSH

https://security.humanativaspa.it/openssh-ssh-agent-shielded-private-key-extraction-x86_64-linux/

https://github.blog/2021-05-10-security-keys-supported-ssh-git-operations/
> https://news.ycombinator.com/item?id=27204695

https://lists.tartarus.org/pipermail/putty-announce/2021/000031.html
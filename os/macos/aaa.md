https://news.ycombinator.com/item?id=26513528 Sensible macOS Defaults

https://www.tecklyfe.com/disable-netbios-macos-os-x/

     brew deps --tree --installed

https://news.ycombinator.com/item?id=26435783 .DS_Store

https://github.com/serhii-londar/open-source-mac-os-apps

# Config
https://endoflife.date/macos

https://eclecticlight.co/2023/07/29/system-settings-that-arent-in-system-settings/
> https://news.ycombinator.com/item?id=36981580

http://apple.stackexchange.com/questions/98782/i-cant-find-a-setting-to-disable-wins-in-network-settings
     sudo launchctl unload -w /System/Library/LaunchDaemons/com.apple.netbiosd.plist

http://osxdaily.com/2007/03/22/how-to-completely-disable-spotlight/

http://recomhub.com/blog/how-to-disable-or-enable-spotlight-in-mac-os-x-yosemite-mavericks-mountain-lion/ave

http://developingandmac.blogspot.com.es/2015/02/no-mouse.html

https://apple.stackexchange.com/questions/259093/can-touch-id-for-the-mac-touch-bar-authenticate-sudo-users-and-admin-privileges/306324#306324

https://eclecticlight.co/2021/06/13/last-week-on-my-mac-the-elephant-at-wwdc/
> https://news.ycombinator.com/item?id=27492268

https://bryce.co/xcode-vim-map/

https://support.apple.com/guide/security/sec469d47bd8/web
> https://apple.stackexchange.com/questions/329532/where-does-gatekeeper-xprotect-log-to
> https://eclecticlight.co/2020/10/27/xprotect-what-do-we-know-about-it/
> https://www.sentinelone.com/blog/apples-malware-removal-mrt-tool-update/
> https://www.reddit.com/r/macsysadmin/comments/sznw8u/xprotect_logs_on_monterey/
> https://nixhacker.com/security-protection-in-macos-2/

https://www.karltarvas.com/2020/10/25/macos-app-sandboxing-via-sandbox-exec.html
> https://news.ycombinator.com/item?id=31973232

https://www.puredarwin.org/
> https://news.ycombinator.com/item?id=31943198

https://heronsperch.blogspot.com/2023/03/compatibility-project-almost-complete.html gnustep
> https://news.ycombinator.com/item?id=35311293

# Security
https://lapcatsoftware.com/articles/2023/6/1.html
> https://news.ycombinator.com/item?id=37103188

https://support.apple.com/guide/security/sec469d47bd8/web

* Who talk to me
    nettop -ln
    sudo lsof -i -P
    sudo lsof -i -P | grep LISTEN | grep :$PORT

* Filter on loop back - port:63342 - IDE Jetbrains IDEA web server
     (sudo pfctl -sr 2>/dev/null; echo "block drop quick on all proto tcp from any to any port = 49806") | sudo pfctl -e -f - 2>/dev/null

* List PF filter rules
    sudo pfctl -sr 2>/dev/null

    sudo pfctl -vnf /etc/pf.conf

* Turn Wi-Fi Off via Command Line in Mac OS X
    networksetup -setairportpower airport off
    networksetup -setairportpower en0 off

/System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport -I
AirPort: Off

networksetup -listnetworkserviceorder

networksetup -removenetworkservice

https://gist.github.com/albertbori/1798d88a93175b9da00b
> https://github.com/bouzou4/osx-eth-wifi-toggle

sudo networksetup -removenetworkservice Wi-Fi

sudo networksetup -removenetworkservice "Bluetooth PAN"

* What starts
sudo launchctl list | sed 1d | awk ' !/0x|apple|com\.vix|edu\.|org\./ { print $3 } '

ls /Library/LaunchDaemons

* print cupsd
https://discussions.apple.com/thread/2078738

https://stackoverflow.com/questions/5510563/how-to-start-syslogd-server-on-mac-to-accept-remote-logging-messages

pkill airportd airPlayXPCHelpe WifiAgent WirelessRadioMa mobileassetd iCltcp4 adpudp4 airudp6 ituudp4 Calendar PerfPowerServic Perudp4 WeatherWidget pluudp6 sharingd bluetoothd Useudp4 shaudp4 amsengagementd

/SpeechSynthesis.framework

https://superuser.com/questions/962917/is-it-safe-to-manually-delete-frameworks-of-unused-programs-from-the-mac-os-x-l
> https://www.mothersruin.com/software/SuspiciousPackage/

parsecd api.smoot.apple.com bag-smoot.v.aaplimg.com 3.73.166.250

https://blog.neilsabol.site/post/quickly-easily-adding-pf-packet-filter-firewall-rules-macos-osx/

https://murusfirewall.com/Documentation/OS%20X%20PF%20Manual.pdf

https://manjusri.ucsc.edu/2015/03/10/PF-on-Mac-OS-X/

https://news.ycombinator.com/item?id=38404792

example for ipv6 IP ranges filter:

block from any to { 2a00:1288:1:1:1:1:1:1/31 }
block from any to { 2a00:1450:4007:1:1:1:1:1/21 }

interface: idx-XX

* /System/Library/PrivateFrameworks/

https://stackoverflow.com/questions/2678047/what-are-private-frameworks-and-how-will-we-use-them

https://stackoverflow.com/questions/65089767/class-amsupporturlconnectiondelegate-is-implemented-in-both
> sudo xcode-select -r

https://discussions.apple.com/thread/7271850?sortBy=best

https://blog.bejarano.io/hardening-macos/
> https://news.ycombinator.com/item?id=27067755
> https://news.ycombinator.com/item?id=31864974
> > https://github.com/jamf/CIS-for-macOS-Catalina-CP

https://apple.stackexchange.com/questions/268512/how-to-setup-the-adaptive-firewall

https://www.netify.ai/resources/applications/apple-updates

https://github.com/drduh/macOS-Security-and-Privacy-Guide

https://objective-see.com/products/knockknock.html

https://objective-see.com/products/lulu.html little snitch alt

https://it.digitaino.com/use-touchid-to-authenticate-sudo-on-macos/
> https://news.ycombinator.com/item?id=32611340

https://www.mandiant.com/resources/blog/reviewing-macos-unified-logs

https://objective-see.org/tools.html
> https://news.ycombinator.com/item?id=32979796

https://hynek.me/articles/macos-dyld-env/
> https://news.ycombinator.com/item?id=34309530

https://krypted.com/mac-os-x/free-space-required-for-modern-macos-upgrades/

https://dortania.github.io/OpenCore-Legacy-Patcher/
> https://news.ycombinator.com/item?id=35538223

https://sveinbjorn.org/sloth lsof

https://www.tokyodev.com/articles/not-setting-up-find-my-bricked-my-macbook
> https://news.ycombinator.com/item?id=37865941

# Dev
https://news.ycombinator.com/item?id=37333404 vm

https://news.ycombinator.com/item?id=36658553

https://news.ycombinator.com/item?id=35525047

https://github.com/shapehq/tartelet github

https://rambo.codes/posts/2021-01-08-distributing-mac-apps-outside-the-app-store
> https://news.ycombinator.com/item?id=34379156

https://lapcatsoftware.com/articles/xcrun.html

https://developer.apple.com/documentation/xcode-release-notes/xcode-14_1-release-notes

https://www.macstrategy.com/article.php?283
> https://news.ycombinator.com/item?id=33416099

https://it.digitaino.com/use-touchid-to-authenticate-sudo-on-macos/

https://github.com/openglonmetal/MGL
> https://news.ycombinator.com/item?id=33383075

https://refruity.xyz/macbook-touch-bar-in-iterm2/

https://thescottkrause.com/emerging_tech/new_macbook_setup_for_dev/

https://developer.apple.com/documentation/extensionkit
> https://news.ycombinator.com/item?id=33409558

https://www.theverge.com/2021/6/8/22523613/macos-monterey-wwdc-apple-ipad
> https://news.ycombinator.com/item?id=27451413

https://cornerbit.tech/a-few-useful-xcode-debugging-tricks/
> https://news.ycombinator.com/item?id=28207810

https://eisel.me/devtool-allocators
> https://news.ycombinator.com/item?id=29068828

https://www.cdfinder.de/guide/blog/apple_hell.html
> https://news.ycombinator.com/item?id=26993857

https://developer.apple.com/documentation/macos-release-notes/macos-12_3-release-notes#Python
> https://news.ycombinator.com/item?id=30115214

https://developer.apple.com/support/unlisted-app-distribution/

https://news.ycombinator.com/item?id=30753584

https://www.a11yproject.com/posts/macos-browser-keyboard-navigation/

https://jdeploy.substack.com/p/apples-code-signing-quagmire?s=w

https://github.com/mikeroyal/Apple-Silicon-Guide

https://github.com/hjuutilainen/sus-inspector

https://developer.apple.com/xcode-cloud/
> https://news.ycombinator.com/item?id=32655347

https://github.com/sebsto/xcodeinstall

https://news.ycombinator.com/item?id=32971599 Ask HN: Xcode users – how do you make it more usable?

https://oleb.net/2022/xcode-14-mac-concurrency-bugs/
> https://news.ycombinator.com/item?id=33187858

https://jvns.ca/blog/2018/01/28/mac-freeze/

# VM
https://news.ycombinator.com/item?id=39059100

https://eclecticlight.co/2024/01/11/how-virtualisation-came-to-apple-silicon-macs/
> https://news.ycombinator.com/item?id=38958266

https://eclecticlight.co/2023/12/29/why-are-apple-silicon-vms-so-different/
> https://news.ycombinator.com/item?id=38803556

https://eclecticlight.co/2023/08/17/run-a-macos-vm-on-apple-silicon-from-a-double-click-with-vimy/
> https://news.ycombinator.com/item?id=37200909

https://news.ycombinator.com/item?id=36889092

https://github.com/utmapp/UTM/releases/tag/v4.1.5

https://eclecticlight.co/2022/12/28/macos-virtualisation-refactored-and-sandboxed-in-viable-updates/
> https://news.ycombinator.com/item?id=34161272

https://weblog.antranigv.am/posts/2022/11/running-arm64-aarch64-freebsd-on-qemu-utm-app-on-apple-silicon/
> https://news.ycombinator.com/item?id=33679818

https://developer.apple.com/documentation/virtualization/running_gui_linux_in_a_virtual_machine_on_a_mac
> https://news.ycombinator.com/item?id=36184400
> https://news.ycombinator.com/item?id=33143016

https://github.com/foxlet/macOS-Simple-KVM

https://github.com/kholia/OSX-KVM
> https://news.ycombinator.com/item?id=29426862

https://developer.apple.com/documentation/virtualization/running_intel_binaries_in_linux_vms_with_rosetta
> https://news.ycombinator.com/item?id=31645140

https://threedots.ovh/blog/2022/06/quick-look-at-rosetta-on-linux/
> https://news.ycombinator.com/item?id=31662978

https://worthdoingbadly.com/hv/
> https://news.ycombinator.com/item?id=31638173

https://dougallj.wordpress.com/2022/11/09/why-is-rosetta-2-fast/
> https://news.ycombinator.com/item?id=33533132

https://bytecellar.com/2022/11/16/a-secret-apple-silicon-extension-to-accommodate-an-intel-8080-artifact/
> https://news.ycombinator.com/item?id=33635720

#
https://github.com/below/HelloSilicon introduction to ARM64 assembly on Apple Silicon Macs
> https://news.ycombinator.com/item?id=34128776

# M3
https://news.ycombinator.com/item?id=38884741

https://news.ycombinator.com/item?id=38214806

https://news.ycombinator.com/item?id=38125771

# M2
https://www.phoronix.com/news/Apple-M2-Device-Tree-Linux-6.4
> https://news.ycombinator.com/item?id=35470392

https://news.ycombinator.com/item?id=34629461

https://www.ifixit.com/News/71442/tearing-down-the-14-macbook-pro-with-apples-help
> https://news.ycombinator.com/item?id=34565006

https://www.apple.com/newsroom/2023/01/apple-unveils-macbook-pro-featuring-m2-pro-and-m2-max/
> https://news.ycombinator.com/item?id=34412610

https://www.jeffgeerling.com/blog/2022/limiting-handbrake-threads-prevent-throttling-on-m2-macbook-air
> https://news.ycombinator.com/item?id=34058609

https://www.macworld.com/article/819644/m2-macbook-air-usb-c-67w-35w-dual-compact-charger.html

https://www.techpowerup.com/298936/report-apple-to-move-a-part-of-its-embedded-cores-to-risc-v-stepping-away-from-arm-isa
> https://news.ycombinator.com/item?id=32874189

https://www.theregister.com/2022/07/21/m2_macbook_air_teardown/

https://semianalysis.substack.com/p/apple-m2-die-shot-and-architecture?s=r
> https://news.ycombinator.com/item?id=31689366

https://eclecticlight.co/2022/06/09/when-will-apple-ship-other-m2-macs/
> https://news.ycombinator.com/item?id=31678464

https://www.apple.com/newsroom/2022/06/apple-unveils-m2-with-breakthrough-performance-and-capabilities/
> https://news.ycombinator.com/item?id=31644008
> https://news.ycombinator.com/item?id=31643610

# M1
https://news.ycombinator.com/item?id=34456047

https://daniel.haxx.se/blog/2022/12/30/an-m1-for-curl/
> https://news.ycombinator.com/item?id=34183020

https://github.com/tpwrules/nixos-m1
> https://news.ycombinator.com/item?id=34134109

https://news.ycombinator.com/item?id=33405359 Ask HN: How to intentionally throttle CPU on a M1 MacBook?

https://www.sevarg.net/2021/01/09/arm-mac-mini-and-boinc/

https://www.corsix.org/content/contrasting-intel-amx-and-apple-amx

https://github.com/corsix/amx
> https://news.ycombinator.com/item?id=32722510

https://amarioguy.github.io/m1windowsproject/
> https://news.ycombinator.com/item?id=31657591

https://eclecticlight.co/2022/04/25/how-macos-manages-m1-cpu-cores/
> https://news.ycombinator.com/item?id=31151393

https://eclecticlight.co/2022/03/17/macos-has-different-strategies-for-m1-cores/

https://github.com/AsahiLinux/docs/wiki/Introduction-to-Apple-Silicon

https://mondaynote.com/apple-m1-ultra-meanings-and-consequences-fc32616f4a66
> https://news.ycombinator.com/item?id=30672500

https://cfarm.tetaneutral.net/news/38# New M1 machine running Linux natively: gcc103

https://www.apple.com/newsroom/2022/03/apple-unveils-m1-ultra-the-worlds-most-powerful-chip-for-a-personal-computer/
> https://news.ycombinator.com/item?id=30604470

https://twitter.com/marcan42/status/1494716035165220872 recovery

https://twitter.com/marcan42/status/1494213855387734019
> https://news.ycombinator.com/item?id=30370551

https://eclecticlight.co/2022/02/07/when-an-m1-mac-mini-is-faster-than-an-m1-pro-contention-and-core-allocation/
> https://news.ycombinator.com/item?id=30242509

https://eclecticlight.co/2022/01/03/power-frequency-management-how-m1-e-cores-win/
> https://news.ycombinator.com/item?id=29778990

https://rosenzweig.io/blog/asahi-gpu-part-2.html
> https://news.ycombinator.com/item?id=25873887

https://eclecticlight.co/2021/12/29/how-secure-boot-works-on-m1-series-macs/

https://unum.cloud/post/2021-12-21-macbook/
> https://news.ycombinator.com/item?id=29670624

https://twitter.com/VadimYuryev/status/1466526403331952644
> https://news.ycombinator.com/item?id=29427316

https://calcagno.blog/m1dev/

https://www.anandtech.com/show/17024/apple-m1-max-performance-review
> https://news.ycombinator.com/item?id=28987276

https://www.anandtech.com/show/16983/the-apple-a15-soc-performance-review-faster-more-efficient/
> https://news.ycombinator.com/item?id=28747182

https://drive.google.com/file/d/1WrMYCZMnhsGP4o3H33ioAUKL_bjuJSPt/view M1 Exploration - v 0.70

https://twitter.com/alyssarzg/status/1432927311058194436
> https://news.ycombinator.com/item?id=28377561

https://eclecticlight.co/2021/09/01/m1-icestorm-cores-can-still-perform-very-well/
> https://news.ycombinator.com/item?id=28377401

https://wiki.netbsd.org/ports/evbarm/apple/

https://www.anaconda.com/blog/apple-silicon-transition

https://alinpanaitiu.com/blog/journey-to-ddc-on-m1-macs/
> https://lobste.rs/s/2zajeu/journey_controlling_external_monitors

https://eclecticlight.co/2021/07/18/last-week-on-my-mac-the-perils-of-m1-ownership/
> https://news.ycombinator.com/item?id=27874600

https://blog.jae.fi/apple-m1-three-months-later/
> https://lobste.rs/s/vqny0j/apple_m1_three_months_later

https://eclecticlight.co/2021/04/22/can-you-trust-floating-point-arithmetic-on-apple-silicon/

https://developer.apple.com/metal/tensorflow-plugin/
> https://news.ycombinator.com/item?id=27442475

https://www.jeffgeerling.com/blog/2021/apple-m1-compiles-linux-30-faster-my-intel-i9

https://www.willusher.io/graphics/2020/12/20/rt-dive-m1
> https://news.ycombinator.com/item?id=27340555

https://blogs.blackberry.com/en/2021/05/strong-arming-with-macos-adventures-in-cross-platform-emulation

https://ridiculousfish.com/blog/posts/benchmarking-libdivide-m1-avx512.html
> https://news.ycombinator.com/item?id=27133804

https://blog.svenpeter.dev/posts/m1_sprr_gxf/

https://rosenzweig.io/blog/asahi-gpu-part-4.html
> https://news.ycombinator.com/item?id=27019249

https://blogs.vmware.com/teamfusion/2021/04/fusion-on-apple-silicon-progress-update.html
> https://news.ycombinator.com/item?id=27011197

https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/commit/?id=0c855563182001c829065faa17f8e29e9ceffe13
> https://news.ycombinator.com/item?id=26952433

https://www.apple.com/newsroom/2021/04/imac-features-all-new-design-in-vibrant-colors-m1-chip-and-45k-retina-display/
> https://news.ycombinator.com/item?id=26877806

https://authzed.com/blog/onboarding-with-an-m1/
> https://news.ycombinator.com/item?id=26843228

# Apple
https://www.wired.com/story/plaintext-apple-secret-40-year-old-mac-still-rules/

https://news.ycombinator.com/item?id=38773037

https://www.theregister.com/2023/12/18/beeper_blocked_imessage_whacamole_continues/

https://news.ycombinator.com/item?id=38689137

https://www.theverge.com/23743095/apple-watch-band-release-x206-assembly-button-of-the-month
> https://news.ycombinator.com/item?id=36140128

https://eclecticlight.co/2022/04/18/m1-thunderbolt-ports-dont-fully-support-usb-3-1-gen-2/
> https://news.ycombinator.com/item?id=31068479

https://sixcolors.com/post/2022/02/apple-in-2021-the-six-colors-report-card/
> https://news.ycombinator.com/item?id=30248161

https://developer.apple.com/news/?id=mdkbobfo Account deletion within apps required starting January 31
> https://news.ycombinator.com/item?id=28776960

https://thenougatmachine.wordpress.com/2022/03/23/an-apple-original-on-dvd-the-definitive-unboxing-and-ux-review/
> https://news.ycombinator.com/item?id=30809226

# News
https://www.bluecataudio.com/Blog/preview/realtime-audio-multicore-issues-for-apple-silicon-end-of-the-story/

https://github.com/koekeishiya/yabai
> https://news.ycombinator.com/item?id=38473942

https://news.ycombinator.com/item?id=38421862

https://fabiensanglard.net/xdr/index.html
> https://news.ycombinator.com/item?id=38402092

https://news.ycombinator.com/item?id=38179773

https://news.ycombinator.com/item?id=38179780

https://www.macrumors.com/2023/11/10/8gb-ram-in-m3-macbook-pro-proves-the-bottleneck/
> https://news.ycombinator.com/item?id=38220942

https://www.latimes.com/business/technology/story/2023-10-27/apple-watches-violate-patents-held-by-orange-county-tech-company-us-international-trade-commission-finds
> https://news.ycombinator.com/item?id=38059668

https://arstechnica.com/gadgets/2023/07/with-macos-sonoma-intel-macs-are-still-getting-fewer-updates-than-they-used-to/

https://mastodon.social/@stroughtonsmith/110708615280659758

https://blog.xpnsec.com/building-a-mach-o-memory-loader-part-1/

https://lna7n.org/2021/04/16/a-survival-guide-to-macos-from-linux.html

https://old.reddit.com/r/apple/comments/110dozc/there_is_something_wrong_with_the_mouse_cursor/
> https://news.ycombinator.com/item?id=35689540

https://www.macrumors.com/2023/04/14/15-inch-macbook-air-m2-like-chip-logs/

https://appleinsider.com/articles/23/02/14/apple-issues-firmware-update-for-magsafe-3-charging-cable

https://notes.alinpanaitiu.com/Making%20macOS%20apps%20uninstallable
> https://news.ycombinator.com/item?id=34841742

https://news.ycombinator.com/item?id=34650452

https://medium.com/@aplaceofmind/ventura-is-not-macos-its-macios-1d00f12fa01e
> https://news.ycombinator.com/item?id=34575553

https://arstechnica.com/gadgets/2023/01/entry-level-m2-pro-macbook-pros-have-slower-ssd-performance-than-m1-versions/
> https://news.ycombinator.com/item?id=34522979

https://twitter.com/danqing_liu/status/1614308997653499905

https://blog.metaobject.com/2023/01/setting-bozo-bit-on-apple.html
> https://news.ycombinator.com/item?id=34371438

https://www.theverge.com/2023/1/10/23549429/microled-apple-watch-rumor-custom-design-samsung

https://nyansatan.github.io/lightning/
> https://news.ycombinator.com/item?id=34158318

https://github.com/rui314/mold/releases/tag/v1.8.0 Mold linker: targeting macOS/iOS now requires a commercial license
> https://news.ycombinator.com/item?id=34141912
> https://news.ycombinator.com/item?id=34382908

https://www.andrewheiss.com/blog/2016/02/10/libreoffice-base-sqlite-odbc-osx/

https://www.apple.com/newsroom/2022/10/macos-ventura-is-now-available/
> https://news.ycombinator.com/item?id=33319367

https://github.com/macbian-linux/macos-subsystem-for-linux
> https://news.ycombinator.com/item?id=32893237

https://github.com/AkihiroSuda/lima/tree/master Lima: Linux-on-Mac ("macOS subsystem for Linux", "containerd for Mac")
> https://news.ycombinator.com/item?id=27151993
> > https://code.visualstudio.com/docs/remote/remote-overview
> > https://www.maconlinux.net/

https://www.quora.com/Retrocomputing-Did-Apple-need-to-license-Xerox-PARCs-GUI-technology-after-their-visit-in-December-1979-or-was-it-just-copied

https://konradybcio.pl/linuxona7/
> https://news.ycombinator.com/item?id=31679293

https://github.com/insidegui/VirtualBuddy Virtualize macOS 12 and later on Apple Silicon, experimental
> https://news.ycombinator.com/item?id=31878876

# Port
https://dortania.github.io/OpenCore-Legacy-Patcher/MODELS.html

# News
https://www.macworld.com/article/2130071/m3-macbook-pro-8gb-memory-too-little.html
> https://news.ycombinator.com/item?id=38215413

https://github.com/AsahiLinux/docs/wiki/macOS-Sonoma-Boot-Failures
> https://news.ycombinator.com/item?id=38089342

https://www.apple.com/newsroom/2023/09/macos-sonoma-is-available-today/
> https://news.ycombinator.com/item?id=37662510

https://news.ycombinator.com/item?id=37333077 vm

https://amitp.blogspot.com/2023/04/mac-keyboard-with-hidutil.html

https://weblog.antranigv.am/posts/2023/02/hardcoded-folder-icons-in-macos/
> https://news.ycombinator.com/item?id=34709690

https://tidbits.com/2023/01/11/iphones-and-ipads-now-require-a-passcode-on-every-backup-sync/
> https://news.ycombinator.com/item?id=34463677
> > https://theevilbit.github.io/posts/cve-2022-32929/

https://www.gimp.org/news/2022/12/02/gimp-2.10.32-apple-silicon/
> https://news.ycombinator.com/item?id=34392193

https://512pixels.net/2022/12/whats-left-in-the-apple-silicon-transition/
> https://news.ycombinator.com/item?id=34189661

https://morrick.me/archives/9696 Mac OS Ventura Issues
> https://news.ycombinator.com/item?id=34199652

https://eclecticlight.co/2022/11/30/an-a-to-z-of-keys-and-keyboards-startup-and-login/
> https://news.ycombinator.com/item?id=33814682

https://lifehacker.com/your-mac-has-a-hidden-white-noise-generator-1849760988
> https://news.ycombinator.com/item?id=33534478

https://www.bloomberg.com/news/newsletters/2022-10-23/should-i-buy-the-new-ipad-pro-what-s-new-about-apple-s-base-model-ipad-l9lejqfk

https://hacks.mozilla.org/2022/10/improving-firefox-responsiveness-on-macos/
> https://news.ycombinator.com/item?id=33152472

 smartctl

https://news.ycombinator.com/item?id=33024863 Ask HN: Has the Apple Silicon excessive disk read/write issue been fixed?

https://applewatchrunner.substack.com/p/apple-watch-running-review
> https://news.ycombinator.com/item?id=32971085

https://browser.geekbench.com/v5/cpu/17124579 Apple A16 Geekbench

https://twitter.com/nikitonsky/status/1557357661171204098 Weird stuff found in redesigned macOS Ventura System Settings app
> https://news.ycombinator.com/item?id=32445737

https://lapcatsoftware.com/articles/VenturaShare.html
> https://news.ycombinator.com/item?id=32401228

https://github.com/ospfranco/sol
> https://news.ycombinator.com/item?id=32402631

https://medium.com/@parttimeben/5-surprising-mac-features-that-i-discovered-recently-e0f288b6e20c

https://www.theverge.com/2022/7/1/23191141/apple-macbook-pro-13-m2-base-model-slow-device

https://github.com/p0deje/Maccy
> https://news.ycombinator.com/item?id=31867121

https://jasonmurray.org/posts/2021/coreaudiod/
> https://news.ycombinator.com/item?id=31842014

https://mjacobson.net/blog/2022-02-throttling.html
> https://news.ycombinator.com/item?id=31788894

https://sal.dev/macos/macos-screenshotting-tips-and-tricks/
> https://news.ycombinator.com/item?id=31769683

https://basicappleguy.com/basicappleblog/settingsapp
> https://news.ycombinator.com/item?id=31715738

https://shadowfacts.net/2022/clarus/
> https://news.ycombinator.com/item?id=31741589

https://mnpn.github.io/blog/airplay-network-disaster
> https://news.ycombinator.com/item?id=31706283

https://www.macrumors.com/2022/06/10/apple-statement-on-stage-manager-m1-ipads/

https://blog.plover.com/2022/06/02/#mac-lock-button

https://lapcatsoftware.com/articles/SystemSettings.html
> https://news.ycombinator.com/item?id=31669950

https://www.apple.com/macos/macos-ventura-preview/

https://mmazzarolo.com/blog/2022-04-16-drag-window-by-clicking-anywhere-on-macos/
> https://news.ycombinator.com/item?id=31273893

https://www.fourth-wall.co.uk/post/10-tips-for-preview-the-default-mac-app-that-people-forget-about
> https://news.ycombinator.com/item?id=31315110

https://eclecticlight.co/2022/04/19/booting-a-mac-studio-from-an-external-ssd-and-what-it-doesnt-solve/
> https://news.ycombinator.com/item?id=31080421

https://www.bloomberg.com/news/articles/2022-04-14/apple-readies-several-new-macs-with-next-generation-m2-chips

https://github.com/rlxone/Equinox Create dynamic wallpapers for macOS

https://eclecticlight.co/2022/04/10/last-week-on-my-mac-why-m1-macs-dont-have-full-support-for-usb-c/

https://github.com/mikeroyal/Apple-Silicon-Guide
> https://news.ycombinator.com/item?id=30912099

https://www.apple.com/newsroom/2022/03/apple-business-essentials-now-available-for-small-businesses/
> https://news.ycombinator.com/item?id=30912973

https://www.jamieonkeys.dev/posts/keyboard-shortcuts/
> https://news.ycombinator.com/item?id=30876934

https://eclecticlight.co/2022/03/31/what-is-triald-and-why-is-it-taking-so-much-disk-space/
> https://news.ycombinator.com/item?id=30864613

https://www.highcaffeinecontent.com/blog/20220325-Intel-Virtualization-and-Apple-Silicon
> https://news.ycombinator.com/item?id=30812855

https://eclecticlight.co/2022/03/20/last-week-on-my-mac-is-look-up-destined-for-csam/
> https://news.ycombinator.com/item?id=30744117

https://www.tomshardware.com/news/mac-studio-dissected-m1-ultra-about-3x-bigger-than-amds-ryzen-cpus
> https://news.ycombinator.com/item?id=30743877

https://www.theverge.com/2022/3/19/22986705/mac-studio-teardown-potentially-upgradeable-ssd-storage-apple

https://eclecticlight.co/2022/03/16/how-good-is-montereys-visual-look-up/
> https://news.ycombinator.com/item?id=30696584

https://daringfireball.net/2022/02/on_the_origin_of_the_iphone

https://alinpanaitiu.com/blog/over-500nits-failed/

https://firt.dev/ios-15.4b Push Notifications, WebXR, and better PWA support coming to iOS
> https://news.ycombinator.com/item?id=30160680

https://www.macrumors.com/2022/01/30/macos-12-2-bluetooth-battery-drain/

https://nova.app/
> https://news.ycombinator.com/item?id=30066298

https://9to5mac.com/2022/01/23/gurman-apple-preparing-to-launch-its-widest-array-of-new-products-ever-this-fall/

https://news.ycombinator.com/item?id=30043764 Ask HN: How to make my macOS less distracting?

https://mjtsai.com/blog/2022/01/12/catching-native-apps/

https://github.com/divar-ir/NetShears Network interceptor framework written in Swift
> https://news.ycombinator.com/item?id=29872786

https://news.ycombinator.com/item?id=29850665 Tell HN: Full macOS reinstall because Apple ID
> https://news.ycombinator.com/item?id=29850665

https://github.com/antimof/UxPlay
> https://news.ycombinator.com/item?id=29837837

https://github.com/ExistentialAudio/BlackHole
> https://news.ycombinator.com/item?id=29621465

https://www.macrumors.com/2021/12/07/apple-ceo-tim-cook-secret-deal-with-china/
> https://news.ycombinator.com/item?id=29482351

https://www.macrumors.com/2021/12/05/apple-planning-five-new-macs-for-2022/

https://merecivilian.com/apple-broke-up-with-me/
> https://news.ycombinator.com/item?id=29446529

https://news.ycombinator.com/item?id=29424245 Interview with Hansen Hsu, engineer at Apple during transition from OS 9 to OS X

https://eclecticlight.co/2021/11/27/explainer-ds_store-files/
> https://news.ycombinator.com/item?id=29358932

https://www.ifixit.com/News/55370/apple-diy-repair-program-parts-tools-guides-software

https://www.apple.com/newsroom/2021/11/apple-announces-self-service-repair/
> https://news.ycombinator.com/item?id=29253047

https://www.macworld.com/article/551393/apple-software-problems-regions-memories-bugs.html
> https://news.ycombinator.com/item?id=29229881

https://eclecticlight.co/2021/11/15/montereys-memory-leak-and-how-to-avoid-it/
> https://news.ycombinator.com/item?id=29227450

https://danpetrov.xyz/macos/2021/11/14/analysing-network-quality-macos.html
> https://news.ycombinator.com/item?id=29225308

https://twitter.com/marcan42/status/1458473546225577987 M1 Pro 14“ MacBook Pro Running KDE Plasma 5 on Arch Linux ARM
> https://news.ycombinator.com/item?id=29197509

https://www.apple.com/business/essentials/
> https://news.ycombinator.com/item?id=29175311

https://news.ycombinator.com/item?id=29079096 brew alt

https://www.corbinstreehouse.com/blog/2021/10/macos-12-monterey-and-user-interface-inconsistencies/
> ttps://news.ycombinator.com/item?id=29073322

https://github.com/waydabber/BetterDummy Custom HiDPI Resolutions

https://www.btaz.com/mac-os-x/find-the-process-listening-to-port-on-mac-os-x/
    ps -Ao user,pid,command | grep -v grep | grep <PID>

https://stackoverflow.com/questions/4421633/who-is-listening-on-a-given-tcp-port-on-mac-os-x
    netstat -anv
    sudo lsof -i -P | grep LISTEN

https://nuxx.net/blog/2021/10/29/network-capture-with-process-name-and-pid-on-macos/

https://eclecticlight.co/2021/10/29/how-macos-is-more-reliable-and-doesnt-need-reinstalling/
> https://news.ycombinator.com/item?id=29052214

https://blog.kaleidoscope.app/2021/10/25/whats-new-in-the-macos-monterey-command-line/

https://blog.yiningkarlli.com/2021/10/takua-on-m1-max.html
> https://news.ycombinator.com/item?id=28994800

https://brew.sh/2021/10/25/homebrew-3.3.0/

https://www.apple.com/newsroom/2021/10/macos-monterey-is-now-available/

https://eclecticlight.co/2021/09/19/last-week-on-my-mac-the-macos-update-problem/

https://fmentzer.github.io/posts/2020/dictionary/
> https://news.ycombinator.com/item?id=28505406

https://git.sr.ht/~habibalamin/Commandeer
> https://lobste.rs/s/vspo8i/commandeer_remap_command_escape_when

http://blog.ret2.io/2021/07/21/wtf-snapshot-fuzzing/
> https://news.ycombinator.com/item?id=27914379

https://9to5mac.com/2021/07/23/exclusive-apple-testing-new-external-display-with-a-dedicated-a13-chip-and-neural-engine/

https://www.barebones.com/products/bbedit/bbedit14.html
> https://news.ycombinator.com/item?id=27905644

https://sixcolors.com/post/2021/07/first-look-macos-monterey-public-beta/
> https://news.ycombinator.com/item?id=27707770

https://www.jessesquires.com/blog/2021/06/29/apple-docc-great-but-useless-for-oss/
> https://news.ycombinator.com/item?id=27686069

http://karolis.koncevicius.lt/posts/cleaning_home_on_macos/

https://developer.apple.com/forums/thread/681907 PHP has been removed in macOS Monterey
> https://news.ycombinator.com/item?id=27537040

https://taoofmac.com/space/blog/2021/06/05/1100 The Big Sur kernel_task Troubleshooting Saga

https://appleinsider.com/articles/21/05/24/apples-moves-point-to-a-future-with-no-bootable-backups-says-developer

https://9to5mac.com/2021/05/18/40-core-mac-pro-high-end-mac-mini-in-development/
> https://news.ycombinator.com/item?id=27194476
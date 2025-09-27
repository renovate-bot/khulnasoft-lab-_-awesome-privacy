<p align="center" id="top"><a href="https://github.com/Lissy93/awesome-privacy"><img src="https://i.ibb.co/80Y5x2T/Awesome-Privacy.png" /></a></p>
<p align="center">🌐 <b><a href="https://awesome-privacy.xyz">awesome-privacy.xyz</a></b></p>
<p align="center"><i>A curated list of privacy & security-focused apps, software, and providers</i> 🔐</p>

[⏬ Skip to Content ⏬](#password-managers)

## Intro [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Large data-hungry corporations dominate the digital world but with little, or no respect for your privacy.
Migrating to open-source applications with a strong emphasis on privacy and security will help stop
corporations, governments, and hackers from logging, storing or selling your personal data.

**Note**: Remember that [no software is perfect](#important-considerations), and it is important to follow good [security practices](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/CHECKLIST.md)<br>
**Mirror**: This repo is mirrored to [https://codeberg.org/alicia/awesome-privacy](https://codeberg.org/alicia/awesome-privacy)<br>
**Repo Admin**: [Website Docs](#the-website) | [Contributing](#contributing) | [Acknowledgment](#acknowledgements) | [License](#license)

<!-- awesome-privacy-start -->
<details>
<summary><h2>Contents</h2></summary>

- **Essentials**
	- [Password Managers](#password-managers) (5)
	- [2-Factor Authentication](#2-factor-authentication) (8)
	- [File Encryption](#file-encryption) (3)
	- [Browsers](#browsers) (5)
	- [Search Engines](#search-engines) (4)
- **Communication**
	- [Encrypted Messaging](#encrypted-messaging) (4)
	- [P2P Messaging](#p2p-messaging) (5)
	- [Encrypted Email](#encrypted-email) (5)
	- [Email Clients](#email-clients) (6)
	- [Mail Forwarding](#mail-forwarding) (6)
	- [Email Security Tools](#email-security-tools) (3)
	- [VOIP Clients](#voip-clients) (2)
	- [Virtual Phone Numbers](#virtual-phone-numbers) (4)
	- [Team Collaboration](#team-collaboration) (5)
- **Security Tools**
	- [Browser Extensions](#browser-extensions) (27)
	- [Mobile Apps](#mobile-apps) (25)
	- [Online Tools](#online-tools) (18)
- **Networking**
	- [Virtual Private Networks](#virtual-private-networks) (5)
	- [Self-Hosted Network Security](#self-hosted-network-security) (8)
	- [Mix Networks](#mix-networks) (3)
	- [Proxies](#proxies) (2)
	- [DNS Providers](#dns-providers) (3)
	- [DNS Clients](#dns-clients) (6)
	- [Firewalls](#firewalls) (14)
	- [Ad Blockers](#ad-blockers) (9)
	- [Host Block Lists](#host-block-lists) (6)
	- [Router Firmware](#router-firmware) (2)
	- [Network Analysis](#network-analysis) (4)
	- [Intrusion Detection](#intrusion-detection) (5)
	- [Cloud Hosting](#cloud-hosting) (3)
	- [Domain Registrars](#domain-registrars) (2)
	- [DNS Hosting](#dns-hosting) (1)
	- [Mail Servers](#mail-servers) (2)
- **Productivity**
	- [Digital Notes](#digital-notes) (8)
	- [Calendar](#calendar) (0)
	- [Backup and Sync](#backup-and-sync) (3)
	- [Cloud Productivity Suites](#cloud-productivity-suites) (6)
	- [Encrypted Cloud Storage](#encrypted-cloud-storage) (7)
	- [File Drop](#file-drop) (3)
	- [Browser Sync](#browser-sync) (5)
	- [Secure Conference Calls](#secure-conference-calls) (2)
- **Utilities**
	- [Virtual Machines](#virtual-machines) (3)
	- [PGP Managers](#pgp-managers) (9)
	- [Metadata Removal](#metadata-removal) (3)
	- [Data Erasers](#data-erasers) (9)
- **Operating Systems**
	- [Mobile Operating Systems](#mobile-operating-systems) (4)
	- [Desktop Operating Systems](#desktop-operating-systems) (6)
	- [Linux Defenses](#linux-defenses) (6)
	- [Windows Defences](#windows-defences) (22)
	- [Mac OS Defences](#mac-os-defences) (3)
	- [Anti-Malware](#anti-malware) (2)
- **Development**
	- [Code Hosting](#code-hosting) (5)
	- [IDEs](#ides) (0)
	- [Terminal Emulators](#terminal-emulators) (0)
- **Smart Home & IoT**
	- [Voice Assistants](#voice-assistants) (2)
	- [Smart Home](#smart-home) (0)
- **Finance**
	- [Cryptocurrencies](#cryptocurrencies) (2)
	- [Crypto Wallets](#crypto-wallets) (9)
	- [Crypto Exchanges](#crypto-exchanges) (4)
	- [Virtual Credit Cards](#virtual-credit-cards) (3)
	- [Other Payment Methods](#other-payment-methods) (3)
	- [Secure Budgeting](#secure-budgeting) (3)
- **Social**
	- [Social Networks](#social-networks) (4)
	- [Video Platforms](#video-platforms) (3)
	- [Blogging Platforms](#blogging-platforms) (5)
	- [News Readers](#news-readers) (3)
	- [Proxy Sites](#proxy-sites) (4)
- **Media**
	- [Gaming](#gaming) (0)
	- [Media Servers](#media-servers) (0)
	- [Music Players](#music-players) (0)
	- [Video Players](#video-players) (0)
	- [Photo Viewers](#photo-viewers) (0)
	- [E-Book Readers](#e-book-readers) (0)
	- [Podcast Players](#podcast-players) (0)
	- [Torrent Downloaders](#torrent-downloaders) (0)
	- [File Converters](#file-converters) (0)
- **Creativity**
	- [Image Editors](#image-editors) (0)
	- [Video Editors](#video-editors) (0)
	- [Audio Editors & Recorders](#audio-editors--recorders) (0)
	- [Casting & Streaming](#casting--streaming) (0)
	- [Screenshot Tools](#screenshot-tools) (0)
	- [3D Graphics](#3d-graphics) (0)
	- [Animation](#animation) (0)
</details>

## Essentials

### Password Managers

- **[<img src='https://icon.horse/icon/bitwarden.com' width='16' height='16' alt='icon' /> Bitwarden](https://bitwarden.com)** - Fully-featured, open source password manager with cloud-sync. Bitwarden is
easy-to-use with a clean UI and client apps for desktop, web and mobile. See
also [Vaultwarden](https://github.com/dani-garcia/vaultwarden), a self-hosted,
Rust implementation of the Bitwarden server and compatible with [upstream
Bitwarden clients](https://bitwarden.com/download/).
 	- [![GitHub: bitwarden/server](https://img.shields.io/github/stars/bitwarden/server?style=flat&logo=github&label=server&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/bitwarden/server)
- **[<img src='https://icon.horse/icon/keepass.info' width='16' height='16' alt='icon' /> KeePass](https://keepass.info)** - Hardened, secure and offline password manager. Does not have cloud-sync baked
in, deemed to be [gold standard](https://keepass.info/ratings.html) for secure
password managers. KeePass clients: [Strongbox](https://apps.apple.com/us/app/strongbox-keepass-pwsafe/id897283731)
*(Mac & iOS)*, [KeePassDX](https://play.google.com/store/apps/details?id=com.kunzisoft.keepass.free)
*(Android)*, [KeeWeb](https://keeweb.info) *(Web-based/ self-hosted)*,
[KeePassXC](https://keepassxc.org) *(Windows, Mac & Linux)*, see more KeePass
clients and extensions at [awesome-keepass](https://github.com/lgg/awesome-keepass)
by @lgg.
 - **[<img src='https://icon.horse/icon/lesspass.com' width='16' height='16' alt='icon' /> LessPass](https://lesspass.com)** - LessPass is a little different, since it generates your passwords using a hash
of the website name, your username and a single main-passphrase that you reuse.
It omits the need for you to ever need to store or sync your passwords. They
have apps for all the common platforms and a CLI, but you can also self-host it.
 	- [![GitHub: lesspass/lesspass](https://img.shields.io/github/stars/lesspass/lesspass?style=flat&logo=github&label=lesspass&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/lesspass/lesspass)
- **[<img src='https://icon.horse/icon/padloc.app' width='16' height='16' alt='icon' /> Padloc](https://padloc.app)** - A modern, open source password manager for individuals and teams. Beautiful,
intuitive and dead simple to use. Apps available for all platforms and you can
self-host it as well.
 	- [![GitHub: padloc/padloc](https://img.shields.io/github/stars/padloc/padloc?style=flat&logo=github&label=padloc&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/padloc/padloc)
- **[<img src='https://icon.horse/icon/proton.me' width='16' height='16' alt='icon' /> ProtonPass](https://proton.me/pass)** - From the creators of ProtonMail, ProtonPass is a new addition to their suite of
services. They have a full collection of user-friendly native mobile and desktop
apps. ProtonPass is one of the few "trustworthy" providers that also offers a
free plan.
 
<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [Password Safe](https://www.pwsafe.org/) - An offline, open source password manager designed by [Bruce Schneier](https://www.schneier.com/academic/passsafe/), with native applications for Windows, Linux, MacOS, Android and iOS, and support for YubiKey. The UI is a little dated, and there is no official browser extension, making is slightly less convenient to use compared with other options
> - [PassBolt](https://www.passbolt.com) - A good option for teams. It is free, open source, self-hosted, extensible and OpenPGP based. It is specifically good for development and DevOps usage, with integrations for the terminal, browser and chat, and can be easily extended for custom usage, and deployed quickly with Docker
> - [1Password](https://1password.com) - (proprietary) A fully-featured cross-platform password manager with sync. Free for self-hosted data (or $3/ month hosted). Be aware that 1Password is not fully open source, but they do regularly publish results of their independent [security audits](https://support.1password.com/security-assessments), and they have a solid reputation for transparently disclosing and fixing vulnerabilities     
</details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> **Other Open Source PM**: [Buttercup](https://buttercup.pw), [Clipperz](https://clipperz.is), [Pass](https://www.passwordstore.org), [Padloc](https://padloc.app), [TeamPass](https://teampass.net), [PSONO](https://psono.com), [UPM](http://upm.sourceforge.net), [Gorilla](https://github.com/zdia/gorilla/wiki), [Seahorse](https://gitlab.gnome.org/GNOME/seahorse) (for GNOME), [GNOME Keyring](https://wiki.gnome.org/Projects/GnomeKeyring), [KDE Wallet Manager](https://userbase.kde.org/KDE_Wallet_Manager). <br /><br /> If you are using a deprecated PM, you should migrate to something actively maintained. This includes: [Firefox Lockwise](https://www.mozilla.org/en-US/firefox/lockwise), [Encryptr](https://spideroak.com/personal/encryptr?ref=awesome-privacyr), [Mitro](https://www.mitro.co), [Rattic](https://spideroak.com/encryptr), [JPasswords](http://jpws.sourceforge.net/jpasswords.html), [Passopolis](https://passopolis.com), [KYPS](https://en.wikipedia.org/wiki/KYPS), [Factotum](http://man.9front.org/4/factotum).
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### 2-Factor Authentication

- **[<img src='https://raw.githubusercontent.com/beemdevelopment/Aegis/master/metadata/en-US/images/icon.png' width='16' height='16' alt='icon' /> Aegis](https://getaegis.app)** - Free, secure and open source authenticator app for Android. Has a backup/
restore feature and a customisable UI with dark mode
 	- [![GitHub: beemdevelopment/Aegis](https://img.shields.io/github/stars/beemdevelopment/Aegis?style=flat&logo=github&label=Aegis&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/beemdevelopment/Aegis)
- **[<img src='https://authenticatorpro.jmh.me/img/icon.svg' width='16' height='16' alt='icon' /> Authenticator Pro](https://authenticatorpro.jmh.me/)** - Free and open-source two factor authentication app for Android. It features
encrypted backups, icons, categories and a high level of customisation. It
also has a Wear OS companion app
 	- [![GitHub: jamie-mh/AuthenticatorPro](https://img.shields.io/github/stars/jamie-mh/AuthenticatorPro?style=flat&logo=github&label=AuthenticatorPro&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/jamie-mh/AuthenticatorPro)
- **[<img src='https://www.tofuauth.com/images/icon.svg' width='16' height='16' alt='icon' /> Tofu](https://www.tofuauth.com)** - An easy-to-use, open-source two-factor authentication app designed specifically
for iOS
 	- [![GitHub: iKenndac/Tofu](https://img.shields.io/github/stars/iKenndac/Tofu?style=flat&logo=github&label=Tofu&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/iKenndac/Tofu)
- **[<img src='https://i.ibb.co/dLqS8ZH/Screenshot-from-2024-02-19-20-47-48.png' width='16' height='16' alt='icon' /> Authenticator](https://mattrubin.me/authenticator)** - Simple, native, open source 2-FA Client for iOS, which never connects to the
internet - built by @mattrubin.me
 	- [![GitHub: mattrubin/Authenticator](https://img.shields.io/github/stars/mattrubin/Authenticator?style=flat&logo=github&label=Authenticator&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mattrubin/Authenticator)
- **[<img src='https://raivo-otp.com/img/app-icon.png' width='16' height='16' alt='icon' /> Raivo OTP](https://raivo-otp.com/)** - A native, lightweight and secure one-time-password (OTP) client built for iOS;
Raivo OTP! - built by @tijme
 	- [![GitHub: raivo-otp/ios-application](https://img.shields.io/github/stars/raivo-otp/ios-application?style=flat&logo=github&label=ios-application&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/raivo-otp/ios-application)
- **[<img src='https://winauth.github.io/winauth/favicon.ico' width='16' height='16' alt='icon' /> WinAuth](https://winauth.github.io/winauth)** - Portable, encrypted desktop authenticator app for Microsoft Windows. With
useful features, like hotkeys and some additional security tools, WinAuth is a
great companion authenticator for desktop power-users. It's open source and
well-established (since mid-2010)
 	- [![GitHub: winauth/winauth](https://img.shields.io/github/stars/winauth/winauth?style=flat&logo=github&label=winauth&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/winauth/winauth)
- **[<img src='https://gitlab.gnome.org/World/Authenticator/-/avatar?width=48' width='16' height='16' alt='icon' /> Authenticator](https://gitlab.gnome.org/World/Authenticator)** - Rust-based OTP authenticator. Has native With GNOME Shell integration. Also
available through [flathub](https://flathub.org/apps/details/com.belmoussaoui.Authenticator).
 - **[<img src='https://authenticator.cc/assets/logo/logo.svg' width='16' height='16' alt='icon' /> Authenticator](https://authenticator.cc)** - Authenticator Extension is an in-browser One-Time Password (OTP) client,
supports both Time-Based One-Time Password (TOTP, specified in [RFC 6238](https://tools.ietf.org/html/rfc6238))
and HMAC-Based One-Time Password (HOTP, specified in [RFC 4226](https://tools.ietf.org/html/rfc4226)).
 	- [![GitHub: Authenticator-Extension/Authenticator](https://img.shields.io/github/stars/Authenticator-Extension/Authenticator?style=flat&logo=github&label=Authenticator&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Authenticator-Extension/Authenticator)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [OTPClient](https://github.com/paolostivanin/OTPClient) *(Linux)*, [gauth](https://github.com/gbraadnl/gauth) *(Self-Hosted, Web-based)*, [Etopa](https://play.google.com/store/apps/details?id=de.ltheinrich.etopa) *(Android)*<br> For KeePass users, [TrayTop](https://keepass.info/plugins.html#traytotp) is a plugin for managing TOTP's -  offline and compatible with Windows, Mac and Linux.
> </details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> Check which websites support multi-factor authentication: [2fa.directory](https://2fa.directory/)
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### File Encryption

- **[<img src='https://veracrypt.fr/favicon.ico' width='16' height='16' alt='icon' /> VeraCrypt](https://www.veracrypt.fr)** - VeraCrypt is open source cross-platform disk encryption software. You can use
it to either encrypt a specific file or directory, or an entire disk or
partition. VeraCrypt is incredibly feature-rich, with comprehensive encryption
options, yet the GUI makes it easy to use. It has a CLI version, and a portable
edition. VeraCrypt is the successor of (the now deprecated) TrueCrypt.
 	- [![GitHub: veracrypt/VeraCrypt](https://img.shields.io/github/stars/veracrypt/VeraCrypt?style=flat&logo=github&label=VeraCrypt&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/veracrypt/VeraCrypt)
- **[<img src='https://avatars.githubusercontent.com/u/11850518' width='16' height='16' alt='icon' /> Cryptomator](https://cryptomator.org)** - Open source client-side encryption for cloud files - Cryptomator is geared
towards using alongside cloud-backup solutions, and hence preserves individual
file structure, so that they can be uploaded. It too is easy to use, but has
fewer technical customizations for how the data is encrypted, compared with
VeraCrypt. Cryptomator works on Windows, Linux and Mac - but also has excellent
mobile apps.
 	- [![GitHub: cryptomator/cryptomator](https://img.shields.io/github/stars/cryptomator/cryptomator?style=flat&logo=github&label=cryptomator&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/cryptomator/cryptomator)
- **[<img src='https://i.ibb.co/H7hHddf/logo-white.png' width='16' height='16' alt='icon' /> age](https://age-encryption.org)** - `age` is a simple, modern and secure CLI file encryption tool and Go library.
It features small explicit keys, no config options, and UNIX-style composability
 	- [![GitHub: FiloSottile/age](https://img.shields.io/github/stars/FiloSottile/age?style=flat&logo=github&label=age&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/FiloSottile/age)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Where possible, choose a cross-platform and well established encryption method, so that you are never faced with not being able to access your files using your current system.<br> Although well-established encryption methods are usually very secure, if the password is not strong, then an adversary may be able to gain access to your files, with a powerful enough GPU. If your system is compromised, then the password may also be able to be skimmed with a keylogger or other similar malware, so take care to follow good basic security practices


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [AES Crypt](https://www.aescrypt.com/) - A light-weight and easy file encryption utility. It includes applications for Windows, Mac OS, BSD and Linux, all of which can be interacted with either through the GUI, CLI or programatically though an API (available for Java, C, C# and Python). Although it is well established, with an overall positive reputation, there have been some [security issues](https://www.reddit.com/r/privacytoolsIO/comments/b7riov/aes_crypt_security_audit_1_serious_issue_found/) raised recently.
> - [CryptSetup](https://gitlab.com/cryptsetup/cryptsetup) - is a convenient layer for use on top of [dm-crypt](https://wiki.archlinux.org/index.php/Dm-crypt). [EncFS](https://github.com/vgough/encfs) is a cross-platform file-based encryption module, for use within user local directories. [geli](https://www.freebsd.org/cgi/man.cgi?query=geli&sektion=8) is a disk encryption subsystem included with FreeBSD.
> - [BitLocker](https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-overview) - is popular among Microsoft Windows and enterprise users, and provides fast, efficient and (if correctly configured) reasonably secure full drive encryption. However it is not open source, has poor compatibility with other operating systems, and has some very dodgy [defaults](https://www.diskcryptor.org/why-not-bitlocker/), which could lead to your system being compromised. Similarly, Apple's [FileVault](https://support.apple.com/en-us/HT204837) on MacOS is easy and secure, but again, the source code is proprietary.
> - [DiskCryptor](https://www.diskcryptor.org/) - Windows-only, open source, file and volume encryption solution, that makes a good alternative to BitLocker.</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Browsers

- **[<img src='https://librewolf.net/icon.svg' width='16' height='16' alt='icon' /> LibreWolf](https://librewolf.net)** - LibreWolf is an independent fork of Firefox that aims to provide better default
settings to improve on privacy, security and user freedom. Mozilla telemetry is
disabled, ties with Google (Safe Browsing) are severed, the content blocker
[uBlock Origin](https://github.com/gorhill/uBlock) is included and privacy
defaults are guided by research like the [Arkenfox project](https://github.com/arkenfox/user.js/).
 - **[<img src='https://brave.com/static-assets/images/brave-logo-sans-text.svg' width='16' height='16' alt='icon' /> Brave Browser](https://brave.com)** - Brave Browser, currently one of the most popular private browsers - it provides
speed, security, and privacy by blocking trackers with a clean, yet fully-featured
UI. It also pays you in [BAT tokens](https://basicattentiontoken.org/) for using it.
Brave also has Tor built-in, when you open up a private tab/ window.
 	- [![GitHub: brave/brave-browser](https://img.shields.io/github/stars/brave/brave-browser?style=flat&logo=github&label=brave-browser&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/brave/brave-browser)
- **[<img src='https://www.mozilla.org/media/protocol/img/logos/firefox/logo.fedb52c912d6.svg' width='16' height='16' alt='icon' /> Firefox](https://www.mozilla.org/firefox)** - Significantly more private, and offers some nifty privacy features than Chrome,
Internet Explorer and Safari. After installing, there are a couple of small tweaks
you will need to make, in order to secure Firefox. For a though config, see
[@arkenfox's user.js](https://github.com/arkenfox/user.js/). You can also follow
one of these guides by: [Restore Privacy](https://restoreprivacy.com/firefox-privacy/)
or [12Bytes](https://codeberg.org/12bytes/firefox-config-guide)
 - **[<img src='https://www.torproject.org/static/images/favicon/favicon.ico' width='16' height='16' alt='icon' /> Tor Browser](https://www.torproject.org/)** - Tor provides an extra layer of anonymity, by encrypting each of your requests, then
routing it through several nodes, making it near-impossible for you to be tracked by
your ISP/ provider. It does make every-day browsing a little slower, and some sites
may not work correctly. As with everything there are [trade-offs](https://github.com/Lissy93/personal-security-checklist/issues/19)
 - **[<img src='https://www.bromite.org/bromite.png' width='16' height='16' alt='icon' /> Bromite](https://www.bromite.org/)** - Hardened and privacy-respecting fork of Chromium for Android. Comes with built-in
adblock and additional settings for hardening.
 	- [![GitHub: bromite/bromite](https://img.shields.io/github/stars/bromite/bromite?style=flat&logo=github&label=bromite&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/bromite/bromite)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> New vulnerabilities are being discovered and patched all the time - use a browser that is being actively maintained, in order to receive these security-critical updates.<br> Even privacy-respecting browsers, often do not have the best privacy options enabled by default. After installing, check the privacy & security settings, and update the configuration to something that you are comfortable with. 12Bytes maintains a comprehensive guide on [Firefox Configuration for Privacy and Performance](https://12bytes.org/articles/tech/firefox/firefoxgecko-configuration-guide-for-privacy-and-performance-buffs/)


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> **Mobile Browsers**: [Mull](https://f-droid.org/en/packages/us.spotco.fennec_dos/) Hardened fork of FF-Fenix (Android), [Firefox Focus](https://support.mozilla.org/en-US/kb/focus) (Android/ iOS), [DuckDuckGo Browser](https://help.duckduckgo.com/duckduckgo-help-pages/mobile/ios/) (Android/ iOS), [Orbot](https://guardianproject.info/apps/orbot/) + [Tor](https://www.torproject.org/download/#android) (Android), [Onion Browser](https://onionbrowser.com/) (iOS)<br><br> **Additional Desktop**: [Nyxt](https://nyxt.atlas.engineer/), [WaterFox](https://www.waterfox.net), [Epic Privacy Browser](https://www.epicbrowser.com), [PaleMoon](https://www.palemoon.org), [Iridium](https://iridiumbrowser.de/), [Sea Monkey](https://www.seamonkey-project.org/), [Ungoogled-Chromium](https://github.com/Eloston/ungoogled-chromium), [Basilisk Browser](https://www.basilisk-browser.org/) and [IceCat](https://www.gnu.org/software/gnuzilla/) 12Bytes also maintains a list privacy & security [extensions](https://12bytes.org/articles/tech/firefox/firefox-extensions-my-picks/)
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Search Engines

- **[<img src='https://duckduckgo.com/favicon.png' width='16' height='16' alt='icon' /> DuckDuckGo](https://duckduckgo.com)** - DuckDuckGo is a very user-friendly, fast and secure search engine. It's totally
private, with no trackers, cookies or ads. It's also highly customisable, with
dark-mode, many languages and features. They even have a [.onion](https://3g2upl4pq6kufc4m.onion)
URL, for use with Tor and a [no Javascript version](https://duckduckgo.com/html/)
 - **[<img src='https://avatars.githubusercontent.com/u/1692504' width='16' height='16' alt='icon' /> Qwant](https://www.qwant.com)** - French service that aggregates Bings results, with its own results. Qwant doesn't
plant any cookies, nor have any trackers or third-party advertising. It returns
non-biased search results, with no promotions. Qwant has a unique, but nice UI.
 - **[<img src='https://www.startpage.com/favicon.ico' width='16' height='16' alt='icon' /> Startpage](https://www.startpage.com)** - Dutch search engine that searches on google and shows the results (slightly
rearranged). It has several configurations that improve privacy during use
(it is not open source)
 - **[<img src='https://www.mojeek.com/favicon.png' width='16' height='16' alt='icon' /> Mojeek](https://mojeek.com)** - British search engine providing independent and unbiased search results using
its own crawler. Has a zero tracking policy (it is not open source)
 
<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [MetaGear](https://metager.org)
> - [YaCy](https://yacy.net)
> - [Brave Search](https://search.brave.com/)
> - [Searx](https://github.com/searxng/searxng) - Self-hostable search engines that use the results of multiple other engines (such as Google and Bing) at the same time. They're open source and self-hostable, although using a [public instance](https://searx.space) has the benefit of not singling out your queries to the engines used. A fork of the original [Searx](https://searx.github.io/searx/).
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Communication

### Encrypted Messaging

- **[<img src='https://signal.org/assets/images/favicon/android-chrome-192x192.png' width='16' height='16' alt='icon' /> Signal](https://signal.org)** - Probably one of the most popular, secure private messaging apps that combines
strong encryption (see [Signal Protocol](https://en.wikipedia.org/wiki/Signal_Protocol))
with a simple UI and plenty of features. It's widely used across the world, and
easy-to-use, functioning similar to WhatsApp - with instant messaging, read-receipts,
support for media attachments and allows for high-quality voice and video calls.
It's cross-platform, open-source and totally free. Signal is [recommended](https://twitter.com/Snowden/status/661313394906161152)
by Edward Snowden, and is a perfect solution for most users.
 	- [![GitHub: signalapp/Signal-Server](https://img.shields.io/github/stars/signalapp/Signal-Server?style=flat&logo=github&label=Signal-Server&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/signalapp/Signal-Server)
- **[<img src='https://getsession.org/favicon.ico' width='16' height='16' alt='icon' /> Session](https://getsession.org)** - Session is a fork of Signal, however unlike Signal it does not require a mobile
number (or any other personal data) to register, instead each user is identified
by a public key. It is also decentralized, with servers being run by the community
though [Loki Net](https://loki.network), messages are encrypted and routed through
several of these nodes. All communications are E2E encrypted, and there is no
meta data.
 	- [![GitHub: oxen-io/lokinet](https://img.shields.io/github/stars/oxen-io/lokinet?style=flat&logo=github&label=lokinet&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/oxen-io/lokinet)
- **[<img src='https://xmpp.org/favicon.ico' width='16' height='16' alt='icon' /> XMPP](https://xmpp.org)** - XMPP, also known as Jabber, is an open standard for decentralized messaging that
has been widely used for decades. It has actually been the basis upon which
WhatsApp, Facebook's Chat and Google's Talk were built, but these companies
(eventually) chose to remove the interoperability with other servers. Prominent
XMPP clients support [OMEMO end-to-end encryption](https://en.wikipedia.org/wiki/OMEMO),
which is based on the [Double Ratchet Algorithm](https://en.wikipedia.org/wiki/Double_Ratchet_Algorithm)
that is used in Signal. For more hands-on information and to register an account
you can visit [JoinJabber](https://joinjabber.org).
 	- [![GitHub: xsf/xmpp.org](https://img.shields.io/github/stars/xsf/xmpp.org?style=flat&logo=github&label=xmpp.org&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/xsf/xmpp.org)
- **[<img src='https://matrix.org/assets/favicon.ico' width='16' height='16' alt='icon' /> Matrix](https://matrix.org)** - Matrix is a decentralized open network for secure communications, with E2E
encryption with Olm and Megolm. Along with the [Element](https://element.io/)
client, it supports VOIP + video calling and IM + group chats. Since Matrix has
an open specification and Simple pragmatic RESTful HTTP/JSON API it makes it easy
to integrates with existing 3rd party IDs to authenticate and discover users, as
well as to build apps on top of it.
 	- [![GitHub: matrix-org/dendrite](https://img.shields.io/github/stars/matrix-org/dendrite?style=flat&logo=github&label=dendrite&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/matrix-org/dendrite)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Many messaging apps claim to be secure, but if they are not open source, then this cannot be verified - and they **should not be trusted**. This applies to [Telegram](https://telegram.org), [Threema](https://threema.ch), [Cypher](https://www.goldenfrog.com/cyphr), [Wickr](https://wickr.com/), [Silent Phone](https://www.silentcircle.com/products-and-solutions/silent-phone/) and [Viber](https://www.viber.com/), to name a few - these apps should not be used to communicate any sensitive data. [Wire](https://wire.com/) has also been removed, due to a [recent acquisition](https://blog.privacytools.io/delisting-wire/)


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [Chat Secure](https://chatsecure.org)
> - [KeyBase](https://keybase.io/) - Allows encrypted real-time chat, group chats, and public and private file sharing. It also has some nice features around cryptographically proving social identities, and makes PGP signing, encrypting and decrypting messages easy. However, since it was [acquired by Zoom](https://keybase.io/blog/keybase-joins-zoom) in 2020, it has no longer been receiving regular updates.
> - [OpenPGP](https://www.openpgp.org) - can be used over existing chat networks (such as email or message boards). It provides cryptographic privacy and authentication, PGP is used to encrypt messages.<br /> **Note/ Issues with PGP**  PGP is [not easy](https://restoreprivacy.com/let-pgp-die/) to use for beginners, and could lead to human error/ mistakes being made, which would be overall much worse than if an alternate, simpler system was used. Do not use [32-bit key IDs](https://evil32.com/) - they are too short to be secure. There have also been vulnerabilities found in the OpenPGP and S/MIME, defined in [EFAIL](https://efail.de/), so although it still considered secure for general purpose use, for general chat, it may be better to use an encrypted messaging or email app instead.
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### P2P Messaging

With [Peer-to-Peer](https://en.wikipedia.org/wiki/Peer-to-peer) networks, there are no central server, so there is nothing that can be raided, shut-down or forced to turn over data. There are P2P networks available that are open source, E2E encrypted, routed through Tor services, totally anonymous and operate without the collection of metadata.

- **[<img src='https://oxen.io/favicon.ico' width='16' height='16' alt='icon' /> Oxen](https://oxen.io/)** - Oxen (previously Loki) is an open source set of tools that allow users to transact
and communicate anonymously and privately, through a decentralised, encrypted,
onion-based network.
Session is a desktop and mobile app that uses these private routing protocols to
secure messages, media and metadata.
 	- [![GitHub: oxen-io/lokinet](https://img.shields.io/github/stars/oxen-io/lokinet?style=flat&logo=github&label=lokinet&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/oxen-io/lokinet)
- **[<img src='https://briarproject.org/img/briar_logo_circle.png' width='16' height='16' alt='icon' /> Briar](https://briarproject.org)** - Tor-based Android app for P2P encrypted messaging and forums. Where content is
stored securely on your device (not in the cloud). It also allows you to connect
directly with nearby contacts, without internet access (using Bluetooth or WiFi).
 - **[<img src='https://www.ricochetrefresh.net/apple-touch-icon.png' width='16' height='16' alt='icon' /> Ricochet Refresh](https://www.ricochetrefresh.net)** - Desktop instant messenger, that uses the Tor network to rendezvous with your
contacts without revealing your identity, location/ IP or meta data. There are
no servers to monitor, censor, or hack so Ricochet is secure, automatic and easy
to use.
 	- [![GitHub: blueprint-freespeech/ricochet-refresh](https://img.shields.io/github/stars/blueprint-freespeech/ricochet-refresh?style=flat&logo=github&label=ricochet-refresh&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/blueprint-freespeech/ricochet-refresh)
- **[<img src='https://jami.net/assets/images/favicon/apple-touch-icon-57x57.png' width='16' height='16' alt='icon' /> Jami](https://jami.net)** - P2P encrypted chat network with cross-platform GNU client apps. Jami supports
audio and video calls, screen sharing, conference hosting and instant messaging.
 	- [![GitHub: savoirfairelinux/jami-project](https://img.shields.io/github/stars/savoirfairelinux/jami-project?style=flat&logo=github&label=jami-project&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/savoirfairelinux/jami-project)
- **[<img src='https://tox.chat/theme/img/favicon.ico' width='16' height='16' alt='icon' /> Tox + qTox client](https://tox.chat)** - Open source, encrypted, distributed chat network, with clients for desktop and
mobile - see [supported clients](https://tox.chat/clients.html). Clearly documented
code and multiple language bindings make it easy for developers to integrate with
Tox.
 
<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [Cwtch](https://cwtch.im)
> - [BitMessage](https://github.com/Bitmessage/PyBitmessage)
> - [RetroShare](https://retroshare.cc)
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Encrypted Email

Email is not secure - your messages can be easily intercepted and read. Corporations scan the content of your mail, to build up a profile of you, either to show you targeted ads or to sell onto third-parties. Through the [Prism Program](https://en.wikipedia.org/wiki/PRISM_(surveillance_program)), the government also has full access to your emails (if not end-to-end encrypted) - this applies to Gmail, Outlook Mail, Yahoo Mail, GMX, ZoHo, iCloud, AOL and more.<br><br> For a more details comparison of email providers, see [email-comparison.as93.net](https://email-comparison.as93.net/)

- **[<img src='https://proton.me/favicons/android-chrome-192x192.png' width='16' height='16' alt='icon' /> ProtonMail](https://protonmail.com)** - An open-source, end-to-end encrypted anonymous email service. ProtonMail has a
modern easy-to-use and customizable UI, as well as fast, secure native mobile
apps. ProtonMail has all the features that you'd expect from a modern email
service and is based on simplicity without sacrificing security. It has a free
plan or a premium option for using custom domains (starting at $5/month).
ProtonMail requires no personally identifiable information for signup, they have
a [.onion](https://protonirockerxow.onion) server, for access via Tor, and they
accept anonymous payment: BTC and cash (as well as the normal credit card and PayPal).
 	- [![GitHub: ProtonMail/WebClients](https://img.shields.io/github/stars/ProtonMail/WebClients?style=flat&logo=github&label=WebClients&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ProtonMail/WebClients)
- **[<img src='https://tuta.com/resources/favicon/logo-favicon.svg' width='16' height='16' alt='icon' /> Tuta](https://tuta.com)** - Free and open source email service based in Germany. It has a basic intuitive UI,
secure native mobile apps, anonymous signup, and a .onion site. Tuta has a
full-featured free plan or a premium subscription for businesses allowing for
custom domains ($12/ month). Tuta [does not use OpenPGP](https://tuta.com/blog/posts/differences-email-encryption/)
like most encrypted mail providers, instead they use a standardized, hybrid method
consisting of a symmetrical and an asymmetrical algorithm (with 128 bit AES, and
2048 bit RSA). This causes compatibility issues when communicating with contacts
using PGP. But it does allow them to encrypt much more of the header data (body,
attachments, subject lines, and sender names etc) which PGP mail providers cannot do.
 	- [![GitHub: tutao/tutanota](https://img.shields.io/github/stars/tutao/tutanota?style=flat&logo=github&label=tutanota&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/tutao/tutanota)
- **[<img src='https://forwardemail.net/img/android-chrome-192x192.png' width='16' height='16' alt='icon' /> Forward Email](https://forwardemail.net)** - An open source, privacy-focused, encrypted email service supporting SMTP, IMAP, and API access
 	- [![GitHub: forwardemail/free-email-forwarding](https://img.shields.io/github/stars/forwardemail/free-email-forwarding?style=flat&logo=github&label=free-email-forwarding&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/forwardemail/free-email-forwarding)
- **[<img src='https://mailfence.com/c/mailfence/images/favicon/android-chrome-192x192.png' width='16' height='16' alt='icon' /> Mailfence](https://mailfence.com?src=digitald)** - Mailfence supports OpenPGP so that you can manually exchange encryption keys
independently from the Mailfence servers, putting you in full control. Mailfence
has a simple UI, similar to that of Outlook, and it comes with bundled with
calendar, address book, and files. All mail settings are highly customizable,
yet still clear and easy to use. Sign up is not anonymous, since your name, and
prior email address is required. There is a fully-featured free plan, or you can
pay for premium, and use a custom domain ($2.50/ month, or $7.50/ month for 5
domains), where Bitcoin, LiteCoin or credit card is accepted.
 - **[<img src='https://i.ibb.co/zJtHBTZ/mailfence.png' width='16' height='16' alt='icon' /> MailBox.org](https://mailbox.org)** - A Berlin-based, eco-friendly secure mail provider. There is no free plan, the
standard service costs €12/year. You can use your own domain, with the option of
a [catch-all alias](https://kb.mailbox.org/display/MBOKBEN/Using+catch-all+alias+with+own+domain).
They provide good account security and email encryption, with OpenPGP, as well as
encrypted storage. There is no dedicated app, but it works well with any standard
mail client with SSL. There's also currently no anonymous payment option.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> - When using an end-to-end encryption technology like OpenPGP, some metadata in the email header will not be encrypted.
- OpenPGP also does not support Forward secrecy, which means if either your or the recipient's private key is ever stolen,
all previous messages encrypted with it will be exposed. You should take great care to keep your private keys safe.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [HushMail](https://www.hushmail.com)
> - [Soverin](https://soverin.net)
> - [StartMail](https://www.startmail.com)
> - [Posteo](https://posteo.de)
> - [Disroot](https://disroot.org/en)
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Email Clients

Email clients are the programs used to interact with the mail server. For hosted email, then the web and mobile clients provided by your email service are usually adequate, and may be the most secure option. For self-hosted email, you will need to install and configure mail clients for web, desktop or mobile. A benefit of using an IMAP client, is that you will always have an offline backup of all email messages (which can then be encrypted and archived), and many applications let you aggregate multiple mailboxes for convenience. Desktop mail clients are not vulnerable to the common browser attacks, that their web app counterparts are.

- **[<img src='https://www.thunderbird.net/media/img/thunderbird/ios-icon-180.png' width='16' height='16' alt='icon' /> Mozilla Thunderbird](https://www.thunderbird.net)** - Free and open source email application developed and backed by Mozilla -it's secure,
private easy and customizable. As of V 78.2.1 encryption is built in, and the
[TorBirdy](https://trac.torproject.org/projects/tor/wiki/torbirdy) extension routes
all traffic through the Tor network. Forks, such as
[Betterbird](https://github.com/Betterbird/thunderbird-patches) may add additional features.
 - **[<img src='https://www.emclient.com/favicon.ico' width='16' height='16' alt='icon' /> eM Client](https://www.emclient.com)** - Productivity-based email client, for Windows and MacOS. eM Client has a clean user
interface, snappy performance and good compatibility. There is a paid version, with
some handy features, including snoozing incoming emails, watching for replies for a
specific thread, message translation, send later, and built-in Calendar, Tasks,
Contacts and Notes. Note, eM Client is proprietary, and not open source.
 - **[<img src='https://snappymail.eu/static/img/logo-256x256.png' width='16' height='16' alt='icon' /> SnappyMail](https://snappymail.eu)** - Simple, modern, fast web-based mail client. This is an IMAP-only fork of
[RainLoop](http://www.rainloop.net) that mitigates a severe
[RainLoop vulnerability](https://thehackernews.com/2022/04/unpatched-bug-in-rainloop-webmail-could.html)
and adds several new [features](https://snappymail.eu/comparison).
 	- [![GitHub: the-djmaze/snappymail](https://img.shields.io/github/stars/the-djmaze/snappymail?style=flat&logo=github&label=snappymail&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/the-djmaze/snappymail)
- **[<img src='https://roundcube.net/images/roundcube_logo_icon.svg' width='16' height='16' alt='icon' /> RoundCube](https://roundcube.net)** - Browser-based multilingual IMAP client with an application-like user interface. It
provides full functionality you expect from an email client, including MIME support,
address book, folder manipulation, message searching and spell checking.
 	- [![GitHub: roundcube/roundcubemail](https://img.shields.io/github/stars/roundcube/roundcubemail?style=flat&logo=github&label=roundcubemail&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/roundcube/roundcubemail)
- **[<img src='https://raw.githubusercontent.com/M66B/FairEmail/master/app/src/main/ic_launcher-web.png' width='16' height='16' alt='icon' /> FairEmail](https://email.faircode.eu)** - Open source, fully-featured and easy mail client for Android. Supports unlimited
accounts and email addresses with the option for a unified inbox. Clean user
interface, with a dark mode option, it is also very lightweight and consumes minimal
data usage.
 	- [![GitHub: M66B/FairEmail](https://img.shields.io/github/stars/M66B/FairEmail?style=flat&logo=github&label=FairEmail&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/M66B/FairEmail)
- **[<img src='https://k9mail.app/assets/img/k9-logo.svg' width='16' height='16' alt='icon' /> K-9 Mail](https://k9mail.app)** - K-9 (or Thunderbird for Android) is open source,
very well supported and trusted - k9 has been around for nearly
as long as Android itself! It supports multiple accounts, search, IMAP push email,
multi-folder sync, flagging, filing, signatures, BCC-self, PGP/MIME & more. Install
OpenKeychain along side it, in order to encrypt/ decrypt emails using OpenPGP.
 	- [![GitHub: thunderbird/thunderbird-android](https://img.shields.io/github/stars/thunderbird/thunderbird-android?style=flat&logo=github&label=thunderbird-android&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/thunderbird/thunderbird-android)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> One disadvantage of mail clients, is that many of them do not support 2FA, so it is important to keep your device secured and encrypted


</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Mail Forwarding

Revealing your real email address online can put you at risk. Email aliasing allows messages to be sent to [anything]@my-domain.com and still land in your primary inbox. This protects your real email address from being revealed. Aliases are generated automatically, the first time they are used. This approach lets you identify which provider leaked your email address, and block an alias with 1-click.

- **[<img src='https://addy.io/apple-touch-icon.png' width='16' height='16' alt='icon' /> Addy](https://addy.io)** - An open source anonymous email forwarding service, allowing you to create unlimited
email aliases. Has a free plan.
 	- [![GitHub: anonaddy/anonaddy](https://img.shields.io/github/stars/anonaddy/anonaddy?style=flat&logo=github&label=anonaddy&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/anonaddy/anonaddy)
- **[<img src='https://33mail.com/favicon.ico' width='16' height='16' alt='icon' /> 33Mail](http://33mail.com)** - A long-standing aliasing service. As well as receiving, 33Mail also lets you reply
to forwarded addresses anonymously. Free plan, as well as Premium plan ($1/ month)
if you'd like to use a custom domain. Note that 33Mail usese Google Analytics.
 - **[<img src='https://simplelogin.io/favicon.ico' width='16' height='16' alt='icon' /> SimpleLogin](https://simplelogin.io)** - Fully open source (view on [GitHub](https://github.com/simple-login)) alias service
with many additional features. Can be self-hosted, or the managed version has a free
plan, as well as hosted premium option ($2.99/ month) for using custom domains.
 - **[<img src='https://relay.firefox.com/favicon.svg' width='16' height='16' alt='icon' /> Firefox Private Relay](https://relay.firefox.com)** - Developed and managed by Mozilla, Relay is a Firefox addon, that lets you make an
email alias with 1 click, and have all messages forwarded onto your personal email.
Relay is totally free to use, and very accessible to less experienced users, but also
[open source](https://github.com/mozilla/fx-private-relay), and able to me self-hosted
for advanced usage.
 	- [![GitHub: mozilla/fx-private-relay](https://img.shields.io/github/stars/mozilla/fx-private-relay?style=flat&logo=github&label=fx-private-relay&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mozilla/fx-private-relay)
- **[<img src='https://forwardemail.net/img/android-chrome-192x192.png' width='16' height='16' alt='icon' /> ForwardEmail](https://forwardemail.net)** - Simple open source catch-all email forwarding service. Easy to self-host (see on
[GitHub](https://github.com/forwardemail/free-email-forwarding)), or the hosted version
has a free plan as well as a ($3/month) premium plan.
 	- [![GitHub: forwardemail/free-email-forwarding](https://img.shields.io/github/stars/forwardemail/free-email-forwarding?style=flat&logo=github&label=free-email-forwarding&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/forwardemail/free-email-forwarding)
- **[<img src='https://proton.me/favicons/android-chrome-192x192.png' width='16' height='16' alt='icon' /> ProtonMail](https://protonmail.com/pricing)** - If you already have ProtonMail's Professional (€8/month) or Visionary (€30/month) package,
then an implementation of this feature is available via the Catch-All Email feature.
 
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Email Security Tools

- **[<img src='https://upload.wikimedia.org/wikipedia/commons/5/50/Enigmail_logo_2018.svg' width='16' height='16' alt='icon' /> Enigmail](https://www.enigmail.net)** - Mail client add-on, enabling the use of OpenPGP to easily encrypt, decrypt,
verify and sign emails. Free and open source, Enigmail is compatible with Interlink
Mail & News and Postbox. Their website contains thorough documentation and
quick-start guides, once set up it is extremely convenient to use.
 - **[<img src='https://icon.horse/icon/www.emailprivacytester.com' width='16' height='16' alt='icon' /> Email Privacy Tester](https://www.emailprivacytester.com/)** - Quick tool, that enables you to test whether your mail client "reads" your emails
before you've opened them, and also checks what analytics, read-receipts or other
tracking data your mail client allows to be sent back to the sender. The system is
open source ([on GitLab](https://gitlab.com/mikecardwell/ept3)), developed by
[Mike Cardwell](https://www.grepular.com/) and trusted, but if you do not want to
use your real email, creating a second account with the same provider, should yield
identical results.
 	- [![GitHub: mikecardwell/email-privacy-tester](https://img.shields.io/github/stars/mikecardwell/email-privacy-tester?style=flat&logo=github&label=email-privacy-tester&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mikecardwell/email-privacy-tester)
- **[<img src='https://addons.thunderbird.net/user-media/addon_icons/438/438634-64.png' width='16' height='16' alt='icon' /> DKIM Verifier](https://addons.thunderbird.net/en-US/thunderbird/addon/dkim-verifier/?collection_id=a5557f08-eafd-7a39-81c6-09127da790f7)** - Verifies DKIM signatures and shows the result in the e-mail header, in order to help
spot spoofed emails (which do not come from the domain that they claim to).
 	- [![GitHub: lieser/dkim_verifier](https://img.shields.io/github/stars/lieser/dkim_verifier?style=flat&logo=github&label=dkim_verifier&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/lieser/dkim_verifier)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> If you are using ProtonMail, then the [ProtonMail Bridge](https://protonmail.com/bridge/thunderbird) enables you to sync & backup your emails to your own desktop mail client. It works well with Thunderbird, Microsoft Outlook and others
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### VOIP Clients

- **[<img src='https://www.mumble.info/css/apple-touch-icon.png' width='16' height='16' alt='icon' /> Mumble](https://www.mumble.info/)** - Open source, low-latency, high quality voice chat software. You can host your
own server, or use a hosted instance, there are client applications for Windows,
MacOS and Linux as well as third-party apps for Android and iOS.
 	- [![GitHub: mumble-voip/mumble](https://img.shields.io/github/stars/mumble-voip/mumble?style=flat&logo=github&label=mumble&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mumble-voip/mumble)
- **[<img src='https://f-droid.org/repo/org.linphone/en-US/icon_G0LG_yfcg9OhsnG4KMctTmcSa71iC8v2lFsDerfB_9s=.png' width='16' height='16' alt='icon' /> Linphone](https://www.linphone.org)** - Open source audio, video and IM groups with E2E encryption and built-in media
server. [SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol)-based
evolving to [RCS](https://en.wikipedia.org/wiki/Rich_Communication_Services).
Native apps for Android, iOS, Windows, GNU/Linux and MacOS.
 	- [![GitHub: BelledonneCommunications/linphone-desktop](https://img.shields.io/github/stars/BelledonneCommunications/linphone-desktop?style=flat&logo=github&label=linphone-desktop&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/BelledonneCommunications/linphone-desktop)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [SpoofCard](https://www.spoofcard.com) - Lets you make anonymous phone calls + voicemail, but not open source and limited information on security (avoid sending any secure info).
> - [MicroSip](https://www.microsip.org) - An open source portable SIP softphone for Windows based on PJSIP stack</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Virtual Phone Numbers

- **[<img src='https://silent.link/static/favicon/apple-icon-114x114.png' width='16' height='16' alt='icon' /> Silent.link](https://silent.link/)** - Anonymous eSIM for sending / receiving SMS, incoming calls and 4G / 5G internet
+ world-wide roaming. No data is required at sign-up. Affordable pricing, with
payments and top-ups accepted in BTC. Requires an eSim-compatible device.
 - **[<img src='https://crypton.sh/assets/shared/icons/favicon-32x32.png' width='16' height='16' alt='icon' /> Crypton.sh](https://crypton.sh/)** - Physical SIM card in the cloud, for sending + receiving SMS messages. Messages
are encrypted using your chosen private key. Includes a web interface, as well
as an API for interacting with it from any device. Pricing is around €7.00/month,
and payment is accepted in BTC, XMR or credit card.
 	- [![GitHub: rinzlerch/user-encryption-wrapper](https://img.shields.io/github/stars/rinzlerch/user-encryption-wrapper?style=flat&logo=github&label=user-encryption-wrapper&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/rinzlerch/user-encryption-wrapper)
- **[<img src='https://jmp.chat/static/jmp.svg' width='16' height='16' alt='icon' /> Jmp.chat](https://jmp.chat/)** - Phone number for incoming + outgoing calls and messages, provided by Soprani.
Works with Jabber, Matrix, Snikket, XMPP or any SIP client. Pricing starts at
$2.99 / month. Only available in the US and Canada, as (as of 2022) the service
is still in Beta. See alternate instances at [soprani.ca](https://soprani.ca/)
 - **[<img src='https://i.ibb.co/Dgwr4Z0/monero-sms.png' width='16' height='16' alt='icon' /> MoneroSMS](https://monerosms.com)** - Anonymous SMS service able to activate accounts. Accessible over web, CLI, or
email. Pricing starts at $3.60 / month. The service is in beta as of 2022.
 
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Team Collaboration

Now more than ever we are relying on software to help with team collaboration. Unfortunately many popular options, such as [Slack](https://www.wired.co.uk/article/slack-privacy-settings-notifications), [Microsoft Teams](https://www.wired.co.uk/article/microsoft-teams-meeting-data-privacy), [Google for Work](https://www.wired.com/story/google-tracks-you-privacy/) and [Discord](https://cybernews.com/privacy/discord-privacy-tips-that-you-should-use-in-2020/) all come with some serious privacy implications.<br> Typical features of team collaboration software includes: instant messaging, closed and open group messaging, voice and video conference calling, file sharing/ file drop, and some level or scheduling functionality.

- **[<img src='https://play-lh.googleusercontent.com/wGn6UxVJUVWBOEAR_864Y_TG42iCsr8Ls3xmLoT4oOimSo6lk2_2gfBATqNDNmArKzQ' width='16' height='16' alt='icon' /> Rocket.Chat](https://rocket.chat)** - Easy-to-deploy, self-hosted team collaboration platform with stable, feature-rich
cross-platform client apps. The UI is fast, good looking and intuitive, so very
little technical experience is needed for users of the platform. Rocket.Chat's
feature set is similar to Slack's, making it a good replacement for any team
looking to have greater control over their data.
 	- [![GitHub: RocketChat/Rocket.Chat](https://img.shields.io/github/stars/RocketChat/Rocket.Chat?style=flat&logo=github&label=Rocket.Chat&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/RocketChat/Rocket.Chat)
- **[<img src='https://retroshare.cc/img/retroshare-symbol.png' width='16' height='16' alt='icon' /> RetroShare](https://retroshare.cc/)** - Secure group communications, with the option to be used over Tor or I2P. Fast
intuitive group and 1-to-1 chats with text and rich media using decentralized
chat rooms, with a mail feature for delivering messages to offline contacts.
A channels feature makes it possible for members of different teams to stay
up-to-date with each other, and to share files. Also includes built-in forums,
link aggregations, file sharing and voice and video calling. RetroShare is a
bit more complex to use than some alternatives, and the UI is quite *retro*,
so may not be appropriate for a non-technical team.
 	- [![GitHub: RetroShare/RetroShare](https://img.shields.io/github/stars/RetroShare/RetroShare?style=flat&logo=github&label=RetroShare&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/RetroShare/RetroShare)
- **[<img src='https://element.io/images/favicon.png' width='16' height='16' alt='icon' /> Element](https://element.io/)** - Privacy-focused messenger using the Matrix protocol. The Element client allows
for group chat rooms, media sharing voice and video group calls.
 	- [![GitHub: element-hq/element-web](https://img.shields.io/github/stars/element-hq/element-web?style=flat&logo=github&label=element-web&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/element-hq/element-web)
- **[<img src='https://www.dlf.pt/dfpng/middlepng/60-606143_internet-relay-chat-irc-logo-hd-png-download.png' width='16' height='16' alt='icon' /> Internet Relay Chat](None)** - An IRC-based solution is another option, being decentralized there is no point
of failure, and it's easy to self-host. However it's important to keep security
in mind while configuring your IRC instance and ensure that channels are properly
encrypted - IRC tends to be better for open communications. There's a variety of
clients to choose from - popular options include: The Longe (Web-based), HexChat
(Linux), Pidgin (Linux), WeeChat (Linux, terminal-based), IceChat (Windows),
XChat Aqua (MacOS), Palaver (iOS) and Revolution (Android).
 - **[<img src='https://avatars.githubusercontent.com/u/9828093' width='16' height='16' alt='icon' /> Mattermost](https://mattermost.org/)** - Mattermost has an open source edition, which can be self-hosted. It makes a good
Slack alternative, with native desktop, mobile and web apps and a wide variety of
integrations.
 	- [![GitHub: mattermost/mattermost](https://img.shields.io/github/stars/mattermost/mattermost?style=flat&logo=github&label=mattermost&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mattermost/mattermost)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> Some chat platforms allow for cross-platform group chats, voice and video conferencing, but without the additional collaboration features. For example, [Tox](https://tox.chat/), [Session](https://getsession.org/), [Ricochet](https://ricochet.im/), [Mumble](https://www.mumble.info/) and [Jami](https://jami.net/).<br> For Conferences, [OSEM](https://osem.io) is an open source all-in-one conference management tool, providing Registration, Schedules, Live and Recorded Sessions, Paper Submissions, Marketing Pages and Administration.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Security Tools

### Browser Extensions

The following browser add-ons give you better control over what content is able to be loaded and executed while your browsing.<br> Before installing anything, you should read the Word of Warning section below.

- **[<img src='https://i.ibb.co/8Y1ds5X/privacy-badger.png' width='16' height='16' alt='icon' /> Privacy Badger](https://privacybadger.org/)** - Blocks invisible trackers, in order to stop advertisers and other third-parties
from secretly tracking where you go and what pages you look at. **Download**:
[Chrome](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp) -
[Firefox](https://addons.mozilla.org/en-GB/firefox/addon/privacy-badger17/)
 	- [![GitHub: EFForg/privacybadger](https://img.shields.io/github/stars/EFForg/privacybadger?style=flat&logo=github&label=privacybadger&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/EFForg/privacybadger)
- **[<img src='https://raw.githubusercontent.com/gorhill/uBlock/master/src/img/ublock.svg' width='16' height='16' alt='icon' /> uBlock Origin](https://ublockorigin.com)** - Block ads, trackers and malware sites. **Download**:
[Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en-GB) -
[Firefox](https://addons.mozilla.org/en-GB/firefox/addon/ublock-origin/)
 	- [![GitHub: gorhill/uBlock](https://img.shields.io/github/stars/gorhill/uBlock?style=flat&logo=github&label=uBlock&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/gorhill/uBlock)
- **[<img src='https://lh3.googleusercontent.com/c5co_NoLmEt48VC_yVp0JgKcgd83yiq_CdekGaOlBBfD5WII5mjxngERgikcQd4P56uoX9epiknU5ktXadPqj2EEVsE' width='16' height='16' alt='icon' /> ScriptSafe](https://www.andryou.com/scriptsafe)** - Allows you to block the execution of certain scripts. **Download**:
[Chrome](https://chromewebstore.google.com/detail/scriptsafe/oiigbmnaadbkfbmpbfijlflahbdbdgdf) -
[Ppera](https://addons.opera.com/en/extensions/details/scriptsafe-2/)
 	- [![GitHub: andryou/scriptsafe](https://img.shields.io/github/stars/andryou/scriptsafe?style=flat&logo=github&label=scriptsafe&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/andryou/scriptsafe)
- **[<img src='https://addons.mozilla.org/user-media/addon_icons/782/782160-64.png' width='16' height='16' alt='icon' /> Firefox Multi-Account Containers](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)** - Firefox Multi-Account Containers lets you keep parts of your online life separated into
color-coded tabs that preserve your privacy. Cookies are separated by container, allowing
you to use the web with multiple identities or accounts simultaneously. **Download**:
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)
 	- [![GitHub: mozilla/multi-account-containers](https://img.shields.io/github/stars/mozilla/multi-account-containers?style=flat&logo=github&label=multi-account-containers&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mozilla/multi-account-containers)
- **[<img src='https://lh3.googleusercontent.com/n4XZC3SfmhMnrIwR1256Cmx5d51OaJImxBtJqaTQnNuWD7xqAgGI2LmAXQk6O1CffLzFNSiTqIO-ZxMCJIGTuKcG=s60' width='16' height='16' alt='icon' /> WebRTC-Leak-Prevent](https://diafygi.github.io/webrtc-ips)** - Provides user control over WebRTC privacy settings in Chromium, in order to prevent WebRTC leaks.
**Download**: [Chrome](https://chrome.google.com/webstore/detail/webrtc-leak-prevent/eiadekoaikejlgdbkbdfeijglgfdalml?hl=en-GB).
For Firefox users, you can do this through [browser settings](https://www.privacytools.io/browsers/#webrtc).
Test for WebRTC leaks, with [browserleaks.com/webrtc](https://browserleaks.com/webrtc)
 	- [![GitHub: aghorler/WebRTC-Leak-Prevent](https://img.shields.io/github/stars/aghorler/WebRTC-Leak-Prevent?style=flat&logo=github&label=WebRTC-Leak-Prevent&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/aghorler/WebRTC-Leak-Prevent)
- **[<img src='https://cdn.webextension.org/icons/canvas-fingerprint-blocker128.png' width='16' height='16' alt='icon' /> Canvas Fingerprint Blocker](https://add0n.com/canvas-fingerprint-blocker.html)** - Block fingerprint without removing access to HTML5 Canvas element. Canvas fingerprinting is
commonly used for tracking, this extension helps to mitigate this through disallowing the browser
to generate a true unique key **Download**: [Chrome](https://chrome.google.com/webstore/detail/canvas-blocker-fingerprin/nomnklagbgmgghhjidfhnoelnjfndfpd) -
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/canvas-blocker-no-fingerprint/) -
[Edge](https://microsoftedge.microsoft.com/addons/detail/ahiddppepedlomdleppkbljnmkchlmdc)
 	- [![GitHub: joue-quroi/canvas-fingerprint-blocker](https://img.shields.io/github/stars/joue-quroi/canvas-fingerprint-blocker?style=flat&logo=github&label=canvas-fingerprint-blocker&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/joue-quroi/canvas-fingerprint-blocker)
- **[<img src='https://addons.mozilla.org/user-media/addon_icons/839/839767-64.png' width='16' height='16' alt='icon' /> ClearURLs](https://gitlab.com/KevinRoebert/ClearUrls)** - This extension will automatically remove tracking elements from the GET parameters of URLs to
help protect some privacy **Download**: [Chrome](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk) -
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) / [Source](https://gitlab.com/KevinRoebert/ClearUrls)
 	- [![GitHub: ClearURLs/Addon](https://img.shields.io/github/stars/ClearURLs/Addon?style=flat&logo=github&label=Addon&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ClearURLs/Addon)
- **[<img src='https://www.mike-gualtieri.com/favicon.ico' width='16' height='16' alt='icon' /> CSS Exfil Protection](https://www.mike-gualtieri.com/css-exfil-vulnerability-tester)** - Sanitizes and blocks any CSS rules which may be designed to steal data, in order to guard against
Exfil attacks **Download**: [Chrome](https://chrome.google.com/webstore/detail/css-exfil-protection/ibeemfhcbbikonfajhamlkdgedmekifo) -
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/css-exfil-protection/) - [Source](https://github.com/mlgualtieri/CSS-Exfil-Protection)
 	- [![GitHub: mlgualtieri/CSS-Exfil-Protection](https://img.shields.io/github/stars/mlgualtieri/CSS-Exfil-Protection?style=flat&logo=github&label=CSS-Exfil-Protection&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mlgualtieri/CSS-Exfil-Protection)
- **[<img src='https://addons.mozilla.org/user-media/addon_icons/865/865865-64.png?modified=1520892249' width='16' height='16' alt='icon' /> First Party Isolation](https://github.com/mozfreddyb/webext-firstpartyisolation)** - Enables the First Party isolation preference (Clicking the Fishbowl icon temporarily disables it)
**Download**: [Firefox](https://addons.mozilla.org/en-US/firefox/addon/first-party-isolation/)
 	- [![GitHub: mozfreddyb/webext-firstpartyisolation](https://img.shields.io/github/stars/mozfreddyb/webext-firstpartyisolation?style=flat&logo=github&label=webext-firstpartyisolation&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mozfreddyb/webext-firstpartyisolation)
- **[<img src='https://addons.mozilla.org/user-media/addon_icons/1012/1012731-64.png?modified=e97aa3af' width='16' height='16' alt='icon' /> Privacy-Oriented Origin Policy](https://claustromaniac.github.io/poop)** - Prevent Firefox from sending Origin headers when they are least likely to be necessary, to protect
your privacy **Download**: [Firefox](https://addons.mozilla.org/en-US/firefox/addon/privacy-oriented-origin-policy/) -
[Source](https://github.com/claustromaniac/poop)
 	- [![GitHub: claustromaniac/poop](https://img.shields.io/github/stars/claustromaniac/poop?style=flat&logo=github&label=poop&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/claustromaniac/poop)
- **[<img src='https://codeberg.org/repo-avatars/5014-6cc14ee9c85003bda3adb1d71762c306' width='16' height='16' alt='icon' /> LocalCDN](https://www.localcdn.org/)** - Emulates remote frameworks (e.g. jQuery, Bootstrap, Angular) and delivers them as local resource.
Prevents unnecessary 3rd party requests to tracking CDNs **Download**: [Firefox](https://addons.mozilla.org/en-US/firefox/addon/localcdn-fork-of-decentraleyes/)
 - **[<img src='https://addons.mozilla.org/user-media/addon_icons/521/521554-64.png' width='16' height='16' alt='icon' /> Decentraleyes](https://decentraleyes.org)** - Similar to LocalCDN, Serves up local versions of common scripts instead of calling to 3rd-party CDN.
Improves privacy and load times. Works out-of-the-box and plays nicely with regular content blockers.
**Download**: [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) -
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes) -
[Opera](https://addons.opera.com/en/extensions/details/decentraleyes) -
[Pale Moon](https://addons.palemoon.org/addon/decentraleyes) -
[Source](https://git.synz.io/Synzvato/decentraleyes)
 - **[<img src='https://avatars.githubusercontent.com/u/342708' width='16' height='16' alt='icon' /> Privacy Essentials](https://duckduckgo.com/app)** - Simple extension by DuckDuckGo, which grades the security of each site. **Download**:
[Chrome](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflcldnnnapblkhphbgpggdiikppg?hl=en-GB) \
[Firefox](https://addons.mozilla.org/en-GB/firefox/addon/duckduckgo-for-firefox/)
 	- [![GitHub: duckduckgo/duckduckgo-privacy-extension](https://img.shields.io/github/stars/duckduckgo/duckduckgo-privacy-extension?style=flat&logo=github&label=duckduckgo-privacy-extension&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/duckduckgo/duckduckgo-privacy-extension)
- **[<img src='https://i.ibb.co/1T06gbX/self-destructing-cookies128.png' width='16' height='16' alt='icon' /> Self-Destructing Cookies](https://add0n.com/self-destructing-cookies.html)** - Prevents websites from tracking you by storing unique cookies (note Fingerprinting is often also used for tracking).
It removes all related cookies whenever you end a session. **Download**:
[Chrome](https://chrome.google.com/webstore/detail/self-destructing-cookies/igdpjhaninpfanncfifdoogibpdidddf) -
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/self-destructing-cookies-webex/) -
[Opera](https://addons.opera.com/en/extensions/details/self-destructing-cookies/) -
[Source](https://github.com/joue-quroi/self-destructing-cookies)
 	- [![GitHub: joue-quroi/self-destructing-cookies](https://img.shields.io/github/stars/joue-quroi/self-destructing-cookies?style=flat&logo=github&label=self-destructing-cookies&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/joue-quroi/self-destructing-cookies)
- **[<img src='https://lh3.googleusercontent.com/pC5a_u12RlaLQhJ-5Jz87rtju2s0tCksUfZHvr3JYzAaiYZJfJapmuftodT7wuAedFOHtgxR2BGh_GmKijgiK5bJyA' width='16' height='16' alt='icon' /> Privacy Redirect](https://github.com/SimonBrazell/privacy-redirect)** - A simple web extension that redirects Twitter, YouTube, Instagram & Google Maps requests to privacy friendly alternatives
**Download**: [Firefox](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect/) - [Chrome](https://chrome.google.com/webstore/detail/privacy-redirect/pmcmeagblkinmogikoikkdjiligflglb)
 	- [![GitHub: SimonBrazell/privacy-redirect](https://img.shields.io/github/stars/SimonBrazell/privacy-redirect?style=flat&logo=github&label=privacy-redirect&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/SimonBrazell/privacy-redirect)
- **[<img src='https://lh3.googleusercontent.com/a2Vje7WEAiLb8NwUY43hyzhTXrQllBc4qP3ymqZdoBEaT8ME98dMzRpFNx0fI5w998jIUaJozj5KeNLTiJBEwe4O' width='16' height='16' alt='icon' /> Site Bleacher](https://github.com/wooque/site-bleacher)** - Remove automatically cookies, local storages, IndexedDBs and service workers **Download**:
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/site-bleacher/) -
[Chrome](https://chrome.google.com/webstore/detail/site-bleacher/mlcfcepfmnjphcdkfbfgokkjodlkmemo) -
[Source](https://github.com/wooque/site-bleacher)
 	- [![GitHub: wooque/site-bleacher](https://img.shields.io/github/stars/wooque/site-bleacher?style=flat&logo=github&label=site-bleacher&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/wooque/site-bleacher)
- **[<img src='https://i.ibb.co/hyb1SGK/useragent-switcher128.png' width='16' height='16' alt='icon' /> User Agent Switcher](https://add0n.com/useragent-switcher.html)** - Spoofs browser's User-Agent string, making it appear that you are on a different device, browser and version to
what you are actually using. This alone does very little for privacy, but combined with other tools, can allow you
to keep your fingerprint changing, and feed fake info to sites tracking you. Some websites show different content,
depending on your user agent. **Download**:
[Chrome](https://chrome.google.com/webstore/detail/user-agent-switcher/bhchdcejhohfmigjafbampogmaanbfkg) -
[Firefox](https://addons.mozilla.org/firefox/addon/user-agent-string-switcher/) -
[Edge](https://microsoftedge.microsoft.com/addons/detail/cnjkedgepfdpdbnepgmajmmjdjkjnifa) -
[Opera](https://addons.opera.com/extensions/details/user-agent-switcher-8/) -
[Source](https://github.com/ray-lothian/UserAgent-Switcher/)
 	- [![GitHub: ray-lothian/UserAgent-Switcher](https://img.shields.io/github/stars/ray-lothian/UserAgent-Switcher?style=flat&logo=github&label=UserAgent-Switcher&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ray-lothian/UserAgent-Switcher)
- **[<img src='https://privacyspy.org/static/img/favicon-32x32.png' width='16' height='16' alt='icon' /> PrivacySpy](https://privacyspy.org)** - The companion extension for PrivacySpy.org - an open project that rates, annotates, and archives privacy policies.
The extension shows a score for the privacy policy of the current website. **Download**:
[Chrome](https://chrome.google.com/webstore/detail/privacyspy/ppembnadnhiknioggbglgiciihgmkmnd) -
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/privacyspy/)
 	- [![GitHub: politiwatch/privacyspy](https://img.shields.io/github/stars/politiwatch/privacyspy?style=flat&logo=github&label=privacyspy&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/politiwatch/privacyspy)
- **[<img src='https://addons.mozilla.org/user-media/addon_icons/1018/1018256-64.png?modified=9b273331' width='16' height='16' alt='icon' /> HTTPZ](https://github.com/claustromaniac/httpz)** - Simplified HTTPS upgrades for Firefox (lightweight alternative to HTTPS-Everywhere) **Download**:
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/httpz/)
 	- [![GitHub: claustromaniac/httpz](https://img.shields.io/github/stars/claustromaniac/httpz?style=flat&logo=github&label=httpz&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/claustromaniac/httpz)
- **[<img src='https://addons.mozilla.org/user-media/addon_icons/642/642100-64.png?modified=1597226821' width='16' height='16' alt='icon' /> Skip Redirect](https://github.com/sblask/webextension-skip-redirect)** - Some web pages use intermediary pages before redirecting to a final page. This add-on tries to extract the final url
from the intermediary url and goes there straight away if successful **Download**:
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/skip-redirect/) -
[Source](https://github.com/sblask/webextension-skip-redirect)
 	- [![GitHub: sblask/webextension-skip-redirect](https://img.shields.io/github/stars/sblask/webextension-skip-redirect?style=flat&logo=github&label=webextension-skip-redirect&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/sblask/webextension-skip-redirect)
- **[<img src='https://i.imgur.com/H9zwf8l.png' width='16' height='16' alt='icon' /> Web Archives](https://github.com/dessant/web-archives)** - View archived and cached versions of web pages on 10+ search engines, such as the Wayback Machine, Archive.is, Google etc
Useful for checking legitimacy of websites, and viewing change logs **Download**:
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/view-page-archive/) -
[Chrome](https://chrome.google.com/webstore/detail/web-archives/hkligngkgcpcolhcnkgccglchdafcnao) -
[Edge](https://microsoftedge.microsoft.com/addons/detail/apcfghlggldjdjepjnahfdjgdcdekhda) -
[Source](https://github.com/dessant/web-archives)
 	- [![GitHub: dessant/web-archives](https://img.shields.io/github/stars/dessant/web-archives?style=flat&logo=github&label=web-archives&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/dessant/web-archives)
- **[<img src='https://flagfox.files.wordpress.com/2014/02/flagfoxlogowithname1.png' width='16' height='16' alt='icon' /> Flagfox](https://flagfox.wordpress.com/)** - Displays a country flag depicting the location of the current website's server, which can be useful to know at a glance.
Click icon for more tools such as site safety checks, whois, validation etc **Download**:
[Firefox](https://addons.mozilla.org/en-US/firefox/addon/flagfox/)
 - **[<img src='https://mozilla.github.io/lightbeam/img/lightbeam_logo-only_32x32.png' width='16' height='16' alt='icon' /> Lightbeam](https://mozilla.github.io/lightbeam/)** - Visualize in detail the servers you are contacting when you are surfing on the Internet. Created by Gary Kovacs (former CEO of Mozilla), presented in his [TED Talk](https://www.ted.com/talks/gary_kovacs_tracking_our_online_trackers). **Download**: [Firefox](https://addons.mozilla.org/en-US/firefox/addon/lightbeam-3-0/) - [Source](https://github.com/mozilla/lightbeam-we)
 	- [![GitHub: mozilla/lightbeam-we](https://img.shields.io/github/stars/mozilla/lightbeam-we?style=flat&logo=github&label=lightbeam-we&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mozilla/lightbeam-we)
- **[<img src='https://static.wixstatic.com/media/654565_824403a4d02548d783f8ca81f9e6bf48~mv2.png/v1/fill/w_268,h_264,al_c,q_85,usm_0.66_1.00_0.01,enc_auto/Logo_Button_TMN.png' width='16' height='16' alt='icon' /> Track Me Not](http://trackmenot.io)** - Helps protect web searchers from surveillance and data-profiling, through creating meaningless noise and obfuscation, outlined in their [whitepaper](http://trackmenot.io/resources/trackmenot2009.pdf). Controversial whether or not this is a good approach **Download**: [Firefox](https://addons.mozilla.org/en-US/firefox/addon/trackmenot/) - [Source](https://github.com/vtoubiana/TrackMeNot)
 	- [![GitHub: vtoubiana/TrackMeNot](https://img.shields.io/github/stars/vtoubiana/TrackMeNot?style=flat&logo=github&label=TrackMeNot&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/vtoubiana/TrackMeNot)
- **[<img src='https://amiunique.org/favicon.ico' width='16' height='16' alt='icon' /> AmIUnique Timeline](https://amiunique.org/timeline)** - Enables you to better understand the evolution of browser fingerprints (which is what websites use to uniquely identify and track you). **Download**: [Chrome](https://chrome.google.com/webstore/detail/amiunique/pigjfndpomdldkmoaiiigpbncemhjeca) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/amiunique)
 - **[<img src='https://lh3.googleusercontent.com/c78SvSl7OD2thLmgX5irlo1tvxGVtkziKTKmp7VByjvvrw2czkP2cFbbRASmopQBV9-PpNBD_NOqt8WIC4JVc0WB3A=s60' width='16' height='16' alt='icon' /> Netcraft Extension](https://www.netcraft.com/apps/browser)** - Notifies you when visiting a known or potential phishing site, and detects suspicious JavaScript (including skimmers and miners). Also provides a simple rating for a given site's legitimacy and security. Great for less technical users. Netcraft also has a handy online tool: [Site Report](https://sitereport.netcraft.com/) for checking what any given website is running. **Download**: [Chrome](https://chrome.google.com/webstore/detail/netcraft-anti-phishing-ex/bmejphbfclcpmpohkggcjeibfilpamia) \ [Firefox](https://addons.mozilla.org/en-us/firefox/addon/netcraft-toolbar?src=external-apps-hero) \ [Opera](https://addons.opera.com/en/extensions/details/netcraft-anti-phishing-extension/) \ [Edge](https://microsoftedge.microsoft.com/addons/detail/netcraft-extension/ngjhgbnmdjjnmejmpamalgnlnmopllkm)
 - **[<img src='https://icon.horse/icon/eff.org' width='16' height='16' alt='icon' /> HTTPS Everywhere](https://eff.org/https-everywhere)** - **NOTE** On modern browsers, this is [no longer needed](https://www.eff.org/deeplinks/2021/09/https-actually-everywhere)
Forces sites to load in HTTPS, in order to encrypt your communications with websites,
making your browsing more secure (Similar to [Smart HTTPS](https://mybrowseraddon.com/smart-https.html)).
Note this functionality is now included by default in most modern browsers. **Download**:
[Chrome](https://www.eff.org/https-everywhere) \
[Firefox](https://www.eff.org/files/https-everywhere-latest.xpi)
 	- [![GitHub: EFForg/https-everywhere](https://img.shields.io/github/stars/EFForg/https-everywhere?style=flat&logo=github&label=https-everywhere&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/EFForg/https-everywhere)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> - Having many extensions installed raises entropy, causing your fingerprint to be more unique, hence making tracking easier.
- Much of the functionality of the above addons can be applied without installing anything, by configuring browser settings yourself. For Firefox this is done in the user.js
- Be careful when installing unfamiliar browser add-ons, since some can compromise your security and privacy. At the time of writing, the above list were all open source, verified and 'safe' extensions.
- In most situations, only a few of the above extensions will be needed in combination.
- See the [arkenfox wiki](https://github.com/arkenfox/user.js/wiki/4.1-Extensions) for more information on the obsolescence and purposelessness of many popular extensions, and why you may only need a very limited set.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [Extension source viewer](https://addons.mozilla.org/en-US/firefox/addon/crxviewer) - A handy extension for viewing the source code of another browser extension, which is a useful tool for verifying the code does what it says 
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Mobile Apps

- **[<img src='https://play-lh.googleusercontent.com/dIIbpr1fh-w7ykJJmfLyu6UH1HJ8bpFKEmyUlKqYHSEinG8v_B7mlqgeTzlFRhs0Uw=s48' width='16' height='16' alt='icon' /> Orbot](https://support.torproject.org/glossary/orbot/)** - System-wide Tor proxy, which encrypts your connection through multiple nodes.
You can also use it alongside Tor Browser to access .onion sites.
 	- [![GitHub: guardianproject/orbot](https://img.shields.io/github/stars/guardianproject/orbot?style=flat&logo=github&label=orbot&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/guardianproject/orbot)
- **[<img src='https://play-lh.googleusercontent.com/XEd1PsXgOSNNpD2hlZMvigIOJ9e5JCL2KhCJ4X984Az5EFw6YiecDebqdsZ12VNU2kPu=w240-h480' width='16' height='16' alt='icon' /> NetGuard](https://netguard.me/)** - A firewall app for Android, which does not require root. NetGuard provides simple
and advanced ways to block access to the internet, where applications and addresses
can individually be allowed or denied access to your Wi-Fi and/or mobile connection.
 	- [![GitHub: M66B/NetGuard](https://img.shields.io/github/stars/M66B/NetGuard?style=flat&logo=github&label=NetGuard&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/M66B/NetGuard)
- **[<img src='https://play-lh.googleusercontent.com/ywvaxXcH90yttClJvgHR5UsfDnGS_YNtFiW6fQJm1p7_6HX9Dbn0v2J9gIzOOKFYQOnA=w240-h480' width='16' height='16' alt='icon' /> Island](https://island.oasisfeng.com/)** - A sandbox environment, allowing you to clone selected apps and run them in an isolated
box, preventing it from accessing your personal data, or device information.
 	- [![GitHub: oasisfeng/island](https://img.shields.io/github/stars/oasisfeng/island?style=flat&logo=github&label=island&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/oasisfeng/island)
- **[<img src='https://gitlab.com/uploads/-/system/project/avatar/18237274/ic_launcher-playstore.png?width=48' width='16' height='16' alt='icon' /> Insular](https://gitlab.com/secure-system/Insular)** - An actively-maintained fork of the Island project with additional enhancements
 	- [![GitHub: oasisfeng/island](https://img.shields.io/github/stars/oasisfeng/island?style=flat&logo=github&label=island&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/oasisfeng/island)
- **[<img src='https://exodus-privacy.eu.org/media/logo/exodus.png' width='16' height='16' alt='icon' /> Exodus](https://exodus-privacy.eu.org/en/page/what/#android-app)** - Shows which trackers, each of your installed apps is using, so that you can better
understand how your data is being collected. Uses data from the Exodus database of scanned APKs.
 - **[<img src='https://play-lh.googleusercontent.com/QbgM-Vgqp32sNMgwC0kD4kJW3YVp7xiPcVIHNcbSQgrkTIDqSfTqSBXKEvoZ9SNSjxw=w240-h480' width='16' height='16' alt='icon' /> Bouncer](https://play.google.com/store/apps/details?id=com.samruston.permission)** - Gives you the ability to grant permissions temporarily, so that you could for example
use the camera to take a profile picture, but when you close the given app, those permissions
will be revoked.
 - **[<img src='https://raw.githubusercontent.com/M66B/XPrivacyLua/master/app/src/main/ic_launcher-web.png' width='16' height='16' alt='icon' /> XPrivacyLua](https://lua.xprivacy.eu/)** - Simple to use privacy manager for Android, that enables you to feed apps fake data when
they request intimate permissions. Solves the problem caused by apps malfunctioning when
you revoke permissions, and protects your real data by only sharing fake information. Enables
you to hide call log, calendar, SMS messages, location, installed apps, photos, clipboard,
network data plus more. And prevents access to camera, microphone, telemetry, GPS and other sensors.
 	- [![GitHub: M66B/XPrivacyLua](https://img.shields.io/github/stars/M66B/XPrivacyLua?style=flat&logo=github&label=XPrivacyLua&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/M66B/XPrivacyLua)
- **[<img src='https://f-droid.org/repo/icons-640/superfreeze.tool.android.1000.png' width='16' height='16' alt='icon' /> SuperFreezZ](https://superfreezz.gitlab.io/)** - Makes it possible to entirely freeze all background activities on a per-app basis.
Intended purpose is to speed up your phone, and prolong battery life, but this app is
also a great utility to stop certain apps from collecting data and tracking your actions
while running in the background. See on [F-Droid](https://f-droid.org/en/packages/superfreeze.tool.android)
 - **[<img src='https://play-lh.googleusercontent.com/PdE-P3oTwa6fFKqQrSuYS1S7Aa_bIq-GECLhj8kvTzXdSc6S_hUtW2hUx0aCP-3h0pQ=w240-h480' width='16' height='16' alt='icon' /> Haven](https://guardianproject.github.io/haven/)** - Allows you to protect yourself, your personal space and your possessions - without
compromising on security. Leveraging device sensors to monitor nearby space, Haven was
developed by The Guardian Project, in partnership with Edward Snowden.
 	- [![GitHub: guardianproject/haven](https://img.shields.io/github/stars/guardianproject/haven?style=flat&logo=github&label=haven&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/guardianproject/haven)
- **[<img src='https://play-lh.googleusercontent.com/Xb_KbjGC3J8xrj1QmZqYhUq1A6aww5ikFuXfCqJonww-vz38y6xUjHzvH65AGrQU9P4=s48' width='16' height='16' alt='icon' /> Secure Task](https://play.google.com/store/apps/details?id=com.balda.securetask)** - Triggers actions, when certain security conditions are met, such as multiple failed login
attempts or monitor settings changed. It does require Tasker, and needs to be set up with
ADB, device does not need to be rooted.
 - **[<img src='https://avatars.githubusercontent.com/u/11850518?s=200&v=4' width='16' height='16' alt='icon' /> Cryptomator](https://cryptomator.org/android/)** - Encrypts files and folders client-side, before uploading them to cloud storage (such as Google
Drive, One Drive or Dropbox), meaning none of your personal documents leave your device in plain text.
 	- [![GitHub: cryptomator/android](https://img.shields.io/github/stars/cryptomator/android?style=flat&logo=github&label=android&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/cryptomator/android)
- **[<img src='https://1.1.1.1/favicon.ico' width='16' height='16' alt='icon' /> 1.1.1.1](https://1.1.1.1/)** - Lets you use CloudFlares fast and secure 1.1.1.1 DNS, with DNS over HTTPS, and also has the option
to enable CloudFlares WARP+ VPN.
 - **[<img src='https://avatars.githubusercontent.com/u/62335928?s=200&v=4' width='16' height='16' alt='icon' /> Fing App](https://www.fing.com/products/fing-app)** - A network scanner to help you monitor and secure your WiFi network. The app is totally free,
but to use the advanced controls, you will need a Fing Box.
 - **[<img src='https://raw.githubusercontent.com/nomoresat/DPITunnel-android/main/assets/logo.webp' width='16' height='16' alt='icon' /> DPI Tunnel](https://f-droid.org/packages/ru.evgeniy.dpitunnelcli/)** - An application for Android that uses various techniques to bypass DPI (Deep Packet Inspection)
systems, which are used to block some sites (not available on Play store).
 	- [![GitHub: nomoresat/DPITunnel-android](https://img.shields.io/github/stars/nomoresat/DPITunnel-android?style=flat&logo=github&label=DPITunnel-android&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/nomoresat/DPITunnel-android)
- **[<img src='https://blokada.org/favicon.png' width='16' height='16' alt='icon' /> Blokada](https://blokada.org/)** - This application blocks ads and trackers, doesn't require root and works for all the apps on your
Android phone. Check out how it works here.
 	- [![GitHub: blokadaorg/blokada](https://img.shields.io/github/stars/blokadaorg/blokada?style=flat&logo=github&label=blokada&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/blokadaorg/blokada)
- **[<img src='https://f-droid.org/repo/icons-640/de.srlabs.snoopsnitch.50.png' width='16' height='16' alt='icon' /> SnoopSnitch](https://opensource.srlabs.de/projects/snoopsnitch)** - Collects and analyzes mobile radio data to make you aware of your mobile network security and to
warn you about threats like fake base stations (IMSI catchers), user tracking and over-the-air updates.
Get from [F-Droid](https://f-droid.org/en/packages/de.srlabs.snoopsnitch/)
 	- [![GitHub: srlabs/snoopsnitch](https://img.shields.io/github/stars/srlabs/snoopsnitch?style=flat&logo=github&label=snoopsnitch&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/srlabs/snoopsnitch)
- **[<img src='https://trackercontrol.org/images/logo.png' width='16' height='16' alt='icon' /> TrackerControl](https://trackercontrol.org/)** - Monitor and control hidden data collection in mobile apps about user behavior/ tracking.
Get from [F-Droid](https://f-droid.org/en/packages/net.kollnig.missioncontrol.fdroid/)
 	- [![GitHub: TrackerControl/tracker-control-android](https://img.shields.io/github/stars/TrackerControl/tracker-control-android?style=flat&logo=github&label=tracker-control-android&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/TrackerControl/tracker-control-android)
- **[<img src='https://f-droid.org/repo/com.smilla.greentooth/en-US/icon_8WaREJ2f7uFLdL9QGDL4xSqsIRB7wgdwv9BY_ET0WEg=.png' width='16' height='16' alt='icon' /> Greentooth](https://gitlab.com/nbergman/greentooth)** - Auto-disable Bluetooth, then it is not being used. Saves battery, and prevent some security risks.
Get from [F-Droid](https://f-droid.org/en/packages/com.smilla.greentooth/)
 - **[<img src='https://f-droid.org/repo/com.wesaphzt.privatelock/en-US/icon_c5gFGZ7VhAR-kLihEfLVrStxIushKtWADc7pR1hQ6b4=.png' width='16' height='16' alt='icon' /> PrivateLock](https://github.com/wesaphzt/privatelock)** - Auto lock your phone based on movement force/ acceleration.
Get from [F-Droid](https://f-droid.org/en/packages/com.wesaphzt.privatelock/)
See also [PluckLock](https://github.com/SyntaxBlitz/PluckLock)
 	- [![GitHub: wesaphzt/privatelock](https://img.shields.io/github/stars/wesaphzt/privatelock?style=flat&logo=github&label=privatelock&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/wesaphzt/privatelock)
- **[<img src='https://schiffer.tech/img/logo.png' width='16' height='16' alt='icon' /> CamWings](https://schiffer.tech/camwings-mobile.html)** - Prevent background processes gaining unauthorized access to your devices camera. Better still,
use a webcam sticker.
 - **[<img src='https://schiffer.tech/img/logo.png' width='16' height='16' alt='icon' /> ScreenWings](https://schiffer.tech/screenwings-mobile.html)** - Prevent background processes taking unauthorized screenshots, which could expose sensitive data.
 - **[<img src='https://play-lh.googleusercontent.com/LGMnS6aiFUxTLMlDQ4VYaJG0V2lY3lr_ru9QZ3OiCp-YZlsCz3F_v0oWQnqrN-giBA=s48' width='16' height='16' alt='icon' /> AFWall+](https://github.com/ukanth/afwall/)** - Android Firewall+ (AFWall+) is an advanced iptables editor (GUI) for rooted Android devices,
which provides very fine-grained control over which Android apps are allowed to access the network.
Get from [F-Droid](https://f-droid.org/packages/dev.ukanth.ufirewall/)
 	- [![GitHub: ukanth/afwall](https://img.shields.io/github/stars/ukanth/afwall?style=flat&logo=github&label=afwall&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ukanth/afwall)
- **[<img src='https://play-lh.googleusercontent.com/hMhLdDNBR_rBIDctJ5yCPbyPy0fi_6FHp9MdgaOIPPedyqgwr6tsZq_AO3W1z4Zb8HJ_=w240-h480' width='16' height='16' alt='icon' /> Catch the Man-in-the-Middle](https://play.google.com/store/apps/details?id=me.brax.certchecker)** - Simple tool, that compares SHA-1 fingerprints of the the SSL certificates seen from your device,
and the certificate seen from an external network. If they do not match, this may indicate a
man-in-the-middle modifying requests.
 - **[<img src='https://f-droid.org/repo/com.celzero.bravedns/en-US/icon_AwgyVcHjczoaNxANCvUeSJrEfOWsIIeIpCgBaUKoXuY=.png' width='16' height='16' alt='icon' /> RethinkDNS + Firewall](https://rethinkdns.com/app)** - An open-source ad-blocker and firewall app for Android 6+ (does not require root).
 	- [![GitHub: celzero/rethink-app](https://img.shields.io/github/stars/celzero/rethink-app?style=flat&logo=github&label=rethink-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/celzero/rethink-app)
- **[<img src='https://f-droid.org/assets/apple-touch-icon_ypJwtCrcixeH_qV6LdcMYk1anFIR9o-_ufR__1wNdJY=.png' width='16' height='16' alt='icon' /> F-Droid](https://f-droid.org/)** - F-Droid is an installable catalogue of FOSS applications for Android. The client enables you
to browse, install, and keep track of updates on your device.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Too many installed apps will increase your attack surface - only install applications that you need.
Be sure to check the permissions, and what data an app has access to prior to installation.
Only install from official sources.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> For more open source security & privacy apps, check out these publishers:
> [The Guardian Project](https://play.google.com/store/apps/dev?id=6502754515281796553),
> [The Tor Project](https://play.google.com/store/apps/developer?id=The+Tor+Project),
> [Oasis Feng](https://play.google.com/store/apps/dev?id=7664242523989527886),
> [Marcel Bokhorst](https://play.google.com/store/apps/dev?id=8420080860664580239),
> [SECUSO Research Group]( https://play.google.com/store/apps/developer?id=SECUSO+Research+Group&hl=en_US)
> and [Simple Mobile Tools](https://play.google.com/store/apps/dev?id=9070296388022589266) -
> all of which are trusted developers or organisations, who've done amazing work.
> 
> For offensive and defensive security, see
> The Kali [Nethunter Catalogue](https://store.nethunter.com/en/packages) of apps
> 
> For *advanced* users, the following tools can be used to closely monitor
> your devise and networks, in order to detect any unusual activity.
> [PortDroid] for network analysis, [Packet Capture] to monitor network
> traffic, [SysLog] for viewing system logs, [Dexplorer] to read .dex or .apk files
> for your installed apps, and [Check and Test] to check status and details of devices hardware.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Online Tools

A selection of free online tools and utilities, to check, test and protect your security

- **[<img src='https://haveibeenpwned.com/favicon.ico' width='16' height='16' alt='icon' /> Have i been pwned](https://haveibeenpwned.com)** - Checks if your credentials (Email address or Password) have been compromised in a data breach.
See also Firefox Monitor.
 - **[<img src='https://i.ibb.co/Vvq8XrM/Exodus.png' width='16' height='16' alt='icon' /> εxodus](https://reports.exodus-privacy.eu.org)** - Checks how many, and which trackers any Android app has. Useful to understand how data is being
collected before you install a certain APK, it also shows which permissions the app asks for.
 	- [![GitHub: Exodus-Privacy/website](https://img.shields.io/github/stars/Exodus-Privacy/website?style=flat&logo=github&label=website&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Exodus-Privacy/website)
- **[<img src='https://amiunique.org/favicon.ico' width='16' height='16' alt='icon' /> Am I Unique?](https://amiunique.org/fingerprint)** - Show how identifiable you are on the Internet by generating a fingerprint based on device information.
This is how many websites track you (even without cookies enabled), so the aim is to not be unique.
 - **[<img src='https://coveryourtracks.eff.org/static/favicon.ico' width='16' height='16' alt='icon' /> Panopticlick](https://panopticlick.eff.org/)** - Check if your browser safe against tracking. Analyzes how well your browser and add-ons protect you
against online tracking techniques, and if your system is uniquely configured—and thus identifiable.
 	- [![GitHub: EFForg/cover-your-tracks](https://img.shields.io/github/stars/EFForg/cover-your-tracks?style=flat&logo=github&label=cover-your-tracks&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/EFForg/cover-your-tracks)
- **[<img src='https://phish.ly/images/logo.svg' width='16' height='16' alt='icon' /> Phish.ly](https://phish.ly/)** - Analyzes emails, checking the URLs and creating a SHA256 and MD5 hash of attachments, with a link to VirusTotal.
To use the service, just forward a potentially malicious or suspicious email to scan@phish.ly, and an automated
reply will include the results. They claim that all email data is purged after analysis, but it would be wise to
not include any sensitive information, and to use a forwarding address.
 - **[<img src='https://browserleaks.com/favicon.ico' width='16' height='16' alt='icon' /> Browser Leak Test](https://browserleaks.com)** - Shows which of personal identity data is being leaked through your browser, so you can better protect yourself
against fingerprinting.
 - **[<img src='https://ipleak.net/favicon.ico' width='16' height='16' alt='icon' /> IP Leak Test](https://ipleak.net)** - Shows your IP address, and other associated details (location, ISP, WebRTC check, DNS, and lots more).
 - **[<img src='https://www.exifremove.com/favicon.ico' width='16' height='16' alt='icon' /> EXIF Remove](https://www.exifremove.com)** - Displays, and removes Meta and EXIF data from an uploaded photo or document.
 - **[<img src='https://redirectdetective.com/redirect-detective.png' width='16' height='16' alt='icon' /> Redirect Detective](https://redirectdetective.com)** - Check where a suspicious URL redirects to (without having to click it). Lets you avoid being tracked by not being
redirected via adware/tracking sites, or see if a shortened link actually resolves a legitimate site, or see if
link is an affiliate ad.
 - **[<img src='https://www.blocked.org.uk/assets/images/blocked/socialmedia/blocked_result.jpg' width='16' height='16' alt='icon' /> Blocked.org](https://www.blocked.org.uk)** - Checks if a given website is blocked by filters applied by your mobile and broadband Internet Service Providers (ISP).
 - **[<img src='https://www.virustotal.com/gui/images/manifest/icon-192x192.png' width='16' height='16' alt='icon' /> Virus Total](https://www.virustotal.com)** - Analyses a potentially-suspicious web resources (by URL, IP, domain or file hash) to detect types of malware
(*note: files are scanned publicly*).
 - **[<img src='https://www.hardenize.com/favicon/android-chrome-192x192.png' width='16' height='16' alt='icon' /> Hardenize](https://www.hardenize.com/)** - Scan websites and shows a security overview, relating to factors such as HTTPS, domain info, email data, www protocols
and so on.
 - **[<img src='https://www.islegitsite.com/apple-touch-icon.png' width='16' height='16' alt='icon' /> Is Legit?](https://www.islegitsite.com/)** - Checks if a website or business is a scam, before buying something from it.
 - **[<img src='https://www.shouldiremoveit.com/favicon.ico' width='16' height='16' alt='icon' /> Should I Remove It?](https://www.shouldiremoveit.com)** - Ever been uninstalling programs from your Windows PC and been unsure of what something is? Should I Remove It is a
database of Windows software, detailing whether it is essential, harmless or dangerous.
 - **[<img src='https://10minemail.com/favicon.ico' width='16' height='16' alt='icon' /> 10 Minute Mail](https://10minemail.com/)** - Generates temporary disposable email address, to avoid giving your real details.
 - **[<img src='https://mxtoolbox.com/favicon.ico' width='16' height='16' alt='icon' /> MXToolBox Mail Headers](https://mxtoolbox.com/Public/Tools/EmailHeaders.aspx)** - Tool for analyzing email headers, useful for checking the authenticity of messages, as well as knowing what info
you are revealing in your outbound messages.
 - **[<img src='https://amifloced.org/favicon.ico' width='16' height='16' alt='icon' /> Am I FloCed?](https://amifloced.org/)** - Google testing out a new tracking feature called Federated Learning of Cohorts (aka "FLoC"). It currently effects
0.5% of Chrome users, this tool developed by the EFF will detect if you are affected, and provide additional info
on how to stay protected.
 - **[<img src='https://static.netcraft.com/images/favicon.ico' width='16' height='16' alt='icon' /> Site Report](https://sitereport.netcraft.com/)** - A tool from Netcraft, for analysing what any given website is running, where it's located and information about its
host, registrar, IP and SSL certificates.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Browsers are inherently insecure, be careful when uploading, or entering personal details.


</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Networking

### Virtual Private Networks

- **[<img src='https://mullvad.net/apple-touch-icon.png' width='16' height='16' alt='icon' /> Mullvad](http://mullvad.net/en)** - Mullvad is one of the best for privacy, they have a totally anonymous sign up process,
you don't need to provide any details at all, you can choose to pay anonymously too
(with Monero, BTC or cash).
 	- [![GitHub: mullvad/mullvadvpn-app](https://img.shields.io/github/stars/mullvad/mullvadvpn-app?style=flat&logo=github&label=mullvadvpn-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mullvad/mullvadvpn-app)
- **[<img src='https://www.azirevpn.com/assets/img/apple-icon-57x57.png' width='16' height='16' alt='icon' /> Azire](https://www.azirevpn.com/)** - Azire is a Swedish VPN provider, who owns their own hardware with physically removed
storage and a no logging policy. Pricing starts at €3.25/mo, with crypto (including XMR)
supported. Note that they've not yet been audited, and client applications are not open
source, for more info, see #140.
 - **[<img src='https://avatars.githubusercontent.com/u/38857113' width='16' height='16' alt='icon' /> IVPN](https://www.ivpn.net/)** - Independently Security Audited VPN with anonymous signup, no logs, no cloud or customer
data stored, open-source apps and website. Strong ethics: no trackers, no false promises,
no surveillance ads. Accepts various payment methods including cryptocurrencies.
 	- [![GitHub: ivpn/desktop-app](https://img.shields.io/github/stars/ivpn/desktop-app?style=flat&logo=github&label=desktop-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ivpn/desktop-app)
- **[<img src='https://protonvpn.com/favicons/apple-touch-icon.png' width='16' height='16' alt='icon' /> ProtonVPN](https://protonvpn.com)** - From the creators of ProtonMail, ProtonVPN has a solid reputation. They have a full suite
of user-friendly native mobile and desktop apps. ProtonVPN is one of the few "trustworthy"
providers that also offer a free plan.
 	- [![GitHub: ProtonVPN/android-app](https://img.shields.io/github/stars/ProtonVPN/android-app?style=flat&logo=github&label=android-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ProtonVPN/android-app)
- **[<img src='https://www.ovpn.com/favicon.ico' width='16' height='16' alt='icon' /> OVPN](https://www.ovpn.com)** - A court-proven VPN service with support for Wireguard and OpenVPN support, and optional
ad-blocking. Running on dedicated hardware, with no hard drives.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> - *A VPN does not make you anonymous - it merely changes your public IP address to that of your VPN provider, instead of your ISP. Your browsing session can still be linked back to your real identity either through your system details (such as user agent, screen resolution even typing patterns), cookies / session storage, or by the identifiable data that you enter. [Read more about fingerprinting](https://pixelprivacy.com/resources/browser-fingerprinting/)*
- *Logging - If you choose to use a VPN because you do not agree with your ISP logging your full browsing history, then it is important to keep in mind that your VPN provider can see (and mess with) all your traffic. Many VPNs claim not to keep logs, but you cannot be certain of this ([VPN leaks](https://vpnleaks.com/)). See [this article](https://gist.github.com/joepie91/5a9909939e6ce7d09e29) for more*
- *IP Leaks - If configured incorrectly, your IP may be exposed through a DNS leak. This usually happens when your system is unknowingly accessing default DNS servers rather than the anonymous DNS servers assigned by an anonymity network or VPN. Read more: [What is a DNS leak](https://www.dnsleaktest.com/what-is-a-dns-leak.html), [DNS Leak Test](https://www.dnsleaktest.com), [How to Fix a DNS Leak](https://www.dnsleaktest.com/how-to-fix-a-dns-leak.html)*
- *Stealth - It will be visible to your adversary that you are using a VPN (usually from the IP address), but other system and browser data, can still reveal information about you and your device (such as your local time-zone, indicating which region you are operating from)*
- *Many reviews are sponsored, and hence biased. Do your own research, or go with one of the above options*
- *Using [Tor](https://www.torproject.org) (or another [Mix Network](/5_Privacy_Respecting_Software.md#mix-networks)) may be a better option for anonimity*


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> If you don't trust a VPN provider not to keep logs, then you could self-host your own VPN. This gives you you total control, but at the cost of anonymity (since your cloud provider, will require your billing info). See [Streisand](https://github.com/StreisandEffect/streisand), to learn more, and get started with running a VPN. [Digital Ocean](https://m.do.co/c/3838338e7f79) provides flexible, secure and easy Linux VMs, (from $0.007/hour or $5/month), Here is a [1-click install script](http://dovpn.carlfriess.com/)for on [Digital Ocean](https://m.do.co/c/3838338e7f79), by Carl Friess.
> Recently distributed self-hosted solutions for running your own VPNs have become more popular, with services like [Outline](https://getoutline.org/) letting you spin up your own instance and share it with friends and family. Since it's distributed, it is very resistant to blocking, and gives you world-wide access to the free and open internet. And since you have full control over the server, you can be confident that there is no logging or monitoring happening. However it comes at the cost of anonymity, especially if it's only you using your instance.</details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> *While choosing a VPN, consider the following: Logging policy (logs are bad),
Jurisdiction (avoid 5-eyes), Number of servers, availability and average load.
Payment method (anonymous methods such as BTC, Monero or cash are better),
Leak protection (1st-party DNS servers = good, and check if IPv6 is supported),
protocols (OpenVPN and WireGuard = good). Finally, usability of their apps,
user reviews and download speeds.*
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Self-Hosted Network Security

Fun little projects that you can run on a Raspberry Pi, or other low-powered computer. In order to help detect and prevent threats, monitor network and filter content

- **[<img src='https://wp-cdn.pi-hole.net/wp-content/uploads/2016/12/cropped-Vortex-R-192x192.png' width='16' height='16' alt='icon' /> Pi-Hole](https://pi-hole.net)** - Network-level advertisement and Internet tracker blocking application which acts as a DNS
sinkhole. Pi-Hole can significantly speed up your internet, remove ads and block malware.
It comes with a nice web interface and a mobile app with monitoring features, it's open
source, easy to install and very widely used.
 	- [![GitHub: pi-hole/pi-hole](https://img.shields.io/github/stars/pi-hole/pi-hole?style=flat&logo=github&label=pi-hole&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/pi-hole/pi-hole)
- **[<img src='https://technitium.com/favicon.ico' width='16' height='16' alt='icon' /> Technitium](https://technitium.com/dns)** - Another DNS server for blocking privacy-invasive content at its source. Technitium doesn't
require much of a setup, and basically works straight out of the box, it supports a wide
range of systems (and can even run as a portable app on Windows). It allows you to do some
additional tasks, such as add local DNS addresses and zones with specific DNS records.
Compared to Pi-Hole, Technitium is very lightweight, but lacks the deep insights that
Pi-Hole provides, and has a significantly smaller community behind it.
 	- [![GitHub: TechnitiumSoftware/DnsServer](https://img.shields.io/github/stars/TechnitiumSoftware/DnsServer?style=flat&logo=github&label=DnsServer&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/TechnitiumSoftware/DnsServer)
- **[<img src='https://www.ipfire.org/static/img/apple-touch-icon-192x192-precomposed.png' width='16' height='16' alt='icon' /> IPFire](https://www.ipfire.org)** - A hardened, versatile, state-of-the-art open source firewall based on Linux. Its ease of
use, high performance and extensibility make it usable for everyone.
 	- [![GitHub: ipfire/ipfire-2.x](https://img.shields.io/github/stars/ipfire/ipfire-2.x?style=flat&logo=github&label=ipfire-2.x&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ipfire/ipfire-2.x)
- **[<img src='https://www.pivpn.io/images/pivpnlogo.png' width='16' height='16' alt='icon' /> PiVPN](https://pivpn.io)** - A simple way to set up a home VPN on any Debian server. Supports OpenVPN and WireGuard
with elliptic curve encryption keys up to 512 bit. Supports multiple DNS providers and
custom DNS providers - works nicely along-side PiHole.
 	- [![GitHub: pivpn/pivpn](https://img.shields.io/github/stars/pivpn/pivpn?style=flat&logo=github&label=pivpn&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/pivpn/pivpn)
- **[<img src='http://e2guardian.org/cms/images/banners/logo-guardian.png' width='16' height='16' alt='icon' /> E2guardian](http://e2guardian.org)** - Powerful open source web content filter.
 	- [![GitHub: e2guardian/e2guardian](https://img.shields.io/github/stars/e2guardian/e2guardian?style=flat&logo=github&label=e2guardian&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/e2guardian/e2guardian)
- **[<img src='https://www.pfsense.org/img/apple-touch-icon.png' width='16' height='16' alt='icon' /> PF Sense](https://www.pfsense.org)** - Widely used, open source firewall/router.
 	- [![GitHub: pfsense/pfsense](https://img.shields.io/github/stars/pfsense/pfsense?style=flat&logo=github&label=pfsense&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/pfsense/pfsense)
- **[<img src='https://zeek.org/wp-content/uploads/2019/09/favicon.ico' width='16' height='16' alt='icon' /> Zeek](https://www.zeek.org)** - Detect if you have a malware-infected computer on your network, and powerful network
analysis framework and monitor.
 	- [![GitHub: zeek/zeek](https://img.shields.io/github/stars/zeek/zeek?style=flat&logo=github&label=zeek&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/zeek/zeek)
- **[<img src='https://www.firezone.dev/favicon.ico' width='16' height='16' alt='icon' /> Firezone](https://www.firezone.dev/)** - Open-source self-hosted VPN and firewall built on WireGuard®.
 	- [![GitHub: firezone/firezone](https://img.shields.io/github/stars/firezone/firezone?style=flat&logo=github&label=firezone&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/firezone/firezone)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Mix Networks

- **[<img src='https://www.torproject.org/static/images/favicon/favicon.ico' width='16' height='16' alt='icon' /> Tor](https://www.torproject.org)** - Tor provides robust anonymity, allowing you to defend against surveillance, circumvent
censorship and reduce tracking. It blocks trackers, resists fingerprinting and implements
multi-layered encryption by default, meaning you can browse freely. Tor also allows access
to OnionLand: hidden services.
 	- [![GitHub: torproject/tor](https://img.shields.io/github/stars/torproject/tor?style=flat&logo=github&label=tor&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/torproject/tor)
- **[<img src='https://geti2p.net/_static/favicon.ico' width='16' height='16' alt='icon' /> I2P](https://geti2p.net)** - I2P offers great generic transports, it is well geared towards accessing hidden services,
and has a couple of technical benefits over Tor: P2P friendly with unidirectional short-lived
tunnels, it is packet-switched (instead of circuit-switched) with TCP and UDP, and continuously
profiles peers, in order to select the best performing ones.
I2P is less mature, but fully-distributed and self-organising, its smaller size means that it
hasn't yet been blocked or DOSed much.
 - **[<img src='https://www.hyphanet.org/favicon.ico' width='16' height='16' alt='icon' /> Freenet](https://freenetproject.org)** - Freenet is easy to setup, provides excellent friend To Friend Sharing vs I2P, and is great for
publishing content anonymously. It's quite large in size, and very slow so not the best choice
for casual browsing.
 	- [![GitHub: hyphanet/fred](https://img.shields.io/github/stars/hyphanet/fred?style=flat&logo=github&label=fred&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/hyphanet/fred)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> To provide low-latency browsing, Tor does not mix packets or generate cover traffic.
If an adversary is powerful enough, theoretically they could either observe the entire network,
or just the victims entry and exit nodes. It's worth mentioning, that even though your ISP
can not see what you are doing, they will be able determine that you are using a mix net,
to hide this - a VPN could be used as well.
If you are doing anything which could put you at risk, then good OpSec is essential,
as the authorities have traced criminals through the Tor network before,
and [made arrests](https://techcrunch.com/2019/05/03/how-german-and-us-authorities-took-down-the-owners-of-darknet-drug-emporium-wall-street-market).
Don't let Tor provide you a false sense of security - be aware of information leaks through DNS, other programs or human error.
Tor-supported browsers may might lag behind their upstream forks, and include exploitable unpatched issues.
See [#19](https://github.com/Lissy93/personal-security-checklist/issues/19)

Note: The Tor network is run by the community.
If you benefit from using it and would like to help sustain uncensored internet access for all,
consider [running a Tor relay](https://trac.torproject.org/projects/tor/wiki/TorRelayGuide)


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [GNUnet](https://gnunet.org/en)
> - [IPFS](https://ipfs.io)
> - [ZeroNet](https://zeronet.io)
> - [Panoramix](https://panoramix-project.eu)
> - [Nym](https://nymtech.neteu)
</details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> Tor, I2P and Freenet are all anonymity networks - but they work very differently and each is good for specific purposes.
So a good and viable solution would be to use all of them, for different tasks.
*You can read more about how I2P compares to Tor, [here](https://blokt.com/guides/what-is-i2p-vs-tor-browser)*
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Proxies

A proxy acts as a gateway between you and the internet, it can be used to
act as a firewall or web filter, improves privacy and can also be used to
provide shared network connections and cache data to speed up common requests.
**Never use a [free](https://whatismyipaddress.com/free-proxies) proxy.**

- **[<img src='https://avatars.githubusercontent.com/u/3006190' width='16' height='16' alt='icon' /> ShadowSocks](https://shadowsocks.org)** - Secure socks5 proxy, designed to protect your Internet traffic. Open source, superfast,
cross-platform and easy to deploy, see [GitHub repo](https://github.com/shadowsocks).
 	- [![GitHub: shadowsocks/shadowsocks-rust](https://img.shields.io/github/stars/shadowsocks/shadowsocks-rust?style=flat&logo=github&label=shadowsocks-rust&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/shadowsocks/shadowsocks-rust)
- **[<img src='https://www.privoxy.org/images/privoxy.png' width='16' height='16' alt='icon' /> Privoxy](https://www.privoxy.org)** - Non-caching web proxy with advanced filtering capabilities for enhancing privacy,
modifying web page data and HTTP headers, controlling access, and removing ads and
other obnoxious Internet junk.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> [Malicious Proxies](https://www.defcon.org/images/defcon-17/dc-17-presentations/defcon-17-edward_zaborowski-doppelganger.pdf) are all too common.
Always use open source software, host it yourself or pay for a reputable cloud service.
Never use a free proxy; it can monitor your connection, steal cookies and contain malware.
VPNs are a better option, better still - use the Tor network.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [V2ray-core](https://github.com/v2ray/v2ray-core) is a platform for building
> proxies to bypass network restrictions and protect your privacy.
> See [more](https://github.com/hugetiny/awesome-vpn)
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### DNS Providers

Without using a secure, privacy-centric DNS all your web requests can be
seen in the clear. You should configure your DNS queries to be managed by
a service that respects privacy and supports DNS-over-TLS, DNS-over-HTTPS or DNSCrypt.

- **[<img src='https://developers.cloudflare.com/assets/icon-512x512-fe4c8fe4.png' width='16' height='16' alt='icon' /> CloudFlare](https://developers.cloudflare.com/1.1.1.1/setting-up-1.1.1.1)** - One of the most performant options, Cloudflare's DNS supports DoH and DoT, and has a Tor
implementation, providing world-class protection. They have native cross-platform apps,
for easy set-up.
 - **[<img src='https://cdn.adguard.info/website/adguard-dns.io/favicon.svg' width='16' height='16' alt='icon' /> AdGuard](https://adguard.com/en/adguard-dns/overview.html)** - Open-source DNS provider, specialising in the blocking of ads, trackers and malicious domains.
They have been independently audited and do not keep logs.
 - **[<img src='https://nextdns.io/favicon.ico' width='16' height='16' alt='icon' /> NextDNS](https://nextdns.io)** - An ad-blocking, privacy-protecting, censorship-bypassing DNS. Also comes with analytics, and
the ability to shield kids from adult content.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Using an encrypted DNS resolver will not make you anonymous, it just makes
it harder for third-partied to discover your domain history.
If you are using a VPN, take a [DNS leak test](https://www.dnsleaktest.com/),
to ensure that some requests are not being exposed.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [Quad9](https://www.quad9.net) - A well-funded, performant DNS with a strong focus on privacy and security and easy set-up, however questions have been raised about the motivation of some of the financial backers.
> - [BlahDNS](https://blahdns.com) - (Japan, Finland or Germany) is an excellent security-focused DNS> - [OpenNIC](https://www.opennic.org/) - [NixNet DNS](https://nixnet.services/dns) and [UncensoredDNS](https://blog.uncensoreddns.org) are open source and democratic, privacy-focused DNS
> - [Unbound](https://nlnetlabs.nl/projects/unbound/about) - A validating, recursive, caching DNS resolver, designed to be fast and lean. Incorporates modern features and based on open standards
> - [Clean Browsing](https://cleanbrowsing.org) - A good option for protecting kids, they offer comprehensive DNS-based Content Filtering
> - [Mullvad](https://mullvad.net/en/help/dns-over-https-and-dns-over-tls) - Mullvads public DNS with QNAME minimization and basic ad blocking. It has been audited by the security experts at Assured. You can use this privacy-enhancing service even if you don't use Mullvad.
</details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> #### DNS Protocols

DNS-over-TLS was proposed in [RTC-7858](https://tools.ietf.org/html/rfc7858)
by the IETF, then 2 years later, the DNS-over-HTTPS specification was outlined
in [RFC8484](https://tools.ietf.org/html/rfc8484) in October '18.
[DNSCrypt](https://dnscrypt.info/), is a protocol that authenticates communications
between a DNS client and a DNS resolver. It prevents DNS spoofing, through
using cryptographic signatures to verify that responses originate from the
chosen DNS resolver, and haven't been tampered with. DNSCrypt is a well
battle-tested protocol, that has been in use since 2013, and is still widely used.
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### DNS Clients

- **[<img src='https://dnscrypt.info/favicon.ico' width='16' height='16' alt='icon' /> DNScrypt-proxy 2](https://dnscrypt.info)** - A flexible DNS proxy, with support for modern encrypted DNS protocols including DNSCrypt V2,
DNS-over-HTTPS and Anonymized DNSCrypt. Also allows for advanced monitoring, filtering, caching
and client IP protection through Tor, SOCKS proxies or Anonymized DNS relays.
 	- [![GitHub: DNSCrypt/dnscrypt-proxy](https://img.shields.io/github/stars/DNSCrypt/dnscrypt-proxy?style=flat&logo=github&label=dnscrypt-proxy&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/DNSCrypt/dnscrypt-proxy)
- **[<img src='https://nlnetlabs.nl/extra/favicons/favicon-196x196.png' width='16' height='16' alt='icon' /> Unbound](https://nlnetlabs.nl/projects/unbound)** - Validating, recursive, caching DNS resolve with support for DNS-over-TLS. Designed to be fast,
lean, and secure Unbound incorporates modern features based on open standards. It's fully open
source, and recently audited. (For an in-depth tutorial, see this article by DNSWatch.)
 	- [![GitHub: NLnetLabs/unbound](https://img.shields.io/github/stars/NLnetLabs/unbound?style=flat&logo=github&label=unbound&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/NLnetLabs/unbound)
- **[<img src='https://raw.githubusercontent.com/Ch4t4r/Nebulo/master/app/src/main/res/mipmap-xxhdpi/ic_launcher.png' width='16' height='16' alt='icon' /> Nebulo](https://nebulo.app)** - Non-root, small-sized DNS changer utilizing DNS-over-HTTPS and DNS-over-TLS. (Note, since this
uses Android's VPN API, it is not possible to run a VPN while using Nebulo.)
 	- [![GitHub: Ch4t4r/Nebulo](https://img.shields.io/github/stars/Ch4t4r/Nebulo?style=flat&logo=github&label=Nebulo&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Ch4t4r/Nebulo)
- **[<img src='https://rethinkdns.com/ico/app_icon.svg' width='16' height='16' alt='icon' /> RethinkDNS + Firewall](https://rethinkdns.com/app)** - Free and open source DNS changer with support for DNS-over-HTTPS, DNS-over-Tor, and DNSCrypt v3
with Anonymized Relays. (Note, since this uses Android's VPN API, it is not possible to run a
VPN while using RethinkDNS + Firewall.)
 	- [![GitHub: celzero/rethink-app](https://img.shields.io/github/stars/celzero/rethink-app?style=flat&logo=github&label=rethink-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/celzero/rethink-app)
- **[<img src='https://github.com/s-s/dnscloak/blob/master/src/images/logo.png?raw=true' width='16' height='16' alt='icon' /> DNS Cloak](https://apps.apple.com/us/app/dnscloak-secure-dns-client/id1452162351)** - Simple all that allows for the use for dnscrypt-proxy 2 on an iPhone.
 	- [![GitHub: s-s/dnscloak](https://img.shields.io/github/stars/s-s/dnscloak?style=flat&logo=github&label=dnscloak&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/s-s/dnscloak)
- **[<img src='https://dnsprivacy.org/images/favicon.png' width='16' height='16' alt='icon' /> Stubby](https://dnsprivacy.org/wiki/display/DP/DNS+Privacy+Daemon+-+Stubby)** - Acts as a local DNS Privacy stub resolver (using DNS-over-TLS). Stubby encrypts DNS queries sent
from a client machine (desktop or laptop) to a DNS Privacy resolver increasing end user privacy.
Stubby can be used in combination with Unbound - Unbound provides a local cache and Stubby manages
the upstream TLS connections (since Unbound cannot yet re-use TCP/TLS connections),
see example configuration.
 	- [![GitHub: getdnsapi/stubby](https://img.shields.io/github/stars/getdnsapi/stubby?style=flat&logo=github&label=stubby&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/getdnsapi/stubby)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Firewalls

A firewall is a program which monitors the incoming and outgoing traffic
on your network, and blocks requests based on rules set during its configuration.
Properly configured, a firewall can help protect against attempts to
remotely access your computer, as well as control which applications
can access which IPs.

- **[<img src='https://raw.githubusercontent.com/M66B/NetGuard/master/app/src/main/res/mipmap-hdpi/ic_launcher.png' width='16' height='16' alt='icon' /> NetGuard](https://netguard.me)** - Provides simple and advanced ways to block access to the internet. Applications and addresses
can individually be allowed or denied access to Wi-Fi and/or mobile connection.
 	- [![GitHub: M66B/NetGuard](https://img.shields.io/github/stars/M66B/NetGuard?style=flat&logo=github&label=NetGuard&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/M66B/NetGuard)
- **[<img src='https://play-lh.googleusercontent.com/Eo7y02OP6nsOqTx-MsYORxLsIXltk-_0DQUkNztdPUrr_2ZIoR_RgaDXt3y6qrcdIT4=w240-h480' width='16' height='16' alt='icon' /> NoRoot Firewall](https://play.google.com/store/apps/details?id=app.greyshirts.firewall)** - Notifies you when an app is trying to access the Internet, so all you need to do is just Allow
or Deny. Allows you to create filter rules based on IP address, host name or domain name, and
you can allow or deny only specific connections of an app.
 - **[<img src='https://play-lh.googleusercontent.com/LGMnS6aiFUxTLMlDQ4VYaJG0V2lY3lr_ru9QZ3OiCp-YZlsCz3F_v0oWQnqrN-giBA=s48' width='16' height='16' alt='icon' /> AFWall+](https://xdaforums.com/t/5-0-root-3-6-0-afwall-iptables-firewall-28-aug-2023.1957231)** - Android Firewall+ (AFWall+) is an advanced iptables editor (GUI) for rooted Android devices,
which provides very fine-grained control over which Android apps are allowed to access the network.
 	- [![GitHub: ukanth/afwall](https://img.shields.io/github/stars/ukanth/afwall?style=flat&logo=github&label=afwall&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ukanth/afwall)
- **[<img src='https://rethinkdns.com/ico/app_icon.svg' width='16' height='16' alt='icon' /> RethinkDNS + Firewall](https://rethinkdns.com/app)** - An open-source ad-blocker and firewall app for Android 6+ (does not require root).
 	- [![GitHub: celzero/rethink-app](https://img.shields.io/github/stars/celzero/rethink-app?style=flat&logo=github&label=rethink-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/celzero/rethink-app)
- **[<img src='https://icon.horse/icon/lockdownprivacy.com' width='16' height='16' alt='icon' /> Lockdown](https://lockdownprivacy.com)** - Firewall app for iPhone, allowing you to block any connection to any domain.
 - **[<img src='https://cdn.lo4d.com/t/icon/128/simplewall.png' width='16' height='16' alt='icon' /> SimpleWall](https://simplewall.en.lo4d.com)** - Tool to control Windows Filtering Platform (WFP), in order to configure detailed network activity on your PC.
(Windows)
 	- [![GitHub: henrypp/simplewall](https://img.shields.io/github/stars/henrypp/simplewall?style=flat&logo=github&label=simplewall&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/henrypp/simplewall)
- **[<img src='https://objective-see.org/images/LL/icon.png' width='16' height='16' alt='icon' /> LuLu](https://objective-see.com/products/lulu.html)** - Free, open source macOS firewall. It aims to block unknown outgoing connections, unless explicitly approved by the user.
 	- [![GitHub: objective-see/LuLu](https://img.shields.io/github/stars/objective-see/LuLu?style=flat&logo=github&label=LuLu&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/objective-see/LuLu)
- **[<img src='https://obdev.at/Images/product-icons/littlesnitch_340.png' width='16' height='16' alt='icon' /> Little Snitch](https://obdev.at/products/littlesnitch/index.html)** - A very polished application firewall, allowing you to easily manage internet connections on a per-app basis.
(Mac OS)
 - **[<img src='https://raw.githubusercontent.com/evilsocket/opensnitch/master/ui/opensnitch/res/icon.png' width='16' height='16' alt='icon' /> OpenSnitch](https://github.com/evilsocket/opensnitch)** - Makes internet connections from all apps visible, allowing you to block or manage traffic on a per-app basis.
GNU/Linux port of the Little Snitch application firewall.
 	- [![GitHub: evilsocket/opensnitch](https://img.shields.io/github/stars/evilsocket/opensnitch?style=flat&logo=github&label=opensnitch&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/evilsocket/opensnitch)
- **[<img src='https://raw.githubusercontent.com/costales/gufw/master/data/icons/48x48/apps/gufw.png' width='16' height='16' alt='icon' /> Gufw](https://en.wikipedia.org/wiki/Uncomplicated_Firewall)** - Open source GUI firewall for Linux, allowing you to block internet access for certain applications.
Supports both simple and advanced mode, GUI and CLI options, very easy to use, lightweight/ low-overhead,
under active maintenance and backed by a strong community.
 	- [![GitHub: costales/gufw](https://img.shields.io/github/stars/costales/gufw?style=flat&logo=github&label=gufw&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/costales/gufw)
- **[<img src='https://icon.horse/icon/wiki.ubuntu.com' width='16' height='16' alt='icon' /> Uncomplicated Firewall](https://wiki.ubuntu.com/UncomplicatedFirewall)** - The ufw (Uncomplicated Firewall) is a GUI application and CLI, that allows you to configure a firewall
using `iptables` much more easily.
 - **[<img src='https://www.ipfire.org/static/img/apple-touch-icon-192x192-precomposed.png' width='16' height='16' alt='icon' /> IPFire](https://www.ipfire.org)** - IPFire is a hardened, versatile, state-of-the-art Open Source firewall based on Linux. Easy to install
on a raspberry Pi, since it is lightweight and heavily customizable.
 	- [![GitHub: ipfire/ipfire-2.x](https://img.shields.io/github/stars/ipfire/ipfire-2.x?style=flat&logo=github&label=ipfire-2.x&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ipfire/ipfire-2.x)
- **[<img src='https://shorewall.org/favicon.ico' width='16' height='16' alt='icon' /> Shorewall](https://shorewall.org)** - An open source firewall tool for Linux that builds upon the Netfilter system built into the Linux kernel,
making it easier to manage more complex configuration schemes with iptables.
 - **[<img src='https://opnsense.org/wp-content/themes/OPNsense/assets/ico/favicon.png' width='16' height='16' alt='icon' /> OPNSense](https://opnsense.org)** - Enterprise firewall and router for protecting networks, built on the FreeBSD system.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> There are different [types](https://www.networkstraining.com/different-types-of-firewalls)
of firewalls, that are used in different circumstances.
This does not omit the need to configure your operating systems defences.
Follow these instructions to enable your firewall in
[Windows](https://support.microsoft.com/en-us/help/4028544/windows-10-turn-windows-defender-firewall-on-or-off),
[Mac OS](https://support.apple.com/en-us/HT201642), [Ubuntu](https://wiki.ubuntu.com/UncomplicatedFirewall)
and other [Linux distros](https://www.tecmint.com/start-stop-disable-enable-firewalld-iptables-firewall).

Even when properly configured, having a firewall enabled does not guarantee
bad network traffic can not get through and especially during boot if you
don't have root privileges.


</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Ad Blockers

There are a few different ways to block ads - browser-based ad-blockers,
router-based / device blockers or VPN ad-blockers.
Typically they work by taking a maintained list of hosts,
and filtering each domain/ IP through it. Some also have other methods to
detect certain content based on pattern matching

- **[<img src='https://wp-cdn.pi-hole.net/wp-content/uploads/2016/12/cropped-Vortex-R-192x192.png' width='16' height='16' alt='icon' /> Pi-Hole](https://pi-hole.net/)** - Incredibly powerful, network-wide ad-blocker. Works out-of-the-box, light-weight with an intuitive
web interface, but still allows for a lot of advanced configuration for power users. As well as
blocking ads and trackers, Pi-Hole speeds up your network speeds quite significantly. The dashboard
has detailed statistics, and makes it easy to pause/ resume Pi-Hole if needed.
 	- [![GitHub: pi-hole/pi-hole](https://img.shields.io/github/stars/pi-hole/pi-hole?style=flat&logo=github&label=pi-hole&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/pi-hole/pi-hole)
- **[<img src='https://diversion.ch/files/theme-src/images/favicon/favicon-16x16.png' width='16' height='16' alt='icon' /> Diversion](https://diversion.ch)** - A shell script application to manage ad-blocking, Dnsmasq logging, Entware and pixelserv-tls installations
and more on supported routers running Asuswrt-Merlin firmware, including its forks.
 - **[<img src='https://f-droid.org/repo/icons-640/org.jak_linux.dns66.29.png' width='16' height='16' alt='icon' /> DN66](https://jak-linux.org/projects/dns66)** - DNS-based host and ad blocker for Android. Easy to configure, but the default config uses several
widely-respected host files aimed at stopping ads, malware, and other weird stuff.
 	- [![GitHub: julian-klode/dns66](https://img.shields.io/github/stars/julian-klode/dns66?style=flat&logo=github&label=dns66&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/julian-klode/dns66)
- **[<img src='https://user-images.githubusercontent.com/425580/202258429-28da1274-2fb6-49dc-930c-3833f929b65e.png' width='16' height='16' alt='icon' /> BlockParty](https://github.com/krishkumar/BlockParty)** - Native Apple (Swift) apps, for system-wide ad-blocking. Can be customized with custom host lists,
primarily aimed for just ad-blocking.
 	- [![GitHub: krishkumar/BlockParty](https://img.shields.io/github/stars/krishkumar/BlockParty?style=flat&logo=github&label=BlockParty&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/krishkumar/BlockParty)
- **[<img src='https://raw.githubusercontent.com/hectorm/hblock/master/resources/logo/bitmaps/logo-shield-ffffff-h512.png' width='16' height='16' alt='icon' /> hBlock](https://hblock.molinero.dev)** - A POSIX-compliant shell script, designed for Unix-like systems, that gets a list of domains that serve ads,
tracking scripts and malware from multiple sources and creates a hosts file (alternative formats are also supported)
that prevents your system from connecting to them. Aimed at improving security and privacy through blocking advert,
tracking and malware associated domains.
 	- [![GitHub: hectorm/hblock](https://img.shields.io/github/stars/hectorm/hblock?style=flat&logo=github&label=hblock&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/hectorm/hblock)
- **[<img src='https://icon.horse/icon/blokada.org' width='16' height='16' alt='icon' /> Blokada](https://blokada.org/)** - Open source mobile ad-blocker that acts like a firewall. Since it's device-wide, once connected all apps will
have ads/ trackers blocked, and the blacklist can be edited. The app is free, but there is a premium option,
which has a built-in VPN.
 	- [![GitHub: blokadaorg/blokada](https://img.shields.io/github/stars/blokadaorg/blokada?style=flat&logo=github&label=blokada&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/blokadaorg/blokada)
- **[<img src='https://rethinkdns.com/ico/app_icon.svg' width='16' height='16' alt='icon' /> RethinkDNS + Firewall](https://rethinkdns.com/app)** - Free and open source ad-blocker and a firewall for Android 6+ (no root required).
 	- [![GitHub: celzero/rethink-app](https://img.shields.io/github/stars/celzero/rethink-app?style=flat&logo=github&label=rethink-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/celzero/rethink-app)
- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Ad Block Radio](https://github.com/adblockradio/adblockradio)** - Python script that uses machine learning to block adverts in live audio streams, such as Radio, Podcasts,
Audio Books, and music platforms such as Spotify. See live demo.
 	- [![GitHub: adblockradio/adblockradio](https://img.shields.io/github/stars/adblockradio/adblockradio?style=flat&logo=github&label=adblockradio&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/adblockradio/adblockradio)
- **[<img src='https://raw.githubusercontent.com/hectorm/hblock/master/resources/logo/bitmaps/logo-shield-ffffff-h512.png' width='16' height='16' alt='icon' /> uBlock Origin](https://github.com/gorhill/uBlock)** - Light-weight, fast browser extension for Firefox and Chromium (Chrome, Edge, Brave Opera etc), that blocks
tracking, ads and known malware. uBlock is easy-to-use out-of-the-box, but also has a highly customisable
advanced mode, with a point-and-click firewall which can be configured on a per-site basis.
 	- [![GitHub: gorhill/uBlock](https://img.shields.io/github/stars/gorhill/uBlock?style=flat&logo=github&label=uBlock&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/gorhill/uBlock)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) is a cross-platform DNS Ad Blocker,
> similar to Pi Hole, but with some additional features, like parental controls,
> per-device configuration and the option to force safe search.
> This may be a good solution for families with young children.
> 
> Some VPNs have ad-tracking blocking features, such as
> [TrackStop with PerfectPrivacy](https://www.perfect-privacy.com/en/features/trackstop?a_aid=securitychecklist).
> 
> [Private Internet Access](https://www.privateinternetaccess.com/),
> [CyberGhost](https://www.cyberghostvpn.com/),
> [PureVPN](https://www.anrdoezrs.net/click-9242873-13842740),
> and [NordVPN](https://www.kqzyfj.com/l5115shqnhp4E797DC8467D69A6D) also have ad-block features.
> But do not meet security/privact requirements to be included.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Host Block Lists

- **[<img src='https://someonewhocares.org/favicon.ico' width='16' height='16' alt='icon' /> SomeoneWhoCares/ Hosts](https://someonewhocares.org/hosts)** - An up-to-date host list, maintained by Dan Pollock - to make the internet not suck (as much).
 - **[<img src='https://i.ibb.co/WzGDCx6/hosts-by-steven-black.png' width='16' height='16' alt='icon' /> Hosts by StevenBlack](https://github.com/StevenBlack/hosts)** - Open source, community-maintained consolidated and extending hosts files from several well-curated
sources. You can optionally pick extensions to block p0rn, Social Media, gambling, fake news and other categories.
 	- [![GitHub: StevenBlack/hosts](https://img.shields.io/github/stars/StevenBlack/hosts?style=flat&logo=github&label=hosts&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/StevenBlack/hosts)
- **[<img src='https://i.ibb.co/878BLq2/GAFAMSPLATTEXTNOGgit.png' width='16' height='16' alt='icon' /> No Google](https://github.com/nickspaargaren/no-google)** - Totally block all direct and indirect content from Google, Amazon, Facebook, Apple and Microsoft (or just some).
 	- [![GitHub: nickspaargaren/no-google](https://img.shields.io/github/stars/nickspaargaren/no-google?style=flat&logo=github&label=no-google&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/nickspaargaren/no-google)
- **[<img src='https://icon.horse/icon/easylist.to' width='16' height='16' alt='icon' /> EasyList](https://easylist.to)** - Comprehensive list of domains for blocking tracking, social scripts, bad cookies and annoying stuff.
 	- [![GitHub: easylist/easylist](https://img.shields.io/github/stars/easylist/easylist?style=flat&logo=github&label=easylist&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/easylist/easylist)
- **[<img src='https://d3pkfiqitivr8j.cloudfront.net/sitefiles/images/favicon.ico' width='16' height='16' alt='icon' /> iBlockList](https://www.iblocklist.com)** - Variety of lists (free and paid-for) for blocking content based on certain topics, inducing: spam, abuse,
political, illegal, hijacked, bad peers and more.
 - **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Energized](https://github.com/EnergizedProtection/block)** - A variety of well-maintained lists, available in all common formats, with millions of hosts included.
 	- [![GitHub: EnergizedProtection/block](https://img.shields.io/github/stars/EnergizedProtection/block?style=flat&logo=github&label=block&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/EnergizedProtection/block)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Router Firmware

Installing a custom firmware on your Wi-Fi router gives you greater
control over security, privacy and performance

- **[<img src='https://openwrt.org/_media/favicon.ico' width='16' height='16' alt='icon' /> OpenWRT](https://openwrt.org)** - Plenty of scope for customization and a ton of supported addons. Stateful firewall, NAT, and dynamically-configured
port forwarding protocols (UPnP, NAT-PMP + upnpd, etc), Load balancing, IP tunneling, IPv4 & IPv6 support.
 	- [![GitHub: openwrt/openwrt](https://img.shields.io/github/stars/openwrt/openwrt?style=flat&logo=github&label=openwrt&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/openwrt/openwrt)
- **[<img src='https://dd-wrt.com/favicon.ico' width='16' height='16' alt='icon' /> DD-WRT](https://dd-wrt.com)** - Easy and powerful user interface. Great access control, bandwidth monitoring and quality of service.
IPTables is built-in for firewall, and there's great VPN support as well as additional plug-and-play
and wake-on-lan features.
 	- [![GitHub: mirror/dd-wrt](https://img.shields.io/github/stars/mirror/dd-wrt?style=flat&logo=github&label=dd-wrt&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mirror/dd-wrt)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Flashing custom firmware may void your warranty.
If power is interrupted mid-way through a firmware install/ upgrade it
is possible for your device to become bricked. So long as you follow a
guide, and use a well supported system, on a supported router, than it
should be safe


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [Tomato](https://www.polarcloud.com/tomato)
> - [Gargoyle](https://www.gargoyle-router.com)
> - [LibreCMC](https://librecmc.org)
> - [DebWRT](http://www.debwrt.net)
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Network Analysis

Whether you live in a country behind a firewall, or accessing the internet
through a proxy - these tools will help you better understand the extent
of blocking, deep packet inspection and what data is being analysed

- **[<img src='https://ooni.org/images/favicon.png' width='16' height='16' alt='icon' /> OONI](https://ooni.org)** - Open Observatory of Network Interference - A free tool and global observation network, for detecting censorship,
surveillance and traffic manipulation on the internet. Developed by The Tor Project, and available for Android,
iOS, and Linux.
 	- [![GitHub: ooni/probe](https://img.shields.io/github/stars/ooni/probe?style=flat&logo=github&label=probe&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ooni/probe)
- **[<img src='https://ntc.party/uploads/default/original/1X/3bdcdffa0d2f06e15ee4c02f4dd2ada9e771e642.png' width='16' height='16' alt='icon' /> Goodbye DPI](https://ntc.party/c/community-software/goodbyedpi/8)** - Passive Deep Packet Inspection blocker and Active DPI circumvention utility, for Windows.
 	- [![GitHub: ValdikSS/GoodbyeDPI](https://img.shields.io/github/stars/ValdikSS/GoodbyeDPI?style=flat&logo=github&label=GoodbyeDPI&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ValdikSS/GoodbyeDPI)
- **[<img src='https://raw.githubusercontent.com/nomoresat/DPITunnel-android/main/assets/logo.webp' width='16' height='16' alt='icon' /> DPITunnel](https://github.com/zhenyolka/DPITunnel)** - An Android app to bypass deep packet inspection.
 	- [![GitHub: nomoresat/DPITunnel-android](https://img.shields.io/github/stars/nomoresat/DPITunnel-android?style=flat&logo=github&label=DPITunnel-android&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/nomoresat/DPITunnel-android)
- **[<img src='https://ping.eu/favicon.ico' width='16' height='16' alt='icon' /> Proxy Checker](https://ping.eu/proxy/)** - You can quickly check if a given IP is using a proxy, this can also be done through the command line.
 
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Intrusion Detection

An IDS is an application that monitors a network or computer system for
malicious activity or policy violations, and notifies you of any unusual
or unexpected events. If you are running a server, then it's essential to
know about an incident as soon as possible, in order to minimize damage.

- **[<img src='https://zeek.org/wp-content/uploads/2019/09/favicon.ico' width='16' height='16' alt='icon' /> Zeek](https://zeek.org/)** - Zeek (formally Bro) Passively monitors network traffic and looks for suspicious activity.
 	- [![GitHub: zeek/zeek](https://img.shields.io/github/stars/zeek/zeek?style=flat&logo=github&label=zeek&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/zeek/zeek)
- **[<img src='https://i.ibb.co/23CNVCk/ossec.png' width='16' height='16' alt='icon' /> OSSEC](https://www.ossec.net/)** - OSSEC is an Open Source host-based intrusion detection system, that performs log analysis, integrity checking,
monitoring, rootkit detection, real-time alerting and active response.
 	- [![GitHub: ossec/ossec-hids](https://img.shields.io/github/stars/ossec/ossec-hids?style=flat&logo=github&label=ossec-hids&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ossec/ossec-hids)
- **[<img src='https://avatars.githubusercontent.com/u/22322275?v=4' width='16' height='16' alt='icon' /> Kismet](https://www.kismetwireless.net)** - An 802.11 layer2 wireless network detector, sniffer, and intrusion detection system.
 	- [![GitHub: kismetwireless/kismet](https://img.shields.io/github/stars/kismetwireless/kismet?style=flat&logo=github&label=kismet&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/kismetwireless/kismet)
- **[<img src='https://www.snaresolutions.com/wp-content/uploads/cropped-Snare-Logo-2022-Icon-Lockup-Original-Color-32x32.png' width='16' height='16' alt='icon' /> Snare](https://www.snaresolutions.com/products/snare-central)** - SNARE (System iNtrusion Analysis and Reporting Environment) is a series of log collection agents that facilitate
centralized analysis of audit log data. Logs from the OS are collected and audited. Full remote access, through
a web interface easy to use manually, or by an automated process.
 - **[<img src='https://icon.horse/icon/elesiuta.github.io' width='16' height='16' alt='icon' /> picosnitch](https://elesiuta.github.io/picosnitch)** - picosnitch helps protect your security and privacy by "snitching" on anything that connects to the internet,
letting you know when, how much data was transferred, and to where. It uses BPF to monitor network traffic per
application, and per parent to cover those that just call others. It also hashes every executable, and will
complain if some mischievous program is giving it trouble.
 	- [![GitHub: elesiuta/picosnitch](https://img.shields.io/github/stars/elesiuta/picosnitch?style=flat&logo=github&label=picosnitch&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/elesiuta/picosnitch)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Cloud Hosting

Whether you are hosting a website and want to keep your users data safe,
or if you are hosting your own file backup, cloud productivity suite or
VP - then choosing a provider that respects your privacy and allows you
to sign up anonymously, and will keep your files and data safe is be
important.

- **[<img src='https://njal.la/favicon.ico' width='16' height='16' alt='icon' /> Njalla](https://njal.la)** - Njalla is a privacy and security-focused domain registrar and VPN hosting provider. They own and manage all their
own servers, which are based in Sweden. They accept crypto, for anonymous payments, and allow you to sign up with
OTR XMPP if you do not want to provide an email address. Both VPS and domain name pricing is reasonable, with
packages starting at $15/ month.
 - **[<img src='https://icon.horse/icon/www.privatelayer.com' width='16' height='16' alt='icon' /> Private Layer](https://www.privatelayer.com)** - Offers enterprise-grade, high-speed offshore dedicated servers, they own their own data centres, have a solid
privacy policy and accept anonymous payment.
 - **[<img src='https://icon.horse/icon/servers.guru' width='16' height='16' alt='icon' /> Servers Guru](https://servers.guru)** - Servers Guru provides affordable and anonymous VPS and cloud servers with dedicated cpu resources. They accept
crypto-currencies (Bitcoin, Monero, Ethereum etc..) and don't require any personal informations. They resell from
reputable providers.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> The country that your data is hosted in, will be subject to local laws and regulations.
It is therefore important to avoid a jurisdiction that is part of the
[5 eyes](https://en.wikipedia.org/wiki/Five_Eyes) (Australia, Canada, New Zealand, US and UK)
and [other international cooperatives](https://en.wikipedia.org/wiki/Five_Eyes#Other_international_cooperatives)
who have legal right to view your data.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> See also: [1984](https://www.1984.is) based in Iceland.
> [Shinjiru](http://shinjiru.com?a_aid=5e401db24a3a4), which offers off-shore dedicated servers.
> [Orange Website](https://www.orangewebsite.com) specialises in protecting online privacy and free speech, hosted in Iceland.
> [RackBone](https://rackbone.ch) (previously DataCell) provides secure and ethical hosting, based in Switzerland.
> And [Bahnhof](https://www.bahnhof.net) offers high-security and ethical hosting, with their data centres locates in Sweden.
> Finally [Simafri](https://www.simafri.com/anonymous) has a range of packages, that support Tor out of the box
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Domain Registrars

- **[<img src='https://njal.la/favicon.ico' width='16' height='16' alt='icon' /> Njal.la](https://njal.la)** - Privacy-aware domain service with anonymous sign-up and accepts cryptocurrency.
 - **[<img src='https://orangewebsite.com/fav.ico' width='16' height='16' alt='icon' /> Orange Website](https://www.orangewebsite.com/domain-registration.php)** - Anonymous domain registration, with low online censorship since they are based outside the
14-eyes jurisdiction (in Iceland).
 
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### DNS Hosting

- **[<img src='https://desec.io/favicon.svg' width='16' height='16' alt='icon' /> deSEC](https://desec.io)** - Free DNS hosting provider designed with security in mind, and running
on purely open source software. deSEC is backed and funded by SSE. 
 	- [![GitHub: desec-io/desec-stack](https://img.shields.io/github/stars/desec-io/desec-stack?style=flat&logo=github&label=desec-stack&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/desec-io/desec-stack)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Mail Servers

- **[<img src='https://mailinabox.email/static/logo.png' width='16' height='16' alt='icon' /> Mail-in-a-box](https://mailinabox.email)** - Easy-to-deploy fully-featured and pre-configured SMTP mail server. It includes everything from
webmail, to spam filtering and backups.
 	- [![GitHub: mail-in-a-box/mailinabox](https://img.shields.io/github/stars/mail-in-a-box/mailinabox?style=flat&logo=github&label=mailinabox&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mail-in-a-box/mailinabox)
- **[<img src='https://docker-mailserver.github.io/docker-mailserver/latest/assets/logo/favicon-32x32.png' width='16' height='16' alt='icon' /> Docker Mailserver](https://docker-mailserver.github.io/docker-mailserver/latest)** - A full-stack but simple mailserver (smtp, imap, antispam, antivirus, ssl...) using Docker. Very
complete, with everything you will need, customizable and very easy to deploy with docker.
 	- [![GitHub: tomav/docker-mailserver](https://img.shields.io/github/stars/tomav/docker-mailserver?style=flat&logo=github&label=docker-mailserver&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/tomav/docker-mailserver)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Self-hosting your own mail server is not recommended for everyone, it can
be time consuming to setup and maintain and securing it correctly is critical


</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Productivity

### Digital Notes

- **[<img src='https://standardnotes.com/favicon.ico' width='16' height='16' alt='icon' /> Standard Notes](https://standardnotes.com)** - S.Notes is a free, open-source, and completely encrypted private notes app. It has a simple UI,
yet packs in a lot of features, thanks to the Extensions Store, allowing for: To-Do lists, Spreadsheets,
Rich Text, Markdown, Math Editor, Code Editor and many more. You can choose between a number of themes
(yay, dark mode!), and it features built-in secure file store, tags/ folders, fast search and more.
Standard Notes is actively developed, and fully open-source.
 	- [![GitHub: standardnotes/app](https://img.shields.io/github/stars/standardnotes/app?style=flat&logo=github&label=app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/standardnotes/app)
- **[<img src='https://turtlapp.com/images/logo.svg' width='16' height='16' alt='icon' /> Turtle](https://turtlapp.com)** - A secure, collaborative notebook. Self-host it yourself, or use their hosted plan (free edition
or $3/ month for premium).
 	- [![GitHub: turtl/desktop](https://img.shields.io/github/stars/turtl/desktop?style=flat&logo=github&label=desktop&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/turtl/desktop)
- **[<img src='https://notable.app/favicon.ico' width='16' height='16' alt='icon' /> Notable](https://notable.md)** - An offline markdown-based note editor for desktop, with a simple, yet feature-rich UI.
All notes are saved individually as .md files, making them easy to manage.
No mobile app, built-in cloud-sync, encryption or web UI. But due to the structure of the files,
it is easy to use your own cloud sync provider, and additional features are provided through extensions.
 	- [![GitHub: notable/notable](https://img.shields.io/github/stars/notable/notable?style=flat&logo=github&label=notable&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/notable/notable)
- **[<img src='https://joplinapp.org/images/favicon.png' width='16' height='16' alt='icon' /> Joplin](https://joplinapp.org)** - Cross-platform desktop and mobile note-taking and todo app. Easy organisation into notebooks and
sections, revision history and a simple UI. Allows for easy import and export of notes to or from
other services. Supports synchronisation with cloud services, implemented with E2EE.
 	- [![GitHub: laurent22/joplin](https://img.shields.io/github/stars/laurent22/joplin?style=flat&logo=github&label=joplin&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/laurent22/joplin)
- **[<img src='https://logseq.com/logo-with-border.5bf84f43.png' width='16' height='16' alt='icon' /> Logseq](https://logseq.com/)** - Privacy-first, open-source knowledge base that works on top of local plain-text Markdown and
Org-mode files.
Supports lots of different note modes, including task management,
PDF annotation, flashcards, whiteboards strong markdown support and more.
Includes themes and extensions, backed by a strong community
 	- [![GitHub: logseq/logseq](https://img.shields.io/github/stars/logseq/logseq?style=flat&logo=github&label=logseq&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/logseq/logseq)
- **[<img src='https://obsidian.md/favicon.svg' width='16' height='16' alt='icon' /> Obsidian](https://obsidian.md/)** - A powerful knowledge base that works on top of local plain-text Markdown files. It has a strong
community, and a lot of plugins and themes. Generally privacy-respecting, but no
encryption out of the box, and some of the code is obfuscated or not fully open source
 	- [![GitHub: obsidianmd/obsidian-releases](https://img.shields.io/github/stars/obsidianmd/obsidian-releases?style=flat&logo=github&label=obsidian-releases&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/obsidianmd/obsidian-releases)
- **[<img src='https://icon.horse/icon/affine.pro' width='16' height='16' alt='icon' /> AFFiNE](https://affine.pro)** - Privacy first, open-source alternative to Notion, monday.com and Miro.
It is a knowledge management tool that allows you to create, organize and share your knowledge.
 	- [![GitHub: toeverything/AFFiNE](https://img.shields.io/github/stars/toeverything/AFFiNE?style=flat&logo=github&label=AFFiNE&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/toeverything/AFFiNE)
- **[<img src='https://raw.githubusercontent.com/cryptee/web-client/v3/source/assets/logo-b.svg' width='16' height='16' alt='icon' /> Cryptee](https://crypt.ee/)** - Private & encrypted rich-text documents. Cryptee has encryption and anonymity at its core,
it also has a beautiful and minimalistic UI. You can use Cryptee from the browser, or download
native apps. Comes with many additional features, such as support for photo albums and file storage.
The disadvantage is that only the frontend is open source. Pricing is free for starter plan, $3/
month for 10GB, additional plans go up-to 2TB.
 	- [![GitHub: cryptee/web-client](https://img.shields.io/github/stars/cryptee/web-client?style=flat&logo=github&label=web-client&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/cryptee/web-client)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> If you are already tied into Evernote, One Note etc, then [SafeRoom](https://www.getsaferoom.com)
> is a utility that encrypts your entire notebook, before it is uploaded to the cloud. 
> 
> [Org Mode](https://orgmode.org) is a mode for [GNU Emacs](https://www.gnu.org/software/emacs/)
> dedicated to working with the Org markup format. Org can be thought of as
> a more featureful Markdown alternative, with support for keeping notes,
> maintaining todo lists, planning projects, managing spreadsheets, and
> authoring documents -all in plaintext.
> 
> For a simple plain text note taking app, with strong encryption, see
> [Protected Text](https://www.protectedtext.com), which works well with the
> [Safe Notes](https://play.google.com/store/apps/details?id=com.protectedtext.android) Android app.
> [Laverna](https://laverna.cc/) is a cross-platform secure notes app,
> where all entries are formatted with markdown.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Calendar

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Backup and Sync

- **[<img src='https://www.seafile.com/media/img/favicon.png?t=3' width='16' height='16' alt='icon' /> SeaFile](https://www.seafile.com)** - An open source cloud storage and sync solution. Files are grouped into Libraries, which can be individually encrypted,
shared of synced. Docker image available for easy deployment, and native clients for Windows, Mac, Linux, Android and iOS.
 	- [![GitHub: haiwen/seafile](https://img.shields.io/github/stars/haiwen/seafile?style=flat&logo=github&label=seafile&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/haiwen/seafile)
- **[<img src='https://syncthing.net/img/favicons/apple-touch-icon-152x152.png' width='16' height='16' alt='icon' /> Syncthing](https://syncthing.net)** - Continuous file synchronization between 2 or more clients. It is simple, yet powerful, and fully-encrypted and private.
Syncthing can be deployed with Docker, and there are native clients for Windows, Mac, Linux, BSD and Android.
 	- [![GitHub: syncthing/syncthing](https://img.shields.io/github/stars/syncthing/syncthing?style=flat&logo=github&label=syncthing&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/syncthing/syncthing)
- **[<img src='https://nextcloud.com/c/uploads/2022/03/favicon.png' width='16' height='16' alt='icon' /> NextCloud](https://nextcloud.com)** - Feature-rich productivity platform, that can be used to backup and selectively sync encrypted files and folders between
1 or more clients. A key benefit the wide range of plug-ins in the NextCloud App Store, maintained by the community.
NextCloud was a hard fork off OwnCloud.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> You should always ensure that any data stored in the cloud is encrypted.
If you are hosting your own server, then take the necessary precautions
to [secure the server](https://med.stanford.edu/irt/security/servers.html).
For hosted solutions - use a strong password, keep your credentials safe and enable 2FA.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> Alternatively, consider a headless utility such as [Duplicacy](https://duplicacy.com)
> or [Duplicity](http://duplicity.nongnu.org).
> Both of offer an encrypted and efficient sync between 2 or more locations,
> using the [rsync](https://linux.die.net/man/1/rsync) algorithm.
> 
> [SpiderOak](https://spideroak.com), [Tresorit](https://tresorit.com) and [Resilio](https://www.resilio.com/individuals)
> are good enterprise solutions, all with solid encryption baked-in
> 
> [FileRun](https://filerun.com) and [Pydio](https://pydio.com)
> are self-hosted file explorers, with cross-platform sync capabilities.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Cloud Productivity Suites

- **[<img src='https://cryptpad.fr/customize/CryptPad_logo.svg' width='16' height='16' alt='icon' /> CryptPad](https://cryptpad.org/)** - A zero knowledge cloud productivity suite. Provides Rich Text, Presentations, Spreadsheets, Kanban, Paint a code
editor and file drive. All notes and user content, are encrypted by default, and can only be accessed with specific
URL. The main disadvantage, is a lack of Android, iOS and desktop apps - CryptPad is entirely web-based. You can use
their web service, or you can host your own instance. Price for hosted: free for 50mb or $5/ month for premium.
 	- [![GitHub: xwiki-labs/cryptpad](https://img.shields.io/github/stars/xwiki-labs/cryptpad?style=flat&logo=github&label=cryptpad&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/xwiki-labs/cryptpad)
- **[<img src='https://nextcloud.com/c/uploads/2022/03/favicon.png' width='16' height='16' alt='icon' /> NextCloud](https://nextcloud.com)** - A complete self-hosted productivity platform, with a strong community and growing app store. NextCloud is similar to
(but arguably more complete than) Google Drive, Office 365 and Dropbox. Clear UI and stable native apps across all
platforms, and also supports file sync. Supports encrypted files, but you need to configure this yourself. Fully open
source.
 	- [![GitHub: nextcloud/server](https://img.shields.io/github/stars/nextcloud/server?style=flat&logo=github&label=server&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/nextcloud/server)
- **[<img src='https://disroot.org/user/themes/disroot/images/favicon.png' width='16' height='16' alt='icon' /> Disroot](https://disroot.org)** - A platform providing online services based on principles of freedom, privacy, federation and decentralization. It is
an implementation of NextCloud, with strong encryption configured - it is widely used by journalists, activists and
whistle-blowers. It is free to use, but there have been reported reliability issues of the cloud services.
 - **[<img src='https://sandstorm.io/favicon.ico' width='16' height='16' alt='icon' /> Sandstorm](https://sandstorm.io)** - An open source platform for self-hosting web apps. Once you've set it up, you can install items from the Sandstorm
App Market with -click, similar to NextCloud in terms of flexibility.
 	- [![GitHub: sandstorm-io/sandstorm](https://img.shields.io/github/stars/sandstorm-io/sandstorm?style=flat&logo=github&label=sandstorm&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/sandstorm-io/sandstorm)
- **[<img src='https://vikunja.io/favicon.ico' width='16' height='16' alt='icon' /> Vikunja](https://vikunja.io)** - Vikunja is an open-source to-do application. It is suitable for a wide variety of projects, supporting List, Gantt,
Table and Kanban views to visualize all tasks in different contexts. For collaboration, it has sharing support via
private teams or public links. It can be self-hosted or used as a managed service for a small fee.
 	- [![GitHub: go-vikunja/vikunja](https://img.shields.io/github/stars/go-vikunja/vikunja?style=flat&logo=github&label=vikunja&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/go-vikunja/vikunja)
- **[<img src='https://skiff.com/favicon.ico' width='16' height='16' alt='icon' /> Skiff Pages](https://skiff.com/pages)** - Skiff Pages is an end-to-end encrypted, privacy-first collaborative document, note-taking, and wiki product. Skiff
Pages has a modern, easy-to-use UI and supports rich text documents with embedded content. Skiff also supports end-to-end
encrypted file upload and sharing (Skiff Drive), as well as workspaces for multiple users to collaborate.
 	- [![GitHub: skiff-org/skiff-apps](https://img.shields.io/github/stars/skiff-org/skiff-apps?style=flat&logo=github&label=skiff-apps&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/skiff-org/skiff-apps)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Encrypted Cloud Storage

Backing up important files is essential, and keeping an off-site copy is recommended.
But many free providers do not respect your privacy, and are not secure enough for
sensitive documents.
Avoid free mainstream providers, such as Google Drive, cloud, Microsoft Overdrive, Dropbox.

It is recommended to encrypt files on your client machine, before syncing to the cloud.
[Cryptomator](https://cryptomator.org) is a cross-platform, open source encryption app, designed for just this.

- **[<img src='https://icon.horse/icon/tresorit.com' width='16' height='16' alt='icon' /> Tresorit](https://tresorit.com)** - End-to-end encrypted zero knowledge file storage, syncing and sharing provider, based in Switzerland.
The app is cross-platform, user-friendly client and with all expected features. £6.49/month for 500 GB.
 - **[<img src='https://icon.horse/icon/icedrive.net' width='16' height='16' alt='icon' /> IceDrive](https://icedrive.net)** - Very affordable encrypted storage provider, with cross-platform apps. Starts as £1.50/month for 150 GB
or £3.33/month for 1 TB.
 - **[<img src='https://icon.horse/icon/www.sync.com' width='16' height='16' alt='icon' /> Sync.com](https://www.sync.com)** - Secure file sync, sharing, collaboration and backup for individuals, small businesses and sole practitioners.
Starts at $8/month for 2 TB.
 - **[<img src='https://icon.horse/icon/www.pcloud.com' width='16' height='16' alt='icon' /> pCloud](https://www.pcloud.com)** - Secure and simple to use cloud storage, with cross-platform client apps. £3.99/month for 500 GB.
 - **[<img src='https://icon.horse/icon/peergos.org' width='16' height='16' alt='icon' /> Peergos](https://peergos.org/)** - A peer-to-peer end-to-end encrypted global filesystem with fine grained access control. Provides a secure
and private space online where you can store, share and view your photos, videos, music and documents.
Also includes a calendar, news feed, task lists, chat and email client. Fully open source and self-hostable
(or use hosted solution, £5/month for 50 GB).
 - **[<img src='https://internxt.com/favicon.ico' width='16' height='16' alt='icon' /> Internxt](https://internxt.com/)** - Store your files in total privacy. Internxt Drive is a zero-knowledge cloud storage service based on best-in-class
privacy and security. Made in Spain. Open-source mobile and desktop apps. 10GB FREE and Paid plans starting from
€0.99/month for 20GB.
 - **[<img src='https://icon.horse/icon/filen.io' width='16' height='16' alt='icon' /> FileN](https://filen.io/)** - Zero knowledge end-to-end encrypted affordable cloud storage made in Germany. Open-source mobile and desktop apps.
10GB FREE with paid plans starting at €0.92/month for 100GB.
 
<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> An alternative option, is to use a cloud computing provider, and implement
> the syncing functionality yourself, and encrypt data locally before
> uploading it - this may work out cheaper in some situations.
> You could also run a local server that you physically own at a secondary location,
> that would mitigate the need to trust a third party cloud provider.
> Note that some knowledge in securing networks is required.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### File Drop

- **[<img src='https://icon.horse/icon/file.pizza' width='16' height='16' alt='icon' /> FilePizza](https://file.pizza)** - Peer-to-peer based file transfer from the browser, using Web Torrent. It's quick and easy to use, and doesn't
require any software to be installed. Can also be self-hosted.
 	- [![GitHub: kern/filepizza](https://img.shields.io/github/stars/kern/filepizza?style=flat&logo=github&label=filepizza&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/kern/filepizza)
- **[<img src='https://icon.horse/icon/filesend.standardnotes.org' width='16' height='16' alt='icon' /> FileSend](https://filesend.standardnotes.org)** - Simple, encrypted file sharing, with a 500mb limit and 5-day retention. Files are secured with client-side AES-256
encryption and no IP address or device info is logged. Files are permanently deleted after download or after specified
duration. Developed by StandardNotes, and has built-in integration with the SN app.
 - **[<img src='https://icon.horse/icon/onionshare.org' width='16' height='16' alt='icon' /> OnionShare](https://onionshare.org/)** - An open source tool that lets you securely and anonymously share a file of any size, via Tor servers. OnionShare does
require installing, but the benefit is that your files are transferred directly to the recipient, without needing to be
hosted on an interim server. The host needs to remain connected for the duration of the transfer, but once it is complete,
the process will be terminated.
 	- [![GitHub: micahflee/onionshare](https://img.shields.io/github/stars/micahflee/onionshare?style=flat&logo=github&label=onionshare&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/micahflee/onionshare)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [Instant.io](https://github.com/webtorrent/instant.io), is another peer-to-peer based solution,
> using [Web Torrent](https://webtorrent.io).
> 
> For specifically transferring images, [Up1](https://github.com/Upload/Up1) is a good self-hosted option, with client-side encryption.
> 
> Finally [PsiTransfer](https://github.com/psi-4ward/psitransfer) is a feature-rich, self-hosted file drop, using streams.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Browser Sync

- **[<img src='https://icon.horse/icon/floccus.org' width='16' height='16' alt='icon' /> Floccus](https://floccus.org)** - Simple and efficient bookmark syncing using either NextCloud Bookmarks, a WebDAV server (local or remote)
or just a local folder through LoFloccus. Browser extensions available for Chrome, Firefox, and Edge.
 	- [![GitHub: marcelklehr/floccus](https://img.shields.io/github/stars/marcelklehr/floccus?style=flat&logo=github&label=floccus&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/marcelklehr/floccus)
- **[<img src='https://icon.horse/icon/www.xbrowsersync.org' width='16' height='16' alt='icon' /> XBrowserSync](https://www.xbrowsersync.org)** - Secure, anonymous and free browser and bookmark syncing. Easy to setup, and no sign up is required, you can
either use a community-run sync server, or host your own with their docker image. Extensions are available for
Chrome, Firefox, and on Android.
 	- [![GitHub: xbrowsersync/app](https://img.shields.io/github/stars/xbrowsersync/app?style=flat&logo=github&label=app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/xbrowsersync/app)
- **[<img src='https://icon.horse/icon/unmark.it' width='16' height='16' alt='icon' /> Unmark](https://unmark.it)** - A web application which acts as a todo app for bookmarks. You can either self-host it, or use their managed
service which has a free and paid-for tier.
 	- [![GitHub: cdevroe/unmark](https://img.shields.io/github/stars/cdevroe/unmark?style=flat&logo=github&label=unmark&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/cdevroe/unmark)
- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Reminiscence](https://github.com/kanishka-linux/reminiscence)** - A self-hosted bookmark and archive manager. Reminiscence is more geared towards archiving useful web pages
either for offline viewing or to preserve a copy. It is a web application, that can be installed with Docker
on either a local or remote server, although it has a comprehensive and well-documented REST API, there is
currently no browser extension.
 	- [![GitHub: kanishka-linux/reminiscence](https://img.shields.io/github/stars/kanishka-linux/reminiscence?style=flat&logo=github&label=reminiscence&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/kanishka-linux/reminiscence)
- **[<img src='https://avatars.githubusercontent.com/u/41993376?s=200&v=4' width='16' height='16' alt='icon' /> Shiori](https://github.com/go-shiori/shiori)** - Simple bookmark manager written in Go, intended to be a clone of Pocket, it has both a simple and clean web
interface as well as a CLI. Shiori has easy import/ export, is portable and has webpage archiving features.
 	- [![GitHub: go-shiori/shiori](https://img.shields.io/github/stars/go-shiori/shiori?style=flat&logo=github&label=shiori&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/go-shiori/shiori)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [Ymarks](https://ymarks.org) is a C-based self-hosted bookmark synchronization
> server and [Chrome](https://chrome.google.com/webstore/detail/ymarks/gefignhaigoigfjfbjjobmegihhaacfi) extension.
> 
> [syncmarx](https://syncmarx.gregmcleod.com) uses your cloud storage to sync
> bookmarks ([Chrome](https://chrome.google.com/webstore/detail/syncmarx/llcdegcpeheociggfokjkkgciplhfdgg)
> and [Firefox](https://addons.mozilla.org/en-US/firefox/addon/syncmarx/)).
> 
> [NextCloud Bookmarks](https://apps.nextcloud.com/apps/bookmarks) has several community browser extensions,
> inducing [FreedomMarks](https://addons.mozilla.org/en-US/firefox/addon/freedommarks/) (Firefox) and
> [OwnCloud Bookmarks](https://chrome.google.com/webstore/detail/owncloud-bookmarks/eomolhpeokmbnincelpkagpapjpeeckc) (Chrome).
> 
> Finally, [Turtl Notes](https://turtlapp.com) has excellent link saving functionality built-in
> 
> [RainDrop](https://raindrop.io) is a fully-featured all-in-1 bookmarking and web-snip suite.
> It has a beautiful UI, good data controls and some very handy integrations and features.
> Available on desktop, mobile, web and through a browser extension.
> The catch is that it is not open source, there is a free and premium plan, but no option for self-hosting.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Secure Conference Calls

With the [many, many security issues with Zoom](https://www.tomsguide.com/uk/news/zoom-security-privacy-woes),
and other mainstream options, it becomes clear that a better, more private and secure alternative is required.
As with other categories, the "best video calling app" will be different
for each of us, depending on the ratio of performance + features to
security + privacy required in your situation.

- **[<img src='https://jami.net/assets/images/favicon/favicon-196x196.png?v=565055118b' width='16' height='16' alt='icon' /> Jami](https://jami.net)** - A free and open source, distributed video, calling and screenshare platform with a focus on security. Jami is
completely peer-to-peer, and has full end-to-end encryption with perfect forward secrecy for all communications,
complying with the X.509 standard. Supported natively on Windows, macOS, iOS, GNU/Linux, Android and Android TV.
Video quality is quite good, but very dependent on network speeds, some of the apps are lacking in features.
 	- [![GitHub: savoirfairelinux/jami-project](https://img.shields.io/github/stars/savoirfairelinux/jami-project?style=flat&logo=github&label=jami-project&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/savoirfairelinux/jami-project)
- **[<img src='https://jitsi.org/wp-content/uploads/2020/04/Jitsi-favicon-196-50x50.png' width='16' height='16' alt='icon' /> Jitsi](https://jitsi.org)** - Encrypted, free and open source video calling app, which does not require creating an account/ providing any personal
details. Available as a web app, and native app for Windows, MacOS, Linux, Android and iOS. You can use the public
Jitsi instance, self-host your own, or use a community hosted instance.
 	- [![GitHub: jitsi/jitsi-meet](https://img.shields.io/github/stars/jitsi/jitsi-meet?style=flat&logo=github&label=jitsi-meet&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/jitsi/jitsi-meet)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [Apache OpenMeetings](https://openmeetings.apache.org) provides self-hosted
> video-conferencing, chat rooms, file server and tools for meetings.
> 
> [together.brave.com](https://together.brave.com) is Brave's Jitsi Fork.
> 
> For remote learning, [BigBlueButton](https://bigbluebutton.org) is self-hosted conference call software,
> aimed specifically at schools and Universities.
> It allows for the host/ teacher to have full control over the session,
> and provides high-quality video streaming, multi-user whiteboards,
> breakout rooms, and instant chat.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Utilities

### Virtual Machines

A virtual machine (VM) is a sandboxed operating system, running within your
current system. Useful for compartmentalisation and safely testing software,
or handling potentially malicious files

- **[<img src='https://www.virtualbox.org/favicon.ico' width='16' height='16' alt='icon' /> VirtualBox](https://www.virtualbox.org)** - Open source, powerful, feature-rich virtualization product, supporting x86 and AMD64/Intel64 architectures.
Available for Windows, MacOS, Linux and BSD, and free for both personal and enterprise use. VirtualBox is
backed by a strong community, and has been under active development since 2007.
 - **[<img src='https://gitlab.com/uploads/-/system/group/avatar/1147069/pngegg.png?width=48' width='16' height='16' alt='icon' /> Xen Project](https://xenproject.org)** - Open source virtual machine monitor intended to serve as a type-1 hyperviser for multiple operating systems
using the same hardware - very useful for servers, as it allows for fully independent virtual Linux machines.
 - **[<img src='https://mac.getutm.app/images/logo.png' width='16' height='16' alt='icon' /> UTM](https://mac.getutm.app)** - Open source, feature rich, powerful type 2 hypervisor for Mac, can emulate x86-64 OSes on Apple Silicon Macs.
There's also an [iOS](https://getutm.app/) version (so you can run Windows on your iPhone!)
 	- [![GitHub: utmapp/UTM](https://img.shields.io/github/stars/utmapp/UTM?style=flat&logo=github&label=UTM&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/utmapp/UTM)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [QEMU](https://wiki.qemu.org/Main_Page) is a virtual hardware emulation tool,
> meaning it is less appropriate for creating fully independant sandboxes,
> but performance is considerable better than that of a traditional virtual machine.
> 
> [VMWare](https://www.vmware.com/) is popular in the enterprise world,
> it is not open source, and although there is a free version, a license
> is required to access all features. VMWare performs very well when running
> on a server, with hundreds of hosts and users.
> 
> For Mac users, [Parallels](https://www.parallels.com/uk/) is a popular
> option which performs really well, but again is not open source.
> 
> For Windows users, there's
> [Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/quick-start/enable-hyper-v),
> which is a native Windows product, developed by Microsoft.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### PGP Managers

Tools for signing, verifying, encrypting and decrypting text and files using [GnuPG](https://www.gnupg.org) standard

- **[<img src='https://wiki.gnome.org/Apps/Seahorse?action=AttachFile&do=get&target=seahorse-icon.png' width='16' height='16' alt='icon' /> SeaHorse](https://wiki.gnome.org/Apps/Seahorse)** - Application for managing encryption keys and passwords, integrated with the GNOME Keyring.
 - **[<img src='https://apps.kde.org/app-icons/org.kde.kleopatra.svg' width='16' height='16' alt='icon' /> Kleopatra](https://apps.kde.org/kleopatra)** - Certificate manager and a universal crypto GUI. It supports managing X.509 and OpenPGP certificates in the GpgSM
keybox and retrieving certificates from LDAP servers.
 - **[<img src='https://www.gpg4win.org/favicon.png' width='16' height='16' alt='icon' /> GPG4Win](https://www.gpg4win.org)** - Kleopatra ported to Windows.
 	- [![GitHub: gpg/gpg4win](https://img.shields.io/github/stars/gpg/gpg4win?style=flat&logo=github&label=gpg4win&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/gpg/gpg4win)
- **[<img src='https://gpgtools.org/favicon-152.png' width='16' height='16' alt='icon' /> GPG Suite](https://gpgtools.org)** - Successor of MacGPG. Plays nice with MacOS apps, including Finder, Appple Mail, Keychain and Spotlight.
Makes encrypting files, emails, and messages / data very easy.
As well as GUI for generating keys, verifying signatures, etc.
 - **[<img src='https://icon.horse/icon/www.openkeychain.org' width='16' height='16' alt='icon' /> OpenKeychain](https://www.openkeychain.org)** - Android app for managing keys, and encrypting messages.
Works both stand-alone, and as integrated into other apps, including k9-Mail.
Everything can be done through a simple yet powerful GUI.
Open source, security audited, transparent permissions, and activley maintained.
 	- [![GitHub: open-keychain/open-keychain](https://img.shields.io/github/stars/open-keychain/open-keychain?style=flat&logo=github&label=open-keychain&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/open-keychain/open-keychain)
- **[<img src='https://www.pgpeverywhere.com/i/favicon/favicon-16x16.png' width='16' height='16' alt='icon' /> PGP Everywhere](https://www.pgpeverywhere.com)** - iOS app for encrypting/ decrypting text.
Has native keyboard integration, keychain support and app integrations which makes it quick to use in any app.
 - **[<img src='https://flowcrypt.com/img/favicons/apple-touch-icon.png?version=69' width='16' height='16' alt='icon' /> FlowCrypt](https://flowcrypt.com)** - Browser extension for using PGP within Gmail, for Chrome and Firefox.
Mobile version supported on Android and iOS.
 	- [![GitHub: FlowCrypt/flowcrypt-browser](https://img.shields.io/github/stars/FlowCrypt/flowcrypt-browser?style=flat&logo=github&label=flowcrypt-browser&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/FlowCrypt/flowcrypt-browser)
- **[<img src='https://enigmail.net/favicon.ico' width='16' height='16' alt='icon' /> EnigMail](https://enigmail.net)** - OpenPGP extension for Thunderbird and PostBox, integrates natively within mail app.
 - **[<img src='https://icon.horse/icon/www.mailvelope.com' width='16' height='16' alt='icon' /> Mailvelope](https://www.mailvelope.com)** - Mailvelope is an addon for email applications, that makes using PGP very easy for beginners. You can use the hosted
version for free, or opt to host your own instance.
Works with Gmail, Yahoo, Outlook, GMX, Posteo, Web.de, FreeNet.de, Mailbox.org and [many others](https://mailvelope.com/en/faq#mailer_list).
 	- [![GitHub: mailvelope/mailvelope](https://img.shields.io/github/stars/mailvelope/mailvelope?style=flat&logo=github&label=mailvelope&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mailvelope/mailvelope)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Metadata Removal

[Exif](https://en.wikipedia.org/wiki/Exif)/ [Metadata](https://en.wikipedia.org/wiki/Metadata)
is "data about data", this additional information attached to files can
lead us to
[share significantly more information than we intended](https://gizmodo.com/vice-magazine-just-accidentally-revealed-where-john-mca-5965295) to.

For example, if you upload an image of a sunset to the internet, but don't remove the metadata,
it [may reveal the location](https://www.nytimes.com/2010/08/12/technology/personaltech/12basics.html?_r=1) (GPS lat + long)
of where it was taken, the device is was taken on, precise camera data, details about modifications and the
picture source + author. Social networks that remove metadata from your photos, often collect and store it,
for their own use.
This could obviously pose a security risk, and that is why it is recommended to strip out this data from a file before sharing.

- **[<img src='https://exifcleaner.com/images/favicon.ico' width='16' height='16' alt='icon' /> ExifCleaner](https://exifcleaner.com)** - Cross-platform, open source, performant EXIF meta data removal tool. This GUI tool makes cleaning media files really
easy, and has great batch process support. Created by @szTheory, and uses ExifTool.
 	- [![GitHub: szTheory/exifcleaner](https://img.shields.io/github/stars/szTheory/exifcleaner?style=flat&logo=github&label=exifcleaner&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/szTheory/exifcleaner)
- **[<img src='https://icon.horse/icon/exiftool.org' width='16' height='16' alt='icon' /> ExifTool](https://exiftool.org)** - Platform-independent open source Perl library & CLI app, for reading, writing and editing meta data. Built by Phill
Harvey. Very good performance, and supports all common metadata formats. An official GUI application is available
for Windows, implemented by Bogdan Hrastnik.
 	- [![GitHub: exiftool/exiftool](https://img.shields.io/github/stars/exiftool/exiftool?style=flat&logo=github&label=exiftool&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/exiftool/exiftool)
- **[<img src='https://imageoptim.com/icon.png' width='16' height='16' alt='icon' /> ImageOptim](https://imageoptim.com/mac)** - Native MacOS app, with drag 'n drop image optimization and meta data removal.
 	- [![GitHub: ImageOptim/ImageOptim](https://img.shields.io/github/stars/ImageOptim/ImageOptim?style=flat&logo=github&label=ImageOptim&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/ImageOptim/ImageOptim)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> It's possible (but slower) to do this without a third-party tool.
> For Windows, right click on a file, and go to: `Properties --> Details --> Remove Properties --> Remove from this File --> Select All --> OK`.
> 
> Alternatively, with [ImageMagic](https://imagemagick.org) installed, just run
> `convert -strip path/to/image.png` to remove all metadata.
> 
> If you have [GIMP](https://www.gimp.org) installed, then just go to `File --> Export As --> Export --> Advanced Options --> Uncheck the "Save EXIF data" option`.
> 
> Often you need to perform meta data removal programmatically, as part of a script or automation process.  
> - GoLang: [go-exif](https://github.com/dsoprea/go-exif) by @dsoprea
> - JS: [exifr](https://github.com/MikeKovarik/exifr) by @MikeKovarik
> - Python: [Piexif](https://github.com/hMatoba/Piexif) by @hMatoba
> - Ruby: [Exif](https://github.com/tonytonyjan/exif) by @tonytonyjan
> - PHP: [Pel](https://github.com/pel/pel) by @mgeisler
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Data Erasers

Simply deleting data, does
[not remove it](https://uk.norton.com/internetsecurity-privacy-is-my-personal-data-really-gone-when-its-deleted-from-a-device.html)
from the disk, and recovering deleted files is a
[simple task](https://www.lifewire.com/how-to-recover-deleted-files-2622870).

Therefore, to protect your privacy, you should erase/ overwrite data from
the disk, before you destroy, sell or give away a hard drive.

- **[<img src='https://eraser.heidi.ie/wp-content/uploads/2015/06/favicon.ico' width='16' height='16' alt='icon' /> Eraser](https://eraser.heidi.ie)** - Allows you to completely remove sensitive data from your hard drive by overwriting it several times with carefully
selected patterns.
 	- [![GitHub: gtrant/eraser](https://img.shields.io/github/stars/gtrant/eraser?style=flat&logo=github&label=eraser&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/gtrant/eraser)
- **[<img src='https://icon.horse/icon/www.summitcn.com' width='16' height='16' alt='icon' /> Hard Disk Scrubber](http://www.summitcn.com/hdscrub.html)** - Easy to use, but with some advanced features, including custom wipe patterns. Data Sanitation Methods: AFSSI-5020,
DoD 5220.22-M, and Random Data.
 - **[<img src='https://learn.microsoft.com/favicon.ico' width='16' height='16' alt='icon' /> SDelete](https://docs.microsoft.com/en-us/sysinternals/downloads/sdelete)** - Microsoft Secure Delete is a CLI utility, uses DoD 5220.22-M.
 - **[<img src='https://schiffer.tech/img/logos/ow.jpg' width='16' height='16' alt='icon' /> OW Shredder](https://schiffer.tech/ow-shredder.html)** - File, folder and drive portable eraser for Windows. Bundled with other tools to scan, analyze, and wipe, and other
traces that were left behind. Includes context menu item, recycle bin integration.
 - **[<img src='https://icon.horse/icon/dban.org' width='16' height='16' alt='icon' /> DBAN](https://dban.org)** - Darik's Boot and Nuke ("DBAN") is a self-contained boot disk that securely wipes the hard disks of most computers.
DBAN will automatically and completely delete the contents of any hard disk that it can detect, which makes it an
appropriate utility for bulk or emergency data destruction. DBAN is the free edition of Blanco, which is an enterprise
tool designed for legal compliance.
 - **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> nwipe](https://github.com/martijnvanbrummelen/nwipe)** - C-based secure light-weight disk eraser, operated through the easy-to-use CLI or a GUI interface.
 	- [![GitHub: martijnvanbrummelen/nwipe](https://img.shields.io/github/stars/martijnvanbrummelen/nwipe?style=flat&logo=github&label=nwipe&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/martijnvanbrummelen/nwipe)
- **[<img src='https://www.gnu.org/favicon.ico' width='16' height='16' alt='icon' /> shred](https://www.gnu.org/software/coreutils/manual/html_node/shred-invocation.html)** - A CLI utility that can be used to securely delete files and devices, to make them extremely difficult to recover.
 - **[<img src='https://icon.horse/icon/www.systutorials.com' width='16' height='16' alt='icon' /> Secure Remove](https://www.systutorials.com/docs/linux/man/1-srm/)** - CLI utility for securely removing files, directories and whole disks, works on Linux, BSD and MacOS.
 - **[<img src='https://drfone.wondershare.com/favicon.ico' width='16' height='16' alt='icon' /> Mr. Phone](https://drfone.wondershare.com)** - Proprietary, closed-source suite of forensic data tools for mobile. The data eraser allows for both Android and iOS to
be fully wiped, through connecting them to a PC.
 
<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> There's no need to use a third-party tool. You can boot into a UNIX-based
> system, mount the disk you need to erase, and use a command to write it
> with arbitrary data. For best results, this process should be repeated
> several times. This is a good way to wipe a disk, before selling or
> destroying it, to protect your data.
> 
> Such as the [`dd`](https://en.wikipedia.org/wiki/Dd_%28Unix%29) command,
> is a tool to convert and copy files, but running
> `sudo dd if=/dev/zero of=/dev/sdX bs=1M` will quickly overwrite the whole disk with zeros.
> Or [badblocks](https://linux.die.net/man/8/badblocks) which is intended to search for all bad blocks,
> but can also be used to write zeros to a disk,
> by running `sudo badblocks -wsv /dev/sdd`.
> 
> An effective method of erasing an SSD, it to use [hdparm](https://en.wikipedia.org/wiki/Hdparm)
> to issue a [secure erase](https://en.wikipedia.org/wiki/Parallel_ATA#HDD_passwords_and_security)
> command, to your target storage device,
> for this, see step-by-step instructions via: [wiki.kernel.org](https://ata.wiki.kernel.org/index.php/ATA_Secure_Erase).
> 
> Finally, [srm](https://www.systutorials.com/docs/linux/man/1-srm/) can be
> use to securely remove files or directories, just run `srm -zsv /path/to/file`
> for a single pass over.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Operating Systems

### Mobile Operating Systems

If you are an Android user, your device has Google built-in at its core.
[Google tracks you](https://digitalcontentnext.org/blog/2018/08/21/google-data-collection-research/),
collecting a wealth of information, and logging your every move.

A [custom ROM](https://en.wikipedia.org/wiki/List_of_custom_Android_distributions),
is an open source, usually Google-free mobile OS that can be flashed to your device.

- **[<img src='https://grapheneos.org/apple-touch-icon.png' width='16' height='16' alt='icon' /> GrapheneOS](https://grapheneos.org/)** - GrapheneOS is an open source privacy and security focused mobile OS with Android app compatibility. Developed by Daniel Micay. 
GrapheneOS is a young project, and currently only supports Pixel devices, partially due to their strong hardware security.
 	- [![GitHub: GrapheneOS/hardened_malloc](https://img.shields.io/github/stars/GrapheneOS/hardened_malloc?style=flat&logo=github&label=hardened_malloc&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/GrapheneOS/hardened_malloc)
- **[<img src='https://calyxos.org/assets/images/favicon/apple-touch-icon.png' width='16' height='16' alt='icon' /> CalyxOS](https://calyxos.org)** - CalyxOS is an free and open source Android mobile operating system that puts privacy and security into the hands of everyday users. 
Plus, proactive security recommendations and automatic updates take the guesswork out of keeping your personal data personal. Also currently 
only supports Pixel devices and Xiaomi Mi A2 with Fairphone 4, OnePlus 8T, OnePlus 9 test builds available. Developed by the Calyx Foundation.
 	- [![GitHub: CalyxOS/calyxos](https://img.shields.io/github/stars/CalyxOS/calyxos?style=flat&logo=github&label=calyxos&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/CalyxOS/calyxos)
- **[<img src='https://divestos.org/images/favicon.png' width='16' height='16' alt='icon' /> DivestOS](https://divestos.org)** - DivestOS is a vastly diverged unofficial more secure and private soft fork of LineageOS. DivestOS primary goal is prolonging the life-span of 
discontinued devices, enhancing user privacy, and providing a modest increase of security where/when possible. Project is developed and maintained 
solely by Tad (SkewedZeppelin) since 2014.
 	- [![GitHub: Divested-Mobile/DivestOS-Build](https://img.shields.io/github/stars/Divested-Mobile/DivestOS-Build?style=flat&logo=github&label=DivestOS-Build&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Divested-Mobile/DivestOS-Build)
- **[<img src='https://www.lineageos.org/images/logo.png' width='16' height='16' alt='icon' /> LineageOS](https://www.lineageos.org)** - A free and open-source operating system for various devices, based on the Android mobile platform - Lineage is light-weight, well maintained, 
supports a wide range of devices, and comes bundled with Privacy Guard.
 	- [![GitHub: LineageOS/android](https://img.shields.io/github/stars/LineageOS/android?style=flat&logo=github&label=android&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/LineageOS/android)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> It is not recommended to root, or flash your device with a custom ROM if you are not an advanced user.
There are risks involved
- Although the above ROMs omit Google, they do open up other security issues: Without DM-verity on the system partition, the file system *could* be tampered with, and no verified boot stack, the kernel/initramfs also *could* be edited. You should understand the risks, before proceeding to flash a custom ROM to your device
- You will need to rely on updates from the community, which could be slower to be released - this may be an issue for a time-urgent, security-critical patch
- It is also possible to brick your device, through interrupted install or bad software
- Finally, rooting and flashing your device, will void your warranty


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [Replicant OS](https://www.replicant.us/) is a fully-featured distro,
> with an emphasis on freedom, privacy and security.
> 
> [OmniRom](https://www.omnirom.org/),
> [Resurrection Remix OS](https://resurrectionremix.com/)
> and [Paranoid Android](http://paranoidandroid.co/) are also popular options.
> 
> Alternatively, [Ubuntu Touch](https://ubports.com/) is a Linux (Ubuntu)- based OS.
> It is secure by design and runs on almost any device, - but it does fall short when it comes to the app store.
> 
> To install apps on the Play Store without using the Play Store app see
> [Aurora Store](https://gitlab.com/AuroraOSS/AuroraStore).
> For Google Play Service see [MicroG](https://microg.org/)
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Desktop Operating Systems

Windows and MacOS have many features that violate your privacy.
Microsoft and Apple are able to collect all your data (including, but not
limited to: keystrokes, searches and mic input, calendar data, music,
photos, credit card information and purchases, identity, passwords, contacts,
conversations and location data). Microsoft Windows is also more susceptible
to malware and viruses, than alternative systems.

Switching to Linux is a great choice in terms of security and privacy -
you don't need necessarily need to use a security distro, any well-maintained
stable distro is going to be considerably better than a proprietary OS

- **[<img src='https://icon.horse/icon/www.qubes-os.org' width='16' height='16' alt='icon' /> Qubes OS](https://www.qubes-os.org/)** - Open-source security-oriented operating system for single-user desktop computing. It uses virtualisation,
to run each application in its own compartment to avoid data being leaked. It features Split GPG, U2F Proxy,
and Whonix integration. Qubes makes is easy to create disposable VMs which are spawned quickly and destroyed
when closed. Qubes is recommended by Edward Snowden.
 - **[<img src='https://icon.horse/icon/www.whonix.org' width='16' height='16' alt='icon' /> Whonix](https://www.whonix.org/)** - Whonix is an anonymous operating system, which can run in a VM, inside your current OS. It is the best way to
use Tor, and provides very strong protection for your IP address. It comes bundled with other features too:
Keystroke Anonymization, Time Attack Defences, Stream Isolation, Kernel Self Protection Settings and an Advanced
Firewall. Open source, well audited, and with a strong community - Whonix is based on Debian, KickSecure and Tor.
 - **[<img src='https://icon.horse/icon/tails.boum.org' width='16' height='16' alt='icon' /> Tails](https://tails.boum.org/)** - Tails is a live operating system (so you boot into it from a USB, instead of installing). It preserves your
privacy and anonymity through having no persistent memory/ leaving no trace on the computer. Tails has Tor
built-in system-wide, and uses state-of-the-art cryptographic tools to encrypt your files, emails and instant
messaging. Open source, and built on top of Debian. Tails is simple to stop, configure and use.
 - **[<img src='https://icon.horse/icon/parrotlinux.org' width='16' height='16' alt='icon' /> Parrot](https://parrotlinux.org/)** - Parrot Linux, is a full Debian-based operating system, that is geared towards security, privacy and development.
It is fully-featured yet light-weight, very open. There are 3 editions: General Purpose, Security and Forensic.
The Secure distribution includes its own sandbox system obtained with the combination of Firejail and AppArmor
with custom security profiles. While the Forensics Edition is bundled with a comprehensive suite of security/
pen-testing tools, similar to Kali and Black Arch.
 - **[<img src='https://icon.horse/icon/www.privacy-cd.org' width='16' height='16' alt='icon' /> Discreete Linux](https://www.privacy-cd.org/)** - Aimed at journalists, activists and whistle-blowers, Discreete Linux is similar to Tails, in that it is booted
live from external media, and leaves no/ minimal trace on the system. The aim of the project, was to provide
all required cryptographic tools offline, to protect against Trojan-based surveillance.
 - **[<img src='https://icon.horse/icon/www.alpinelinux.org' width='16' height='16' alt='icon' /> Alpine Linux](https://www.alpinelinux.org/)** - Alpine is a security-oriented, lightweight distro based on musl libc and busybox. It compiles all user-space
binaries as position-independent executables with stack-smashing protection. Install and setup may be quite
complex for some new users.
 
<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [Septor](https://septor.sourceforge.io/) is a Debian-based distro with the
> KDE Plasma desktop environment, and Tor baked-in. Designed for surfing the
> web anonymously, and completing other internet-based activities (with
> Thunderbird, Ricochet IM, HexChat, QuiteRSS, OnionShare).
> Septor is light-weight, but comes bundled with all the essential privacy +
> security utilities (including: Gufw, Ark, Sweeper, KGpg, Kleopatra,
> KWallet, VeraCrypt, Metadata Anonymisation Toolkit and more).
> 
> [Subgraph OS](https://subgraph.com) is designed to be an *adversary resistant
> computing platform*, it includes strong system-wide attack mitigations,
> and all key applications run in sandbox environments. Subgraph is still
> in beta (at the time of writing), but still is well tested, and has some
> nice anonymization features
> 
> For defensive security, see [Kali](https://www.kali.org) and [BlackArch](https://blackarch.org),
> both are bundled with hundreds of security tools, ready for pretty much any job
> (not reccomended as a daily driver!)
> 
> Other security-focused distros include: [TENS OS](https://www.tens.af.mil/),
> [Fedora CoreOS](https://getfedora.org/coreos?stream=stable),
> [Kodachi](https://www.digi77.com/linux-kodachi/) and [IprediaOS](https://www.ipredia.org)
> (Avoid systems that are not being actively maintained)
> </details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> 
#### General Purpose Linux Distros
If you do not want to use a specalist security-based distro, or you are
new to Unix - then just switching to any well-maintained Linux distro,
is going to be significantly more secure and private than Windows or Mac OS.
Since it is open source, major distros are constantly being audited by
members of the community. Linux does not give users admin rights by default -
this makes is much less likely that your system could become infected with malware.
And of course, there is no proprietary Microsoft or Apple software constantly
monitoring everything you do.

Some good distros to consider would be: **[Fedora](https://getfedora.org/)**,
**[Debian](https://www.debian.org/)**, or **[Arch](https://www.archlinux.org/)**-
all of which have a large community behind them. **[Manjaro](https://manjaro.org/)**
(based of Arch) is a good option, with a simple install process, used by new comers,
and expers alike.
**[POP_OS](https://pop.system76.com/)** and **[PureOS](https://www.pureos.net/)**
are reasonably new general purpose Linux, with a strong focus on privacy, but also
very user-friendly with an intuitive interfac and install process.
See [Detailed Comparison](https://en.wikipedia.org/wiki/Comparison_of_Linux_distributions).

#### BSD
BSD systems arguably have far superior network stacks.
**[OpenBSD](https://www.openbsd.org)** is designed for maximum security —
not just with its features, but with its implementation practices.
It's a commonly used OS by banks and critical systems.
**[FreeBSD](https://www.freebsd.org)** is more popular, and aims for high
performance and ease of use.

#### Windows
Two alternative options for Windows users are Windows 10 AME (ameliorated)
project and the LTSC stream.
- **[Windows 10 AME](https://ameliorated.info/)** AME project aims at delivering
a stable, non-intrusive yet fully functional build of Windows 10 to anyone,
who requires the Windows operating system natively. Core applications, such
as the included Edge web-browser, Windows Media Player, Cortana, as well as
any appx applications (appx apps will no longer work), have also been successfully
eliminated. The total size of removed files is about 2 GB. Comes as a pre-built
ISO or option to build from scratch with de-bloat scripts. Strong, supportive
community on Telegram.
- **[Windows 10 LTSC](https://docs.microsoft.com/en-us/windows/whats-new/ltsc/)**
LTSC provides several security benefits over a standard Win 10 Installation.
LTSC or Long Term Servicing Channel is a lightweight, low-cost Windows 10
version, that is intended for specialized systems, and receives less regular
feature updates. What makes it appealing, is that it doesn't come with any
bloatware or non-essential applications, and needs to be configured from the
ground up by the user. This gives you much better control over what is running
on your system, ultimately improving security and privacy. It also includes
several enterprise-grade
[security features](https://docs.microsoft.com/en-us/windows/whats-new/ltsc/whats-new-windows-10-2019#security),
which are not available in a standard Windows 10 instance. It does require
some technical knowledge to get started with, but once setup should perform
just as any other Windows 10 system. Note that you should only download the
LTSC ISO from the Microsoft's
[official page](https://www.microsoft.com/en-in/evalcenter/evaluate-windows-10-enterprise) 


#### Improve the Security and Privacy of your current OS
After installing your new operating system, or if you have chosen to stick
with your current OS, there are a couple of things you can do to improve security.
See: [Windows 10 security guide](https://heimdalsecurity.com/en/windows-10-security-guide/privacy),
[Mac OS security guide](https://spreadprivacy.com/mac-privacy-tips/) or
[Linux security guide](https://spreadprivacy.com/linux-privacy-tips/).
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Linux Defenses

- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Firejail](https://github.com/netblue30/firejail)** - Firejail is a SUID sandbox program that reduces the risk of security breaches by restricting the running environment
of untrusted applications using Linux namespaces and seccomp-bpf. Written in C, virtually no dependencies, runs on any
modern Linux system, with no daemon running in the background, no complicated configuration, and it's super lightweight
and super secure, since all actions are implemented by the kernel. It includes security profiles for over 800 common
Linux applications. FireJail is recommended for running any app that may potential pose some kind of risk, such as
torrenting through Transmission, browsing the web, opening downloaded attachments.
 	- [![GitHub: netblue30/firejail](https://img.shields.io/github/stars/netblue30/firejail?style=flat&logo=github&label=firejail&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/netblue30/firejail)
- **[<img src='https://icon.horse/icon/gufw.org' width='16' height='16' alt='icon' /> Gufw](http://gufw.org)** - Open source GUI firewall for Linux, allowing you to block internet access for certain applications. Supports both simple
and advanced mode, GUI and CLI options, very easy to use, lightweight/ low-overhead, under active maintenance and backed
by a strong community. Installable through most package managers, or compile from source.
 - **[<img src='https://icon.horse/icon/gitlab.com' width='16' height='16' alt='icon' /> ClamTk](https://gitlab.com/dave_m/clamtk/-/wikis/home)** - ClamTk is basically a graphical front-end for ClamAV, making it an easy to use, light-weight, on-demand virus scanner
for Linux systems.
 	- [![GitHub: dave_m/clamtk](https://img.shields.io/github/stars/dave_m/clamtk?style=flat&logo=github&label=clamtk&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/dave_m/clamtk)
- **[<img src='https://icon.horse/icon/www.chkrootkit.org' width='16' height='16' alt='icon' /> chkrootkit](http://www.chkrootkit.org)** - Locally checks for signs of a rootkit.
 - **[<img src='https://icon.horse/icon/www.snort.org' width='16' height='16' alt='icon' /> Snort](https://www.snort.org)** - Open source intrusion prevention system capable of real-time traffic analysis and packet logging.
 - **[<img src='https://icon.horse/icon/www.bleachbit.org' width='16' height='16' alt='icon' /> BleachBit](https://www.bleachbit.org)** - Clears cache and deletes temporary files very effectively. This frees up disk space, improves performance, but most
importantly helps to protect privacy.
 
<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [SecTools.org](https://sectools.org) is a directory or popular Unix security tools.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Windows Defences

- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Windows Spy Blocker](https://github.com/crazy-max/WindowsSpyBlocker)** - Capture and interprets network traffic based on a set of rules, and depending on the interactions certain assignments are blocked.
Open source, written in Go and delivered as a single executable.
 	- [![GitHub: crazy-max/WindowsSpyBlocker](https://img.shields.io/github/stars/crazy-max/WindowsSpyBlocker?style=flat&logo=github&label=WindowsSpyBlocker&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/crazy-max/WindowsSpyBlocker)
- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> HardenTools](https://github.com/securitywithoutborders/hardentools)** - A utility that disables a number of risky Windows features. These "features" are exposed by the OS and primary consumer applications,
and very commonly abused by attackers, to execute malicious code on a victim's computer. So this tool just reduces the attack surface by disabling the low-hanging fruit.
 	- [![GitHub: securitywithoutborders/hardentools](https://img.shields.io/github/stars/securitywithoutborders/hardentools?style=flat&logo=github&label=hardentools&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/securitywithoutborders/hardentools)
- **[<img src='https://icon.horse/icon/www.oo-software.com' width='16' height='16' alt='icon' /> ShutUp10](https://www.oo-software.com/en/shutup10)** - A portable app that lets you disable core Windows features (such as Cortana, Edge) and control which data is passed to Microsoft.
(Note: Free, but not open source).
 - **[<img src='https://icon.horse/icon/wpd.app' width='16' height='16' alt='icon' /> WPD](https://wpd.app/)** - Portable app with a GUI, that makes it really easy to safely block key telemetry features, from sending data to Microsoft and other third parties
(It uses the Windows API to interact with key features of Local Group Police, Services, Tasks Scheduler, etc).
 - **[<img src='https://icon.horse/icon/schiffer.tech' width='16' height='16' alt='icon' /> GhostPress](https://schiffer.tech/ghostpress.html)** - Anti low-level keylogger: Provides full system-wide key press protection, and target window screenshot protection.
 - **[<img src='https://icon.horse/icon/www.qfxsoftware.com' width='16' height='16' alt='icon' /> KeyScrambler](https://www.qfxsoftware.com)** - Provides protection against software keyloggers. Encrypts keypresses at driver level, and decrypts at application level, to protect against common keyloggers.
 - **[<img src='https://icon.horse/icon/www.aplin.com.au' width='16' height='16' alt='icon' /> SafeKeys V3.0](http://www.aplin.com.au)** - Portable virtual keyboard. Useful for protecting from keyloggers when using a public computer, as it can run of a USB with no administrative permissions.
 - **[<img src='https://icon.horse/icon/www.bleepingcomputer.com' width='16' height='16' alt='icon' /> RKill](https://www.bleepingcomputer.com/download/rkill/)** - Useful utility, that attempts to terminate known malware processes, so that your normal security software can then run and clean your computer of infections.
 - **[<img src='https://icon.horse/icon/www.nartac.com' width='16' height='16' alt='icon' /> IIS Crypto](https://www.nartac.com/Products/IISCrypto)** - A utility for configuring encryption protocols, cyphers, hashing methods, and key exchanges for Windows components. Useful for sysadmins on Windows Server.
 - **[<img src='https://icon.horse/icon/www.netlimiter.com' width='16' height='16' alt='icon' /> NetLimiter](https://www.netlimiter.com)** - Internet traffic control and monitoring tool.
 - **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Sticky-Keys-Slayer](https://github.com/linuz/Sticky-Keys-Slayer)** - Scans for accessibility tools backdoors via RDP.
 	- [![GitHub: linuz/Sticky-Keys-Slayer](https://img.shields.io/github/stars/linuz/Sticky-Keys-Slayer?style=flat&logo=github&label=Sticky-Keys-Slayer&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/linuz/Sticky-Keys-Slayer)
- **[<img src='https://icon.horse/icon/docs.microsoft.com' width='16' height='16' alt='icon' /> SigCheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck)** - A CLI utility that shows file version number, timestamp information, and digital signature details.
 - **[<img src='https://icon.horse/icon/www.bleachbit.org' width='16' height='16' alt='icon' /> BleachBit](https://www.bleachbit.org)** - Clears cache and deletes temporary files very effectively. This frees up disk space, improves performance, but most importantly helps to protect privacy.
 - **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Windows Secure Baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline)** - Group Policy objects, compliance checks, and configuration tools that provide an automated and flexible approach for securely deploying and maintaining the latest releases of Windows 10.
 	- [![GitHub: nsacyber/Windows-Secure-Host-Baseline](https://img.shields.io/github/stars/nsacyber/Windows-Secure-Host-Baseline?style=flat&logo=github&label=Windows-Secure-Host-Baseline&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/nsacyber/Windows-Secure-Host-Baseline)
- **[<img src='https://icon.horse/icon/www.usb-antivirus.com' width='16' height='16' alt='icon' /> USBFix](https://www.usb-antivirus.com/)** - Detects infected USB removable devices.
 - **[<img src='https://icon.horse/icon/www.gmer.net' width='16' height='16' alt='icon' /> GMER](http://www.gmer.net)** - Rootkit detection and removal utility.
 - **[<img src='https://icon.horse/icon/schiffer.tech' width='16' height='16' alt='icon' /> ScreenWings](https://schiffer.tech/screenwings.html)** - Blocks malicious background applications from taking screenshots.
 - **[<img src='https://icon.horse/icon/schiffer.tech' width='16' height='16' alt='icon' /> CamWings](https://schiffer.tech/camwings.html)** - Blocks unauthorized webcam access.
 - **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> SpyDish](https://github.com/mirinsoft/spydish)** - Open source GUI app built upon PowerShell, allowing you to perform a quick and easy privacy check, on Windows 10 systems.
 	- [![GitHub: mirinsoft/spydish](https://img.shields.io/github/stars/mirinsoft/spydish?style=flat&logo=github&label=spydish&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mirinsoft/spydish)
- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> SharpApp](https://github.com/mirinsoft/sharpapp)** - Open source GUI app built upon PowerShell, for disabling telemetry functions in Windows 10, uninstalling preinstalled apps, installing software packages and automating Windows tasks with integrated PowerShell scripting.
 	- [![GitHub: mirinsoft/sharpapp](https://img.shields.io/github/stars/mirinsoft/sharpapp?style=flat&logo=github&label=sharpapp&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mirinsoft/sharpapp)
- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Debotnet](https://github.com/Mirinsoft/Debotnet)** - Light-weight, portable app for controlling the many privacy-related settings within Windows 10- with the aim of helping to keep private data, private.
 	- [![GitHub: Mirinsoft/Debotnet](https://img.shields.io/github/stars/Mirinsoft/Debotnet?style=flat&logo=github&label=Debotnet&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Mirinsoft/Debotnet)
- **[<img src='https://icon.horse/icon/privazer.com' width='16' height='16' alt='icon' /> PrivaZer](https://privazer.com/)** - Good alternative to CCleaner, for deleting unnecessary data - logs, cache, history, etc.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> (The above software was last tested on 01/05/20).
Many of the above tools are not necessary or suitable for beginners,
and can cause your system to break - only use software that you need,
according to your threat model. Take care to only download from an
official/ legitimate source, verify the executable before proceeding,
and check reviews/ forums.
Create a system restore point, before making any significant changes to
your OS (such as disabling core features).

From a security and privacy perspective, Linux may be a better option.  


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> See also these lists:
> - [github.com/Awesome-Windows/Awesome#security](https://github.com/Awesome-Windows/Awesome#security)
> - [github.com/PaulSec/awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening)
> - [github.com/meitar/awesome-cybersecurity-blueteam#windows-based-defenses](https://github.com/meitar/awesome-cybersecurity-blueteam#windows-based-defenses)
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Mac OS Defences

- **[<img src='https://objective-see.org/images/logoApple.ico' width='16' height='16' alt='icon' /> LuLu](https://objective-see.com/products/lulu.html)** - Free, open source macOS firewall. It aims to block unknown outgoing connections, unless explicitly approved by the user.
 	- [![GitHub: objective-see/LuLu](https://img.shields.io/github/stars/objective-see/LuLu?style=flat&logo=github&label=LuLu&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/objective-see/LuLu)
- **[<img src='https://i.ibb.co/jVmsrYp/stronghold.png' width='16' height='16' alt='icon' /> Stronghold](https://github.com/alichtman/stronghold)** - Easily configure macOS security settings from the terminal.
 	- [![GitHub: alichtman/stronghold](https://img.shields.io/github/stars/alichtman/stronghold?style=flat&logo=github&label=stronghold&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/alichtman/stronghold)
- **[<img src='https://icon.horse/icon/github.com' width='16' height='16' alt='icon' /> Fortress](https://github.com/essandess/macOS-Fortress)** - Kernel-level, OS-level, and client-level security for macOS. With a Firewall, Blackhole, and Privatizing Proxy for Trackers, Attackers, Malware, Adware, and Spammers; with On-Demand and On-Access Anti-Virus Scanning.
 	- [![GitHub: essandess/macOS-Fortress](https://img.shields.io/github/stars/essandess/macOS-Fortress?style=flat&logo=github&label=macOS-Fortress&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/essandess/macOS-Fortress)

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Anti-Malware

Cross-platform, open source malware detection and virus prevention tools

- **[<img src='https://www.clamav.net/assets/clamav-trademark.png' width='16' height='16' alt='icon' /> ClamAV](https://www.clamav.net)** - An open source cross-platform antivirus engine for detecting viruses, malware & other malicious threats. It is versatile, performant and very effective.
 - **[<img src='https://www.virustotal.com/gui/images/manifest/icon-192x192.png' width='16' height='16' alt='icon' /> VirusTotal](https://www.virustotal.com)** - Web-based malware scanner, that inspects files and URLs with over 70 antivirus scanners, URL/domain services, and other tools to extract signals and determine the legitimacy.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> For Microsoft Windows, Windows Defender provides totally adequate virus
protection in most cases. These tools are intended for single-use in
detecting/ removing threats on an infected machine, and are not recommended
to be left running in the background, use portable editions where available.

Many anti virus products have a history of introducing vulnerabilities themselves,
and several of them seriously degrade the performance of your computer, as well as
decrease your privacy. Never use a free anti-virus, and never trust the companies
that offer free solutions, even if you pay for the premium package.
This includes (but not limited to) Avast, AVG, McAfee and Kasperky.
For AV to be effective, it needs intermate access to all areas of your PC,
so it is important to go with a trusted vendor, and monitor its activity closely. 


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> For 1-off malware scans on Windows, [MalwareBytes](https://www.malwarebytes.com)
> is portable and very effective, but [not open source](https://forums.malwarebytes.com/topic/5495-open-source)
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Development

### Code Hosting

- **[<img src='https://sr.ht/static/logo.svg' width='16' height='16' alt='icon' /> SourceHut](https://sourcehut.org)** - Git and mercurial code hosting, task management, mailing lists, wiki hosting and Alpine-based build pipelines. Can be self-hosted, or used through the managed instance at sr.ht.
 - **[<img src='https://codeberg.org/assets/img/favicon.svg' width='16' height='16' alt='icon' /> Codeberg](https://codeberg.org)** - A fully-managed instance of Forgejo.
 - **[<img src='https://icon.horse/icon/gitlab.com' width='16' height='16' alt='icon' /> GitLab](https://gitlab.com)** - Fully-featured git, CI and project management platform. Managed instance available, but can also be self-hosted.
 - **[<img src='https://icon.horse/icon/gitea.io' width='16' height='16' alt='icon' /> Gitea](https://gitea.io/)** - Lightweight self-hosted git platform, written in Go.
 - **[<img src='https://icon.horse/icon/gogs.io' width='16' height='16' alt='icon' /> Gogs](https://gogs.io/)** - Lightweight self-hosted git platform, written in Go.
 
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### IDEs

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Terminal Emulators

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Smart Home & IoT

### Voice Assistants

Google Assistant, Alexa and Siri don't have the best
[reputation](https://srlabs.de/bites/smart-spies) when it comes to protecting
consumers privacy, there have been
[many recent breaches](https://www.theverge.com/2019/10/21/20924886/alexa-google-home-security-vulnerability-srlabs-phishing-eavesdropping).

For that reason it is recommended not to have these devices in your house.
The following are open source AI voice assistants, that aim to provide a
human voice interface while also protecting your privacy and security

- **[<img src='https://avatars.githubusercontent.com/u/14171097?s=200&v=4' width='16' height='16' alt='icon' /> Mycroft](https://mycroft-ai.gitbook.io/mark-ii)** - An open source privacy-respecting AI platform, compatible with a wide range of
devices including Raspberry Pi, desktop computers, or dedicated Mycroft hardware.
Actively developed, with extensive documentation and a broad skill set. Facilitates
easy development of new skills.
 	- [![GitHub: MycroftAI/mycroft-core](https://img.shields.io/github/stars/MycroftAI/mycroft-core?style=flat&logo=github&label=mycroft-core&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/MycroftAI/mycroft-core)
- **[<img src='https://icon.horse/icon/kalliope-project.github.io' width='16' height='16' alt='icon' /> Kalliope](https://kalliope-project.github.io)** - A modular, always-on, voice-controlled personal assistant geared towards home automation.
Optimized for Raspberry Pi, Debian, or Ubuntu. Skills are easily programmable in YAML,
though the library of pre-built add-ons is not as extensive.
 	- [![GitHub: kalliope-project/kalliope](https://img.shields.io/github/stars/kalliope-project/kalliope?style=flat&logo=github&label=kalliope&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/kalliope-project/kalliope)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> If you are building your own assistant, you may want to consider a hardware-switch
for disabling the microphone. Keep tabs on issues and check the code, to ensure
you are happy with how it works, from a privacy perspective.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> If you choose to continue using Google Home/ Alexa, then check out
> **[Project Alias](https://github.com/bjoernkarmann/project_alias)**.
> It's a small app that runs on a Pi, and gives you more control over your smart assistants, for both customisation and privacy.
> 
> For a desktop-based assistant, see
> [Dragonfire](https://github.com/DragonComputer/Dragonfire) for Ubuntu,
> and [Jarvis](https://github.com/sukeesh/Jarvis) for MacOS.
> 
> [LinTO](https://linto.ai), [Jovo](https://www.jovo.tech) and [Snips](https://snips.ai)
> are private-by-design voice assistant frameworks that can be built on by developers,
> or used by enterprises.
> 
> [Jasper](https://jasperproject.github.io),
> [Stephanie](https://github.com/SlapBot/stephanie-va) and
> [Hey Athena](https://github.com/rcbyron/hey-athena-client) are Python-based voice assistant, but neither is under active development anymore.
> See also [OpenAssistant](https://openassistant.org).
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Smart Home

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Finance

### Cryptocurrencies

- **[<img src='https://icon.horse/icon/www.getmonero.org' width='16' height='16' alt='icon' /> Monero](https://www.getmonero.org)** - One of the most private cryptocurrencies, since no meta data is available (not even the transaction amount). It uses complex on-chain cryptographic methods such as Ring signatures, RingCT, Kovri, and Stealth addresses all of which help protect the privacy of users.
 	- [![GitHub: monero-project/monero](https://img.shields.io/github/stars/monero-project/monero?style=flat&logo=github&label=monero&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/monero-project/monero)
- **[<img src='https://icon.horse/icon/z.cash' width='16' height='16' alt='icon' /> ZCash](https://z.cash)** - Uses zero-knowledge proofs to protect privacy cryptographic technique, that allows two users to transact without ever revealing their true identity or address. The Zcash blockchain uses two types of addresses and transactions, Z transactions and addresses are private and T transactions and addresses are transparent like Bitcoin.
 	- [![GitHub: zcash/zcash](https://img.shields.io/github/stars/zcash/zcash?style=flat&logo=github&label=zcash&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/zcash/zcash)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Not all cryptocurrencies are anonymous, and without using a privacy-focused coin,
a record of your transaction will live on a publicly available distributed ledger, forever.
If you send of receive multiple payments, ensure you switch up addresses or use a mixer,
to make it harder for anyone trying to trace your transactions.
Cryptocurrencies that allow private and public transactions may reveal meta
data about your transactions and balances when funds are moving from
private to public addresses which can compromise your privacy with methods
similar to a knapsack problem.

Always store private keys somewhere safe, but offline

Note: Cryptocurrency prices can go down. Storing any wealth in crypto may result in losses.
If you are new to digital currencies - do your research first, don't invest more than you can afford to loose,
and be very weary crypto-related scams are very common. as is and cryptocurrency-related malware.

**This is NOT financial advice**


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> Other privacy-focused cryptocurrencies include:
> [PIVX](https://pivx.org),
> [Verge](https://vergecurrency.com), and [Piratechain](https://pirate.black/). 
> </details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> It is still possible to use currencies that have a public ledger 'privately',
but you will need to take great care not to cause any transactions to be
linked with your identity or activity. For example, avoid exchanges that
require KYC, and consider using a service such as
[Local Bitcoins](https://localbitcoins.net).
If you use a [Bitcoin ATM](https://coinatmradar.com), then take care to not
be physically tracked (CCTV, phone location, card payments etc)
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Crypto Wallets

- **[<img src='https://wasabiwallet.io/img/favicon.ico' width='16' height='16' alt='icon' /> Wasabi Wallet](https://www.wasabiwallet.io)** - An open source, native desktop wallet for Windows, Linux, and MacOS. Wasabi implements trustless CoinJoins over the Tor network. Neither an observer nor the participants can determine which output belongs to which input. This makes it difficult for outside parties to trace where a particular coin originated from and where it was sent to, which greatly improves privacy. Since it's trustless, the CoinJoin coordinator cannot breach the privacy of the participants. Wasabi is compatible with cold storage and hardware wallets, including OpenCard and Trezor.
 	- [![GitHub: zkSNACKs/WalletWasabi](https://img.shields.io/github/stars/zkSNACKs/WalletWasabi?style=flat&logo=github&label=WalletWasabi&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/zkSNACKs/WalletWasabi)
- **[<img src='https://trezor.io/favicon/apple-touch-icon.png' width='16' height='16' alt='icon' /> Trezor](https://trezor.io)** - Open source, cross-platform, offline, crypto wallet, compatible with 1000+ coins. Your private key is generated on the device, and never leaves it, all transactions are signed by the Trezor, which ensures your wallet is safe from theft. There are native apps for Windows, Linux, MacOS, Android, and iOS, but Trezor is also compatible with other wallets, such as Wasabi. You can back the Trezor up, either by writing down the seed, or by duplicating it to another device. It is simple and intuitive to use, but also incredibly customizable with a large range of advanced features.
 	- [![GitHub: trezor/trezor-firmware](https://img.shields.io/github/stars/trezor/trezor-firmware?style=flat&logo=github&label=trezor-firmware&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/trezor/trezor-firmware)
- **[<img src='https://icon.horse/icon/coldcardwallet.com' width='16' height='16' alt='icon' /> ColdCard](https://coldcardwallet.com/)** - An easy-to-use, super secure Bitcoin hardware wallet, which can be used independently as an air-gapped wallet. ColdCard is based on partially signed Bitcoin transactions following the BIP174 standard. Built specifically for Bitcoin, and with a variety of unique security features, ColdCard is secure, trustless, private, and easy-to-use. Companion products for the ColdCard include: BlockClock, SeedPlate, and ColdPower.
 	- [![GitHub: Coldcard/firmware](https://img.shields.io/github/stars/Coldcard/firmware?style=flat&logo=github&label=firmware&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Coldcard/firmware)
- **[<img src='https://icon.horse/icon/electrum.org' width='16' height='16' alt='icon' /> Electrum](https://electrum.org/)** - Long-standing Python-based Bitcoin wallet with good security features. Private keys are encrypted and do not touch the internet and balance is checked with a watch-only wallet. Compatible with other wallets, so there is no tie-in, and funds can be recovered with your secret seed. It supports proof-checking to verify transactions using SPV, multi-sig, and add-ons for compatibility with hardware wallets. A decentralized server indexes ledger transactions, meaning it's fast and doesn't require much disk space. The potential security issue here would not be with the wallet, but rather your PC - you must ensure your computer is secure and your wallet has a long, strong passphrase to encrypt it with.
 	- [![GitHub: spesmilo/electrum](https://img.shields.io/github/stars/spesmilo/electrum?style=flat&logo=github&label=electrum&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/spesmilo/electrum)
- **[<img src='https://icon.horse/icon/samouraiwallet.com' width='16' height='16' alt='icon' /> Samourai Wallet](https://samouraiwallet.com/)** - An open-source, Bitcoin-only privacy-focused wallet, with some innovative features. Samourai Wallet works under any network conditions, with a full offline mode, useful for cold storage. It also supports a comprehensive range of privacy features including: STONEWALL that helps guard against address clustering deanonymization attacks, PayNym which allows you to receive funds without revealing your public address for all to see, Stealth Mode which hides Samourai from your devices launcher, Remote SMS Commands to wipe or recover your wallet if the device is seized or stolen, and Whirlpool which is similar to a coin mixer, and OpenDime is also supported for offline USB hardware wallets.
 	- [![GitHub: Samourai-Wallet/samourai-wallet-android](https://img.shields.io/github/stars/Samourai-Wallet/samourai-wallet-android?style=flat&logo=github&label=samourai-wallet-android&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Samourai-Wallet/samourai-wallet-android)
- **[<img src='https://icon.horse/icon/sparrowwallet.com' width='16' height='16' alt='icon' /> Sparrow Wallet](https://sparrowwallet.com/)** - Sparrow is a Bitcoin wallet for those who value financial self-sovereignty. Sparrow’s emphasis is on security, privacy, and usability. Sparrow does not hide information from you - on the contrary, it attempts to provide as much detail as possible about your transactions and UTXOs, but in a way that is manageable and usable.
 	- [![GitHub: sparrowwallet/sparrow](https://img.shields.io/github/stars/sparrowwallet/sparrow?style=flat&logo=github&label=sparrow&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/sparrowwallet/sparrow)
- **[<img src='https://icon.horse/icon/atomicwallet.io' width='16' height='16' alt='icon' /> Atomic Wallet](https://atomicwallet.io/)** - Atomic is an open-source desktop and mobile-based wallet, where your private keys are stored on your local device, and do not touch the internet. Atomic has a great feature set, and supports swapping, staking, and lending directly from the app. However, most of Atomic's features require an active internet connection, and Atomic does not support hardware wallets yet. Therefore, it may only be a good choice as a secondary wallet, for storing small amounts of your actively used currency.
 	- [![GitHub: Atomicwallet/bip38](https://img.shields.io/github/stars/Atomicwallet/bip38?style=flat&logo=github&label=bip38&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Atomicwallet/bip38)
- **[<img src='https://icon.horse/icon/cryptosteel.com' width='16' height='16' alt='icon' /> CryptoSteel](https://cryptosteel.com/how-it-works)** - A steel plate, with engraved letters which can be permanently screwed - CryptoSteel is a good fire-proof, shock-proof, water-proof, and stainless cryptocurrency backup solution.
 - **[<img src='https://icon.horse/icon/shiftcrypto.ch' width='16' height='16' alt='icon' /> BitBox02](https://shiftcrypto.ch/)** - Open source hardware wallet, supporting secure multisig with the option for making encrypted backups on a MicroSD card.
 	- [![GitHub: digitalbitbox/bitbox-wallet-app](https://img.shields.io/github/stars/digitalbitbox/bitbox-wallet-app?style=flat&logo=github&label=bitbox-wallet-app&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/digitalbitbox/bitbox-wallet-app)

<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Avoid using any online/ hot-wallet, as you will have no control over
the security of your private keys.

Offline paper wallets are very secure, but ensure you store it
properly - to keep it safe from theft, loss or damage.


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> [Metamask](https://metamask.io/) (Ethereum and ERC20 tokens) is a bridge
> that allows you to visit and interact with distributed web apps in your browser.
> Metamask has good hardware wallet support, so you can use it to swap, stake,
> sign, lend and interact with dapps without you're private key ever leaving your device.
> However the very nature of being a browser-based app means that you need to stay vigilant with what services you give access to.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Crypto Exchanges

- **[<img src='https://icon.horse/icon/bisq.network' width='16' height='16' alt='icon' /> Bisq](https://bisq.network)** - An open-source, peer-to-peer application that allows you to buy and sell
cryptocurrencies in exchange for national currencies. Fully decentralized,
and no registration required.
 - **[<img src='https://icon.horse/icon/localbitcoins.com' width='16' height='16' alt='icon' /> LocalBitcoins](https://localbitcoins.com/)** - Person-to-person exchange, find people local to your area, and trade
directly with them, to avoid going through any central organization.
Primarily focused on Bitcoin, Ethereum, Ripple, and LiteCoin,
as it gets harder to find people near you selling niche alt-coins.
 - **[<img src='https://icon.horse/icon/atomicdex.io' width='16' height='16' alt='icon' /> AtomicDEX](https://atomicdex.io/)** - Person-to-person cryptocurrency exchange with no KYC or registration
required and uses atomic swaps to perform trustless trades.
The orderbook uses a modified libp2p protocol to prevent censorship and maintain decentralization.
Fiat currencies are not supported, but hundreds of alt-coins and major cryptocurrencies are supported.
 	- [![GitHub: KomodoPlatform/atomicDEX-Pro](https://img.shields.io/github/stars/KomodoPlatform/atomicDEX-Pro?style=flat&logo=github&label=atomicDEX-Pro&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/KomodoPlatform/atomicDEX-Pro)
- **[<img src='https://icon.horse/icon/learn.robosats.com' width='16' height='16' alt='icon' /> RoboSats](https://learn.robosats.com)** - RoboSats is an easy way to privately exchange Bitcoin for national currencies.
It simplifies the peer-to-peer experience and makes use of lightning hold
invoices to minimize custody and trust requirements.
The deterministically generated avatars help users stick to best privacy practices.
 	- [![GitHub: RoboSats/robosats](https://img.shields.io/github/stars/RoboSats/robosats?style=flat&logo=github&label=robosats&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/RoboSats/robosats)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> For traders, [BaseFEX](https://www.basefex.com/) doesn't require ID and has a good privacy policy.
> 
> [BitMex](https://www.bitmex.com/) has more advanced trading features,
> but ID verification is required for higher value trades involving Fiat currency.
> 
> For buying and selling alt-coins, [Binance](https://www.binance.com/en/register?ref=X2BHKID1) has a wide range of currencies,
> ~and ID verification is not needed for small-value trades~ but ID verification is required in most countries.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Virtual Credit Cards

Virtual cards generated provide an extra layer of security, improve privacy
and help protect from fraud. Most providers have additional features,
such as single-use cards (that cannot be charged more than once),
card limits (so you can be sure you won't be charged more than you expected)
and other security controls.

In most countries KYC is required. The bank will of course be able to see all your transactions.
Be sure to read their privacy policy and terms of service beforehand.
Not all services are available in all countries.

- **[<img src='https://icon.horse/icon/privacy.com' width='16' height='16' alt='icon' /> Privacy.com](https://privacy.com)** - Privacy.com has a good reputation, and is the largest virtual card provider
in the US. Unlike other providers, it is free for personal use (up to 12 cards
per month) with no fees, apps and support is good. There is a premium plan
for $10/month, with 1% cashback and 36 cards/month.
 - **[<img src='https://icon.horse/icon/revolut.ngih.net' width='16' height='16' alt='icon' /> Revolut Premium](https://revolut.ngih.net)** - Revolut is more of a digital bank account, and identity checks are required
to sign up. Virtual cards are only available on Premium/ Metal accounts, which
start at $7/month.
 - **[<img src='https://icon.horse/icon/mysudo.com' width='16' height='16' alt='icon' /> MySudo](https://mysudo.com)** - Much more than just virtual cards, MySudo is a platform for creating
compartmentalised identities, each with their own virtual cards, virtual phone
numbers, virtual email addresses, messaging, private browsing, and more. There
is a free plan for up to 3 identities, and premium plans start at $0.99/month.
 
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Other Payment Methods

- **[<img src='https://i.ibb.co/GWcPjYs/cash.png' width='16' height='16' alt='icon' /> Cash](None)** - Actual physical cash is still the most private option, with no chance of leaving
any transactional records.
 - **[<img src='https://i.ibb.co/dKBV5Xq/gift-card.png' width='16' height='16' alt='icon' /> Gift Cards](None)** - Gift cards can be purchased for cash in many convenience stores, and redeemed
online for goods or services. Try to avoid CCTV as best as possible.
 - **[<img src='https://i.ibb.co/hm1gPsG/pre-paid.png' width='16' height='16' alt='icon' /> Pre-paid Cards](None)** - Similarly to gift cards, buying a pre-paid card for cash can enable you to
purchase goods and services in stores that only accept card payments.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Note that credit card providers heavily track transaction metadata, which build
up a detailed picture of each persons spending habits. This is done both to
provide improved fraud alerts, but also because the data is extremely valuable
and is often 'anonymized' and sold to 3rd parties. Hence your privacy is degraded
if these cards are used for daily transactions


</details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> Paying for goods and services is a good example of where privacy and security conflict;
the most secure option would be to pay with credit card, since most providers include
comprehensive fraud protection, whereas the most private option would be to pay using
crypto currency or cash, since neither can be easily tied back to your identity.
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Secure Budgeting

- **[<img src='https://icon.horse/icon/www.firefly-iii.org' width='16' height='16' alt='icon' /> Firefly III](https://www.firefly-iii.org)** - A free and open source personal finance manager. Firefly III features a clean
and clear UI, is easy to set up and use, and is backed by a strong community.
Regular updates bring new features, improvements, and fixes. There's also a hass.io
addon, and compatibility with Home Assistant. Ensure your server is securely configured.
 	- [![GitHub: firefly-iii/firefly-iii](https://img.shields.io/github/stars/firefly-iii/firefly-iii?style=flat&logo=github&label=firefly-iii&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/firefly-iii/firefly-iii)
- **[<img src='https://www.gnucash.org/images/gnc-download.png' width='16' height='16' alt='icon' /> GnuCash](https://www.gnucash.org)** - A full-featured cross-platform accounting application suitable for personal
and small business finance. Stable and reliable, GnuCash offers a comprehensive
suite of financial management tools. Available for Windows, Mac, Linux, and
Android.
 	- [![GitHub: Gnucash/gnucash](https://img.shields.io/github/stars/Gnucash/gnucash?style=flat&logo=github&label=gnucash&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/Gnucash/gnucash)
- **[<img src='https://icon.horse/icon/plaintextaccounting.org' width='16' height='16' alt='icon' /> Plain Text Accounting](https://plaintextaccounting.org)** - Utilizes plain text files and scriptable, command-line-friendly software for
bookkeeping/accounting, offering full control over data. Popular tools include
Ledger, hledger, and Beancount among others, providing a flexible and vendor-independent
approach to accounting.
 	- [![GitHub: plaintextaccounting/plaintextaccounting](https://img.shields.io/github/stars/plaintextaccounting/plaintextaccounting?style=flat&logo=github&label=plaintextaccounting&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/plaintextaccounting/plaintextaccounting)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> Spreadsheets remain a popular choice for managing budgets and financial planning.
> [Collabora](https://nextcloud.com/collaboraonline) or
> [OnlyOffice](https://nextcloud.com/onlyoffice) (on [NextCloud](https://nextcloud.com)),
> [Libre Office](https://www.libreoffice.org) and [EtherCalc](https://ethercalc.net)
> are popular open source spread sheet applications. [Mintable](https://github.com/kevinschaich/mintable)
> allows you to auto-populate your spreadsheets from your financial data,
> using publicly accessible API - mitigating the requirement for a dedicated budgeting application.
> 
> Other notable open source budgeting applications include:
> [Smart Wallet](https://apps.apple.com/app/smart-wallet/id1378013954) (iOS),
> [My-Budget](https://rezach.github.io/my-budget) (Desktop),
> [MoneyManager EX](https://www.moneymanagerex.org),
> [Skrooge](https://skrooge.org),
> [kMyMoney](https://kmymoney.org) and
> [Budget Zen](https://budgetzen.net) (a simple E2E encrypted budget manager)
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Social

### Social Networks

Over the past decade, social networks have revolutionized the way we communicate
and bought the world closer together - but it came at the
[cost of our privacy](https://en.wikipedia.org/wiki/Privacy_concerns_with_social_networking_services).

Social networks are built on the principle of sharing - but you, the user
should be able to choose with whom you share what, and that is what the
following sites aim to do.

- **[<img src='https://icon.horse/icon/getaether.net' width='16' height='16' alt='icon' /> Aether](https://getaether.net)** - Offers self-governing communities with auditable moderation, akin to Reddit but
prioritizing privacy, democracy, and transparency. Aether is peer-to-peer and open
source, available for Windows, Mac, and Linux.
 	- [![GitHub: getaether/aether-community-firmware](https://img.shields.io/github/stars/getaether/aether-community-firmware?style=flat&logo=github&label=aether-community-firmware&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/getaether/aether-community-firmware)
- **[<img src='https://icon.horse/icon/www.discourse.org' width='16' height='16' alt='icon' /> Discourse](https://www.discourse.org)** - A fully open-source, self-hostable discussion platform usable as a mailing list,
discussion forum, or long-form chat room.
 	- [![GitHub: discourse/discourse](https://img.shields.io/github/stars/discourse/discourse?style=flat&logo=github&label=discourse&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/discourse/discourse)
- **[<img src='https://icon.horse/icon/mastodon.social' width='16' height='16' alt='icon' /> Mastodon](https://mastodon.social)** - An open-source, distributed social media platform functioning similarly to Twitter,
without algorithmic timeline manipulations. It operates across independent servers.
 	- [![GitHub: mastodon/mastodon](https://img.shields.io/github/stars/mastodon/mastodon?style=flat&logo=github&label=mastodon&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mastodon/mastodon)
- **[<img src='https://icon.horse/icon/www.minds.com' width='16' height='16' alt='icon' /> Minds](https://www.minds.com)** - A social media platform designed to foster open conversations and community
engagement. Rewards content creation.
 	- [![GitHub: minds/minds](https://img.shields.io/github/stars/minds/minds?style=flat&logo=github&label=minds&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/minds/minds)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [diaspora\*](https://diasporafoundation.org), [Pleroma](https://pleroma.social), [Friendica](https://friendi.ca) and [Hubzilla ](https://hubzilla.org) - distributed, decentralized social networks, built on open protocols
> - [Tildes](https://tildes.net), [Lemmy](https://dev.lemmy.ml) and [notabug.io](https://notabug.io) - bulletin boards and news aggregators (similar to Reddit)
> - [Pixelfed](https://pixelfed.org) - A free, ethical, federated photo sharing platform (FOSS alternative to Instagram)
> </details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> The content on many of these smaller sites tends to be more *niche*.
To continue using Twitter, there are a couple of
[tweaks](https://www.offensiveprivacy.com/blog/twitter-privacy),
that will improve security. For Reddit, use a privacy-respecting client -
such as [Reditr](http://reditr.com/).
Other main-stream social networking sites do not respect your privacy,
so should be avoided, but if you choose to keep using them see
[this guide](https://proprivacy.com/guides/social-media-privacy-guide) for tips on protecting your privacy
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Video Platforms

- **[<img src='https://icon.horse/icon/joinpeertube.org' width='16' height='16' alt='icon' /> PeerTube](https://joinpeertube.org)** - A federated video platform leveraging peer-to-peer technology to decrease server
load during video streaming. Supports self-hosting or joining existing instances,
enabling video viewing from any PeerTube server.
 - **[<img src='https://icon.horse/icon/d.tube' width='16' height='16' alt='icon' /> DTube](https://d.tube)** - A decentralized, ad-free video platform emphasizing minimal moderation. It rewards
users with cryptocurrency, leveraging blockchain technology.
 - **[<img src='https://www.bitchute.com/static/1.1.10/images/favicon-16x16.png' width='16' height='16' alt='icon' /> BitChute](https://www.bitchute.com)** - Established in 2017, BitChute is a video hosting service that offers a platform for
uploaders to evade the content restrictions found on other sites like YouTube.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> Without moderation, some of these platforms accommodate video creators
whose content may not be appropriate for all audiences


</details>

<details>
<summary>ℹ️ <b>Further Info</b></summary>

> #### YouTube Proxies
The content on many of the smaller video sites, often just doesn't compare to YouTube.
So another alternative, is to access YouTube through a proxy client, which reduces what Google can track.
- Good options are: [Invidious](https://invidious.io/) (web), [Piped](https://piped.kavin.rocks) (web), [FreeTube](https://freetubeapp.io/) (Windows, Mac OS, Linux), [NewPipe](https://newpipe.schabi.org/) (Android), [YouTube++](https://iosninja.io/ipa-library/download-youtube-plus-ipa-ios) (iOS)
- Or download videos with [youtube-dl](https://ytdl-org.github.io/youtube-dl/) (cli) or [youtube-dl-gui](https://github.com/MrS0m30n3/youtube-dl-gui) (gui). For just audio, there is [PodSync](https://podsync.net/)

#### Video Search Engines
[Petey Vid](https://www.peteyvid.com) is a non-biased video search engine.
Unlike normal search engines it indexes videos from a lot of sources,
including Twitter, Veoh, Instagram, Twitch, MetaCafe, Minds, BitChute,
Brighteon, D-Tube, PeerTube, and many others.
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Blogging Platforms

- **[<img src='https://icon.horse/icon/writefreely.org' width='16' height='16' alt='icon' /> Write Freely](https://writefreely.org)** - A minimalist, federated blogging platform offering a clean UI. It's free, open source,
and caters to writers seeking simplicity and federation capabilities. For hosted options,
visit Write.as.
 	- [![GitHub: writeas/writefreely](https://img.shields.io/github/stars/writeas/writefreely?style=flat&logo=github&label=writefreely&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/writeas/writefreely)
- **[<img src='https://icon.horse/icon/telegra.ph' width='16' height='16' alt='icon' /> Telegraph](https://telegra.ph)** - A quick, anonymous blogging platform by Telegram. It's designed for simplicity and speed,
allowing for straightforward content publishing without registration.
 - **[<img src='https://icon.horse/icon/mataroa.blog' width='16' height='16' alt='icon' /> Mataroa](https://mataroa.blog)** - A minimalist blogging platform focused on privacy and simplicity. It's open source and
eschews complex features for a straightforward writing and publishing experience.
 	- [![GitHub: mataroa-blog/mataroa](https://img.shields.io/github/stars/mataroa-blog/mataroa?style=flat&logo=github&label=mataroa&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/mataroa-blog/mataroa)
- **[<img src='https://icon.horse/icon/bearblog.dev' width='16' height='16' alt='icon' /> Bear Blog](https://bearblog.dev/)** - A no-nonsense, super-fast blogging platform prioritizing privacy. It strips back
unnecessary features to focus on straightforward blogging. The platform is open source.
 	- [![GitHub: HermanMartinus/bearblog](https://img.shields.io/github/stars/HermanMartinus/bearblog?style=flat&logo=github&label=bearblog&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/HermanMartinus/bearblog)
- **[<img src='https://icon.horse/icon/movim.eu' width='16' height='16' alt='icon' /> Movim](https://movim.eu/)** - A web frontend for XMPP, offering decentralized blogging and chatrooms. Movim is open source,
integrating social and communication tools in a unified platform.
 	- [![GitHub: movim/movim](https://img.shields.io/github/stars/movim/movim?style=flat&logo=github&label=movim&labelColor=%230d1117&color=%23302982&cacheSeconds=3600)](https://github.com/movim/movim)

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> If you use [Standard Notes](https://standardnotes.com/?s=chelvq36),
> then [Listed.to](https://listed.to) is a public blogging platform with
> strong privacy features.
> It lets you publish posts directly through the Standard Notes app or web interface.
> 
> Other minimalistic platforms include [Notepin.co](https://notepin.co) and [Pen.io](http://pen.io).
> 
> Want to write a simple text post and promote it yourself?
> Check out [telegra.ph](https://telegra.ph), [txt.fyi](https://txt.fyi) and [NotePin](https://notepin.co).
> For seriously anonymous platforms, aimed at activists, see [noblogs](https://noblogs.org/)
> and [autistici](https://www.autistici.org).
> It is also possible to host a normal [WordPress](https://wordpress.com) site,
> without it being linked to your real identity, although WP does not have
> the best reputation when it comes to privacy.
> 
> Of course you could also host your blog on your own server,
> using a standard open source blog platform, such as
> [Ghost](https://ghost.org) and configure it to disable all trackers, ads and analytics.
> </details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### News Readers

- **[<img src='https://icon.horse/icon/tt-rss.org' width='16' height='16' alt='icon' /> Tiny RSS](https://tt-rss.org)** - A web-based news feed reader and aggregator, supporting RSS/Atom feeds. It's free, open source,
and offers a customizable and self-hostable platform for managing your news feeds.
 - **[<img src='https://icon.horse/icon/www.rssowl.org' width='16' height='16' alt='icon' /> RSSOwl](http://www.rssowl.org)** - A powerful, desktop-based RSS reader offering extensive organization features. It facilitates
managing and curating news feeds from various sources.
 - **[<img src='https://icon.horse/icon/feedly.com' width='16' height='16' alt='icon' /> Feedly](https://feedly.com)** - Offers a premium news aggregation experience, presenting news from chosen sources in a clean,
modern interface. Beyond RSS, it integrates with various news outlets, ensuring a tailored
news feed without manipulated content. Parts of the service are open source.
 
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Proxy Sites

These are websites that enable you to access existing social media platforms,
without using their primary website - with the aim of improving privacy &
security and providing better user experience. The below options are open
source (so can be self-hosted, if you wish), and they do not display ads
or tracking (unless otherwise stated).

- **[<img src='https://icon.horse/icon/nitter.net' width='16' height='16' alt='icon' /> Nitter](https://nitter.net)** - A privacy-centric alternative to Twitter's front-end, focusing on preventing user tracking.
It's free, open source, lightweight, supports multiple themes, and offers customizable RSS feeds.
All client requests are proxied, enhancing privacy. No JavaScript required.
 - **[<img src='https://icon.horse/icon/invidious.io' width='16' height='16' alt='icon' /> Invidious](https://invidious.io)** - An open source, privacy-focused YouTube frontend. It minimizes Google tracking, supports audio-only mode,
integrates Reddit comments, and offers advanced playback options. Lightweight and can function without
JavaScript. Supports import/export of subscriptions and feed customization.
 - **[<img src='https://icon.horse/icon/libreddit.spike.codes' width='16' height='16' alt='icon' /> Libreddit](https://libreddit.spike.codes)** - A private, fast Reddit frontend written in Rust. Excludes ads, trackers, and bloat, making it much faster
than the official site. Can be self-hosted via Docker or other methods. Implements most Reddit features
for anonymous browsing.
 - **[<img src='https://icon.horse/icon/weboproxy.com' width='16' height='16' alt='icon' /> WebProxy](https://weboproxy.com)** - A free proxy service offering a Tor mode for evading censorship and accessing geo-restricted content.
Claims to encrypt traffic, but caution is advised for personal information. Managed by DevroLabs.
 
<details>
<summary>⚠️ <b>Word of Warning</b></summary>

> When proxies are involved - only use reputable services, and **never** enter any personal information


</details>

<details>
<summary>✳️ <b>Notable Mentions</b></summary>

> - [NewPipe](https://newpipe.schabi.org) - An open source, privacy-respecting YouTube client for Android.> - [FreeTube](https://freetubeapp.io) - An open source YouTube client for Windows, MacOS and Linux, providing
a more private experience, with a native-feel desktop app.
It is built upon the [Invidious](https://invidious.io/) API.
</details>

<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Media

### Gaming

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Media Servers

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Music Players

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Video Players

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Photo Viewers

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### E-Book Readers

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Podcast Players

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Torrent Downloaders

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### File Converters

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

## Creativity

### Image Editors

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Video Editors

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Audio Editors & Recorders

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Casting & Streaming

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Screenshot Tools

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### 3D Graphics

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

### Animation

<p  align="center"><b>⚠️ This section is still a work in progress ⚠️</b><br /><i>Check back soon, or help us complete it by submitting a pull request</i></p>
<p align="right"><sup><a href="#top">⬆️ [Back to Top]</a></sub></p>

---

<!-- awesome-privacy-end -->

---

## Final Notes

### Conclusion

Many corporations put profit before people, collecting data and exploiting privacy. They claim to be secure but without being open source it can't be verified, until there's been a breach and it's too late. Switching to privacy-respecting open source software will drastically help improving your security, privacy and anonymity online.

However, that's not all you need to do. It is also important to: use strong and unique passwords, 2-factor authentication,
adopt good networking practices and be mindful of data that are collected when browsing the web. You can see the full
**[personal security checklist](https://github.com/Lissy93/personal-security-checklist/blob/HEAD/CHECKLIST.md)** for more tips to stay safe. 


### Important Considerations

**Compartmentalise, Update and Be Ready**<br>
No piece of software is truly secure or private.  Further to this, software can only as secure as the system it is running on. Vulnerabilities are being discovered and patched all the time, so you much keep your system up-to-date. Breaches occur regularly, so compartmentalise your data to minimise damage. It's not just about choosing secure software, you must also follow good security practices.

**Attack Surface**<br>
It is a good idea to keep your trusted software base small, to reduce potential attack surface. At the same time trusting a single application for too many tasks or too much personal data could be a weakness in your system. So you will need to judge the situation according to your threat model, and carefully plan which software and applications you trust with each segment of your data.

**Convenience Vs Security**<br>
There is often a trade-off between convenience and security. Construct a threat model, and choose a balance that is right for you. In a similar way in some situations there is privacy and security conflict (e.g. Find My Phone is great for security, but terrible for privacy, and anonymous payments may be good for privacy but less secure than insured fiat currency). Again it is about assessing your situation, understanding the risks and making an informed decision.

**Hosted Vs Self-Hosted Considerations**<br>
When using a hosted or managed application that is open-source software - there is often no easy way to tell if the version running is the same as that of the published source code (even published signatures can be faked). There is always the possibility that additional backdoors may have been knowingly or unknowingly implemented in the running instance. One way round this is to self-host software yourself. When self-hosting you will then know for sure which code is running, however you will also be responsible for the managing security of the server, and so may not be recommended for beginners.

**Open Source Software Considerations**<br>
Open source software has long had a reputation of being more secure than its closed source counterparts. Since bugs are raised transparently, fixed quickly, the code can be checked by experts in the community and there is usually little or no data collection or analytics. 
That being said, there is no piece of software that it totally bug free, and hence never truly secure or private. Being open source, is in no way a guarantee that something is safe. There is no shortage of poorly-written, obsolete or sometimes harmful open source projects on the internet. Some open source apps, or a dependency bundled within it are just plain malicious (such as, that time [Colourama was found in the PyPI Repository](https://hackaday.com/2018/10/31/when-good-software-goes-bad-malware-in-open-source/))

**Proprietary Software Considerations**<br>
When using a hosted or proprietary solution - always check the privacy policy, research the reputation of the organisation, and be weary about which data you trust them with. It may be best to choose open source software for security-critical situations, where possible.

**Maintenance**<br>
When selecting a new application, ensure it is still being regularly maintained, as this will allow for recently discovered security issues to be addressed. Software in an alpha or beta phase, may be buggy and lacking in features, but  more importantly - it could have critical vulnerabilities open to exploit. Similarly, applications that are no longer being actively maintained may pose a security risk, due to lack of patching. When using a forked application, or software that is based on an upstream code base, be aware that it may receive security-critical patches and updates at a slightly later date than the original application. 

**This List: Disclaimer**<br>
This list contains packages that range from entry-level to advanced, a lot of the software here will not be appropriate for all audiences. It is in no way a definitive list of secure applications, and aims only to be a guide, a collection of software and services that myself and other contributors have used, and would recommend. There will always be new vulnerabilities discovered or introduced, bugs and security-critical glitches, malicious actors and poorly configured systems. It is up to you to do your research, draw up a threat model, and decide where and how your data are managed.

If you find something on this list that should no longer be deemed secure or private/ or should have a warning note attached, please raise an issue. In the same way if you know of something that is missing, or would like to make an edit, then pull requests are welcome, and are much appreciated!

### Further Reading

**More Awesome Software Lists**<br>

This list was focused on privacy-respecting software. Below are other awesome lists, maintained by the community of open source software, categorised by operating system.

- Windows: [awesome-windows-apps](https://github.com/Awesome-Windows/Awesome) by 'many'
- MacOS: [awesome-macOS-apps](https://github.com/iCHAIT/awesome-macOS) by @iCHAIT
- Linux: [awesome-linux-software](https://github.com/luong-komorebi/Awesome-Linux-Software) by @luong-komorebi
- iOS: [open-source-ios-apps](https://github.com/dkhamsing/open-source-ios-apps) by @dkhamsing
- Android: [open-source-android-apps](https://github.com/pcqpcq/open-source-android-apps) by @pcqpcq
- Server: [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) by 'many'
- [**More GitHub Awesome Lists →**](https://github.com/Lissy93/personal-security-checklist/blob/master/articles/4_Privacy_And_Security_Links.md#more-awesome-github-lists)

**Security List**<br>
- [Personal Security Checklist](https://github.com/lissy93/personal-security-checklist) - A curated list of security and privacy advice, tools, and resources.

**News & Updates**<br>
A custom Reddit feed covering news and updates for all the apps covered here can be found [here](https://www.reddit.com/user/lissy93/m/software_projects/)

---

## The Website
The easist way to browse Awesome Privacy, is via our website, at **[awesome-privacy.xyz](https://awesome-privacy.xyz)**

[![screenshots](https://raw.githubusercontent.com/Lissy93/awesome-privacy/main/.github/screenshots/grid.png)](https://awesome-privacy.xyz)

### About Website
The source for the website is in the [`web/`](https://github.com/Lissy93/awesome-privacy/tree/main/web) directory.

This is a statically generated site, built with Astro, Svelte, TypeScript an SCSS.<br>
At build-time, it reads the data from [`awesome-privacy.yml`](https://github.com/Lissy93/awesome-privacy/blob/main/awesome-privacy.yml) and generates the pages.

### Running the Website Locally
You'll need [Node.js](https://nodejs.org/en) (20.11.1 or later) and [Git](https://git-scm.com/) installed.<br>
Then run the following commands to fetch the code, install dependencies and start the dev server.

```shell
git clone git@github.com:Lissy93/awesome-privacy.git
cd awesome-privacy/web
cp .env.sample .env
yarn install
yarn dev
# Then open 127.0.0.1:4321 in your browser
```

### Deploying the Website
Follow the steps above, then run `yarn build` to generate the static files.<br>
You can then upload the `./dist` directory to any web server, static host or CDN.<br>
Alternatively, you can fork the repo and import it into either Vercel or Netlify.

---

## Contributing
We welcome suggestions, additions, edits and removals to the list.<br>
It's thanks to contributors like you that this project is possible 💜 

All data is stored in [`awesome-privacy.yml`](https://github.com/Lissy93/awesome-privacy/blob/main/awesome-privacy.yml).
If you're adding, editing or removing a listing - **this is the only file you need to edit**.

Please familiarise yourself with the [Contributing Guidelines](https://github.com/Lissy93/awesome-privacy/blob/main/.github/CONTRIBUTING.md) before submiting your pull request, as we have some guidelines that **must be followed** to ensure your PR can be accepted.

If you're new to open source, you can find some resources to get you started at [git-in.to](https://git-in.to),
but feel free to reach out if you need any help 😊 

---

## Acknowledgements

### Sponsors
Huge thanks to the following sponsors, for their ongoing support 💖

<!-- readme: sponsors -start -->
<table>
</table>
<!-- readme: sponsors -end -->


### Contributors
This project exists thanks to all the people who've helped build and maintain it  🌟
<!-- readme: contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/liss-bot">
            <img src="https://avatars.githubusercontent.com/u/87835202?v=4" width="80;" alt="liss-bot"/>
            <br />
            <sub><b>Alicia Bot</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Lissy93">
            <img src="https://avatars.githubusercontent.com/u/1862727?v=4" width="80;" alt="Lissy93"/>
            <br />
            <sub><b>Alicia Sykes</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Ki-er">
            <img src="https://avatars.githubusercontent.com/u/32241933?v=4" width="80;" alt="Ki-er"/>
            <br />
            <sub><b>Kieran</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/lilithium-hydride">
            <img src="https://avatars.githubusercontent.com/u/78992082?v=4" width="80;" alt="lilithium-hydride"/>
            <br />
            <sub><b>Lilith</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/renovate-bot">
            <img src="https://avatars.githubusercontent.com/u/25180681?v=4" width="80;" alt="renovate-bot"/>
            <br />
            <sub><b>Mend Renovate</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/ltguillaume">
            <img src="https://avatars.githubusercontent.com/u/4777345?v=4" width="80;" alt="ltguillaume"/>
            <br />
            <sub><b>Guillaume</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/A-childs-encyclopedia">
            <img src="https://avatars.githubusercontent.com/u/84061672?v=4" width="80;" alt="A-childs-encyclopedia"/>
            <br />
            <sub><b>A-childs-encyclopedia</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/amilich">
            <img src="https://avatars.githubusercontent.com/u/1927690?v=4" width="80;" alt="amilich"/>
            <br />
            <sub><b>Andrew Milich</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/kerbless">
            <img src="https://avatars.githubusercontent.com/u/32358946?v=4" width="80;" alt="kerbless"/>
            <br />
            <sub><b>Kerbless</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/ksharizard">
            <img src="https://avatars.githubusercontent.com/u/78494833?v=4" width="80;" alt="ksharizard"/>
            <br />
            <sub><b>Kshamendra</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/titanism">
            <img src="https://avatars.githubusercontent.com/u/101466223?v=4" width="80;" alt="titanism"/>
            <br />
            <sub><b>Titanism</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/slade991">
            <img src="https://avatars.githubusercontent.com/u/10143703?v=4" width="80;" alt="slade991"/>
            <br />
            <sub><b>Slade991</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/samsapti">
            <img src="https://avatars.githubusercontent.com/u/26819407?v=4" width="80;" alt="samsapti"/>
            <br />
            <sub><b>Sam A.</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/gabrielvicenteYT">
            <img src="https://avatars.githubusercontent.com/u/68158102?v=4" width="80;" alt="gabrielvicenteYT"/>
            <br />
            <sub><b>Coccocoa's Helper</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/AlexOgden">
            <img src="https://avatars.githubusercontent.com/u/1379601?v=4" width="80;" alt="AlexOgden"/>
            <br />
            <sub><b>Alex Ogden</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/spignelon">
            <img src="https://avatars.githubusercontent.com/u/92091338?v=4" width="80;" alt="spignelon"/>
            <br />
            <sub><b>Ujjawal Saini</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/WardPearce">
            <img src="https://avatars.githubusercontent.com/u/27844174?v=4" width="80;" alt="WardPearce"/>
            <br />
            <sub><b>Ward</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Wesley-Ryan">
            <img src="https://avatars.githubusercontent.com/u/69822796?v=4" width="80;" alt="Wesley-Ryan"/>
            <br />
            <sub><b>Wesley-Ryan</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/thezacharytaylor">
            <img src="https://avatars.githubusercontent.com/u/21206039?v=4" width="80;" alt="thezacharytaylor"/>
            <br />
            <sub><b>Zachary Taylor</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/ZhymabekRoman">
            <img src="https://avatars.githubusercontent.com/u/61125068?v=4" width="80;" alt="ZhymabekRoman"/>
            <br />
            <sub><b>Zhymabek Roman</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/baddate">
            <img src="https://avatars.githubusercontent.com/u/37013819?v=4" width="80;" alt="baddate"/>
            <br />
            <sub><b>Sanmonji</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/colenh">
            <img src="https://avatars.githubusercontent.com/u/40342475?v=4" width="80;" alt="colenh"/>
            <br />
            <sub><b>Cole</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/jxhn">
            <img src="https://avatars.githubusercontent.com/u/1396009?v=4" width="80;" alt="jxhn"/>
            <br />
            <sub><b>Jxhn</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/kolaente">
            <img src="https://avatars.githubusercontent.com/u/13721712?v=4" width="80;" alt="kolaente"/>
            <br />
            <sub><b>Kolaente</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/magical-heyrovsky">
            <img src="https://avatars.githubusercontent.com/u/101060148?v=4" width="80;" alt="magical-heyrovsky"/>
            <br />
            <sub><b>Magical-heyrovsky</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/mrpavan">
            <img src="https://avatars.githubusercontent.com/u/20220426?v=4" width="80;" alt="mrpavan"/>
            <br />
            <sub><b>Pavan</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/pnodet">
            <img src="https://avatars.githubusercontent.com/u/5941125?v=4" width="80;" alt="pnodet"/>
            <br />
            <sub><b>Paul Nodet</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/rollsicecream">
            <img src="https://avatars.githubusercontent.com/u/153316540?v=4" width="80;" alt="rollsicecream"/>
            <br />
            <sub><b>Rollsicecream</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/tschlotfeldt">
            <img src="https://avatars.githubusercontent.com/u/149240?v=4" width="80;" alt="tschlotfeldt"/>
            <br />
            <sub><b>Tim Schlotfeldt</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/edent">
            <img src="https://avatars.githubusercontent.com/u/837136?v=4" width="80;" alt="edent"/>
            <br />
            <sub><b>Terence Eden</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: contributors -end -->

---

## License

> _**[Lissy93/Awesome-Privacy/web](https://github.com/Lissy93/awesome-privacy/tree/main/web)** is licensed under [MIT](https://gist.github.com/Lissy93/143d2ee01ccc5c052a17)_<br>
> _**[awesome-privacy.yml](https://github.com/Lissy93/awesome-privacy/blob/main/awesome-privacy.yml)** is licensed under [CC0-1.0 license](https://github.com/Lissy93/awesome-privacy/blob/HEAD/LICENSE)_<br>
> _Copyright © Alicia Sykes <[aliciasykes.com](https://aliciasykes.com)> 2024._<br>
> <sup align="right">For information, see <a href="https://tldrlegal.com/license/mit-license">TLDR Legal > MIT</a></sup>

<details>
<summary>Expand License</summary>

```
The MIT License (MIT)
Copyright (c) Alicia Sykes <alicia@omg.com> 

Permission is hereby granted, free of charge, to any person obtaining a copy 
of this software and associated documentation files (the "Software"), to deal 
in the Software without restriction, including without limitation the rights 
to use, copy, modify, merge, publish, distribute, sub-license, and/or sell 
copies of the Software, and to permit persons to whom the Software is furnished 
to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included install 
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANT ABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

</details>

<!-- License + Copyright -->
<p  align="center">
  <i>© <a href="https://aliciasykes.com">Alicia Sykes</a> 2024</i><br>
  <i>Licensed under <a href="https://gist.github.com/Lissy93/143d2ee01ccc5c052a17">MIT</a> &
  <a href="https://github.com/Lissy93/awesome-privacy/blob/HEAD/LICENSE">CC0-1.0</a></i><br>
  <a href="https://github.com/lissy93"><img src="https://i.ibb.co/4KtpYxb/octocat-clean-mini.png" /></a>
  <br><sup>Thanks for visiting :)</sup>
</p>

<!-- Dinosaurs are Awesome -->
<!-- 
                        . - ~ ~ ~ - .
      ..     _      .-~               ~-.
     //|     \ `..~                      `.
    || |      }  }              /       \  \
(\   \\ \~^..'                 |         }  \
 \`.-~  o      /       }       |        /    \
 (__          |       /        |       /      `.
  `- - ~ ~ -._|      /_ - ~ ~ ^|      /- _      `.
              |     /          |     /     ~-.     ~- _
              |_____|          |_____|         ~ - . _ _~_-_
-->


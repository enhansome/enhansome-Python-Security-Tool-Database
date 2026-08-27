# Awesome Python Exploit & Tool Database with stars

***

![Last Commit](https://img.shields.io/github/last-commit/MythicStack/Python-Security-Tool-Database)

***

## Synopsis

I didn't really find a good Python toolkit online and I just want to make something people will use so if you have input, talk to me on BlueSky! <https://bsky.app/profile/mythicstack.com>

If you think a project should be included here I really want to know, but keep in mind that this isn't supposed to be a dictionary. I want to keep the best, covering as many bases as possible while minimizing overlap.

***

### Table of Contents

* [Not Python](#not-python)
* [Adversary Simulation](#adversary-simulation)
* [Digital Forensics and Incident Response](#digital-forensics-and-incident-response-dfir)
* [Information  Gathering](#information-gathering)
* [Networking](#networking)
* [Penetration Testing](#penetration-testing)
* [Social Engineering](#social-engineering)
* [Vulnerability Scanning](#vulnerability-scanning)
* [Wireless Security](#wireless-security)

***

##### Not Python

* [Metasploit](https://github.com/rapid7/metasploit-framework) ⭐ 38,892 | 🐛 591 | 🌐 Ruby | 📅 2026-08-27 - Alright so this thing isn't even close to being mostly Python, but cmon it's Metasploit. This has to be in here because I love this thing so much. This makes my life easier every single day.

##### Adversary Simulation

* [Caldera](https://github.com/mitre/caldera) ⭐ 7,213 | 🐛 69 | 🌐 Python | 📅 2026-08-27 - Mitre's adversary emulation tool. It's not entirely python, but it's mostly python and so sick that it has to be included here.
* [Infection Monkey](https://github.com/guardicore/monkey) ⭐ 7,077 | 🐛 239 | 🌐 Python | 📅 2025-05-01 - Attack simulation tool with self-propagation functionality and a web portal that provides mini security write-ups after attack is complete. Several exploits to chose from + it's a very clean tool.
* [FakeNet-NG](https://github.com/mandiant/flare-fakenet-ng) ⭐ 2,184 | 🐛 81 | 🌐 Python | 📅 2026-05-28 - Simulate legitimate network services while redirecting specified traffic. This is also an older project that is no longer maintained, but I could not find something that provided the same functionality and this still works.
* [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) ⭐ 1,039 | 🐛 4 | 🌐 Python | 📅 2020-05-27 - Old, on Python2, and no longer maintained. That being said, it's got a lot of reference material if you're interested. I messed around with it for an hour or two and all the modules I played with worked without too much finagling (No clue about the OSX stuff though, let me know).
* [Splunk Attack Data](https://github.com/splunk/attack_data) ⭐ 808 | 🐛 4 | 🌐 Python | 📅 2026-08-26 - Allows you to replay attacks generated from logs, lots of datasets to chose from have already been included in the repo.

##### Digital Forensics and Incident Response (DFIR)

* [Loki (IOC Scanner)](https://github.com/Neo23x0/Loki) ⭐ 3,783 | 🐛 18 | 🌐 Python | 📅 2026-01-12 - Loki is an absolutely sick IOC scanner. Supports: hashes, yara, filenames, and C2 IOCs.
* [Malware CAPE](https://github.com/kevoreilly/CAPEv2) ⭐ 3,453 | 🐛 58 | 🌐 Python | 📅 2026-08-27 - This is the Malware Configuration and Payload Extractor, hence the name CAPE. It's phenomenal and there's an [online instance](https://capesandbox.com/).
* [OSSEM](https://github.com/OTRF/OSSEM) ⭐ 1,300 | 🐛 17 | 🌐 Python | 📅 2023-02-27 - This is the Open Source Security Events Metadata. Weird name, but great idea. Event log analysis + documentation + standardized framework = win in my book. I'm not a DFIR expert, so can't say for sure how useful this is in a corportate setting, but I appreciate what's going on here.
* [Cuckoo Modified(+Sandbox)](https://github.com/spender-sandbox/cuckoo-modified) ⭐ 406 | 🐛 173 | 🌐 Python | 📅 2017-11-21 - This is deprecated, but the one I'm familiar with. Never used the new one, but it's [here](http://www.cuckoosandbox.org/). This is a really excellent automated malware analyzer, highly recommend.
* [Cold Disk, Quick Response](https://github.com/orlikoski/CDQR) ⭐ 345 | 🐛 5 | 🌐 Python | 📅 2022-06-25 - CDQR is a disk parser and artifact collector. Their readme explains all. This is one of the few on my list that I've never personally used. I also couldn't easily set up a situation in order to use it effectively to test it, but it's been in a bunch of DFIR kits I've been around so I feel comfortable including it here.
* [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) ⭐ 253 | 🐛 13 | 🌐 Python | 📅 2020-09-22 - First, how great is that name?! Second, this is the best Python based live memory acquisition tool. Done and dusted. It's a bit old, but still kicking.
* [Image Mounter](https://github.com/ralphje/imagemounter) ⭐ 127 | 🐛 6 | 🌐 Python | 📅 2023-02-09 - CLI mounting tool for virtual and non-virtual images.

##### Information Gathering

* [sherlock](https://github.com/sherlock-project/sherlock) ⭐ 90,388 | 🐛 333 | 🌐 Python | 📅 2026-08-27 - Best broad social media hunter I've used by far. So simple a caveman could do it.
* [SpiderFoot](https://github.com/smicallef/spiderfoot) ⭐ 21,455 | 🐛 313 | 🌐 Python | 📅 2026-04-13 - Easily the coolest OSINT tool on the list, it would be first if I wasn't trying to keep this thing alphabetical. Its perks are too numerous to outline here, go to their page.
* [theHarvester](https://github.com/laramies/theHarvester) ⭐ 17,207 | 🐛 7 | 🌐 Python | 📅 2026-08-27 - Jack of Most Trades OSINT tool maintained by a bunch of people. Often Updated and might as well be a household name. It's well-rounded and efficient. What more could you ask for?
* [holehe](https://github.com/megadose/holehe) ⭐ 14,308 | 🐛 115 | 🌐 Python | 📅 2024-09-10 - Simple mail checker for popular websites. Clean and to the point, updated by [megadose](https://twitter.com/palenath) as needed. They also have a lot of other interesting projects.
* [Osintgram](https://github.com/Datalux/Osintgram) ⭐ 14,150 | 🐛 883 | 🌐 Python | 📅 2025-08-25 - Instagram is a wealth of data for those that look, it's maintained by a lot of folks, but Instagram changes may break functionality. It's a well organized project and lots of forks to take a look at.
* [BlackBird](https://github.com/p1ngul1n0/blackbird) ⭐ 7,867 | 🐛 20 | 🌐 Python | 📅 2025-07-13 - Another OSINT tool! I seem to have a favorite category at this point.
* [Recon-ng](https://github.com/lanmaster53/recon-ng) ⭐ 5,873 | 🐛 38 | 🌐 Python | 📅 2024-11-01 - The OSINT equivalent to the Metasploit Framework. Could be updated more often, but it's well respected and there's decades of content on the internet to help you get familiar with it.
* [IntelOwl](https://github.com/intelowlproject/IntelOwl) ⭐ 4,684 | 🐛 69 | 🌐 Python | 📅 2026-08-26 - It's a cool malware/malspam threat intel tool. It's mostly Python, but it's pretty JS heavy. I've used it and my thoughts on it are: "Clean/Functional/Well Documented, but it smells like a corporate project."
* [Moriarty Project](https://github.com/AzizKpln/Moriarty-Project) ⭐ 2,074 | 🐛 28 | 🌐 Python | 📅 2024-07-13 - Checks for provided phone number on popular websites, performs searches, and provides ownership information.
* [Anubis](https://github.com/jonluca/Anubis) ⭐ 1,375 | 🐛 0 | 🌐 Python | 📅 2026-08-03 - Subdomain enumerator actively maintained by [jonluca](https://github.com/jonluca). It's a good tool and it works well. Has the added benefit of having a nice README with clear examples. Every issue (at the time of writing) has been resolved. The dude has some pretty cool projects on his blog too.
* [Metagoofil](https://github.com/laramies/metagoofil) ⭐ 1,313 | 🐛 19 | 🌐 Python | 📅 2024-03-21 - This is an oldie, but a goodie from the days of Python 2. This tool helps obtain files and metadata from target websites using Google.
* [DaProfiler](https://github.com/daprofiler/DaProfiler) ⚠️ Archived - This a person profiler and covers bases that others on this list do not. It's fairly in-depth, updated regularly, and has a clean UI. Easy to use and works well, some false positives.
* [whoisrecon](https://github.com/MythicStack/whoisrecon) - Shameless self-plug, this is a pretty useful tool I cooked up that lets you use CLI to query a WHOIS archive for historical data and find related domains from wildcard support searches of emails, organizations, and more!

##### Networking

* [NetworkX](https://github.com/networkx/networkx) ⭐ 17,228 | 🐛 325 | 🌐 Python | 📅 2026-08-26 - Incredibly thourough network mapping and analysis tool for small and large networks.
* [Impacket](https://github.com/fortra/impacket) ⭐ 16,040 | 🐛 316 | 🌐 Python | 📅 2026-08-24 - Impacket is a flexible toolkit for crafting, manipulating, and analyzing network protocols. Never leave home without it.
* [Scapy](https://github.com/secdev/scapy) ⭐ 12,501 | 🐛 137 | 🌐 Python | 📅 2026-08-27 - Python packet manipulation tool for a really solid number of protocols.

##### Password Cracking

* [Patator](https://github.com/lanjelot/patator) ⭐ 3,923 | 🐛 36 | 🌐 Python | 📅 2025-05-20 - All in one brute forcer. This is built as an alternative to Hydra (near and dear to me, but definitely not Python anymore, mostly C) and some other tooling built into Kali by default. It's a sick multi-threaded application that's super flexible and inclusive.

##### Penetration Testing

* [SQL Map](https://github.com/sqlmapproject/sqlmap) ⭐ 38,277 | 🐛 34 | 🌐 Python | 📅 2026-08-26 - This thing is so cool! Really awesome set of contributors on this project, basically it's an automated detector/exploiter for SQL injection vulnerabilities. This thing kicks ass once you get the hang of it.
* [CrackMapExec](https://www.kali.org/tools/crackmapexec/) - CrackMapExec (CME) is a post-exploitation tool to automate the assessment of large Active Directory networks. I think there's some drama here between [byt3bl33d3r](https://github.com/byt3bl33d3r/CrackMapExec) ⚠️ Archived and Kali, but I don't know so I'm linking primarily to the Kali one since it's maintained and byt3's is archived.
* [EvilTwinFramework](https://github.com/Esser50K/EvilTwinFramework) ⭐ 359 | 🐛 7 | 🌐 Python | 📅 2024-08-01 - Python tool to help penetration testers perform evil twin attacks and some other wifi related exploits.

##### Social Engineering

* [Social Engineering Toolkit](https://github.com/trustedsec/social-engineer-toolkit) ⭐ 15,241 | 🐛 12 | 🌐 Python | 📅 2026-06-04 - Built by one of my favorite people [@HackingDave](www.twitter.com/HackingDave), this Python toolkit (so it's built with more than just Python, sue me) is a modular piece of art with 15+ built in tools that work well out of the box. Plus for new folks to the tool it also has a extremely easy to digest User Manual.
* [King Phisher](https://github.com/rsmusllp/king-phisher) ⭐ 2,583 | 🐛 2 | 🌐 Python | 📅 2026-08-04 - May look reduntant since the SET has a set of modules for phishing, but worry not this is definitely meant to be here. SET has a broad set of tooling in it, but King Phisher focuses on one thing and it does it really well. SMS alerts, MFA bypass, detailed email building, and a lot more are cooked into this tool.

##### Vulnerability Scanning

* [Bandit](https://github.com/PyCQA/bandit) ⭐ 8,242 | 🐛 260 | 🌐 Python | 📅 2026-08-24 - Slight change up to the rest of the tools in this list, but Bandit is still pretty useful. It's a static code analysis tool for Python scripts. Can be helpful for finding vulnerabilities in home brew applications and it's just a nice tool to have around if you're going to be building anything on your own with Python so you're not making any egregious slip ups.
* [Faraday](https://github.com/infobyte/faraday) ⭐ 6,696 | 🐛 26 | 🌐 Python | 📅 2026-08-20 - Faraday is clean and I love using it, I've messed with it in my home lab a lot. Bottom line is, it's fantastic. It has a clean & intuitive web UI, tracks vulnerability history, aids in remediation efforts, and it's updated as often as you'd expect. All the damn time.
* [Raccoon](https://github.com/evyatarmeged/Raccoon) ⭐ 4,001 | 🐛 14 | 🌐 Python | 📅 2026-04-21 - Raccoon is pretty sweet, very helpful, and a must have in your toolkit. It's not super well maintained, but it's open source and works perfectly out of the box for external attack surface scanning and information gathering.

##### Wireless Security

* [BetterCAP](https://github.com/bettercap/bettercap) ⭐ 19,866 | 🐛 44 | 🌐 Go | 📅 2026-08-13 - BetterCAP is a powerful, flexible, and portable tool designed for performing various types of MITM attacks against networks along with general network recon.
* [Wifite2](https://github.com/derv82/wifite2) ⭐ 8,088 | 🐛 348 | 🌐 Python | 📅 2026-08-05 - Whatever description isn't going to do the wifite rewrite any justice. WEP, WPS, and WPA/2 attacks galore. Must have if you're doing anything with wireless access points. I don't use any other Python tooling for wireless stuff, that's probably because I don't do much with wireless stuff in the first place so let me know what I missed!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._

# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210714 | BruteShark - 用于分析网络流量的工具，支持从中提取密码、认证 Hash、DNS 记录等信息 | https://github.com/odedshimon/BruteShark| 
| 20210714 | Revil 勒索软件攻击 Kaseya VSA Server RCE 漏洞的细节分析 | https://blog.truesec.com/2021/07/06/kaseya-vsa-zero-day-exploit/| 
| 20210714 | 2194 - Windows: CreateProcessWithLogon Write Restricted Service EoP - project-zero | https://bugs.chromium.org/p/project-zero/issues/detail?id=2194| 
| 20210714 | Part 2: Dive into Zoom Applications | https://rakesh-thodupunoori.medium.com/part-2-dive-into-zoom-applications-1b01091345c1| 
| 20210714 | 研究员 Axel Souchet 开源了一个基于快照的用于 Fuzz Windows 用户态程序和内核的 Fuzzer，支持代码覆盖率收集和分布式部署 | https://github.com/0vercl0k/wtf| 
| 20210714 | 微软今天发布 7 月份漏洞补丁，修复 116 个漏洞，其中 3 个已被野外利用 | https://threatpost.com/microsoft-crushes-116-bugs/167764/| 
| 20210714 | DLL Side-Loading Technique Used in the Recent Kaseya Ransomware Attack | https://www.fortinet.com/blog/threat-research/dll-side-loading-technique-used-in-recent-kaseya-ransomware-attack?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+fortinet%2Fblog%2Fthreat-research+%28Fortinet+Threat+Research+Blog%29| 
| 20210714 | Quarkslab 对 WinDefender Network Inspection 驱动实现机制的研究 | https://blog.quarkslab.com/guided-tour-inside-windefenders-network-inspection-driver.html| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210714T12:29:59Z | CVE-2021-50126 | Null | https://github.com/hacker-ali-17/CVE-2021-50126 | 未查询到CVE信息| 
| 20210714T10:44:00Z | cve-2021-34558 | Null | https://github.com/alexzorin/cve-2021-34558 | 未查询到CVE信息| 
| 20210714T06:42:35Z | CVE-2020-0796 | Null | https://github.com/1stPeak/CVE-2020-0796-Scanner | A remote code execution vulnerability exists in the way that the Microsoft Server Message Block 3.1.1 (SMBv3) protocol handles certain requests, aka %Windows SMBv3 Client/Server Remote Code Execution Vulnerability%.| 
| 20210714T05:29:08Z | CVE-2020-15368 | How to exploit a vulnerable windows driver. Exploit for AsrDrv104.sys | https://github.com/stong/CVE-2020-15368 | AsrDrv103.sys in the ASRock RGB Driver does not properly restrict access from user space, as demonstrated by triggering a triple fault via a request to zero CR3.| 
| 20210714T04:43:00Z | CVE-2021-10086 | Null | https://github.com/Mochican/CVE-2021-10086 | 未查询到CVE信息| 
| 20210714T04:38:47Z | cve-2021-1675 | Null | https://github.com/k8gege/cve-2021-1675 | Windows Print Spooler Elevation of Privilege Vulnerability| 
| 20210714T02:26:53Z | CVE-2020-1938 | Scanner for CVE-2020-1938 | https://github.com/yukiNeko114514/CVE-2020-1938 | When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T10:16:20Z | Null | https://github.com/JaimePSantos/ResearchKlee | 0 | 0| 
| 20210714T08:40:08Z | RVT is a collection of tools/libraries to support both static and dynamic verification of Rust programs. | https://github.com/project-oak/rust-verification-tools | 161 | 15| 
| 20210714T06:35:21Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 710 | 15| 
| 20210714T06:19:45Z | Symbiotic is a tool for finding bugs in computer programs based on instrumentation, program slicing and KLEE | https://github.com/staticafi/symbiotic | 216 | 35| 
| 20210714T06:10:09Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1730 | 498| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T02:13:53Z | GUI Configuration tool for WIZnet serial to ethernet devices. | https://github.com/Wiznet/WIZnet-S2E-Tool-GUI | 13 | 8| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T12:15:22Z | exploit-exercices (old school bugs) | https://github.com/ozswar94/Protostar | 0 | 0| 
| 20210714T12:05:53Z | C2X - C2/Post-Exploitation For Red Teaming and Ethical Hacking | https://github.com/nxenon/c2x | 0 | 0| 
| 20210714T12:03:04Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 26 | 12| 
| 20210714T11:55:48Z |  Using Lua C Parser ( Runs Script based on Lua C or Ancient Execution Method ) on Roblox in these modern day 2021 | https://github.com/Panda-Respiratory/Lua-C-Exploit-2021-Updated- | 0 | 0| 
| 20210714T11:27:22Z | CAUTION - Malicious files 💀 | https://github.com/Am0rphous/Malware | 18 | 7| 
| 20210714T09:34:01Z | A performant and a reliable server sided anti exploit capable of handling many common exploits smoothly with rare false positives and with minimal performance overhead. | https://github.com/SilentsReplacement/BoboFighter | 5 | 2| 
| 20210714T09:14:03Z | GoodSecurity was tasked with performing an internal penetration test on GoodCorps CEO, Hans Gruber. An internal penetration test is a dedicated attack against internally connected systems.  | https://github.com/Samwel8/Pentesting_Icecast_Exploit | 0 | 0| 
| 20210714T08:56:32Z | An attack/exploit Detector that utilizes Polymorphism and Diversity | https://github.com/polyverse/zerotect | 22 | 2| 
| 20210714T08:43:50Z | Modular C2 framework aiming to ease post exploitation for red teamers.  | https://github.com/CMatri/MeetC2 | 55 | 3| 
| 20210714T08:41:04Z | The legendary VXHeaven malware collection. | https://github.com/BaRRaKudaRain/RedZone | 18 | 6| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T11:44:57Z | Poweshell backdoor metasploit  | https://github.com/crypt0n-root/powershell-backdoor | 1 | 0| 
| 20210714T07:05:08Z | 🤖An Evil and Smart Bot for Enslaving Windows Written in Rust and Python | https://github.com/wildonion/katyusha | 3 | 1| 
| 20210714T04:39:11Z | Null | https://github.com/iK4oS/PremiumBackdoor.exe | 0 | 1| 
| 20210714T04:28:36Z | Mock server backdoor for playing around with another python tool I made.  | https://github.com/CadenFore/ServerBackdoor | 0 | 0| 
| 20210714T04:28:16Z | this program interacts with the server backdoor program I made and returns info on the given system/directory content when given commands. This was made as a fun project to practice using python for a pentester course through INE.  | https://github.com/CadenFore/backdoorClient | 0 | 0| 
| 20210714T04:04:02Z | Generate Virus/Backdoor/Worm you name it! | https://github.com/FonderElite/Warrior | 1 | 0| 
| 20210714T02:58:14Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 259 | 49| 
| 20210714T02:33:11Z | Null | https://github.com/backdoor322/backdoor322.github.io | 0 | 0| 
| 20210714T00:41:01Z | EcchiExploit Shell v1.0 | https://github.com/dmzhari/ecchi-shell | 0 | 1| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210714T09:49:42Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 147 | 33| 
| 20210714T06:10:09Z | KLEE Symbolic Execution Engine | https://github.com/klee/klee | 1730 | 498| 
| 20210714T05:19:16Z | SymCC: efficient compiler-based symbolic execution | https://github.com/eurecom-s3/symcc | 439 | 67| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 



# 日更新程序

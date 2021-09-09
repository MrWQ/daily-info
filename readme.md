# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210909 | Facebook 邮件泄露及账号接管漏洞分析 | https://rikeshbaniyaaa.medium.com/facebook-email-disclosure-and-account-takeover-ecdb44ee12e9| 
| 20210909 | New CPU side-channel attack takes aim at Chrome’s Site Isolation feature | https://therecord.media/new-cpu-side-channel-attack-takes-aim-at-chromes-site-isolation-feature/| 
| 20210909 | GitHub 提供的拼写检查 workflow 被发现存在漏洞，可以泄露 GITHUB_TOKEN API Key | https://github.com/justinsteven/advisories/blob/master/2021_github_actions_checkspelling_token_leak_via_advice_symlink.md| 
| 20210909 | Alles CTF 比赛中一个 macOS XPC 相关的 UAF 漏洞的分析及利用 | http://www.synacktiv.com/publications/macos-xpc-exploitation-sandbox-share-case-study.html| 
| 20210909 | Exploiting checkm8 with unknown SecureROM for the T2 chip | https://zeronights.ru/wp-content/uploads/2021/09/04_kovrizhnyh.pdf| 
| 20210909 | 利用 Opera 浏览器的 Stored XSS 漏洞实现本地文件读 | https://blogs.opera.com/security/2021/09/bug-bounty-guest-post-local-file-read-via-stored-xss-in-the-opera-browser/| 
| 20210909 | Yagi - 将 Ghidra decompiler 集成到 IDA 的工具 | https://github.com/airbus-cert/Yagi| 
| 20210909 | lsassy - 远程从 lsass dump 提取敏感凭据信息的工具 | https://github.com/Hackndo/lsassy| 
| 20210909 | Panda Dome Antivirus - Heap-Based Buffer Overflow Vulnerability | http://zeifan.my/security/heap/overflow/2021/09/08/panda-av-heap-overflow.html| 
| 20210909 | Khepri - Golang/C++ 语言写的一个跨平台的后渗透测试阶段的工具 | https://sec.today/pulses/0a75736d-c503-4d38-a972-073088bb59a2/| 
| 20210909 | Khepri - Golang/C++ 语言写的一个跨平台的后渗透测试阶段的工具 | https://github.com/geemion/Khepri| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210909 | IoT 恶意软件进化谱系研究 | https://mp.weixin.qq.com/s/xXYFcVOXA6lZfhign0BJlg| 
| 20210909 | Miara的延续--gafgyt病毒分析 | https://mp.weixin.qq.com/s/JYBdhxbt0mqU3wIqFFWdhQ| 
| 20210909 | HAProxy 场景绕过之一: CVE-2021-40346 | https://github.com/CHYbeta/OddProxyDemo/tree/master/haproxy/demo1| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210909T12:56:56Z | CVE-2021-37678 | TP Seguridad Informática | https://github.com/fran-CICS/ExploitTensorflowCVE-2021-37678 | TensorFlow is an end-to-end open source platform for machine learning. In affected versions TensorFlow and Keras can be tricked to perform arbitrary code execution when deserializing a Keras model from YAML format. The [implementation](https://github.com/tensorflow/tensorflow/blob/460e000de3a83278fb00b61a16d161b1964f15f4/tensorflow/python/keras/saving/model_config.py#L66-L104) uses `yaml.unsafe_load` which can perform arbitrary code execution on the input. Given that YAML format support requires a significant amount of work, we have removed it for now. We have patched the issue in GitHub commit 23d6383eb6c14084a8fc3bdf164043b974818012. The fix will be included in TensorFlow 2.6.0. We will also cherrypick this commit on TensorFlow 2.5.1, TensorFlow 2.4.3, and TensorFlow 2.3.4, as these are also affected and still in supported range.| 
| 20210909T11:48:48Z | CVE-2021-26084 | Confluence OGNL injection | https://github.com/dorkerdevil/CVE-2021-26084 | In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an unauthenticated attacker to execute arbitrary code on a Confluence Server or Data Center instance. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.| 
| 20210909T08:28:19Z | CVE-2021-39115 | Template Injection in Email Templates leads to code execution on Jira Service Management Server | https://github.com/PetrusViet/CVE-2021-39115 | Affected versions of Atlassian Jira Service Management Server and Data Center allow remote attackers with %Jira Administrators% access to execute arbitrary Java code or run arbitrary system commands via a Server_Side Template Injection vulnerability in the Email Template feature. The affected versions are before version 4.13.9, and from version 4.14.0 before 4.18.0.| 
| 20210909T04:01:49Z | 未知编号 | Null | https://github.com/itom-qe/itom-qe-2021-09-08-T-21-09-456-cveaj | | 
| 20210909T03:26:23Z | CVE-2021-40444 | Null | https://github.com/rfcxv/CVE-2021-40444-POC | 未查询到CVE信息| 
| 20210909T02:37:51Z | CVE-2021-1590 | PoC for exploiting CVE-2021-1590 : A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device. | https://github.com/AlAIAL90/CVE-2021-1590 | A vulnerability in the implementation of the system login block-for command for Cisco NX-OS Software could allow an unauthenticated, remote attacker to cause a login process to unexpectedly restart, causing a denial of service (DoS) condition. This vulnerability is due to a logic error in the implementation of the system login block-for command when an attack is detected and acted upon. An attacker could exploit this vulnerability by performing a brute-force login attack on an affected device. A successful exploit could allow the attacker to cause a login process to reload, which could result in a delay during authentication to the affected device.| 
| 20210909T02:37:48Z | CVE-2021-1591 | PoC for exploiting CVE-2021-1591 : A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface. | https://github.com/AlAIAL90/CVE-2021-1591 | A vulnerability in the EtherChannel port subscription logic of Cisco Nexus 9500 Series Switches could allow an unauthenticated, remote attacker to bypass access control list (ACL) rules that are configured on an affected device. This vulnerability is due to oversubscription of resources that occurs when applying ACLs to port channel interfaces. An attacker could exploit this vulnerability by attempting to access network resources that are protected by the ACL. A successful exploit could allow the attacker to access network resources that would be protected by the ACL that was applied on the port channel interface.| 
| 20210909T02:37:45Z | CVE-2021-1592 | PoC for exploiting CVE-2021-1592 : A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device. | https://github.com/AlAIAL90/CVE-2021-1592 | A vulnerability in the way Cisco UCS Manager software handles SSH sessions could allow an authenticated, remote attacker to cause a denial of service (DoS) condition on an affected device. This vulnerability is due to improper resource management for established SSH sessions. An attacker could exploit this vulnerability by opening a significant number of SSH sessions on an affected device. A successful exploit could allow the attacker to cause a crash and restart of internal Cisco UCS Manager software processes and a temporary loss of access to the Cisco UCS Manager CLI and web UI. Note: The attacker must have valid user credentials to authenticate to the affected device.| 
| 20210909T02:37:42Z | CVE-2021-32955 | PoC for exploiting CVE-2021-32955 : Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code. | https://github.com/AlAIAL90/CVE-2021-32955 | Delta Electronics DIAEnergie Version 1.7.5 and prior allows unrestricted file uploads, which may allow an attacker to remotely execute code.| 
| 20210909T02:37:39Z | CVE-2021-32967 | PoC for exploiting CVE-2021-32967 : Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges. | https://github.com/AlAIAL90/CVE-2021-32967 | Delta Electronics DIAEnergie Version 1.7.5 and prior may allow an attacker to add a new administrative user without being authenticated or authorized, which may allow the attacker to log in and use the device with administrative privileges.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T11:08:29Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2743 | 73| 
| 20210909T11:06:54Z | Backend application for running static analysis of rust-based programs | https://github.com/LedgerProject/safepkt_backend | 0 | 1| 
| 20210909T11:06:44Z | Web application for running static analysis of rust-based programs | https://github.com/LedgerProject/safepkt | 0 | 1| 
| 20210909T09:03:31Z | Null | https://github.com/kleeenz/kleeenzapp | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T06:42:02Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 149 | 37| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T13:09:20Z | Mon CV de Tehcnicien d%Exploitation | https://github.com/studentOCDBX/CV_tech_exploitation | 0 | 0| 
| 20210909T13:03:07Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 30 | 17| 
| 20210909T12:57:56Z | Rust Post-Exploitation Framework | https://github.com/ThottySploity/Nomios | 0 | 0| 
| 20210909T12:56:56Z | TP Seguridad Informática | https://github.com/fran-CICS/ExploitTensorflowCVE-2021-37678 | 0 | 0| 
| 20210909T12:53:48Z | Sub4Sub Website Exploits & Scripts | https://github.com/Tim2906/Sub4Sub | 2 | 0| 
| 20210909T12:52:38Z | 🔍NVD exploit & JVN(Japan Vulnerability Notes) easy description | https://github.com/nomi-sec/NVD-Exploit-List-Ja | 22 | 14| 
| 20210909T12:46:59Z | C# based tool which automates the process of discovering and exploiting DLL Hijacks in target binaries. The Hijacked paths discovered can later be weaponized during Red Team Operations to evade EDR%s. | https://github.com/knight0x07/ImpulsiveDLLHijack | 35 | 7| 
| 20210909T12:31:35Z | Übersicht remote command execution 0day exploit | https://github.com/BoofSec/Ubersicht-rce-0day | 5 | 0| 
| 20210909T11:35:13Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 10019 | 1673| 
| 20210909T11:08:09Z | Exploit Code | https://github.com/wjddnjs33/Exploit | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T07:13:07Z | Pupy is an opensource, cross-platform (Windows, Linux, OSX, Android) remote administration and post-exploitation tool mainly written in python | https://github.com/n1nj4sec/pupy | 6549 | 1657| 
| 20210909T06:48:28Z | Undetectable & Xor encrypting with custom KEY (FUD Metasploit Rat) bypass Top Antivirus like BitDefender,Malwarebytes,Avast,ESET-NOD32,AVG,... & Automatically Add ICON and MANIFEST to excitable | https://github.com/persianhydra/Xeexe-TopAntivirusEvasion | 548 | 126| 
| 20210909T04:40:47Z | TrojanZoo provides a universal pytorch platform to conduct security researches (especially backdoor attacks/defenses) of image classification in deep learning. | https://github.com/ain-soph/trojanzoo | 95 | 17| 
| 20210909T04:08:17Z | Backdoor Attacks on Lottery Ticket Hypothesis | https://github.com/zeyuanyin/LTH-Backdoor | 0 | 0| 
| 20210909T02:30:57Z | Remote control software | https://github.com/h1zzz/purewater | 0 | 0| 
| 20210909T02:21:54Z | https://51pwn.com,Awesome Penetration Testing，hacker tools collection, metasploit exploit, meterpreter....struts2、weblogic, 0day,poc,apt,backdoor,VulApps,vuln,pentest-script | https://github.com/hktalent/myhktools | 11 | 9| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T11:23:55Z | Symbolic-execution-based verifier for the Viper intermediate verification language. | https://github.com/viperproject/silicon | 20 | 12| 
| 20210909T11:19:30Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 157 | 34| 
| 20210909T10:37:27Z | Symbolica%s open-source symbolic execution engine. | https://github.com/SymbolicaDev/Symbolica | 21 | 1| 
| 20210909T08:43:09Z | A unit test-like interface for fuzzing and symbolic execution | https://github.com/trailofbits/deepstate | 654 | 65| 
| 20210909T08:17:50Z | RAUK: Automatic Schedulability Analysis of RTIC Applications Using Symbolic Execution | https://github.com/markhakansson/master-thesis | 5 | 0| 
| 20210909T06:42:02Z | S2E: A platform for multi-path program analysis with selective symbolic execution. | https://github.com/S2E/s2e | 149 | 37| 
| 20210909T04:20:56Z | Symbolic execution tool | https://github.com/trailofbits/manticore | 2448 | 362| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T00:18:45Z | Code for NDSS 2021 Paper %Manipulating the Byzantine: Optimizing Model Poisoning Attacks and Defenses Against Federated Learning% | https://github.com/vrt1shjwlkr/NDSS21-Model-Poisoning | 21 | 4| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210909T13:09:41Z | The first open-source AI-driven tool for automatically generating system-level test cases (also known as fuzzing) for web/enterprise applications. Currently targeting whitebox and blackbox testing of REST APIs. | https://github.com/EMResearch/EvoMaster | 181 | 36| 
| 20210909T13:02:33Z | a simplified means to CRUD ephemeral user-scoped EC2 instances | https://github.com/rstudio/fuzzbucket | 3 | 1| 
| 20210909T12:56:32Z | REASONING-FUZZY | https://github.com/irfanharfiansyah/REASONING-FUZZY | 0 | 0| 
| 20210909T12:56:32Z | Fuzzy inference system using python | https://github.com/rizkinabil/Fuzzy-Logic | 0 | 0| 
| 20210909T12:54:21Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210909T12:39:40Z | A JavaScript Engine Fuzzer | https://github.com/googleprojectzero/fuzzilli | 1288 | 230| 
| 20210909T12:28:40Z | Attempts to find security vulnerabilities in NetHack via input Fuzzing | https://github.com/recursion-ninja/NetHack-Fuzzing | 0 | 0| 
| 20210909T12:15:18Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 22 | 9| 
| 20210909T11:43:35Z | Null | https://github.com/s9varesc/url-fuzzing-results | 0 | 0| 
| 20210909T11:38:55Z | My first PHP application  | https://github.com/haricoder/fuzzy-telegram | 0 | 0| 



# 日更新程序

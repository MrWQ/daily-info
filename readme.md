# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210406 | 有关漏洞挖掘时需要做的工作的教程。 | https://github.com/KathanP19/HowToHunt| 
| 20210406 | 有关渗透等的 Hack 技术分享。 | https://book.hacktricks.xyz/| 
| 20210406 | 什么是有效的电子邮件地址？关于 RFC5321 4.1.2节定义的分析。 | http://www.netmeister.org/blog/email.html| 
| 20210406 | Breaking GitHub Private Pages for $35k | https://robertchen.cc/blog/2021/04/03/github-pages-xss| 
| 20210406 | 针对 Android 设备信息收集的脚本。 | https://blog.digital-forensics.it/2021/03/triaging-modern-android-devices-aka.html| 
| 20210406 | 【视频】通过分析 C 语言开发的二进制程序补丁来挖掘相关漏洞。 | https://www.youtube.com/watch?v=gb02dzgHBeU| 
| 20210406 | 基于 Rust 编写 Windows 内核驱动程序。 | https://not-matthias.github.io/kernel-driver-with-rust/| 
| 20210406 | AFINE：总结当前的 Java 反序列化的测试和利用方法。 | https://afinepl.medium.com/testing-and-exploiting-java-deserialization-in-2021-e762f3e43ca2| 
| 20210406 | CVE-2019-8761：由于 macOS 的默认文本编辑软件 TextEdit 解析 txt 文本中 HTML 标签，可以被利用泄漏文件或产生其它安全问题。 | https://www.paulosyibelo.com/2021/04/this-man-thought-opening-txt-file-is.html| 
| 20210406 | 基于上下文模糊测试和动态分析的XSS漏洞自动检测。 | https://sec.today/pulses/a74b6e7a-1a10-4f25-8a26-fe071d72d08f/| 
| 20210406 | PageBuster：静默转储 Linux 进程中所有可执行页面的工具。 | https://sec.today/pulses/9bfed75c-958c-4455-be5d-f068fbebb04e/| 
| 20210406 | John Hammond：一个基于 PowerShell 的 Payload 分析。 | https://sec.today/pulses/c37dba1f-57d5-44c9-bf74-407e6df1c174/| 
| 20210406 | Solar：对于 Solidity 智能合约开发语言的交互式静态分析框架。 | https://sec.today/pulses/ab70893d-a866-465f-87aa-7fc49bc1cb3f/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210406 | 俄罗斯网络空间攻击特点与模式 | https://mp.weixin.qq.com/s/oMy1EDOYPT82ec5QEdiIVA| 
| 20210406 | Dragos《2020年度工控网络安全回顾》 | https://mp.weixin.qq.com/s/ceASNJrgKkqgzlCnxNps7Q| 
| 20210406 | 驱动病毒那些事（完结）----劫持 | https://www.sec-in.com/article/997| 
| 20210406 | As-Exploits-部分后渗透模块 | https://mp.weixin.qq.com/s/8G0il9gIkubI1w15gOBX6A| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210406T10:44:28Z | CVE-2021-30109 | Froala Persistent XSS | https://github.com/Hackdwerg/CVE-2021-30109 | Froala Editor 3.2.6 is affected by Cross Site Scripting (XSS). Under certain conditions, a base64 crafted string leads to persistent Cross-site scripting (XSS) vulnerability within the hyperlink creation module.| 
| 20210406T10:39:53Z | CVE-2021-21972 | [CVE-2021-21972] VMware vSphere Client Unauthorized File Upload to Remote Code Execution (RCE) | https://github.com/murataydemir/CVE-2021-21972 | The vSphere Client (HTML5) contains a remote code execution vulnerability in a vCenter Server plugin. A malicious actor with network access to port 443 may exploit this issue to execute commands with unrestricted privileges on the underlying operating system that hosts vCenter Server. This affects VMware vCenter Server (7.x before 7.0 U1c, 6.7 before 6.7 U3l and 6.5 before 6.5 U3n) and VMware Cloud Foundation (4.x before 4.2 and 3.x before 3.10.1.2).| 
| 20210406T10:26:41Z | CVE-2021-22986 | CVE-2021-22986 & F5 BIG-IP RCE | https://github.com/Al1ex/CVE-2021-22986 | On BIG-IP versions 16.0.x before 16.0.1.1, 15.1.x before 15.1.2.1, 14.1.x before 14.1.4, 13.1.x before 13.1.3.6, and 12.1.x before 12.1.5.3 amd BIG-IQ 7.1.0.x before 7.1.0.3 and 7.0.0.x before 7.0.0.2, the iControl REST interface has an unauthenticated remote command execution vulnerability. Note: Software versions which have reached End of Software Development (EoSD) are not evaluated.| 
| 20210406T09:29:49Z | CVE-2021-30146 | Seafile 7.0.5 Persistent XSS | https://github.com/Security-AVS/CVE-2021-30146 | 未查询到CVE信息| 
| 20210406T09:17:43Z | CVE-2021-3297 | Null | https://github.com/Sec504/Zyxel-NBG2105-CVE-2021-3297 | On Zyxel NBG2105 V1.00(AAGU.2)C0 devices, setting the login cookie to 1 provides administrator access.| 
| 20210406T08:21:28Z | CVE-2021-3156 | Exploit for Sudo heap overflow (CVE-2021-3156) on Debain 10 | https://github.com/0xdevil/CVE-2021-3156 | Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via %sudoedit -s% and a command-line argument that ends with a single backslash character.| 
| 20210406T02:14:31Z | CVE-2021-21300 | Null | https://github.com/fengzhouc/CVE-2021-21300 | Git is an open-source distributed revision control system. In affected versions of Git a specially crafted repository that contains symbolic links as well as files using a clean/smudge filter such as Git LFS, may cause just-checked out script to be executed while cloning onto a case-insensitive file system such as NTFS, HFS+ or APFS (i.e. the default file systems on Windows and macOS). Note that clean/smudge filters have to be configured for that. Git for Windows configures Git LFS by default, and is therefore vulnerable. The problem has been patched in the versions published on Tuesday, March 9th, 2021. As a workaound, if symbolic link support is disabled in Git (e.g. via `git config --global core.symlinks false`), the described attack won%t work. Likewise, if no clean/smudge filters such as Git LFS are configured globally (i.e. _before_ cloning), the attack is foiled. As always, it is best to avoid cloning repositories from untrusted sources. The earliest impacted version is 2.14.2. The fix versions are: 2.30.1, 2.29.3, 2.28.1, 2.27.1, 2.26.3, 2.25.5, 2.24.4, 2.23.4, 2.22.5, 2.21.4, 2.20.5, 2.19.6, 2.18.5, 2.17.62.17.6.| 
| 20210406T01:57:31Z | CVE-2021-26855 | Null | https://github.com/shacojx/CVE-2021-26855-exploit-Exchange | | 
| 20210406T01:24:42Z | CVE-2021-21975 | Nmap script to check vulnerability CVE-2021-21975 | https://github.com/GuayoyoCyber/CVE-2021-21975 | Server Side Request Forgery in vRealize Operations Manager API (CVE-2021-21975) prior to 8.4 may allow a malicious actor with network access to the vRealize Operations Manager API can perform a Server Side Request Forgery attack to steal administrative credentials.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210406T04:12:36Z | Null | https://github.com/abbykleespie/Assignment4AbbyKleespie.appstudio | 0 | 0| 
| 20210406T03:53:43Z | Null | https://github.com/bboysteed/klee_test | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210406T11:55:30Z | 📈 A visualization of MetricQ data exploiting the advantages of the HTA db backend  | https://github.com/metricq/metricq-webview | 0 | 1| 
| 20210406T11:50:59Z | Scripts and programs used in exploiting Windows-Based Buffer Overflow | https://github.com/ravi5hanka/Windows-Buffer-Overflow- | 0 | 0| 
| 20210406T11:45:10Z | Online visual analytics tool designed to investigate how attention maps in transformer models behaves, and build hypothesis on those models bias exploitation.  | https://github.com/Theo-Jaunet/VisQA | 0 | 0| 
| 20210406T11:44:52Z | The official Exploit Database repository | https://github.com/offensive-security/exploitdb | 6011 | 1708| 
| 20210406T11:25:46Z | Vulmap 是一款 web 漏洞扫描和验证工具, 可对 webapps 进行漏洞扫描, 并且具备漏洞验证功能 | https://github.com/zhzyker/vulmap | 1178 | 212| 
| 20210406T11:02:36Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 21 | 8| 
| 20210406T10:34:51Z | linux post-exploitation framework made by linux user | https://github.com/jm33-m0/emp3r0r | 434 | 81| 
| 20210406T10:30:51Z | Exploit Development and Reverse Engineering with GDB Made Easy | https://github.com/pwndbg/pwndbg | 3553 | 518| 
| 20210406T10:10:56Z | Null | https://github.com/I7Z3R0/Exploit | 1 | 0| 
| 20210406T09:57:39Z | IC1 project part %Low% (Exploitation) | https://github.com/buykjk/ic1-project-low | 0 | 0| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210406T00:26:30Z | [Disclaimer FireROOT] This repository is for research purposes only, the use of this code is your responsibility. CONTACT ME: Attack@fireRootHacker.Ga | https://github.com/facenano/fireroothacker | 1 | 1| 
| 20210406T00:13:50Z | Arsnick is a Python IRC Bot/Backdoor written in Python | https://github.com/netzwerk/Arsnick | 0 | 0| 
| 20210406T00:04:39Z | hidden Backdoor in Python | https://github.com/ilovehcking/Backdoor_JUSTIN | 1 | 0| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210406T01:27:12Z | Generator of random circuits | https://github.com/drom/circt-fuzzer | 1 | 0| 
| 20210406T00:53:03Z | RESTler is the first stateful REST API fuzzing tool for automatically testing cloud services through their REST APIs and finding security and reliability bugs in these services. | https://github.com/microsoft/restler-fuzzer | 739 | 75| 
| 20210406T00:44:22Z | Software for fuzzing, used on web application pentestings. | https://github.com/NESCAU-UFLA/FuzzingTool | 48 | 8| 
| 20210406T00:37:42Z | Fuzzy matching for Neovim | https://github.com/amirrezaask/fuzzy.nvim | 23 | 1| 
| 20210406T00:29:38Z | A self-hosted Fuzzing-As-A-Service platform | https://github.com/microsoft/onefuzz | 2305 | 123| 
| 20210406T00:15:32Z | OSS-Fuzz - continuous fuzzing for open source software. | https://github.com/google/oss-fuzz | 6179 | 1248| 
| 20210406T00:09:33Z | A Fuzzer implementation in Rust following the guidelines exposed in https://www.fuzzingbook.org/. | https://github.com/fuzzing-unb/Ruszzer | 0 | 0| 
| 20210406T00:07:29Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 1 | 0| 



# 日更新程序

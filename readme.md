# 互联网安全 推荐
| ts | title | url| 
| --- | --- | ---| 


# 玄武实验室 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210730 | A virtual journey: From hardware virtualization to Hyper-Vs Virtual Trust Levels | http://blog.quarkslab.com/a-virtual-journey-from-hardware-virtualization-to-hyper-vs-virtual-trust-levels.html| 
| 20210730 | 2186 - Exchange: AD Schema Misconfiguration Elevation of Privilege | https://bugs.chromium.org/p/project-zero/issues/detail?id=2186| 
| 20210730 | Kernel Pwning with eBPF: a Love Story | https://www.graplsecurity.com/post/kernel-pwning-with-ebpf-a-love-story| 
| 20210730 | hallucinate - 基于动态插桩实现的 TLS 流量 Hook 和修改工具 | https://blog.syss.com/posts/hallucinate/| 
| 20210730 | 研究员 Axel Souchet Fuzz IDA 发现大量内存类问题 | https://github.com/0vercl0k/fuzzing-ida75| 
| 20210730 | Pre-Auth RCE in Moodle Part I - PHP Object Injection in Shibboleth | http://haxolot.com/posts/2021/moodle_pre_auth_shibboleth_rce_part1/| 
| 20210730 | 利用欺骗的方式检测 AD 域环境的 Bloodhound 探测和渗透行为 | https://medium.com/securonix-tech-blog/detecting-ldap-enumeration-and-bloodhound-s-sharphound-collector-using-active-directory-decoys-dfc840f2f644| 
| 20210730 | 欧盟网络安全局发布调查报告称，涉及供应链的攻击快速增长且应对不足 | http://www.enisa.europa.eu/news/enisa-news/understanding-the-increase-in-supply-chain-security-attacks| 
| 20210730 | 现在的 Linux 恶意软件常常会主动检查并禁用系统和第三方的一些安全监控软件 | https://threatpost.com/six-malicious-linux-shell-scripts-how-to-stop-them/168127/| 


# 安全维基 推荐
| ts | title | url| 
| --- | --- | ---| 
| 20210730 | [HTB] Active Writeup | https://mp.weixin.qq.com/s/-6eTR-2WCnVSRnn2DjgRmg| 
| 20210730 | 第二届网鼎杯线下决赛网络靶场复盘 | https://mp.weixin.qq.com/s/rXqSfjTFUQJsirkhi1hmHQ| 
| 20210730 | 强行打点途径 | https://www.yuque.com/ee/nangod/bh75w2| 


# CVE Github 推荐
| ts | cve_id | title | url | cve_detail| 
| --- | --- | --- | --- | ---| 
| 20210730T12:34:50Z | CVE-2021-3490 | Null | https://github.com/chompie1337/Linux_LPE_eBPF_CVE-2021-3490 | The eBPF ALU32 bounds tracking for bitwise ops (AND, OR and XOR) in the Linux kernel did not properly update 32-bit bounds, which could be turned into out of bounds reads and writes in the Linux kernel and therefore, arbitrary code execution. This issue was fixed via commit 049c4e13714e (%bpf: Fix alu32 const subreg bound tracking on bitwise operations%) (v5.13-rc4) and backported to the stable kernels in v5.12.4, v5.11.21, and v5.10.37. The AND/OR issues were introduced by commit 3f50f132d840 (%bpf: Verifier, do explicit ALU32 bounds tracking%) (5.7-rc1) and the XOR variant was introduced by 2921c90d4718 (%bpf:Fix a verifier failure with xor%) ( 5.10-rc1).| 
| 20210730T12:29:18Z | CVE-2021-36934 | CVE-2021-36934 HiveNightmare vulnerability checker and workaround | https://github.com/irissentinel/CVE-2021-36934 | Windows Elevation of Privilege Vulnerability| 
| 20210730T11:55:50Z | CVE-2021-24155 | WordPress Backup Guard Authenticated Remote Code Execution Exploit | https://github.com/0Day-dev/CVE-2021-24155.rb | The WordPress Backup and Migrate Plugin – Backup Guard WordPress plugin before 1.6.0 did not ensure that the imported files are of the SGBP format and extension, allowing high privilege users (admin+) to upload arbitrary files, including PHP ones, leading to RCE.| 
| 20210730T11:43:35Z | CVE-2021-3560 | Polkit D-Bus Authentication Bypass Exploit | https://github.com/0Day-dev/CVE-2021-3560 | 未查询到CVE信息| 
| 20210730T07:53:07Z | CVE-2020-15368 | How to exploit a vulnerable windows driver. Exploit for AsrDrv104.sys | https://github.com/stong/CVE-2020-15368 | AsrDrv103.sys in the ASRock RGB Driver does not properly restrict access from user space, as demonstrated by triggering a triple fault via a request to zero CR3.| 
| 20210730T03:48:26Z | cve-2021-1480 | Null | https://github.com/xmco/sdwan-cve-2021-1480 | Multiple vulnerabilities in Cisco SD-WAN vManage Software could allow an unauthenticated, remote attacker to execute arbitrary code or allow an authenticated, local attacker to gain escalated privileges on an affected system. For more information about these vulnerabilities, see the Details section of this advisory.| 
| 20210730T01:22:36Z | CVE-2021-33909 | Null | https://github.com/ikramimamoglu/AmIAHuman-CVE-2021-33909 | fs/seq_file.c in the Linux kernel 3.16 through 5.13.x before 5.13.4 does not properly restrict seq buffer allocations, leading to an integer overflow, an Out-of-bounds Write, and escalation to root by an unprivileged user, aka CID-8cae8cd89f05.| 


# klee on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210730T12:34:11Z | An open-source Chinese font derived from Fontworks% Klee One. 一款基于 FONTWORKS 的 Klee One 的开源中文字体。 | https://github.com/lxgw/LxgwWenKai | 2438 | 57| 
| 20210730T09:34:23Z | Null | https://github.com/xenoney/kleee | 0 | 0| 


# s2e on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# exploit on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210730T12:35:14Z | This repository is primarily maintained by Omar Santos and includes thousands of resources related to ethical hacking  / penetration testing, digital forensics and incident response (DFIR), vulnerability research, exploit development, reverse engineering, and more. | https://github.com/The-Art-of-Hacking/h4cker | 9782 | 1615| 
| 20210730T12:34:20Z | Exploits project Hacking Command Center | https://github.com/chacka0101/exploits | 12 | 10| 
| 20210730T12:28:59Z |  CamOver is a camera exploitation tool that allows to disclosure network camera admin password. | https://github.com/EntySec/CamOver | 71 | 22| 
| 20210730T12:26:03Z | A Roblox Exploit | https://github.com/WhyTeaCEO/WhyTea-Hax | 0 | 0| 
| 20210730T12:15:47Z | System Exploitation Fundamental | https://github.com/JiWonOck/DreamHack | 0 | 0| 
| 20210730T12:02:57Z | Open-Source Vulnerability Intelligence Center - Unified source of vulnerability, exploit and threat Intelligence feeds | https://github.com/Patrowl/PatrowlHearsData | 29 | 14| 
| 20210730T12:01:11Z | A python based tool for exploiting and managing Android devices via ADB | https://github.com/mesquidar/adbsploit | 233 | 49| 
| 20210730T11:57:37Z | CamRaptor is a tool that exploits several vulnerabilities in popular DVR cameras to obtain network camera credentials. | https://github.com/EntySec/CamRaptor | 49 | 12| 
| 20210730T11:55:50Z | WordPress Backup Guard Authenticated Remote Code Execution Exploit | https://github.com/0Day-dev/CVE-2021-24155.rb | 1 | 1| 
| 20210730T11:48:46Z | Fast jacobian computation through sparsity exploitation and matrix coloring | https://github.com/JuliaDiff/SparseDiffTools.jl | 100 | 18| 


# backdoor on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210730T11:04:46Z | Null | https://github.com/gduweng/simple-c-backdoor | 0 | 0| 
| 20210730T10:39:38Z | Implementation of a native-code HatSploit membrane for unix-like systems, designed for portability, embeddability, and low resource utilization. | https://github.com/EntySec/membrane | 6 | 3| 
| 20210730T05:48:40Z | A curated list of backdoor learning resources | https://github.com/THUYimingLi/backdoor-learning-resources | 270 | 51| 
| 20210730T02:25:59Z | The code of AAAI-21 paper %Defending against Backdoors in Federated Learning with Robust Learning Rate%. | https://github.com/TinfoilHat0/Defending-Against-Backdoors-with-Robust-Learning-Rate | 0 | 1| 
| 20210730T00:59:59Z | Python AV Evasion Tools | https://github.com/G1ft3dC0d3/MsfMania | 190 | 45| 


# symbolic execution on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210730T10:45:08Z | symbolic execution plugin for binary ninja | https://github.com/borzacchiello/seninja | 91 | 6| 
| 20210730T08:39:33Z | The symbolic execution engine powering the K Framework | https://github.com/kframework/kore | 153 | 33| 
| 20210730T08:39:14Z | Triton is a Dynamic Binary Analysis (DBA) framework. It provides internal components like a Dynamic Symbolic Execution (DSE) engine, a dynamic taint engine, AST representations of the x86, x86-64, ARM32 and AArch64 Instructions Set Architecture (ISA), SMT simplification passes, an SMT solver interface and, the last but not least, Python bindings. | https://github.com/JonathanSalwan/Triton | 1856 | 388| 
| 20210730T08:02:07Z | A toy symbolic execution engine, supporting the blog article ... | https://github.com/synacktiv/toy-wasm-symbexp | 2 | 1| 


# big4 on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 


# fuzz on Github 推荐
| ts | title | url | stars | forks| 
| --- | --- | --- | --- | ---| 
| 20210730T12:40:13Z | Fuzzinator Random Testing Framework | https://github.com/renatahodovan/fuzzinator | 178 | 38| 
| 20210730T12:35:05Z | Null | https://github.com/randstad-strategic-analytics/fuzzy_merge | 0 | 0| 
| 20210730T12:22:57Z | A JavaScript Engine Fuzzer | https://github.com/googleprojectzero/fuzzilli | 1256 | 225| 
| 20210730T12:15:13Z | OSS-Fuzz vulnerabilities for OSV. | https://github.com/google/oss-fuzz-vulns | 20 | 8| 
| 20210730T12:15:02Z | Dictionary of attack patterns and primitives for black-box application fault injection and resource discovery. | https://github.com/fuzzdb-project/fuzzdb | 5896 | 1760| 
| 20210730T12:03:16Z | Advanced Fuzzing Library - Slot your Fuzzer together in Rust! Scales across cores and machines. For Windows, Android, MacOS, Linux, no_std, ... | https://github.com/AFLplusplus/LibAFL | 511 | 48| 
| 20210730T12:03:16Z | The fuzzer afl++ is afl with community patches, qemu 5.1 upgrade, collision-free coverage, enhanced laf-intel & redqueen, AFLfast++ power schedules, MOpt mutators, unicorn_mode, and a lot more! | https://github.com/AFLplusplus/AFLplusplus | 1936 | 384| 
| 20210730T12:02:46Z | Null | https://github.com/zyrouge/fuzzle | 0 | 1| 
| 20210730T11:48:19Z | Fuzzing cryptographic libraries. Magic bug printer go brrrr. | https://github.com/guidovranken/cryptofuzz | 291 | 39| 
| 20210730T11:44:37Z | Associating input coverage to code coverage for targeted fuzzing | https://github.com/havrikov/codeine | 0 | 0| 



# 日更新程序

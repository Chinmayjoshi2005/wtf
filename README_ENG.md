# Collected Projects:
- [Collection of all open-source tools: sec-tool-list](https://github.com/alphaSeclab/sec-tool-list): More than 18K entries, available in both Markdown and JSON formats.
- [Cross-platform reverse-engineering resources: awesome-reverse-engineering](https://github.com/alphaSeclab/awesome-reverse-engineering):
    - Windows平台安全: PE/DLL/DLL-Injection/Dll-Hijack/Dll-Load/UAC-Bypass/Sysmon/AppLocker/ETW/WSL/.NET/Process-Injection/Code-Injection/DEP/Kernel/...
    - Linux安全: ELF/...
    - macOS/iXxx安全: Mach-O/越狱/LLDB/XCode/...
    - Android安全: HotFix/XPosed/Pack/Unpack/Emulator/Obfuscate
    - 知名工具: IDA/Ghidra/x64dbg/OllDbg/WinDBG/CuckooSandbox/Radare2/BinaryNinja/DynamoRIO/IntelPin/Frida/QEMU/...
- [Network-related security resources: awesome-network-stuff](https://github.com/alphaSeclab/awesome-network-stuff):
    - 网络通信: 代理/SS/V2ray/GFW/反向代理/隧道/VPN/Tor/I2P/...
    - 网络攻击: 中间人/PortKnocking/...
    - 网络分析: 嗅探/协议分析/网络可视化/网络分析/网络诊断等
- [Offensive cybersecurity resources: awesome-cyber-security](https://github.com/alphaSeclab/awesome-cyber-security): Vulnerabilities/Penetration Testing/IoT Security/Data Penetration/Metasploit/BurpSuite/KaliLinux/C&C/OWASP/AV Evasion/CobaltStrike/Reconnaissance/OSINT/Social Engineering/Passwords/Credentials/Threat Hunting/Payload/Wi-Fi Hacking/Wireless Attacks/Post-Exploitation/Privilege Escalation/UAC Bypass/...
- [Open-source remote-access tools and reports analysing malicious remote-access tools: awesome-rat](https://github.com/alphaSeclab/awesome-rat): Open-source remote-access tools for Windows/Linux/macOS/Android, along with reports analysing remote-access malware.
- [Webshell tools and articles about their analysis and usage: awesome-webshell](https://github.com/alphaSeclab/awesome-webshell): A collection of webshell resources, including 150 GitHub projects and around 200 articles.
- [Forensics-related tools and articles: awesome-forensics](https://github.com/alphaSeclab/awesome-forensics): Nearly 300 open-source forensics tools and nearly 600 articles related to digital forensics.




# ReverseEngineering


- A collection of reverse-engineering resources. It currently includes 3,500+ tools, roughly classified by function, with Chinese descriptions for some tools, and 2,300+ articles.
- This page contains only part of the collection. [View the full version](https://github.com/alphaSeclab/awesome-reverse-engineering/blob/master/Readme_full.md)



# Notes
[EnglishVersion](https://github.com/alphaSeclab/awesome-reverse-engineering/blob/master/Readme_en.md)


# Table of Contents
- [Windows](#2f81493de610f9b796656b269380b2de)
    - [PE](#620af0d32e6ac1f4a3e97385d4d3efc0)
        - [(68) Tools](#574db8bbaafbee72eeb30e28e2799458)
        - [(324) Articles](#7e890d391fa32df27beb1377a371518b)
    - [DLL](#89f963773ee87e2af6f9170ee60a7fb2)
        - [DLL注入](#3b4617e54405a32290224b729ff9f2b3)
            - [(67) Tools](#b0d50ee42d53b1f88b32988d34787137)
            - [(70) Articles](#1a0b0dab4cdbab08bbdc759bab70dbb6)
        - [DLL劫持](#f39e40e340f61ae168b67424baac5cc6)
            - [(60) Articles](#01e95333e07439ac8326253aa8950b4f)
            - [(18) Tools](#c9cdcc6f4acbeda6c8ac8f4a1ba1ea6b)
        - [Recently Added](#4dcfd9135aa5321b7fa65a88155256f9)
            - [(16) Articles](#b05f4c5cdfe64e1dde2a3c8556e85827)
            - [(107) Tools](#9753a9d52e19c69dc119bf03e9d7c3d2)
    - [UAC](#40fd1488e4a26ebf908f44fdcedd9675)
        - [(29) Tools](#02517eda8c2519c564a19219e97d6237)
        - [(123) Articles](#90d7d5feb7fd506dc8fd6ee0d7e98285)
    - [Sysmon](#0fed6a96b28f339611e7b111b8f42c23)
        - [(12) Tools](#d48f038b58dc921660be221b4e302f70)
        - [(131) Articles](#2c8cb7fdf765b9d930569f7c64042d62)
    - [ETW](#ac43a3ce5a889d8b18cf22acb6c31a72)
        - [(64) Articles](#11c4c804569626c1eb02140ba557bb85)
        - [(35) Tools](#0af4bd8ca0fd27c9381a2d1fa8b71a1f)
    - [AppLocker](#184bbacd8b9e08c30cc9ffcee9513f44)
        - [(11) Tools](#8f1876dff78e80b60d00de25994276d9)
        - [(93) Articles](#286317d6d7c1a0578d8f5db940201320)
    - [Tools](#b478e9a9a324c963da11437d18f04998)
        - [(213) Other](#1afda3039b4ab9a3a1f60b179ccb3e76)
        - [(10) .NET](#d90b60dc79837e06d8ba2a7ee1f109d3)
        - [Recently Added](#f9fad1d4d1f0e871a174f67f63f319d8)
        - [(5) Environment&&环境&&配置](#6d2fe834b7662ecdd48c17163f732daf)
        - [Process Injection](#8bfd27b42bb75956984994b3419fb582)
        - [Code Injection](#1c6069610d73eb4246b58d78c64c9f44)
        - [Memory Modules](#7c1541a69da4c025a89b0571d8ce73d2)
        - [(6) VT&&Virtualisation&&Hypbervisor](#19cfd3ea4bd01d440efb9d4dd97a64d0)
        - [(8) Kernel&&Drivers](#c3cda3278305549f4c21df25cbf638a4)
        - [(3) Registry](#920b69cea1fc334bbc21a957dd0d9f6f)
        - [(4) System Calls](#d295182c016bd9c2d5479fe0e98a75df)
        - [(3) Procmon](#518d80dfb8e9dda028d18ace1d3f3981)
    - [Articles](#3939f5e83ca091402022cb58e0349ab8)
        - [Recently Added](#8e1344cae6e5f9a33e4e5718a012e292)
        - [(5) Procmon](#af06263e9a92f6036dc5d4c4b28b9d8c)
        - [(68) DEP](#fa89526db1f9373c57ea4ffa1ac8c39f)
- [Linux](#dc664c913dc63ec6b98b47fcced4fdf0)
    - [ELF](#a63015576552ded272a242064f3fe8c9)
        - [(59) Tools](#929786b8490456eedfb975a41ca9da07)
        - [(102) Articles](#72d101d0f32d5521d5d305e7e653fdd3)
    - [Tools](#89e277bca2740d737c1aeac3192f374c)
        - [(99) Recently Added](#203d00ef3396d68f5277c90279f4ebf3)
    - [Articles](#f6d78e82c3e5f67d13d9f00c602c92f0)
        - [Recently Added](#bdf33f0b1200cabea9c6815697d9e5aa)
- [Apple&&iOS&&iXxx](#069664f347ae73b1370c4f5a2ec9da9f)
    - [Mach-O](#830f40713cef05f0665180d840d56f45)
        - [(28) Tools](#9b0f5682dc818c93c4de3f46fc3f43d0)
        - [(24) Articles](#750700dcc62fbd83e659226db595b5cc)
    - [Jailbreaking](#bba00652bff1672ab1012abd35ac9968)
        - [(96) Tools](#ff19d5d94315d035bbcb3ef0c348c75b)
        - [(14) Articles](#cbb847a025d426a412c7cd5d8a2332b5)
    - [LLDB](#004d0b9e325af207df8e1ca61af7b721)
        - [(11) Tools](#c20772abc204dfe23f3e946f8c73dfda)
        - [(17) Articles](#86eca88f321a86712cc0a66df5d72e56)
    - [Xcode](#977cef2fc942ac125fa395254ab70eea)
        - [(18) Tools](#7037d96c1017978276cb920f65be2297)
        - [(49) Articles](#a2d228a68b40162953d3d482ce009d4e)
    - [Tools](#58cd9084afafd3cd293564c1d615dd7f)
        - [(319) Recently Added](#d0108e91e6863289f89084ff09df39d0)
    - [Articles & Videos](#c97bbe32bbd26c72ceccb43400e15bf1)
        - [Recently Added](#d4425fc7c360c2ff324be718cf3b7a78)
- [Android](#11a59671b467a8cdbdd4ea9d5e5d9b51)
    - [Tools](#2110ded2aa5637fa933cc674bc33bf21)
        - [(183) Recently Added](#883a4e0dd67c6482d28a7a14228cd942)
        - [(4) HotFix](#fa49f65b8d3c71b36c6924ce51c2ca0c)
        - [(1) 打包](#ec395c8f974c75963d88a9829af12a90)
        - [(2) Collections](#767078c52aca04c452c095f49ad73956)
        - [(1) 各ClassesApp](#17408290519e1ca7745233afea62c43c)
        - [(30) Xposed](#7f353b27e45b5de6b0e6ac472b02cbf1)
        - [(19) Packing&&Unpacking](#50f63dce18786069de2ec637630ff167)
        - [(12) HOOK](#596b6cf8fd36bc4c819335f12850a915)
        - [(9) Emulator&&Emulators](#5afa336e229e4c38ad378644c484734a)
        - [(6) IDA](#0a668d220ce74e11ed2738c4e3ae3c9e)
        - [(11) Debug&&Debugging](#bb9f8e636857320abf0502c19af6c763)
        - [(34) Malware&&Malware](#f975a85510f714ec3cc2551e868e75b8)
        - [(5) Obfuscate&&Obfuscation](#1d83ca6d8b02950be10ac8e4b8a2d976)
        - [(15) ReverseEngineering](#6d2b758b3269bac7d69a2d2c8b45194c)
        - [(319) Recently Added1](#63fd2c592145914e99f837cecdc5a67c)
    - [(2) Articles and Videos](#f0493b259e1169b5ddd269b13cfd30e6)
- [IDA](#08e59e476824a221f6e4a69c0bba7d63)
    - [Plugins&&Scripts](#f11ab1ff46aa300cc3e86528b8a98ad7)
        - [(97) Uncategorised](#c39a6d8598dde6abfeef43faf931beb5)
        - [Structures&&Classes的Detection&&Creation&&Recovery](#fb4f0c061a72fc38656691746e7c45ce)
            - [(6) Uncategorised](#fa5ede9a4f58d4efd98585d3158be4fb)
            - [(8) C++Classes&&虚表](#4900b1626f10791748b20630af6d6123)
        - [(3) Collections](#a7dac37cd93b8bb42c7d6aedccb751b3)
        - [(9) Appearance&&Themes](#fabf03b862a776bbd8bcc4574943a65a)
        - [(4) Firmware&&Embedded Devices](#a8f5db3ab4bc7bc3d6ca772b3b9b0b1e)
        - [Signatures(FLIRT等)&&Comparison(Diff)&&Matching](#02088f4884be6c9effb0f1e9a3795e58)
            - [(17) Uncategorised](#cf04b98ea9da0056c055e2050da980c1)
            - [FLIRTSignatures](#19360afa4287236abe47166154bc1ece)
                - [(3) FLIRTSignaturesCollections](#1c9d8dfef3c651480661f98418c49197)
                - [(2) FLIRTSignatures生成](#a9a63d23d32c6c789ca4d2e146c9b6d0)
            - [(11) Diff&&MatchTools](#161e5a3437461dc8959cc923e6a18ef7)
            - [(7) Yara](#46c9dfc585ae59fe5e6f7ddf542fb31a)
        - [(6) IDB操作](#5e91b280aab7f242cbc37d64ddbff82f)
        - [(5) Collaborative Reverse Engineering&&Multiple Users Working on the Same IDB File](#206ca17fc949b8e0ae62731d9bb244cb)
        - [(9) Synchronisation with the Debugger&&Communication&&Interaction](#f7d311685152ac005cfce5753c006e4b)
        - [Import/Export&Interoperability with Other Tools](#6fb7e41786c49cc3811305c520dfe9a1)
            - [(13) Uncategorised](#8ad723b704b044e664970b11ce103c09)
            - [(5) Ghidra](#c7066b0c388cd447e980bf0eb38f39ab)
            - [(3) BinNavi](#11139e7d6db4c1cef22718868f29fe12)
            - [(3) BinaryNinja](#d1ff64bee76f6749aef6100d72bfbe3a)
            - [(2) Radare2](#21ed198ae5a974877d7a635a4b039ae3)
            - [(4) Frida](#a1cf7f7f849b4ca2101bd31449c2a0fd)
            - [(2) IntelPin](#dd0332da5a1482df414658250e6357f8)
        - [Target-Specific Analysis](#004c199e1dbf71769fbafcd8e58d1ead)
            - [(26) Uncategorised](#5578c56ca09a5804433524047840980e)
            - [(2) GoLang](#1b17ac638aaa09852966306760fda46b)
            - [(4) WindowsDrivers](#4c158ccc5aee04383755851844fdd137)
            - [(4) PS3&&PS4](#315b1b8b41c67ae91b841fce1d4190b5)
            - [(33) Loader&Processor](#cb59d84840e41330a7b5e275c0b81725)
            - [(4) PDB](#f5e51763bb09d8fd47ee575a98bedca1)
            - [(2) Flash&&SWF](#7d0681efba2cf3adaba2780330cd923a)
            - [(4) Specific Malware Families](#841d605300beba45c3be131988514a03)
            - [(1) CTF](#ad44205b2d943cfa2fa805b2643f4595)
        - [IDAPython本身](#ad68872e14f70db53e8d9519213ec039)
            - [(8) Uncategorised](#2299bc16945c25652e5ad4d48eae8eca)
            - [(1) 清单](#c42137cf98d6042372b1fd43c3635135)
        - [(6) Instruction Reference&Documentation](#846eebe73bef533041d74fc711cafb43)
        - [Script-Writing Helpers](#c08ebe5b7eec9fc96f8eff36d1d5cc7d)
            - [(9) Uncategorised](#45fd7cfce682c7c25b4f3fbc4c461ba2)
            - [(3) Qt](#1a56a5b726aaa55ec5b7a5087d6c8968)
            - [(3) Console&&Window Interface](#1721c09501e4defed9eaa78b8d708361)
            - [(2) Plugins模板](#227fbff77e3a13569ef7b007344d5d2e)
            - [(2) Other语言](#8b19bb8cf9a5bc9e6ab045f3b4fabf6a)
        - [(16) Legacy](#dc35a2b02780cdaa8effcae2b6ce623e)
        - [Debugging&&Dynamic Execution&Dynamic Data](#e3e7030efc3b4de3b5b8750b7d93e6dd)
            - [(10) Uncategorised](#2944dda5289f494e5e636089db0d6a6a)
            - [(10) DBI数据](#0fbd352f703b507853c610a664f024d1)
            - [(4) Debugging数据](#b31acf6c84a9506066d497af4e702bf5)
        - [(14) Decompilers&&AST](#d2166f4dac4eab7fadfe0fd06467fbc9)
        - [(7) Deobfuscation](#7199e8787c0de5b428f50263f965fda7)
        - [Efficiency&&Navigation&&Quick Access&&Graphs&&Images&&Visualisation](#fcf75a0881617d1f684bc8b359c684d7)
            - [(15) Other](#c5b120e1779b928d860ad64ff8d23264)
            - [(9) Display Enhancements](#03fac5b3abdbd56974894a261ce4e25f)
            - [(3) Graphs&&Images](#3b1dba00630ce81cba525eea8fcdae08)
            - [(3) Search](#8f9468e9ab26128567f4be87ead108d7)
        - [(7) Android](#66052f824f5054aa0f70785a2389a478)
        - [Apple&&macOS&&iXxx&&Objective-C&&SWift&&Mach-O](#2adc0044b2703fb010b3bf73b1f1ea4a)
            - [(5) Uncategorised](#8530752bacfb388f3726555dc121cb1a)
            - [(3) Kernel缓存](#82d0fa2d6934ce29794a651513934384)
            - [(3) Mach-O](#d249a8d09a3f25d75bb7ba8b32bd9ec5)
            - [(3) Swift](#1c698e298f6112a86c12881fbd8173c7)
        - [(9) ELF](#e5e403123c70ddae7bd904d3a3005dbb)
        - [(5) Microcode](#7a2977533ccdac70ee6e58a7853b756b)
        - [(6) Emulators集成](#b38dab81610be087bd5bc7785269b8cc)
        - [(4) Recently Added](#c39dbae63d6a3302c4df8073b4d1cdc8)
        - [(4) 作为辅助&&构成Other的一环](#83de90385d03ac8ef27360bfcdc1ab48)
        - [Vulnerabilities](#1ded622dca60b67288a591351de16f8b)
            - [(7) Uncategorised](#385d6777d0747e79cccab0a19fa90e7e)
            - [(2) ROP](#cf2efa7e3edb24975b92d2e26ca825d2)
        - [(7) 补丁&&Patch](#7d557bc3d677d206ef6c5a35ca8b3a14)
        - [(3) Other](#7dfd8abad50c14cd6bdc8d8b79b6f595)
        - [函数相关](#90bf5d31a3897400ac07e15545d4be02)
            - [(4) Uncategorised](#347a2158bdd92b00cd3d4ba9a0be00ae)
            - [(6) 重命名&&前缀&&标记](#73813456eeb8212fd45e0ea347bec349)
            - [(5) Navigation&&查看&&查找](#e4616c414c24b58626f834e1be079ebc)
            - [(2) demangle](#cadae88b91a57345d266c68383eb05c5)
        - [(3) 污点分析&&符号执行](#34ac84853604a7741c61670f2a075d20)
        - [(8) 字符串](#9dcc6c7dd980bec1f92d0cc9a2209a24)
        - [(3) 加密解密](#06d2caabef97cf663bd29af2b1fe270c)
    - [Articles](#18c6a45392d6b383ea24b363d2f3e76b)
        - [(6) 系列Articles-LabelessPlugins介绍](#04cba8dbb72e95d9c721fe16a3b48783)
        - [(24) 系列Articles-使用IDA从零开始学逆向](#1a2e56040cfc42c11c5b4fa86978cc19)
        - [系列Articles-IDAPython-让你的生活更美好](#e838a1ecdcf3d068547dd0d7b5c446c6)
            - [(6) 原文](#7163f7c92c9443e17f3f76cc16c2d796)
            - [(5) 译文](#fc62c644a450f3e977af313edd5ab124)
        - [Tools&&Plugins&&Scripts介绍](#3d3bc775abd7f254ff9ff90d669017c9)
            - [(51) Uncategorised](#cd66794473ea90aa6241af01718c3a7d)
            - [(3) Loader&&Processor](#43a4761e949187bf737e378819752c3b)
            - [(1) Interoperability with Other Tools](#c7483f3b20296ac68084a8c866230e15)
        - [(10) Tips&&Tricks](#a4bd25d3dc2f0be840e39674be67d66b)
        - [(125) Uncategorised](#4187e477ebc45d1721f045da62dbf4e8)
        - [(5) 翻译-TheIDAProBook](#ea11818602eb33e8b165eb18d3710965)
        - [(2) 翻译-ReverseEngineeringCodeWithIDAPro](#ec5f7b9ed06500c537aa25851a3f2d3a)
        - [(5) 系列Articles-使用IDA逆向C代码](#8433dd5df40aaf302b179b1fda1d2863)
        - [逆向实战](#d8e48eb05d72db3ac1e050d8ebc546e1)
            - [(11) Uncategorised](#374c6336120363a5c9d9a27d7d669bf3)
            - [(15) Malware分析](#0b3e1936ad7c4ccc10642e994c653159)
            - [(2) Vulnerabilities分析&&挖掘](#03465020d4140590326ae12c9601ecfd)
        - [(27) Recently Added](#37634a992983db427ce41b37dd9a98c2)
        - [(4) IDA本身](#2120fe5420607a363ae87f5d2fed459f)
        - [(1) Microcode](#e9ce398c2c43170e69c95fe9ad8d22fc)
        - [(1) IDA对抗](#9c0ec56f402a2b9938417f6ecbaeaa72)
- [Ghidra](#319821036a3319d3ade5805f384d3165)
    - [Plugins&&Scripts](#fa45b20f6f043af1549b92f7c46c9719)
        - [(12) Recently Added](#ce70b8d45be0a3d29705763564623aca)
        - [特定分析目标](#69dc4207618a2977fe8cd919e7903fa5)
            - [(4) Uncategorised](#da5d2b05da13f8e65aa26d6a1c95a8d0)
            - [(18) Loader&&Processor](#058bb9893323f337ad1773725d61f689)
            - [(2) Xbox](#51a2c42c6d339be24badf52acb995455)
        - [Interoperability with Other Tools](#99e3b02da53f1dbe59e0e277ef894687)
            - [(2) Radare2](#e1cc732d1388084530b066c26e24887b)
            - [Uncategorised](#5923db547e1f04f708272543021701d2)
            - [(5) IDA](#d832a81018c188bf585fcefa3ae23062)
            - [(1) DBI](#60e86981b2c98f727587e7de927e0519)
            - [(1) Debugging器](#e81053b03a859e8ac72f7fe79e80341a)
        - [(1) Appearance&&Themes](#cccbd06c6b9b03152d07a4072152ae27)
        - [(4) Ghidra](#2ae406afda6602c8f02d73678b2ff040)
        - [Scripts编写](#45910c8ea12447df9cdde2bea425f23f)
            - [(1) Other](#c12ccb8e11ba94184f8f24767eb64212)
            - [(1) 编程语言](#b24e162720cffd2d2456488571c1a136)
    - [Articles and Videos](#273df546f1145fbed92bb554a327b87a)
        - [(30) Recently Added](#ce49901b4914f3688ef54585c8f9df1a)
        - [(4) GhidraVulnerabilities](#b7fb955b670df2babc67e5942297444d)
        - [实战分析](#dd0d49a5e6bd34b372d9bbf4475e8024)
            - [(3) Vulnerabilities分析&&挖掘](#375c75af4fa078633150415eec7c867d)
            - [(9) Uncategorised](#f0ab053d7a282ab520c3a327fc91ba2e)
            - [(9) Malware](#4e3f53845efe99da287b2cea1bdda97c)
        - [Other](#92f60c044ed13b3ffde631794edd2756)
        - [Tips&&Tricks](#4bfa6dcf708b3f896870c9d3638c0cde)
        - [(5) Tools&&Plugins&&Scripts](#0d086cf7980f65da8f7112b901fecdc1)
        - [(15) Recently Added1](#8962bde3fbfb1d1130879684bdf3eed0)
- [x64dbg](#b1a6c053e88e86ce01bbd78c54c63a7c)
    - [Plugins&&Scripts](#b4a856db286f9f29b5a32d477d6b3f3a)
        - [(63) Recently Added](#da5688c7823802e734c39b539aa39df7)
        - [(1) x64dbg](#353ea40f2346191ecb828210a685f9db)
    - [(21) Articles and Videos](#22894d6f2255dc43d82dd46bdbc20ba1)
- [OllyDbg](#37e37e665eac00de3f55a13dcfd47320)
    - [Plugins&&Scripts](#7834e399e48e6c64255a1a0fdb6b88f5)
        - [(13) Recently Added](#92c44f98ff5ad8f8b0f5e10367262f9b)
    - [(122) Articles and Videos](#8dd3e63c4e1811973288ea8f1581dfdb)
- [WinDBG](#0a506e6fb2252626add375f884c9095e)
    - [Plugins&&Scripts](#37eea2c2e8885eb435987ccf3f467122)
        - [(67) Recently Added](#2ef75ae7852daa9862b2217dca252cc3)
    - [(155) Articles and Videos](#6d8bac8bfb5cda00c7e3bd38d64cbce3)
- [Radare2](#86cb7d8f548ca76534b5828cb5b0abce)
    - [Plugins&&Scripts](#0e08f9478ed8388319f267e75e2ef1eb)
        - [(76) Recently Added](#6922457cb0d4b6b87a34caf39aa31dfe)
        - [(1) Radare2](#ec3f0b5c2cf36004c4dd3d162b94b91a)
        - [Interoperability with Other Tools](#1a6652a1cb16324ab56589cb1333576f)
            - [(4) Uncategorised](#dfe53924d678f9225fc5ece9413b890f)
            - [(3) IDA](#1cfe869820ecc97204a350a3361b31a7)
        - [GUI](#f7778a5392b90b03a3e23ef94a0cc3c6)
            - [(4) GUI](#8f151d828263d3bc038f75f8d6418758)
            - [(5) Cutter](#df45c3c60bd074e21d650266aa85c241)
    - [Articles and Videos](#95fdc7692c4eda74f7ca590bb3f12982)
        - [(167) Uncategorised](#a4debf888d112b91e56c90136f513ec0)
        - [(5) Cutter](#d86e19280510aee0bcf2599f139cfbf7)
- [Cuckoo](#0ae4ddb81ff126789a7e08b0768bd693)
    - [Tools](#5830a8f8fb3af1a336053d84dd7330a1)
        - [(40) Recently Added](#f2b5c44c2107db2cec6c60477c6aa1d0)
    - [(62) Articles and Videos](#ec0a441206d9a2fe1625dce0a679d466)
- [BinaryNinja](#afb7259851922935643857c543c4b0c2)
    - [Plugins&&Scripts](#3034389f5aaa9d7b0be6fa7322340aab)
        - [(58) Recently Added](#a750ac8156aa0ff337a8639649415ef1)
        - [Interoperability with Other Tools](#bba1171ac550958141dfcb0027716f41)
            - [(2) Uncategorised](#c2f94ad158b96c928ee51461823aa953)
            - [(3) IDA](#713fb1c0075947956651cc21a833e074)
    - [(12) Articles and Videos](#2d24dd6f0c01a084e88580ad22ce5b3c)
- [DBI](#7ab3a7005d6aa699562b3a0a0c6f2cff)
    - [DynamoRIO](#c8cdb0e30f24e9b7394fcd5681f2e419)
        - [Tools](#6c4841dd91cb173093ea2c8d0b557e71)
            - [(8) Recently Added](#ff0abe26a37095f6575195950e0b7f94)
            - [(2) DynamoRIO](#3a577a5b4730a1b5b3b325269509bb0a)
            - [(3) Interoperability with Other Tools](#928642a55eff34b6b52622c6862addd2)
        - [(15) Articles and Videos](#9479ce9f475e4b9faa4497924a2e40fc)
    - [IntelPin](#7b8a493ca344f41887792fcc008573e7)
        - [Tools](#fe5a6d7f16890542c9e60857706edfde)
            - [(18) Recently Added](#78a2edf9aa41eb321436cb150ea70a54)
            - [Interoperability with Other Tools](#e6a829abd8bbc5ad2e5885396e3eec04)
                - [(8) Uncategorised](#e129288dfadc2ab0890667109f93a76d)
        - [Articles and Videos](#226190bea6ceb98ee5e2b939a6515fac)
    - [Frida](#f24f1235fd45a1aa8d280eff1f03af7e)
        - [Tools](#a5336a0f9e8e55111bda45c8d74924c1)
            - [(100) Recently Added](#54836a155de0c15b56f43634cd9cfecf)
            - [Interoperability with Other Tools](#74fa0c52c6104fd5656c93c08fd1ba86)
                - [(1) Uncategorised](#00a86c65a84e58397ee54e85ed57feaf)
                - [(3) IDA](#d628ec92c9eea0c4b016831e1f6852b3)
                - [(2) BinaryNinja](#f9008a00e2bbc7535c88602aa79c8fd8)
                - [(2) Radare2](#ac053c4da818ca587d57711d2ff66278)
            - [(1) Frida](#6d3c24e43835420063f9ca50ba805f15)
        - [(92) Articles and Videos](#a1a7e3dd7091b47384c75dba8f279caf)
    - [QBDI](#b2fca17481b109a9b3b0bc290a1a1381)
        - [(1) Tools](#e72b766bcd3b868c438a372bc365221e)
        - [(6) Articles and Videos](#2cf79f93baf02a24d95d227a0a3049d8)
    - [Other](#5a9974bfcf7cdf9b05fe7a7dc5272213)
        - [(4) Tools](#104bc99e36692f133ba70475ebc8825f)
        - [(1) Articles and Videos](#8f1b9c5c2737493524809684b934d49a)
- [Other](#d3690e0b19c784e104273fe4d64b2362)
    - [Articles-Recently Added](#9162e3507d24e58e9e944dd3f6066c0e)
    - [(284) Tools-Recently Added](#1d9dec1320a5d774dc8e0e7604edfcd3)
    - [(3) Tools-Other](#bc2b78af683e7ba983205592de8c3a7a)
    - [angr](#4fe330ae3e5ce0b39735b1bfea4528af)
        - [(27) Tools](#1ede5ade1e55074922eb4b6386f5ca65)
        - [(4) Articles](#042ef9d415350eeb97ac2539c2fa530e)
    - [Debug&&Debugging](#324874bb7c3ead94eae6f1fa1af4fb68)
        - [(116) Tools](#d22bd989b2fdaeda14b64343b472dfb6)
        - [Articles](#136c41f2d05739a74c6ec7d8a84df1e8)
    - [BAP](#9f8d3f2c9e46fbe6c25c22285c8226df)
        - [(26) Tools](#f10e9553770db6f98e8619dcd74166ef)
        - [Articles](#e111826dde8fa44c575ce979fd54755d)
    - [BinNavi](#2683839f170250822916534f1db22eeb)
        - [(3) Tools](#2e4980c95871eae4ec0e76c42cc5c32f)
        - [(5) Articles](#ff4dc5c746cb398d41fb69a4f8dfd497)
    - [Decompiler&&Decompilers](#0971f295b0f67dc31b7aa45caf3f588f)
        - [(73) Tools](#e67c18b4b682ceb6716388522f9a1417)
        - [Articles](#a748b79105651a8fd8ae856a7dc2b1de)
    - [Disassemble&&反汇编](#2df6d3d07e56381e1101097d013746a0)
        - [(30) Tools](#59f472c7575951c57d298aef21e7d73c)
        - [Articles](#a6eb5a22deb33fc1919eaa073aa29ab5)
    - [GDB](#975d9f08e2771fccc112d9670eae1ed1)
        - [(80) Tools](#5f4381b0a90d88dd2296c2936f7e7f70)
        - [(102) Articles](#37b17362d72f9c8793973bc4704893a2)
    - [Monitor&&监控&&Trace&&追踪](#70e64e3147675c9bcd48d4f475396e7f)
        - [(29) Tools](#cd76e644d8ddbd385939bb17fceab205)
- [TODO](#35f8efcff18d0449029e9d3157ac0899)


# <a id="35f8efcff18d0449029e9d3157ac0899"></a>TODO


- Classify the tools in greater detail
- Add detailed Chinese descriptions of the tools, including their implementation principles and usage.
- Add repositories hosted outside GitHub
- Add more articles
- Revise descriptions of articles that have already been added


# <a id="08e59e476824a221f6e4a69c0bba7d63"></a>IDA


***


## <a id="f11ab1ff46aa300cc3e86528b8a98ad7"></a>Plugins&&Scripts


- Primarily covers open-source tools hosted on GitHub


### <a id="c39dbae63d6a3302c4df8073b4d1cdc8"></a>Recently Added




### <a id="c39a6d8598dde6abfeef43faf931beb5"></a>Uncategorised


- [**1058** stars][17d] [Py] [fireeye/flare-ida](https://github.com/fireeye/flare-ida) — Multiple tools.
  - [StackStrings](https://github.com/fireeye/flare-ida/blob/master/plugins/stackstrings_plugin.py): Automatically recover manually constructed strings.
    - [Struct Typer](https://github.com/fireeye/flare-ida/blob/master/plugins/struct_typer_plugin.py) implements the struct typing described [here](https://www.mandiant.com/blog/applying-function-types-structure-fields-ida/)
    - [ApplyCalleeType](https://github.com/fireeye/flare-ida/blob/master/python/flare/apply_callee_type.py) specify or choose a function type for indirect calls as described [here](https://www.fireeye.com/blog/threat-research/2015/04/flare_ida_pro_script.html)
  - [argtracker](https://github.com/fireeye/flare-ida/blob/master/python/flare/argtracker.py): Identifies the static arguments used by a function.
  - [idb2pat](https://github.com/fireeye/flare-ida/blob/master/python/flare/idb2pat.py): Generates FLIRT signatures.
  - [objc2_analyzer](https://github.com/fireeye/flare-ida/blob/master/python/flare/objc2_analyzer.py): Creates cross-references between selector references and their implementations in the Objective-C runtime-related parts of a target Mach-O executable.
  - [MSDN Annotations](https://github.com/fireeye/flare-ida/tree/master/python/flare/IDB_MSDN_Annotator): Extracts MSDN information from XML files and adds it to the IDB database.
  - [ironstrings](https://github.com/fireeye/flare-ida/tree/master/python/flare/ironstrings): Uses code emulation through flare-emu to recover constructed strings.
  - [Shellcode Hashes](https://github.com/fireeye/flare-ida/tree/master/shellcode_hashes): Generates a hash database.
- [**737** stars][7m] [Py] [devttys0/ida](https://github.com/devttys0/ida): A collection of IDA plugins, scripts and modules.
  - [wpsearch](https://github.com/devttys0/ida/blob/master/scripts/wpsearch.py): Finds immediate values commonly used in MIPS WPS checksum implementations.
  - [md5hash](https://github.com/devttys0/ida/tree/master/modules/md5hash): A pure-Python implementation of MD5 hashing (IDA's `hashlib` has issues).
  - [alleycat](https://github.com/devttys0/ida/tree/master/plugins/alleycat): Finds paths to code blocks inside a specified function, finds paths between two or more functions, generates interactive call graphs and supports programmability.
  - [codatify](https://github.com/devttys0/ida/tree/master/plugins/codatify): Defines ASCII strings, functions and code missed by IDA's automated analysis. Converts all undefined bytes in the data segment into DWORDs so that IDA can recognise functions and jump-table pointers.
  - [fluorescence](https://github.com/devttys0/ida/tree/master/plugins/fluorescence): Highlights function-call instructions.
  - [leafblower](https://github.com/devttys0/ida/tree/master/plugins/leafblower): Identifies common POSIX functions such as `printf`, `sprintf`, `memcmp` and `strcpy`.
  - [localxrefs](https://github.com/devttys0/ida/tree/master/plugins/localxrefs): Finds all references to any selected text within the current function.
  - [mipslocalvars](https://github.com/devttys0/ida/tree/master/plugins/mipslocalvars): Names stack variables used only for storing registers, simplifying stack-data analysis (MIPS).
  - [mipsrop](https://github.com/devttys0/ida/tree/master/plugins/mipsrop): Searches MIPS executable code for ROP and common ROP gadgets.
  - [rizzo](https://github.com/devttys0/ida/tree/master/plugins/rizzo): Identifies and renames functions across two or more IDB files using function signatures, references to unique strings/constants, fuzzy signatures and call graphs.
- [**318** stars][2m] [C] [ohjeongwook/darungrim](https://github.com/ohjeongwook/darungrim): A software patch-analysis tool.
  - [IDA Plugin](https://github.com/ohjeongwook/darungrim/tree/master/Src/IDAPlugin)
    - [DGEngine](https://github.com/ohjeongwook/darungrim/tree/master/Src/DGEngine) 
- [**277** stars][4m] [Py] [jpcertcc/aa-tools](https://github.com/jpcertcc/aa-tools): A collection of scripts.
  - [apt17scan.py](https://github.com/jpcertcc/aa-tools/blob/master/apt17scan.py): Volatility plugin that detects malware related to APT17 and extracts its configuration.
  - [emdivi_postdata_decoder](https://github.com/jpcertcc/aa-tools/blob/master/emdivi_postdata_decoder.py): Decodes Emdivi POST data.
  - [emdivi_string_decryptor](https://github.com/jpcertcc/aa-tools/blob/master/emdivi_string_decryptor.py): An IDAPython script that decrypts strings inside Emdivi.
    - [citadel_decryptor](https://github.com/jpcertcc/aa-tools/tree/master/citadel_decryptor) Data decryption tool for Citadel
    - [adwind_string_decoder](https://github.com/jpcertcc/aa-tools/blob/master/adwind_string_decoder.py) Python script for decoding strings inside Adwind
    - [redleavesscan](https://github.com/jpcertcc/aa-tools/blob/master/redleavesscan.py) Volatility plugin for detecting RedLeaves and extracting its config
    - [datper_splunk](https://github.com/jpcertcc/aa-tools/blob/master/datper_splunk.py) Python script for detects Datper communication and adds result field to Splunk index
    - [datper_elk](https://github.com/jpcertcc/aa-tools/blob/master/datper_elk.py) Python script for detects Datper communication and adds result field to Elasticsearch index
    - [tscookie_decode](https://github.com/jpcertcc/aa-tools/blob/master/tscookie_decode.py) Python script for decrypting and parsing TSCookie configure data
    - [wellmess_cookie_decode](https://github.com/jpcertcc/aa-tools/blob/master/wellmess_cookie_decode.py) Python script for decoding WellMess's cookie data (support Python2)
    - [cobaltstrikescan](https://github.com/jpcertcc/aa-tools/blob/master/cobaltstrikescan.py) Volatility plugin for detecting Cobalt Strike Beacon and extracting its config
    - [tscookie_data_decode](https://github.com/jpcertcc/aa-tools/blob/master/tscookie_data_decode.py) Python script for decrypting and parsing TSCookie configure data


### <a id="fb4f0c061a72fc38656691746e7c45ce"></a>Structures&&Classes的Detection&&Creation&&Recovery


#### <a id="fa5ede9a4f58d4efd98585d3158be4fb"></a>Uncategorised


- [**931**stars][25d] [OCaml] [airbus-seclab/bincat](https://github.com/airbus-seclab/bincat) 二进制代码静态分析工具。值分析（寄存器、内存）、污点分析、类型重建和传播（propagation）、前向/后向分析
    - 重复区段: [IDA->插件->污点分析](#34ac84853604a7741c61670f2a075d20) |
- [**664** stars][27d] [Py] [igogo-x86/hexrayspytools](https://github.com/igogo-x86/hexrayspytools): A plugin for reconstructing structures and classes.


#### <a id="4900b1626f10791748b20630af6d6123"></a>C++Classes&&虚表


- [**607**stars][3m] [Py] [0xgalz/virtuailor](https://github.com/0xgalz/virtuailor) 利用IDA调试获取的信息，自动创建C++的虚表
    - 重复区段: [IDA->插件->调试->调试数据](#b31acf6c84a9506066d497af4e702bf5) |
        <details>
        <summary>View details</summary>


        ## 静态部分: 
        - 检测非直接调用
        - 利用条件断点, Hook非直接调用的值赋值过程
        
        ## 动态 部分
        - 创建虚表结构
        - 重命名函数和虚表地址
        - 给反汇编非直接调用添加结构偏移
        - 给非直接调用到虚表之间添加交叉引用
        
        ## 使用
        - File -> Script File -> Main.py(设置断点) -> IDA调试器执行
        </details>






### <a id="a7dac37cd93b8bb42c7d6aedccb751b3"></a>Collections


- [**1771**stars][10d] [onethawt/idaplugins-list](https://github.com/onethawt/idaplugins-list) IDA插件收集
- [**363**stars][9m] [fr0gger/awesome-ida-x64-olly-plugin](https://github.com/fr0gger/awesome-ida-x64-olly-plugin) IDA x64DBG OllyDBG 插件收集
    - 重复区段: [x64dbg->插件->新添加的](#da5688c7823802e734c39b539aa39df7) |


### <a id="fabf03b862a776bbd8bcc4574943a65a"></a>Appearance&&Themes


- [**723**stars][7m] [Py] [zyantific/idaskins](https://github.com/zyantific/idaskins) 皮肤插件


### <a id="a8f5db3ab4bc7bc3d6ca772b3b9b0b1e"></a>Firmware&&Embedded Devices


- [**5228**stars][2m] [Py] [refirmlabs/binwalk](https://github.com/ReFirmLabs/binwalk) 固件分析工具（命令行+IDA插件）
    - [IDA插件](https://github.com/ReFirmLabs/binwalk/tree/master/src/scripts) 
    - [binwalk](https://github.com/ReFirmLabs/binwalk/tree/master/src/binwalk) 
- [**492**stars][5m] [Py] [maddiestone/idapythonembeddedtoolkit](https://github.com/maddiestone/idapythonembeddedtoolkit) 自动分析嵌入式设备的固件


### <a id="02088f4884be6c9effb0f1e9a3795e58"></a>Signatures(FLIRT等)&&Comparison(Diff)&&Matching


#### <a id="cf04b98ea9da0056c055e2050da980c1"></a>Uncategorised


- [**421**stars][1m] [C] [mcgill-dmas/kam1n0-community](https://github.com/McGill-DMaS/Kam1n0-Community) 汇编代码管理与分析平台(独立工具+IDA插件)
    - 重复区段: [IDA->插件->作为辅助](#83de90385d03ac8ef27360bfcdc1ab48) |
    - [IDA插件](https://github.com/McGill-DMaS/Kam1n0-Community/tree/master2.x/kam1n0-clients/ida-plugin) 
    - [kam1n0](https://github.com/McGill-DMaS/Kam1n0-Community/tree/master2.x/kam1n0) 


#### <a id="19360afa4287236abe47166154bc1ece"></a>FLIRTSignatures


##### <a id="1c9d8dfef3c651480661f98418c49197"></a>FLIRTSignaturesCollections


- [**605**stars][2m] [Max] [maktm/flirtdb](https://github.com/Maktm/FLIRTDB) A community driven collection of IDA FLIRT signature files
- [**321**stars][5m] [push0ebp/sig-database](https://github.com/push0ebp/sig-database) IDA FLIRT Signature Database


##### <a id="a9a63d23d32c6c789ca4d2e146c9b6d0"></a>FLIRTSignatures生成






#### <a id="161e5a3437461dc8959cc923e6a18ef7"></a>Diff&&MatchTools


- [**1554** stars][13d] [Python] [joxeankoret/diaphora](https://github.com/joxeankoret/diaphora) — Program diffing.
- [**360** stars][1m] [Python] [checkpointsw/karta](https://github.com/checkpointsw/karta) — A source-code-assisted plugin for fast binary matching in IDA.
- [**332** stars][1y] [Python] [joxeankoret/pigaios](https://github.com/joxeankoret/pigaios) — A tool for matching and diffing source code directly against binaries.


#### <a id="46c9dfc585ae59fe5e6f7ddf542fb31a"></a>Yara


- [**449**stars][2m] [Py] [polymorf/findcrypt-yara](https://github.com/polymorf/findcrypt-yara) 使用Yara规则查找加密常量
    - 重复区段: [IDA->插件->加密解密](#06d2caabef97cf663bd29af2b1fe270c) |




### <a id="5e91b280aab7f242cbc37d64ddbff82f"></a>IDB操作


- [**316** stars][6m] [Python] [williballenthin/python-idb](https://github.com/williballenthin/python-idb) — Tool for parsing and analysing IDB files.


### <a id="206ca17fc949b8e0ae62731d9bb244cb"></a>Collaborative Reverse Engineering&&Multiple Users Working on the Same IDB File


- [**508** stars][11m] [Python] [idarlingteam/idarling](https://github.com/IDArlingTeam/IDArling) — Collaborative plugin.
- [**258** stars][1y] [C++] [dga-mi-ssi/yaco](https://github.com/dga-mi-ssi/yaco) — Uses Git version control to synchronise modifications made by multiple people to the same binary file.


### <a id="f7d311685152ac005cfce5753c006e4b"></a>Synchronisation with the Debugger&&Communication&&Interaction


- [**471**stars][13d] [C] [bootleg/ret-sync](https://github.com/bootleg/ret-sync) 在反汇编工具和调试器之间同步调试会话
    - 重复区段: [x64dbg->插件->新添加的](#da5688c7823802e734c39b539aa39df7) |
    - [GDB插件](https://github.com/bootleg/ret-sync/tree/master/ext_gdb) 
    - [Ghidra插件](https://github.com/bootleg/ret-sync/tree/master/ext_ghidra) 
    - [IDA插件](https://github.com/bootleg/ret-sync/tree/master/ext_ida) 
    - [LLDB](https://github.com/bootleg/ret-sync/tree/master/ext_lldb) 
    - [OD](https://github.com/bootleg/ret-sync/tree/master/ext_olly1) 
    - [OD2](https://github.com/bootleg/ret-sync/tree/master/ext_olly2) 
    - [WinDgb](https://github.com/bootleg/ret-sync/tree/master/ext_windbg/sync) 
    - [x64dbg](https://github.com/bootleg/ret-sync/tree/master/ext_x64dbg) 
- [**292** stars][11m] [C] [a1ext/labeless](https://github.com/a1ext/labeless) — Seamlessly synchronises labels, comments, and other information between IDA and debuggers.
    - [IDA plugin](https://github.com/a1ext/labeless/tree/master/labeless_ida)
    - [OD](https://github.com/a1ext/labeless/tree/master/labeless_olly) 
    - [OD2](https://github.com/a1ext/labeless/tree/master/labeless_olly2) 
    - [x64dbg](https://github.com/a1ext/labeless/tree/master/labeless_x64dbg) 


### <a id="6fb7e41786c49cc3811305c520dfe9a1"></a>Import/Export&Interoperability with Other Tools


#### <a id="8ad723b704b044e664970b11ce103c09"></a>Uncategorised




#### <a id="c7066b0c388cd447e980bf0eb38f39ab"></a>Ghidra


- [**299**stars][4m] [Py] [cisco-talos/ghida](https://github.com/cisco-talos/ghida) 在IDA中集成Ghidra反编译器
    - 重复区段: [Ghidra->插件->与其他工具交互->IDA](#d832a81018c188bf585fcefa3ae23062) |
- [**238**stars][9m] [Py] [daenerys-sre/source](https://github.com/daenerys-sre/source) 使IDA和Ghidra脚本通用, 无需修改
    - 重复区段: [Ghidra->插件->与其他工具交互->IDA](#d832a81018c188bf585fcefa3ae23062) |


#### <a id="11139e7d6db4c1cef22718868f29fe12"></a>BinNavi


- [**382** stars][26d] [C++] [google/binexport](https://github.com/google/binexport) — Exports disassembly into a PostgreSQL database in Protocol Buffer format so it can be imported and used in BinNavi.
    - 重复区段: [其他->BinNavi->工具](#2e4980c95871eae4ec0e76c42cc5c32f) |


#### <a id="d1ff64bee76f6749aef6100d72bfbe3a"></a>BinaryNinja




#### <a id="21ed198ae5a974877d7a635a4b039ae3"></a>Radare2




#### <a id="a1cf7f7f849b4ca2101bd31449c2a0fd"></a>Frida




#### <a id="dd0332da5a1482df414658250e6357f8"></a>IntelPin






### <a id="004c199e1dbf71769fbafcd8e58d1ead"></a>Target-Specific Analysis


#### <a id="5578c56ca09a5804433524047840980e"></a>Uncategorised




#### <a id="cb59d84840e41330a7b5e275c0b81725"></a>Loader&Processor


- [**205** stars][1y] [Python] [fireeye/idawasm](https://github.com/fireeye/idawasm) — Loader and parser for WebAssembly.


#### <a id="1b17ac638aaa09852966306760fda46b"></a>GoLang


- [**376** stars][9m] [Python] [sibears/idagolanghelper](https://github.com/sibears/idagolanghelper) — Parses GoLang type information from Go-compiled binaries.
- [**297** stars][2m] [Python] [strazzere/golang_loader_assist](https://github.com/strazzere/golang_loader_assist) — Assists with Go reverse engineering.


#### <a id="4c158ccc5aee04383755851844fdd137"></a>WindowsDrivers


- [**306** stars][1y] [Python] [fsecurelabs/win_driver_plugin](https://github.com/FSecureLABS/win_driver_plugin) — A tool that helps when working with Windows IOCTL codes or reverse-engineering Windows drivers.
- [**218** stars][1y] [Python] [nccgroup/driverbuddy](https://github.com/nccgroup/driverbuddy) — Assists with reverse-engineering Windows kernel drivers.


#### <a id="315b1b8b41c67ae91b841fce1d4190b5"></a>PS3&&PS4




#### <a id="f5e51763bb09d8fd47ee575a98bedca1"></a>PDB




#### <a id="7d0681efba2cf3adaba2780330cd923a"></a>Flash&&SWF




#### <a id="841d605300beba45c3be131988514a03"></a>Specific Malware Families




#### <a id="ad44205b2d943cfa2fa805b2643f4595"></a>CTF






### <a id="ad68872e14f70db53e8d9519213ec039"></a>IDAPython本身


#### <a id="2299bc16945c25652e5ad4d48eae8eca"></a>Uncategorised


- [**720** stars][15d] [Python] [idapython/src](https://github.com/idapython/src) — IDAPython source code.
- [**373** stars][3m] [Python] [tmr232/sark](https://github.com/tmr232/sark) — A higher-level abstraction for IDAPython.


#### <a id="c42137cf98d6042372b1fd43c3635135"></a>清单


- [**258** stars][28d] [Python] [inforion/idapython-cheatsheet](https://github.com/inforion/idapython-cheatsheet) — Scripts and cheat sheets for IDAPython.




### <a id="846eebe73bef533041d74fc711cafb43"></a>Instruction Reference&Documentation


- [**497** stars][1y] [PLpgSQL] [nologic/idaref](https://github.com/nologic/idaref) — Instruction reference plugin.
- [**449**stars][4m] [C++] [alexhude/friend](https://github.com/alexhude/friend) 反汇编显示增强, 文档增强插件
    - 重复区段: [IDA->插件->效率->其他](#c5b120e1779b928d860ad64ff8d23264) |


### <a id="c08ebe5b7eec9fc96f8eff36d1d5cc7d"></a>Script-Writing Helpers


#### <a id="45fd7cfce682c7c25b4f3fbc4c461ba2"></a>Uncategorised


- [**282** stars][2m] [Python] [fireeye/flare-emu](https://github.com/fireeye/flare-emu) — Simplifies the development of emulation scripts by integrating the Unicorn Engine.
    - 重复区段: [IDA->插件->模拟器集成](#b38dab81610be087bd5bc7785269b8cc) |


#### <a id="1a56a5b726aaa55ec5b7a5087d6c8968"></a>Qt




#### <a id="1721c09501e4defed9eaa78b8d708361"></a>Console&&Window Interface


- [**269** stars][1m] [Python] [eset/ipyida](https://github.com/eset/ipyida) — Integrates an IPython console.


#### <a id="227fbff77e3a13569ef7b007344d5d2e"></a>Plugins模板




#### <a id="8b19bb8cf9a5bc9e6ab045f3b4fabf6a"></a>Other语言






### <a id="dc35a2b02780cdaa8effcae2b6ce623e"></a>Legacy




### <a id="e3e7030efc3b4de3b5b8750b7d93e6dd"></a>Debugging&&Dynamic Execution&Dynamic Data


#### <a id="2944dda5289f494e5e636089db0d6a6a"></a>Uncategorised


- [**395** stars][1y] [C++] [cseagle/sk3wldbg](https://github.com/cseagle/sk3wldbg) — A debugging plugin that uses the Unicorn Engine as its backend.
    - 重复区段: [IDA->插件->模拟器集成](#b38dab81610be087bd5bc7785269b8cc) |


#### <a id="0fbd352f703b507853c610a664f024d1"></a>DBI数据


- [**943**stars][1y] [Py] [gaasedelen/lighthouse](https://github.com/gaasedelen/lighthouse) 从DBI中收集代码覆盖情况，在IDA/Binja中映射、浏览、查看
    - 重复区段: [DBI->IntelPin->工具->与其他工具交互->未分类](#e129288dfadc2ab0890667109f93a76d) |[DBI->Frida->工具->与其他工具交互->IDA](#d628ec92c9eea0c4b016831e1f6852b3) |[DBI->Frida->工具->与其他工具交互->BinaryNinja](#f9008a00e2bbc7535c88602aa79c8fd8) |
    - [coverage-frida](https://github.com/gaasedelen/lighthouse/blob/master/coverage/frida/README.md) 使用Frida收集信息
    - [coverage-pin](https://github.com/gaasedelen/lighthouse/blob/master/coverage/pin/README.md) 使用Pin收集覆盖信息
    - [插件](https://github.com/gaasedelen/lighthouse/blob/master/plugin/lighthouse_plugin.py) 支持IDA和BinNinja


#### <a id="b31acf6c84a9506066d497af4e702bf5"></a>Debugging数据


- [**607**stars][3m] [Py] [0xgalz/virtuailor](https://github.com/0xgalz/virtuailor) 利用IDA调试获取的信息，自动创建C++的虚表
    - 重复区段: [IDA->插件->结构体->C++类](#4900b1626f10791748b20630af6d6123) |
        <details>
        <summary>View details</summary>


        ## 静态部分: 
        - 检测非直接调用
        - 利用条件断点, Hook非直接调用的值赋值过程
        
        ## 动态 部分
        - 创建虚表结构
        - 重命名函数和虚表地址
        - 给反汇编非直接调用添加结构偏移
        - 给非直接调用到虚表之间添加交叉引用
        
        ## 使用
        - File -> Script File -> Main.py(设置断点) -> IDA调试器执行
        </details>


- [**386** stars][5m] [Python] [ynvb/die](https://github.com/ynvb/die) — Collects runtime information using the IDA debugger to assist with static analysis.




### <a id="d2166f4dac4eab7fadfe0fd06467fbc9"></a>Decompilers&&AST


- [**1672**stars][7m] [C++] [yegord/snowman](https://github.com/yegord/snowman) Snowman反编译器，支持x86, AMD64, ARM。有独立的GUI工具、命令行工具、IDA/Radare2/x64dbg插件，也可以作为库使用
    - 重复区段: [x64dbg->插件->新添加的](#da5688c7823802e734c39b539aa39df7) |
    - [IDA插件](https://github.com/yegord/snowman/tree/master/src/ida-plugin) 
    - [snowman](https://github.com/yegord/snowman/tree/master/src/snowman) QT界面
    - [nocode](https://github.com/yegord/snowman/tree/master/src/nocode) 命令行工具
    - [nc](https://github.com/yegord/snowman/tree/master/src/nc) 核心代码，可作为库使用
- [**418** stars][3m] [C++] [avast/retdec-idaplugin](https://github.com/avast/retdec-idaplugin) — IDA plugin for RetDec.
- [**235**stars][7m] [Py] [patois/dsync](https://github.com/patois/dsync) 反汇编和反编译窗口同步插件
    - 重复区段: [IDA->插件->效率->其他](#c5b120e1779b928d860ad64ff8d23264) |


### <a id="7199e8787c0de5b428f50263f965fda7"></a>Deobfuscation


- [**1365**stars][3m] [Py] [fireeye/flare-floss](https://github.com/fireeye/flare-floss) 自动从恶意代码中提取反混淆后的字符串
    - 重复区段: [IDA->插件->字符串](#9dcc6c7dd980bec1f92d0cc9a2209a24) |
    - [floss](https://github.com/fireeye/flare-floss/tree/master/floss) 
    - [IDA插件](https://github.com/fireeye/flare-floss/blob/master/scripts/idaplugin.py) 
- [**304** stars][4m] [C++] [rolfrolles/hexraysdeob](https://github.com/rolfrolles/hexraysdeob) — Uses the Hex-Rays microcode API to break compiler-level obfuscation.
    - 重复区段: [IDA->插件->Microcode](#7a2977533ccdac70ee6e58a7853b756b) |


### <a id="fcf75a0881617d1f684bc8b359c684d7"></a>Efficiency&&Navigation&&Quick Access&&Graphs&&Images&&Visualisation 


#### <a id="c5b120e1779b928d860ad64ff8d23264"></a>Other


- [**449**stars][4m] [C++] [alexhude/friend](https://github.com/alexhude/friend) 反汇编显示增强, 文档增强插件
    - 重复区段: [IDA->插件->指令参考](#846eebe73bef533041d74fc711cafb43) |
- [**372**stars][3m] [Py] [l4ys/lazyida](https://github.com/l4ys/lazyida) 若干快速访问功能, 扫描字符串格式化漏洞
    - 重复区段: [IDA->插件->字符串](#9dcc6c7dd980bec1f92d0cc9a2209a24) |[IDA->插件->漏洞->未分类](#385d6777d0747e79cccab0a19fa90e7e) |
        <details>
        <summary>View details</summary>


        ### 功能
        - 快速移除函数返回类型
        - 数据格式(format)快速转换
        - 扫描字符串格式化漏洞
        - 双击跳转vtable函数
        - 快捷键: w/c/v
        </details>


- [**329** stars][4m] [Python] [pfalcon/scratchabit](https://github.com/pfalcon/scratchabit) — Interactive disassembly tool with a plugin API compatible with IDAPython.
- [**235**stars][7m] [Py] [patois/dsync](https://github.com/patois/dsync) 反汇编和反编译窗口同步插件
    - 重复区段: [IDA->插件->反编译器](#d2166f4dac4eab7fadfe0fd06467fbc9) |


#### <a id="03fac5b3abdbd56974894a261ce4e25f"></a>Display Enhancements


- [**208** stars][1m] [Python] [patois/idacyber](https://github.com/patois/idacyber) — Interactive data-visualisation plugin.


#### <a id="3b1dba00630ce81cba525eea8fcdae08"></a>Graphs&&Images


- [**2569** stars][6m] [Java] [google/binnavi](https://github.com/google/binnavi) — Binary analysis IDE for exploring, navigating, editing, and commenting on control-flow graphs and call graphs generated from disassembly. The IDA plugin is used to export disassembly.


#### <a id="8f9468e9ab26128567f4be87ead108d7"></a>Search






### <a id="66052f824f5054aa0f70785a2389a478"></a>Android


- [**246**stars][28d] [C++] [strazzere/android-scripts](https://github.com/strazzere/android-scripts) Android逆向脚本收集
    - 重复区段: [Android->工具->ReverseEngineering](#6d2b758b3269bac7d69a2d2c8b45194c) |


### <a id="2adc0044b2703fb010b3bf73b1f1ea4a"></a>Apple&&macOS&&iXxx&&Objective-C&&SWift&&Mach-O


#### <a id="8530752bacfb388f3726555dc121cb1a"></a>Uncategorised




#### <a id="82d0fa2d6934ce29794a651513934384"></a>Kernel缓存




#### <a id="d249a8d09a3f25d75bb7ba8b32bd9ec5"></a>Mach-O




#### <a id="1c698e298f6112a86c12881fbd8173c7"></a>Swift






### <a id="e5e403123c70ddae7bd904d3a3005dbb"></a>ELF




### <a id="7a2977533ccdac70ee6e58a7853b756b"></a>Microcode


- [**304** stars][4m] [C++] [rolfrolles/hexraysdeob](https://github.com/rolfrolles/hexraysdeob) — Uses the Hex-Rays microcode API to break compiler-level obfuscation.
    - 重复区段: [IDA->插件->反混淆](#7199e8787c0de5b428f50263f965fda7) |


### <a id="b38dab81610be087bd5bc7785269b8cc"></a>Emulators集成


- [**504**stars][20d] [Py] [alexhude/uemu](https://github.com/alexhude/uemu) 基于Unicorn的模拟器插件
- [**395** stars][1y] [C++] [cseagle/sk3wldbg](https://github.com/cseagle/sk3wldbg) — A debugging plugin that uses the Unicorn Engine as its backend.
    - 重复区段: [IDA->插件->调试->未分类](#2944dda5289f494e5e636089db0d6a6a) |
- [**282** stars][2m] [Python] [fireeye/flare-emu](https://github.com/fireeye/flare-emu) — Simplifies the development of emulation scripts by integrating the Unicorn Engine.
    - 重复区段: [IDA->插件->辅助脚本编写->未分类](#45fd7cfce682c7c25b4f3fbc4c461ba2) |


### <a id="83de90385d03ac8ef27360bfcdc1ab48"></a>作为辅助&&构成Other的一环


- [**1542**stars][28d] [Py] [lifting-bits/mcsema](https://github.com/lifting-bits/mcsema) 将x86, amd64, aarch64二进制文件转换成LLVM字节码
    - [IDA7插件](https://github.com/lifting-bits/mcsema/tree/master/tools/mcsema_disass/ida7) 用于反汇编二进制文件并生成控制流程图
    - [IDA插件](https://github.com/lifting-bits/mcsema/tree/master/tools/mcsema_disass/ida) 用于反汇编二进制文件并生成控制流程图
    - [Binja插件](https://github.com/lifting-bits/mcsema/tree/master/tools/mcsema_disass/binja) 用于反汇编二进制文件并生成控制流程图
    - [mcsema](https://github.com/lifting-bits/mcsema/tree/master/mcsema) 
- [**421**stars][1m] [C] [mcgill-dmas/kam1n0-community](https://github.com/McGill-DMaS/Kam1n0-Community) 汇编代码管理与分析平台(独立工具+IDA插件)
    - 重复区段: [IDA->插件->签名(FLIRT等)->未分类](#cf04b98ea9da0056c055e2050da980c1) |
    - [IDA插件](https://github.com/McGill-DMaS/Kam1n0-Community/tree/master2.x/kam1n0-clients/ida-plugin) 
    - [kam1n0](https://github.com/McGill-DMaS/Kam1n0-Community/tree/master2.x/kam1n0) 


### <a id="1ded622dca60b67288a591351de16f8b"></a>Vulnerabilities


#### <a id="385d6777d0747e79cccab0a19fa90e7e"></a>Uncategorised


- [**492**stars][7m] [Py] [danigargu/heap-viewer](https://github.com/danigargu/heap-viewer) 查看glibc堆, 主要用于漏洞开发
- [**372**stars][3m] [Py] [l4ys/lazyida](https://github.com/l4ys/lazyida) 若干快速访问功能, 扫描字符串格式化漏洞
    - 重复区段: [IDA->插件->字符串](#9dcc6c7dd980bec1f92d0cc9a2209a24) |[IDA->插件->效率->其他](#c5b120e1779b928d860ad64ff8d23264) |
        <details>
        <summary>View details</summary>


        ### 功能
        - 快速移除函数返回类型
        - 数据格式(format)快速转换
        - 扫描字符串格式化漏洞
        - 双击跳转vtable函数
        - 快捷键: w/c/v
        </details>




#### <a id="cf2efa7e3edb24975b92d2e26ca825d2"></a>ROP






### <a id="7d557bc3d677d206ef6c5a35ca8b3a14"></a>补丁&&Patch


- [**727**stars][1y] [Py] [keystone-engine/keypatch](https://github.com/keystone-engine/keypatch) 汇编/补丁插件, 支持多架构, 基于Keystone引擎


### <a id="7dfd8abad50c14cd6bdc8d8b79b6f595"></a>Other




### <a id="90bf5d31a3897400ac07e15545d4be02"></a>函数相关


#### <a id="347a2158bdd92b00cd3d4ba9a0be00ae"></a>Uncategorised




#### <a id="73813456eeb8212fd45e0ea347bec349"></a>重命名&&前缀&&标记


- [**291** stars][3m] [Python] [a1ext/auto_re](https://github.com/a1ext/auto_re) — Automatically renames functions.


#### <a id="e4616c414c24b58626f834e1be079ebc"></a>Navigation&&查看&&查找




#### <a id="cadae88b91a57345d266c68383eb05c5"></a>demangle






### <a id="34ac84853604a7741c61670f2a075d20"></a>污点分析&&符号执行


- [**931**stars][25d] [OCaml] [airbus-seclab/bincat](https://github.com/airbus-seclab/bincat) 二进制代码静态分析工具。值分析（寄存器、内存）、污点分析、类型重建和传播（propagation）、前向/后向分析
    - 重复区段: [IDA->插件->结构体->未分类](#fa5ede9a4f58d4efd98585d3158be4fb) |


### <a id="9dcc6c7dd980bec1f92d0cc9a2209a24"></a>字符串


- [**1365**stars][3m] [Py] [fireeye/flare-floss](https://github.com/fireeye/flare-floss) 自动从恶意代码中提取反混淆后的字符串
    - 重复区段: [IDA->插件->反混淆](#7199e8787c0de5b428f50263f965fda7) |
    - [floss](https://github.com/fireeye/flare-floss/tree/master/floss) 
    - [IDA插件](https://github.com/fireeye/flare-floss/blob/master/scripts/idaplugin.py) 
- [**372**stars][3m] [Py] [l4ys/lazyida](https://github.com/l4ys/lazyida) 若干快速访问功能, 扫描字符串格式化漏洞
    - 重复区段: [IDA->插件->效率->其他](#c5b120e1779b928d860ad64ff8d23264) |[IDA->插件->漏洞->未分类](#385d6777d0747e79cccab0a19fa90e7e) |
        <details>
        <summary>View details</summary>


        ### 功能
        - 快速移除函数返回类型
        - 数据格式(format)快速转换
        - 扫描字符串格式化漏洞
        - 双击跳转vtable函数
        - 快捷键: w/c/v
        </details>




### <a id="06d2caabef97cf663bd29af2b1fe270c"></a>加密解密


- [**449**stars][2m] [Py] [polymorf/findcrypt-yara](https://github.com/polymorf/findcrypt-yara) 使用Yara规则查找加密常量
    - 重复区段: [IDA->插件->签名(FLIRT等)->Yara](#46c9dfc585ae59fe5e6f7ddf542fb31a) |




***


## <a id="18c6a45392d6b383ea24b363d2f3e76b"></a>Articles


### <a id="37634a992983db427ce41b37dd9a98c2"></a>Recently Added


- 2019.12 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P27)](https://medium.com/p/5fa5c173547c)
- 2019.12 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P26)](https://medium.com/p/f3fc8d187258)
- 2019.12 [knownsec] [使用 IDA 处理 U-Boot 二进制流文件](https://blog.knownsec.com/2019/12/%e4%bd%bf%e7%94%a8-ida-%e5%a4%84%e7%90%86-u-boot-%e4%ba%8c%e8%bf%9b%e5%88%b6%e6%b5%81%e6%96%87%e4%bb%b6/)
- 2019.12 [venus] [Processing U-Boot Binary Stream Files with IDA](https://paper.seebug.org/1090/)
- 2019.11 [hexblog] [Extending IDA processor modules for GDB debugging](http://www.hexblog.com/?p=1371)
- 2019.11 [0x48] [Processing U-Boot Binary Stream Files with IDA](https://nobb.site/2019/11/29/0x57/)
- 2019.11 [aliyun] [Removing OLLVM Obfuscation with IDA Microcode (Part 1)](https://xz.aliyun.com/t/6749)
- 2019.10 [cisco] [New IDA Pro plugin provides TileGX support](https://blogs.cisco.com/security/talos/new-ida-pro-plugin-provides-tilegx-support)
- 2019.09 [cisco] [GhIDA: Ghidra decompiler for IDA Pro](https://blogs.cisco.com/security/talos/ghida-ghidra-decompiler-for-ida-pro)
- 2019.09 [cn0xroot] [Fix IDA Crash bug on osx 10.14](https://cn0xroot.com/2019/09/02/fix-ida-crash-bug-on-osx-10-14/)
- 2019.08 [hexblog] [IDA 7.4: IDAPython and Python 3](http://www.hexblog.com/?p=1355)
- 2019.08 [hexblog] [IDA 7.4: Turning off IDA 6.x compatibility in IDAPython by default](http://www.hexblog.com/?p=1352)
- 2019.06 [hitbsecconf] [#HITB2019AMS D1T2 - fn_fuzzy: Fast Multiple Binary Diffing Triage With IDA - Takahiro Haruyama](https://www.youtube.com/watch?v=kkvNebE9amY)
- 2019.05 [aliyun] [Tricking IDA's F5 Parameter Recognition](https://xz.aliyun.com/t/5186)
- 2019.05 [aliyun] [A Small Trick to Confuse IDA F5 on x64](https://xz.aliyun.com/t/4994)
- 2018.11 [4hou] [Automatically Mapping Binary Files to Replace Default Function Names Using IDAPython](http://www.4hou.com/technology/14149.html)
- 2018.10 [WarrantyVoider] [Ida Pro Tutorial -  Compare Reverse Engineering](https://www.youtube.com/watch?v=7-OytQJRwtE)
- 2018.06 [freebuf] [MindshaRE: Using IDA Python to Explore the Windows Kernel](http://www.freebuf.com/articles/system/173269.html)
- 2018.05 [WarrantyVoider] [Tutorial - Debugging In Source Code With IDA Pro](https://www.youtube.com/watch?v=Jgb3KTVg-rY)
- 2018.03 [BinaryAdventure] [x86 In-Depth 4: Labeling Structs Properly in IDA Pro](https://www.youtube.com/watch?v=X3xCwNt2ZVY)


### <a id="4187e477ebc45d1721f045da62dbf4e8"></a>Uncategorised


- 2018.05 [tradahacking] [Comparing Binary Files Using IDA and Supporting Tools](https://medium.com/p/651e62117695)
- 2018.04 [pediy] [Translation: IDAPython Book (Alexander Hanel)](https://bbs.pediy.com/thread-225920.htm)
- 2018.03 [hexblog] [IDA on non-OS X/Retina Hi-DPI displays](http://www.hexblog.com/?p=1180)
- 2018.03 [pediy] [Translation: Text Execution in IDA v6.5](https://bbs.pediy.com/thread-225514.htm)
- 2018.02 [pediy] [Original: Getting Familiar with IDA Through Reverse Engineering](https://bbs.pediy.com/thread-224499.htm)
- 2018.01 [pediy] [Original: Setting Up an IDA Pro Remote Debugging Environment on ARM Linux](https://bbs.pediy.com/thread-224337.htm)
- 2018.01 [pediy] [Translation: Techniques for Countering ARM Disassembly in the IDA Pro Debugger](https://bbs.pediy.com/thread-223894.htm)
- 2017.12 [OALabs] [Debugging shellcode using BlobRunner and IDA Pro](https://www.youtube.com/watch?v=q9q8dy-2Jeg)
- 2017.12 [pediy] [Original: Guide to Compiling IDA 7.0 Mac Plugins](https://bbs.pediy.com/thread-223211.htm)
- 2017.12 [pediy] [Original: Installing and Using the IDA FRIEND Plugin](https://bbs.pediy.com/thread-223156.htm)
- 2017.12 [BinaryAdventure] [IDAPython Tutorial with example script](https://www.youtube.com/watch?v=5ehI2wgcSGo)
- 2017.11 [OALabs] [How To Defeat Anti-VM and Anti-Debug Packers With IDA Pro](https://www.youtube.com/watch?v=WlE8abc8V-4)
- 2017.11 [pediy] [Original: IDAPython Script — Automatically Setting a Breakpoint at JNI_OnLoad](https://bbs.pediy.com/thread-222998.htm)
- 2017.11 [pediy] [Question: Debugging a .so File with IDA Pro Shows Only DCB Pseudo-Instructions After Attaching](https://bbs.pediy.com/thread-222646.htm)
- 2017.11 [OALabs] [IDA Pro Malware Analysis Tips](https://www.youtube.com/watch?v=qCQRKLaz2nQ)
- 2017.10 [hexblog] [IDA and common Python issues](http://www.hexblog.com/?p=1132)
- 2017.10 [pediy] [Sharing: Debugging Windows 7 x64 with IDA and VMware](https://bbs.pediy.com/thread-221884.htm)
- 2017.06 [pediy] [Translation: Tips for Using the IDA Hex-Rays Decompiler](https://bbs.pediy.com/thread-218780.htm)
- 2017.06 [qmemcpy] [IDA series, part 2: debugging a .NET executable](https://qmemcpy.io/post/ida-series-2-debugging-net)
- 2017.06 [qmemcpy] [IDA series, part 1: the Hex-Rays decompiler](https://qmemcpy.io/post/ida-series-1-hex-rays)


### <a id="a4bd25d3dc2f0be840e39674be67d66b"></a>Tips&&Tricks


- 2019.07 [kienbigmummy] [Cách export data trong IDA](https://medium.com/p/d4c8128704f)
- 2019.07 [hexacorn] [Batch decompilation with IDA / Hex-Rays Decompiler](http://www.hexacorn.com/blog/2019/07/04/batch-decompilation-with-ida-hex-rays-decompiler/)
- 2019.06 [openanalysis] [Disable ASLR for Easier Malware Debugging With x64dbg and IDA Pro](https://oalabs.openanalysis.net/2019/06/12/disable-aslr-for-easier-malware-debugging/)
- 2019.06 [OALabs] [Disable ASLR For Easier Malware Debugging With x64dbg and IDA Pro](https://www.youtube.com/watch?v=DGX7oZvdmT0)
- 2019.06 [openanalysis] [Reverse Engineering C++ Malware With IDA Pro: Classes, Constructors, and Structs](https://oalabs.openanalysis.net/2019/06/03/reverse-engineering-c-with-ida-pro-classes-constructors-and-structs/)
- 2019.06 [OALabs] [Reverse Engineering C++ Malware With IDA Pro](https://www.youtube.com/watch?v=o-FFGIloxvE)
- 2019.03 [aliyun] [IDA Pro 7.0 Tips and Tricks](https://xz.aliyun.com/t/4205)
- 2018.06 [checkpoint] [Scriptable Remote Debugging with Windbg and IDA Pro](https://research.checkpoint.com/scriptable-remote-debugging-windbg-ida-pro/)
- 2015.07 [djmanilaice] [Automatic Suggestions in PyCharm When Writing IDAPython Scripts](http://djmanilaice.blogspot.com/2015/07/pycharm-for-your-ida-development.html)
- 2015.07 [djmanilaice] [Automatically Opening DLL and EXE Files in the Current Directory with IDA](http://djmanilaice.blogspot.com/2015/07/auto-open-dlls-and-exe-in-current.html)


### <a id="04cba8dbb72e95d9c721fe16a3b48783"></a>系列Articles-LabelessPlugins介绍


- 2018.10 [checkpoint] [Labeless Part 6: How to Resolve Obfuscated API Calls in the Ngioweb Proxy Malware - Check Point Research](https://research.checkpoint.com/labeless-part-6-how-to-resolve-obfuscated-api-calls-in-the-ngioweb-proxy-malware/)
- 2018.10 [checkpoint] [Labeless Part 5: How to Decrypt Strings in Boleto Banking Malware Without Reconstructing Decryption Algorithm. - Check Point Research](https://research.checkpoint.com/labeless-part-5-how-to-decrypt-strings-in-boleto-banking-malware-without-reconstructing-decryption-algorithm/)
- 2018.10 [checkpoint] [Labeless Part 4: Scripting - Check Point Research](https://research.checkpoint.com/labeless-part-4-scripting/)
- 2018.08 [checkpoint] [Labeless Part 3: How to Dump and Auto-Resolve WinAPI Calls in LockPos Point-of-Sale Malware - Check Point Research](https://research.checkpoint.com/19558-2/)
- 2018.08 [checkpoint] [Labeless Part 2: Installation - Check Point Research](https://research.checkpoint.com/installing-labeless/)
- 2018.08 [checkpoint] [Labeless Part 1: An Introduction - Check Point Research](https://research.checkpoint.com/labeless-an-introduction/)


### <a id="1a2e56040cfc42c11c5b4fa86978cc19"></a>系列Articles-使用IDA从零开始学逆向


- 2019.11 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P25)](https://medium.com/p/304110bdf635)
- 2019.10 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P24)](https://medium.com/p/66451e50163e)
- 2019.10 [tradahacking] [REVERSING WITH IDA FROM SCRATCH (P23)](https://medium.com/p/a03897f960be)
- 2019.09 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P21)](https://medium.com/p/17ce2ee804af)
- 2019.08 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P20)](https://medium.com/p/adc2bad58cc3)
- 2019.08 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P19)](https://medium.com/p/b8a5ccc0efbc)
- 2019.07 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P18)](https://medium.com/p/b9b5987eea22)
- 2019.07 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P17)](https://medium.com/p/13aae3c33824)
- 2019.06 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P16)](https://medium.com/p/66c697636724)
- 2019.06 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P15)](https://medium.com/p/9bb2bbdf6fbc)
- 2019.05 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P14)](https://medium.com/p/fd20c144c844)
- 2019.05 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P13)](https://medium.com/p/adc88403c295)
- 2019.04 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P12)](https://medium.com/p/6b19df3db60e)
- 2019.04 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P11)](https://medium.com/p/34e6214132d6)
- 2019.03 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P10)](https://medium.com/p/f054072cc4cd)
- 2019.03 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P9)](https://medium.com/p/3ead456499d2)
- 2019.03 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P8)](https://medium.com/p/c627c70b5efd)
- 2019.03 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P7)](https://medium.com/p/986cb6c09405)
- 2019.03 [tradahacking] [REVERSING WITH IDA FROM SCRATCH (P6)](https://medium.com/p/ec232b87a091)
- 2019.03 [kienbigmummy] [REVERSING WITH IDA FROM SCRATCH (P5)](https://medium.com/p/f153835b4ffc)


### <a id="e838a1ecdcf3d068547dd0d7b5c446c6"></a>系列Articles-IDAPython-让你的生活更美好


#### <a id="7163f7c92c9443e17f3f76cc16c2d796"></a>原文


- 2016.06 [paloaltonetworks] [ Using IDAPython to Make Your Life Easier, Part6](https://unit42.paloaltonetworks.com/unit42-using-idapython-to-make-your-life-easier-part-6/)
- 2016.01 [paloaltonetworks] [ Using IDAPython to Make Your Life Easier, Part5](https://unit42.paloaltonetworks.com/using-idapython-to-make-your-life-easier-part-5/)
- 2016.01 [paloaltonetworks] [ Using IDAPython to Make Your Life Easier, Part4](https://unit42.paloaltonetworks.com/using-idapython-to-make-your-life-easier-part-4/)
- 2016.01 [paloaltonetworks] [ Using IDAPython to Make Your Life Easier, Part3](https://unit42.paloaltonetworks.com/using-idapython-to-make-your-life-easier-part-3/)
- 2015.12 [paloaltonetworks] [ Using IDAPython to Make Your Life Easier, Part2](https://unit42.paloaltonetworks.com/using-idapython-to-make-your-life-easier-part-2/)
- 2015.12 [paloaltonetworks] [ Using IDAPython to Make Your Life Easier, Part1](https://unit42.paloaltonetworks.com/using-idapython-to-make-your-life-easier-part-1/)


#### <a id="fc62c644a450f3e977af313edd5ab124"></a>译文


- 2016.01 [freebuf] [IDAPython：让你的生活更美好（五）](http://www.freebuf.com/articles/system/93440.html)
- 2016.01 [freebuf] [IDAPython：让你的生活更美好（四）](http://www.freebuf.com/articles/system/92505.html)
- 2016.01 [freebuf] [IDAPython：让你的生活更美好（三）](http://www.freebuf.com/articles/system/92488.html)
- 2016.01 [freebuf] [IDAPython：让你的生活更美好（二）](http://www.freebuf.com/sectool/92168.html)
- 2016.01 [freebuf] [IDAPython：让你的生活更美好（一）](http://www.freebuf.com/sectool/92107.html)




### <a id="8433dd5df40aaf302b179b1fda1d2863"></a>系列Articles-使用IDA逆向C代码


- 2019.01 [ly0n] [Reversing C code with IDA part V](https://paumunoz.tech/2019/01/12/reversing-c-code-with-ida-part-v/)
- 2019.01 [ly0n] [Reversing C code with IDA part IV](https://paumunoz.tech/2019/01/07/reversing-c-code-with-ida-part-iv/)
- 2019.01 [ly0n] [Reversing C code with IDA part III](https://paumunoz.tech/2019/01/02/reversing-c-code-with-ida-part-iii/)
- 2018.12 [ly0n] [Reversing C code with IDA part II](https://paumunoz.tech/2018/12/31/reversing-c-code-with-ida-part-ii/)
- 2018.01 [ly0n] [Reversing C code with IDA part I](https://paumunoz.tech/2018/01/11/reversing-c-code-with-ida-part-i/)


### <a id="3d3bc775abd7f254ff9ff90d669017c9"></a>Tools&&Plugins&&Scripts介绍


#### <a id="cd66794473ea90aa6241af01718c3a7d"></a>Uncategorised


- 2019.10 [vmray] [VMRay IDA Plugin v1.1: Streamlining Deep-Dive Malware Analysis](https://www.vmray.com/cyber-security-blog/vmray-ida-plugin-v1-1-streamlining-deep-dive-malware-analysis/)
- 2019.10 [talosintelligence] [New IDA Pro plugin provides TileGX support](https://blog.talosintelligence.com/2019/10/new-ida-pro-plugin-provides-tilegx.html)
- 2019.09 [talosintelligence] [GhIDA: Ghidra decompiler for IDA Pro](https://blog.talosintelligence.com/2019/09/ghida.html)
- 2019.05 [carbonblack] [fn_fuzzy: Fast Multiple Binary Diffing Triage with IDA](https://www.carbonblack.com/2019/05/09/fn_fuzzy-fast-multiple-binary-diffing-triage-with-ida/)
- 2019.04 [] [climacros – IDA productivity tool](http://0xeb.net/2019/04/climacros-ida-productivity-tool/)
- 2019.04 [] [QScripts – IDA Scripting productivity tool](http://0xeb.net/2019/04/ida-qscripts/)
- 2019.03 [] [Daenerys: IDA Pro and Ghidra interoperability framework](http://0xeb.net/2019/03/daenerys-ida-pro-and-ghidra-interoperability-framework/)
- 2019.03 [freebuf] [Ponce：一键即可实现符号执行（IDA插件）](https://www.freebuf.com/sectool/197708.html)
- 2019.01 [talosintelligence] [Dynamic Data Resolver (DDR) - IDA Plugin](https://blog.talosintelligence.com/2019/01/ddr.html)
- 2018.11 [4hou] [FLARE脚本系列：使用idawasm IDA Pro插件逆向WebAssembly（Wasm）模块](http://www.4hou.com/reverse/13935.html)
- 2018.10 [aliyun] [用idawasm IDA Pro逆向WebAssembly模块](https://xz.aliyun.com/t/2854)
- 2018.10 [fireeye] [FLARE Script Series: Reverse Engineering WebAssembly Modules Using the
idawasm IDA Pro Plugin](https://www.fireeye.com/blog/threat-research/2018/10/reverse-engineering-webassembly-modules-using-the-idawasm-ida-pro-plugin.html)
- 2018.10 [vmray] [Introducing the IDA Plugin for VMRay Analyzer](https://www.vmray.com/cyber-security-blog/ida-plugin-vmray-analyzer/)
- 2018.10 [aliyun] [IDA-minsc在Hex-Rays插件大赛中获得第二名（2）](https://xz.aliyun.com/t/2842)
- 2018.10 [aliyun] [IDA-minsc在Hex-Rays插件大赛中获得第二名（1）](https://xz.aliyun.com/t/2841)
- 2018.10 [aliyun] [通过两个IDAPython插件支持A12 PAC指令和iOS12 kernelcache 重定位](https://xz.aliyun.com/t/2839)
- 2018.09 [ptsecurity] [How we developed the NIOS II processor module for IDA Pro](http://blog.ptsecurity.com/2018/09/how-we-developed-nios-ii-processor.html)
- 2018.09 [talosintelligence] [IDA-minsc Wins Second Place in Hex-Rays Plugins Contest](https://blog.talosintelligence.com/2018/09/ida-minsc.html)
- 2018.09 [cisco] [IDA-minsc Wins Second Place in Hex-Rays Plugins Contest](https://blogs.cisco.com/security/talos/ida-minsc-wins-second-place-in-hex-rays-plugins-contest)
- 2018.09 [msreverseengineering] [Weekend Project: A Custom IDA Loader Module for the Hidden Bee Malware Family](http://www.msreverseengineering.com/blog/2018/9/2/weekend-project-a-custom-ida-loader-module-for-the-hidden-bee-malware-family)


#### <a id="43a4761e949187bf737e378819752c3b"></a>Loader&&Processor


- 2019.03 [360] [为CHIP-8编写IDA processor module](https://www.anquanke.com/post/id/172217/)
- 2018.10 [ptsecurity] [Modernizing IDA Pro: how to make processor module glitches go away](http://blog.ptsecurity.com/2018/10/modernizing-ida-pro-how-to-make.html)
- 2018.08 [360] [Lua程序逆向之为Luac编写IDA Pro处理器模块](https://www.anquanke.com/post/id/153699/)


#### <a id="c7483f3b20296ac68084a8c866230e15"></a>Interoperability with Other Tools


- 2018.09 [dustri] [IDAPython vs. r2pipe](https://dustri.org/b/idapython-vs-r2pipe.html)




### <a id="ea11818602eb33e8b165eb18d3710965"></a>翻译-TheIDAProBook


- 2008.10 [pediy] [[翻译]The IDA Pro Book 第六章](https://bbs.pediy.com/thread-75632.htm)
- 2008.10 [pediy] [[翻译]（20081030更新）The IDA Pro Book 第12章：使用FLIRT签名识别库](https://bbs.pediy.com/thread-75422.htm)
- 2008.10 [pediy] [[翻译]The IDA Pro Book(第二章)](https://bbs.pediy.com/thread-74943.htm)
- 2008.10 [pediy] [[翻译]The IDA Pro book 第5章---IDA DATA DISPLAY](https://bbs.pediy.com/thread-74838.htm)
- 2008.10 [pediy] [[翻译]The IDA Pro Book(第一章)](https://bbs.pediy.com/thread-74564.htm)


### <a id="ec5f7b9ed06500c537aa25851a3f2d3a"></a>翻译-ReverseEngineeringCodeWithIDAPro


- 2009.01 [pediy] [[原创]Reverse Engineering Code with IDA Pro第七章中文译稿](https://bbs.pediy.com/thread-80580.htm)
- 2008.06 [pediy] [[翻译]Reverse Engineering Code with IDA Pro(第一、二章)](https://bbs.pediy.com/thread-66010.htm)


### <a id="2120fe5420607a363ae87f5d2fed459f"></a>IDA本身


- 2019.01 [pediy] [[原创]IDA7.2安装包分析](https://bbs.pediy.com/thread-248989.htm)
- 2019.01 [pediy] [[原创]IDA 在解析 IA64 中的 brl 指令时存在一个 Bug](https://bbs.pediy.com/thread-248983.htm)
- 2018.11 [hexblog] [IDA 7.2 – The Mac Rundown](http://www.hexblog.com/?p=1300)
- 2018.10 [pediy] [[原创] 修复 IDA Pro 7.0在macOS Mojave崩溃的问题](https://bbs.pediy.com/thread-247334.htm)


### <a id="d8e48eb05d72db3ac1e050d8ebc546e1"></a>逆向实战


#### <a id="374c6336120363a5c9d9a27d7d669bf3"></a>Uncategorised


- 2019.11 [4hou] [反作弊游戏如何破解，看看《黑色沙漠》逆向分析过程：使用 IDAPython 和 FLIRT 签名恢复 IAT](https://www.4hou.com/web/21806.html)
- 2019.11 [aliyun] [使用IDA microcode去除ollvm混淆(下)](https://xz.aliyun.com/t/6795)
- 2019.06 [devco] [破密行動: 以不尋常的角度破解 IDA Pro 偽隨機數](https://devco.re/blog/2019/06/21/operation-crack-hacking-IDA-Pro-installer-PRNG-from-an-unusual-way/)
- 2019.05 [360] [IDAPython实战项目——DES算法识别](https://www.anquanke.com/post/id/177808/)
- 2019.04 [venus] [使用 IDA Pro 的 REobjc 模块逆向 Objective-C 二进制文件](https://paper.seebug.org/887/)
- 2019.01 [ly0n] [Cracking with IDA (redh@wk 2.5 crackme)](https://paumunoz.tech/2019/01/05/cracking-with-ida-redhwk-2-5-crackme/)
- 2018.11 [somersetrecon] [Introduction to IDAPython for Vulnerability Hunting - Part 2](http://www.somersetrecon.com/blog/2018/8/2/idapython-part-2)
- 2018.11 [pediy] [[原创]IDA动态调试ELF](https://bbs.pediy.com/thread-247830.htm)
- 2018.06 [pediy] [[翻译]在IDA中使用Python Z3库来简化函数中的算术运算](https://bbs.pediy.com/thread-228688.htm)
- 2018.03 [duo] [Reversing Objective-C Binaries With the REobjc Module for IDA Pro](https://duo.com/blog/reversing-objective-c-binaries-with-the-reobjc-module-for-ida-pro)
- 2006.05 [pediy] [Themida v1008 驱动程序分析,去除花指令的 IDA 文件](https://bbs.pediy.com/thread-25836.htm)


#### <a id="0b3e1936ad7c4ccc10642e994c653159"></a>Malware分析


- 2019.04 [360] [两种姿势批量解密恶意驱动中的上百条字串](https://www.anquanke.com/post/id/175964/)
- 2019.03 [cyber] [使用IDAPython分析Trickbot](https://cyber.wtf/2019/03/22/using-ida-python-to-analyze-trickbot/)
- 2019.01 [OALabs] [Lazy String Decryption Tips With IDA PRO and Shade Ransomware Unpacked!](https://www.youtube.com/watch?v=RfnuMhosxuQ)
- 2018.09 [4hou] [Hidden Bee恶意软件家族的定制IDA装载模块开发](http://www.4hou.com/technology/13438.html)
- 2018.09 [4hou] [用IDAPython解密Gootkit中的字符串](http://www.4hou.com/technology/13209.html)
- 2018.05 [OALabs] [Unpacking Gootkit Part 2 - Debugging Anti-Analysis Tricks With IDA Pro and x64dbg](https://www.youtube.com/watch?v=QgUlPvEE4aw)
- 2018.04 [OALabs] [Unpacking VB6 Packers With IDA Pro and API Hooks (Re-Upload)](https://www.youtube.com/watch?v=ylWInOcQy2s)
- 2018.03 [OALabs] [Unpacking Gootkit Malware With IDA Pro and X64dbg - Subscriber Request](https://www.youtube.com/watch?v=242Tn0IL2jE)
- 2018.01 [OALabs] [Unpacking Pykspa Malware With Python and IDA Pro - Subscriber Request Part 1](https://www.youtube.com/watch?v=HfSQlC76_s4)
- 2017.11 [OALabs] [Unpacking Process Injection Malware With IDA PRO (Part 2)](https://www.youtube.com/watch?v=kdNQhfgoQoU)
- 2017.11 [OALabs] [Unpacking Process Injection Malware With IDA PRO (Part 1)](https://www.youtube.com/watch?v=ScBB-Hi7NxQ)
- 2017.06 [hackers] [Reverse Engineering Malware, Part 3:  IDA Pro Introduction](https://www.hackers-arise.com/single-post/2017/06/22/Reverse-Engineering-Malware-Part-3-IDA-Pro-Introduction)
- 2017.05 [4hou] [逆向分析——使用IDA动态调试WanaCrypt0r中的tasksche.exe](http://www.4hou.com/technology/4832.html)
- 2017.05 [3gstudent] [逆向分析——使用IDA动态调试WanaCrypt0r中的tasksche.exe](https://3gstudent.github.io/3gstudent.github.io/%E9%80%86%E5%90%91%E5%88%86%E6%9E%90-%E4%BD%BF%E7%94%A8IDA%E5%8A%A8%E6%80%81%E8%B0%83%E8%AF%95WanaCrypt0r%E4%B8%AD%E7%9A%84tasksche.exe/)
- 2012.06 [trustwave] [使用IDAPython对Flame的字符串进行反混淆](https://www.trustwave.com/Resources/SpiderLabs-Blog/Defeating-Flame-String-Obfuscation-with-IDAPython/)


#### <a id="03465020d4140590326ae12c9601ecfd"></a>Vulnerabilities分析&&挖掘


- 2018.07 [360] [如何使用 IDAPython 寻找漏洞](https://www.anquanke.com/post/id/151898/)
- 2018.07 [somersetrecon] [如何使用IDAPython挖掘漏洞](http://www.somersetrecon.com/blog/2018/7/6/introduction-to-idapython-for-vulnerability-hunting)




### <a id="e9ce398c2c43170e69c95fe9ad8d22fc"></a>Microcode


- 2019.10 [amossys] [探秘Hex-Rays microcode](https://blog.amossys.fr/stage-2019-hexraysmicrocode.html)


### <a id="9c0ec56f402a2b9938417f6ecbaeaa72"></a>IDA对抗


- 2019.05 [aliyun] [混淆IDA F5的一个小技巧-x86](https://xz.aliyun.com/t/5062)




# <a id="319821036a3319d3ade5805f384d3165"></a>Ghidra


***


## <a id="fa45b20f6f043af1549b92f7c46c9719"></a>Plugins&&Scripts


### <a id="2ae406afda6602c8f02d73678b2ff040"></a>Ghidra


- [**18649** stars][10d] [Java] [nationalsecurityagency/ghidra](https://github.com/nationalsecurityagency/ghidra) — A software reverse-engineering framework.


### <a id="ce70b8d45be0a3d29705763564623aca"></a>Recently Added


- [**455** stars][9m] [YARA] [ghidraninja/ghidra_scripts](https://github.com/ghidraninja/ghidra_scripts) — A collection of Ghidra scripts.
    - [binwalk](https://github.com/ghidraninja/ghidra_scripts/blob/master/binwalk.py) — Runs Binwalk on the current program and labels the content it finds.
    - [yara](https://github.com/ghidraninja/ghidra_scripts/blob/master/yara.py) — Uses YARA to search for cryptographic constants.
    - [swift_demangler](https://github.com/ghidraninja/ghidra_scripts/blob/master/swift_demangler.py) — Automatically demangles Swift function names.
    - [golang_renamer](https://github.com/ghidraninja/ghidra_scripts/blob/master/golang_renamer.py) — Restores function names in stripped Go binaries.
- [**204** stars][8m] [Java] [rolfrolles/ghidrapal](https://github.com/rolfrolles/ghidrapal) — A Ghidra program-analysis library (no documentation).


### <a id="69dc4207618a2977fe8cd919e7903fa5"></a>特定分析目标


#### <a id="da5d2b05da13f8e65aa26d6a1c95a8d0"></a>Uncategorised




#### <a id="058bb9893323f337ad1773725d61f689"></a>Loader&&Processor




#### <a id="51a2c42c6d339be24badf52acb995455"></a>Xbox






### <a id="99e3b02da53f1dbe59e0e277ef894687"></a>Interoperability with Other Tools


#### <a id="5923db547e1f04f708272543021701d2"></a>Uncategorised




#### <a id="e1cc732d1388084530b066c26e24887b"></a>Radare2




#### <a id="d832a81018c188bf585fcefa3ae23062"></a>IDA


- [**299**stars][4m] [Py] [cisco-talos/ghida](https://github.com/cisco-talos/ghida) 在IDA中集成Ghidra反编译器
    - 重复区段: [IDA->插件->导入导出->Ghidra](#c7066b0c388cd447e980bf0eb38f39ab) |
- [**238**stars][9m] [Py] [daenerys-sre/source](https://github.com/daenerys-sre/source) 使IDA和Ghidra脚本通用, 无需修改
    - 重复区段: [IDA->插件->导入导出->Ghidra](#c7066b0c388cd447e980bf0eb38f39ab) |


#### <a id="60e86981b2c98f727587e7de927e0519"></a>DBI




#### <a id="e81053b03a859e8ac72f7fe79e80341a"></a>Debugging器






### <a id="cccbd06c6b9b03152d07a4072152ae27"></a>Appearance&&Themes




### <a id="45910c8ea12447df9cdde2bea425f23f"></a>Scripts编写


#### <a id="c12ccb8e11ba94184f8f24767eb64212"></a>Other




#### <a id="b24e162720cffd2d2456488571c1a136"></a>编程语言








***


## <a id="273df546f1145fbed92bb554a327b87a"></a>Articles and Videos


### <a id="8962bde3fbfb1d1130879684bdf3eed0"></a>Recently Added1


- 2019.12 [shogunlab] [Here Be Dragons: Reverse Engineering with Ghidra - Part 1 [Data, Functions & Scripts]](https://www.shogunlab.com/blog/2019/12/22/here-be-dragons-ghidra-1.html)
- 2019.11 [freebuf] [Analysing the phpStudy Backdoor with Ghidra](https://www.freebuf.com/sectool/217560.html)
- 2019.10 [4hou] [Analysing the phpStudy Backdoor with Ghidra](https://www.4hou.com/technology/21097.html)
- 2019.10 [knownsec] [使用 Ghidra 分析 phpStudy 后门](https://blog.knownsec.com/2019/10/%e4%bd%bf%e7%94%a8-ghidra-%e5%88%86%e6%9e%90-phpstudy-%e5%90%8e%e9%97%a8/)
- 2019.10 [venus] [Analysing the phpStudy Backdoor with Ghidra](https://paper.seebug.org/1058/)
- 2019.10 [WarrantyVoider] [C64LoaderWV - Loading C64 programs into Ghidra](https://www.youtube.com/watch?v=thl6VciaUzg)
- 2019.08 [pentestpartners] [CVE-2019-12103 – Analysis of a Pre-Auth RCE on the TP-Link M7350, with Ghidra!](https://www.pentestpartners.com/security-blog/cve-2019-12103-analysis-of-a-pre-auth-rce-on-the-tp-link-m7350-with-ghidra/)
- 2019.08 [xpnsec] [Analysing RPC With Ghidra and Neo4j](https://blog.xpnsec.com/analysing-rpc-with-ghidra-neo4j/)
- 2019.04 [X0x6d696368] [ghidra_scripts: GoogleSearch.py (to lookup function names via Google)](https://www.youtube.com/watch?v=BMmNg35Cjqo)
- 2019.04 [X0x6d696368] [ghidra_scripts: SimpleStackStrings.py (to reassemble "stack strings")](https://www.youtube.com/watch?v=K_2khlMATew)
- 2019.04 [X0x6d696368] [ghidra_scripts: colorCallGraphCallsTo.py (using SetBackroundColor and traversing the call graph)](https://www.youtube.com/watch?v=SHNO1ZrIQB8)
- 2019.04 [4hou] [Reverse Engineering the Tytera MD380 Firmware Using Ghidra](https://www.4hou.com/reverse/17464.html)
- 2019.04 [jeanmichel] [First steps with Ghidra: crackme01](https://medium.com/p/319827a2e80b)
- 2019.03 [GynvaelEN] [Hacking Livestream #74: Ghidra](https://www.youtube.com/watch?v=tXxiuHzjm34)
- 2019.01 [sans] [How to Train Your Dragon:  Ghidra Basics](https://www.sans.org/cyber-security-summit/archives/file/summit_archive_1574103618.pdf)


### <a id="ce49901b4914f3688ef54585c8f9df1a"></a>Recently Added


- 2019.09 [dustri] [Radare2, IDA Pro, and Binary ninja, a metaphoric comparison](https://dustri.org/b/radare2-ida-pro-and-binary-ninja-a-metaphoric-comparison.html)
- 2019.05 [vimeo] [Three Heads are Better Than One: Mastering Ghidra - Alexei Bulazel, Jeremy Blackthorne - INFILTRATE 2019](https://vimeo.com/335158460)
- 2019.04 [X0x6d696368] [Ghidra: Stack Depth (to detect stack manipulation)](https://www.youtube.com/watch?v=hP9FQrD61tk)
- 2019.04 [X0x6d696368] [Ghidra: Version Tracking](https://www.youtube.com/watch?v=K83T7iVla5s)
- 2019.04 [X0x6d696368] [Ghidra: Export Symbols and Load External Libraries (to resolve imported function names)](https://www.youtube.com/watch?v=Avn8s7iW3Rc)
- 2019.04 [X0x6d696368] [Ghidra: Data Type Manager / Archives and Parse C Source... (resolve function signatures)](https://www.youtube.com/watch?v=u15-r5Erfnw)
- 2019.04 [X0x6d696368] [Ghidra: Generate Checksum... (to extract hashes of embedded malware artifacts)](https://www.youtube.com/watch?v=vLG7c5Eae0s)
- 2019.04 [msreverseengineering] [An Abstract Interpretation-Based Deobfuscation Plugin for Ghidra](https://www.msreverseengineering.com/blog/2019/4/17/an-abstract-interpretation-based-deobfuscation-plugin-for-ghidra)
- 2019.04 [X0x6d696368] [Ghidra: FunctionID (to identify libraries and code reuse)](https://www.youtube.com/watch?v=P8Ul2K7pEfU)
- 2019.04 [X0x6d696368] [Ghidra: Server / Shared Projects (using ghidra-server.org)](https://www.youtube.com/watch?v=ka4vGxLmr4w)
- 2019.04 [X0x6d696368] [Ghidra: Bytes View (to patch binary and export to a working PE file)](https://www.youtube.com/watch?v=utUqAbfURko)
- 2019.04 [X0x6d696368] [Ghidra: Fixing Bugs (Fixing PE section import size alignment)](https://www.youtube.com/watch?v=vpt7-Hn-Uhg)
- 2019.04 [X0x6d696368] [Ghidra: Clear Flow and Repair, and Patch Instruction (to defeat anti-disassembly)](https://www.youtube.com/watch?v=H9DyLQ2iuyE)
- 2019.04 [X0x6d696368] [Ghidra: Scripting (Python) (a quick introduction by implementing pipeDecoder.py)](https://www.youtube.com/watch?v=WLXlq3lvUGs)
- 2019.04 [X0x6d696368] [Ghidra: Decompile and compile (to quickly reimplement malware decoding functions)](https://www.youtube.com/watch?v=YuwOgBDt_b4)
- 2019.04 [X0x6d696368] [Ghidra: EditBytesScript (to fix/manipulate PE header to load ShadowHammer setup.exe sample)](https://www.youtube.com/watch?v=7__tiVMPIEE)
- 2019.04 [X0x6d696368] [Ghidra: Extract and Import ... (to extract resources from PE binaries)](https://www.youtube.com/watch?v=M19ZSTAgubI)
- 2019.04 [X0x6d696368] [Ghidra: YaraGhidraGUIScript (to generate a YARA signature for threat/retro hunting)](https://www.youtube.com/watch?v=tBvxVkJrkh0)
- 2019.04 [X0x6d696368] [Ghidra: XORMemoryScript (to XOR decode strings)](https://www.youtube.com/watch?v=vPqs7E_nhdQ)
- 2019.04 [yoroi] [Ghidra SRE: The AZORult Field Test](https://blog.yoroi.company/research/ghidra-sre-the-azorult-field-test/)


### <a id="b7fb955b670df2babc67e5942297444d"></a>GhidraVulnerabilities


- 2019.10 [securityaffairs] [Code Execution Vulnerability in Ghidra 9.0.4 and Earlier Versions](https://securityaffairs.co/wordpress/92280/hacking/ghidra-code-execution-flaw.html)
- 2019.10 [4hou] [CVE-2019-16941: RCE Vulnerability in the NSA Ghidra Tool](https://www.4hou.com/info/news/20698.html)
- 2019.03 [venus] [From XXE to RCE in Ghidra](https://paper.seebug.org/861/)
- 2019.03 [tencent] [From XXE to RCE in Ghidra](https://xlab.tencent.com/cn/2019/03/18/ghidra-from-xxe-to-rce/)


### <a id="dd0d49a5e6bd34b372d9bbf4475e8024"></a>实战分析


#### <a id="f0ab053d7a282ab520c3a327fc91ba2e"></a>Uncategorised


- 2019.09 [venus] [Using Ghidra to Analyse msgSend in iOS Applications](https://paper.seebug.org/1037/)
- 2019.09 [4hou] [Using Ghidra to Analyse msgSend in iOS Applications](https://www.4hou.com/system/20326.html)
- 2019.09 [WarrantyVoider] [X360 XEX Decompiling With Ghidra](https://www.youtube.com/watch?v=coGz0f7hHTM)
- 2019.08 [WarrantyVoider] [N64 ROM Decompiling With Ghidra - N64LoaderWV](https://www.youtube.com/watch?v=3d3a39LuCwc)
- 2019.08 [4hou] [RPC Analysis Techniques Based on Ghidra and Neo4j](https://www.4hou.com/technology/19730.html)
- 2019.04 [X0x6d696368] [Ghidra: Search Program Text... (to find XOR decoding functions in malware)](https://www.youtube.com/watch?v=MaxwIxrmrWY)
- 2019.04 [shogunlab] [Here Be Dragons: Reverse Engineering with Ghidra - Part 0 [Main Windows & CrackMe]](https://www.shogunlab.com/blog/2019/04/12/here-be-dragons-ghidra-0.html)
- 2019.03 [GhidraNinja] [Reverse engineering with #Ghidra: Breaking an embedded firmware encryption scheme](https://www.youtube.com/watch?v=4urMITJKQQs)
- 2019.03 [GhidraNinja] [Ghidra quickstart & tutorial: Solving a simple crackme](https://www.youtube.com/watch?v=fTGTnrgjuGA)


#### <a id="375c75af4fa078633150415eec7c867d"></a>Vulnerabilities分析&&挖掘


- 2019.11 [4hou] [Using Ghidra to Compare Patches for an Overflow Vulnerability in the WhatsApp VoIP Stack](https://www.4hou.com/vulnerable/21141.html)
- 2019.09 [4hou] [Using Ghidra to Analyse the RCE Vulnerability in the TP-Link M7350 4G Portable Wi-Fi Device](https://www.4hou.com/vulnerable/20267.html)
- 2019.08 [aliyun] [CVE-2019-12103: Analysing the Pre-Authentication RCE Vulnerability in TP-Link M7350 Using Ghidra](https://xz.aliyun.com/t/6017)


#### <a id="4e3f53845efe99da287b2cea1bdda97c"></a>Malware


- 2019.06 [dawidgolak] [IcedID aka #Bokbot Analysis with Ghidra.](https://medium.com/p/560e3eccb766)
- 2019.04 [aliyun] [Analysing the Emotet Malware Using Ghidra](https://xz.aliyun.com/t/4931)
- 2019.04 [X0x6d696368] [Ghidra: Shadow Hammer (Stage 1: Setup.exe) complete static Analysis](https://www.youtube.com/watch?v=gI0nZR4z7_M)
- 2019.04 [X0xd0cf11e] [Analyzing Emotet with Ghidra — Part 2](https://medium.com/p/9efbea374b14)
- 2019.04 [X0x6d696368] [Ghidra: Android APK (it's basically dex2jar with a .dex decompiler)](https://www.youtube.com/watch?v=At_T6riSb9A)
- 2019.04 [X0xd0cf11e] [Analyzing Emotet with Ghidra — Part 1](https://medium.com/p/4da71a5c8d69)
- 2019.03 [GhidraNinja] [Reversing WannaCry Part 1 - Finding the killswitch and unpacking the malware in #Ghidra](https://www.youtube.com/watch?v=Sv8yu12y5zM)
- 2019.03 [HackerSploit] [Malware Analysis With Ghidra - Stuxnet Analysis](https://www.youtube.com/watch?v=TJhfnItRVOA)
- 2019.03 [sans] [Analysing meterpreter payload with Ghidra](https://isc.sans.edu/forums/diary/Analysing+meterpreter+payload+with+Ghidra/24722/)




### <a id="92f60c044ed13b3ffde631794edd2756"></a>Other




### <a id="4bfa6dcf708b3f896870c9d3638c0cde"></a>Tips&&Tricks




### <a id="0d086cf7980f65da8f7112b901fecdc1"></a>Tools&&Plugins&&Scripts


- 2019.11 [deadc0de] [Examples of Writing Ghidra Scripts in Python](https://deadc0de.re/articles/ghidra-scripting-python.html)
- 2019.04 [X0x6d696368] [ghidra_scripts: RC4Decryptor.py](https://www.youtube.com/watch?v=kXaHrPyZtGs)
- 2019.04 [aliyun] [How to Develop Ghidra Plugins for Vulnerability Research, Part 1](https://xz.aliyun.com/t/4723)
- 2019.04 [somersetrecon] [Ghidra Plugin Development for Vulnerability Research - Part-1](https://www.somersetrecon.com/blog/2019/ghidra-plugin-development-for-vulnerability-research-part-1)
- 2019.03 [wololo] [PS4 release: GhidraPS4Loader and Playstation 4 Flash tool](http://wololo.net/2019/03/18/ps4-release-ghidraps4loader-and-playstation-4-flash-tool/)




# <a id="b1a6c053e88e86ce01bbd78c54c63a7c"></a>x64dbg


***


## <a id="b4a856db286f9f29b5a32d477d6b3f3a"></a>Plugins&&Scripts


### <a id="353ea40f2346191ecb828210a685f9db"></a>x64dbg


- [**34576** stars][1m] [C++] [x64dbg/x64dbg](https://github.com/x64dbg/x64dbg) — A 32-bit and 64-bit debugger for Windows.


### <a id="da5688c7823802e734c39b539aa39df7"></a>Recently Added


- [**1672**stars][7m] [C++] [yegord/snowman](https://github.com/yegord/snowman) Snowman反编译器，支持x86, AMD64, ARM。有独立的GUI工具、命令行工具、IDA/Radare2/x64dbg插件，也可以作为库使用
    - 重复区段: [IDA->插件->反编译器](#d2166f4dac4eab7fadfe0fd06467fbc9) |
    - [IDA插件](https://github.com/yegord/snowman/tree/master/src/ida-plugin) 
    - [snowman](https://github.com/yegord/snowman/tree/master/src/snowman) QT界面
    - [nocode](https://github.com/yegord/snowman/tree/master/src/nocode) 命令行工具
    - [nc](https://github.com/yegord/snowman/tree/master/src/nc) 核心代码，可作为库使用
- [**1341** stars][1m] [C] [x64dbg/x64dbgpy](https://github.com/x64dbg/x64dbgpy) — Automates x64dbg using Python; supports snapshots.
- [**972** stars][2m] [Python] [x64dbg/docs](https://github.com/x64dbg/docs) — x64dbg documentation.
- [**471**stars][13d] [C] [bootleg/ret-sync](https://github.com/bootleg/ret-sync) 在反汇编工具和调试器之间同步调试会话
    - 重复区段: [IDA->插件->与调试器同步](#f7d311685152ac005cfce5753c006e4b) |
    - [GDB插件](https://github.com/bootleg/ret-sync/tree/master/ext_gdb) 
    - [Ghidra插件](https://github.com/bootleg/ret-sync/tree/master/ext_ghidra) 
    - [IDA插件](https://github.com/bootleg/ret-sync/tree/master/ext_ida) 
    - [LLDB](https://github.com/bootleg/ret-sync/tree/master/ext_lldb) 
    - [OD](https://github.com/bootleg/ret-sync/tree/master/ext_olly1) 
    - [OD2](https://github.com/bootleg/ret-sync/tree/master/ext_olly2) 
    - [WinDgb](https://github.com/bootleg/ret-sync/tree/master/ext_windbg/sync) 
    - [x64dbg](https://github.com/bootleg/ret-sync/tree/master/ext_x64dbg) 
- [**363**stars][9m] [fr0gger/awesome-ida-x64-olly-plugin](https://github.com/fr0gger/awesome-ida-x64-olly-plugin) IDA x64DBG OllyDBG 插件收集
    - 重复区段: [IDA->插件->收集](#a7dac37cd93b8bb42c7d6aedccb751b3) |




***


## <a id="22894d6f2255dc43d82dd46bdbc20ba1"></a>Articles and Videos


- 2019.02 [freebuf] [Using x64dbg to Analyse WeChat and Retrieve All Contact Information](https://www.freebuf.com/articles/terminal/195774.html)
- 2018.03 [freebuf] [Analysing WeChat Chat Functions with x64dbg and Implementing Message Sending](http://www.freebuf.com/sectool/164988.html)
- 2018.03 [360] [Using x64dbg to Unpack UPX, an Open-Source Packer](https://www.anquanke.com/post/id/99750/)
- 2018.02 [360] [Using x64dbg to Analyse WeChat's Multi-Instance Protection](https://www.anquanke.com/post/id/98825/)
- 2018.02 [360] [Using x64dbg to Analyse the Message-Recall Feature in TIM 2.0 QQ](https://www.anquanke.com/post/id/98498/)
- 2018.02 [KirbiflintCracking] [Patching a Keygenme with x64dbg [Learning Cracking]](https://www.youtube.com/watch?v=tkHW-VNBBQo)
- 2018.01 [KirbiflintCracking] [Cracking & Keygen a crackme with x64dbg [Learning Cracking]](https://www.youtube.com/watch?v=6JsYRg8_yeY)
- 2018.01 [KirbiflintCracking] [Cracking the new Steam Stub drm with x64dbg [Learning Cracking]](https://www.youtube.com/watch?v=yrrcL8xGPoE)
- 2018.01 [KirbiflintCracking] [Cracking a simple crackme & bypassing Anti-debugger protection with x64dbg [Learning Cracking]](https://www.youtube.com/watch?v=Sal3xbSJdJA)
- 2017.12 [KirbiflintCracking] [Cracking some Crackmes with x64dbg [Learning Cracking]](https://www.youtube.com/watch?v=E1zD4Lp7b1g)
- 2017.12 [KirbiflintCracking] [Cracking a simple Crackme with x64dbg [Learning cracking]](https://www.youtube.com/watch?v=MHw8Xu9Od_c)
- 2017.10 [x64dbg] [Limitations in x64dbg](https://x64dbg.com/blog/2017/10/06/Limitations-in-x64dbg.html)
- 2017.09 [pediy] [Translation: Applying Message Breakpoints in x64dbg, by lantie@15PB](https://bbs.pediy.com/thread-221551.htm)
- 2017.07 [pediy] [Original: Removing WinRAR 5.40 (64-bit) Advertising Pop-ups Using x64dbg and VS2015 Spy++](https://bbs.pediy.com/thread-219435.htm)
- 2017.06 [seowhistleblower] [Channel Update + Let's Hack: Sniper Elite 4 (Cheat Engine and x64dbg Tutorial)](https://www.youtube.com/watch?v=KCHsOmebYo4)
- 2016.10 [x64dbg] [Architecture of x64dbg](https://x64dbg.com/blog/2016/10/04/architecture-of-x64dbg.html)
- 2016.07 [x64dbg] [x64dbg plugin SDK](https://x64dbg.com/blog/2016/07/30/x64dbg-plugin-sdk.html)
- 2016.07 [adelmas] [Introducing x64dbg and Pizzacrypts Ransomware Unpacking](http://adelmas.com/blog/x64dbg_pizzacrypts.php)
- 2015.12 [pediy] [Original: Compiling x64dbg from Source](https://bbs.pediy.com/thread-206431.htm)
- 2015.10 [pediy] [Original: Win7 X64DBGPORT Shifted Data](https://bbs.pediy.com/thread-205123.htm)


# <a id="37e37e665eac00de3f55a13dcfd47320"></a>OllyDbg


***


## <a id="7834e399e48e6c64255a1a0fdb6b88f5"></a>Plugins&&Scripts


### <a id="92c44f98ff5ad8f8b0f5e10367262f9b"></a>Recently Added






***


## <a id="8dd3e63c4e1811973288ea8f1581dfdb"></a>Articles and Videos


- 2019.04 [freebuf] [Practical Buffer Overflow Tutorial Series (Part 3): Understanding How Programs Run with OllyDbg](https://www.freebuf.com/articles/system/198149.html)
- 2018.10 [pediy] [Original: Adding Sections and DLLs (APIs) to a PE File Using a PE Section Tool, LordPE, WinHex, and OllyDbg](https://bbs.pediy.com/thread-247370.htm)
- 2018.10 [pediy] [Original: The Process of Writing an OllyDbg Plugin](https://bbs.pediy.com/thread-247331.htm)
- 2018.03 [pediy] [Original: Developing an IDA-Like Static Disassembler with an OllyDbg-Style Interface](https://bbs.pediy.com/thread-225396.htm)
- 2018.01 [kienbigmummy] [OllyDbg_tut32](https://medium.com/p/345972799c44)
- 2018.01 [pediy] [How to Implement Your Own OllyDbg Debugger (1): Implementing the Interface](https://bbs.pediy.com/thread-224157.htm)
- 2017.12 [hackers] [Reverse Engineering Malware, Part 5: OllyDbg Basics](https://www.hackers-arise.com/single-post/2017/10/03/Reverse-Engineering-Malware-Part-5-OllyDbg-Basics)
- 2017.10 [4hou] [Recommended Tool: OllyDbg, a Powerful Reverse-Engineering Tool](http://www.4hou.com/tools/7890.html)
- 2017.07 [ColinHardy] [Three and a half ways to unpack malware using Ollydbg](https://www.youtube.com/watch?v=n_gxtaFX8Ao)
- 2016.12 [360] [Tracing and Analysing Process Hollowing with OllyDbg](https://www.anquanke.com/post/id/85124/)
- 2016.12 [airbuscybersecurity] [Following Process Hollowing in OllyDbg](http://blog.airbuscybersecurity.com/post/2016/06/Following-Process-Hollowing-in-OllyDbg)
- 2015.11 [pediy] [Original: Tutorial on Writing OllyDbg 2.x Plugins (Open Source)](https://bbs.pediy.com/thread-206175.htm)
- 2015.11 [pediy] [Original: An Introduction to Writing OllyDbg Plugins](https://bbs.pediy.com/thread-206064.htm)
- 2015.11 [pediy] [Translation: Chinese Translation of the OllyDbg 2.0x Help Manual](https://bbs.pediy.com/thread-205870.htm)
- 2015.08 [pediy] [Original: Complete Solutions for Exercises in Lesson 14 of Cracking from Scratch with OllyDbg](https://bbs.pediy.com/thread-203152.htm)
- 2015.01 [pediy] [Translation: Cracking from Scratch with OllyDbg, Chapter 58 — Unpacking EXECryptor v2.2.50.h](https://bbs.pediy.com/thread-196797.htm)
- 2014.11 [reversec0de] [OllyDbg Plugin Converter v0.1b](https://reversec0de.wordpress.com/2014/11/09/ollydbg-plugin-converter-v0-1b/)
- 2014.10 [pediy] [Translation: Cracking from Scratch with OllyDbg, Chapter 44 — Unpacking ACProtect v1.09 and Fixing Anti-Dump](https://bbs.pediy.com/thread-193537.htm)
- 2014.10 [pediy] [Translation: Cracking from Scratch with OllyDbg, Chapter 43 — Unpacking ACProtect v1.09 and Fixing the IAT with a Script](https://bbs.pediy.com/thread-193467.htm)
- 2014.10 [pediy] [Cracking from Scratch with OllyDbg, Chapter 42 — Unpacking ACProtect v1.09: Finding the OEP, Bypassing Hardware-Breakpoint Detection, and Fixing Stolen Code](https://bbs.pediy.com/thread-193405.htm)


# <a id="0a506e6fb2252626add375f884c9095e"></a>WinDBG


***


## <a id="37eea2c2e8885eb435987ccf3f467122"></a>Plugins&&Scripts


### <a id="2ef75ae7852daa9862b2217dca252cc3"></a>Recently Added


- [**564** stars][6m] [C#] [fremag/memoscope.net](https://github.com/fremag/memoscope.net) — Dumps and analyses the memory of .NET applications; a GUI for WinDbg and ClrMD.
- [**279** stars][1m] [Python] [hugsy/defcon_27_windbg_workshop](https://github.com/hugsy/defcon_27_windbg_workshop) — DEF CON 27 workshop: Modern Debugging with WinDbg Preview.
- [**230** stars][9m] [C++] [microsoft/windbg-samples](https://github.com/microsoft/windbg-samples) — Sample extensions, scripts, and API usage examples for WinDbg.




***


## <a id="6d8bac8bfb5cda00c7e3bd38d64cbce3"></a>Articles and Videos


- 2019.10 [freebuf] [Iris: A WinDbg Extension for Detecting Common Windows Exploitation Techniques](https://www.freebuf.com/sectool/214276.html)
- 2019.08 [lowleveldesign] [Synthetic types and tracing syscalls in WinDbg](https://lowleveldesign.org/2019/08/27/synthetic-types-and-tracing-syscalls-in-windbg/)
- 2019.08 [benoit] [Portable WinDbg](https://medium.com/p/c0087e320ddc)
- 2019.07 [osr] [How L1 Terminal Fault (L1TF) Mitigation and WinDbg Wasted My Morning (a.k.a. Yak Shaving: WinDbg Edition)](https://www.osr.com/blog/2019/07/02/how-l1-terminal-fault-l1tf-mitigation-and-windbg-wasted-my-morning-a-k-a-yak-shaving-windbg-edition/)
- 2019.06 [360] [Dive into WinDbg Series: Troubleshooting Explorer Not Starting](https://www.anquanke.com/post/id/179748/)
- 2019.05 [nul] [An Example of Extremely Slow WinDbg/cdb Performance](http://www.nul.pw/2019/05/21/281.html)
- 2019.04 [360] [Dive into WinDbg Series: AudioSrv Audio Service Failure](https://www.anquanke.com/post/id/176343/)
- 2019.04 [freebuf] [How to Write ClrMD Plugins for WinDbg](https://www.freebuf.com/articles/network/198951.html)
- 2019.03 [aliyun] [Writing ClrMD Extensions for WinDbg and LLDB](https://xz.aliyun.com/t/4459)
- 2019.03 [offensive] [Development of a new Windows 10 KASLR Bypass (in One WinDBG Command)](https://www.offensive-security.com/vulndev/development-of-a-new-windows-10-kaslr-bypass-in-one-windbg-command/)
- 2019.02 [OALabs] [WinDbg Basics for Malware Analysis](https://www.youtube.com/watch?v=QuFJpH3My7A)
- 2019.01 [TheSourceLens] [Windows Internals - Processes Part 6 of 20 -  Process related windbg commands.](https://www.youtube.com/watch?v=Hg0xcpBc6R4)
- 2019.01 [TheSourceLens] [Introduction to Windbg Series 1 Part 23 - Time travellers tracing ( IDNA )](https://www.youtube.com/watch?v=Is8mZ5kklfw)
- 2018.09 [pediy] [Original: Analysing Paging Mechanisms with WinDbg Examples from the Software Debugging Series](https://bbs.pediy.com/thread-246768.htm)
- 2018.08 [pediy] [Translation: Introduction to Configuring WinDbg Kernel Debugging](https://bbs.pediy.com/thread-246228.htm)
- 2018.06 [pediy] [Original: Making WinDbg Break Before the Driver Entry Point](https://bbs.pediy.com/thread-228575.htm)
- 2018.05 [criteo] [Extending the new WinDbg, Part 3 – Embedding a C# interpreter](http://labs.criteo.com/2018/05/extending-new-windbg-part-3-embedding-c-interpreter/)
- 2018.04 [whereisk0shl] [Buffer Overflow Vulnerability in WinDbg's logviewer.exe](http://whereisk0shl.top/post/2018-04-26)
- 2018.04 [nettitude] [WinDbg: using pykd to dump private symbols](https://labs.nettitude.com/blog/windbg-using-pykd-to-dump-private-symbols/)
- 2018.02 [comae] [YARA scans in WinDbg](https://medium.com/p/b98851bf599b)


# <a id="11a59671b467a8cdbdd4ea9d5e5d9b51"></a>Android


***


## <a id="2110ded2aa5637fa933cc674bc33bf21"></a>Tools


### <a id="63fd2c592145914e99f837cecdc5a67c"></a>Recently Added1


- [**6101** stars][3m] [Java] [google/android-classyshark](https://github.com/google/android-classyshark) — Analyses Android/Java-based apps and games.
- [**6094** stars][5m] [Java] [qihoo360/replugin](https://github.com/qihoo360/replugin) — RePlugin: A flexible, stable, and easy-to-use Android plugin framework.
- [**5195** stars][19d] [Python] [mobsf/mobile-security-framework-mobsf](https://github.com/MobSF/Mobile-Security-Framework-MobSF) — Mobile Security Framework (MobSF), an automated, all-in-one framework for mobile application (Android/iOS/Windows) penetration testing, malware analysis, and security assessment. It supports static and dynamic analysis.
- [**5084**stars][15d] [HTML] [owasp/owasp-mstg](https://github.com/owasp/owasp-mstg) 关于移动App安全开发、测试和逆向的相近手册
- [**4882**stars][24d] [Java] [guardianproject/haven](https://github.com/guardianproject/haven) 通过Android应用和设备上的传感器保护自己的个人空间和财产而又不损害
- [**4776**stars][12d] [C++] [facebook/redex](https://github.com/facebook/redex) Android App字节码优化器
- [**4306**stars][15d] [Shell] [ashishb/android-security-awesome](https://github.com/ashishb/android-security-awesome) A collection of android security related resources
- [**3649**stars][2m] [C++] [anbox/anbox](https://github.com/anbox/anbox) 在常规GNU / Linux系统上引导完整的Android系统，基于容器
- [**2314**stars][1y] [Java] [csploit/android](https://github.com/csploit/android) cSploit - The most complete and advanced IT security professional toolkit on Android.
- [**2120**stars][9m] [Py] [linkedin/qark](https://github.com/linkedin/qark) 查找Android App的漏洞, 支持源码或APK文件
- [**2095**stars][10m] [jermic/android-crack-tool](https://github.com/jermic/android-crack-tool) 
- [**2051**stars][21d] [Py] [sensepost/objection](https://github.com/sensepost/objection) runtimemobile exploration
- [**2011**stars][8m] [Py] [fsecurelabs/drozer](https://github.com/FSecureLABS/drozer) The Leading Security Assessment Framework for Android.
- [**1976**stars][9d] [Java] [kyson/androidgodeye](https://github.com/kyson/androidgodeye) AndroidGodEye:A performance monitor tool , like "Android Studio profiler" for Android , you can easily monitor the performance of your app real time in pc browser
- [**1925**stars][7m] [Java] [fuzion24/justtrustme](https://github.com/fuzion24/justtrustme) An xposed module that disables SSL certificate checking for the purposes of auditing an app with cert pinning
- [**1430**stars][11m] [Java] [aslody/legend](https://github.com/aslody/legend) (Android)无需Root即可Hook Java方法的框架, 支持Dalvik和Art环境
- [**1417**stars][1m] [Java] [chrisk44/hijacker](https://github.com/chrisk44/hijacker) Aircrack, Airodump, Aireplay, MDK3 and Reaver GUI Application for Android
- [**1241**stars][3m] [Java] [whataa/pandora](https://github.com/whataa/pandora) an android library for debugging what we care about directly in app.
- [**1235**stars][2m] [Java] [find-sec-bugs/find-sec-bugs](https://github.com/find-sec-bugs/find-sec-bugs) The SpotBugs plugin for security audits of Java web applications and Android applications. (Also work with Kotlin, Groovy and Scala projects)
- [**1213**stars][2m] [JS] [megatronking/httpcanary](https://github.com/megatronking/httpcanary) A powerful capture and injection tool for the Android platform
- [**1208**stars][4m] [Java] [javiersantos/piracychecker](https://github.com/javiersantos/piracychecker) An Android library that prevents your app from being pirated / cracked using Google Play Licensing (LVL), APK signature protection and more. API 14+ required.
- [**1134**stars][1m] [Java] [huangyz0918/androidwm](https://github.com/huangyz0918/androidwm) 一个支持不可见数字水印（隐写术）的android图像水印库。
- [**885**stars][2m] [C] [504ensicslabs/lime](https://github.com/504ensicslabs/lime) LiME (formerly DMD) is a Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, such as those powered by Android. The tool supports acquiring memory either to the file system of the device or over the network. LiME is unique in that it is the first tool that allows full memory captures f…
- [**820**stars][11d] [proxymanapp/proxyman](https://github.com/proxymanapp/proxyman) Modern and Delightful HTTP Debugging Proxy for macOS, iOS and Android
- [**810**stars][4m] [Scala] [antox/antox](https://github.com/antox/antox) Android client for Project Tox - Secure Peer to Peer Messaging
- [**800**stars][3m] [sh4hin/androl4b](https://github.com/sh4hin/androl4b) 用于评估Android应用程序，逆向工程和恶意软件分析的虚拟机
- [**769**stars][1y] [C] [ele7enxxh/android-inline-hook](https://github.com/ele7enxxh/android-inline-hook) thumb16 thumb32 arm32 inlineHook in Android
- [**668**stars][2m] [doridori/android-security-reference](https://github.com/doridori/android-security-reference) A W.I.P Android Security Ref
- [**608**stars][7m] [JS] [vincentcox/stacoan](https://github.com/vincentcox/stacoan) StaCoAn is a crossplatform tool which aids developers, bugbounty hunters and ethical hackers performing static code analysis on mobile applications.
- [**559**stars][14d] [Shell] [owasp/owasp-masvs](https://github.com/owasp/owasp-masvs) OWASP 移动App安全标准
- [**546**stars][2m] [nordicsemiconductor/android-nrf-connect](https://github.com/nordicsemiconductor/android-nrf-connect) Documentation and issue tracker for nRF Connect for Android.
- [**541**stars][1y] [Java] [jaredrummler/apkparser](https://github.com/jaredrummler/apkparser) APK parser for Android
- [**527**stars][4m] [JS] [wooyundota/droidsslunpinning](https://github.com/wooyundota/droidsslunpinning) Android certificate pinning disable tools
- [**518**stars][4m] [Java] [megatronking/stringfog](https://github.com/megatronking/stringfog) 一款自动对字节码中的字符串进行加密Android插件工具
- [**511**stars][9d] [Java] [happylishang/cacheemulatorchecker](https://github.com/happylishang/cacheemulatorchecker) Android模拟器检测，检测Android模拟器 ，获取相对真实的IMEI AndroidId 序列号 MAC地址等，作为DeviceID，应对防刷需求等
- [**482**stars][2m] [JS] [lyxhh/lxhtoolhttpdecrypt](https://github.com/lyxhh/lxhtoolhttpdecrypt) Simple Android/iOS protocol analysis and utilization tool
- [**450**stars][12m] [Kotlin] [shadowsocks/kcptun-android](https://github.com/shadowsocks/kcptun-android) kcptun for Android.
- [**443**stars][1m] [TS] [shroudedcode/apk-mitm](https://github.com/shroudedcode/apk-mitm) 
- [**431**stars][13d] [C] [guardianproject/orbot](https://github.com/guardianproject/orbot) The Github home of Orbot: Tor on Android (Also available on gitlab!)
- [**426**stars][19d] [Py] [thehackingsage/hacktronian](https://github.com/thehackingsage/hacktronian) All in One Hacking Tool for Linux & Android
- [**412**stars][4m] [Java] [megatronking/netbare](https://github.com/megatronking/netbare) Net packets capture & injection library designed for Android
- [**409**stars][3m] [CSS] [angea/pocorgtfo](https://github.com/angea/pocorgtfo) a "Proof of Concept or GTFO" mirror with extra article index, direct links and clean PDFs.
- [**408**stars][1y] [Java] [testwhat/smaliex](https://github.com/testwhat/smaliex) A wrapper to get de-optimized dex from odex/oat/vdex.
- [**379**stars][6m] [Makefile] [crifan/android_app_security_crack](https://github.com/crifan/android_app_security_crack) 安卓应用的安全和破解
- [**379**stars][1y] [CSS] [nowsecure/secure-mobile-development](https://github.com/nowsecure/secure-mobile-development) A Collection of Secure Mobile Development Best Practices
- [**358**stars][5m] [b3nac/android-reports-and-resources](https://github.com/b3nac/android-reports-and-resources) A big list of Android Hackerone disclosed reports and other resources.
- [**358**stars][5m] [C] [the-cracker-technology/andrax-mobile-pentest](https://github.com/the-cracker-technology/andrax-mobile-pentest) ANDRAX The first and unique Penetration Testing platform for Android smartphones
- [**333**stars][25d] [Java] [datatheorem/trustkit-android](https://github.com/datatheorem/trustkit-android) Easy SSL pinning validation and reporting for Android.
- [**284**stars][9m] [Py] [micropyramid/forex-python](https://github.com/micropyramid/forex-python) Foreign exchange rates, Bitcoin price index and currency conversion using ratesapi.io
- [**267**stars][4m] [Py] [amimo/dcc](https://github.com/amimo/dcc) DCC (Dex-to-C Compiler) is method-based aot compiler that can translate DEX code to C code.
- [**265**stars][11d] [Py] [den4uk/andriller](https://github.com/den4uk/andriller) a collection of forensic tools for smartphones
- [**251**stars][10m] [C] [chef-koch/android-vulnerabilities-overview](https://github.com/chef-koch/android-vulnerabilities-overview) An small overview of known Android vulnerabilities
- [**234**stars][3m] [C] [grant-h/qu1ckr00t](https://github.com/grant-h/qu1ckr00t) A PoC application demonstrating the power of an Android kernel arbitrary R/W.
- [**234**stars][1y] [Ruby] [hahwul/droid-hunter](https://github.com/hahwul/droid-hunter) (deprecated) Android application vulnerability analysis and Android pentest tool
- [**229**stars][8m] [Java] [jieyushi/luffy](https://github.com/jieyushi/luffy) Android字节码插件，编译期间动态修改代码，改造添加全埋点日志采集功能模块，对常见控件进行监听处理
- [**225**stars][3m] [Java] [virb3/trustmealready](https://github.com/virb3/trustmealready) Disable SSL verification and pinning on Android, system-wide
- [**208**stars][26d] [C] [derrekr/fastboot3ds](https://github.com/derrekr/fastboot3ds) A homebrew bootloader for the Nintendo 3DS that is similar to android's fastboot.


### <a id="883a4e0dd67c6482d28a7a14228cd942"></a>Recently Added




### <a id="fa49f65b8d3c71b36c6924ce51c2ca0c"></a>HotFix


- [**14557**stars][13d] [Java] [tencent/tinker](https://github.com/tencent/tinker) Tinker is a hot-fix solution library for Android, it supports dex, library and resources update without reinstall apk.
- [**3462**stars][27d] [Java] [meituan-dianping/robust](https://github.com/meituan-dianping/robust) Robust is an Android HotFix solution with high compatibility and high stability. Robust can fix bugs immediately without a reboot.
- [**1117**stars][6m] [Java] [manbanggroup/phantom](https://github.com/manbanggroup/phantom)  唯一零 Hook 稳定占坑类 Android 热更新插件化方案


### <a id="ec395c8f974c75963d88a9829af12a90"></a>打包


- [**5080**stars][2m] [Java] [meituan-dianping/walle](https://github.com/meituan-dianping/walle) Android Signature V2 Scheme签名下的新一代渠道包打包神器


### <a id="767078c52aca04c452c095f49ad73956"></a>Collections




### <a id="17408290519e1ca7745233afea62c43c"></a>各ClassesApp


- [**12285**stars][11d] [Java] [signalapp/signal-android](https://github.com/signalapp/Signal-Android) A private messenger for Android.


### <a id="7f353b27e45b5de6b0e6ac472b02cbf1"></a>Xposed


- [**8756**stars][2m] [Java] [android-hacker/virtualxposed](https://github.com/android-hacker/virtualxposed) A simple app to use Xposed without root, unlock the bootloader or modify system image, etc.
- [**2559**stars][7m] [taichi-framework/taichi](https://github.com/taichi-framework/taichi) A framework to use Xposed module with or without Root/Unlock bootloader, supportting Android 5.0 ~ 10.0
- [**2034**stars][12d] [Java] [elderdrivers/edxposed](https://github.com/elderdrivers/edxposed) Elder driver Xposed Framework.
- [**1726**stars][1y] [Java] [ac-pm/inspeckage](https://github.com/ac-pm/inspeckage) Android Package Inspector - dynamic analysis with api hooks, start unexported activities and more. (Xposed Module)
- [**1655**stars][2m] [Java] [tiann/epic](https://github.com/tiann/epic) Dynamic java method AOP hook for Android(continution of Dexposed on ART), Supporting 4.0~10.0
- [**1296**stars][2m] [Java] [android-hacker/exposed](https://github.com/android-hacker/exposed) A library to use Xposed without root or recovery(or modify system image etc..).
- [**790**stars][8m] [Java] [blankeer/mdwechat](https://github.com/blankeer/mdwechat) 一个能让微信 Material Design 化的 Xposed 模块
- [**669**stars][12d] [Java] [ganyao114/sandhook](https://github.com/ganyao114/sandhook) Android ART Hook/Native Inline Hook/Single Instruction Hook - support 4.4 - 10.0 32/64 bit - Xposed API Compat
- [**478**stars][2m] [Java] [tornaco/x-apm](https://github.com/tornaco/x-apm) 应用管理 Xposed
- [**322**stars][1y] [C] [smartdone/dexdump](https://github.com/smartdone/dexdump) 一个用来快速脱一代壳的工具（稍微改下就可以脱类抽取那种壳）（Android）
- [**309**stars][1m] [bigsinger/androididchanger](https://github.com/bigsinger/androididchanger) Xposed Module for Changing Android Device Info
- [**309**stars][13d] [Java] [ganyao114/sandvxposed](https://github.com/ganyao114/sandvxposed) Xposed environment without root (OS 5.0 - 10.0)
- [**204**stars][1y] [C] [gtoad/android_inline_hook](https://github.com/gtoad/android_inline_hook) Build an so file to automatically do the android_native_hook work. Supports thumb-2/arm32 and ARM64 ! With this, tools like Xposed can do android native hook.


### <a id="50f63dce18786069de2ec637630ff167"></a>Packing&&Unpacking


- [**1793**stars][8m] [C++] [wrbug/dumpdex](https://github.com/wrbug/dumpdex) Android脱壳
- [**1465**stars][3m] [C++] [vaibhavpandeyvpz/apkstudio](https://github.com/vaibhavpandeyvpz/apkstudio) Open-source, cross platform Qt based IDE for reverse-engineering Android application packages.
- [**811**stars][4m] [C] [strazzere/android-unpacker](https://github.com/strazzere/android-unpacker) Android Unpacker presented at Defcon 22: Android Hacker Protection Level 0
- [**712**stars][2m] [YARA] [rednaga/apkid](https://github.com/rednaga/apkid) Android Application Identifier for Packers, Protectors, Obfuscators and Oddities - PEiD for Android
- [**366**stars][3m] [Java] [patrickfav/uber-apk-signer](https://github.com/patrickfav/uber-apk-signer) A cli tool that helps signing and zip aligning single or multiple Android application packages (APKs) with either debug or provided release certificates. It supports v1, v2 and v3 Android signing scheme has an embedded debug keystore and auto verifies after signing.
- [**322**stars][6m] [Shell] [1n3/reverseapk](https://github.com/1n3/reverseapk) Quickly analyze and reverse engineer Android packages


### <a id="596b6cf8fd36bc4c819335f12850a915"></a>HOOK


- [**1500**stars][27d] [C] [iqiyi/xhook](https://github.com/iqiyi/xhook) a PLT (Procedure Linkage Table) hook library for Android native ELF 
- [**1494**stars][9d] [C++] [jmpews/dobby](https://github.com/jmpews/Dobby) a lightweight, multi-platform, multi-architecture hook framework.
- [**804**stars][25d] [C++] [aslody/whale](https://github.com/aslody/whale) Hook Framework for Android/IOS/Linux/MacOS
- [**530**stars][7m] [Java] [aslody/andhook](https://github.com/asLody/AndHook) Android dynamic instrumentation framework
- [**361**stars][8m] [C] [turing-technician/fasthook](https://github.com/turing-technician/fasthook) Android ART Hook


### <a id="5afa336e229e4c38ad378644c484734a"></a>Emulator&&Emulators


- [**1492**stars][1y] [C++] [f1xpl/openauto](https://github.com/f1xpl/openauto) AndroidAuto headunit emulator
- [**532**stars][7m] [Java] [limboemu/limbo](https://github.com/limboemu/limbo) Limbo is a QEMU-based emulator for Android. It currently supports PC & ARM emulation for Intel x86 and ARM architecture. See our wiki
- [**471**stars][3m] [Java] [strazzere/anti-emulator](https://github.com/strazzere/anti-emulator) Android Anti-Emulator


### <a id="0a668d220ce74e11ed2738c4e3ae3c9e"></a>IDA




### <a id="bb9f8e636857320abf0502c19af6c763"></a>Debug&&Debugging


- [**10794**stars][1m] [Java] [konloch/bytecode-viewer](https://github.com/konloch/bytecode-viewer) A Java 8+ Jar & Android APK Reverse Engineering Suite (Decompiler, Editor, Debugger & More)
- [**6762**stars][10m] [Java] [amitshekhariitbhu/android-debug-database](https://github.com/amitshekhariitbhu/android-debug-database) A library for debugging android databases and shared preferences - Make Debugging Great Again


### <a id="f975a85510f714ec3cc2551e868e75b8"></a>Malware&&Malware


- [**429**stars][4m] [Shell] [ashishb/android-malware](https://github.com/ashishb/android-malware) Collection of android malware samples
- [**347**stars][3m] [Java] [droidefense/engine](https://github.com/droidefense/engine) Droidefense: Advance Android Malware Analysis Framework


### <a id="1d83ca6d8b02950be10ac8e4b8a2d976"></a>Obfuscate&&Obfuscation


- [**3078**stars][2m] [Java] [calebfenton/simplify](https://github.com/calebfenton/simplify) Generic Android Deobfuscator
- [**294**stars][4m] [C] [shadowsocks/simple-obfs-android](https://github.com/shadowsocks/simple-obfs-android) A simple obfuscating tool for Android


### <a id="6d2b758b3269bac7d69a2d2c8b45194c"></a>ReverseEngineering


- [**9285** stars][1m] [Java] [ibotpeaches/apktool](https://github.com/ibotpeaches/apktool) — A tool for reverse engineering Android APK files.
- [**2053**stars][1m] [Java] [genymobile/gnirehtet](https://github.com/genymobile/gnirehtet) Gnirehtet provides reverse tethering for Android
- [**585** stars][3m] [C++] [secrary/andromeda](https://github.com/secrary/andromeda) — Interactive reverse-engineering tool for Android applications. This project is no longer maintained.
- [**545** stars][20d] [maddiestone/androidappre](https://github.com/maddiestone/androidappre) — Android application reverse-engineering workshop.
- [**267** stars][10m] [Dockerfile] [cryptax/androidre](https://github.com/cryptax/androidre) — Docker container for Android reverse engineering.
- [**246**stars][28d] [C++] [strazzere/android-scripts](https://github.com/strazzere/android-scripts) Android逆向脚本收集
    - 重复区段: [IDA->插件->Android](#66052f824f5054aa0f70785a2389a478) |




***


## <a id="f0493b259e1169b5ddd269b13cfd30e6"></a>Articles and Videos


- 2019.12 [aliyun] [Security Hardening for Android Smart-Terminal Systems (Part 1)](https://xz.aliyun.com/t/6852)
- 2019.11 [venus] [Android Ransomware Analysis (Part 1)](https://paper.seebug.org/1085/)


# <a id="069664f347ae73b1370c4f5a2ec9da9f"></a>Apple&&iOS&&iXxx


***


## <a id="830f40713cef05f0665180d840d56f45"></a>Mach-O


### <a id="9b0f5682dc818c93c4de3f46fc3f43d0"></a>Tools


- [**2540** stars][10m] [Objective-C] [nygard/class-dump](https://github.com/nygard/class-dump) — Generates Objective-C header files from Mach-O files.
- [**2140**stars][2m] [Py] [jonathansalwan/ropgadget](https://github.com/jonathansalwan/ropgadget) This tool lets you search your gadgets on your binaries to facilitate your ROP exploitation. ROPgadget supports ELF, PE and Mach-O format on x86, x64, ARM, ARM64, PowerPC, SPARC and MIPS architectures.
- [**399** stars][2m] [Logos] [limneos/classdump-dyld](https://github.com/limneos/classdump-dyld) — Dumps classes from Mach-O files without extracting them from `dyld_shared_cache`.
- [**265** stars][8m] [Objective-C] [devaukz/macho-kit](https://github.com/devaukz/macho-kit) — A C/Objective-C library for parsing Mach-O files.


### <a id="750700dcc62fbd83e659226db595b5cc"></a>Articles


- 2017.11 [pnfsoftware] [Having Fun with Obfuscated Mach-O Files](https://www.pnfsoftware.com/blog/having-fun-with-obfuscated-mach-o-files/)
- 2017.03 [lse] [Playing with Mach-O binaries and dyld](https://blog.lse.epita.fr:443/articles/82-playing-with-mach-os-and-dyld.html)
- 2017.03 [lse] [Playing with Mach-O binaries and dyld](https://blog.lse.epita.fr/articles/82-playing-with-mach-os-and-dyld.html)
- 2017.02 [venus] [A Mach-O Unpacking Technique](https://paper.seebug.org/202/)
- 2016.05 [turingh] [Analysis of the nlist Mach-O File Relocation Information Data Structure](http://turingh.github.io/2016/05/24/nlist-Mach-O%E6%96%87%E4%BB%B6%E9%87%8D%E5%AE%9A%E5%90%91%E4%BF%A1%E6%81%AF%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E5%88%86%E6%9E%90/)
- 2016.05 [pediy] [Original: Initial Notes on Learning Mach-O (Source Code Included)](https://bbs.pediy.com/thread-209957.htm)
- 2016.03 [turingh] [Analysis of the macOS Kernel's Mach-O Loading Process](http://turingh.github.io/2016/03/30/OSX%E5%86%85%E6%A0%B8%E5%8A%A0%E8%BD%BDmach-o%E6%B5%81%E7%A8%8B%E5%88%86%E6%9E%90/)
- 2016.03 [pediy] [Original: A Brief Analysis of Mach-O Dynamic Linking (Lazy Binding)](https://bbs.pediy.com/thread-208455.htm)
- 2016.03 [turingh] [Knowledge of Mach-O Dynamic Linking](http://turingh.github.io/2016/03/10/Mach-O%E7%9A%84%E5%8A%A8%E6%80%81%E9%93%BE%E6%8E%A5/)
- 2016.03 [pediy] [Original: Analysis of the Mach-O File Format](https://bbs.pediy.com/thread-208357.htm)
- 2016.03 [turingh] [Analysis of the Mach-O File Format](http://turingh.github.io/2016/03/07/mach-o%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F%E5%88%86%E6%9E%90/)
- 2016.03 [pediy] [Original: Analysing How dyld Loads Mach-O Files](https://bbs.pediy.com/thread-208255.htm)
- 2016.03 [turingh] [A Brief Analysis of Mach-O Loading in dyld](http://turingh.github.io/2016/03/01/dyld%E4%B8%ADmacho%E5%8A%A0%E8%BD%BD%E7%9A%84%E7%AE%80%E5%8D%95%E5%88%86%E6%9E%90/)
- 2014.09 [pediy] [Original: Notes on Learning the Mach-O File Format](https://bbs.pediy.com/thread-192657.htm)
- 2014.09 [cerbero] [Stripping symbols from a Mach-O](http://cerbero-blog.com/?p=1483)
- 2014.08 [secureallthethings] [Patching the Mach-o Format the Simple and Easy Way](http://secureallthethings.blogspot.com/2014/08/patching-mach-o-format-simple-and-easy.html)
- 2013.06 [cerbero] [Mach-O support (including Universal Binaries and Apple Code Signatures)](http://cerbero-blog.com/?p=1139)
- 2013.05 [volatility] [MoVP II - 1.1 - Mach-O Address Space](https://volatility-labs.blogspot.com/2013/05/movp-ii-11-mach-o-address-space.html)
- 2013.03 [reverse] [OS.X/Boubou – Mach-O infector PoC source code](https://reverse.put.as/2013/03/05/os-xboubou-mach-o-infector-poc-source-code/)
- 2012.02 [reverse] [A little more fun with Mach-O headers: adding and spoofing a constructor](https://reverse.put.as/2012/02/06/a-little-more-fun-with-mach-o-headers-adding-and-spoofing-a-constructor/)




***


## <a id="bba00652bff1672ab1012abd35ac9968"></a>Jailbreaking


### <a id="ff19d5d94315d035bbcb3ef0c348c75b"></a>Tools


- [**5451** stars][3m] [Python] [axi0mx/ipwndfu](https://github.com/axi0mx/ipwndfu) — Open-source jailbreaking tool for many iOS devices.
- [**5390** stars][6m] [C] [pwn20wndstuff/undecimus](https://github.com/pwn20wndstuff/undecimus) — unc0ver jailbreak for iOS 11.0–12.4.
- [**4248** stars][8m] [Objective-C] [alonemonkey/monkeydev](https://github.com/alonemonkey/monkeydev) — Supports CaptainHook tweaks, Logos tweaks, command-line tools and patching iOS applications without jailbreaking.
- [**3221** stars][5m] [Objective-C] [naituw/ipapatch](https://github.com/naituw/ipapatch) — Patches iOS applications without jailbreaking.
- [**1193**stars][15d] [JS] [alonemonkey/frida-ios-dump](https://github.com/alonemonkey/frida-ios-dump) pull decrypted ipa from jailbreak device
    - 重复区段: [DBI->Frida->工具->新添加的](#54836a155de0c15b56f43634cd9cfecf) |
- [**404** stars][1y] [C] [coalfire-research/ios-11.1.2-15b202-jailbreak](https://github.com/coalfire-research/ios-11.1.2-15b202-jailbreak) — Jailbreak for iOS 11.1.2 (15B202).
- [**287** stars][7m] [Shell] [0ki/mikrotik-tools](https://github.com/0ki/mikrotik-tools) — Universal jailbreaking tool for MikroTik devices.
- [**237** stars][11m] [C] [geosn0w/osirisjailbreak12](https://github.com/geosn0w/osirisjailbreak12) — An incomplete jailbreak for iOS 12.0–12.1.2 using CVE-2019-6225, by GeoSn0w (FCE365).


### <a id="cbb847a025d426a412c7cd5d8a2332b5"></a>Articles


- 2019.10 [talosintelligence] [Checkrain fake iOS jailbreak leads to click fraud](https://blog.talosintelligence.com/2019/10/checkrain-click-fraud.html)
- 2019.08 [elcomsoft] [Why iOS 12.4 Jailbreak Is a Big Deal for the Law Enforcement](https://blog.elcomsoft.com/2019/08/why-ios-12-4-jailbreak-is-a-big-deal-for-the-law-enforcement/)
- 2019.05 [elcomsoft] [Step by Step Guide to iOS Jailbreaking and Physical Acquisition](https://blog.elcomsoft.com/2019/05/step-by-step-guide-to-ios-jailbreaking-and-physical-acquisition/)
- 2019.02 [securityinnovation] [iOS 12 Jailbreak](https://blog.securityinnovation.com/jailbreak)
- 2019.02 [elcomsoft] [iOS 12 Rootless Jailbreak](https://blog.elcomsoft.com/2019/02/ios-12-rootless-jailbreak/)
- 2019.01 [] [IPC Voucher UaF Remote Jailbreak Stage 2](http://blogs.360.cn/post/IPC%20Voucher%20UaF%20Remote%20Jailbreak%20Stage%202.html)
- 2019.01 [] [IPC Voucher UaF Remote Jailbreak Stage 2 (EN)](http://blogs.360.cn/post/IPC%20Voucher%20UaF%20Remote%20Jailbreak%20Stage%202%20(EN).html)
- 2018.07 [elcomsoft] [Using iOS 11.2-11.3.1 Electra Jailbreak for iPhone Physical Acquisition](https://blog.elcomsoft.com/2018/07/electra-jailbreak-ios-11-2-11-3-1-iphone-physical-acquisition/)
- 2017.12 [venus] [GreatiOSJailbreakMaterial - Only List the Most Useful Materials Here!](https://paper.seebug.org/482/)
- 2015.10 [welivesecurity] [New YiSpecter malware attacks iOS devices without jailbreak](https://www.welivesecurity.com/2015/10/06/new-yispecter-malware-attacks-ios-devices-without-jailbreak/)
- 2011.07 [sans] [Jailbreakme Takes Advantage of 0-day PDF Vuln in Apple iOS Devices](https://isc.sans.edu/forums/diary/Jailbreakme+Takes+Advantage+of+0day+PDF+Vuln+in+Apple+iOS+Devices/11185/)
- 2010.09 [securelist] [iPhone Jailbreaking, Greenpois0n and SHAtter Trojans](https://securelist.com/iphone-jailbreaking-greenpois0n-and-shatter-trojans/29748/)
- 2010.08 [trendmicro] [The Security Implications of iOS Jailbreaking](https://blog.trendmicro.com/trendlabs-security-intelligence/the-security-implications-of-ios-jailbreaking/)
- 2010.08 [trendmicro] [Online iPhone Jailbreak Uses iOS Vulnerabilities](https://blog.trendmicro.com/trendlabs-security-intelligence/online-iphone-jailbreak-uses-ios-vulnerabilities/)




***


## <a id="004d0b9e325af207df8e1ca61af7b721"></a>LLDB


### <a id="c20772abc204dfe23f3e946f8c73dfda"></a>Tools


- [**8031** stars][3m] [Python] [facebook/chisel](https://github.com/facebook/chisel) — Collection of LLDB commands to assist with debugging iOS applications.
- [**784** stars][3m] [C++] [nodejs/llnode](https://github.com/nodejs/llnode) — LLDB plugin for Node.js and V8. It allows inspection of JavaScript states to understand Node.js processes and core dumps.
- [**636** stars][2m] [C++] [apple/swift-lldb](https://github.com/apple/swift-lldb) — LLDB version that supports the Swift programming language and REPL.
- [**492** stars][28d] [Rust] [vadimcn/vscode-lldb](https://github.com/vadimcn/vscode-lldb) — Native debugger extension for VS Code based on LLDB.
- [**388** stars][2m] [C++] [llvm-mirror/lldb](https://github.com/llvm-mirror/lldb) — Mirror of the official LLDB Git repository.


### <a id="86eca88f321a86712cc0a66df5d72e56"></a>Articles


- 2019.11 [4hou] [LLDBagility: A Practical macOS Kernel Debugging Tool](https://www.4hou.com/tools/21472.html)
- 2019.11 [reverse] [How to make LLDB a real debugger](https://reverse.put.as/2019/11/19/how-to-make-lldb-a-real-debugger/)
- 2019.08 [trendmicro] [LLDBFuzzer: Debugging and Fuzzing the Apple Kernel with LLDB Script](https://blog.trendmicro.com/trendlabs-security-intelligence/lldbfuzzer-debugging-and-fuzzing-the-apple-kernel-with-lldb-script/)
- 2019.06 [quarkslab] [LLDBagility: practical macOS kernel debugging](https://blog.quarkslab.com/lldbagility-practical-macos-kernel-debugging.html)
- 2018.05 [freebuf] [How to use LLDB to debug applications on Electra-jailbroken devices](http://www.freebuf.com/articles/terminal/173218.html)
- 2018.01 [reverse] [lldbinit - Improving LLDB](https://reverse.put.as/2018/01/15/lldbinit-improving-lldb/)
- 2017.10 [venus] [Native LLDB(v3.8) for iOS](https://paper.seebug.org/419/)
- 2017.10 [pediy] [[Original] Trying Proteas's Native LLDB on iOS 9.3.5 for iPhone 4s](https://bbs.pediy.com/thread-221926.htm)
- 2017.07 [pediy] [[Share] Compiling LLDB on macOS](https://bbs.pediy.com/thread-219717.htm)
- 2016.09 [pediy] [[Original] How to use LLDB (study notes)](https://bbs.pediy.com/thread-212731.htm)
- 2015.01 [pediy] [[Original] Fixing the Thumb disassembly issue in LLDB 310 and later versions](https://bbs.pediy.com/thread-196735.htm)
- 2014.08 [3xp10it] [lldb命令](http://3xp10it.cc/%E4%BA%8C%E8%BF%9B%E5%88%B6/2017/12/25/lldb%E5%91%BD%E4%BB%A4/)
- 2014.08 [3xp10it] [lldb命令](http://3xp10it.cc/%E4%BA%8C%E8%BF%9B%E5%88%B6/2017/12/25/lldb%E5%91%BD%E4%BB%A4/)
- 2014.05 [pediy] [[Original] gikdbg v1.1 arrives with LLDB—looking for beta testers!](https://bbs.pediy.com/thread-187657.htm)
- 2013.03 [it] [iTunes debugging disabling ptrace with LLDB](https://blog.it-securityguard.com/itunes-exploit-development/)
- 2005.08 [pediy] [[Original] A few words about OllyDbg](https://bbs.pediy.com/thread-16177.htm)
- 2004.06 [pediy] [Using OllyDbg to crack and analyse an OCX control](https://bbs.pediy.com/thread-2134.htm)




***


## <a id="977cef2fc942ac125fa395254ab70eea"></a>XCode


### <a id="7037d96c1017978276cb920f65be2297"></a>Tools


- [**6203** stars][3m] [ObjC] [johnno1962/injectionforxcode](https://github.com/johnno1962/injectionforxcode) Runtime code injection for Objective-C and Swift
- [**2057** stars][19d] [ObjC] [ios-control/ios-deploy](https://github.com/ios-control/ios-deploy) Install and debug iPhone apps from the command line without using Xcode
- [**1606** stars][2m] [Swift] [indragiek/inappviewdebugger](https://github.com/indragiek/inappviewdebugger) A UIView debugger, similar to Reveal or Xcode, that can be embedded in an app for on-device view debugging
- [**1409** stars][1m] [Swift] [johnno1962/injectioniii](https://github.com/johnno1962/injectioniii) A rewrite of Injection for Xcode, implemented mostly in Swift 4
- [**572** stars][1m] [ObjC] [hdb-li/lldebugtool](https://github.com/hdb-li/lldebugtool) LLDebugTool is a debugging tool for developers and testers. It helps analyse and inspect data when Xcode is unavailable.
- [**384** stars][3m] [JS] [johnno1962/xprobeplugin](https://github.com/johnno1962/xprobeplugin) Live memory browser for apps and Xcode


### <a id="a2d228a68b40162953d3d482ce009d4e"></a>Articles


- 2019.07 [pewpewthespells] [Using Xcode Targets](https://pewpewthespells.com/blog/using_xcode_targets.pdf)
- 2019.07 [pewpewthespells] [Xcode Build Locations](https://pewpewthespells.com/blog/xcode_build_locations.pdf)
- 2019.07 [pewpewthespells] [Migrating Code Signing Configurations to Xcode 8](https://pewpewthespells.com/blog/migrating_code_signing.pdf)
- 2019.06 [pewpewthespells] [Xcode SDKs](https://pewpewthespells.com/blog/sparse_sdks.pdf)
- 2019.04 [pewpewthespells] [Xcode Build Settings Reference](https://pewpewthespells.com/blog/buildsettings.pdf)
- 2019.03 [pewpewthespells] [Xcode DerivedData Hashes](https://pewpewthespells.com/blog/xcode_deriveddata_hashes.pdf)
- 2019.02 [pewpewthespells] [The Xcode Build System](https://pewpewthespells.com/blog/xcode_build_system.pdf)
- 2019.02 [pewpewthespells] [Managing Xcode](https://pewpewthespells.com/blog/managing_xcode.pdf)
- 2019.02 [hakin9] [Building an iOS App Without Xcode’s Build System by Vojta Stavik](https://hakin9.org/building-an-ios-app-without-xcodes-build-system/)
- 2018.11 [CodeColorist] [Xcode Instruments for iOS: reversing and abuse](https://medium.com/p/dd73d72d87e2)
- 2018.06 [applehelpwriter] [Xcode 10: where did snippets go?](https://applehelpwriter.com/2018/06/10/xcode-10-where-did-snippets-go/)
- 2018.05 [freecodecamp] [How to convert your Xcode plugins to Xcode extensions](https://medium.com/p/ac90f32ae0e3)
- 2017.07 [pediy] [[Original] A modified version of MonkeyDev based on iOSOpenDev, tested with the latest Theos and Xcode 9](https://bbs.pediy.com/thread-219003.htm)
- 2017.06 [alonemonkey] [0x01: Debugging an LLVM Pass in Xcode](http://www.alonemonkey.com/2017/06/02/writing-an-llvm-pass/)
- 2017.03 [360] [XcodeGhost may return: malicious code found in numerous Google Play apps](https://www.anquanke.com/post/id/85636/)
- 2016.05 [rachelbythebay] [Go upgrade Xcode.  Fix your git security hole.](http://rachelbythebay.com/w/2016/05/05/xcode/)
- 2015.12 [metricpanda] [Compiling NASM Assembly with Xcode in a C/C++ Project](https://metricpanda.com/compiling-nasm-with-xcode-in-a-cpp-project)
- 2015.12 [360] [Xcode 7 Bitcode workflow and security assessment](https://www.anquanke.com/post/id/83125/)
- 2015.12 [freebuf] [Xcode 7 Bitcode workflow and security assessment](http://www.freebuf.com/articles/others-articles/89806.html)
- 2015.11 [freebuf] [XcodeGhost S: another wave of impact caused by a variant](http://www.freebuf.com/news/84064.html)




***


## <a id="58cd9084afafd3cd293564c1d615dd7f"></a>Tools


### <a id="d0108e91e6863289f89084ff09df39d0"></a>Recently Added


- [**10966** stars][10d] [ObjC] [flipboard/flex](https://github.com/flipboard/flex) An in-app debugging and exploration tool for iOS
- [**5775** stars][4m] [ObjC] [square/ponydebugger](https://github.com/square/ponydebugger) Remote network and data debugging for native iOS apps using Chrome Developer Tools
- [**4663** stars][1m] [C] [google/ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) A DevTools proxy using the Chrome Remote Debugging Protocol for Safari Remote Web Inspector on iOS devices
- [**4397** stars][12d] [Swift] [signalapp/signal-ios](https://github.com/signalapp/Signal-iOS) A private messaging app for iOS
- [**3686** stars][4m] [C] [facebook/fishhook](https://github.com/facebook/fishhook) A library for dynamically rebinding symbols in Mach-O binaries running on iOS
- [**3414** stars][2m] [icodesign/potatso](https://github.com/icodesign/Potatso) An iOS client that implements different proxies using the NetworkExtension framework in iOS 10 and later
- [**3327** stars][3m] [Swift] [yagiz/bagel](https://github.com/yagiz/bagel) A small native network debugging tool for iOS
- [**3071** stars][10m] [JS] [jipegit/osxauditor](https://github.com/jipegit/osxauditor) A free computer forensics tool for Mac OS X
- [**2867** stars][12d] [ObjC] [facebook/idb](https://github.com/facebook/idb) A flexible command-line interface for automating iOS simulators and devices
- [**2795** stars][24d] [Swift] [kasketis/netfox](https://github.com/kasketis/netfox) A lightweight iOS/macOS network debugging library that requires only one line of setup
- [**2753** stars][1m] [Makefile] [theos/theos](https://github.com/theos/theos) A cross-platform tool suite for building and deploying software for iOS and other platforms
- [**2733** stars][26d] [ObjC] [dantheman827/ios-app-signer](https://github.com/dantheman827/ios-app-signer) A macOS app that can sign or re-sign apps and bundle them into IPA files ready for installation on iOS devices
- [**2708** stars][2m] [ObjC] [kjcracks/clutch](https://github.com/kjcracks/clutch) A fast iOS executable dumper
- [**1801** stars][1y] [aozhimin/ios-monitor-platform](https://github.com/aozhimin/ios-monitor-platform)
- [**1695** stars][6m] [Py] [yelp/osxcollector](https://github.com/yelp/osxcollector) A forensic evidence collection and analysis toolkit for OS X
- [**1683** stars][2m] [Swift] [pmusolino/wormholy](https://github.com/pmusolino/wormholy) Network debugging for iOS
- [**1642** stars][7m] [Objective-C++] [tencent/oomdetector](https://github.com/tencent/oomdetector) An iOS memory-monitoring component that supports out-of-memory monitoring, allocation monitoring, memory-leak detection and more
- [**1630** stars][1m] [ivrodriguezca/re-ios-apps](https://github.com/ivrodriguezca/re-ios-apps) A completely free, open-source online course on reverse engineering iOS applications
- [**1442** stars][28d] [ObjC] [nabla-c0d3/ssl-kill-switch2](https://github.com/nabla-c0d3/ssl-kill-switch2) A black-box tool for disabling SSL certificate validation, including certificate pinning, in iOS and OS X apps
- [**1299** stars][6m] [JS] [feross/spoof](https://github.com/feross/spoof) Easily spoof your MAC address on macOS, Windows and Linux
- [**1291** stars][1m] [JS] [icymind/vrouter](https://github.com/icymind/vrouter) A project built with VirtualBox and OpenWrt to provide transparent proxying on macOS and Windows
- [**1253** stars][2m] [Vue] [chaitin/passionfruit](https://github.com/chaitin/passionfruit) A feature-rich black-box assessment tool for iOS apps with a built-in web-based GUI
- [**1252** stars][17d] [michalmalik/osx-re-101](https://github.com/michalmalik/osx-re-101) A collection of OS X/iOS reverse-engineering resources
- [**1239** stars][8d] [C] [datatheorem/trustkit](https://github.com/datatheorem/trustkit) SSL pinning validation and reporting for iOS, macOS, tvOS and watchOS
- [**1215** stars][16d] [YARA] [horsicq/detect-it-easy](https://github.com/horsicq/detect-it-easy) A program for identifying file types on Windows, Linux and macOS
- [**1113** stars][1y] [ObjC] [neoneggplant/eggshell](https://github.com/neoneggplant/eggshell) A remote administration tool for iOS, macOS and Linux
- [**1001** stars][2m] [ObjC] [lmirosevic/gbdeviceinfo](https://github.com/lmirosevic/gbdeviceinfo) Detects the current iOS or Mac OS X device's hardware, software and display information at runtime
- [**907** stars][4m] [ObjC] [ptoomey3/keychain-dumper](https://github.com/ptoomey3/keychain-dumper) A tool for checking which Keychain items may be accessible to an attacker after an iOS device is jailbroken
- [**866** stars][16d] [ObjC] [meitu/mthawkeye](https://github.com/meitu/mthawkeye) iOS profiling and debugging tools for memory leaks, OOM, ANR, stalls, networking, OpenGL and time profiling
- [**840** stars][9d] [JS] [cypress-io/cypress-example-recipes](https://github.com/cypress-io/cypress-example-recipes) Recipes for testing common scenarios with Cypress
- [**796** stars][13d] [Shell] [aqzt/kjyw](https://github.com/aqzt/kjyw) A quick operations and maintenance toolkit based on Shell and Python, containing common scripts for quickly installing Nginx, MySQL, PHP, Redis, Nagios and other tools
- [**662** stars][1y] [Py] [deepzec/bad-pdf](https://github.com/deepzec/bad-pdf) Creates malicious PDF files designed to steal NTLMv1/NTLMv2 hashes from Windows machines
- [**651** stars][9m] [ObjC] [chenxiancai/stcobfuscator](https://github.com/chenxiancai/stcobfuscator) An automated global code-obfuscation tool for iOS. It also supports code in CocoaPods components and avoids obfuscating hard-coded methods, static-library methods and system-library methods
- [**604** stars][2m] [siguza/ios-resources](https://github.com/siguza/ios-resources) Useful resources for iOS hacking
- [**500** stars][27d] [Swift] [google/science-journal-ios](https://github.com/google/science-journal-ios) Uses mobile-device sensors to conduct science experiments, helping users explore how the world works with their phones
- [**482** stars][1y] [Swift] [icepa/icepa](https://github.com/icepa/icepa) A system-wide VPN Tor client for iOS
- [**478** stars][15d] [pixelcyber/thor](https://github.com/pixelcyber/thor) An HTTP sniffer and capture tool for iOS network debugging and inspection
- [**471** stars][8m] [C++] [everettjf/machoexplorer](https://github.com/everettjf/machoexplorer) A Mach-O file viewer for Windows and macOS
- [**462** stars][15d] [Java] [dsheirer/sdrtrunk](https://github.com/dsheirer/sdrtrunk) A cross-platform Java application for decoding, monitoring, recording and streaming trunked mobile and related radio protocols using software-defined radios (SDRs). Website:
- [**430** stars][11m] [captainarash/the_holy_book_of_x86](https://github.com/captainarash/the_holy_book_of_x86) A simple guide to x86 architecture, assembly, memory management, paging, segmentation, SMM and BIOS
- [**396** stars][4m] [ansjdnakjdnajkd/ios](https://github.com/ansjdnakjdnajkd/ios) A collection of useful tools for iOS penetration testing
- [**382** stars][11m] [C] [coolstar/electra1131](https://github.com/coolstar/electra1131) Electra for iOS 11.0–11.3.1
- [**375** stars][29d] [Swift] [justeat/justlog](https://github.com/justeat/justlog) An advanced iOS logging library supporting console, file and remote Logstash logging over TCP, with support for logz.io
- [**371** stars][18d] [Shell] [matthewpierson/1033-ota-downgrader](https://github.com/matthewpierson/1033-ota-downgrader) A tool for downgrading supported iPhone 5s, iPad Air and iPad Mini 2 devices to iOS 10.3.3 using OTA blobs and checkm8
- [**349** stars][19d] [C] [jedisct1/swift-sodium](https://github.com/jedisct1/swift-sodium) Safe and easy-to-use cryptography for iOS and macOS
- [**346** stars][4m] [TS] [bacher09/pwgen-for-bios](https://github.com/bacher09/pwgen-for-bios) A BIOS password generator
- [**340** stars][3m] [C++] [trailofbits/cb-multios](https://github.com/trailofbits/cb-multios) DARPA challenge sets for Linux, Windows and macOS
- [**322** stars][2m] [ObjC] [auth0/simplekeychain](https://github.com/auth0/simplekeychain) A Keychain helper that simplifies storing and retrieving values from the iOS Keychain
- [**310** stars][28d] [Swift] [securing/iossecuritysuite](https://github.com/securing/iossecuritysuite) An iOS security and anti-tampering Swift library
- [**263** stars][14d] [ObjC] [strongbox-password-safe/strongbox](https://github.com/strongbox-password-safe/strongbox) A KeePass/Password Safe client for iOS and OS X
- [**247** stars][1m] [C++] [s0uthwest/futurerestore](https://github.com/s0uthwest/futurerestore) An iOS upgrade and downgrade tool that uses SHSH blobs
- [**244** stars][7m] [JS] [we11cheng/wcshadowrocket](https://github.com/we11cheng/wcshadowrocket) An iOS Shadowrocket project (app decryption and re-signing; for reference only; adding nodes has issues). The source code for another proxy project, Potatso, is referenced separately.
- [**239** stars][1y] [ObjC] [lmirosevic/gbping](https://github.com/lmirosevic/gbping) A highly accurate ICMP ping controller for iOS
- [**238** stars][4m] [Swift] [shadowsocksr-live/ishadowsocksr](https://github.com/shadowsocksr-live/ishadowsocksr) ShadowsocksR for iOS, derived from another project
- [**223** stars][12m] [AppleScript] [lifepillar/csvkeychain](https://github.com/lifepillar/csvkeychain) Imports and exports data between Apple Keychain and plain CSV files
- [**219** stars][6m] [ObjC] [rickyzhang82/tethering](https://github.com/rickyzhang82/tethering) A proxy and DNS server for iOS
- [**213** stars][8m] [C] [owasp/igoat](https://github.com/owasp/igoat) OWASP iGoat, a learning tool for iOS app penetration testing and security by Swaroop Yermalkar
- [**211** stars][13d] [TS] [bevry/getmac](https://github.com/bevry/getmac) Gets the MAC address of the current machine using Node.js
- [**203** stars][5m] [Py] [googleprojectzero/ios-messaging-tools](https://github.com/googleprojectzero/ios-messaging-tools) Several tools used by Google Project Zero to test iPhone messaging
- [**200** stars][6m] [PS] [mkellerman/invoke-commandas](https://github.com/mkellerman/invoke-commandas) Runs commands as System, Interactive, GMSA or a user on a local or remote machine and returns PowerShell objects




***


## <a id="c97bbe32bbd26c72ceccb43400e15bf1"></a>Articles & Videos


### <a id="d4425fc7c360c2ff324be718cf3b7a78"></a>Recently Added






# <a id="0ae4ddb81ff126789a7e08b0768bd693"></a>Cuckoo


***


## <a id="5830a8f8fb3af1a336053d84dd7330a1"></a>Tools


### <a id="f2b5c44c2107db2cec6c60477c6aa1d0"></a>Recently Added


- [**4042** stars][3m] [JS] [cuckoosandbox/cuckoo](https://github.com/cuckoosandbox/cuckoo) Cuckoo Sandbox is an automated dynamic malware analysis system.
- [**308** stars][2m] [Py] [hatching/vmcloak](https://github.com/hatching/vmcloak) Automatically creates and configures virtual machines for Cuckoo Sandbox.
- [**238** stars][7m] [Py] [cuckoosandbox/community](https://github.com/cuckoosandbox/community) Community-contributed modules and signatures.
- [**236** stars][4m] [Py] [brad-sp/cuckoo-modified](https://github.com/brad-sp/cuckoo-modified) A modified version of Cuckoo.
- [**225** stars][1y] [PHP] [cuckoosandbox/monitor](https://github.com/cuckoosandbox/monitor) The new Cuckoo Monitor.
- [**220** stars][4m] [Shell] [blacktop/docker-cuckoo](https://github.com/blacktop/docker-cuckoo) Dockerfile for Cuckoo Sandbox.




***


## <a id="ec0a441206d9a2fe1625dce0a679d466"></a>Articles and Videos


- 2019.04 [eforensicsmag] [How to Integrate RSA Malware Analysis with Cuckoo Sandbox | By Luiz Henrique Borges](https://eforensicsmag.com/how-to-integrate-rsa-malware-analysis-with-cuckoo-sandbox-by-luiz-henrique-borges/)
- 2019.02 [thehive] [Cortex-Analyzers 1.15.3 get ready for  URLhaus and Cuckoo](https://blog.thehive-project.org/2019/02/26/cortex-analyzers-1-15-3-get-ready-for-urlhaus-and-cuckoo/)
- 2018.07 [360] [Analysis of an IRC bot's evasive techniques against the Cuckoo Sandbox](https://www.anquanke.com/post/id/152631/)
- 2018.05 [trustedsec] [Malware Analysis is for the (Cuckoo) Birds – Working with Proxmox](https://www.trustedsec.com/2018/05/working-with-proxmox/)
- 2018.05 [trustedsec] [Protected: Malware Analysis is for the (Cuckoo) Birds](https://www.trustedsec.com/2018/05/malware-cuckoo-1/)
- 2018.05 [trustedsec] [Protected: Malware Analysis is for the (Cuckoo) Birds – Cuckoo Installation Notes for Debian](https://www.trustedsec.com/2018/05/malware-cuckoo-2/)
- 2018.04 [ly0n] [Automating malware analysis, cuckoo api + postfix](https://paumunoz.tech/2018/04/25/automating-malware-analysis-cuckoo-api-postfix/)
- 2018.04 [ly0n] [Automating malware analysis, cuckoo api + postfix](http://ly0n.me/2018/04/25/automating-malware-analysis-cuckoo-api-postfix/)
- 2018.04 [nviso] [Painless Cuckoo Sandbox Installation](https://blog.nviso.be/2018/04/12/painless-cuckoo-sandbox-installation/)
- 2018.03 [rapid7] [Next Threat Intel Book Club 4/5: Recapping The Cuckoo’s Egg](https://blog.rapid7.com/2018/03/18/next-threat-intel-book-club-4-5-recapping-the-cuckoos-egg/)
- 2018.03 [ensurtec] [Cuckoo Sandbox Setup Tutorial](https://ensurtec.com/cuckoo-sandbox-setup-tutorial/)
- 2018.01 [fortinet] [Prevalent Threats Targeting Cuckoo Sandbox Detection and Our Mitigation](https://blog.fortinet.com/2018/01/03/prevalent-threats-targeting-cuckoo-sandbox-detection-and-our-mitigation)
- 2018.01 [fortinet] [Prevalent Threats Targeting Cuckoo Sandbox Detection and Our Mitigation](https://www.fortinet.com/blog/threat-research/prevalent-threats-targeting-cuckoo-sandbox-detection-and-our-mitigation.html)
- 2017.09 [360] [Capturing Malware in the Details: Improving Cuckoo Sandbox's Ability to Detect Malicious Office Document Behaviour](https://www.anquanke.com/post/id/86826/)
- 2017.08 [trustwave] [Cuckoo & Linux Subsystem: Some Love for Windows 10](https://www.trustwave.com/Resources/SpiderLabs-Blog/Cuckoo--Linux-Subsystem--Some-Love-for-Windows-10/)
- 2017.08 [n0where] [Automated Android Malware Analysis: CuckooDroid](https://n0where.net/automated-android-malware-analysis-cuckoodroid)
- 2017.05 [robertputt] [Basic Malware Analysis with Cuckoo Sandbox](http://robertputt.co.uk/basic-malware-analysis-with-cuckoo-sandbox.html)
- 2017.05 [rastamouse] [Playing with Cuckoo](https://rastamouse.me/2017/05/playing-with-cuckoo/)
- 2017.04 [mcafee] [OpenDXL Case Study: Sandbox Mania featuring Cuckoo and Wildfire](https://securingtomorrow.mcafee.com/business/optimize-operations/opendxl-case-study-sandbox-mania-featuring-cuckoo-wildfire/)
- 2016.11 [tribalchicken] [Guide: Cuckoo Sandbox on FreeBSD](https://tribalchicken.io/guide-cuckoo-sandbox-on-freebsd/)


# <a id="7ab3a7005d6aa699562b3a0a0c6f2cff"></a>DBI


***


## <a id="c8cdb0e30f24e9b7394fcd5681f2e419"></a>DynamoRIO


### <a id="6c4841dd91cb173093ea2c8d0b557e71"></a>Tools


#### <a id="3a577a5b4730a1b5b3b325269509bb0a"></a>DynamoRIO


- [**1388** stars][12d] [C] [dynamorio/drmemory](https://github.com/dynamorio/drmemory) A memory debugger for Windows, Linux, macOS and Android.
- [**1228** stars][12d] [C] [dynamorio/dynamorio](https://github.com/dynamorio/dynamorio) A platform for dynamic instrumentation.


#### <a id="ff0abe26a37095f6575195950e0b7f94"></a>Recently Added


- [**1364** stars][3m] [C] [googleprojectzero/winafl](https://github.com/googleprojectzero/winafl) A fork of AFL for fuzzing Windows binaries.
- [**249** stars][5m] [C] [ampotos/dynstruct](https://github.com/ampotos/dynstruct) A reverse-engineering tool for automatically recovering data structures and analysing memory usage, based on DynamoRIO and Capstone.


#### <a id="928642a55eff34b6b52622c6862addd2"></a>Interoperability with Other Tools






### <a id="9479ce9f475e4b9faa4497924a2e40fc"></a>Articles and Videos


- 2019.10 [freebuf] [DrSemu: A Malware Detection and Classification Tool Based on Dynamic Behaviour](https://www.freebuf.com/sectool/214277.html)
- 2019.06 [freebuf] [Functrace: Tracing Function Calls with DynamoRIO](https://www.freebuf.com/sectool/205989.html)
- 2019.01 [360] [Understanding strace and ltrace Through DynamoRIO-Based Implementations](https://www.anquanke.com/post/id/169257/)
- 2018.08 [n0where] [Dynamic API Call Tracer for Windows and Linux Applications: Drltrace](https://n0where.net/dynamic-api-call-tracer-for-windows-and-linux-applications-drltrace)
- 2018.07 [topsec] [动态二进制修改(Dynamic Binary Instrumentation)入门：Pin、DynamoRIO、Frida](http://blog.topsec.com.cn/%e5%8a%a8%e6%80%81%e4%ba%8c%e8%bf%9b%e5%88%b6%e4%bf%ae%e6%94%b9dynamic-binary-instrumentation%e5%85%a5%e9%97%a8%ef%bc%9apin%e3%80%81dynamorio%e3%80%81frida/)
- 2017.11 [SECConsult] [The Art of Fuzzing - Demo 10: In-memory Fuzzing HashCalc using DynamoRio](https://www.youtube.com/watch?v=FEJGlgBeUJ8)
- 2017.11 [SECConsult] [The Art of Fuzzing - Demo 6: Extract Coverage Information using DynamoRio](https://www.youtube.com/watch?v=Ur_E9c2vX1A)
- 2017.04 [pediy] [[Original] Learning Dynamic Instrumentation with DynamoRIO Through Selfie](https://bbs.pediy.com/thread-216970.htm)
- 2016.11 [360] [Selfie: A Tool for Automatically Unpacking Self-Modifying Code Using DynamoRIO](https://www.anquanke.com/post/id/84999/)
- 2016.09 [securitygossip] [Practical Memory Checking With Dr. Memory](http://securitygossip.com/blog/2016/09/12/2016-09-12/)
- 2016.09 [sjtu] [Practical Memory Checking With Dr. Memory](https://loccs.sjtu.edu.cn/gossip/blog/2016/09/12/2016-09-12/)
- 2016.08 [n0where] [Dynamic Instrumentation Tool Platform: DynamoRIO](https://n0where.net/dynamic-instrumentation-tool-platform-dynamorio)
- 2014.01 [dustri] [Memory debugging under Windows with drmemory](https://dustri.org/b/memory-debugging-under-windows-with-drmemory.html)
- 2012.10 [redplait] [building dynamorio](http://redplait.blogspot.com/2012/10/building-dynamorio.html)
- 2011.06 [redplait] [dynamorio](http://redplait.blogspot.com/2011/06/dynamorio.html)




***


## <a id="7b8a493ca344f41887792fcc008573e7"></a>IntelPin


### <a id="fe5a6d7f16890542c9e60857706edfde"></a>Tools


#### <a id="78a2edf9aa41eb321436cb150ea70a54"></a>Recently Added


- [**299** stars][2m] [C] [vusec/vuzzer](https://github.com/vusec/vuzzer) Depends heavily on a modified version of DataTracker, which in turn depends on the LibDFT Pin tool.


#### <a id="e6a829abd8bbc5ad2e5885396e3eec04"></a>Interoperability with Other Tools


##### <a id="e129288dfadc2ab0890667109f93a76d"></a>Uncategorised


- [**943**stars][1y] [Py] [gaasedelen/lighthouse](https://github.com/gaasedelen/lighthouse) 从DBI中收集代码覆盖情况，在IDA/Binja中映射、浏览、查看
    - 重复区段: [IDA->插件->调试->DBI数据](#0fbd352f703b507853c610a664f024d1) |[DBI->Frida->工具->与其他工具交互->IDA](#d628ec92c9eea0c4b016831e1f6852b3) |[DBI->Frida->工具->与其他工具交互->BinaryNinja](#f9008a00e2bbc7535c88602aa79c8fd8) |
    - [coverage-frida](https://github.com/gaasedelen/lighthouse/blob/master/coverage/frida/README.md) 使用Frida收集信息
    - [coverage-pin](https://github.com/gaasedelen/lighthouse/blob/master/coverage/pin/README.md) 使用Pin收集覆盖信息
    - [插件](https://github.com/gaasedelen/lighthouse/blob/master/plugin/lighthouse_plugin.py) 支持IDA和BinNinja






### <a id="226190bea6ceb98ee5e2b939a6515fac"></a>Articles and Videos






***


## <a id="f24f1235fd45a1aa8d280eff1f03af7e"></a>Frida


### <a id="a5336a0f9e8e55111bda45c8d74924c1"></a>Tools


#### <a id="6d3c24e43835420063f9ca50ba805f15"></a>Frida


- [**4516**stars][13d] [Makefile] [frida/frida](https://github.com/frida/frida) Clone this repo to build Frida


#### <a id="54836a155de0c15b56f43634cd9cfecf"></a>Recently Added


- [**1193**stars][15d] [JS] [alonemonkey/frida-ios-dump](https://github.com/alonemonkey/frida-ios-dump) pull decrypted ipa from jailbreak device
    - 重复区段: [Apple->越狱->工具](#ff19d5d94315d035bbcb3ef0c348c75b) |
- [**895**stars][5m] [JS] [dpnishant/appmon](https://github.com/dpnishant/appmon) 用于监视和篡改本地macOS，iOS和android应用程序的系统API调用的自动化框架。基于Frida。
- [**645**stars][16d] [Py] [igio90/dwarf](https://github.com/igio90/dwarf) Full featured multi arch/os debugger built on top of PyQt5 and frida
- [**559**stars][1m] [JS] [nccgroup/house](https://github.com/nccgroup/house) 运行时手机 App 分析工具包, 带Web GUI
- [**513**stars][1m] [JS] [iddoeldor/frida-snippets](https://github.com/iddoeldor/frida-snippets) Hand-crafted Frida examples
- [**422**stars][1y] [Py] [dstmath/frida-unpack](https://github.com/dstmath/frida-unpack) 基于Frida的脱壳工具
- [**420**stars][13d] [C] [frida/frida-python](https://github.com/frida/frida-python) Frida Python bindings
- [**332**stars][15d] [JS] [chichou/bagbak](https://github.com/ChiChou/bagbak) Yet another frida based iOS dumpdecrypted, works on iOS 13 with checkra1n and supports decrypting app extensions
- [**321**stars][1m] [C] [frida/frida-core](https://github.com/frida/frida-core) Frida core library intended for static linking into bindings
- [**308** stars][4m] [JS] [smartdone/frida-scripts](https://github.com/smartdone/frida-scripts) A collection of Frida scripts.
- [**283** stars][8m] [Py] [nightbringer21/fridump](https://github.com/nightbringer21/fridump) A universal memory dumper that uses Frida.
- [**243** stars][19d] [JS] [frenchyeti/dexcalibur](https://github.com/frenchyeti/dexcalibur) A dynamic binary instrumentation tool for Android applications powered by Frida. It disassembles DEX files, performs static analysis, generates hooks, discovers reflected methods, stores intercepted data and enables further analysis. Its goal is to be an all-in-one Android reverse-engineering platform.
- [**228** stars][13d] [C] [frida/frida-gum](https://github.com/frida/frida-gum) A low-level code instrumentation library used by Frida Core.


#### <a id="74fa0c52c6104fd5656c93c08fd1ba86"></a>Interoperability with Other Tools


##### <a id="00a86c65a84e58397ee54e85ed57feaf"></a>Uncategorised


- [**584** stars][1y] [Java] [federicodotta/brida](https://github.com/federicodotta/brida) A bridge between Burp Suite and Frida.


##### <a id="d628ec92c9eea0c4b016831e1f6852b3"></a>IDA


- [**943**stars][1y] [Py] [gaasedelen/lighthouse](https://github.com/gaasedelen/lighthouse) 从DBI中收集代码覆盖情况，在IDA/Binja中映射、浏览、查看
    - 重复区段: [IDA->插件->调试->DBI数据](#0fbd352f703b507853c610a664f024d1) |[DBI->IntelPin->工具->与其他工具交互->未分类](#e129288dfadc2ab0890667109f93a76d) |[DBI->Frida->工具->与其他工具交互->BinaryNinja](#f9008a00e2bbc7535c88602aa79c8fd8) |
    - [coverage-frida](https://github.com/gaasedelen/lighthouse/blob/master/coverage/frida/README.md) 使用Frida收集信息
    - [coverage-pin](https://github.com/gaasedelen/lighthouse/blob/master/coverage/pin/README.md) 使用Pin收集覆盖信息
    - [插件](https://github.com/gaasedelen/lighthouse/blob/master/plugin/lighthouse_plugin.py) 支持IDA和BinNinja


##### <a id="f9008a00e2bbc7535c88602aa79c8fd8"></a>BinaryNinja


- [**943**stars][1y] [Py] [gaasedelen/lighthouse](https://github.com/gaasedelen/lighthouse) 从DBI中收集代码覆盖情况，在IDA/Binja中映射、浏览、查看
    - 重复区段: [IDA->插件->调试->DBI数据](#0fbd352f703b507853c610a664f024d1) |[DBI->IntelPin->工具->与其他工具交互->未分类](#e129288dfadc2ab0890667109f93a76d) |[DBI->Frida->工具->与其他工具交互->IDA](#d628ec92c9eea0c4b016831e1f6852b3) |
    - [coverage-frida](https://github.com/gaasedelen/lighthouse/blob/master/coverage/frida/README.md) 使用Frida收集信息
    - [coverage-pin](https://github.com/gaasedelen/lighthouse/blob/master/coverage/pin/README.md) 使用Pin收集覆盖信息
    - [插件](https://github.com/gaasedelen/lighthouse/blob/master/plugin/lighthouse_plugin.py) 支持IDA和BinNinja


##### <a id="ac053c4da818ca587d57711d2ff66278"></a>Radare2


- [**378** stars][27d] [JS] [nowsecure/r2frida](https://github.com/nowsecure/r2frida) Integrates Radare2 and Frida.
    - 重复区段: [Radare2->插件->与其他工具交互->未分类](#dfe53924d678f9225fc5ece9413b890f) |






### <a id="a1a7e3dd7091b47384c75dba8f279caf"></a>Articles and Videos


- 2019.12 [xakcop] [Cloning RSA tokens with Frida](https://xakcop.com/post/cloning-rsa/)
- 2019.09 [freebuf] [Dwarf: A Reverse-Engineering and Debugging Tool Based on PyQt5 and Frida](https://www.freebuf.com/sectool/212123.html)
- 2019.06 [two06] [Fun With Frida](https://medium.com/p/5d0f55dd331a)
- 2019.05 [nsfocus] [Decrypting Communication Data with Frida](http://blog.nsfocus.net/communication-data-decryption-based-on-frida/)
- 2019.05 [nsfocus] [Frida Basics and Bypassing HTTPS Certificate Validation in Apps](http://blog.nsfocus.net/frida%e5%ba%94%e7%94%a8%e5%9f%ba%e7%a1%80%e5%8f%8a-app-https%e8%af%81%e4%b9%a6%e9%aa%8c%e8%af%81%e7%a0%b4%e8%a7%a3/)
- 2019.05 [nsfocus] [Frida Basics and Bypassing HTTPS Certificate Validation in Apps](http://blog.nsfocus.net/frida-application-foundation-app-https-certificate-verification-cracking-2/)
- 2019.05 [nsfocus] [Frida Basics and Bypassing HTTPS Certificate Validation in Apps](http://blog.nsfocus.net/frida-application-foundation-app-https-certificate-verification-cracking/)
- 2019.05 [CodeColorist] [Trace child process with frida on macOS](https://medium.com/p/3b8f0f953f3d)
- 2019.05 [360] [FRIDA Script Series (Part 4): Updates to Several Major Mechanisms](https://www.anquanke.com/post/id/177597/)
- 2019.03 [360] [FRIDA Script Series (Part 3): Training Baidu AI with Douyin AI](https://www.anquanke.com/post/id/175621/)
- 2019.03 [securityinnovation] [Setting up Frida Without Jailbreak on the Latest iOS 12.1.4 Device](https://blog.securityinnovation.com/frida)
- 2019.02 [nowsecure] [Frida 12.3 Debuts New Crash Reporting Feature](https://www.nowsecure.com/blog/2019/02/07/frida-12-3-debuts-new-crash-reporting-feature/)
- 2019.01 [fuzzysecurity] [Windows Hacking: Application Introspection and Hooking with Frida](http://fuzzysecurity.com/tutorials/29.html)
- 2019.01 [fuping] [Android App Testing: Hooking with Frida](https://fuping.site/2019/01/25/Frida-Hook-SoulAPP/)
- 2019.01 [360] [FRIDA Script Series (Part 2): Combining Static and Dynamic Analysis to Reverse Engineer WhatsApp](https://www.anquanke.com/post/id/169315/)
- 2019.01 [pediy] [[Original] Frida Scripts Used in Android Reverse Engineering and Delayed Hooking Techniques](https://bbs.pediy.com/thread-248848.htm)
- 2018.12 [360] [FRIDA Script Series (Part 1): Getting Started—Dumping Bluetooth Interfaces and Instances on Android 8.1](https://www.anquanke.com/post/id/168152/)
- 2018.12 [pediy] [[Original] Analysis of CVE-2017-4901, a VMware Virtual Machine Escape Vulnerability (Frida on Windows)](https://bbs.pediy.com/thread-248384.htm)
- 2018.12 [freebuf] [An Article to Understand Frida in Depth (Based on Android 8.1)](https://www.freebuf.com/articles/system/190565.html)
- 2018.12 [pediy] [[Original] Frida Handbook: Preparing the Android Environment](https://bbs.pediy.com/thread-248293.htm)




***


## <a id="b2fca17481b109a9b3b0bc290a1a1381"></a>QBDI


### <a id="e72b766bcd3b868c438a372bc365221e"></a>Tools


- [**578** stars][1y] [C++] [qbdi/qbdi](https://github.com/QBDI/QBDI) A dynamic binary instrumentation framework based on LLVM.


### <a id="2cf79f93baf02a24d95d227a0a3049d8"></a>Articles and Videos


- 2019.09 [quarkslab] [QBDI 0.7.0](https://blog.quarkslab.com/qbdi-070.html)
- 2019.07 [freebuf] [How to Use the QBDI Dynamic Binary Instrumentation Framework](https://www.freebuf.com/sectool/207898.html)
- 2019.06 [quarkslab] [Android Native Library Analysis with QBDI](https://blog.quarkslab.com/android-native-library-analysis-with-qbdi.html)
- 2018.01 [quarkslab] [Slaying Dragons with QBDI](https://blog.quarkslab.com/slaying-dragons-with-qbdi.html)
- 2018.01 [pentesttoolz] [QBDI – QuarkslaB Dynamic binary Instrumentation](https://pentesttoolz.com/2018/01/13/qbdi-quarkslab-dynamic-binary-instrumentation/)
- 2018.01 [n0where] [QuarkslaB Dynamic binary Instrumentation: QBDI](https://n0where.net/quarkslab-dynamic-binary-instrumentation-qbdi)




***


## <a id="5a9974bfcf7cdf9b05fe7a7dc5272213"></a>Other


### <a id="104bc99e36692f133ba70475ebc8825f"></a>Tools




### <a id="8f1b9c5c2737493524809684b934d49a"></a>Articles and Videos


- 2018.08 [4hou] [Principles and Basic Implementation of Dynamic Binary Instrumentation (Part 1)](http://www.4hou.com/binary/13026.html)




# <a id="d3690e0b19c784e104273fe4d64b2362"></a>Other


***


## <a id="9162e3507d24e58e9e944dd3f6066c0e"></a> Articles-Recently Added




***


## <a id="1d9dec1320a5d774dc8e0e7604edfcd3"></a>Tools-Recently Added


- [**19766**stars][3m] [Jupyter Notebook] [camdavidsonpilon/probabilistic-programming-and-bayesian-methods-for-hackers](https://github.com/camdavidsonpilon/probabilistic-programming-and-bayesian-methods-for-hackers) aka "Bayesian Methods for Hackers": An introduction to Bayesian methods + probabilistic programming with a computation/understanding-first, mathematics-second point of view. All in pure Python ;)
- [**14349**stars][2m] [Py] [corentinj/real-time-voice-cloning](https://github.com/corentinj/real-time-voice-cloning) Clone a voice in 5 seconds to generate arbitrary speech in real-time
- [**11402**stars][10d] [Java] [oracle/graal](https://github.com/oracle/graal) Run Programs Faster Anywhere
- [**11213**stars][2m] [Jupyter Notebook] [selfteaching/the-craft-of-selfteaching](https://github.com/selfteaching/the-craft-of-selfteaching) One has no future if one couldn't teach themself.
- [**10378**stars][11d] [Go] [goharbor/harbor](https://github.com/goharbor/harbor) An open source trusted cloud native registry project that stores, signs, and scans content.
- [**7748**stars][10d] [Go] [git-lfs/git-lfs](https://github.com/git-lfs/git-lfs) Git extension for versioning large files
- [**7020**stars][14d] [Go] [nats-io/nats-server](https://github.com/nats-io/nats-server) High-Performance server for NATS, the cloud native messaging system.
- [**6894**stars][2m] [Go] [sqshq/sampler](https://github.com/sqshq/sampler) A tool for shell commands execution, visualization and alerting. Configured with a simple YAML file.
- [**6454**stars][9m] [HTML] [open-power-workgroup/hospital](https://github.com/open-power-workgroup/hospital) OpenPower工作组收集汇总的医院开放数据
- [**6353**stars][2m] [Py] [seatgeek/fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) Fuzzy String Matching in Python
- [**6055**stars][7m] [JS] [haotian-wang/google-access-helper](https://github.com/haotian-wang/google-access-helper) 谷歌访问助手破解版
- [**5876**stars][3m] [Gnuplot] [nasa-jpl/open-source-rover](https://github.com/nasa-jpl/open-source-rover) A build-it-yourself, 6-wheel rover based on the rovers on Mars!
- [**5829**stars][7m] [JS] [sindresorhus/fkill-cli](https://github.com/sindresorhus/fkill-cli) Fabulously kill processes. Cross-platform.
- [**5753**stars][18d] [Go] [casbin/casbin](https://github.com/casbin/casbin) An authorization library that supports access control models like ACL, RBAC, ABAC in Golang
- [**5751**stars][9m] [C] [xoreaxeaxeax/movfuscator](https://github.com/xoreaxeaxeax/movfuscator) C编译器，编译的二进制文件只有1个代码块。
- [**5717**stars][28d] [JS] [swagger-api/swagger-editor](https://github.com/swagger-api/swagger-editor) Swagger Editor
- [**5420**stars][12d] [Py] [mlflow/mlflow](https://github.com/mlflow/mlflow) Open source platform for the machine learning lifecycle
- [**5229**stars][4m] [Py] [ytisf/thezoo](https://github.com/ytisf/thezoo) A repository of LIVE malwares for your own joy and pleasure. theZoo is a project created to make the possibility of malware analysis open and available to the public.
- [**5226**stars][13d] [Shell] [denisidoro/navi](https://github.com/denisidoro/navi) An interactive cheatsheet tool for the command-line
- [**5116**stars][11d] [ASP] [hq450/fancyss](https://github.com/hq450/fancyss) fancyss is a project providing tools to across the GFW on asuswrt/merlin based router.
- [**5007**stars][2m] [Py] [snare/voltron](https://github.com/snare/voltron) A hacky debugger UI for hackers
- [**4857**stars][13d] [Go] [gcla/termshark](https://github.com/gcla/termshark) A terminal UI for tshark, inspired by Wireshark
- [**4810**stars][8m] [Py] [10se1ucgo/disablewintracking](https://github.com/10se1ucgo/disablewintracking) Uses some known methods that attempt to minimize tracking in Windows 10
- [**4747**stars][8d] [C++] [paddlepaddle/paddle-lite](https://github.com/PaddlePaddle/Paddle-Lite) Multi-platform high performance deep learning inference engine (『飞桨』多平台高性能深度学习预测引擎）
- [**4651**stars][13d] [powershell/win32-openssh](https://github.com/powershell/win32-openssh) Win32 port of OpenSSH
- [**4610**stars][1y] [C] [upx/upx](https://github.com/upx/upx) UPX - the Ultimate Packer for eXecutables
- [**4600**stars][12m] [Py] [ecthros/uncaptcha2](https://github.com/ecthros/uncaptcha2) defeating the latest version of ReCaptcha with 91% accuracy
- [**4597**stars][12d] [C++] [mozilla/rr](https://github.com/mozilla/rr) 记录与重放App的调试执行过程
- [**4541**stars][4m] [TS] [apis-guru/graphql-voyager](https://github.com/apis-guru/graphql-voyager) 
- [**4352**stars][1y] [Py] [lennylxx/ipv6-hosts](https://github.com/lennylxx/ipv6-hosts) Fork of
- [**4314**stars][15d] [Rust] [timvisee/ffsend](https://github.com/timvisee/ffsend) Easily and securely share files from the command line
- [**4258**stars][12m] [JS] [butterproject/butter-desktop](https://github.com/butterproject/butter-desktop) All the free parts of Popcorn Time
- [**4062**stars][3m] [Java] [jesusfreke/smali](https://github.com/jesusfreke/smali) smali/baksmali
- [**4060**stars][2m] [JS] [sigalor/whatsapp-web-reveng](https://github.com/sigalor/whatsapp-web-reveng) WhatsApp Web API逆向与重新实现
- [**4003**stars][11d] [Go] [dexidp/dex](https://github.com/dexidp/dex) OpenID Connect Identity (OIDC) and OAuth 2.0 Provider with Pluggable Connectors
- [**3980**stars][1m] [Rust] [svenstaro/genact](https://github.com/svenstaro/genact) a nonsense activity generator
- [**3960**stars][11d] [Py] [angr/angr](https://github.com/angr/angr) A powerful and user-friendly binary analysis platform!
- [**3954**stars][16d] [Go] [eranyanay/1m-go-websockets](https://github.com/eranyanay/1m-go-websockets) handling 1M websockets connections in Go
- [**3939**stars][15d] [C] [aquynh/capstone](https://github.com/aquynh/capstone) Capstone disassembly/disassembler framework: Core (Arm, Arm64, BPF, EVM, M68K, M680X, MOS65xx, Mips, PPC, RISCV, Sparc, SystemZ, TMS320C64x, Web Assembly, X86, X86_64, XCore) + bindings.
- [**3908**stars][12d] [C++] [baldurk/renderdoc](https://github.com/baldurk/renderdoc) RenderDoc is a stand-alone graphics debugging tool.
- [**3844**stars][2m] [ObjC] [sveinbjornt/sloth](https://github.com/sveinbjornt/sloth) Mac app that shows all open files, directories and sockets in use by all running processes. Nice GUI for lsof.
- [**3773**stars][25d] [jjqqkk/chromium](https://github.com/jjqqkk/chromium) Chromium browser with SSL VPN. Use this browser to unblock websites.
- [**3768**stars][2m] [Go] [microsoft/ethr](https://github.com/microsoft/ethr) Ethr is a Network Performance Measurement Tool for TCP, UDP & HTTP.
- [**3749**stars][12d] [Go] [hashicorp/consul-template](https://github.com/hashicorp/consul-template) Template rendering, notifier, and supervisor for
- [**3690**stars][21d] [JS] [lesspass/lesspass](https://github.com/lesspass/lesspass) 
- [**3688**stars][29d] [HTML] [hamukazu/lets-get-arrested](https://github.com/hamukazu/lets-get-arrested) This project is intended to protest against the police in Japan
- [**3627**stars][26d] [HTML] [consensys/smart-contract-best-practices](https://github.com/consensys/smart-contract-best-practices) A guide to smart contract security best practices
- [**3608**stars][9d] [Pascal] [cheat-engine/cheat-engine](https://github.com/cheat-engine/cheat-engine) Cheat Engine. A development environment focused on modding
- [**3538**stars][5m] [Shell] [chengr28/revokechinacerts](https://github.com/chengr28/revokechinacerts) Revoke Chinese certificates.
- [**3505**stars][16d] [C] [cyan4973/xxhash](https://github.com/cyan4973/xxhash) Extremely fast non-cryptographic hash algorithm
- [**3451**stars][19d] [C] [mikebrady/shairport-sync](https://github.com/mikebrady/shairport-sync) AirPlay audio player. Shairport Sync adds multi-room capability with Audio Synchronisation
- [**3306**stars][19d] [C] [microsoft/windows-driver-samples](https://github.com/microsoft/windows-driver-samples) This repo contains driver samples prepared for use with Microsoft Visual Studio and the Windows Driver Kit (WDK). It contains both Universal Windows Driver and desktop-only driver samples.
- [**3295**stars][15d] [JS] [koenkk/zigbee2mqtt](https://github.com/koenkk/zigbee2mqtt) Zigbee
- [**3289**stars][15d] [C] [virustotal/yara](https://github.com/virustotal/yara) The pattern matching swiss knife
- [**3280**stars][29d] [Java] [oldmanpushcart/greys-anatomy](https://github.com/oldmanpushcart/greys-anatomy) Java诊断工具
- [**3243**stars][14d] [Shell] [gfw-breaker/ssr-accounts](https://github.com/gfw-breaker/ssr-accounts) 一键部署Shadowsocks服务；免费Shadowsocks账号分享；免费SS账号分享; 翻墙；无界，自由门，SquirrelVPN
- [**3233**stars][25d] [C] [tmate-io/tmate](https://github.com/tmate-io/tmate) Instant Terminal Sharing
- [**3219**stars][2m] [TS] [google/incremental-dom](https://github.com/google/incremental-dom) An in-place DOM diffing library
- [**3202**stars][1y] [Shell] [toyodadoubi/doubi](https://github.com/toyodadoubi/doubi) 一个逗比写的各种逗比脚本~
- [**3188**stars][11d] [C] [meetecho/janus-gateway](https://github.com/meetecho/janus-gateway) Janus WebRTC Server
- [**3131**stars][2m] [CSS] [readthedocs/sphinx_rtd_theme](https://github.com/readthedocs/sphinx_rtd_theme) Sphinx theme for readthedocs.org
- [**3129**stars][13d] [C] [qemu/qemu](https://github.com/qemu/qemu) Official QEMU mirror. Please see
- [**3120**stars][11d] [Go] [tencent/bk-cmdb](https://github.com/tencent/bk-cmdb) 蓝鲸智云配置平台(BlueKing CMDB)
- [**3108**stars][1m] [C] [unicorn-engine/unicorn](https://github.com/unicorn-engine/unicorn) Unicorn CPU emulator framework (ARM, AArch64, M68K, Mips, Sparc, X86)
- [**3052**stars][4m] [C++] [google/robotstxt](https://github.com/google/robotstxt) The repository contains Google's robots.txt parser and matcher as a C++ library (compliant to C++11).
- [**2993**stars][18d] [Py] [quantaxis/quantaxis](https://github.com/quantaxis/quantaxis) 支持任务调度 分布式部署的 股票/期货/自定义市场 数据/回测/模拟/交易/可视化 纯本地PAAS量化解决方案
- [**2980**stars][14d] [ObjC] [google/santa](https://github.com/google/santa) 用于Mac系统的二进制文件白名单/黑名单系统
- [**2948**stars][1m] [C] [libfuse/sshfs](https://github.com/libfuse/sshfs) A network filesystem client to connect to SSH servers
- [**2898**stars][8m] [C] [p-h-c/phc-winner-argon2](https://github.com/p-h-c/phc-winner-argon2) The password hash Argon2, winner of PHC
- [**2872**stars][14d] [C] [lxc/lxc](https://github.com/lxc/lxc) LXC - Linux Containers
- [**2854**stars][1m] [Py] [espressif/esptool](https://github.com/espressif/esptool) ESP8266 and ESP32 serial bootloader utility
- [**2848**stars][6m] [Py] [instantbox/instantbox](https://github.com/instantbox/instantbox) Get a clean, ready-to-go Linux box in seconds.
- [**2833**stars][2m] [Assembly] [cirosantilli/x86-bare-metal-examples](https://github.com/cirosantilli/x86-bare-metal-examples) 几十个用于学习 x86 系统编程的小型操作系统
- [**2815**stars][20d] [C] [processhacker/processhacker](https://github.com/processhacker/processhacker) A free, powerful, multi-purpose tool that helps you monitor system resources, debug software and detect malware.
- [**2808**stars][10m] [Py] [plasma-disassembler/plasma](https://github.com/plasma-disassembler/plasma) Plasma is an interactive disassembler for x86/ARM/MIPS. It can generates indented pseudo-code with colored syntax.
- [**2789**stars][13d] [C++] [qtox/qtox](https://github.com/qtox/qtox) qTox is a chat, voice, video, and file transfer IM client using the encrypted peer-to-peer Tox protocol.
- [**2772**stars][2m] [JS] [trufflesuite/ganache-cli](https://github.com/trufflesuite/ganache-cli) Fast Ethereum RPC client for testing and development
- [**2760**stars][10d] [TS] [webhintio/hint](https://github.com/webhintio/hint) 
- [**2718**stars][3m] [Py] [drivendata/cookiecutter-data-science](https://github.com/drivendata/cookiecutter-data-science) A logical, reasonably standardized, but flexible project structure for doing and sharing data science work.
- [**2687**stars][11d] [Go] [adguardteam/adguardhome](https://github.com/adguardteam/adguardhome) Network-wide ads & trackers blocking DNS server
- [**2631**stars][8m] [leandromoreira/linux-network-performance-parameters](https://github.com/leandromoreira/linux-network-performance-parameters) Learn where some of the network sysctl variables fit into the Linux/Kernel network flow
- [**2627**stars][23d] [JS] [popcorn-official/popcorn-desktop](https://github.com/popcorn-official/popcorn-desktop) Popcorn Time is a multi-platform, free software BitTorrent client that includes an integrated media player. Desktop ( Windows / Mac / Linux ) a Butter-Project Fork
- [**2621**stars][2m] [pditommaso/awesome-pipeline](https://github.com/pditommaso/awesome-pipeline) A curated list of awesome pipeline toolkits inspired by Awesome Sysadmin
- [**2619**stars][2m] [Swift] [zhuhaow/nekit](https://github.com/zhuhaow/nekit) A toolkit for Network Extension Framework
- [**2615**stars][1m] [JS] [knownsec/kcon](https://github.com/knownsec/kcon) KCon is a famous Hacker Con powered by Knownsec Team.
- [**2587**stars][10d] [C] [esnet/iperf](https://github.com/esnet/iperf) A TCP, UDP, and SCTP network bandwidth measurement tool
- [**2535**stars][3m] [Java] [jboss-javassist/javassist](https://github.com/jboss-javassist/javassist) Java bytecode engineering toolkit
- [**2478**stars][11m] [JS] [weixin/miaow](https://github.com/weixin/Miaow) A set of plugins for Sketch include drawing links & marks, UI Kit & Color sync, font & text replacing.
- [**2474**stars][25d] [JS] [vitaly-t/pg-promise](https://github.com/vitaly-t/pg-promise) PostgreSQL interface for Node.js
- [**2391**stars][21d] [Java] [mock-server/mockserver](https://github.com/mock-server/mockserver) MockServer enables easy mocking of any system you integrate with via HTTP or HTTPS with clients written in Java, JavaScript and Ruby. MockServer also includes a proxy that introspects all proxied traffic including encrypted SSL traffic and supports Port Forwarding, Web Proxying (i.e. HTTP proxy), HTTPS Tunneling Proxying (using HTTP CONNECT) and…
- [**2364**stars][10d] [C] [domoticz/domoticz](https://github.com/domoticz/domoticz) monitor and configure various devices like: Lights, Switches, various sensors/meters like Temperature, Rain, Wind, UV, Electra, Gas, Water and much more
- [**2345**stars][4m] [Go] [vuvuzela/vuvuzela](https://github.com/vuvuzela/vuvuzela) Private messaging system that hides metadata
- [**2344**stars][16d] [C] [tsl0922/ttyd](https://github.com/tsl0922/ttyd) Share your terminal over the web
- [**2340**stars][2m] [JS] [pa11y/pa11y](https://github.com/pa11y/pa11y) Pa11y is your automated accessibility testing pal
- [**2305**stars][2m] [C] [moby/hyperkit](https://github.com/moby/hyperkit) A toolkit for embedding hypervisor capabilities in your application
- [**2286**stars][1m] [JS] [talkingdata/inmap](https://github.com/talkingdata/inmap) 大数据地理可视化
- [**2260**stars][13d] [dumb-password-rules/dumb-password-rules](https://github.com/dumb-password-rules/dumb-password-rules) Shaming sites with dumb password rules.
- [**2217**stars][14d] [Go] [google/mtail](https://github.com/google/mtail) extract whitebox monitoring data from application logs for collection in a timeseries database
- [**2214**stars][18d] [getlantern/lantern-binaries](https://github.com/getlantern/lantern-binaries) Lantern installers binary downloads.
- [**2211**stars][1m] [C++] [google/bloaty](https://github.com/google/bloaty) Bloaty McBloatface: a size profiler for binaries
- [**2194**stars][13d] [C] [armmbed/mbedtls](https://github.com/armmbed/mbedtls) An open source, portable, easy to use, readable and flexible SSL library
- [**2137**stars][19d] [Assembly] [pret/pokered](https://github.com/pret/pokered) disassembly of Pokémon Red/Blue
- [**2132**stars][20d] [goq/telegram-list](https://github.com/goq/telegram-list) List of telegram groups, channels & bots // Список интересных групп, каналов и ботов телеграма // Список чатов для программистов
- [**2093**stars][10d] [C] [flatpak/flatpak](https://github.com/flatpak/flatpak) Linux application sandboxing and distribution framework
- [**2092**stars][26d] [swiftonsecurity/sysmon-config](https://github.com/swiftonsecurity/sysmon-config) Sysmon configuration file template with default high-quality event tracing
- [**2080**stars][2m] [Go] [theupdateframework/notary](https://github.com/theupdateframework/notary) Notary is a project that allows anyone to have trust over arbitrary collections of data
- [**2053**stars][4m] [Go] [maxmcd/webtty](https://github.com/maxmcd/webtty) Share a terminal session over WebRTC
- [**2053**stars][24d] [C#] [mathewsachin/captura](https://github.com/mathewsachin/captura) Capture Screen, Audio, Cursor, Mouse Clicks and Keystrokes
- [**2052**stars][13d] [C++] [openthread/openthread](https://github.com/openthread/openthread) OpenThread released by Google is an open-source implementation of the Thread networking protocol
- [**2031**stars][10m] [C] [dekunukem/nintendo_switch_reverse_engineering](https://github.com/dekunukem/nintendo_switch_reverse_engineering) A look at inner workings of Joycon and Nintendo Switch
- [**2003**stars][2m] [C++] [asmjit/asmjit](https://github.com/asmjit/asmjit) Complete x86/x64 JIT and AOT Assembler for C++
- [**1998**stars][2m] [Swift] [github/softu2f](https://github.com/github/softu2f) Software U2F authenticator for macOS
- [**1955**stars][11d] [Go] [solo-io/gloo](https://github.com/solo-io/gloo) An Envoy-Powered API Gateway
- [**1949**stars][17d] [C] [microsoft/procdump-for-linux](https://github.com/microsoft/procdump-for-linux) Linux 版本的 ProcDump
- [**1930**stars][22d] [C++] [mhammond/pywin32](https://github.com/mhammond/pywin32) Python for Windows (pywin32) Extensions
- [**1907**stars][18d] [Go] [minishift/minishift](https://github.com/minishift/minishift) Run OpenShift 3.x locally
- [**1899**stars][25d] [C++] [acidanthera/lilu](https://github.com/acidanthera/Lilu) Arbitrary kext and process patching on macOS
- [**1877**stars][25d] [Java] [adoptopenjdk/jitwatch](https://github.com/adoptopenjdk/jitwatch) Log analyser / visualiser for Java HotSpot JIT compiler. Inspect inlining decisions, hot methods, bytecode, and assembly. View results in the JavaFX user interface.
- [**1863**stars][10d] [C++] [pytorch/glow](https://github.com/pytorch/glow) Compiler for Neural Network hardware accelerators
- [**1859**stars][12m] [C++] [googlecreativelab/open-nsynth-super](https://github.com/googlecreativelab/open-nsynth-super) Open NSynth Super is an experimental physical interface for the NSynth algorithm
- [**1854**stars][19d] [C] [github/glb-director](https://github.com/github/glb-director) GitHub Load Balancer Director and supporting tooling.
- [**1852**stars][1y] [Py] [jinnlynn/genpac](https://github.com/jinnlynn/genpac) PAC/Dnsmasq/Wingy file Generator, working with gfwlist, support custom rules.
- [**1851**stars][1y] [Java] [yeriomin/yalpstore](https://github.com/yeriomin/yalpstore) Download apks from Google Play Store
- [**1848**stars][9m] [Py] [netflix-skunkworks/stethoscope](https://github.com/Netflix-Skunkworks/stethoscope) Personalized, user-focused recommendations for employee information security.
- [**1846**stars][3m] [C] [retroplasma/earth-reverse-engineering](https://github.com/retroplasma/earth-reverse-engineering) Reversing Google's 3D satellite mode
- [**1837**stars][3m] [Go] [influxdata/kapacitor](https://github.com/influxdata/kapacitor) Open source framework for processing, monitoring, and alerting on time series data
- [**1827**stars][13d] [Py] [trailofbits/manticore](https://github.com/trailofbits/manticore) 动态二进制分析工具，支持符号执行（symbolic execution）、污点分析（taint analysis）、运行时修改。
- [**1816**stars][29d] [Go] [gdamore/tcell](https://github.com/gdamore/tcell) Tcell is an alternate terminal package, similar in some ways to termbox, but better in others.
- [**1786**stars][1m] [C++] [apitrace/apitrace](https://github.com/apitrace/apitrace) Tools for tracing OpenGL, Direct3D, and other graphics APIs
- [**1781**stars][26d] [PHP] [ezyang/htmlpurifier](https://github.com/ezyang/htmlpurifier) Standards compliant HTML filter written in PHP
- [**1779**stars][29d] [17mon/china_ip_list](https://github.com/17mon/china_ip_list) 
- [**1761**stars][1y] [JS] [puppeteer/examples](https://github.com/puppeteer/examples) Use case-driven examples for using Puppeteer and headless chrome
- [**1761**stars][13d] [C] [google/wuffs](https://github.com/google/wuffs) Wrangling Untrusted File Formats Safely
- [**1756**stars][16d] [PHP] [wordpress/wordpress-coding-standards](https://github.com/wordpress/wordpress-coding-standards) PHP_CodeSniffer rules (sniffs) to enforce WordPress coding conventions
- [**1727**stars][8d] [TSQL] [brentozarultd/sql-server-first-responder-kit](https://github.com/brentozarultd/sql-server-first-responder-kit) sp_Blitz, sp_BlitzCache, sp_BlitzFirst, sp_BlitzIndex, and other SQL Server scripts for health checks and performance tuning.
- [**1722**stars][4m] [Py] [anorov/cloudflare-scrape](https://github.com/anorov/cloudflare-scrape) A Python module to bypass Cloudflare's anti-bot page.
- [**1714**stars][1m] [Go] [hashicorp/memberlist](https://github.com/hashicorp/memberlist) Golang package for gossip based membership and failure detection
- [**1698**stars][21d] [C++] [microsoft/detours](https://github.com/microsoft/detours) Detours is a software package for monitoring and instrumenting API calls on Windows. It is distributed in source code form.
- [**1676**stars][10d] [Java] [apache/geode](https://github.com/apache/geode) Apache Geode
- [**1672**stars][7m] [C] [easyhook/easyhook](https://github.com/easyhook/easyhook) The reinvention of Windows API Hooking
- [**1668**stars][3m] [Py] [boppreh/keyboard](https://github.com/boppreh/keyboard) Hook and simulate global keyboard events on Windows and Linux.
- [**1659**stars][25d] [JS] [tylerbrock/mongo-hacker](https://github.com/tylerbrock/mongo-hacker) MongoDB Shell Enhancements for Hackers
- [**1650**stars][13d] [sarojaba/awesome-devblog](https://github.com/sarojaba/awesome-devblog) 어썸데브블로그. 국내 개발 블로그 모음(only 실명으로).
- [**1637**stars][12d] [JS] [efforg/privacybadger](https://github.com/efforg/privacybadger) Privacy Badger is a browser extension that automatically learns to block invisible trackers.
- [**1624**stars][9m] [JS] [localtunnel/server](https://github.com/localtunnel/server) server for localtunnel.me
- [**1620**stars][16d] [C++] [lief-project/lief](https://github.com/lief-project/lief) Library to Instrument Executable Formats
- [**1592**stars][2m] [ObjC] [ealeksandrov/provisionql](https://github.com/ealeksandrov/provisionql) Quick Look plugin for apps and provisioning profile files
- [**1584**stars][1y] [C] [qihoo360/phptrace](https://github.com/qihoo360/phptrace) A tracing and troubleshooting tool for PHP scripts.
- [**1572**stars][1m] [C] [codahale/bcrypt-ruby](https://github.com/codahale/bcrypt-ruby)  Ruby binding for the OpenBSD bcrypt() password hashing algorithm, allowing you to easily store a secure hash of your users' passwords.
- [**1562**stars][1m] [C] [p-gen/smenu](https://github.com/p-gen/smenu) Terminal utility that reads words from standard input or from a file and creates an interactive selection window just below the cursor. The selected word(s) are sent to standard output for further processing.
- [**1562**stars][19d] [Java] [gchq/gaffer](https://github.com/gchq/Gaffer) A large-scale entity and relation database supporting aggregation of properties
- [**966**stars][7m] [PHP] [jenssegers/optimus](https://github.com/jenssegers/optimus)  id transformation With this library, you can transform your internal id's to obfuscated integers based on Knuth's integer has和
- [**906**stars][7m] [C++] [dfhack/dfhack](https://github.com/DFHack/dfhack) Memory hacking library for Dwarf Fortress and a set of tools that use it
- [**895**stars][12m] [JS] [levskaya/jslinux-deobfuscated](https://github.com/levskaya/jslinux-deobfuscated) An old version of Mr. Bellard's JSLinux rewritten to be human readable, hand deobfuscated and annotated.
- [**706**stars][1y] [Jupyter Notebook] [anishathalye/obfuscated-gradients](https://github.com/anishathalye/obfuscated-gradients) Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples
- [**658**stars][10m] [Jupyter Notebook] [supercowpowers/data_hacking](https://github.com/SuperCowPowers/data_hacking) Data Hacking Project
- [**657**stars][1y] [Rust] [endgameinc/xori](https://github.com/endgameinc/xori) Xori is an automation-ready disassembly and static analysis library for PE32, 32+ and shellcode
- [**637**stars][21d] [PS] [olafhartong/sysmon-modular](https://github.com/olafhartong/sysmon-modular) sysmon配置模块收集
- [**587**stars][6m] [nshalabi/sysmontools](https://github.com/nshalabi/sysmontools) Utilities for Sysmon
- [**568**stars][11m] [JS] [raineorshine/solgraph](https://github.com/raineorshine/solgraph) Visualize Solidity control flow for smart contract security analysis.
- [**523**stars][2m] [mhaggis/sysmon-dfir](https://github.com/mhaggis/sysmon-dfir) Sources, configuration and how to detect evil things utilizing Microsoft Sysmon.
- [**522**stars][4m] [Java] [java-deobfuscator/deobfuscator](https://github.com/java-deobfuscator/deobfuscator) Java 代码反混淆工具
- [**507**stars][8m] [JS] [mindedsecurity/jstillery](https://github.com/mindedsecurity/jstillery) Advanced JavaScript Deobfuscation via Partial Evaluation
- [**449**stars][12m] [C++] [ntquery/scylla](https://github.com/ntquery/scylla) Imports Reconstructor
- [**447**stars][3m] [Go] [retroplasma/flyover-reverse-engineering](https://github.com/retroplasma/flyover-reverse-engineering) Reversing Apple's 3D satellite mode
- [**446**stars][11m] [Batchfile] [ion-storm/sysmon-config](https://github.com/ion-storm/sysmon-config) Advanced Sysmon configuration, Installer & Auto Updater with high-quality event tracing
- [**408**stars][19d] [Py] [crytic/slither](https://github.com/crytic/slither) Static Analyzer for Solidity
- [**383**stars][1y] [HTML] [maestron/reverse-engineering-tutorials](https://github.com/maestron/reverse-engineering-tutorials) Reverse Engineering Tutorials
- [**344**stars][1y] [Ruby] [calebfenton/dex-oracle](https://github.com/calebfenton/dex-oracle) A pattern based Dalvik deobfuscator which uses limited execution to improve semantic analysis
- [**308**stars][25d] [Py] [baderj/domain_generation_algorithms](https://github.com/baderj/domain_generation_algorithms) 域名生成算法
- [**306**stars][2m] [C] [nagyd/sdlpop](https://github.com/nagyd/sdlpop) An open-source port of Prince of Persia, based on the disassembly of the DOS version.
- [**291**stars][28d] [C] [tomb5/tomb5](https://github.com/tomb5/tomb5) Chronicles Disassembly translated to C source code.
- [**265**stars][3m] [Assembly] [pret/pokeyellow](https://github.com/pret/pokeyellow) Disassembly of Pokemon Yellow
- [**240**stars][4m] [JS] [consensys/surya](https://github.com/consensys/surya) A set of utilities for exploring Solidity contracts
- [**214**stars][2m] [Py] [rpisec/llvm-deobfuscator](https://github.com/rpisec/llvm-deobfuscator) 
- [**211**stars][12m] [Java] [neo23x0/fnord](https://github.com/neo23x0/fnord) Pattern Extractor for Obfuscated Code


***


## <a id="bc2b78af683e7ba983205592de8c3a7a"></a>Tools-Other




***


## <a id="4fe330ae3e5ce0b39735b1bfea4528af"></a>angr


### <a id="1ede5ade1e55074922eb4b6386f5ca65"></a>Tools


- [**534**stars][12d] [Py] [angr/angr-doc](https://github.com/angr/angr-doc) Documentation for the angr suite
- [**305**stars][2m] [Py] [salls/angrop](https://github.com/salls/angrop) a rop gadget finder and chain builder 


### <a id="042ef9d415350eeb97ac2539c2fa530e"></a>Articles


- 2016.04 [] [Solving kao's toy project with symbolic execution and angr](https://0xec.blogspot.com/2016/04/solving-kaos-toy-project-with-symbolic.html)
- 2016.02 [theobsidiantower] [Angr and me](https://theobsidiantower.com/2016/02/11/4047a80b3927bd0a09363e7ccd202effe4b336aa.html)
- 2014.08 [3xp10it] [angr解题](http://3xp10it.cc/%E4%BA%8C%E8%BF%9B%E5%88%B6/2017/11/16/angr%E8%A7%A3%E9%A2%98/)
- 2014.08 [3xp10it] [angr解题](http://3xp10it.cc/%E4%BA%8C%E8%BF%9B%E5%88%B6/2017/11/16/angr%E8%A7%A3%E9%A2%98/)




***


## <a id="324874bb7c3ead94eae6f1fa1af4fb68"></a>Debug&&Debugging


### <a id="d22bd989b2fdaeda14b64343b472dfb6"></a>Tools


- [**1450**stars][10d] [Go] [google/gapid](https://github.com/google/gapid) Graphics API Debugger
- [**1422**stars][17d] [C++] [eteran/edb-debugger](https://github.com/eteran/edb-debugger) edb is a cross platform AArch32/x86/x86-64 debugger.
- [**1413**stars][19d] [Go] [cosmos72/gomacro](https://github.com/cosmos72/gomacro) Interactive Go interpreter and debugger with REPL, Eval, generics and Lisp-like macros
- [**1275**stars][4m] [Go] [solo-io/squash](https://github.com/solo-io/squash) The debugger for microservices
- [**1147**stars][5m] [C++] [cgdb/cgdb](https://github.com/cgdb/cgdb) Console front-end to the GNU debugger
- [**1128**stars][20d] [C] [blacksphere/blackmagic](https://github.com/blacksphere/blackmagic) In application debugger for ARM Cortex microcontrollers.
- [**899**stars][10d] [Py] [derekselander/lldb](https://github.com/derekselander/lldb) A collection of LLDB aliases/regexes and Python scripts to aid in your debugging sessions
- [**836**stars][8d] [C++] [tasvideos/bizhawk](https://github.com/tasvideos/bizhawk) BizHawk is a multi-system emulator written in C#. BizHawk provides nice features for casual gamers such as full screen, and joypad support in addition to full rerecording and debugging tools for all system cores.
- [**560**stars][21d] [C#] [microsoft/miengine](https://github.com/microsoft/miengine) The Visual Studio MI Debug Engine ("MIEngine") provides an open-source Visual Studio Debugger extension that works with MI-enabled debuggers such as gdb, lldb, and clrdbg.
- [**521**stars][1y] [C] [wubingzheng/memleax](https://github.com/wubingzheng/memleax) debugs memory leak of running process. Not maintained anymore, try `libleak` please.
- [**462**stars][5m] [C++] [emoon/prodbg](https://github.com/emoon/prodbg) Debugging the way it's meant to be done
- [**423**stars][4m] [C++] [cobaltfusion/debugviewpp](https://github.com/cobaltfusion/debugviewpp) DebugView++, collects, views, filters your application logs, and highlights information that is important to you!
- [**418**stars][26d] [C++] [simonkagstrom/kcov](https://github.com/simonkagstrom/kcov) Code coverage tool for compiled programs, Python and Bash which uses debugging information to collect and report data without special compilation options
- [**377**stars][1m] [Py] [pdbpp/pdbpp](https://github.com/pdbpp/pdbpp) pdb++, a drop-in replacement for pdb (the Python debugger)
- [**332**stars][8m] [Py] [romanvm/python-web-pdb](https://github.com/romanvm/python-web-pdb) Web-based remote UI for Python's PDB debugger
- [**306**stars][21d] [Java] [widdix/aws-s3-virusscan](https://github.com/widdix/aws-s3-virusscan) Free Antivirus for S3 Buckets
- [**291**stars][12d] [Py] [sosreport/sos](https://github.com/sosreport/sos) A unified tool for collecting system logs and other debug information
- [**285**stars][2m] [C++] [changeofpace/viviennevmm](https://github.com/changeofpace/viviennevmm) VivienneVMM is a stealthy debugging framework implemented via an Intel VT-x hypervisor.
- [**272**stars][4m] [Py] [mariovilas/winappdbg](https://github.com/mariovilas/winappdbg) WinAppDbg Debugger
- [**270**stars][21d] [Py] [ionelmc/python-manhole](https://github.com/ionelmc/python-manhole) Debugging manhole for python applications.
- [**250**stars][2m] [Py] [quantopian/qdb](https://github.com/quantopian/qdb) Quantopian Remote Debugger for Python
- [**240**stars][6m] [C++] [facebook/ds2](https://github.com/facebook/ds2) Debug server for lldb.
- [**239**stars][8m] [C++] [strivexjun/xantidebug](https://github.com/strivexjun/xantidebug) VMProtect 3.x Anti-debug Method Improved
- [**239**stars][8m] [Py] [beeware/bugjar](https://github.com/beeware/bugjar) A interactive graphical debugger for Python code.
- [**233**stars][2m] [Py] [gilligan/vim-lldb](https://github.com/gilligan/vim-lldb) lldb debugger integration plugin for vim
- [**220**stars][9m] [letoram/senseye](https://github.com/letoram/senseye) Dynamic Visual Debugging / Reverse Engineering Toolsuite
- [**218**stars][2m] [Py] [nteseyes/pylane](https://github.com/nteseyes/pylane) An python vm injector with debug tools, based on gdb.
- [**213**stars][12d] [C++] [thalium/icebox](https://github.com/thalium/icebox) Virtual Machine Introspection, Tracing & Debugging
- [**209**stars][2m] [C] [joyent/mdb_v8](https://github.com/joyent/mdb_v8) postmortem debugging for Node.js and other V8-based programs
- [**200**stars][6m] [C++] [rainers/cv2pdb](https://github.com/rainers/cv2pdb) converter of DMD CodeView/DWARF debug information to PDB files


### <a id="136c41f2d05739a74c6ec7d8a84df1e8"></a>Articles






***


## <a id="9f8d3f2c9e46fbe6c25c22285c8226df"></a>BAP


### <a id="f10e9553770db6f98e8619dcd74166ef"></a>Tools


- [**1106**stars][14d] [OCaml] [binaryanalysisplatform/bap](https://github.com/binaryanalysisplatform/bap) Binary Analysis Platform
- [**411**stars][13d] [HTML] [w3c/webappsec](https://github.com/w3c/webappsec) Web App安全工作组
- [**299**stars][17d] [JS] [w3c/webappsec-trusted-types](https://github.com/w3c/webappsec-trusted-types) A browser API to prevent DOM-Based Cross Site Scripting in modern web applications.


### <a id="e111826dde8fa44c575ce979fd54755d"></a>Articles






***


## <a id="2683839f170250822916534f1db22eeb"></a>BinNavi


### <a id="2e4980c95871eae4ec0e76c42cc5c32f"></a>Tools


- [**382** stars][26d] [C++] [google/binexport](https://github.com/google/binexport) — Exports disassembly into a PostgreSQL database in Protocol Buffer format so it can be imported and used in BinNavi.
    - 重复区段: [IDA->插件->导入导出->BinNavi](#11139e7d6db4c1cef22718868f29fe12) |


### <a id="ff4dc5c746cb398d41fb69a4f8dfd497"></a>Articles


- 2015.12 [summitroute] [Setting up fREedom and BinNavi](https://summitroute.com/blog/2015/12/31/setting_up_freedom_and_binnavi/)
- 2015.12 [addxorrol] [Open-Source BinNavi ... and fREedom](http://addxorrol.blogspot.com/2015/12/open-source-binnavi-and-freedom.html)
- 2015.08 [freebuf] [逆向分析神器BinNavi开源了](http://www.freebuf.com/sectool/75529.html)
- 2008.11 [addxorrol] [BinDiff / BinNavi User Forum](http://addxorrol.blogspot.com/2008/11/bindiff-binnavi-user-forum.html)
- 2008.11 [addxorrol] [BinNavi v2 and PHP !](http://addxorrol.blogspot.com/2008/11/binnavi-v2-and-php.html)




***


## <a id="0971f295b0f67dc31b7aa45caf3f588f"></a>Decompiler&&Decompilers


### <a id="e67c18b4b682ceb6716388522f9a1417"></a>Tools


- [**20779**stars][8d] [Java] [skylot/jadx](https://github.com/skylot/jadx) dex 转 java 的反编译器
- [**7733**stars][1m] [Java] [java-decompiler/jd-gui](https://github.com/java-decompiler/jd-gui) A standalone Java Decompiler GUI
- [**3135**stars][26d] [Java] [deathmarine/luyten](https://github.com/deathmarine/luyten) An Open Source Java Decompiler Gui for Procyon
- [**1867**stars][1y] [Java] [jindrapetrik/jpexs-decompiler](https://github.com/jindrapetrik/jpexs-decompiler) JPEXS Free Flash Decompiler
- [**1652**stars][12m] [Java] [fesh0r/fernflower](https://github.com/fesh0r/fernflower) Unofficial mirror of FernFlower Java decompiler (All pulls should be submitted upstream)
- [**1466**stars][12d] [Py] [rocky/python-uncompyle6](https://github.com/rocky/python-uncompyle6) Python反编译器，跨平台
- [**1084**stars][4m] [Py] [storyyeller/krakatau](https://github.com/storyyeller/krakatau) Java decompiler, assembler, and disassembler
- [**764**stars][12m] [C++] [comaeio/porosity](https://github.com/comaeio/porosity) *UNMAINTAINED* Decompiler and Security Analysis tool for Blockchain-based Ethereum Smart-Contracts
- [**673**stars][18d] [C#] [uxmal/reko](https://github.com/uxmal/reko) Reko is a binary decompiler.
- [**671**stars][11m] [C++] [zrax/pycdc](https://github.com/zrax/pycdc) C++ python bytecode disassembler and decompiler
- [**538**stars][6m] [Java] [java-decompiler/jd-eclipse](https://github.com/java-decompiler/jd-eclipse) A Java Decompiler Eclipse plugin
- [**347**stars][16d] [C#] [steamdatabase/valveresourceformat](https://github.com/steamdatabase/valveresourceformat) Valve's Source 2 resource file format (also known as Stupid Valve Format) parser and decompiler.
- [**331**stars][11d] [Java] [leibnitz27/cfr](https://github.com/leibnitz27/cfr) This is the public repository for the CFR Java decompiler
- [**327**stars][2m] [C++] [silverf0x/rpcview](https://github.com/silverf0x/rpcview) RpcView is a free tool to explore and decompile Microsoft RPC interfaces
- [**283**stars][8m] [Shell] [venshine/decompile-apk](https://github.com/venshine/decompile-apk) APK 反编译
- [**243**stars][3m] [Java] [kwart/jd-cmd](https://github.com/kwart/jd-cmd) Command line Java Decompiler
- [**242**stars][11d] [C#] [icsharpcode/avaloniailspy](https://github.com/icsharpcode/avaloniailspy) Avalonia-based .NET Decompiler (port of ILSpy)
- [**240**stars][2m] [Java] [ata4/bspsrc](https://github.com/ata4/bspsrc) A Source engine map decompiler
- [**232**stars][1y] [C++] [wwwg/wasmdec](https://github.com/wwwg/wasmdec) WebAssembly to C decompiler
- [**226**stars][11d] [C++] [boomerangdecompiler/boomerang](https://github.com/BoomerangDecompiler/boomerang) Boomerang Decompiler - Fighting the code-rot :)


### <a id="a748b79105651a8fd8ae856a7dc2b1de"></a>Articles






***


## <a id="2df6d3d07e56381e1101097d013746a0"></a>Disassemble&&反汇编


### <a id="59f472c7575951c57d298aef21e7d73c"></a>Tools


- [**1374**stars][20d] [C] [zyantific/zydis](https://github.com/zyantific/zydis) 快速的轻量级x86/x86-64 反汇编库
- [**1346**stars][12m] [Rust] [das-labor/panopticon](https://github.com/das-labor/panopticon) A libre cross-platform disassembler.
- [**877**stars][11m] [C++] [wisk/medusa](https://github.com/wisk/medusa) An open source interactive disassembler
- [**835**stars][8d] [GLSL] [khronosgroup/spirv-cross](https://github.com/khronosgroup/spirv-cross)  a practical tool and library for performing reflection on SPIR-V and disassembling SPIR-V back to high level languages.
- [**828**stars][3m] [C++] [redasmorg/redasm](https://github.com/redasmorg/redasm) The OpenSource Disassembler
- [**627**stars][3m] [C] [gdabah/distorm](https://github.com/gdabah/distorm) Powerful Disassembler Library For x86/AMD64
- [**430**stars][2m] [C#] [0xd4d/iced](https://github.com/0xd4d/iced) x86/x64 disassembler, instruction decoder & encoder
- [**351**stars][21d] [Ruby] [jjyg/metasm](https://github.com/jjyg/metasm) This is the main repository for metasm, a free assembler / disassembler / compiler written in ruby
- [**246**stars][5m] [Py] [bontchev/pcodedmp](https://github.com/bontchev/pcodedmp) A VBA p-code disassembler


### <a id="a6eb5a22deb33fc1919eaa073aa29ab5"></a>Articles






***


## <a id="975d9f08e2771fccc112d9670eae1ed1"></a>GDB


### <a id="5f4381b0a90d88dd2296c2936f7e7f70"></a>Tools


- [**7019**stars][10d] [JS] [cs01/gdbgui](https://github.com/cs01/gdbgui) Browser-based frontend to gdb (gnu debugger). Add breakpoints, view the stack, visualize data structures, and more in C, C++, Go, Rust, and Fortran. Run gdbgui from the terminal and a new tab will open in your browser.
- [**6052**stars][13d] [Py] [cyrus-and/gdb-dashboard](https://github.com/cyrus-and/gdb-dashboard) Modular visual interface for GDB in Python
- [**3784**stars][11m] [Py] [longld/peda](https://github.com/longld/peda) Python Exploit Development Assistance for GDB
- [**2568**stars][1m] [Py] [hugsy/gef](https://github.com/hugsy/gef) gdb增强工具，使用Python API，用于漏洞开发和逆向分析。
- [**2439**stars][16d] [Py] [pwndbg/pwndbg](https://github.com/pwndbg/pwndbg) GDB插件，辅助漏洞开发和逆向
- [**1417**stars][3m] [Go] [hellogcc/100-gdb-tips](https://github.com/hellogcc/100-gdb-tips) A collection of gdb tips. 100 maybe just mean many here.
- [**452**stars][3m] [Py] [scwuaptx/pwngdb](https://github.com/scwuaptx/pwngdb) gdb for pwn
- [**446**stars][1y] [Py] [jfoote/exploitable](https://github.com/jfoote/exploitable) The 'exploitable' GDB plugin. I don't work at CERT anymore, but here is the original homepage:
- [**244**stars][2m] [JS] [bet4it/hyperpwn](https://github.com/bet4it/hyperpwn) A hyper plugin to provide a flexible GDB GUI with the help of GEF, pwndbg or peda
- [**208**stars][2m] [Py] [sakhnik/nvim-gdb](https://github.com/sakhnik/nvim-gdb) Neovim thin wrapper for GDB, LLDB and PDB


### <a id="37b17362d72f9c8793973bc4704893a2"></a>Articles


- 2019.11 [ocallahan] [Supercharging Gdb With Pernosco](https://robert.ocallahan.org/2019/11/supercharging-gdb-with-pernosco.html)
- 2019.10 [FOSSiFoundation] [A Unified Debug Server for Deeply Embedded Systems and GDB/LLDB - Simon Cook - ORConf 2019](https://www.youtube.com/watch?v=bfxHGq2m8M8)
- 2019.10 [TheLinuxFoundation] [Using Serial kdb / kgdb to Debug the Linux Kernel - Douglas Anderson, Google](https://www.youtube.com/watch?v=HBOwoSyRmys)
- 2019.09 [GNUToolsCauldron] [GDB: Tab-Completion & Command Options - GNU Tools Cauldron 2019](https://www.youtube.com/watch?v=jEllWJ0at9o)
- 2019.09 [GNUToolsCauldron] [GDB on s390x: To-dos and Challenges - GNU Tools Cauldron 2019](https://www.youtube.com/watch?v=iQAd5Atlz1s)
- 2019.09 [GNUToolsCauldron] [GDB BoF - GNU Tools Cauldron 2019](https://www.youtube.com/watch?v=vdzpbnGDvZM)
- 2019.09 [GNUToolsCauldron] [A New Debug Server for Supporting GDB on Embedded Platforms - GNU Tools Cauldron 2019](https://www.youtube.com/watch?v=mQYKEzWAoqI)
- 2019.05 [tunnelshade] [Quick linux kernel with gdb setup with little help from Linux distros](https://tunnelshade.in/blog/2019/05/linux-kernel-gdb-setup/)
- 2019.02 [360] [ARM汇编之堆栈溢出实战分析四(GDB)](https://www.anquanke.com/post/id/170651/)
- 2019.01 [freebuf] [ARM汇编之堆栈溢出实战分析三（GDB）](https://www.freebuf.com/news/193664.html)
- 2019.01 [360] [ARM汇编之堆栈溢出实战分析二(GDB)](https://www.anquanke.com/post/id/169186/)
- 2019.01 [360] [ARM汇编之堆栈溢出实战分析（GDB）](https://www.anquanke.com/post/id/169071/)
- 2018.09 [blackroomsec] [Reversing small crackme w/ GDB-Peda](https://www.blackroomsec.com/reversing-small-crackme-w-gdb-peda/)
- 2018.09 [doyler] [Metasploit adduser Analysis via GDB (SLAE Exam Assignment #5.2)](https://www.doyler.net/security-not-included/metasploit-adduser-analysis)
- 2018.07 [pediy] [[编程][翻译]　用 gdb 学 C 语言](https://bbs.pediy.com/thread-229985.htm)
- 2018.05 [djmanilaice] [Ignorance .gdbinit](http://djmanilaice.blogspot.com/2018/05/ignorance-gdbinit.html)
- 2018.05 [360] [DEFCON CHINA议题解读 | Triton和符号执行在 GDB 上](https://www.anquanke.com/post/id/144984/)
- 2018.03 [aliyun] [利用GDB实现进程注入](https://xz.aliyun.com/t/2164)
- 2018.02 [freebuf] [GDB调试CVE-2018-5711 PHP-GD拒绝服务漏洞](http://www.freebuf.com/vuls/162029.html)
- 2018.02 [HITCON] [[HITCON CMT 2017] R0D202 - 陳威伯 - Triton and Symbolic execution on GDB](https://www.youtube.com/watch?v=LOTQIAVXdCI)




***


## <a id="70e64e3147675c9bcd48d4f475396e7f"></a>Monitor&&监控&&Trace&&追踪


### <a id="cd76e644d8ddbd385939bb17fceab205"></a>Tools


- [**1419**stars][9m] [C] [namhyung/uftrace](https://github.com/namhyung/uftrace) Function (graph) tracer for user-space




# <a id="86cb7d8f548ca76534b5828cb5b0abce"></a>Radare2


***


## <a id="0e08f9478ed8388319f267e75e2ef1eb"></a>Plugins&&Scripts


### <a id="ec3f0b5c2cf36004c4dd3d162b94b91a"></a>Radare2


- [**11588**stars][12d] [C] [radareorg/radare2](https://github.com/radareorg/radare2) unix-like reverse engineering framework and commandline tools


### <a id="6922457cb0d4b6b87a34caf39aa31dfe"></a>Recently Added


- [**410**stars][6m] [Py] [itayc0hen/a-journey-into-radare2](https://github.com/itayc0hen/a-journey-into-radare2) A series of tutorials about radare2 framework from
- [**339**stars][28d] [TeX] [radareorg/radare2book](https://github.com/radareorg/radare2book) Radare2 official book
- [**259**stars][1m] [C] [radareorg/r2dec-js](https://github.com/radareorg/r2dec-js) radare2插件,将汇编代码反编译为C伪代码
- [**258**stars][4m] [Rust] [radareorg/radeco](https://github.com/radareorg/radeco) radare2-based decompiler and symbol executor
- [**202**stars][3m] [PS] [wiredpulse/posh-r2](https://github.com/wiredpulse/posh-r2) PowerShell - Rapid Response... For the incident responder in you!


### <a id="1a6652a1cb16324ab56589cb1333576f"></a>Interoperability with Other Tools


#### <a id="dfe53924d678f9225fc5ece9413b890f"></a>Uncategorised


- [**378** stars][27d] [JS] [nowsecure/r2frida](https://github.com/nowsecure/r2frida) Integrates Radare2 and Frida.
    - 重复区段: [DBI->Frida->工具->与其他工具交互->Radare2](#ac053c4da818ca587d57711d2ff66278) |


#### <a id="1cfe869820ecc97204a350a3361b31a7"></a>IDA






### <a id="f7778a5392b90b03a3e23ef94a0cc3c6"></a>GUI


#### <a id="8f151d828263d3bc038f75f8d6418758"></a>GUI




#### <a id="df45c3c60bd074e21d650266aa85c241"></a>Cutter


- [**6176**stars][8d] [C++] [radareorg/cutter](https://github.com/radareorg/cutter) 逆向框架 radare2的Qt界面，iaito的升级版






***


## <a id="95fdc7692c4eda74f7ca590bb3f12982"></a>Articles and Videos


### <a id="a4debf888d112b91e56c90136f513ec0"></a>Uncategorised


- 2019.10 [prsecurity] [Radare2 for RE CTF](https://medium.com/p/e0163cb0466e)
- 2019.09 [securityartwork] [YaraRET (I): Carving with Radare2 & Yara](https://www.securityartwork.es/2019/09/02/yararet-i-carving-with-radare2-yara/)
- 2019.07 [freebuf] [教你使用Cutter和Radare2对APT32恶意程序流程图进行反混淆处理](https://www.freebuf.com/articles/network/208019.html)
- 2019.07 [THER] [0x0D - FLARE-On #3 Challenge Part 2 [Reversing with Radare2]](https://www.youtube.com/watch?v=QP9Cepdqf-o)
- 2019.07 [THER] [0x09 Cross References [Reversing with Radare2]](https://www.youtube.com/watch?v=yOtx6LL_R08)
- 2019.07 [THER] [0x08 Navigation [Reversing with Radare2]](https://www.youtube.com/watch?v=rkygJSjJbso)
- 2019.07 [THER] [0x04 Target Application [Reversing with Radare2]](https://www.youtube.com/watch?v=jlr3FablVIc)
- 2019.06 [THER] [0x03 Environment Setup [Reversing with Radare2]](https://www.youtube.com/watch?v=qGSFk_CkIaw)
- 2019.06 [THER] [0x02 What is Radare2 [Reversing with Radare2]](https://www.youtube.com/watch?v=9fLfD2fZWiA)
- 2019.06 [THER] [0x00 Intro [Reversing with Radare2]](https://www.youtube.com/watch?v=Lva32dXS0mU)
- 2019.06 [hitbsecconf] [#HITB2019AMS D1T3 - Overcoming Fear: Reversing With Radare2 - Arnau Gamez Montolio](https://www.youtube.com/watch?v=317dNavABKo)
- 2019.05 [X0x0FFB347] [Solving MalwareTech Shellcode challenges with some radare2 magic!](https://medium.com/p/b91c85babe4b)
- 2019.05 [360] [使用Cutter和Radare2对APT32恶意程序流程图进行反混淆处理](https://www.anquanke.com/post/id/178047/)
- 2019.05 [SagiDana] [Radare2 — Keep It Or Leave It?](https://medium.com/p/3d45059ec0d1)
- 2019.04 [X0x0FFB347] [Solving MalwareTech String Challenges With Some Radare2 Magic!](https://medium.com/p/98ebd8ff0b88)
- 2019.04 [radare] [Radare2 Summer of Code 2019 Selection Results](https://radareorg.github.io/blog/posts/rsoc-2019-selection/)
- 2019.04 [radare] [Radare2 Summer of Code 2019 Selection Results](http://radare.today/posts/rsoc-2019-selection/)
- 2019.03 [sans] [Binary Analysis with Jupyter and Radare2](https://isc.sans.edu/forums/diary/Binary+Analysis+with+Jupyter+and+Radare2/24748/)
- 2019.02 [freebuf] [Radare2：一款类Unix命令行逆向安全框架](https://www.freebuf.com/sectool/195703.html)
- 2019.02 [radare] [Radare2 Community Survey Results](http://radare.today/posts/radare2-survey/)


### <a id="d86e19280510aee0bcf2599f139cfbf7"></a>Cutter


- 2019.12 [megabeets] [5 Ways to patch binaries with Cutter](https://www.megabeets.net/5-ways-to-patch-binaries-with-cutter/)
- 2019.07 [THER] [0x0C - Cutter: FLARE-On #3 Challenge Part 1 [Reversing with Radare2]](https://www.youtube.com/watch?v=hbEpVwD5rJI)
- 2018.10 [PancakeNopcode] [r2con2018 - Cutter by @xarkes](https://www.youtube.com/watch?v=w8Bl5ZSmmZM)
- 2018.08 [radare] [GSoC 2018 Final: Debugging and Emulation Support for Cutter](https://radareorg.github.io/blog/posts/cutter_debug/)
- 2017.12 [n0where] [Qt C++ radare2 GUI: Cutter](https://n0where.net/qt-c-radare2-gui-cutter)




# <a id="afb7259851922935643857c543c4b0c2"></a>BinaryNinja


***


## <a id="3034389f5aaa9d7b0be6fa7322340aab"></a>Plugins&&Scripts


### <a id="a750ac8156aa0ff337a8639649415ef1"></a>Recently Added


- [**2820**stars][1m] [Py] [androguard/androguard](https://github.com/androguard/androguard) Reverse engineering, Malware and goodware analysis of Android applications ... and more (ninja !)
- [**328**stars][5m] [Py] [vector35/binaryninja-api](https://github.com/vector35/binaryninja-api) Public API, examples, documentation and issues for Binary Ninja
- [**280**stars][3m] [Py] [pbiernat/ripr](https://github.com/pbiernat/ripr) Package Binary Code as a Python class using Binary Ninja and Unicorn Engine
- [**201**stars][14d] [JS] [ret2got/disasm.pro](https://github.com/ret2got/disasm.pro) A realtime assembler/disassembler (formerly known as disasm.ninja)


### <a id="bba1171ac550958141dfcb0027716f41"></a>Interoperability with Other Tools


#### <a id="c2f94ad158b96c928ee51461823aa953"></a>Uncategorised




#### <a id="713fb1c0075947956651cc21a833e074"></a>IDA








***


## <a id="2d24dd6f0c01a084e88580ad22ce5b3c"></a>Articles and Videos


- 2019.08 [trailofbits] [Reverse Taint Analysis Using Binary Ninja](http://blog.trailofbits.com/2019/08/29/reverse-taint-analysis-using-binary-ninja/)
- 2018.09 [aliyun] [使用Binary Ninja调试共享库](https://xz.aliyun.com/t/2826)
- 2018.09 [kudelskisecurity] [Analyzing ARM Cortex-based MCU firmwares using Binary Ninja](https://research.kudelskisecurity.com/2018/09/25/analyzing-arm-cortex-based-mcu-firmwares-using-binary-ninja/)
- 2018.07 [aliyun] [WCTF 2018  -   binja - rswc](https://xz.aliyun.com/t/2436)
- 2018.04 [trailofbits] [使用Binary Ninja的MLIL和SSA, 挖掘二进制文件的漏洞. (MLIL: Medium Level IL, 中间层IL)(SSA: Single Static Assignment)](https://blog.trailofbits.com/2018/04/04/vulnerability-modeling-with-binary-ninja/)
- 2018.01 [pediy] [[翻译]逆向平台Binary Ninja介绍](https://bbs.pediy.com/thread-224141.htm)
- 2017.11 [] [bnpy - A python architecture plugin for Binary Ninja](https://0xec.blogspot.com/2017/11/bnpy-python-architecture-plugin-for.html)
- 2017.10 [ret2] [Untangling Exotic Architectures with Binary Ninja](http://blog.ret2.io/2017/10/17/untangling-exotic-architectures-with-binary-ninja/)
- 2017.10 [chokepoint] [Pin Visual Coverage Tool for Binary Ninja](http://www.chokepoint.net/2017/10/pin-visual-coverage-tool-for-binary.html)
- 2017.03 [GynvaelEN] [Hacking Livestream #14: Binary Ninja Plugins (with carstein)](https://www.youtube.com/watch?v=c9Tn2nEPp7A)
- 2016.12 [kchung] [Binary Ninja: IPython and the Python Console](https://blog.kchung.co/binary-ninja-ipython-and-the-python-console/)
- 2016.03 [arm] [Introduction to the Binary Ninja API](http://arm.ninja/2016/03/08/intro-to-binary-ninja-api/)


# <a id="2f81493de610f9b796656b269380b2de"></a>Windows


***


## <a id="620af0d32e6ac1f4a3e97385d4d3efc0"></a>PE


### <a id="574db8bbaafbee72eeb30e28e2799458"></a>Tools


- [**877**stars][8m] [Py] [erocarrera/pefile](https://github.com/erocarrera/pefile) pefile is a Python module to read and work with PE (Portable Executable) files
- [**634**stars][10d] [C] [thewover/donut](https://github.com/thewover/donut) Generates x86, x64, or AMD64+x86 position-independent shellcode that loads .NET Assemblies, PE files, and other Windows payloads from memory and runs them with parameters
- [**537**stars][1y] [C#] [ghostpack/safetykatz](https://github.com/ghostpack/safetykatz) Mimikatz和 .NET PE Loader的结合
- [**388**stars][1y] [Assembly] [hasherezade/pe_to_shellcode](https://github.com/hasherezade/pe_to_shellcode) Converts PE into a shellcode
- [**385**stars][3m] [Jupyter Notebook] [endgameinc/ember](https://github.com/endgameinc/ember) 110万PE文件的数据集合, 可用于训练相关模型. PE文件信息主要包括: SHA256/histogram(直方图)/byteentropy(字节熵)/字符串/PE头信息/段信息/导入表/导出表
- [**344**stars][1y] [Assembly] [egebalci/amber](https://github.com/egebalci/amber) 反射式PE加壳器，用于绕过安全产品和缓解措施
- [**337**stars][5m] [C] [merces/pev](https://github.com/merces/pev) The PE file analysis toolkit
- [**316**stars][24d] [C++] [trailofbits/pe-parse](https://github.com/trailofbits/pe-parse) Principled, lightweight C/C++ PE parser
- [**315**stars][14d] [VBA] [itm4n/vba-runpe](https://github.com/itm4n/vba-runpe) A VBA implementation of the RunPE technique or how to bypass application whitelisting.
- [**296**stars][12d] [C++] [hasherezade/libpeconv](https://github.com/hasherezade/libpeconv) 用于映射和取消映射PE 文件的库
- [**285**stars][7m] [Java] [katjahahn/portex](https://github.com/katjahahn/portex) Java library to analyse Portable Executable files with a special focus on malware analysis and PE malformation robustness


### <a id="7e890d391fa32df27beb1377a371518b"></a>Articles


- 2019.12 [aliyun] [手工shellcode注入PE文件](https://xz.aliyun.com/t/6939)
- 2019.10 [freebuf] [PEpper：一款针对可执行程序的开源恶意软件静态分析工具](https://www.freebuf.com/sectool/214265.html)
- 2019.09 [sevagas] [Process PE Injection Basics](https://blog.sevagas.com/?Process-PE-Injection-Basics)
- 2019.07 [hexacorn] [PE Section names – re-visited, again](http://www.hexacorn.com/blog/2019/07/26/pe-section-names-re-visited-again/)
- 2019.06 [hasherezade] [PE-sieve v0.2.1 release notes - import recovery & unpacking ASPack (part 2)](https://www.youtube.com/watch?v=-YVrU4-507A)
- 2019.05 [0x00sec] [Backdoorin pe files](https://0x00sec.org/t/backdoorin-pe-files/13912/)
- 2019.05 [360] [Windows调试艺术——PE文件变形（一）](https://www.anquanke.com/post/id/178088/)
- 2019.05 [arxiv] [[1905.01999] A Benchmark API Call Dataset for Windows PE Malware Classification](https://arxiv.org/abs/1905.01999)
- 2019.04 [decoder] [Combinig LUAFV PostLuafvPostReadWrite Race Condition PE with DiagHub collector exploit -> from standard user to SYSTEM](https://decoder.cloud/2019/04/29/combinig-luafv-postluafvpostreadwrite-race-condition-pe-with-diaghub-collector-exploit-from-standard-user-to-system/)
- 2019.04 [MalwareAnalysisForHedgehogs] [Malware Theory - PE Malformations and Anomalies](https://www.youtube.com/watch?v=-0DEEbQq8jU)
- 2019.04 [freebuf] [Xori：一款针对PE32和Shellcode的自动化反编译与静态分析库](https://www.freebuf.com/sectool/199629.html)
- 2019.03 [hexacorn] [PE files and the DemoScene](http://www.hexacorn.com/blog/2019/03/14/pe-files-and-the-demoscene/)
- 2019.03 [] [携带恶意PE文件的壁纸类应用出现在Google Play](http://blogs.360.cn/post/malicious_PE_files_discovered_on_Google%20Play.html)
- 2019.03 [] [携带恶意PE文件的壁纸类应用出现在Google Play](http://blogs.360.cn/post/malicious_PE_files_discovered_on_Google%20Play.html)
- 2019.03 [] [Malicious PE files discovered on Google Play](http://blogs.360.cn/post/malicious_PE_files_discovered_on_GooglePlay_EN.html)
- 2019.03 [hexacorn] [PE Compilation Timestamps vs. forensics](http://www.hexacorn.com/blog/2019/03/11/pe-compilation-timestamps-vs-forensics/)
- 2019.03 [cristivlad25] [Machine Learning for Malware Detection - 4 - Portable Executable (PE) Files](https://www.youtube.com/watch?v=2Pr6MNcXLFE)
- 2019.03 [hexacorn] [Extracting and Parsing PE signatures en masse](http://www.hexacorn.com/blog/2019/03/03/extracting-and-parsing-pe-signatures-en-masse/)
- 2019.02 [hexacorn] [PE files and the Easy Programming Language (EPL)](http://www.hexacorn.com/blog/2019/02/13/pe-files-and-the-easy-programming-language-epl/)
- 2019.01 [pediy] [[原创]PE加载器的简单实现](https://bbs.pediy.com/thread-249133.htm)




***


## <a id="89f963773ee87e2af6f9170ee60a7fb2"></a>DLL


### <a id="4dcfd9135aa5321b7fa65a88155256f9"></a>Recently Added


#### <a id="9753a9d52e19c69dc119bf03e9d7c3d2"></a>Tools


- [**1915**stars][22d] [C#] [lucasg/dependencies](https://github.com/lucasg/dependencies) A rewrite of the old legacy software "depends.exe" in C# for Windows devs to troubleshoot dll load dependencies issues.
- [**1333**stars][10m] [C] [fancycode/memorymodule](https://github.com/fancycode/memorymodule) Library to load a DLL from memory.
- [**1146**stars][27d] [C#] [perfare/il2cppdumper](https://github.com/perfare/il2cppdumper) Restore dll from Unity il2cpp binary file (except code)
- [**793**stars][11m] [C#] [terminals-origin/terminals](https://github.com/terminals-origin/terminals) Terminals is a secure, multi tab terminal services/remote desktop client. It uses Terminal Services ActiveX Client (mstscax.dll). The project started from the need of controlling multiple connections simultaneously. It is a complete replacement for the mstsc.exe (Terminal Services) client. This is official source moved from Codeplex.
- [**388**stars][7m] [C++] [hasherezade/dll_to_exe](https://github.com/hasherezade/dll_to_exe) Converts a DLL into EXE
- [**363**stars][19d] [C#] [3f/dllexport](https://github.com/3f/dllexport) .NET DllExport
- [**240**stars][10m] [C++] [wbenny/detoursnt](https://github.com/wbenny/detoursnt) Detours with just single dependency - NTDLL
- [**230**stars][1y] [C#] [misaka-mikoto-tech/monohooker](https://github.com/Misaka-Mikoto-Tech/MonoHooker) hook C# method at runtime without modify dll file (such as UnityEditor.dll)
- [**215**stars][6m] [C#] [erfg12/memory.dll](https://github.com/erfg12/memory.dll) C# Hacking library for making PC game trainers.
- [**214**stars][26d] [C++] [chuyu-team/mint](https://github.com/Chuyu-Team/MINT) Contains the definitions for the Windows Internal UserMode API from ntdll.dll, samlib.dll and winsta.dll.


#### <a id="b05f4c5cdfe64e1dde2a3c8556e85827"></a>Articles


- 2019.12 [freebuf] [如何使用ADSI接口和反射型DLL枚举活动目录](https://www.freebuf.com/articles/system/218855.html)
- 2019.11 [tyranidslair] [The Internals of AppLocker - Part 4 - Blocking DLL Loading](https://tyranidslair.blogspot.com/2019/11/the-internals-of-applocker-part-4.html)
- 2019.09 [hexacorn] [RunDll32 — API calling](http://www.hexacorn.com/blog/2019/09/28/rundll32-api-calling/)
- 2019.09 [4hou] [《MiniDumpWriteDump via COM+ Services DLL》的利用测试](https://www.4hou.com/technology/20146.html)
- 2019.08 [osandamalith] [Converting an EXE to a DLL](https://osandamalith.com/2019/08/26/converting-an-exe-to-a-dll/)
- 2019.06 [4hou] [域渗透——利用dnscmd在DNS服务器上实现远程加载Dll](https://www.4hou.com/penetration/18447.html)
- 2019.06 [hexacorn] [Playing with Delay-Loaded DLLs…](http://www.hexacorn.com/blog/2019/06/03/playing-with-delay-loaded-dlls/)
- 2019.05 [3gstudent] [域渗透——利用dnscmd在DNS服务器上实现远程加载Dll](https://3gstudent.github.io/3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-%E5%88%A9%E7%94%A8dnscmd%E5%9C%A8DNS%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E5%AE%9E%E7%8E%B0%E8%BF%9C%E7%A8%8B%E5%8A%A0%E8%BD%BDDll/)
- 2019.05 [3gstudent] [域渗透——利用dnscmd在DNS服务器上实现远程加载Dll](https://3gstudent.github.io/3gstudent.github.io/%E5%9F%9F%E6%B8%97%E9%80%8F-%E5%88%A9%E7%94%A8dnscmd%E5%9C%A8DNS%E6%9C%8D%E5%8A%A1%E5%99%A8%E4%B8%8A%E5%AE%9E%E7%8E%B0%E8%BF%9C%E7%A8%8B%E5%8A%A0%E8%BD%BDDll/)
- 2019.05 [4sysops] [PS Protector: Convert your PowerShell module into a .NET assembly DLL](https://4sysops.com/archives/ps-protector-convert-your-powershell-module-into-a-net-assembly-dll/)
- 2019.05 [0x00sec] [Malicious DLL execution using Apple's APSDaemon.exe signed binary](https://0x00sec.org/t/malicious-dll-execution-using-apples-apsdaemon-exe-signed-binary/13409/)
- 2019.04 [4hou] [Qt5漏洞导致Cisco WebEx和Malwarebytes反病毒产品可远程加载任意DLL](https://www.4hou.com/vulnerable/17257.html)
- 2019.04 [id] [DLL CryptoMix](http://id-ransomware.blogspot.com/2019/04/dll-cryptomix-ransomware.html)
- 2019.03 [CyborgElf] [How To Make an Internal DLL Game Hack C++ (Rainbow Six Siege)](https://www.youtube.com/watch?v=wrIPVBXXisc)
- 2019.02 [] [No Source Code For a 14-Year Old Vulnerable DLL? No Problem. (CVE-2018-20250)](https://blog.0patch.com/2019/02/no-source-code-for-14-year-old.html)
- 2018.12 [srcincite] [思科Webex桌面会议App提权漏洞, 可导致RCE](https://srcincite.io/blog/2018/12/03/webexec-reloaded-cisco-webex-meetings-desktop-app-lpe.html)




### <a id="3b4617e54405a32290224b729ff9f2b3"></a>DLL注入


#### <a id="b0d50ee42d53b1f88b32988d34787137"></a>Tools


- [**713**stars][5m] [C++] [darthton/xenos](https://github.com/darthton/xenos) Windows DLL 注入器
- [**588**stars][2m] [PS] [monoxgas/srdi](https://github.com/monoxgas/srdi) Shellcode implementation of Reflective DLL Injection. Convert DLLs to position independent shellcode


#### <a id="1a0b0dab4cdbab08bbdc759bab70dbb6"></a>Articles


- 2019.12 [freebuf] [如何防止恶意的第三方DLL注入到进程](https://www.freebuf.com/articles/system/219198.html)
- 2019.06 [aliyun] [Windows 10 Task Scheduler服务DLL注入漏洞分析](https://xz.aliyun.com/t/5286)
- 2018.10 [pediy] [[原创]代替创建用户线程使用ShellCode注入DLL的小技巧](https://bbs.pediy.com/thread-247515.htm)
- 2018.10 [4hou] [如何利用DLL注入绕过Win10勒索软件保护](http://www.4hou.com/technology/13923.html)
- 2018.10 [0x00sec] [Reflective Dll Injection - Any Way to check If a process is already injected?](https://0x00sec.org/t/reflective-dll-injection-any-way-to-check-if-a-process-is-already-injected/8980/)
- 2018.09 [pediy] [[原创]win10_arm64 驱动注入dll 到 arm32程序](https://bbs.pediy.com/thread-247032.htm)
- 2018.08 [freebuf] [sRDI：一款通过Shellcode实现反射型DLL注入的强大工具](http://www.freebuf.com/sectool/181426.html)
- 2018.07 [4hou] [注入系列——DLL注入](http://www.4hou.com/technology/12703.html)
- 2018.06 [0x00sec] [Reflective DLL Injection - AV detects at runtime](https://0x00sec.org/t/reflective-dll-injection-av-detects-at-runtime/7307/)
- 2018.06 [qq] [【游戏漏洞】注入DLL显示游戏窗口](http://gslab.qq.com/article-508-1.html)
- 2017.12 [secist] [Mavinject | Dll Injected](http://www.secist.com/archives/5912.html)
- 2017.12 [secvul] [SSM终结dll注入](https://secvul.com/topics/951.html)
- 2017.10 [nsfocus] [【干货分享】Sandbox技术之DLL注入](http://blog.nsfocus.net/sandbox-technology-dll-injection/)
- 2017.10 [freebuf] [DLL注入新姿势：反射式DLL注入研究](http://www.freebuf.com/articles/system/151161.html)
- 2017.10 [pediy] [[原创]通过Wannacry分析内核shellcode注入dll技术](https://bbs.pediy.com/thread-221756.htm)
- 2017.09 [360] [Dll注入新姿势：SetThreadContext注入](https://www.anquanke.com/post/id/86786/)
- 2017.08 [silentbreaksecurity] [sRDI – Shellcode Reflective DLL Injection](https://silentbreaksecurity.com/srdi-shellcode-reflective-dll-injection/)
- 2017.08 [360] [DLL注入那些事](https://www.anquanke.com/post/id/86671/)
- 2017.08 [freebuf] [系统安全攻防战：DLL注入技术详解](http://www.freebuf.com/articles/system/143640.html)
- 2017.08 [pediy] [[翻译]多种DLL注入技术原理介绍](https://bbs.pediy.com/thread-220405.htm)




### <a id="f39e40e340f61ae168b67424baac5cc6"></a>DLL劫持


#### <a id="c9cdcc6f4acbeda6c8ac8f4a1ba1ea6b"></a>Tools


- [**431**stars][7m] [Pascal] [mojtabatajik/robber](https://github.com/mojtabatajik/robber) 查找易于发生DLL劫持的可执行文件
- [**299**stars][11m] [C++] [anhkgg/superdllhijack](https://github.com/anhkgg/superdllhijack) 一种通用Dll劫持技术，不再需要手工导出Dll的函数接口了


#### <a id="01e95333e07439ac8326253aa8950b4f"></a>Articles


- 2019.06 [4hou] [戴尔预装的SupportAssist组件存在DLL劫持漏洞，全球超过1亿台设备面临网络攻击风险](https://www.4hou.com/vulnerable/18764.html)
- 2019.05 [4hou] [《Lateral Movement — SCM and DLL Hijacking Primer》的利用扩展](https://www.4hou.com/technology/18008.html)
- 2019.04 [3gstudent] [《Lateral Movement — SCM and DLL Hijacking Primer》的利用扩展](https://3gstudent.github.io/3gstudent.github.io/Lateral-Movement-SCM-and-DLL-Hijacking-Primer-%E7%9A%84%E5%88%A9%E7%94%A8%E6%89%A9%E5%B1%95/)
- 2019.04 [3gstudent] [《Lateral Movement — SCM and DLL Hijacking Primer》的利用扩展](https://3gstudent.github.io/3gstudent.github.io/Lateral-Movement-SCM-and-DLL-Hijacking-Primer-%E7%9A%84%E5%88%A9%E7%94%A8%E6%89%A9%E5%B1%95/)
- 2019.04 [specterops] [Lateral Movement — SCM and Dll Hijacking Primer](https://medium.com/p/d2f61e8ab992)
- 2019.01 [sans] [DLL Hijacking Like a Boss!](https://www.sans.org/cyber-security-summit/archives/file/summit_archive_1493862085.pdf)
- 2018.11 [t00ls] [一种通用DLL劫持技术研究](https://www.t00ls.net/articles-48756.html)
- 2018.11 [pediy] [[原创]一种通用DLL劫持技术研究](https://bbs.pediy.com/thread-248050.htm)
- 2018.09 [DoktorCranium] [Understanding how DLL Hijacking works](https://www.youtube.com/watch?v=XADSrZEJdXY)
- 2018.09 [astr0baby] [Understanding how DLL Hijacking works](https://astr0baby.wordpress.com/2018/09/08/understanding-how-dll-hijacking-works/)
- 2018.08 [parsiya] [DVTA - Part 5 - Client-side Storage and DLL Hijacking](https://parsiya.net/blog/2018-08-25-dvta-part-5-client-side-storage-and-dll-hijacking/)
- 2018.08 [parsiya] [DVTA - Part 5 - Client-side Storage and DLL Hijacking](https://parsiya.net/blog/2018-08-25-dvta---part-5---client-side-storage-and-dll-hijacking/)
- 2018.06 [cybereason] [Attackers incriminate a signed Oracle process for DLL hijacking, running Mimikatz](https://www.cybereason.com/blog/oracle-mimikatz-dll-hijacking)
- 2018.05 [360] [独辟蹊径：如何通过URL文件实现DLL劫持](https://www.anquanke.com/post/id/145715/)
- 2018.05 [insert] [利用URL文件实现DLL劫持](https://insert-script.blogspot.com/2018/05/dll-hijacking-via-url-files.html)
- 2017.10 [cybereason] [Siofra, a free tool built by Cybereason researcher, exposes DLL hijacking vulnerabilities in Windows programs](https://www.cybereason.com/blog/blog-siofra-free-tool-exposes-dll-hijacking-vulnerabilities-in-windows)
- 2017.08 [securiteam] [SSD Advisory – Dashlane DLL Hijacking](https://blogs.securiteam.com/index.php/archives/3357)
- 2017.05 [4hou] [Windows 下的 7 种 DLL 劫持技术](http://www.4hou.com/technology/4945.html)
- 2017.05 [pediy] [[原创]让代码飞出一段钢琴曲（freepiano小助手）（全局键盘钩子+dll劫持）+有码](https://bbs.pediy.com/thread-217330.htm)
- 2017.03 [pentestlab] [DLL Hijacking](https://pentestlab.blog/2017/03/27/dll-hijacking/)






***


## <a id="40fd1488e4a26ebf908f44fdcedd9675"></a>UAC


### <a id="02517eda8c2519c564a19219e97d6237"></a>Tools


- [**2355**stars][11d] [C] [hfiref0x/uacme](https://github.com/hfiref0x/uacme) Defeating Windows User Account Control
- [**2307**stars][1m] [PS] [k8gege/k8tools](https://github.com/k8gege/k8tools) K8工具合集(内网渗透/提权工具/远程溢出/漏洞利用/扫描工具/密码破解/免杀工具/Exploit/APT/0day/Shellcode/Payload/priviledge/BypassUAC/OverFlow/WebShell/PenTest) Web GetShell Exploit(Struts2/Zimbra/Weblogic/Tomcat/Apache/Jboss/DotNetNuke/zabbix)
- [**1688**stars][3m] [Py] [rootm0s/winpwnage](https://github.com/rootm0s/winpwnage) UAC bypass, Elevate, Persistence and Execution methods


### <a id="90d7d5feb7fd506dc8fd6ee0d7e98285"></a>Articles


- 2019.11 [4hou] [CVE-2019-1388： Windows UAC权限提升漏洞](https://www.4hou.com/info/news/21710.html)
- 2019.10 [freebuf] [UAC绕过初探](https://www.freebuf.com/articles/system/216337.html)
- 2019.09 [4sysops] [Security options in Windows Server 2016: Accounts and UAC](https://4sysops.com/archives/security-options-in-windows-server-2016-accounts-and-uac/)
- 2019.08 [freebuf] [SneakyEXE：一款嵌入式UAC绕过工具](https://www.freebuf.com/sectool/209097.html)
- 2019.04 [markmotig] [Brute Forcing Admin Passwords with UAC](https://medium.com/p/e711c551ad7e)
- 2019.03 [4hou] [通过模拟可信目录绕过UAC的利用分析](https://www.4hou.com/technology/16713.html)
- 2019.03 [aliyun] [如何滥用Access Tokens UIAccess绕过UAC](https://xz.aliyun.com/t/4126)
- 2019.02 [3gstudent] [通过模拟可信目录绕过UAC的利用分析](https://3gstudent.github.io/3gstudent.github.io/%E9%80%9A%E8%BF%87%E6%A8%A1%E6%8B%9F%E5%8F%AF%E4%BF%A1%E7%9B%AE%E5%BD%95%E7%BB%95%E8%BF%87UAC%E7%9A%84%E5%88%A9%E7%94%A8%E5%88%86%E6%9E%90/)
- 2019.02 [3gstudent] [通过模拟可信目录绕过UAC的利用分析](https://3gstudent.github.io/3gstudent.github.io/%E9%80%9A%E8%BF%87%E6%A8%A1%E6%8B%9F%E5%8F%AF%E4%BF%A1%E7%9B%AE%E5%BD%95%E7%BB%95%E8%BF%87UAC%E7%9A%84%E5%88%A9%E7%94%A8%E5%88%86%E6%9E%90/)
- 2019.02 [sans] [UAC is not all that bad really](https://isc.sans.edu/forums/diary/UAC+is+not+all+that+bad+really/24620/)
- 2019.01 [fuzzysecurity] [Anatomy of UAC Attacks](http://fuzzysecurity.com/tutorials/27.html)
- 2019.01 [sevagas] [Yet another sdclt UAC bypass](https://blog.sevagas.com/?Yet-another-sdclt-UAC-bypass)
- 2018.11 [4hou] [利用metasploit绕过UAC的5种方式](http://www.4hou.com/system/13707.html)
- 2018.11 [tenable] [UAC Bypass by Mocking Trusted Directories](https://medium.com/p/24a96675f6e)
- 2018.10 [0x000x00] [How to bypass UAC in newer Windows versions](https://0x00-0x00.github.io/research/2018/10/31/How-to-bypass-UAC-in-newer-Windows-versions.html)
- 2018.10 [tyranidslair] [Farewell to the Token Stealing UAC Bypass](https://tyranidslair.blogspot.com/2018/10/farewell-to-token-stealing-uac-bypass.html)
- 2018.10 [freebuf] [使用Metasploit绕过UAC的多种方法](http://www.freebuf.com/articles/system/185311.html)
- 2018.09 [freebuf] [一种绕过UAC的技术介绍](http://www.freebuf.com/articles/system/184140.html)
- 2018.09 [hackingarticles] [Multiple Ways to Bypass UAC using Metasploit](http://www.hackingarticles.in/multiple-ways-to-bypass-uac-using-metasploit/)
- 2018.09 [hexacorn] [A bit of a qUACkery – how to elevate… w/o doing a single thing ;)](http://www.hexacorn.com/blog/2018/09/07/a-bit-of-a-quackery-how-to-elevate-w-o-doing-a-single-thing/)




***


## <a id="0fed6a96b28f339611e7b111b8f42c23"></a>Sysmon


### <a id="d48f038b58dc921660be221b4e302f70"></a>Tools


- [**206**stars][1y] [JS] [jpcertcc/sysmonsearch](https://github.com/jpcertcc/sysmonsearch) Investigate suspicious activity by visualizing Sysmon's event log


### <a id="2c8cb7fdf765b9d930569f7c64042d62"></a>Articles


- 2019.12 [vanimpe] [Use Sysmon DNS data for incident response](https://www.vanimpe.eu/2019/12/02/use-sysmon-dns-data-for-incident-response/)
- 2019.11 [4hou] [你不知道的威胁狩猎技巧：Windows API 与 Sysmon 事件的映射](https://www.4hou.com/system/21461.html)
- 2019.10 [HackersOnBoard] [Subverting Sysmon Application of a Formalized Security Product Evasion Methodology](https://www.youtube.com/watch?v=7eor4Gq1YXE)
- 2019.09 [sans] [Parsing Sysmon Events for IR Indicators](https://digital-forensics.sans.org/blog/2019/09/25/parsing-sysmon-events-for-ir-indicators)
- 2019.09 [blackhillsinfosec] [Getting Started With Sysmon](https://www.blackhillsinfosec.com/getting-started-with-sysmon/)
- 2019.09 [osandamalith] [Unloading the Sysmon Minifilter Driver](https://osandamalith.com/2019/09/22/unloading-the-sysmon-minifilter-driver/)
- 2019.09 [specterops] [Shhmon — Silencing Sysmon via Driver Unload](https://medium.com/p/682b5be57650)
- 2019.09 [4hou] [如何逃逸Sysmon工具对DNS的监控](https://www.4hou.com/web/18660.html)
- 2019.09 [olafhartong] [Sysmon 10.4 release](https://medium.com/p/7f7480300dff)
- 2019.09 [blackhillsinfosec] [Webcast: Windows logging, Sysmon, and ELK](https://www.blackhillsinfosec.com/webcast-windows-logging-sysmon-and-elk/)
- 2019.08 [blackhillsinfosec] [Webcast: Implementing Sysmon and Applocker](https://www.blackhillsinfosec.com/webcast-implementing-sysmon-and-applocker/)
- 2019.07 [eforensicsmag] [Using Sysmon and ETW For So Much More | By David Kennedy](https://eforensicsmag.com/using-sysmon-and-etw-for-so-much-more-by-david-kennedy/)
- 2019.06 [nosecurecode] [Sysmon in a Box](https://nosecurecode.com/2019/06/29/sysmon-in-a-box/)
- 2019.06 [binarydefense] [Using Sysmon and ETW For So Much More - Binary Defense](https://www.binarydefense.com/using-sysmon-and-etw-for-so-much-more/)
- 2019.06 [360] [如何规避Sysmon DNS监控](https://www.anquanke.com/post/id/180418/)
- 2019.06 [SecurityWeekly] [Sysmon DNS Logging, Gravwell - PSW #608](https://www.youtube.com/watch?v=e_E6F1G6b88)
- 2019.06 [xpnsec] [Evading Sysmon DNS Monitoring](https://blog.xpnsec.com/evading-sysmon-dns-monitoring/)
- 2019.06 [olafhartong] [Using Sysmon in Azure Sentinel](https://medium.com/p/883eb6ffc431)
- 2019.05 [olafhartong] [Sysmon 10.0 - New features and changes](https://medium.com/p/e82106f2e00)
- 2019.02 [specterops] [Putting Sysmon v9.0 AND/OR Grouping Logic to the Test](https://medium.com/p/c3ec27263df8)




***


## <a id="ac43a3ce5a889d8b18cf22acb6c31a72"></a>ETW


### <a id="0af4bd8ca0fd27c9381a2d1fa8b71a1f"></a>Tools


- [**1228**stars][10d] [JS] [jpcertcc/logontracer](https://github.com/jpcertcc/logontracer) 通过可视化和分析Windows事件日志来调查恶意的Windows登录
- [**865**stars][22d] [C++] [google/uiforetw](https://github.com/google/uiforetw) User interface for recording and managing ETW traces
- [**654**stars][10m] [Roff] [palantir/windows-event-forwarding](https://github.com/palantir/windows-event-forwarding) 使用 Windows 事件转发实现网络事件监测和防御
- [**609**stars][19d] [PS] [sbousseaden/evtx-attack-samples](https://github.com/sbousseaden/evtx-attack-samples) 与特定攻击和利用后渗透技术相关的Windows事件样例
- [**504**stars][10m] [C#] [lowleveldesign/wtrace](https://github.com/lowleveldesign/wtrace) Command line tracing tool for Windows, based on ETW.
- [**479**stars][5m] [PS] [sans-blue-team/deepbluecli](https://github.com/sans-blue-team/deepbluecli) a PowerShell Module for Threat Hunting via Windows Event Logs
- [**446**stars][9m] [PS] [nsacyber/event-forwarding-guidance](https://github.com/nsacyber/Event-Forwarding-Guidance) 帮助管理员使用Windows事件转发（WEF）收集与安全相关的Windows事件日志
- [**393**stars][10m] [Py] [williballenthin/python-evtx](https://github.com/williballenthin/python-evtx) 纯Python编写的Windows事件日志解析器
- [**341**stars][1y] [C++] [qax-a-team/eventcleaner](https://github.com/QAX-A-Team/EventCleaner) A tool mainly to erase specified records from Windows event logs, with additional functionalities.
- [**306**stars][1m] [C#] [zodiacon/procmonx](https://github.com/zodiacon/procmonx) 通过Windows事件日志获取与Process Monitor显示的相同的信息，无需内核驱动
- [**282**stars][3m] [C#] [fireeye/silketw](https://github.com/fireeye/silketw) flexible C# wrappers for ETW
- [**282**stars][10m] [C#] [nsacyber/windows-event-log-messages](https://github.com/nsacyber/Windows-Event-Log-Messages) 检索Windows二进制文件中嵌入的Windows事件日志消息的定义，并以discoverable的格式提供它们
- [**261**stars][3m] [C++] [gametechdev/presentmon](https://github.com/gametechdev/presentmon) Tool for collection and processing of ETW events related to DXGI presentation.
- [**249**stars][3m] [C++] [microsoft/krabsetw](https://github.com/microsoft/krabsetw) KrabsETW provides a modern C++ wrapper and a .NET wrapper around the low-level ETW trace consumption functions.


### <a id="11c4c804569626c1eb02140ba557bb85"></a>Articles


- 2019.12 [Cooper] [EventList, Matching Windows Event Log IDs With MITRE ATT&CK - Miriam Wiesner](https://www.youtube.com/watch?v=l5PpbOmopyA)
- 2019.09 [adventuresincyberchallenges] [Powershell Encoded Payload In Clear Text in Windows Event Log 4688](https://adventuresincyberchallenges.blogspot.com/2019/09/powershell-encoded-payload-in-clear.html)
- 2019.09 [Cyb3rWard0g] [Threat Hunting with ETW events and HELK — Part 2: Shipping ETW events to HELK ⚒](https://medium.com/p/16837116d2f5)
- 2019.09 [Cyb3rWard0g] [Threat Hunting with ETW events and HELK — Part 1: Installing SilkETW 🏄‍♀🏄](https://medium.com/p/6eb74815e4a0)
- 2019.05 [freebuf] [SilkETW：一款针对Windows事件追踪的自定义C#封装工具](https://www.freebuf.com/sectool/203531.html)
- 2019.04 [4sysops] [Forward Windows events to a Syslog server with free SolarWinds Event Log Forwarder for Windows](https://4sysops.com/archives/forward-windows-events-to-a-syslog-server-with-free-solarwinds-event-log-forwarder-for-windows/)
- 2019.02 [360] [ETW注册表监控windows内核实现原理](https://www.anquanke.com/post/id/171298/)
- 2019.01 [sans] [Rocking Your Windows EventID with ELK Stack](https://www.sans.org/cyber-security-summit/archives/file/summit_archive_1492181323.pdf)
- 2019.01 [sans] [Threat Hunting via Windows Event Logs](https://www.sans.org/cyber-security-summit/archives/file/summit_archive_1524493093.pdf)
- 2019.01 [sans] [Hunting for Lateral Movement Using Windows Event Log](https://www.sans.org/cyber-security-summit/archives/file/summit_archive_1536265369.pdf)
- 2018.12 [palantir] [Tampering with Windows Event Tracing: Background, Offense, and Defense](https://medium.com/p/4be7ac62ac63)
- 2018.12 [sophos] [Hunting for threats with Intercept X and the Windows Event Collector](https://news.sophos.com/en-us/2018/12/03/hunting-for-threats-with-intercept-x-and-the-windows-event-collector/)
- 2018.08 [4sysops] [Query multiple Windows event logs with PowerShell](https://4sysops.com/archives/query-multiple-windows-event-logs-with-powershell/)
- 2018.07 [criteo] [Grab ETW Session, Providers and Events](http://labs.criteo.com/2018/07/grab-etw-session-providers-and-events/)
- 2018.07 [3gstudent] [Windows Event Viewer Log (EVT)单条日志清除（三）——删除当前系统指定指定时间段evt日志记录](https://3gstudent.github.io/3gstudent.github.io/Windows-Event-Viewer-Log-(EVT)%E5%8D%95%E6%9D%A1%E6%97%A5%E5%BF%97%E6%B8%85%E9%99%A4-%E4%B8%89-%E5%88%A0%E9%99%A4%E5%BD%93%E5%89%8D%E7%B3%BB%E7%BB%9F%E6%8C%87%E5%AE%9A%E6%8C%87%E5%AE%9A%E6%97%B6%E9%97%B4%E6%AE%B5evt%E6%97%A5%E5%BF%97%E8%AE%B0%E5%BD%95/)
- 2018.07 [3gstudent] [Windows Event Viewer Log (EVT)单条日志清除（三）——删除当前系统指定指定时间段evt日志记录](https://3gstudent.github.io/3gstudent.github.io/Windows-Event-Viewer-Log-(EVT)%E5%8D%95%E6%9D%A1%E6%97%A5%E5%BF%97%E6%B8%85%E9%99%A4-%E4%B8%89-%E5%88%A0%E9%99%A4%E5%BD%93%E5%89%8D%E7%B3%BB%E7%BB%9F%E6%8C%87%E5%AE%9A%E6%8C%87%E5%AE%9A%E6%97%B6%E9%97%B4%E6%AE%B5evt%E6%97%A5%E5%BF%97%E8%AE%B0%E5%BD%95/)
- 2018.07 [pentesttoolz] [LogonTracer – Investigate Malicious Windows Logon By Visualizing And Analyzing Windows Event Log](https://pentesttoolz.com/2018/07/17/logontracer-investigate-malicious-windows-logon-by-visualizing-and-analyzing-windows-event-log/)
- 2018.07 [dragos] [EvtxToElk: A Python Module to Load Windows Event Logs into ElasticSearch](https://dragos.com/blog/20180717EvtxToElk.html)
- 2018.07 [3gstudent] [Windows Event Viewer Log (EVT)单条日志清除（二）——程序实现删除evt文件指定时间段的日志记录](https://3gstudent.github.io/3gstudent.github.io/Windows-Event-Viewer-Log-(EVT)%E5%8D%95%E6%9D%A1%E6%97%A5%E5%BF%97%E6%B8%85%E9%99%A4-%E4%BA%8C-%E7%A8%8B%E5%BA%8F%E5%AE%9E%E7%8E%B0%E5%88%A0%E9%99%A4evt%E6%96%87%E4%BB%B6%E6%8C%87%E5%AE%9A%E6%97%B6%E9%97%B4%E6%AE%B5%E7%9A%84%E6%97%A5%E5%BF%97%E8%AE%B0%E5%BD%95/)
- 2018.07 [3gstudent] [Windows Event Viewer Log (EVT)单条日志清除（二）——程序实现删除evt文件指定时间段的日志记录](https://3gstudent.github.io/3gstudent.github.io/Windows-Event-Viewer-Log-(EVT)%E5%8D%95%E6%9D%A1%E6%97%A5%E5%BF%97%E6%B8%85%E9%99%A4-%E4%BA%8C-%E7%A8%8B%E5%BA%8F%E5%AE%9E%E7%8E%B0%E5%88%A0%E9%99%A4evt%E6%96%87%E4%BB%B6%E6%8C%87%E5%AE%9A%E6%97%B6%E9%97%B4%E6%AE%B5%E7%9A%84%E6%97%A5%E5%BF%97%E8%AE%B0%E5%BD%95/)




***


## <a id="184bbacd8b9e08c30cc9ffcee9513f44"></a>AppLocker


### <a id="8f1876dff78e80b60d00de25994276d9"></a>Tools


- [**921**stars][7m] [PS] [api0cradle/ultimateapplockerbypasslist](https://github.com/api0cradle/ultimateapplockerbypasslist) The goal of this repository is to document the most common techniques to bypass AppLocker.


### <a id="286317d6d7c1a0578d8f5db940201320"></a>Articles


- 2019.11 [tyranidslair] [The Internals of AppLocker - Part 3 - Access Tokens and Access Checking](https://tyranidslair.blogspot.com/2019/11/the-internals-of-applocker-part-3.html)
- 2019.11 [tyranidslair] [The Internals of AppLocker - Part 2 - Blocking Process Creation](https://tyranidslair.blogspot.com/2019/11/the-internals-of-applocker-part-2.html)
- 2019.11 [tyranidslair] [The Internals of AppLocker - Part 1 - Overview and Setup](https://tyranidslair.blogspot.com/2019/11/the-internals-of-applocker-part-1.html)
- 2019.09 [blackhillsinfosec] [Getting Started With AppLocker](https://www.blackhillsinfosec.com/getting-started-with-applocker/)
- 2019.08 [p0w3rsh3ll] [How to delete a single Applocker rule](https://p0w3rsh3ll.wordpress.com/2019/08/02/how-to-delete-a-single-applocker-rule/)
- 2019.05 [oddvar] [A small discovery about AppLocker](https://oddvar.moe/2019/05/29/a-small-discovery-about-applocker/)
- 2019.04 [4hou] [通过regsrv32.exe绕过Applocker应用程序白名单的多种方法](https://www.4hou.com/web/17354.html)
- 2019.03 [4sysops] [Application whitelisting: Software Restriction Policies vs. AppLocker vs. Windows Defender Application Control](https://4sysops.com/archives/application-whitelisting-software-restriction-policies-vs-applocker-vs-windows-defender-application-control/)
- 2019.03 [4hou] [逃避手段再开花——从一个能逃避AppLocker和AMSI检测的Office文档讲起](https://www.4hou.com/system/16916.html)
- 2019.03 [yoroi] [The Document that Eluded AppLocker and AMSI](https://blog.yoroi.company/research/the-document-that-eluded-applocker-and-amsi/)
- 2019.03 [p0w3rsh3ll] [Applocker and PowerShell: how do they tightly work together?](https://p0w3rsh3ll.wordpress.com/2019/03/07/applocker-and-powershell-how-do-they-tightly-work-together/)
- 2019.02 [4hou] [如何以管理员身份绕过AppLocker](http://www.4hou.com/web/16213.html)
- 2019.02 [oddvar] [Bypassing AppLocker as an admin](https://oddvar.moe/2019/02/01/bypassing-applocker-as-an-admin/)
- 2019.01 [hackingarticles] [Windows Applocker Policy – A Beginner’s Guide](https://www.hackingarticles.in/windows-applocker-policy-a-beginners-guide/)
- 2019.01 [t00ls] [投稿文章：Bypass Applocker + 免杀执行任意 shellcode [ csc + installUtil ]](https://www.t00ls.net/articles-49443.html)
- 2018.12 [hecfblog] [Daily Blog #580: Applocker and Windows 10](https://www.hecfblog.com/2018/12/daily-blog-580-applocker-and-windows-10.html)
- 2018.12 [hecfblog] [Daily Blog #581: Forensic Lunch Test Kitchen 12/28/18 Syscache Applocker and Server 2012](https://www.hecfblog.com/2018/12/daily-blog-581-forensic-lunch-test.html)
- 2018.12 [360] [多维度对抗Windows AppLocker](https://www.anquanke.com/post/id/168633/)
- 2018.12 [tsscyber] [BloodHound.xpab — Applocker bypass](https://medium.com/p/895377ffa98e)
- 2018.10 [tsscyber] [AppLocker Bypass — presentationhost.exe](https://medium.com/p/8c87b2354cd4)




***


## <a id="b478e9a9a324c963da11437d18f04998"></a>Tools


### <a id="f9fad1d4d1f0e871a174f67f63f319d8"></a>Recently Added




### <a id="518d80dfb8e9dda028d18ace1d3f3981"></a>Procmon




### <a id="d90b60dc79837e06d8ba2a7ee1f109d3"></a>.NET


- [**12676**stars][14d] [C#] [0xd4d/dnspy](https://github.com/0xd4d/dnspy) .NET debugger and assembly editor
- [**9261**stars][11d] [C#] [icsharpcode/ilspy](https://github.com/icsharpcode/ilspy) .NET Decompiler
- [**3694**stars][27d] [C#] [0xd4d/de4dot](https://github.com/0xd4d/de4dot) .NET deobfuscator and unpacker.
- [**3263**stars][7m] [JS] [sindresorhus/speed-test](https://github.com/sindresorhus/speed-test) Test your internet connection speed and ping using speedtest.net from the CLI
- [**1657**stars][14d] [C#] [jbevain/cecil](https://github.com/jbevain/cecil) C#库, 探查/修改/生成 .NET App/库
- [**217**stars][11m] [C#] [rainwayapp/warden](https://github.com/rainwayapp/warden) Warden.NET is an easy to use process management library for keeping track of processes on Windows.


### <a id="6d2fe834b7662ecdd48c17163f732daf"></a>Environment&&环境&&配置


- [**1521**stars][11m] [PS] [joefitzgerald/packer-windows](https://github.com/joefitzgerald/packer-windows) 使用Packer创建Vagrant boxes的模板
- [**1347**stars][1m] [Go] [securitywithoutborders/hardentools](https://github.com/securitywithoutborders/hardentools) 禁用许多有危险的Windows功能
- [**1156**stars][1y] [HTML] [nsacyber/windows-secure-host-baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline) Windows 10和Windows Server 2016 DoD 安全主机基准设置的配置指南
- [**1008**stars][6m] [adolfintel/windows10-privacy](https://github.com/adolfintel/windows10-privacy) Win10隐私指南
- [**508**stars][17d] [PS] [stefanscherer/packer-windows](https://github.com/stefanscherer/packer-windows) Windows Packer 模板：Win10, Server 2016, 1709, 1803, 1809, 2019, 1903, Insider with Docker


### <a id="8bfd27b42bb75956984994b3419fb582"></a>Process Injection




### <a id="1c6069610d73eb4246b58d78c64c9f44"></a>Code Injection




### <a id="7c1541a69da4c025a89b0571d8ce73d2"></a>Memory Modules




### <a id="19cfd3ea4bd01d440efb9d4dd97a64d0"></a>VT&&Virtualisation&&Hypbervisor


- [**1348**stars][22d] [C] [intel/haxm](https://github.com/intel/haxm) Intel 开源的英特尔硬件加速执行管理器，通过硬件辅助的虚拟化引擎，加速 Windows/macOS 主机上的 IA emulation（(x86/ x86_64) ）
- [**1011**stars][1y] [C] [ionescu007/simplevisor](https://github.com/ionescu007/simplevisor) 英特尔VT-x虚拟机管理程序，简单、可移植。支持Windows和UEFI
- [**717**stars][23d] [C++] [tandasat/hyperplatform](https://github.com/tandasat/hyperplatform) 基于Intel VT-x的虚拟机管理程序，旨在在Windows上提供精简的VM-exit过滤平台
- [**570** stars][12m] [C] [asamy/ksm](https://github.com/asamy/ksm) A fast, hackable, and simple x64 VT-x hypervisor supporting Windows and Linux.
    - 重复区段: [Linux->工具->新添加](#203d00ef3396d68f5277c90279f4ebf3) |


### <a id="c3cda3278305549f4c21df25cbf638a4"></a>Kernel&&Drivers


- [**933**stars][9m] [C] [microsoft/windows-driver-frameworks](https://github.com/microsoft/windows-driver-frameworks) Windows驱动框架(WDF)
- [**781**stars][19d] [axtmueller/windows-kernel-explorer](https://github.com/axtmueller/windows-kernel-explorer) Windows内核研究工具
- [**510**stars][5m] [Py] [rabbitstack/fibratus](https://github.com/rabbitstack/fibratus) Windows内核探索和跟踪工具
- [**479**stars][1m] [C] [jkornev/hidden](https://github.com/jkornev/hidden) Windows驱动，带用户模式接口：隐藏文件系统和注册表对象、保护进程等
- [**278**stars][12d] [PS] [microsoftdocs/windows-driver-docs](https://github.com/MicrosoftDocs/windows-driver-docs) 官方Windows驱动程序工具包文档


### <a id="920b69cea1fc334bbc21a957dd0d9f6f"></a>Registry


- [**490**stars][14d] [Batchfile] [chef-koch/regtweaks](https://github.com/chef-koch/regtweaks) Windows注册表调整（Win 7-Win 10）
- [**288**stars][8m] [Py] [williballenthin/python-registry](https://github.com/williballenthin/python-registry) 用于对Windows NT注册表文件进行纯读取访问的Python库


### <a id="d295182c016bd9c2d5479fe0e98a75df"></a>System Calls


- [**725**stars][2m] [HTML] [j00ru/windows-syscalls](https://github.com/j00ru/windows-syscalls) Windows 系统调用表(NT/2000/XP/2003/Vista/2008/7/2012/8/10)
- [**328**stars][2m] [C] [hfiref0x/syscalltables](https://github.com/hfiref0x/syscalltables) Windows NT x64系统调用表


### <a id="1afda3039b4ab9a3a1f60b179ccb3e76"></a>Other


- [**949**stars][3m] [C] [basil00/divert](https://github.com/basil00/divert) 用户模式数据包拦截库，适用于Win 7/8/10
- [**863**stars][14d] [C++] [henrypp/simplewall](https://github.com/henrypp/simplewall) 为Windows 过滤平台提供的配置界面
- [**726**stars][2m] [Py] [diyan/pywinrm](https://github.com/diyan/pywinrm) Python实现的WinRM客户端
- [**570**stars][1m] [C] [hfiref0x/winobjex64](https://github.com/hfiref0x/winobjex64) Windows对象浏览器. x64
- [**463**stars][8m] [C#] [microsoft/dbgshell](https://github.com/microsoft/dbgshell) PowerShell编写的Windows调试器引擎前端
- [**418**stars][15d] [C] [samba-team/samba](https://github.com/samba-team/samba) 适用于Linux和Unix的标准Windows interoperability程序套件
- [**389**stars][2m] [C#] [microsoft/binskim](https://github.com/microsoft/binskim) 二进制静态分析工具，可为PE和ELF二进制格式提供安全性和正确性分析
- [**387**stars][19d] [Jupyter Notebook] [microsoft/windowsdefenderatp-hunting-queries](https://github.com/microsoft/windowsdefenderatp-hunting-queries) 在MS Defender ATP中进行高级查询的示例
- [**370**stars][27d] [Ruby] [winrb/winrm](https://github.com/winrb/winrm) 在Windows中使用WinRM的功能调用原生对象的SOAP库。Ruby编写
- [**360**stars][12d] [C#] [digitalruby/ipban](https://github.com/digitalruby/ipban) 监视Windows/Linux系统的登录失败和不良行为，并封禁对应的IP地址。高度可配置，精简且功能强大。
- [**269**stars][12m] [Py] [hakril/pythonforwindows](https://github.com/hakril/pythonforwindows) 简化Python与Windows操作系统交互的库
- [**238**stars][5m] [PS] [microsoft/aaronlocker](https://github.com/microsoft/aaronlocker) Windows应用程序白名单
- [**233**stars][10m] [Go] [masterzen/winrm](https://github.com/masterzen/winrm) Windows远程命令执行，命令行工具+库，Go编写
- [**232**stars][1y] [C++] [ionescu007/simpleator](https://github.com/ionescu007/simpleator) Windows x64用户模式应用程序模拟器
- [**229**stars][4m] [C] [tishion/mmloader](https://github.com/tishion/mmloader) 绕过Windows PE Loader，直接从内存中加载DLL模块（x86/x64）
- [**228**stars][3m] [C] [leecher1337/ntvdmx64](https://github.com/leecher1337/ntvdmx64) 在64位版本上执行Windows DOS版的 NTVDM
- [**226**stars][1y] [C++] [rexdf/commandtrayhost](https://github.com/rexdf/commandtrayhost) 监控Windows systray的命令行工具
- [**210**stars][3m] [adguardteam/adguardforwindows](https://github.com/adguardteam/adguardforwindows) Windows系统范围的AdBlocker
- [**208**stars][10m] [C] [hzqst/unicorn_pe](https://github.com/hzqst/unicorn_pe) 模拟Windows PE文件的代码执行，基于Unicorn
- [**205**stars][3m] [C] [jasonwhite/ducible](https://github.com/jasonwhite/ducible) 使PE和PDB的构建具有可复制性




***


## <a id="3939f5e83ca091402022cb58e0349ab8"></a>Articles


### <a id="8e1344cae6e5f9a33e4e5718a012e292"></a>Recently Added




### <a id="fa89526db1f9373c57ea4ffa1ac8c39f"></a>DEP


- 2019.11 [aliyun] [ARM EXP 开发 - 绕过 DEP 执行 mprotect()](https://xz.aliyun.com/t/6750)
- 2019.07 [codingvision] [Bypassing ASLR and DEP - Getting Shells with pwntools](https://codingvision.net/security/bypassing-aslr-dep-getting-shells-with-pwntools)
- 2019.01 [fuzzysecurity] [MS13-009 Use-After-Free IE8 (DEP)](http://fuzzysecurity.com/exploits/20.html)
- 2019.01 [fuzzysecurity] [BlazeVideo HDTV Player 6.6 Professional SEH&DEP&ASLR](http://fuzzysecurity.com/exploits/11.html)
- 2019.01 [fuzzysecurity] [NCMedia Sound Editor Pro v7.5.1 SEH&DEP&ASLR](http://fuzzysecurity.com/exploits/16.html)
- 2019.01 [fuzzysecurity] [ALLMediaServer 0.8 SEH&DEP&ASLR](http://fuzzysecurity.com/exploits/15.html)
- 2018.12 [360] [CoolPlayer bypass DEP(CVE-2008-3408)分析](https://www.anquanke.com/post/id/167424/)
- 2018.09 [duo] [Weak Apple DEP Authentication Leaves Enterprises Vulnerable to Social Engineering Attacks and Rogue Devices](https://duo.com/blog/weak-apple-dep-authentication-leaves-enterprises-vulnerable-to-social-engineering-attacks-and-rogue-devices)
- 2018.09 [3or] [ARM Exploitation - Defeating DEP - executing mprotect()](https://blog.3or.de/arm-exploitation-defeating-dep-executing-mprotect.html)
- 2018.09 [3or] [ARM Exploitation - Defeating DEP - execute system()](https://blog.3or.de/arm-exploitation-defeating-dep-execute-system.html)
- 2018.06 [pediy] [[原创]Easy MPEG to DVD Burner 1.7.11 SEH + DEP Bypass Local Buffer Overflow](https://bbs.pediy.com/thread-228537.htm)
- 2018.05 [pediy] [[翻译]DEP缓解技术(一)](https://bbs.pediy.com/thread-226625.htm)
- 2017.12 [360] [利用缓解技术：数据执行保护（DEP）](https://www.anquanke.com/post/id/91266/)
- 2017.12 [0x00sec] [Exploit Mitigation Techniques - Data Execution Prevention (DEP)](https://0x00sec.org/t/exploit-mitigation-techniques-data-execution-prevention-dep/4634/)
- 2017.10 [freebuf] [在64位系统中使用ROP+Return-to-dl-resolve来绕过ASLR+DEP](http://www.freebuf.com/articles/system/149364.html)
- 2017.10 [freebuf] [如何在32位系统中使用ROP+Return-to-dl来绕过ASLR+DEP](http://www.freebuf.com/articles/system/149214.html)
- 2017.08 [pediy] [[原创]利用Ret2Libc挑战DEP——利用ZwSetInformationProcess](https://bbs.pediy.com/thread-220346.htm)
- 2017.06 [360] [ropasaurusrex:ROP入门教程——DEP（下）](https://www.anquanke.com/post/id/86197/)
- 2017.06 [360] [ropasaurusrex:ROP入门教程——DEP（上）](https://www.anquanke.com/post/id/86196/)
- 2017.05 [myonlinesecurity] [fake clothing order Berhanu (PURCHASE DEPARTMENT) using winace files delivers Loki bot](https://myonlinesecurity.co.uk/fake-clothing-order-berhanu-purchase-department-using-winace-files-delivers-loki-bot/)


### <a id="af06263e9a92f6036dc5d4c4b28b9d8c"></a>Procmon


- 2017.06 [lowleveldesign] [How to decode managed stack frames in procmon traces](https://lowleveldesign.org/2017/06/23/how-to-decode-managed-stack-frames-in-procmon-traces/)
- 2017.02 [lowleveldesign] [When procmon trace is not enough](https://lowleveldesign.org/2017/02/20/when-procmon-trace-is-not-enough/)
- 2016.09 [dist67] [Malware: Process Explorer &  Procmon](https://www.youtube.com/watch?v=vq12OCVm2-o)
- 2015.06 [guyrleech] [Advanced Procmon Part 2 – Filtering inclusions](https://guyrleech.wordpress.com/2015/06/22/advanced-procmon-part-2-filtering-inclusions/)
- 2014.12 [guyrleech] [Advanced Procmon Part 1 – Filtering exclusions](https://guyrleech.wordpress.com/2014/12/25/advanced-procmon-part-1-filtering-exclusions/)




# <a id="dc664c913dc63ec6b98b47fcced4fdf0"></a>Linux


***


## <a id="a63015576552ded272a242064f3fe8c9"></a>ELF


### <a id="929786b8490456eedfb975a41ca9da07"></a>Tools


- [**930** stars][15d] [Py] [eliben/pyelftools](https://github.com/eliben/pyelftools) Parses ELF and DWARF files using Python.
- [**787** stars][2m] [C] [nixos/patchelf](https://github.com/nixos/patchelf) A small utility for modifying the dynamic linker and RPATH of ELF executables.
- [**411** stars][9m] [Assembly] [mewmew/dissection](https://github.com/mewmew/dissection) Dissects a simple "Hello World" ELF binary.
- [**337** stars][9m] [Py] [rek7/fireelf](https://github.com/rek7/fireelf) A fileless Linux malware framework.
- [**277** stars][4m] [Shell] [cryptolok/aslray](https://github.com/cryptolok/aslray) An exploit for bypassing ASLR and DEP/NX on Linux ELF x32/x64 using stack spraying.
- [**233** stars][2m] [C] [elfmaster/libelfmaster](https://github.com/elfmaster/libelfmaster) A secure ELF parsing and loading library for malware reconstruction, forensics, and robust reverse-engineering tools.


### <a id="72d101d0f32d5521d5d305e7e653fdd3"></a>Articles


- 2019.10 [aliyun] [A Universal One-Gadget Approach for 64-bit ELF Binaries](https://xz.aliyun.com/t/6598)
- 2019.10 [HackersOnBoard] [AFL's Blindspot and How to Resist AFL Fuzzing for Arbitrary ELF Binaries](https://www.youtube.com/watch?v=fhNNPJVlj4A)
- 2019.10 [HackersOnBoard] [Black Hat USA 2016 Intra-Process Memory Protection for App on ARM & X86 Leveraging the ELF ABI](https://www.youtube.com/watch?v=IeBrb1-AtOk)
- 2019.09 [freebuf] [CVE-2018-6924: Kernel Memory Disclosure Caused by FreeBSD ELF Header Parsing](https://www.freebuf.com/vuls/213345.html)
- 2019.07 [quarkslab] [CVE-2018-6924: FreeBSD ELF Header Parsing Kernel Memory Disclosure](https://blog.quarkslab.com/cve-2018-6924-freebsd-elf-header-parsing-kernel-memory-disclosure.html)
- 2019.07 [trendmicro] [A Quick and Efficient Method For Locating the main() function of Linux ELF Malware Variants](https://blog.trendmicro.com/trendlabs-security-intelligence/a-quick-and-efficient-method-for-locating-the-main-function-of-linux-elf-malware-variants/)
- 2019.05 [0x00sec] [Doubt infect ELF](https://0x00sec.org/t/doubt-infect-elf/13605/)
- 2019.04 [guitmz] [Linux ELF Runtime Crypter](https://www.guitmz.com/linux-elf-runtime-crypter/)
- 2019.03 [guitmz] [Running ELF executables from memory](https://www.guitmz.com/running-elf-from-memory/)
- 2019.02 [icyphox] [Python for Reverse Engineering #1: ELF Binaries](https://medium.com/p/e31e92c33732)
- 2019.01 [aliyun] [Santa's ELFs: Running Linux Executables Without `execve`](https://xz.aliyun.com/t/3856)
- 2019.01 [freebuf] [Exploring the Principles of Pwntools DynELF](https://www.freebuf.com/news/193646.html)
- 2019.01 [rapid7] [Santa's ELFs: Running Linux Executables Without execve](https://blog.rapid7.com/2019/01/03/santas-elfs-running-linux-executables-without-execve/)
- 2018.12 [360] [Various Methods for Executing ELF Files in Linux Memory](https://www.anquanke.com/post/id/168791/)
- 2018.12 [ZeroNights] [Yaroslav Moskvin - ELF execution in Linux RAM](https://www.youtube.com/watch?v=Q23nuzZ5YJI)
- 2018.11 [k3170makan] [Introduction to the ELF Format (Part VII): Dynamic Linking / Loading and the .dynamic section](http://blog.k3170makan.com/2018/11/introduction-to-elf-format-part-vii.html)
- 2018.10 [k3170makan] [Introduction to the ELF Format (Part VI) : More Relocation tricks - r_addend execution (Part 3)](http://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-vi-more.html)
- 2018.10 [k3170makan] [Introduction to The ELF Format (Part VI): The Symbol Table and Relocations (Part 2)](http://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-vi_18.html)
- 2018.10 [k3170makan] [Introduction to the ELF Format (Part VI) : The Symbol Table and Relocations (Part 1)](http://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-vi.html)
- 2018.10 [k3170makan] [Introduction to the ELF Format (Part V) : Understanding C start up .init_array and .fini_array sections](http://blog.k3170makan.com/2018/10/introduction-to-elf-format-part-v.html)




***


## <a id="89e277bca2740d737c1aeac3192f374c"></a>Tools


### <a id="203d00ef3396d68f5277c90279f4ebf3"></a>Recently Added


- [**1450** stars][2m] [C] [feralinteractive/gamemode](https://github.com/feralinteractive/gamemode) Optimises Linux system performance on demand.
- [**1413** stars][21d] [C++] [google/nsjail](https://github.com/google/nsjail) A lightweight process-isolation tool using Linux namespaces and seccomp-bpf system-call filters, with support from the Kafel BPF language.
- [**895** stars][29d] [C] [buserror/simavr](https://github.com/buserror/simavr) A lightweight, powerful, and hackable AVR simulator for Linux and macOS.
- [**759** stars][1m] [Py] [korcankaraokcu/pince](https://github.com/korcankaraokcu/pince) A Linux reverse-engineering tool intended to serve as an alternative to Cheat Engine.
- [**741** stars][2m] [C] [yrp604/rappel](https://github.com/yrp604/rappel) A Linux-based assembly REPL for x86, AMD64, ARMv7, and ARMv8.
- [**731** stars][17d] [C] [strace/strace](https://github.com/strace/strace) A diagnostic, debugging, and learning utility for Linux user space.
- [**570** stars][12m] [C] [asamy/ksm](https://github.com/asamy/ksm) A fast, hackable, and simple x64 VT-x hypervisor supporting Windows and Linux.
    - 重复区段: [Windows->工具->VT](#19cfd3ea4bd01d440efb9d4dd97a64d0) |
- [**565** stars][12d] [C++] [intel/linux-sgx](https://github.com/intel/linux-sgx) Intel SGX for Linux.
- [**560** stars][2m] [Py] [autotest/autotest](https://github.com/autotest/autotest) A fully automated testing framework for Linux.
- [**536** stars][5m] [C++] [nytrorst/shellcodecompiler](https://github.com/nytrorst/shellcodecompiler) Compiles C/C++-style code into small, position-independent, NULL-free shellcode for Windows (x86/x64) and Linux (x86/x64).
- [**509** stars][8m] [C] [iovisor/ply](https://github.com/iovisor/ply) Dynamic tracing for Linux.
- [**468** stars][9d] [C] [libreswan/libreswan](https://github.com/libreswan/libreswan) An Internet Key Exchange (IKE) implementation for Linux.
- [**441** stars][12d] [C] [facebook/openbmc](https://github.com/facebook/openbmc) An open-source software framework for building a complete Linux image for a Board Management Controller (BMC).
- [**405** stars][10m] [Shell] [microsoft/linux-vm-tools](https://github.com/microsoft/linux-vm-tools) Enhancements for Linux guest virtual machines running on Hyper-V.
- [**393** stars][2m] [Shell] [yadominjinta/atilo](https://github.com/yadominjinta/atilo) A Linux installer for Termux.
- [**354** stars][2m] [C] [seccomp/libseccomp](https://github.com/seccomp/libseccomp) An easy-to-use, platform-independent interface to the Linux kernel's system-call filtering mechanism.
- [**331** stars][5m] [Go] [capsule8/capsule8](https://github.com/capsule8/capsule8) Advanced behavioural monitoring for cloud-native environments, containers, and traditional Linux-based servers.
- [**282** stars][2m] [Py] [facebook/fbkutils](https://github.com/facebook/fbkutils) A collection of utilities developed and maintained by Facebook's Linux Kernel Team and shared with the community.
- [**228** stars][8m] [C] [wkz/ply](https://github.com/wkz/ply) A lightweight dynamic tracer for Linux.




***


## <a id="f6d78e82c3e5f67d13d9f00c602c92f0"></a>Articles


### <a id="bdf33f0b1200cabea9c6815697d9e5aa"></a>Recently Added






# 贡献
内容为系统自动导出, 有任何问题请提issue

# Awesome Forensics with stars

Curated list of awesome **free** (mostly open source) forensic analysis tools and resources.

> :star: Recommended · :package: Archived · :zzz: Unmaintained (2+ years)

* Awesome Forensics
  * [Collections](#collections)
  * [Tools](#tools)
    * [Distributions](#distributions)
    * [Frameworks](#frameworks)
    * [Live Forensics](#live-forensics)
    * [IOC Scanner](#ioc-scanner)
    * [Acquisition](#acquisition)
    * [Imaging](#imaging)
    * [Carving](#carving)
    * [Memory Forensics](#memory-forensics)
    * [Network Forensics](#network-forensics)
    * [Windows Artifacts](#windows-artifacts)
      * [NTFS/MFT Processing](#ntfsmft-processing)
    * [OS X Forensics](#os-x-forensics)
    * [Mobile Forensics](#mobile-forensics)
    * [Docker Forensics](#docker-forensics)
    * [Internet Artifacts](#internet-artifacts)
    * [Timeline Analysis](#timeline-analysis)
    * [Disk image handling](#disk-image-handling)
    * [Decryption](#decryption)
    * [Management](#management)
    * [Picture Analysis](#picture-analysis)
    * [Metadata Forensics](#metadata-forensics)
    * [Steganography](#steganography)
  * [Learn Forensics](#learn-forensics)
    * [CTFs and Challenges](#ctfs-and-challenges)
  * [Resources](#resources)
    * [Web](#web)
    * [Blogs](#blogs)
    * [Books](#books)
    * [File System Corpora](#file-system-corpora)
    * [Other](#other)
    * [Labs](#labs)
  * [Related Awesome Lists](#related-awesome-lists)
  * [Contributing](#contributing)

***

## Collections

* [AboutDFIR – The Definitive Compendium Project](https://aboutdfir.com) - Collection of forensic resources for learning and research. Offers lists of certifications, books, blogs, challenges and more
* :star: [ForensicArtifacts.com Artifact Repository](https://github.com/ForensicArtifacts/artifacts) ⭐ 1,267 | 🐛 44 | 🌐 Python | 📅 2026-07-31 - Machine-readable knowledge base of forensic artifacts

## Tools

* [Forensics tools on Wikipedia](https://en.wikipedia.org/wiki/List_of_digital_forensics_tools)
* [Eric Zimmerman's Tools](https://ericzimmerman.github.io/#!index.md)

### Distributions

* :zzz: [SANS Investigative Forensics Toolkit (sift)](https://github.com/teamdfir/sift) ⭐ 550 | 🐛 19 | 📅 2024-02-14 - Linux distribution for forensic analysis
* [bitscout](https://github.com/vitaly-kamluk/bitscout) ⭐ 479 | 🐛 0 | 🌐 Shell | 📅 2025-03-21 - LiveCD/LiveUSB for remote forensic acquisition and analysis
* [Remnux](https://remnux.org/) - Distro for reverse-engineering and analyzing malicious software
* [Tsurugi Linux](https://tsurugi-linux.org/) - Linux distribution for forensic analysis
* [WinFE](https://www.winfe.net/home) - Windows Forensics environment

### Frameworks

* :star: [The Sleuth Kit](https://github.com/sleuthkit/sleuthkit) ⭐ 3,135 | 🐛 475 | 🌐 C | 📅 2026-08-19 - Tools for low level forensic analysis
* [IPED - Indexador e Processador de Evidências Digitais](https://github.com/sepinf-inc/IPED) ⭐ 2,694 | 🐛 372 | 🌐 Java | 📅 2026-08-21 - Brazilian Federal Police Tool for Forensic Investigations
* :zzz: [PowerForensics](https://github.com/Invoke-IR/PowerForensics) ⭐ 1,442 | 🐛 64 | 🌐 C# | 📅 2023-11-16 - PowerForensics is a framework for live disk forensic analysis
* [Dissect](https://github.com/fox-it/dissect) ⭐ 1,147 | 🐛 10 | 📅 2026-02-25 - Dissect is a digital forensics & incident response framework and toolset that allows you to quickly access and analyse forensic artefacts from various disk and file formats, developed by Fox-IT (part of NCC Group).
* [IntelMQ](https://github.com/certtools/intelmq) ⭐ 1,133 | 🐛 253 | 🌐 Python | 📅 2026-04-28 - IntelMQ collects and processes security feeds
* [Kuiper](https://github.com/DFIRKuiper/Kuiper) ⭐ 901 | 🐛 12 | 🌐 JavaScript | 📅 2024-10-12 - Digital Investigation Platform
* [turbinia](https://github.com/google/turbinia) ⭐ 792 | 🐛 104 | 🌐 Python | 📅 2026-08-09 - Turbinia is an open-source framework for deploying, managing, and running forensic workloads on cloud platforms
* [Laika BOSS](https://github.com/lmco/laikaboss) ⭐ 753 | 🐛 26 | 🌐 Python | 📅 2024-12-16 - Laika is an object scanner and intrusion detection system
* :zzz: [dff](https://github.com/arxsys/dff) ⭐ 317 | 🐛 21 | 🌐 Python | 📅 2020-02-13 - Forensic framework
* :zzz: [hashlookup-forensic-analyser](https://github.com/hashlookup/hashlookup-forensic-analyser) ⭐ 130 | 🐛 4 | 🌐 Python | 📅 2023-09-24 - A tool to analyse files from a forensic acquisition to find known/unknown hashes from [hashlookup](https://www.circl.lu/services/hashlookup/) API or using a local Bloom filter.
* :zzz: [dexter](https://github.com/coinbase/dexter) ⭐ 127 | 🐛 9 | 🌐 Go | 📅 2019-06-21 - Dexter is a forensics acquisition framework designed to be extensible and secure
* [Wombat Forensics](https://github.com/pjrinaldi/wombatforensics) ⭐ 50 | 🐛 58 | 📅 2024-07-19 - Forensic GUI tool
* [AIFT](https://github.com/FlipForensics/AIFT) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2026-06-13 - AIFT (AI Forensic Triage) parses evidence using dissect and generates AI-assisted forensic reports.
* :star: [Autopsy](http://www.sleuthkit.org/autopsy/) - SleuthKit GUI
* [OpenRelik](https://openrelik.org/) - Forensic platform to store file artifacts and run workflows

### Live Forensics

* [osquery](https://github.com/osquery/osquery) ⭐ 23,482 | 🐛 623 | 🌐 C++ | 📅 2026-08-19 - SQL powered operating system analytics
* [grr](https://github.com/google/grr) ⭐ 5,089 | 🐛 191 | 🌐 Python | 📅 2026-05-12 - GRR Rapid Response: remote live forensics for incident response
* [UAC](https://github.com/tclahr/uac) ⭐ 1,437 | 🐛 9 | 🌐 Shell | 📅 2026-08-18 - UAC (Unix-like Artifacts Collector) is a Live Response collection script for Incident Response that makes use of native binaries and tools to automate the collection of AIX, Android, ESXi, FreeBSD, Linux, macOS, NetBSD, NetScaler, OpenBSD and Solaris systems artifacts.
* :package: [mig](https://github.com/mozilla/mig) ⚠️ Archived - Distributed & real time digital forensics at the speed of the cloud
* :package: [Linux Expl0rer](https://github.com/intezer/linux-explorer) ⚠️ Archived - Easy-to-use live forensics toolbox for Linux endpoints written in Python & Flask
* [POFR](https://github.com/gmagklaras/pofr) ⭐ 41 | 🐛 1 | 🌐 Perl | 📅 2026-03-27 - The Penguin OS Flight Recorder collects, stores and organizes for further analysis process execution, file access and network/socket endpoint data from the Linux Operating System.
* [InnerWarden](https://github.com/InnerWarden/innerwarden) - Security agent with built-in forensic capture (process state, network connections, memory maps, hidden process detection via direct /proc reads)

### IOC Scanner

* [Loki](https://github.com/Neo23x0/Loki) ⭐ 3,782 | 🐛 18 | 🌐 Python | 📅 2026-01-12 - Simple IOC and Incident Response Scanner
* :zzz: [Fenrir](https://github.com/Neo23x0/Fenrir) ⭐ 776 | 🐛 1 | 🌐 Shell | 📅 2022-02-12 - Simple Bash IOC Scanner
* [Fastfinder](https://github.com/codeyourweb/fastfinder) ⭐ 260 | 🐛 0 | 🌐 Go | 📅 2026-01-24 - Fast customisable cross-platform suspicious file finder. Supports md5/sha1/sha256 hashes, literal/wildcard strings, regular expressions and YARA rules
* [Redline](https://fireeye.market/apps/211364) - Free endpoint security tool from FireEye
* [THOR Lite](https://www.nextron-systems.com/thor-lite/) - Free IOC and YARA Scanner

### Acquisition

* [Velociraptor](https://github.com/Velocidex/velociraptor) ⭐ 4,194 | 🐛 74 | 🌐 Go | 📅 2026-08-20 - Velociraptor is a tool for collecting host based state information using Velocidex Query Language (VQL) queries
* [LiME](https://github.com/jtsylve/LiME) ⭐ 2,028 | 🐛 35 | 🌐 C | 📅 2026-04-05 - Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, formerly called DMD
* [AVML](https://github.com/microsoft/avml) ⭐ 1,117 | 🐛 5 | 🌐 Rust | 📅 2026-08-19 - A portable volatile memory acquisition tool for Linux
* :zzz: [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector) ⭐ 521 | 🐛 11 | 🌐 Python | 📅 2021-01-26 - Collect artifacts on windows
* [UFADE](https://github.com/prosch88/UFADE) ⭐ 515 | 🐛 3 | 🌐 Python | 📅 2026-08-20 - Extract files from iOS devices on Linux and MacOS. Mostly a wrapper for pymobiledevice3. Creates iTunes-style backups and advanced logical backups.
* [artifactcollector](https://github.com/forensicanalysis/artifactcollector) ⚠️ Archived - A customizable agent to collect forensic artifacts on any Windows, macOS or Linux system
* [Fuji](https://github.com/Lazza/Fuji/) ⭐ 295 | 🐛 6 | 🌐 Python | 📅 2026-06-02 - MacOS forensic acquisition made simple. It creates full file system copies or targeted collection of Mac computers.
* [ForensicMiner](https://github.com/securityjoes/ForensicMiner) ⭐ 164 | 🐛 2 | 🌐 PowerShell | 📅 2025-04-06 - A PowerShell-based DFIR automation tool, for artifact and evidence collection on Windows machines.
* [Acquire](https://github.com/fox-it/acquire) ⭐ 122 | 🐛 53 | 🌐 Python | 📅 2026-08-12 - Acquire is a tool to quickly gather forensic artifacts from disk images or a live system into a lightweight container
* [FIT](https://github.com/fit-project/fit) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2026-03-06 - Forensic acquisition of web pages, emails, social media, etc.
* [ALEX](https://github.com/prosch88/ALEX) ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2026-08-06 - Extract files from ADB devices on Windows, Linux and MacOS. Mostly a wrapper for adbutils.
* [SPECTR3](https://github.com/alpine-sec/SPECTR3) ⭐ 44 | 🐛 0 | 🌐 C# | 📅 2024-10-25 - Acquire, triage and investigate remote evidence via portable iSCSI readonly access
* [unix\_collector](https://github.com/op7ic/unix_collector) ⭐ 43 | 🐛 0 | 🌐 Shell | 📅 2026-06-18 - A live forensic collection script for UNIX-like systems as a single script.
* [Hypoxia](https://github.com/xinitd/hypoxia) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2026-04-09 - Cross-platform CLI tool for targeted file collection with SHA-256 manifest, chain-of-custody log, and checkpoint/resume support.
* [Belkasoft RAM Capturer](https://belkasoft.com/ram-capturer) - Volatile Memory Acquisition Tool
* [DFIR ORC](https://dfir-orc.github.io/) - Forensics artefact collection tool for systems running Microsoft Windows
* [FireEye Memoryze](https://fireeye.market/apps/211368) - A free memory forensic software
* [Magnet RAM Capture / DumpIt](https://www.magnetforensics.com/resources/magnet-dumpit-for-windows/) - A free imaging tool designed to capture the physical memory
* [WinTriage](https://www.securizame.com/wintriage-the-triage-tool-for-windows-dfirers/) - Wintriage is a live response tool that extracts Windows artifacts. It must be executed with local or domain administrator privileges and recommended to be done from an external drive.

### Imaging

* [dc3dd](https://sourceforge.net/projects/dc3dd/) - Improved version of dd
* :zzz: [dcfldd](https://sourceforge.net/projects/dcfldd/) - Different improved version of dd (this version has some bugs!, another version is on github [adulau/dcfldd](https://github.com/adulau/dcfldd) ⭐ 75 | 🐛 2 | 🌐 C | 📅 2018-06-17)
* [FTK Imager](https://www.exterro.com/digital-forensics-software/ftk-imager) - Free imaging tool for windows
* :star: [Guymager](https://sourceforge.net/projects/guymager/) - Open source version for disk imaging on linux systems

### Carving

* [floss](https://github.com/mandiant/flare-floss) ⭐ 4,130 | 🐛 121 | 🌐 Python | 📅 2026-08-21 - Static analysis tool to automatically deobfuscate strings from malware binaries
* [bulk\_extractor](https://github.com/simsong/bulk_extractor) ⭐ 1,412 | 🐛 67 | 🌐 C++ | 📅 2026-08-18 - Extracts information such as email addresses, creditcard numbers and histrograms from disk images
* :zzz: [swap\_digger](https://github.com/sevagas/swap_digger) ⭐ 536 | 🐛 1 | 🌐 Shell | 📅 2021-06-26 - A bash script used to automate Linux swap analysis, automating swap extraction and searches for Linux user credentials, Web form credentials, Web form emails, etc.
* [bstrings](https://github.com/EricZimmerman/bstrings) ⭐ 151 | 🐛 0 | 🌐 C# | 📅 2026-04-26 - Improved strings utility
* :star: [photorec](https://www.cgsecurity.org/wiki/PhotoRec) - File carving tool

### Memory Forensics

* :package: [volatility](https://github.com/volatilityfoundation/volatility) ⚠️ Archived - The memory forensic framework
* [MemProcFS](https://github.com/ufrisk/MemProcFS) ⭐ 4,297 | 🐛 9 | 🌐 C | 📅 2026-08-17 - An easy and convenient way of accessing physical memory as files a virtual file system.
* :package: [Rekall](https://github.com/google/rekall) ⚠️ Archived - Memory Forensic Framework
* :zzz: [KeeFarce](https://github.com/denandz/KeeFarce) ⭐ 1,029 | 🐛 4 | 🌐 C++ | 📅 2015-11-17 - Extract KeePass passwords from memory
* [VolUtility](https://github.com/kevthehermit/VolUtility) ⭐ 387 | 🐛 40 | 🌐 Python | 📅 2026-01-13 - Web App for Volatility framework
* :zzz: [inVtero.net](https://github.com/ShaneK2/inVtero.net) ⭐ 296 | 🐛 2 | 🌐 C# | 📅 2023-09-30 - High speed memory analysis framework
  developed in .NET supports all Windows x64, includes code integrity and write support

### Network Forensics

* [RustNet](https://github.com/domcyrus/rustnet) ⭐ 4,892 | 🐛 17 | 🌐 Rust | 📅 2026-08-22 - A cross-platform network monitoring terminal UI providing real-time visibility into network connections
* [Kismet](https://github.com/kismetwireless/kismet) ⭐ 2,205 | 🐛 206 | 🌐 C++ | 📅 2026-08-15 - A passive wireless sniffer
* [NetworkMiner](https://www.netresec.com/?page=Networkminer) - Network Forensic Analysis Tool
* [Squey](https://squey.org) - Logs/PCAP visualization software designed to detect anomalies and weak signals in large amounts of data.
* :star: [WireShark](https://www.wireshark.org/) - A network protocol analyzer

### Windows Artifacts

* [Hayabusa](https://github.com/Yamato-Security/hayabusa) ⭐ 3,319 | 🐛 21 | 🌐 Rust | 📅 2026-08-22 - A sigma-based threat hunting and fast forensics timeline generator for Windows event logs.
* [LogonTracer](https://github.com/JPCERTCC/LogonTracer) ⭐ 3,217 | 🐛 21 | 🌐 Python | 📅 2026-08-02 - Investigate malicious Windows logon by visualizing and analyzing Windows event log
* :zzz: [Beagle](https://github.com/yampelo/beagle) ⭐ 1,351 | 🐛 44 | 🌐 Python | 📅 2022-12-13 -  Transform data sources and logs into graphs
* [RegRipper3.0](https://github.com/keydet89/RegRipper3.0) ⭐ 713 | 🐛 9 | 🌐 Perl | 📅 2026-05-27 - RegRipper is an open source Perl tool for parsing the Registry and presenting it for analysis
* [RegRippy](https://github.com/airbus-cert/regrippy) ⭐ 217 | 🐛 2 | 🌐 Python | 📅 2026-05-12 - A framework for reading and extracting useful forensics data from Windows registry hives
* [Blauhaunt](https://github.com/cgosec/Blauhaunt) ⭐ 188 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-18 - A tool collection for filtering and visualizing logon events
* :zzz: [python-evt](https://github.com/williballenthin/python-evt) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2023-06-30 - Pure Python parser for classic Windows Event Log files (.evt)
* [FRED](https://www.pinguin.lu/fred) - Cross-platform microsoft registry hive editor
* [LastActivityView](https://www.nirsoft.net/utils/computer_activity_view.html) - LastActivityView by Nirsoftis a tool for Windows operating system that collects information from various sources on a running system, and displays a log of actions made by the user and events occurred on this computer.

#### NTFS/MFT Processing

* [NTFSTool](https://github.com/thewhiteninja/ntfstool) ⭐ 623 | 🐛 6 | 🌐 C++ | 📅 2026-06-26 - Complete NTFS forensics tool
* [RecuperaBit](https://github.com/Lazza/RecuperaBit) ⭐ 622 | 🐛 35 | 🌐 Python | 📅 2026-07-26 - Reconstruct and recover NTFS data
* :zzz: [NTFS USN Journal parser](https://github.com/PoorBillionaire/USN-Journal-Parser) ⭐ 119 | 🐛 4 | 🌐 Python | 📅 2022-07-15
* :zzz: [python-ntfs](https://github.com/williballenthin/python-ntfs) ⭐ 86 | 🐛 4 | 🌐 Python | 📅 2017-12-22 - NTFS analysis
* [MFTExtractor](https://github.com/aarsakian/FileSystemForensics) ⭐ 18 | 🐛 0 | 🌐 Go | 📅 2026-08-01 - MFT-Parser
* [MFT-Parsers](http://az4n6.blogspot.com/2015/09/whos-your-master-mft-parsers-reviewed.html) - Comparison of MFT-Parsers
* [MFTEcmd](https://binaryforay.blogspot.com/2018/06/introducing-mftecmd.html) - MFT Parser by Eric Zimmerman
* [NTFS journal parser](http://strozfriedberg.github.io/ntfs-linker/)

### OS X Forensics

* :zzz: [OSXAuditor](https://github.com/jipegit/OSXAuditor) ⭐ 3,135 | 🐛 8 | 🌐 JavaScript | 📅 2020-07-27
* [APFS Fuse](https://github.com/sgan81/apfs-fuse) ⭐ 2,136 | 🐛 125 | 🌐 C++ | 📅 2024-08-13 - A read-only FUSE driver for the new Apple File System
* :package: [OSX Collect](https://github.com/YelpArchive/osxcollector) ⚠️ Archived
* [mac\_apt (macOS Artifact Parsing Tool)](https://github.com/ydkhatri/mac_apt) ⭐ 1,075 | 🐛 8 | 🌐 Python | 📅 2026-08-21 - Extracts forensic artifacts from disk images or live machines
* :zzz: [macMRUParser](https://github.com/mac4n6/macMRU-Parser) ⭐ 111 | 🐛 1 | 🌐 Python | 📅 2018-02-22 - Python script to parse the Most Recently Used (MRU) plist files on macOS into a more human friendly format
* :zzz: [MacLocationsScraper](https://github.com/mac4n6/Mac-Locations-Scraper) ⭐ 92 | 🐛 0 | 🌐 Python | 📅 2022-10-26 - Dump the contents of the location database files on iOS and macOS

### Mobile Forensics

* [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) ⭐ 21,618 | 🐛 20 | 🌐 JavaScript | 📅 2026-08-21 - An automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.
* :zzz: [Andriller](https://github.com/den4uk/andriller) ⭐ 1,598 | 🐛 11 | 🌐 Python | 📅 2022-06-27 - A software utility with a collection of forensic tools for smartphones
* [iLEAPP](https://github.com/abrignoni/iLEAPP) ⭐ 1,165 | 🐛 61 | 🌐 Python | 📅 2026-08-22 - An iOS Logs, Events, And Plists Parser
* [ALEAPP](https://github.com/abrignoni/ALEAPP) ⭐ 882 | 🐛 51 | 🌐 Python | 📅 2026-08-22 - An Android Logs Events and Protobuf Parser
* :zzz: [OpenBackupExtractor](https://github.com/vgmoose/OpenBackupExtractor) ⭐ 191 | 🐛 7 | 🌐 Swift | 📅 2022-01-06 - An app for extracting data from iPhone and iPad backups.
* :zzz: [MEAT](https://github.com/jfarley248/MEAT) ⭐ 168 | 🐛 2 | 🌐 Python | 📅 2020-05-21 - Perform different kinds of acquisitions on iOS devices
* :zzz: [iOS Frequent Locations Dumper](https://github.com/mac4n6/iOS-Frequent-Locations-Dumper) ⭐ 92 | 🐛 1 | 🌐 Python | 📅 2018-11-04 - Dump the contents of the StateModel#.archive files located in /private/var/mobile/Library/Caches/com.apple.routined/
* [ArtEx](https://www.doubleblak.com/index.php) - Artifact Examiner for iOS Full File System extractions

### Docker Forensics

* :package: [Docker Explorer](https://github.com/google/docker-explorer) ⚠️ Archived - Extracts and interprets forensic artifacts from disk images of Docker Host systems
* :zzz: [dof (Docker Forensics Toolkit)](https://github.com/docker-forensics-toolkit/toolkit) ⭐ 112 | 🐛 1 | 🌐 Python | 📅 2024-02-18 - Extracts and interprets forensic artifacts from disk images of Docker Host systems

### Internet Artifacts

* [hindsight](https://github.com/RyanDFIR/hindsight) ⭐ 1,490 | 🐛 7 | 🌐 Python | 📅 2026-08-22 - Internet history forensics for Google Chrome/Chromium
* [unfurl](https://github.com/RyanDFIR/unfurl) ⭐ 762 | 🐛 32 | 🌐 Python | 📅 2026-08-20 - Extract and visualize data from URLs
* [WinSearchDBAnalyzer](https://github.com/moaistory/WinSearchDBAnalyzer) ⭐ 134 | 🐛 2 | 🌐 C# | 📅 2024-07-20 - This tool can parse normal records and recover deleted records in Windows.edb.
* [IE10Analyzer](https://github.com/moaistory/IE10Analyzer) ⭐ 20 | 🐛 0 | 🌐 C# | 📅 2024-07-20 - This tool can parse normal records and recover deleted records in WebCacheV01.dat.
* [ChromeCacheView](https://www.nirsoft.net/utils/chrome_cache_view.html) - A small utility that reads the cache folder of Google Chrome Web browser, and displays the list of all files currently stored in the cache

### Timeline Analysis

* [timesketch](https://github.com/google/timesketch) ⭐ 3,391 | 🐛 217 | 🌐 Python | 📅 2026-08-18 - Collaborative forensic timeline analysis
* :star: [plaso](https://github.com/log2timeline/plaso) ⭐ 2,137 | 🐛 283 | 🌐 Python | 📅 2026-08-03 - Extract timestamps from various files and aggregate them
* [DFTimewolf](https://github.com/log2timeline/dftimewolf) ⭐ 352 | 🐛 4 | 🌐 Python | 📅 2026-08-21 - Framework for orchestrating forensic collection, processing and data export using GRR and Rekall
* [timeliner](https://github.com/airbus-cert/timeliner) ⭐ 41 | 🐛 0 | 🌐 Go | 📅 2024-08-05 - A rewrite of mactime, a bodyfile reader
* [Timeline Explorer](https://binaryforay.blogspot.com/2017/04/introducing-timeline-explorer-v0400.html) - Timeline Analysis tool for CSV and Excel files. Built for SANS FOR508 students

### Disk image handling

* [Disk Arbitrator](https://github.com/aburgh/Disk-Arbitrator) ⭐ 714 | 🐛 30 | 🌐 Objective-C | 📅 2025-08-25 - A Mac OS X forensic utility designed to help the user ensure correct forensic procedures are followed during imaging of a disk device
* [libewf](https://github.com/libyal/libewf) ⭐ 312 | 🐛 13 | 🌐 C | 📅 2026-07-16 - Libewf is a library and some tools to access the Expert Witness Compression Format (EWF, E01)
* :zzz: [imagemounter](https://github.com/ralphje/imagemounter) ⭐ 127 | 🐛 6 | 🌐 Python | 📅 2023-02-09 - Command line utility and Python package to ease the (un)mounting of forensic disk images
* [xmount](https://www.pinguin.lu/xmount) - Convert between different disk image formats

### Decryption

* [hashcat](https://hashcat.net/hashcat/) - Fast password cracker with GPU support
* [John the Ripper](https://www.openwall.com/john/) - Password cracker

### Management

* [iris](https://github.com/dfir-iris/iris-web) ⭐ 1,543 | 🐛 420 | 🌐 Python | 📅 2026-07-13 - Collaborative Incident Response platform
* [dfirtrack](https://github.com/dfirtrack/dfirtrack) ⭐ 538 | 🐛 7 | 🌐 Python | 📅 2026-01-13 - Digital Forensics and Incident Response Tracking application, track systems
* [Catalyst](https://github.com/SecurityBrewery/catalyst) ⚠️ Archived - Catalyst is an open source security automation and ticket system

### Picture Analysis

* [sherloq](https://github.com/GuidoBartoli/sherloq) ⭐ 3,188 | 🐛 25 | 🌐 Perl | 📅 2026-07-16 - An open-source digital photographic image forensic toolset
* :zzz: [Ghiro](https://github.com/Ghirensics/ghiro) ⭐ 526 | 🐛 18 | 🌐 Python | 📅 2016-09-15 - A fully automated tool designed to run forensics analysis over a massive amount of images

### Metadata Forensics

* :zzz: [FOCA](https://github.com/ElevenPaths/FOCA) ⭐ 3,619 | 🐛 26 | 🌐 C# | 📅 2022-12-08 - FOCA is a tool used mainly to find metadata and hidden information in the documents
* [oletools](https://github.com/decalage2/oletools) ⭐ 3,397 | 🐛 518 | 🌐 Python | 📅 2026-02-14 - Tools to analyze Microsoft OLE2 files and MS Office documents for malware analysis and forensics
* :zzz: [Metagoofil](https://github.com/laramies/metagoofil) ⭐ 1,311 | 🐛 19 | 🌐 Python | 📅 2024-03-21 - Metadata harvester for extracting metadata from public documents
* [mat2](https://github.com/jvoisin/mat2) ⭐ 341 | 🐛 2 | 🌐 Python | 📅 2026-08-21 - Metadata removal tool, supporting a wide range of commonly used file formats
* [EXIF Editor](https://exifeditor.io/) - In-browser, privacy first EXIF Viewer/Editor/Analysis tool (Zero Sign Up). Home to the The EXIF Guide, and The EXIF Quiz.
* [ExifTool](https://exiftool.org/) by Phil Harvey
* [pdf-parser](https://blog.didierstevens.com/programs/pdf-tools/) - Parse and analyze PDF files to extract metadata and identify malicious content

### Steganography

* [Zsteg](https://github.com/zed-0xff/zsteg) ⭐ 1,611 | 🐛 6 | 🌐 Ruby | 📅 2026-01-28 - Detect steganography hidden in PNG and BMP files
* :zzz: [Steghide](https://github.com/StegHigh/steghide) ⭐ 770 | 🐛 4 | 🌐 C++ | 📅 2024-02-20 - is a steganography program that hides data in various kinds of image and audio files
* [Sonicvisualizer](https://www.sonicvisualiser.org)

## Learn Forensics

* [Forensic challenges](https://www.amanhardikar.com/mindmaps/ForensicChallenges.html) - Mindmap of forensic challenges

### CTFs and Challenges

* [Forensics CTFs](https://github.com/apsdehal/awesome-ctf/blob/master/README.md#forensics) ⭐ 11,782 | 🐛 64 | 🌐 JavaScript | 📅 2024-07-22
* :zzz: [MemLabs](https://github.com/stuxnet999/MemLabs) ⭐ 1,887 | 🐛 0 | 🌐 Shell | 📅 2021-03-08
* [BelkaCTF](https://belkasoft.com/ctf) - CTFs by Belkasoft
* [CyberDefenders](https://cyberdefenders.org/blueteam-ctf-challenges/?type=ctf)
* [DefCon CTFs](https://archive.ooo) - archive of DEF CON CTF challenges.
* [MagnetForensics CTF Challenge](https://www.magnetforensics.com/blog/magnet-weekly-ctf-challenge/)
* [MalwareTech Labs](https://malwaretech.com/labs/)
* [NW3C Chanllenges](https://nw3.ctfd.io)
* [Precision Widgets of North Dakota Intrusion](https://betweentwodfirns.blogspot.com/2017/11/dfir-ctf-precision-widgets-of-north.html)
* [ReverseEngineering Challenges](https://challenges.re)

## Resources

### Web

* [ForensicsFocus](https://www.forensicfocus.com/)
* [SANS Digital Forensics](https://www.sans.org/cybersecurity-focus-areas/digital-forensics-incident-response)
* [Forensics StartMe by Stark 4N6](https://startme.stark4n6.com)

### Blogs

* [Netresec](https://www.netresec.com/index.ashx?page=Blog)
* [SANS Forensics Blog](https://www.sans.org/blog?focus-area=digital-forensics)
* [SecurityAffairs](https://securityaffairs.com/) - blog by Pierluigi Paganini
* [This Week In 4n6](https://thisweekin4n6.com/) - Weekly updates for forensics
* [Zena Forensics](https://blog.digital-forensics.it/)

### Books

*more at [Recommended Readings](http://dfir.org/?q=node/8) by Andrew Case*

* [Network Forensics: Tracking Hackers through Cyberspace](https://www.pearson.com/en-us/subject-catalog/p/Davidoff-Network-Forensics-Tracking-Hackers-through-Cyberspace/P200000009228) - Learn to recognize hackers’ tracks and uncover network-based evidence
* [The Art of Memory Forensics](https://memoryanalysis.net/amf/) - Detecting Malware and Threats in Windows, Linux, and Mac Memory
* [The Practice of Network Security Monitoring](https://nostarch.com/nsm) - Understanding Incident Detection and Response

### File System Corpora

* [Digital Forensic Challenge Images](https://www.ashemery.com/dfir.html) - Two DFIR challenges with images
* [Digital Forensics Tool Testing Images](https://sourceforge.net/projects/dftt/)

### Other

* [/r/computerforensics/](https://www.reddit.com/r/computerforensics/) - Subreddit for computer forensics
* [CybersecurityGuide – Digital Forensics Careers](https://cybersecurityguide.org/careers/digital-forensics/) - Guide on skills, certs, and career paths in cyber forensics.
* [ForensicPosters](https://github.com/Invoke-IR/ForensicPosters) ⭐ 453 | 🐛 3 | 📅 2024-11-21 - Posters of file system structures
* [SANS Posters](https://www.sans.org/posters) - Free posters provided by SANS

### Labs

* [BlueTeam.Lab](https://github.com/op7ic/BlueTeam.Lab) ⭐ 187 | 🐛 1 | 🌐 Jinja | 📅 2024-11-20 - Blue Team detection lab created with Terraform and Ansible in Azure.

## Related Awesome Lists

* [Pentesting](https://github.com/enaqx/awesome-pentest) ⭐ 26,983 | 🐛 101 | 📅 2026-07-25
* [Hacking](https://github.com/carpedm20/awesome-hacking) ⭐ 16,921 | 🐛 68 | 📅 2024-06-02
* [Security](https://github.com/sbilly/awesome-security) ⭐ 14,787 | 🐛 314 | 📅 2026-01-11
* [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) ⭐ 14,148 | 🐛 25 | 📅 2024-06-07
* [CTFs](https://github.com/apsdehal/awesome-ctf) ⭐ 11,782 | 🐛 64 | 🌐 JavaScript | 📅 2024-07-22
* [Honeypots](https://github.com/paralax/awesome-honeypots) ⭐ 10,526 | 🐛 22 | 🌐 Python | 📅 2026-06-01
* [Android Security](https://github.com/ashishb/android-security-awesome) ⭐ 9,626 | 🐛 0 | 🌐 Makefile | 📅 2026-08-21
* [Incident-Response](https://github.com/meirwah/awesome-incident-response) ⭐ 9,345 | 🐛 74 | 📅 2026-07-15
* [AppSec](https://github.com/paragonie/awesome-appsec) ⭐ 7,038 | 🐛 40 | 🌐 PHP | 📅 2025-02-22
* [Infosec](https://github.com/onlurking/awesome-infosec) ⭐ 5,720 | 🐛 15 | 📅 2026-08-15
* [YARA](https://github.com/InQuest/awesome-yara) ⭐ 4,259 | 🐛 1 | 📅 2026-06-15
* [Social Engineering](https://github.com/giuliacassara/awesome-social-engineering) ⭐ 4,240 | 🐛 12 | 📅 2023-04-05

## [Contributing](CONTRIBUTING.md)

Pull requests and issues with suggestions are welcome!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._

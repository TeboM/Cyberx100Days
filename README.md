# :desktop_computer: Cyber X 100 Days
This is part of my personal journey as I rebuild, rediscover and expand my cybersecurity skills in 100 days 

# 🛡️ Cybersecurity Training Journey 

Welcome to my personal cybersecurity upskilling journey!  
I'll be completing daily training using **CyberDefenders**, **HackTheBox**, **PortSwigger Academy**, **TryHackMe**, **BTLO** and related platforms.

This repo documents my progress, learnings, and reflections — updated daily for accountability.  
Join me or follow along. 💻🔥

---

## 🎯 Goals

- ✅ Complete 30 days (Phase 1 - Why 30 days? They say it takes 21 Days to form a habit, we take it further, we make sure)
- 🕐 Progress to 60, 80 then 100 days
- 📚 Improve in Security Research, Investigation Methodology, Malware Analysis, Threat Hunting, Web Exploitation, Learn new skills...
- 🚀 Build consistency, clarity, and confidence

---

## 🗓️ Daily Progress Tracker

| Day | Date       | Platform        | Challenge/Room                 | Time Spent | Key Learnings                        | Status    |
|-----|------------|------------------|--------------------------------|------------|--------------------------------------|-----------|
| 1   | 13 Aug     | CyberDefenders   | Golden Spray                   | 2 hours    | Password Spraying, Priv Escl, Cred Dump | ✅ Done    |
| 2   | 14 Aug     | CyberDefenders   | OpenCTI 101                    | 30 min     | Threat Intel, APT29 Ops Overview, OpenCTI, OSINT     | ✅ Done |
| 3   | 15 Aug     | CyberDefenders   | OpenCTI 101                    | 30 min     | APT29 Old Wine in New Bottle Phishing, 2023 EU Gov Campaigns  | ✅ Done  |
| 4   | 16 Aug     | CyberDefenders   | XLMRat                         | 1 hour     | WireShark, Malware Delivery, Deobfuscation, Code Review | 🔁 Incomplete  |
| 5   | 17 Aug     | CyberDefenders   | XLMRat                         | 30 min     | Script Decoding & Analysis               | 🔁 Incomplete  |
| 6   | 18 Aug     | CyberDefenders   | OpenFire Platform              | 2 hours    | WireShark, Command Injection, CVE-2023-32315, Path Travesal | ✅ Done  |
| 7   | 19 Aug     | CyberDefenders   | Black Busta - 0x1              | 1 hour     | Initial Access and Execution, ZIP download, Malicious Excel Doc (Macros) | ✅ Done  |
| 8   | 20 Aug     | CyberDefenders   | Black Busta - 0x2              | 1 hour     | Persistence & Defense Evasion, Scheduled Tasks, Registry Changes  | ✅ Done  |
| 9   | 21 Aug     | CyberDefenders   | Black Busta - 0x3, 0x4         | 2 hours    | C2, Lateral Movement & Discovery,   | ✅ Done  |
| 10  | 22 Aug     | CyberDefenders   | Black Busta - 0x5              | 30 min     | Impact, Analysis surrounding ransomware execution | ✅ Done  |
| 11  | 23 Aug     | CyberDefenders   | Black Busta - 0x5              | 30 min     | Ransom payload deployed, payload execution | ✅ Done  |
| 00  | 24 Aug     | N/A              | None                           | 0 min      | No training done (AFK All Day) Brass Duties  | ⛔ N/A  |
| 12  | 25 Aug     | CyberDefenders   | Black Busta - 0x5              | 15 min     | Ransomware execution via privileged account, Shadow Copy deletion, File Encryption | ✅ Done  |
| 13  | 26 Aug     | CyberDefenders   | Black Busta - 0x6              | 15 min     | Exfiltration: preparation before exfil, file zipped  | ✅ Done  |
| 14  | 27 Aug     | CyberDefenders   | Black Busta - 0x6              | 30 min     | Data Theft: Collection after ransomware, Exfil using cloud based storage  |  ✅ Done  |
| 15  | 28 Aug     | CyberDefenders   | Rhysida - 0x1                  | 30 min     | Initial Access: O365 credential phishing | ✅ Done  |
| 16  | 29 Aug     | CyberDefenders   | Rhysida - 0x1                  | 30 min     | Initial Access: Unauthorized SSH Logins  | ✅ Done  |
| 17  | 30 Aug     | CyberDefenders   | Rhysida - 0x1                  | 15 min     | Initial Access: Compromised Credential Abuse  | ✅ Done  |
| 18  | 31 Aug     | CyberDefenders   | Rhysida - 0x1                  | 15 min     | Execution: Use of LOLBINs for downloading payloads  | ✅ Done  |
| 19  | 01 Sep     | CyberDefenders   | Rhysida - 0x2                  | 30 min     | Persistence: Registry changes mimicking normal system activity  |  ✅ Done  |
| 20  | 02 Sep     | CyberDefenders   | Rhysida - 0x2, 0x3             | 1 hour     | Defense Evasion: WinDefender and System Auditing disabled. System logs cleared to cover tracks. Credential Access: Browser credential dumping, credential storage | ✅ Done  |
| 21  | 03 Sep     | CyberDefenders   | Rhysida - 0x4                  | 30 min     | Lateral Movement & Command and Control: Service-based remote execution (SysInternals Tools), C2 Beacon Established, RMM Abuse AnyWhat, System Discovery | ✅ Done  |
| 22  | 04 Sep     | CyberDefenders   | Rhysida - 0x5                  | 15 min     | Exfiltration: Data Collection & storage in Public Directory, File Compression before exfil | ✅ Done  |
| 23  | 05 Sep     | CyberDefenders   | Rhysida - 0x6                  | 15 min     | Impact: Ransomware execution across multiple hosts, Ingress Tools stored in sensetive location | ✅ Done  |
| 24  | 06 Sep     | CyberDefenders   | T1598.002 - Spearphishing      | 30 min     | Malicious Attachment Analysis, Used OleDump + Outlookspy Tools for Investigation, .LNK file used for downloading further payloads. | ✅ Done  |
| 25  | 07 Sep     | CyberDefenders   | ???                            | 30 min     | ??? | ⏳ Planned  |
| ... | ...        | ...              | ...                            | ...        | ...                                  | ...       |

---

## 🧠 Reflections & Notes

### Day 1 – 13 Aug
> Started with foundational network security concepts. Revisiting TCP/IP and packet inspection helped clarify Wireshark usage. Felt a bit slow but solid.

### Day 2 – 14 August
> Worked on the OpenCTI platform, investigated the techniques, tools, and procedures (TTPs) used by APT29 (Cozy Bear :bear: - Russia says Hi :wave:) and mapping them to the MITRE ATT&CK framework. Very cool platform with multiple helpful features (Overview of topics, A very rich knowledge-base, History on threats, adversaries, tools, you name it, Attribution of attacks, IOCs and many more...)

### Day 20 - 02 September
> Rhysida Lab (Persistence) Identified registry changes For persistence the attacker made registry changes that appear
...

---

## 📦 Tools & Platforms

- [TryHackMe](https://tryhackme.com/)
- [CyberDefenders](https://cyberdefenders.org/)
- [Hack The Box](https://www.hackthebox.com/) 
- [BTLO](https://blueteamlabs.online/)

---

## 📈 Milestones

- ✅ Day 1–10: Kickstart phase
- ⏳ Day 11–30: Deepen learning and build momentum
- 🔥 Day 31–90: Mastery and real-case emulation

---

## 💬 Contact / Follow Along

Follow my journey via commits or [Twitter/X](https://x.com/yourprofile) and feel free to join in!



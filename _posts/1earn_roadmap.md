#roadmap

---

`The document is updated occasionally. If you find that the link is invalid or the content is wrong, please let me know through issue`

---

## Preface

There are a lot of security knowledge points and they are very complicated. It takes a lot of time to master them. If you just read the article, copy and paste to take notes, and collect a certain POC and think you know it, I understand. This kind of superficial taste will still end up trapping yourself in the end. , must be hands-on practice.

This technical article by Meituan is very well written [How to accumulate technology at work] (https://tech.meituan.com/2018/04/16/study-vs-work.html) The following paragraph is one of them part of it, share it with everyone

---

As the ancients said: "What you learn on paper will only make sense, but you will never know it without doing it." There is a so-called 721 model in the field of learning: 70% of personal growth comes from job practice, 20% from learning from others, and 10% from training. Although this theory is controversial, it is generally good for engineers to rank the importance of practice, learning and training. Therefore, attaching importance to practice and growing in practice are the most important learning principles.

There are two types of human cognition: perceptual cognition and rational cognition. These two cognitions are irreplaceable. Practice largely comes from perceptual learning, while reading is more like rational learning. Take learning to drive a car as an example. It is difficult to imagine that someone can drive a car just by learning book knowledge.

Book knowledge is mainly about evangelism - describing abstract prototypes, while descriptions of specific application scenarios are often vague, and the relationship between abstract prototypes is only briefly touched upon. Using the same precise language to describe application scenarios and relationships will lose focus and make people confused. So, growing by just reading books is like walking on one leg.

The correct way to learn is to attach importance to practice, make full use of your perceptual cognitive potential, and hone yourself in projects. In practice, deliberate practice of certain key movements will also achieve twice the result with half the effort.

---

Below I will build a basic learning roadmap from the perspective of a security engineer. Since I personally prefer web+misc, I do not include reverse engineering content. Please forgive me.

If you are good at reverse engineering, pwn, mobile security or other security-related skills and provide relevant tutorials, blogs, notes, etc., you are welcome to submit a PR and build a roadmap together.

![](https://github.com/ffffffff0x/assets/img/roadmap.png)

## Getting Started

Basic skills are important

- Use of virtual machines - Learn to install and use virtual machines, and understand the differences between several VMware network connections
     - slightly

- How to use the Internet scientifically - Everything you need to know
     - slightly

- Markdown syntax - it is also important to learn to take notes
     - slightly

---

## Basic development knowledge

- Character encoding - nothing much to say, basic skills
     - slightly

- The use of git and github - Participating in more open source projects can quickly improve your development level
     - [Git study notes](https://github.com/ffffffff0x/1earn/Develop/version control/Git study notes.md)

- Handling of data types
     -xml
     -json

- Regular - Understand regular syntax
     - [regex](https://github.com/ffffffff0x/1earn/Develop/regex/regex.md)

- python - Master the syntax, be able to write POC, and be able to modify exp as needed
     - slightly

---

## WEBDevelopment

-dotnet
     - Not finished yet :)

-java
     - Not finished yet :)

-php
     - Not finished yet :)

---

## Basic operation and maintenance knowledge

### Linux operation and maintenance

- What is Linux
     - [Distribution](https://github.com/ffffffff0x/1earn/Integrated/Linux/notes/distribution.md)
     - [Process](https://github.com/ffffffff0x/1earn/Integrated/Linux/notes/process.md)

- Linux basic commands
     - [Speed-Linux](https://github.com/ffffffff0x/1earn/Integrated/Linux/Speed-Linux.md)

- Linux service construction - At least learn how to build httpd and nginx
     - [Power-Linux](https://github.com/ffffffff0x/1earn/Integrated/Linux/Power-Linux.md)

- Docker usage - must be mastered, it can save you a lot of time
     - [Speed-Docker](https://github.com/ffffffff0x/1earn/Integrated/virtualization/Docker/Speed-Docker.md)

### Network knowledge

- TCP/IP model - You need to understand what IP and MAC are, and what are the common protocols at each layer and their functions.
     - slightly

### Windows Server

- Commonly used commands under Windows
     - [Speed-Win](https://github.com/ffffffff0x/1earn/Integrated/Windows/Speed-Win.md)

- What can Windows server do?
     - [Windows Basic Service Construction](https://github.com/ffffffff0x/1earn/Integrated/Windows/Experimental/Windows Basic Service Construction.md)

---

## web basics

- HTTP protocol
     - slightly

-html+js
     - slightly

- web basic vulnerabilities
     - [Web_Generic](https://github.com/ffffffff0x/1earn/Security/RedTeam/WebSecurity/Web_Generic/Web_Generic.md)

- web logic vulnerability
     - [IDOR](https://github.com/ffffffff0x/1earn/Security/RedTeam/WebSecurity/IDOR.md)

- Shooting Range - If you have free time, you can practice on the shooting range
     - [Range](https://github.com/No-Github/1earn/tree/master/1earn/Security/RedTeam/Web%E5%AE%89%E5%85%A8/%E9%9D%B6% E5%9C%BA)

## webAdvanced

- Various common vulnerability exploits
     - [BS-Exploits](https://github.com/ffffffff0x/1earn/Security/RedTeam/WebSecurity/BS-Exploits.md)

-OOB
     - [OOB](https://github.com/ffffffff0x/1earn/Security/RedTeam/WebSecurity/Web_Tricks/OOB.md)

-JWT
     - [JWT Security](https://github.com/ffffffff0x/1earn/Security/RedTeam/Web Security/Web_Tricks/JWT Security.md)

## Code audit

- Not finished yet :)

---

## Host Security

### linux

- linux permissions, files
     - [Certification](https://github.com/ffffffff0x/1earn/Integrated/Linux/notes/certification.md)
     - [File](https://github.com/ffffffff0x/1earn/Integrated/Linux/Notes/File.md)

- Linux privilege escalation and vulnerability exploitation
     - [OS-Exploits](https://github.com/ffffffff0x/1earn/Security/RedTeam/OSSecurity/OS-Exploits.md#linux)

- linux lol
     - [Linux Security](https://github.com/ffffffff0x/1earn/Security/RedTeam/OS Security/Linux Security.md#lol)

### windows

- windows certification system
     - [Certification](https://github.com/ffffffff0x/1earn/Integrated/Windows/notes/certification.md)

- Windows privilege escalation and vulnerability exploitation
     - [OS-Exploits](https://github.com/ffffffff0x/1earn/Security/RedTeam/OSSecurity/OS-Exploits.md#windows)

- windows lol
     - [Windows-LOL](https://github.com/ffffffff0x/1earn/Security/RedTeam/OSSecurity/Experimental/Windows-LOL.md)

- windows rdp exploit
     - [Windows Security](https://github.com/ffffffff0x/1earn/Security/RedTeam/OS Security/Windows Security.md#rdp)

- windows credential capture
     - [Windows Security](https://github.com/ffffffff0x/1earn/Security/RedTeam/OS Security/Windows Security.md#certification)

---

## Post penetration

### Privilege Elevation

- linux privilege escalation
     - [OS-Exploits](https://github.com/ffffffff0x/1earn/Security/RedTeam/OSSecurity/OS-Exploits.md#linux)

- windows privilege escalation
     - [OS-Exploits](https://github.com/ffffffff0x/1earn/Security/RedTeam/OSSecurity/OS-Exploits.md#windows)

- Third-party software privilege escalation
     - [Elevation of Privilege](https://github.com/ffffffff0x/1earn/Security/RedTeam/Post-Exploitation/Elevation of Privilege.md)

### Permission maintenance

- Various webshells
     - [Permission maintenance](https://github.com/ffffffff0x/1earn/Security/RedTeam/Post-infiltration/Permission maintenance.md#web)

- Windows permission maintenance
     - [Permission maintenance](https://github.com/ffffffff0x/1earn/Security/RedTeam/Post-infiltration/Permission maintenance.md#win)

- Linux permission maintenance
     - [Permission maintenance](https://github.com/ffffffff0x/1earn/Security/RedTeam/Post-infiltration/Permission maintenance.md#linux)

- Various C2, anti-kill
     - [Permission maintenance](https://github.com/ffffffff0x/1earn/Security/RedTeam/Post-infiltration/Permission maintenance.md#c2-rat)

### windows domain

- What is a work group, a domain, and how to build a domain environment
     - [Workgroup](https://github.com/ffffffff0x/1earn/Integrated/Windows/notes/workgroup.md)
     - [domain](https://github.com/ffffffff0x/1earn/Integrated/Windows/notes/domain.md)
     - [Windows domain setup](https://github.com/ffffffff0x/1earn/Integrated/Windows/Experimental/Windows domain setup.md)

- Kerberos
     - [Certification](https://github.com/ffffffff0x/1earn/Integrated/Windows/Notes/Certification.md#Domain Certification)

- Domain credentials capture
     - [Windows Security](https://github.com/ffffffff0x/1earn/Security/RedTeam/OS Security/Windows Security.md# domain)

- Domain control privilege escalation
     - [OS-Exploits](https://github.com/ffffffff0x/1earn/Security/RedTeam/OSSecurity/OS-Exploits.md#domain)

-pth/k/t
     - [PTH](https://github.com/ffffffff0x/1earn/Security/RedTeam/OS Security/Windows Security.md#pth)
     - [PTT](https://github.com/ffffffff0x/1earn/Security/RedTeam/OS Security/Windows Security.md#ptt)

-Exchange
     - [Exchange Build](https://github.com/ffffffff0x/1earn/Integrated/Windows/Experiment/Exchange Build.md)
     - [Exchange](https://github.com/ffffffff0x/1earn/Security/RedTeam/Post-Exploration/Experimental/Exchange.md)

---

## Blue Team Skills

### Blue team service construction

### analytical skills

- linux logs, information
     - [Log](https://github.com/ffffffff0x/1earn/Integrated/Linux/Notes/Log.md)
     - [Information](https://github.com/ffffffff0x/1earn/Integrated/Linux/Notes/Information.md)

- windows logs, messages
     - [Log](https://github.com/ffffffff0x/1earn/Integrated/Windows/Notes/Log.md)
     - [Message](https://github.com/ffffffff0x/1earn/Integrated/Windows/Notes/Message.md)

- Malicious file analysis
     - [Analysis](https://github.com/ffffffff0x/1earn/Security/BlueTeam/Analysis.md)

### Forensic Technology

- Document forensics
     - [Forensic](https://github.com/ffffffff0x/1earn/Security/BlueTeam/Forensic.md#File Forensic)

- Memory forensics
     - [Memory Forensics](https://github.com/ffffffff0x/1earn/Security/BlueTeam/Notes/Memory Forensics.md)

- Traffic Analysis
     - [Traffic Analysis](https://github.com/ffffffff0x/1ear

# How I Detect Malicious Activity

I’m **Johnny Colomo**. I’m certified in **DoD 8570 Level II** and hold several industry-recognized certifications, including **CCNA**, **CompTIA Security+**, and **CompTIA CySA+**. These qualifications highlight my expertise in cybersecurity and make me well-suited for roles across various industries, including both government and private sectors.

I’ve specialized in **In-Flight Entertainment (IFE)** systems during my time at **Panasonic**, and I’m currently working at **Trader Joe's**, where I run their **Vulnerability Management Program** using **Pentera Software**.

---

When I’m tracking down threats, I start by paying close attention to both **network** and **host-level indicators**. 

- **Network side**: I look for rogue devices popping up, odd traffic spikes, scanning attempts, or anything that breaks the usual flow—things that hint someone’s probing where they shouldn’t be.  
- **Hosts** give up a lot too: high CPU usage, strange system changes, malware traces, or signs that data might be slipping out the back door.

**Apps?** They have tells of their own—suddenly created user accounts, weird behaviors, or logs that don’t make sense. Even **URLs** can tip me off when they’re obfuscated or tied to phishing campaigns. Basically, if it moves or makes noise in the environment, I’m paying attention to it.

---

## 🧠 Threat Intelligence vs. Threat Hunting—And How I Use Both

I don’t just wait for alerts. I actively **dig**.

- On the **threat intel** side, I stay on top of the **tactics, techniques, and procedures (TTPs)** used by threat actors—whether we’re talking APTs, insiders, or nation-state-level players.  
- I leverage both open and closed sources and believe in **sharing that intelligence** through platforms like **CERTs and ISACs**. It helps raise everyone’s game.

Then there’s **threat hunting**. That’s where I roll up my sleeves:

- I go looking for indicators of compromise, misconfigurations, or anything that could lead to bigger issues.
- I’ve deployed **honeypots**, safeguarded **crown-jewel assets**, and uncovered **stealthy footholds** in environments others thought were clean.

---

## ⚙️ The Core Stuff I Never Skip

Understanding the fundamentals is **non-negotiable**.

I’ve built a strong foundation around:

- System processes  
- Time sync  
- OS internals  
- Logs  
- File structures  

I’m comfortable whether I’m in a **Linux terminal**, **Windows Event Viewer**, or digging through **syslogs**.

**Environments I've worked in:**

- Cloud  
- On-prem  
- Hybrid  
- Virtualized  
- Containerized  

Each setup changes the threat landscape, and I tailor my approach accordingly.

**Networking?** I bring a **Zero Trust** mindset:

- Segmentation strategies  
- SASE frameworks  
- SDN architecture  
- IAM practices like MFA, SSO, federation, PAM, and passwordless solutions

**Data security:**

- Implement encryption protocols (PKI, SSL)  
- Protect sensitive data (CHD/PII)  
- Use DLP and CASB tools to control where data goes and who accesses it

---

## 🛠️ The Tools and Skills That Back It All Up

I use tools like:

- `tcpdump` and **Wireshark** to analyze network traffic down to the packet
- **EDR platforms**, with integrated **threat intel feeds**
- **SIEMs**, which I configure and tune
- **SOAR tools**, to automate response workflows

**Email forensics**:

- Check SPF, DKIM, and DMARC to trace spoofing/fraud attempts

**File analysis**:

- Sandbox suspicious executables  
- Cross-reference with **VirusTotal**

I’m big on **behavioral detection**—spotting anomalies like impossible travel or strange logon patterns.

And yes, I script:

- Python  
- PowerShell  
- Regex

I use scripts to parse JSON, XML, and pull **actionable intel** from raw data.

---

## 🚀 Making Security Operations More Efficient

I don’t believe in manual, repetitive work where automation can take over.

- I streamline with **API integrations**
- Design **workflows** that reduce alert fatigue
- Tie tools together into a **unified dashboard**

The goal? Reduce noise, minimize human error, and surface what actually matters.

More than anything, I bring a mindset of **continuous improvement**. I’m not just here to maintain systems—I’m here to **elevate them**.

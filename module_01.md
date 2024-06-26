# CIA Triad
+ Authenticity
+ Non Repudiation

# Methods:
- Integrity - Hashing
- Authenticity/Non Repudiation - Digital Signatures

# Attacks = Motive + Method (Exploit) + Vulnerability

# Attacks:
- Passive: Not directly engaging
- Active: Engaging (High Risk/High Reward)

# Different ways attacks can occur:
- Close-In: Close proximity to target
- Insider: Privileged Access
- Distribution: Supply chain targetting attacks

# CEH Methodology
- Foot printing & Reconnaissance
- Scanning
	-- Enumeration
	-- Vulnerability Analysis
- Gaining Access
	-- Cracking Passwords
	-- Vulnerability Exploitation
	-- Escalating Privileges
- Maintaining Access
	-- Executing Applications
	-- Hiding Files
- Covering Tracks
	-- Covering Logs
	
# Lockheed Martin - Cyber Kill Chain
- Reconnaissance: Gathering data
- Weaponization: Creating a payload using an exploit and a backdoor
- Delivery: Delivery of payload to the victim
- Exploitation: Exploiting the vulnerability to gain access
- Installation: Installing the malware on the victim's system
- Command and Control: Create a C2C server to communicate with the victim machine
- Actions on objectives: Perform the required actions to fulfil the set objectives

# Tactics, Techniques and Procedures: pattern of activities and methods associated with specific threat actor or group of threat actors.
- Tactics: The way an attacker performs the attack
- Techniques: The technical methods used by the attacker to achieve immediate results
- Procedures: Organizational approaches followed by threat actors to launch an attack

# MITRE ATT&CK Framework: A knowledge base of techniques, tactics and procedures, used for developing threat methodologies
- Pre-ATT&CK
	-- Reconnaissance
	-- Weaponize
- Enterprise ATT&CK
	-- Deliver
	-- Exploit
	-- Control
	-- Execute
	-- Maintain

# Diamond Model of Intrusion Analysis: Used for identifying the cluster of events by recognizing an atomic event, known as the diamond event; helpful in developing efficient migration approaches.
- adversary: attacker entity
- victim: target entity
- capability: how the attack was performed
- infrastructure: the technical pathway utilized by the adversary in the attack

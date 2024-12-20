# H1 Adversarial mindset

>*You will read the famous cyber kill chain paper. And start your very own hacking lab by installing Linux virtual machine.*
>*You can only start this homework after accepting course rules in Moodle.*

## Assignment

Full assignment can be viewed at the courses website : [H1 Adversarial mindset](https://terokarvinen.com/trust-to-blockchain/#h1-adversarial-mindset)

## Assignment answers

### Assignment links

Links to assignment answers.

- [Answer to assignment x](h1_Adversarial_mindset.md#x)
- [Answer to assignment a](h1_Adversarial_mindset.md#a)
- [Answer to assignment b](h1_Adversarial_mindset.md#b)
- [Answer to assignment c](h1_Adversarial_mindset.md#c)
- [Answer to assignment d](h1_Adversarial_mindset.md#d)
- [Answer to assignment e](h1_Adversarial_mindset.md#e)
- [Answer to assignment f](h1_Adversarial_mindset.md#f)

## x

>x) Read and summarize. Some bullets is enough for a summary.
>- Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains
>- Darknet Diaries. Pick one episode. (RSS feed)
>- MITRE ATT&CK FAQ explains the ATT&CK Enterprise Matrix. Explain "tactic", "technique" and "procedure" in context of ATT&CK, and give an example of each. The enterprise matrix is big, you can just glimpse/browse it to see what's available instead of reading hundreds of pages.

### Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains

The document summarized can be read at the Lockheed Martin website : [Intelligence-Driven Computer Network Defense
Informed by Analysis of Adversary Campaigns and
Intrusion Kill Chains](https://lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf)

- Introduces the concept of an Intrusion Kill Chain, to engage and mitigate intrusions by APT:s (Advanced Persistent Threat).
    - APT:s are a new class of security threat that are manually operated and more focused, they poses a more complex threat than threats deemed more "traditional", such as worms and viruses.   
- The Intrusion Kill Chain consists of seven (7) phases used by the attacker in sequence:
    1. Reconnaissance
    2. Weaponization
    3. Delivery
    4. Exploitation
    5. Installation 
    6. Command and Control (C2)
    7. Actions on Objectives
    - If an intrusion is prevented within a kill chain phase, the attacker cannot continue to the next phase.
- The Intrusion Kill Chain drives to be more proactive in mitigating intrusions by utilizing Intelligence-driven computer network defense (intelligence-driven CND) analyzing the compromised phase (if detected) of the attack but more importantly the previous phases within the the kill chain.
    - Analyzing and determining indicators for the attack.
        - Indicators can be atomic (indivisible information, like an IP-address), computed (collected data from the intrusion, like hash values) and behavioral (collection of atomic and computed values which form a logical structure).
    - Applying a mitigation for the affected phase and possibly the phases before and after, if if the indicators analyzed enable this.
    - Moving the possibility of detection to earlier phases of the kill chain.
    - Finding similarities between attacks based on discovered indicators, applying mitigation if possible and forming a coherent picture a possible intrusion campaign.
    - Aiming to be a step ahead of possible attackers and increasing the costs to benefit ratio for the attacked.

### Darknet Diaries, episode 83: NSA Cryptologist

I chose this episode randomly, since the last episode is numbered at 150, I would assume the first is 1. The RANDOM bash function decided for me (*echo $((1 + $RANDOM % 150))*). R
As far as the name goes, I'm pleased with the result. The episode can be found at the Darknet Diaries website : [EP 83: NSA Cryptologist](https://darknetdiaries.com/episode/83/) 

#### Episode summary

The host, Jack Rhysider Interviews two former NSA agents, Marcus J. Carey and Jeff Man.

##### Marcus J. Carey

- Found interest in programming in a young age (elementary school)
- Enlisted in the Navy as was trained in cryptography.
- While in the navy learned about signals intelligence, cryptographic systems, secure communication protocols, network hardware, programming and security.
- Was considered an asset of the NSA, even though he was a part of the navy. Received extensive provided by the DoD (department of defense).
- Worked in the NOC (Network Operation Center) and helped in setting up a NSA:s SOC (Security Operation Center).
- After leaving the navy, started working in the Department of Defense Cyber Crime Center (CSC), which does forensic investigation for the DoD.
- While at CSC, trained federal officers in cyber security and build a cyber security range to help with this.
    - The cyber security range consisted of physical equipment (servers, networking hardware) and was a complete mock-up of a corporate network.
    - Made it possible to test and train new threats securely and physically interact with the devices. 
    - 
- Marcus started his own company, Threatcare, which creates threat scenarios and runs exercises in cyber ranges and tabletop format. The company was bought by ReliaQuest, which is marcus's current employer.
- Started writing books on cyber security, named Tribe of Hackers and was published three so far in teh series. Has he's own podcast : [Tribe of Hackers Podcast](https://tohpodcast.buzzsprout.com/)
    - Also has written children’s book about security.
- He's son also works in cyber security, as a software engineer for Rapid7, the company that owns [Metasploit](https://www.metasploit.com/)

Marcus noted that the NSA is and has been committed to their primary objective, protecting the US communications and assets (which include domestic private companies operating abroad), even though it may not always seem like that. 
The NSA provides public information regarding defensive measures and best practices but the offensive measures and reconnaissance methods are kept private. He mentioned Bin Ladens satellite phone tracking and the unintentional leaking of this information as an example.

##### Jeff Man

- Jeff considers on having the hacker mentality since a young age.
    - By a hacker mentality he means a person who has the capability for critical thinking, has curiosity and is eager to learn more in a faster pace than the general public.
- Started working in the NSA in 1986 and ended up in information security (InfoSec) and was trained as a cryptographer.
- Note that in those days at the NSA, cryptographic decryption was done primarily manually. 
- Started to study the possibility to use computers for encryption and decryption.
    - At that time, cryptographic systems were based on hardware, not software.
    - States tha in a way he hacker the NSA, by doing something in a NSA styled corporate environment should have  been impossible. 
- Began to suspect weaknesses in the one-time-pad based cryptographic system.
    - People using the the pad more than one time and thus severely weakening it's security. In essence, incorrectly using a tested and proven cryptographic method.
    - The notion being that if he "enemy" has been caught doing this, are we also doing it?
- Was part of the System and Network Attack Center (SNAC), that was formed in 1995.
- Was a part of, what is by some considered the first red team. They used the name "The Pit" for they're office.
    - The team focused more on offensive network security, learning from hackers and studying and generating exploits.
        - In those days, zero-day exploits were not really a concept, they relied on operation system (UNIX in most cases) weaknesses that they had found to achieve privilege escalation. 
- The Pit did internal penetration testing in NSA, looking for weaknesses in security.
- What was learned by Jeff Mann and the team working in the Pit, has been used in governmental security testing. Most notably operation Eligible Receiver, which was intended to test the security of the US defense forces network.

##### Summary

I liked this episode, it maybe is bit more personal than the other episodes but like how it tels security history through personal experiences.

### ATT&CK Enterprise Matrix

The documents summarized can be read at the Mitre Corporation website: [Mitre ATT&CK FAQ](https://attack.mitre.org/resources/faq/), [Mitre ATT&CK Enterprise Matrix](https://attack.mitre.org/matrices/enterprise/)

- A large, bi-annually updated knowledge repository, that consists of tactics and techniques used by cyber security threat actors. created and maintained by the Mitre Corporation.
- Consists of two parts:
    - ATT&CK for Enterprise, focuses on enterprise IT-networks and cloud applications.  
    - ATT&CK for Mobile, focuses on mobile devices.
- Consists of techniques for multiple systems and platforms, these include Windows, Linux, macOS, Android and iOS to name a few.
- Focuses on 14 tactics that consists of different techniques and procedures (TTP:s) used by APT:s (Advanced Persistent Threat). [APT explained in the cyber Kill chain](h1_Adversarial_mindset.md#hutchins-et-al-2011-intelligence-driven-computer-network-defense-informed-by-analysis-of-adversary-campaigns-and-intrusion-kill-chains).
    - Tactics
        - Represents the "why" or more precisely the goal of the technique used by the threat actor.
        - A tactic could be have the goal of for example: 
            - Gaining vital information of a target (*Reconnaissance*).
            - Gaining access to the target system (*Initial Access*).
            - Achieving privilege escalation in the target system (*Privilege Escalation*).
    - Techniques
        - Represents the "how" to achieve the chosen tactic.  
        - A technique could be for example:
            - Gathering target information by analyzing the target network (*Gather Victim Identity Information*).
            - Gaining initial access to the target system by exploiting a weakness in the target system (*Exploit Public-Facing Application*).
            - Achieving privilege escalation in the target system by abusing the systems elevation control mechanism (*Abuse Elevation Control Mechanism*).
        - Techniques can also be explained by sub-techniques, which describe the technique more precisely.
            - For instance, gathering target information by analyzing the target networks IP-addresses (*Gather Victim Network Information: IP Addresses*).
    - Procedures
        - Describes how a threat actor uses techniques and sub-techniques to achieve a chosen tactic.
        - Procedures could be for example:
            - A threat actor gathering target information by analyzing the target networks IP-addresses by using nmap (a network discovery and security auditing tool).
            - A threat actor gaining initial access to the target system by exploiting a weakness in the target system by using a SQL-injection.
            - A threat actor achieving privilege escalation in the target system, abusing the systems elevation control mechanism by using Cobalt Strike.
- So how do tactics, techniques, and procedures represent themselves in the ATT&CK Enterprise Matrix?
    - Tactics are the column headers in the matrix (left to right)
    - Techniques are boxes under the header, you also could call them rows.
        - Sub-techniques (if available) are listed within the techniques.
    - Procedures are listed within a given technique and/or sub-technique.
    - In the previous examples, precise ATT&CK Enterprise Matrix tactics, techniques and sub-techniques are within round brackets written in *italic*.
- ATT&CK Enterprise Matrix consists of tactics in a logical and chronological order a threat actor would proceed in, from reconnaissance to impact.

## a

>a) How would you compare Cyber Kill Chain and ATT&CK Enterprise matrix? Who do you think could benefit from these models?

The Cyber Kill Chain and ATT&CK Enterprise Matrix serve different purposes and in my view aren't comparable, even though they can complement each other and work side by side.
The Cyber Kill Chain provides a model for analyzing, identifying and mitigating intrusions and developing a more robust approach on cyber security. 
The ATT&CK Enterprise Matrix on the other hand, consists of documented incidents and guidelines on how mitigate them.
These two can coexists, ATT&CK Enterprise Matrix providing knowledge of tactics and techniques used to battle the APT:s in different phases of the Cyber Kill Chain, while the new acquired knowledge of incidents from the Cyber Kill Chain can be added to the ATT&CK Enterprise Matrix.


>Who do you think could benefit from these models?

I don't know if this is a tough question, since I had to contemplate on it for a while. Generally I would divide the beneficial parties in two, one for The Cyber Kill Chain and another for the ATT&CK Enterprise Matrix.
The Cyber Kill Chain benefits most people and organizations working in or with cyber security, since it deals more on on active and adaptive defense measures.
I see the ATT&CK Enterprise Matrix benefiting system and network administrators, since it provides knowledge on how to defend against intrusion tactics and techniques that are already documented.
There is also the notion that both parties would benefit from both models, since I see these two models working side by side strengthening each other as stated before.
There is also a third group that would benefit from these models, maybe a bit indirectly with out dwelling too much on the technical side and these are the decision makers, CEO:S, COO:s and CTO:s. Reviewing these should raise the question "are we doing enough", "should we do more", "Are we already doing something".

## b

>b) Pick a security incident and learn about it. Write briefly about it. Point out the concepts of threat actor, exploit, vulnerability and (business) impact. (You can find writeups about security incidents from Darknet Diaries and Krebs)

I decided to search Krebs on security for an incident to investigate and I found an interesting case involving Github users. 
The incident report can be read at the Krebs on security website: [This Windows PowerShell Phish Has Scary Potential](https://krebsonsecurity.com/2024/09/this-windows-powershell-phish-has-scary-potential/)

### Incident review

The incident was reported on having affected GitHub users at his stage.
GitHub users have received phishing emails alerting them of security vulnerabilities in they're repositories. To fix this, the email provides a link (not pasted in this report) that takes the user to a webpage that asks them to verify that they are human (CAPTCHA). Normally you select pictures containing certain elements (trains for instance) or asks you to identify a picture but this one asks you to do three steps once you click the "I'm not a robot" button to verify that you indeed are a human.

*Note: This only works in Windows operating systems*

1. Press windows key + R (open Windows “Run” prompt)
2. Press CTRL + v (Paste something to the "Run" prompt)
3. Press enter (Executes what is pasted)

Once you click the "I'm not a robot" button at the website, it copies malicious code (powershell) to target systems clipboard. It is then pasted to the "Run" prompt and executed, downloading and executing a file (l6e.exe), that downloads the Lumma Stealer malware that is designed to steal credentials from the infected PC and once acquired, sends them to a C2 server using HTTP Post requests. This malware has been confirmed by Virustotal.com by their analyzes. 

Now, as the Krebs report states, GitHub users are most likely more vigilant and aware than the average PC user and chances are, that not that many fell to this trap, but what if this was less targeted and affected regular PC users? The likelihood of success would most likely increase drastically.

The incident report does not describe how target selection was made for this, but I would assume that the emails have been compromised with the association to GitHub (compromised emailing list perhaps), manual reconnaissance and target selection seems to be too far fetched in this case.

[Malpedia](https://malpedia.caad.fkie.fraunhofer.de/details/win.lumma) states that Lumma Stealer is developed by a threat actor Shamel (also using the alias Lumma) and is available through a Malware-as-a-Service (MaaS) model. Origin most likely from Russia (Made available on Russian speaking forums), but at this stage I cannot find confirmation on this. It seems that the primary target of this is cryptocurrency wallets and two-factor authentication (2FA) browser extensions, which would mean that the end goal is monetary gain. This could be done by extorsion, blackmail, by the theft of cryptocurrency assets or by selling the hijacked credentials.

Honestly, while the user can protect themselves from this by being careful, this is in an way quite elegant. CAPTCHA checks are so common place now days that this could be (and most likely is) executed accidentally if the user is less tech savvy. 
The impact from this malware could be quite severe, for businesses and private people alike. I would imagine that this is going to get a bit more refined and be less targeted. 

## c

>c) Install Debian on Virtualbox. Report your work, including the environment (including host OS, the real physical computer used), the steps you took and their results.

### Foreword
It has been a few years since I last used Virtualbox, I have had little need to run full virtualization, since containers (Docker for Linux, Jails for BSD) fulfill my current needs. Last time I used a full virtualization platform  was most likely virt-manager (libvirt), since I managed the virtual machines using cockpit, although backup automation was done using virsh on the command line.

### System environment
- Computer
    - CPU: AMD 7700 (Clocked @ 5.45 GHz)
    - Motherboard: ASUS B650M-plus-wifi
    - Memory: 32 GB DDR5 6000MHz
    - Graphics card: AMD RX 7900XTX
    - Storage: 1TB Western digital black SN850X (m.2, nvme)
    - Operating system: EndeavourOS (Arch linux)
    - Desktop: KDE plasma 6 (Wayland)
    - Package manager: pacman

### Virtualbox Installation

I usually review the Arch linux wiki for information, just in case. [Virtualbox Arch wiki page](https://wiki.archlinux.org/title/VirtualBox).

Update the system. Review upgrades if there is any and approve if deemed acceptable (This step is not mentioned again, but it's always a good practice to even glance what you are about to update)
- *sudo pacman -Syu*

Reboot system if required.

Install Virtualbox and the required dependencies if there is any. Note that the Arch linux offers three (3) different host module packages, consult the Arch wiki page for the right one for you. In my case it is "virtualbox-host-modules-arch", since I only use the LTS kernel as a backup option.
- *sudo pacman -S virtualbox*

Reboot system or manually load the Virtualbox kernel module.
- To load manually *sudo modprobe vboxdrv*

Other considerations regarding the installation on Arch linux.
- To enable USB access from the host machine, add user to the vboxusers group. I am not planning on using this now.
    - *sudo usermod -a -G vboxusers username*
- **Extension pack**, this is a new feature for me. The Oracle VM VirtualBox Extension Pack should provide additional features, but I don't think we need them now.
Start the regular Virtualbox GUI.
    - *VirtualBox*

![Arch linux Virtualbox installation](/img/virtual_box_install.png)

### Virtual machine installation

Download the installation ISO image from the [Debian home page](https://www.debian.org/)
Create a new virtual machine in Virtualbox.

- Click the *New* icon
    - Set VM name
    - Set VM location, the default location (user home folder) is OK, since we probably don't have access rights outside our home folder (no super user privileges used)
- Select ISO image
    - Check "Skip unattended Installation", since we want to do things manually. 
     Click *Next*
- Select memory amount and processor count, let's stick with the defaults.
    - Click *Next*
- Create a virtual hard disc for the Virtual machine. 
    - 20 GB is OK for this test.
    - No pre-allocation needed, pre-allocation reserves the entire disc size, instead of used space.
    - Click *Next*
-  Review and click finish if everything is in order.

| New VM                                | Memory                                | Virtual hard disc                             | Review                                |
| ------------------------------------- | -----------------------------------   | --------------------------------------------- | ------------------------------------- |
| ![](/img/Virtualbox_vm_install_1.png) | ![](/img/Virtualbox_vm_install_2.png) | ![](/img/Virtualbox_vm_install_3.png)         | ![](/img/Virtualbox_vm_install_4.png) |

Start the VM by clicking *Start*

![](/img/Virtualbox_vm_install_5.png)

And at this stage I remembered that I have disabled the virtualization support on the motherboard. Don't enable it if you are not using it they say...
Let's reboot the system and make the necessary changes in the UEFI and try again.

![](/img/Virtualbox_vm_install_6.png)

Everything seems to be in order now.

![](/img/Virtualbox_vm_install_7.png)

### Debian Virtual machine installation

Let's select the graphical installation.
- Select installation language, English will do in our case.
- Select location, Finland can be found under the "Other" selection, but let's just say we are in the US.
- Select keyboard layout. NOTE! US usually uses an ANSI keyboard layout, which is ok but I prefer ISO (used in Finland for example).
- Select hostname for the new VM. "vbox" is OK in this case, but you should select a unique hostname for each computer for the sake of convenience.

| Language                              | Location                              | Keyboard layout                               | Hostname                              |
| ------------------------------------- | -----------------------------------   | --------------------------------------------- | ------------------------------------- |
| ![](/img/Virtualbox_vm_install_8.png) | ![](/img/Virtualbox_vm_install_9.png) | ![](/img/Virtualbox_vm_install_10.png)        | ![](/img/Virtualbox_vm_install_11.png)|

- No domain name needed, but let's use something that should be safe => *.local*
- Set password for the root (system administrator) account.
    - Let's use something short this time, since this is a test installation. Otherwise you should use a good password, preferably randomly generated with with letters (small and large), numbers and special characters.
- Create a user account, let's use the same username as the host system. Note, usually the system asks your'e name and generates a username based on that. I like to skip this and define my username manually.
- Add a password fot the new user account.
- Configure system clock, select time zone. Note, the VM thinks we are in the US..

| Domain name                               | Root password                                 | User account                                  | User account password                     | System Clock                              |
| ----------------------------------------- | --------------------------------------------- | --------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| ![](/img/Virtualbox_vm_install_12.png)    | ![](/img/Virtualbox_vm_install_13.png)        | ![](/img/Virtualbox_vm_install_14.png)        | ![](/img/Virtualbox_vm_install_15.png)    | ![](/img/Virtualbox_vm_install_16.png)    | 


- Select how the disc is partitioned. Let's stick to the default in this case.
- Select disc used (only one available as a default)
- Confirm choices and continue

| Disc partitioning                         | Disc selection                                | Partitioning options                          |  Partitioning overview                    | Partitioning confirmation                 |
| ----------------------------------------- | --------------------------------------------- | --------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| ![](/img/Virtualbox_vm_install_17.png)    | ![](/img/Virtualbox_vm_install_18.png)        | ![](/img/Virtualbox_vm_install_19.png)        | ![](/img/Virtualbox_vm_install_20.png)    | ![](/img/Virtualbox_vm_install_21.png)    | 

- Wait for the installation to complete

![](/img/Virtualbox_vm_install_22.png)

- No need to scan for another installation media for the package manager.
- Select location and mirror to be used with the package manager 
- No need for a proxy
- Wait for the package manager configuration.

| Additional media                          | Mirror country                                | Mirror address                                |  HTTP proxy                               | Configuration                             |
| ----------------------------------------- | --------------------------------------------- | --------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| ![](/img/Virtualbox_vm_install_23.png)    | ![](/img/Virtualbox_vm_install_24.png)        | ![](/img/Virtualbox_vm_install_25.png)        | ![](/img/Virtualbox_vm_install_26.png)    | ![](/img/Virtualbox_vm_install_27.png)    | 


- Let's not participate in this for now.

![](/img/Virtualbox_vm_install_28.png)

- Select desktop environment and system utilities, KDE plasma is usually a good choice, xfce is another good choice.
- Wait for the installation to finish
- Install CRUB boot loader, select the VM system disc for this.
- Wait for the installation to finnish and click *Continue* to reboot the new VM.

| Desktop environment & utilities           | Software installation                         | GRUB installation                             | GRUB installation location                | Finish installation                       |
| ----------------------------------------- | --------------------------------------------- | --------------------------------------------- | ----------------------------------------- | ----------------------------------------- |
| ![](/img/Virtualbox_vm_install_29.png)    | ![](/img/Virtualbox_vm_install_30.png)        | ![](/img/Virtualbox_vm_install_31.png)        | ![](/img/Virtualbox_vm_install_32.png)    | ![](/img/Virtualbox_vm_install_33.png)    | 

- Once the VM reboots, select the default choice in GRUB (or just wait) and you can log in to you're new VM

| Login screen                          | New VM desktop                          |
| ------------------------------------- | --------------------------------------- |
| ![](/img/Virtualbox_vm_install_34.png) | ![](/img/Virtualbox_vm_install_35.png) | 

## d

>d) Voluntary bonus: Use either (Hutchins et al 2011) cyber kill chain or MITRE ATT&CK framework for analyzing a security incident. You can pick any incident you want (even the one you used earlier in this homework), but try to pick a source that gives you enough technical and business detail to do some analysis. (If you're in a hurry, cyber kill chain is much simpler. If you're technically skillful, you might find ATT&CK interesting)

I will try and analyze the security incident described in [assignment b](h1_Adversarial_mindset.md#b) using the Mitre ATT&CK Enterprise Matrix.
I will do this in a chronological order by the factors I can find.

1. Tactic: Resource Development
    - Technique: Obtain Capabilities
    - Procedure: The threat actor buys a license (presumably since its a Maas model) for the Lumma Stealer malware.

2. Tactic: Reconnaissance
    - Technique: Gather Victim Identity Information
    - Sub-technique: Email Addresses
    - Procedure: The threat actor acquires GitHub user emails from a compromised emailing list (presumably)

3. Tactic: Initial Access
    - Technique: Phishing
    - Sub-technique:  Spearphishing Link
    - Procedure: The threat actor sends users an email warning account/repository vulnerability, containing a link to a web site that tries to make the user run malicious powershell code on their computer.

4. Tactic: Execution
    - Technique: User Execution
    - Sub-technique: Malicious Link 
    - Procedure: The users clicks on a link, which copies malicious powershell code to the target computers clipboard. If the user does a the link describes, the user will execute the power shell code, which downloads a malware to the target computer.

5. Tactic: Collection
    - Technique: Automated Collection
    - Procedure: The Lumma Stealer malware searches for credential and bitcoin wallet information using regex, copies files if set criteria is met.

6. Tactic: Exfiltration
    - Technique: Automated Exfiltration
    - Procedure: The malware sends the copied credential and/or bitcoin wallet data to a C2 server via HTTP POST request.

7. Tactic: Impact
    - Technique: Financial Theft
    - Procedure: The threat actor used the Lumma Stealer malware to steal the targets cryptocurrency wallet.

8. Tactic: Impact
    - Technique: Account Access Removal
    - Procedure: The threat actor used the Lumma Stealer malware to steal the targets credentials and use them to lock the account.

9. Tactic: Impact
    - Technique: Financial Theft
    - Procedure: The threat actor ransoms the locked user accounts the the targets.


## e

>e) Voluntary bonus: What do you consider the fundamentals of security? What are the theoretical foundations you would teach on the first day?

I will approach this question in a more general, non-technical fashion. Meaning that I will try to answer this question if it was asked by a "regular", non IT person.
In my opinion, the fundamentals of security can be stated in two words, Trust and Consideration.

The question of trust can be put into many situations, when the person should ask the question "Can I trust this"? "Is this email valid and trustworthy?", "Can I trust this new computer program", "Is this website safe?".
After we have formed some level of trust, we can start considering our next action and form the question, "Should I do this?". "Should I click on this link from an email?", "Should I install this computer program", "Should I allow remote access to my computer by the person on the telephone?".
I'm not trying to over simplify things, but usually the weakest link in security is people and it should be prudent to acknowledge this and not be offended by it

## f

>f) Voluntary bonus: Do you think anything is missing from these models, Cyber Kill Chain or MITRE ATT&CK?

I would not say that anything is missing from these, since in my opinion they answer their given purpose, but I would like to make an addition to the ATT&CK Enterprise Matrix.
The Mitre ATT&CK Enterprise Matrix documents tactics, techniques and procedures well and gives advice on detecting and mitigating these, but what I would like to is links to more technical information regarding techniques and sub-techniques. By technical information I mean practical examples and more detailed exploit descriptions.
I know that this most likely is not what the Enterprise Matrix is intended to provide and there is a danger that i would become bloated.

## laughing-chainsaw
**disable windows task mgr leveraging badusb / badkb scripts**

**Target: windows 11**

**Version 1.0 Flipper_Ducky / OMG_Cable**

## Introduction
Attackers continuously develop sophisticated methods to exploit vulnerabilities in systems. One of the more insidious techniques that has gained popularity among threat actors is the use of Ducky Script attacks, particularly when combined with USB Rubber Ducky devices. These attacks allow malicious actors to execute powerful payloads with little to no detection, making them a favorite tool in the arsenal of cybercriminals and even nation-state actors.
## The Ducky Script: A Silent, Lethal Weapon
The Ducky Script presented above is a prime example of how a seemingly harmless script can be weaponized to compromise a system. At first glance, the script appears simple—it disables the Windows Task Manager by modifying the Windows registry. However, the implications of such an action can be devastating.
By disabling Task Manager, attackers prevent victims from easily terminating malicious processes, effectively rendering them blind to ongoing attacks. Task Manager is often the first tool a user reaches for when they suspect something is amiss with their system. Without it, users are left vulnerable, with fewer options to detect and mitigate the attack.
## Real-World Usage and Threat Landscape
**In the hands of a skilled attacker, this script can be combined with other techniques to achieve a variety of malicious goals:**

1.  **Persistence and Evasion:** Disabling Task Manager is often one step in a larger attack strategy. For example, an attacker might use this script in conjunction with malware that establishes persistence on the target system. By disabling Task Manager, the attacker makes it significantly more challenging for the victim to detect and remove the malware.
2.  **Data Exfiltration:** Nation-state actors have been known to use similar techniques to maintain a foothold within compromised networks. Once inside, they can quietly exfiltrate sensitive data over extended periods, all while the victim remains unaware of their presence.
3.  **Ransomware Deployment:** Ransomware operators could use this script as part of their payload to ensure that their encryption process runs uninterrupted. By preventing the user from accessing Task Manager, they make it harder to stop the ransomware from locking down files.
4.  **Denial of Service (DoS):** While not a traditional DoS attack, disabling key system functionalities like Task Manager can severely disrupt a user's ability to use their computer. This form of attack could be used to render critical infrastructure inoperable, serving as a form of digital sabotage.
## Leveraging USB Ducky Script Devices

Ducky Script is a popular tool for executing keystroke injection like the one provided. An **OMG_Cable** looks like an ordinary USB charging cable but functions as a keyboard, allowing it to input keystrokes at lightning speed. When plugged into a target machine, it can execute a preloaded script in a matter of seconds. The speed and stealth of a **Flipper_Ducky** or **USB_Rubber_Ducky** make it ideal for social engineering attacks, where an attacker simply needs to plug the device into an unattended or unlocked machine to deliver a payload.
## Conclusion
The Ducky Script provided is not just a simple script—it’s a powerful tool that can be leveraged by malicious actors to achieve a wide range of nefarious goals. From disabling security measures to aiding in persistent attacks, the potential damage is significant.

**Disclaimer:** The information provided is for educational and testing purposes only. The use of these techniques for unauthorized access or harm to any system without explicit permission is illegal and unethical.

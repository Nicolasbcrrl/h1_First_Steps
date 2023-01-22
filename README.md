# Abstract
* Conventional cyber defense tools (intrusion detection systems and anti-virus) focus on at-risk components, traditional intrusion methodologies and observed system 		vulnerabilities.

* Advanced Persistent Threat or APT is a new type of threat that is defined by an adversary that is more trained, better equipped and more informed about conventional   cyber defense methods. The APT threat renders conventional methods insufficient to counter the attacks launched by this adversary. This new type of adversary conducts multi-year attacks targeting economic, private or national security information.

* Cyber defense techniques have put in place a feedback loop, which will allow the collection of information about the attacks. This will allow defenders to improve     their knowledge of the opponent. This method allows to reduce the chances of success of the opponent at each attack.

*  Based on the collected information, the creation of the attack pattern named kil Chain was possible. The Kill Chain model is a model that allows to synthesize the     different phases of an intrusion, in order to prepare and anticipate the next move of the adversary and thus reduce its chances of success.

* The accelerated evolution of threats, requires an investment in network defense and especially a defense model based on intelligence as highlighted by the use of the   Kill Chain.

# 3.2 Intrusion Kill Chain
The Kill Chain is a schematic of the different states thought by the US military to target and engage an adversary, in order to create the desired effects. The Kill Chain consists of different steps: finding the potential targets of the adversary, locating them, tracking and observing them, targeting them with the appropriate means to create the desired effect, engaging the adversary and finally evaluating the effects of the operation. Illustrated as a chain to highlight that if one link fails, the whole process is interrupted.

Based on the military Kill Chain, a new Kill Chain has been developed specifically for intrusions. This chain takes as a base that an intrusion implies that the adversary must be in possession of enough power to establish a presence in a trusted environment. 

This new Kill Chain is composed of the following steps: 

* **Reconnaissance**: Search, identification and selection of targets.

* **Weaponization**: This is the act of coupling a deliverable with software to allow the adversary remote access to the environment. This is usually done using client applications such as PDF files that are used as the armed deliverable.

* **Delivery**: Transmission of the weapon to the targeted environment. This is done via email attachments, USB sticks or websites.  

* **Exploitation**:  Once the weapon is transmitted to the victim. It can target an application, an operating system vulnerability by automatically executing code or exploit users directly.

* **Installation**:  The adversary can also remain in the environment and cause no apparent damage, but simply take information. This is achieved by installing a remote access Trojan  or backdoor on the victim's system.

* **Command and Control (C2)**: A hot compormis will send a signal to a server Internet controller to establish a C2 channel. This is required to be done manually for APT type malware. As soon as the connection is established, the intruder has full control over the victim's system.

* **Action on Objectives**: It is only at this stage that the intruder can carry out his real objective. Most often, intruders seek to extract confidential information or use the victim's system as a weapon to attack another victim.

# 3.3 Courses of Action
The Intrusion kill Chain becomes an intelligence model for defenders as the enterprise's defensive capabilities are put in place to defend the resources the attacker is targeting. With this method, defenders can put in place procedures and investment plans to close the capability gap. This methodology is the foundation of intelligence-driven, allowing the defender to make decisions and take action based on intelligence and in-depth knowledge of the adversary. 

The table below illustrates a matrix with different tools to be used by the defender according to the phase of the kill chain and also for what purpose these tools are used. As for example in the exploitation phase we find the host intrusion detection systems (HIDS) which can passively detect exploit, patching denies exploitation altogether and data execution prevention. It includes traditional systems like the network intrusion detection systems (NIDS) and the firewall access control lists (ACL).


![Table 1 : Courses of Action Matrix](courses_of_action_metrix.PNG)

* Completeness equals resilience, which is the main goal of the defender in the face of persistent and creative attackers who continually improve their techniques.

* The "zero-day" or "day one attack" exploit is a flawed approach that does not take into account the fact that the exploit is only one change in a larger process.

* A defensive strategy of full use of indicators forces the attacker to readapt his approach to each attack. This means that the attacker's costs increase with each intrusion attempt.

* Defenders can generate metrics of this resilience by measuring the performance and effectiveness of measures taken against the adversary.

* The illustration below shows that at least one mitigation measure was implemented for three intrusion attempts. It also shows that attackers' techniques are evolving very quickly. This implies that defenders must also implement new mitigations. For example, in December the defenders managed to dig up the weaponry and block it. Unfortunately, the attackers managed to get through by evolving their technique and equipment. This shows that if the measures taken do not evolve, they become useless.


![Mitigation](mitigation.PNG)

# Sources
[Hutchins et al 2011: Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains, chapters Abstract, 3.2 Intrusion Kill Chain and 3.3 Courses of Action](https://lockheedmartin.com/content/dam/lockheed-martin/rms/documents/cyber/LM-White-Paper-Intel-Driven-Defense.pdf)

---------------
# Commande Line Basics Revisited

* Time passes but the use of the command line does not disappear. It is convenient, fast, easy to automate and easily accessible. 

* Before launching yourself in the world without user interface, that of the command line. You need to know some things: 
  * This simbol "$", is the user command prompt. It is placed automatically by the system.
  * The "#" symbol is a character for placing a comment. Everything that is put after it will be ignored by the system, as it is considered as text.

# Moving and looking around

When we use the command line, we must always keep in mind that we are always in a directory. By default when opening the command line, you will be in the working directory.

* The command "pwd" allows you to know in which directories you are. 

 $ pwd
/home/tero


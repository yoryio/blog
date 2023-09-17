---
title: Incident Response Lifecycle
date: 2023-09-16T18:29:24-05:00
cover:
    image: "assets/incident.png"
---
Is made up of the major steps taken in intrusion detection and response with the goal to be _agnostic_ to type of attack, it means that the cycle can be adapted to any scenario.

## Preparation

_Before trying to understand the adversary is necessary to organizations to understand themselves, with this we can assess if we are giving the **opportunity** to the adversary and help understand if we fall in the **intentions** or objectives of this adversaries_ 

- **Attack Surface mapping**
- **Telemetry and Visibility**
- **Hardening**
- **Process and Documentation**
- **Practice**

How attackers see us through Internet?
How we recollect information about our systems and networks?
How easy could be to an attacker to get into our systems?
Are we prepared and know what and how to do the necessary actions in a cyber attack event?

## Identification

- Anomaly in network connections
- Phishing Emails
- Anomaly in resources used by servers or endpoints

This phase is considered the first impact an adversary had done to our users, systems or resources.

Can be described as something unusual or unexpected behavior in the network.

With Threat Intelligence we can improve our Identification phase with the increase of accuracy and quantity of methods to identify adversaries earlier.

## Containment

The first stage where we can take actions on the incident, because the previous stages are more about information gathering.

Initial attempt to stop the attacker and mitigate malicious activities with short-term actions and objectives but while preparing to the long-term response. It's important to take in consideration the _capability_ of the attacker because with these actions is 

These actions can be represented with:

- Disabling networks, ports, systems, applications, etc.
- Blocking access.
- Locking suspicious user accounts.

## Eradication

Unlike _Containment_, the actions in this stage are intended to kick out definitely the adversary from our the systems with a range of activities that needs to be considered very careful:

- Scanning and removing any trace of malware or tools
- Resetting and remediating all impacted users and devices
- Recreating any password, certificates and tokens.
- Patching software vulnerabilities and changing vulnerable configurations.
- Security awareness among all users

## Recovery

With the strong actions taken in the previous stage, now is the time to go back to a non-incident state. Also here we work with a lot of teams of the organization, both security and non-security teams to return to business as usual.

## Lessons Learned

Asses past decisions and improve future decisions.
Helps evaluates the performance and ask questions through each stage of the incident.

- What happened?
- What did we do well?
- What could we have done better?
- What will we do differently next time?

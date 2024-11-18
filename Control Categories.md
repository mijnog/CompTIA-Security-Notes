# Control Categories

## Technical Controls
**Logical controls executed by a system**
Includes:
- Authentication
- Access control
- Auditing
- Cryptography

e.g. *Firewalls, session locks, radius servers, raid 5 arrays.*

## Managerial Controls
**Techniques and concerns addressed by an organization’s management**

They focus on decisions and the management of risk.
- Procedures
- legal and regulatory policies
- SDLC,
- the computer security lifecycle
- information assurance
- and vulnerability management/scanning.

Managerial, or administrative, controls include business and organizational processes and procedures, such as security policies and procedures, personnel background checks, security awareness training, and formal change-management procedures.

## Operational Controls

**Controls executed by people that are designed to increase individual and group system security.**

- User Awareness Training
- Fault tolerance
- Disaster recovery plans
- Incident handling
- Computer Support
- Baseline Configuration Development
- Environmental Security

Executed by people with technical expertise, who understand how to implement what management asks.

Operational controls include *physical controls* that form the outer line of defense against direct access to data, such as protecting backup media; securing output and mobile file storage devices; and paying attention to facility design details, including layout, doors, guards, locks, and surveillance systems.

## Physical Controls

The first line of defense in controlling access, (as a firewall is the first line of defense for a network.)
Implementing physical acces security methods should be a top priority for an organization.
Proper building entrance access and secure access to physical equipment are vital.
Anyone coming and going should be logged and surveilled.

*Operational/physical controls* include organizational culture and physical controls that form the outer line of defense against direct access to data, such as protecting backup media; securing output and mobile file storage devices; and paying attention to facility design details, including layout, doors, guards, locks, and surveillance systems.

# Control Types (different to categories)

## Preventive Controls 
*(Sometimes referred to as Deterrent Controls)*

**Employed before an event occurs and designed to prevent incidents from occurring.**

E.g.

- Biometric systems
- NIPS
- RAID 1 (prevent loss of data)
- Access lists
- Passwords
- fences (google that)

Can be bypassed by finding a flaw in implementation logic.

Preventive controls include:
- Security awareness 
- Separation of duties
- Access control
- Security policies 
- Intrusion prevention systems.

## Deterrent Controls

**An organization uses deterrent controls to try to deter threat actors from executing offensive assaults on its environment.**

E.g. 
- An alarm system
- A system banner warning that any unauthorized attempt to log in will be monitored

Primarily used to discourage attackers from attempting to compromise a system. May not prevent them entirely.

## Detective Controls

**Aim to monitor and detect unauthorized behavior or hazards.**

These types of controls are generally used to alert to failures in other types of controls, such as preventive, deterrent, and compensating controls. Detective controls are very powerful while an attack is taking place, and they are useful in postmortem analyses to understand what has happened. 

E.g.
- Audit logs
- IDSs
- Motion detection,
- SIEM systems.

Detective controls are used during an event to determine whether malicious activity is occurring or has occurred. Examples include CCTV/video surveillance, alarms, NIDS's, and auditing. Detective controls warn that physical security measures are being violated and attempt to identify unwanted events after they have occurred. Common technical detective controls include:

- Audit trails
- Intrusion detection systems
- System monitoring
- Checksums
- Anti-malware.

## Corrective Controls
*Sometimes referred to as **compensating controls***
**Used after an event has occurred.**

Limit the extent of damage and help the company recover from damage quickly and include all the controls used in an incident to correct the problem.

Includes:

- Tape backup
- Hot sites 
- Other fault tolerance and disaster recovery methods

Examples:

- Quarantining a system
- Sending a guard to block an intruder
- Firing somone for not following security policy

These controls are reactive and provide measures to reduce harmful effects or restore a system after being compromised.

E.g.

- System upgrades
- Data backup restores
- Vulnerability mitigation
- Anti-malware

## Compensating Controls

**Mechanisms to satisfy security requirements that are hard or impractical to implement**

E.g.

- Using NAC, DLP, or other security methods instead of expensive hardware encryption modules (technical)
- Additional logging and auditing instead of implementing seperation of duties.

Intended to reduce risk of an existing or potential control weakness.

E.g.

- Audit trails
- Transaction logs that someone in a higher position reviews.

*PROCEED WITH CAUTION WHEN IMPLEMENTING COMPENSATING CONTROLS!*

## Directive Controls (Instructive Controls)
**strategies established to guide the operation and use of systems within an organization.**

Serve to direct or instruct users towards secure behaviour.

Examples:

- Standards
- Procedures
- Policy Guidelines
- Security Awareness Training

Standards define the approved use of hardware, software, security measures, and procedures within an organization.
Procedures provide detailed instructions for executing certain tasks securely and effectively.
Policy guidelines dictate how a specific policy should be executed, outlining the steps to be taken, roles and responsibilities, and expectations for adherence.


 




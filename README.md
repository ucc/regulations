UCC Committee Regulations 2018
==============================

This document constitutes a complete list of all current UCC Committee Regulations. It is recommended that these regulations be reviewed and explicitly replaced or reapproved during the first meeting of a new Committee immediately following an Annual General Meeting. Included are appendices for any technical details or guidelines pertaining to club operations that are not appropriate as regulations.

- The Committee shall make every reasonable effort to clearly communicate all responsibilities and tasks to the members to whom they apply
	- The Committee may require a member sign a statement that they are aware of their responsibilities
	
- Members wishing to apply to join any group are ecouraged to contact committee in writing

- Members shall adhere to the [Club Service Usage Guidelines](#usage_guidelines)

- There shall be a group known as 'Door'
	- An absolute majority of the Committee may appoint Door members
	- Door members have the following responsibilities:
		- To act in good faith towards the club
		- To represent the club to current and prospective members
		- To open and oversee the use of the room
		- To maintain a welcoming and helpful atmosphere in the room
		- To ensure the safety and security of club members and property in the room
		- To ensure the club and its members adhere to club, Guild, and University rules and standards including but not limited to:
			- The [Club Service Usage Guidelines](#usage_guidelines);
			- The [Guild Tenancy policies](https://myuwastudentguild.com/clubs-societies/resources/tenancy/); and
			- The [University Codes of Ethics and Conduct](http://www.hr.uwa.edu.au/policies/policies/conduct/code)
		- To accept money from members on behalf of the club
	- The Committee will afford powers to Door members so that they may fulfil these responsibilities
	- An absolute majority of the Committee may remove Door members or call for their reapplication as they see fit
	- See the [Door Group Manual](#door_manual) for technical details about Door

- Committee and Door members may temporarily evict and ban individuals from the room (known as 'dooring' or 'being doored')
	- The dooring may be conditional, for example on time or behaviour
	- Doorings lasting a significant amount of time should be reported to Committee and Door
	- The maximum duration of a dooring is until the next Committee or General Meeting, at which the dooring will be reviewed, and either extended or lifted

- There shall be a group known as 'Wheel'
	- An absolute majority of the Committee in consultation with existing Wheel members may appoint Wheel members
	- Wheel has the following responsibilities:
		- To act in good faith towards the club
		- To maintain the functionality and security of club systems and services
		- To ensure the club and its members comply with University network access policies
		- To adhere to the [Wheel Group Ethical Guidelines](#wheel_ethics)
	- The Committee will afford powers to Wheel members so that they may fulfil these responsibilities
	- An absolute majority of the Committee may remove Wheel members or call for their reapplication as they see fit

- Wheel members shall have administrator access to all club machines, and are responsible for administering such access

- Wheel members may lock and unlock member accounts
	- Accounts may be locked if:
		- It is requested by the Committee; or
		- There is, in the opinion of the Wheel member, a technical or security reason to do so; or
		- The user of the account is no longer a member of the club
	- An attempt should be made to notify the user of the account of any locking
	- An account should remain locked only so long as there is reason for it to be

- A club member may be rewarded with dispense credit for performing certain services for the club
	- Emptying a full bin: 96c
	- Restocking the coke machine: 128c
	- Driving a food run: 512c

- Donations to the club must be reported to the Committee, and are considered to remain the property of the donor until they are accepted by the Committee, at which point they become the property of the club

- The club shall abide by the [Joint Event Subcommittee Regulations](https://github.com/gozzarda/subcommittee_regulations)

Appendix A: Club Service Usage Guidelines <a name="usage_guidelines"></a>
-----------------------------------------

Any services provided by the club are provided with the understanding that the user will behave in a responsible manner. These guidelines are in addition to the conditions of any external services accessed using the club's services. Ignorance of any guideline or rule is not considered adequate excuse for the violation of that guideline or rule. Account security and activity is considered the responsibility of the holder of that account.

Fundamental guidelines include but are not limited to:

- Not attempting to break or weaken security measures in any way without prior and continued permission from the administration of all systems and networks concerned
- Not making excessive, inappropriate, or abusive use of any club services as defined by the administration of that service
- Treating the services, systems, users, and administrators of any club service with respect and common courtesy
- Not participating in any illegal activities
- Obeying the guidelines and rules of all systems, services, and networks accessed
- Not using club services in such a way that hinders their more appropriate or club-related use
- Not sharing account access or other security credentials with another entity without the permission of the administration of the service in question

In general the following uses are considered to have priority corresponding to their order:

1. Club work
2. University work
3. General education
4. General computing including gaming

Appendix B: Door Group Manual <a name="door_manual"></a>
-----------------------------

The following is intended as a quick reference guide for Door members

- Contact numbers
	- Security (Emergency): (6488) 2222
	- Security (Non-emergency): (6488) 3020
	- UWA Medical Centre: (6488) 2118
	- Note: 6488 prefix is not required on campus landlines

- See the [Instructions for Signing Up New Members](http://wiki.ucc.asn.au/HowToCommittee/NewMembers)

- Dispense cheat sheet:
	- `dispense username +1000 "money in safe bag 14"` will add 1000 cents ($10.00) to the account 'username' with a note saying that the cash has been put in the safe in money bag number 14
	- `/home/other/coke/cokelog` or `~coke/cokelog` contain logs of dispense activity
		- Browse the file with `less ~coke/cokelog`, press q to quit the less program
		- See the bottom (most recent) few lines with `tail ~coke/cokelog`
		- Search for occurrences of "mytext" using `grep "mytext" ~coke/cokelog`
	- `dispense refund username coke:3` will refund the account 'username' for a purchase of the item in slot 3 of the coke machine, and similarly for `snack:` and `pseudo:`
	- `dispense slot snack:23 120 "tiny teddies"` will rename slot 23 of the snack machine to "tiny teddies" and set its price to 120 cents ($1.20)
	- `man dispense` or `dispense --help` will show full documentation of the `dispense` command

- Door members are able to dispense the 'door' item and so unlock the electronic door lock by:
	- Logging into the snack machine and entering item code 55
	- Logging into any club machine with 'dispense' installed and running the command `dispense door`

- If you are the last Door member leaving the room and closing up:
	- Bin any litter
	- Make sure all members and their property are out of the room
	- Turn off:
		- Lights
		- Fan
		- Soldering iron
	- Close and lock:
		- Tool cupboard
		- Machine room
		- Windows
		- Room door
	- If Cameron Hall is empty close the fire escape and lock the doors at the top and bottom of the front stair well

- In the event of a fire or other emergency, evacuate in accordance with [University Emergency Procedures](http://www.safety.uwa.edu.au/incidents-injuries-emergency/procedures), closing the room if it is empty and safe to do so

Appendix C: Wheel Group Ethical Guidelines <a name="wheel_ethics"></a>
------------------------------------------
As a UCC Wheel Member I will uphold the ethical ideals and obligations which this entails. I am committed to maintaining the confidentiality and integrity of computer systems which we manage, for the benefit of the Computer Club members. These guidelines below are not intended to cover all situations, but to outline the ethics the UCC expects from Wheel Members. Common sense must dictate how things are dealt with, when difficulties arise.

### Fair Treatment
I will treat everyone fairly. I will not discriminate against anyone on grounds such as age, disability, gender, sexual orientation, religion, race, or national origin.

### Privacy
Private information of users will be accessed only when necessary to do so to ensure security is not compromised, and only to the extent required to ensure security. Private information will be treated confidentially, and forgotten when it does not affect security.

### Communication
I will keep users informed about computing matters that may affect them --- such as conditions of acceptable use, sharing of common resources, maintenance of security, occurrence of system monitoring, limitations of electronic media, and any relevant legal obligations.

### System Integrity
I will strive to ensure the integrity of the systems for which I have responsibility, using all appropriate means -- such as regularly maintaining software and hardware; analysing levels of system performance and activity; and, as far as possible, preventing unauthorised use or access.

### Cooperation
I will cooperate with and support fellow Wheel Members, and abide by rulings of the UCC Committee. I acknowledge the community responsibility that is fundamental to the integrity of local, national, and international network resources.

### Honesty
I will be honest about my competence and will seek help when necessary. When my professional advice is sought, I will be impartial. I will avoid conflicts of interest; if they do arise I will declare them.

### Education:
I will continue to update and enhance my technical knowledge and management skills by training, study, and the sharing of information and experiences with my fellow professionals.

### Social Responsibility
I will continue to enlarge my understanding of the social and legal issues that arise in computing environments, and I will communicate that understanding to others when appropriate. I will strive to ensure that policies and laws about computer systems are consistent with my ethical principles.

### Environmental Quality
I will strive to achieve and maintain a safe, healthy, productive environment for all users.

Any Wheel Member may be requested to justify an action by other Wheel Members or Committee. It is expected that when Wheel Members affect users that they give an explanation to the user(s) concerned.
If a Wheel Member acts in a way contrary to the Club's interests, they will be removed from Wheel. Further action, as per UWA Network Policy and other such agreements binding the Club, may be taken if necessary.

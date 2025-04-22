# Diamond Model
## Description
The Diamond Model is a methodological framework for comprehensive analysis of cyber incidents, which represents each attack as a “diamond” of four elements:
- Adversary — who is behind the attack: group, motivation, skills.
- Capability — what tools and exploits were used.
- Infrastructure — servers, domains, communication channels through which attacks were carried out.
- Victim — what organization or system became the target, its role and significance.
- This approach helps analysts-researchers not only understand the technical details of the incident, but also “build a portrait” of the event itself and its participants: who the attackers are, how they act and why.

## Practice
- Artifact Collection: When reviewing Red Team reports or Blue Team data, create a Diamond for each incident to document who attacked, what tools and infrastructure they used, and what systems were compromised.
- Connectivity: Compare Diamonds across incidents to find common infrastructure nodes, similar tactics, or repeating tools to help build attacker group profiles.
- Attacker Profiling: Create a profile of the adversary based on their motivation (financial, political), technical level, known APT groups, and their TTPs (tactics, techniques, procedures).
- Scenario Analysis: Visualize a diamond for each stage of the attack to visualize the relationship between elements and identify points where the chain could be broken.

## Connection with other knowledge
- MITRE ATT&CK: ATT&CK techniques describe Capability and partly Infrastructure — the Diamond Model helps link them to specific adversary and victim.
- Threat Intelligence: Known infrastructure and group profiles enrich the adversary and infrastructure in the Diamond.
- Incident Analysis: The Diamond Model serves as a common framework for compiling technical and tactical details into a single report.

## How to improve
- Practice building Diamonds using open cases (leaks, attacks on well-known organizations) — describe each diamond element and check the validity of the connections.
- Get familiar with visualization tools (for example, MISP or ATT&CK Navigator) that support diamond rendering to automate some of the work.
- Collect APT group profiles: based on public reports from Positive Technologies, Mandiant, Kaspersky — fill in the adversary field in the diamond.
- Develop critical analysis skills: check each adversary and infrastructure hypothesis for reliability, relying on several sources.
- Integrate the Diamond Model into regular reviews: include it in analytical report templates and presentations so that colleagues get used to a single structure.

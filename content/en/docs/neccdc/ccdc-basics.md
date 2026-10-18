---
title: "CCDC Basics"
description: "How CCDC works, who is involved, and how to compete"
includeInList: false
---

## How It Works

### The Scenario

Each team is given an identical network for a fictional organization.
It always includes a mix of Windows and Linux servers and business services such as web, email, DNS, databases, and file shares.
The systems are intentionally insecure, with weak or default passwords, outdated software, and planted vulnerabilities.

### Keep Services Up

A scoring engine regularly checks whether each team's required services are reachable and working correctly, for example the website loads, mail can be sent, and DNS resolves.
Every successful check earns points.

### Complete Business Tasks (Injects)

Throughout the event, management (White Team) issues business tasks called injects.
Examples include writing a security policy, adding a user, deploying a new service, producing an inventory, or briefing executives.
Injects are time-limited and scored on quality and completeness.

### Defend Against the Red Team

A team of professional penetration testers attacks every team's network throughout the competition.
Successful compromises such as admin access, data theft, defacement, or persistence result in point deductions.

#### Report Incidents

Teams can win back some of the points lost to the Red Team by submitting clear, accurate incident reports describing what happened, how it was detected, and how it was remediated.
See the [Red Team advice](/docs/red-team/red-team-advice) and [sample incident report](/docs/red-team/sample-ir) for what a good report looks like.

For how these are weighted, see the [Scoring Overview](/docs/neccdc/scoring).

## The Teams

**Blue Team**: The student competitors.
They defend their environment's network, keep services online, and complete injects.

**Red Team**: Industry professionals acting as attackers.
They probe, exploit, and maintain access to Blue Team systems to simulate real threat actors.

**White Team**: Competition officials & judges.
They enforce the rules, write and grade injects, review incident reports, and act as in-room moderators.
See [volunteering with White Team](/volunteer/white-team).

**Black Team**: The technical staff who build and run the competition infrastructure, networks, and scoring engine.
See [volunteering with Black Team](/volunteer/black-team).

## How to Compete

1. **Check Eligibility.**
   Competitors must be students currently enrolled at a college or university, and all team members must meet the eligibility requirements in the [NECCDC Rules](/docs/neccdc/rules) and the [National CCDC Rules](https://nationalccdc.org/rules.html).
2. **Form a Team.**
   Find a faculty or staff member to act as coach and recruit students with a mix of skills (Windows, Linux, networking and firewalls, web and database services, incident response, and strong writing for injects and reports).
3. **Join the League and Register with Nationals.**
   See [Join the League](/join), or the [Exhibition Team](/docs/neccdc/neccdc-exhibition-team) option to compete in the Qualifier competition only.
4. **Prepare.**
   - Practice hardening systems: change default credentials, remove unneeded accounts and services, patch, and configure firewalls.
   - Learn to hunt for persistence: scheduled tasks, startup items, rogue users, web shells, SSH keys, and services.
   - Build checklists and scripts for the first 15, 30, and 60 minutes.
   - Practice writing short, professional business documents.
   - Run mock practice competitions and divide responsibilities by system.
   - Study past [competition history](/history) and team packets.
5. **Compete.**
   Teams compete in the NECCDC Qualifier, and the top teams advance to the NECCDC Regional.
   The regional winner advances to the National CCDC.

## Tips for New Teams

- Communication and organization matter as much as technical skill.
- Don't break services while securing them.
- Don't ignore injects. They are half of the score.
- Assume your systems are already compromised when the event starts.

---
title: Troubleshooting and Incident Guide
toc: true
---

## Introduction

This site is meant to be an assist to our daily operations and troubleshooting that we perform. In addition, if there are tasks, i.e., upgrading servers or configuring out networks, setup of a new campus, etc., this will be a place to document things that really aren't manual-related information. This way, if people are out, new, or unreachable, we have a common starting point to give outsiders and new people alike a fighting chance at keeping our schools operational, from an IT perspective.

Why do we want to move this direction? Consider the alternative- an unmanaged incident and the impact it can have.

## The Anatomy of an Unmanaged Incident
In this type of scenario, everyone is doing their job, as they saw it. How could things go so wrong? A few common hazards can cause an incident to spiral out of control.

### Sharp Focus on the Technical Problem
We tend to hire people for their technical prowess. So it’s not surprising that when busy making operational changes to a system, trying valiantly to solve a problem, there becomes a granular focus. People like this are often not in a position to think about the bigger picture of how to mitigate a problem because the technical task at hand is overwhelming.

### Poor Communication
For the same reason, individuals that troubleshoot are often far too busy to communicate clearly. Nobody knew what actions their coworkers are taking. Administrators and leaders may be angry, customers are frustrated, and other people in IT who could have lent a hand in debugging or fixing the issue weren’t used effectively. There is a saying in open source culture which says, "All bugs are shallow given enough eyes". If you have people who may be able to help, it doesn't make sense to isolate yourself and to try and be the hero in the name of saving a minute, but possibly risking hours or worse.

### Freelancing
When making changes to a system with the best of intentions, if you don't coordinate with coworkers, event when technically in charge of troubleshooting, changes can make a bad situation far worse.

### Elements of Incident Management Process
Incident management skills and practices exist to channel the energies of enthusiastic individuals. For example, Google’s incident management system is based on the Incident Command System, which is known for its clarity and scalability.

A well-designed incident management process has the following features:

* Recursive Separation of Responsibilities
>It’s important to make sure that everybody involved in the incident knows their role and doesn’t stray onto someone else’s >turf. Somewhat counterintuitively, a clear separation of responsibilities allows individuals more autonomy than they might >otherwise have, since they need not second-guess their colleagues.

>If the load on a given member becomes excessive, that person needs to ask the planning lead for more staff. They should >then delegate work to others, a task that might entail creating subincidents. Alternatively, a role leader might delegate >system components to colleagues, who report high-level information back up to the leaders.

### Several distinct roles should be considered when approaching problems:

* Incident Command
The incident commander holds the high-level state about the incident. They structure the incident response task force, assigning responsibilities according to need and priority. De facto, the commander holds all positions that they have not delegated. If appropriate, they can remove roadblocks that prevent Ops from working most effectively.

* Operational Work
The Ops lead works with the incident commander to respond to the incident by applying operational tools to the task at hand. The operations team should be the only group modifying the system during an incident.

* Communication
This person is the public face of the incident response task force. Their duties most definitely include issuing periodic updates to the incident response team and stakeholders (usually via email), and may extend to tasks such as keeping the incident document accurate and up to date.

* Planning
The planning role supports Ops by dealing with longer-term issues, such as filing bugs, ordering dinner, arranging handoffs, and tracking how the system has diverged from the norm so it can be reverted once the incident is resolved.
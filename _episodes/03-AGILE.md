---
title: "AGILE Development"
teaching: 0
exercises: 0
questions:
- "Key question (FIXME)"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "First key point. Brief Answer to questions. (FIXME)"
---

## Agile Methodology
At the other end of the spectrum as the Waterfall-based methods are agile methodologies.
When issues with the Waterfall-based methods became evident in the 1990s, agile methodologies surged in popularity because they are optimized to deal with poorly understood and/or changing requirements during development.
They tend to incorporate other practices to improve software quality.

> ## The Agile Manifesto
> We are uncovering better ways of developing software by doing it and helping others do it.
> Through this work we have come to value: 
> - **Individuals and interactions** over processes and tools
> - **Working software** over comprehensive documentation
> - **Customer collaboration** over contract negotiation
> - **Responding to change** over following a plan 
> That is, while there is value in the items on the right, we value the items on the left more.

(Nearly) everything about Agile Development is based on one value: Identify and eliminate sources of WASTE

### Individuals and Interactions over Processes and Tools
Good processes and tools are important, but it’s more important to make sure that people are happy, productive and communicating.
If a process or tool isn’t working for people, change it!
Agile methods favor lightweight, widely accessible tools over fancy, expensive software packages.
This can mean collaborative whiteboards in public areas and simple text formats like markdown and restructuredText for documents.
Agile methods promote a sustainable pace for software development that can be sustained indefinitely and without heroics.

Agile methods incorporate very regular communication of status, identification of issues, and retrospectives/postmortems on efforts.
This is preferably in face-to-face interactions like daily interactions between software developers.
Planning and retrospective discussions are usually held every 1-4 weeks.

Agile methods also respect the time of individuals.
Meetings are time-boxed so that software developers can focus on the problems they are solving.
Daily status meetings are kept to 15 minutes and planning meetings are kept to 1 hour per week of development effort.

### Working Software over Comprehensive Documentation
Requirements specifications and design documents have one main purpose:  to help get to useful, working software.
Customers generally don’t care about them once they have their software!

Agile methods generally maintain only documentation that allows the project to be developed, used and maintained, and nothing more. 
A common agile approach is “just barely enough” documentation.
The documentation should focus on what developers can’t easily figure out looking at the code, i.e. the “big picture,” and “why?” rather than “what?”
Work should be completed “at the latest responsible moment."
Guards should be implemented to prevent wasted work from changing requirements.

Agile methods generally use lightweight representations for software requirements, UI designs, software architecture/design, etc.:
- a whiteboard sketch of a UI workflow or domain model
- a 3x5 card with a brief user story described on it
- GitHub Issues to capture feature requests as well as bugs

### Customer Collaboration over Contract Negotiation
If “contract negotiation” really means:  “Give me a specification of what you want, then leave me alone so I can go get it done" there might be a problem.
This can occur between team members, as well as between a team and its client, and tends to make processes less flexible and adaptable to change.
Agile expects requirements, or the understanding of requirements, to change!

Agile methodology encourage constant collaboration within teams, and between developers and clients, to ensure that everyone’s needs and goals are being met. 
Some agile approaches do limit opportunities for requirements to change in order to reduce what is called “requirements churn."

### Responding to Change over Following a Plan
When requirements change, the current plan may no longer be the right plan.
Agile methods adapt to change by reviewing and revising plans iteratively, over short time periods.
Agile methods tend to only have detailed plans for the short- to medium-term.
It doesn’t make sense to devise detailed plans for the long-term, if circumstances are likely to change.
If, or more like when, changes come, any effort spent on detailed long-term plans would have been wasted.

## Scrum
**Scrum** (and variants) is one of the most widely used agile methodologies.
In the initial phase, project envisioning takes place.
How long this takes depends on the scope of the project and may take as much as 2-4 weeks.

During project envisioning, the client and the team define the following at high-level:
- A project vision – what the project is intended to accomplish.
This should be no longer than a few pages at most, and often  times is much shorter.
- A project backlog – a list of key features to be implemented.
In envisioning, the features tend to be high-level and broad
    - Typically expressed as “User Stories”
    - Future efforts will refine the details
- An initial roadmap – a series of releases that include features in the backlog 
    - The first release should be the “Minimal Viable Product”

### Sprints
After project envisioning is completed, development occurs in a series of time-boxed iterations (1 week to 4 weeks) called sprints or iterations.

Sprints start with a planning meeting, time-boxed to 1 hour per week. 
For example,for a 4-week sprint, the planning meeting may be no longer than 4 hours.
The developers choose features from the project backlog to be implemented in the sprint.
Larger features are decomposed into smaller features and details are discussed.
Feature priority is determined by the client and the team, based on relevance to the product roadmap, risk/uncertainty, level of difficulty, etc.
Implementation cost of the features is determined by the developers.
The developers then commit to completing those tasks within the sprint.

At the end of the sprint is a sprint demo, and a retrospective discussion.
This tends to be a short meeting, or is first part of next sprint’s planning meeting where completed work is demonstrated to the client / stakeholders.
Remember, Agile places high priority on working software, and on customer collaboration.
Everyone discusses lessons learned in the sprint, such as what unexpected issues had to be dealt with and what can be done better in future sprints.
A sprint may include releasing/deploying software, or it may not. 
This depends on where the team is with respect to the product roadmap.

## Agile vs. Waterfall
Agile does requirements gathering and design incrementally, mostly just before implementation.
Overall, Agile may be more costly than a well-executed waterfall approach, as long as requirements and design don’t change!

![image tooltip here](/assets/agilevswaterfall.png)

## Defining the Work
In scrum, the project backlog is the specification of what work remains to be done on the project. 
User stories are descriptions of features that can be implemented within a single sprint.
Epics are features that will require multiple sprints to complete.
Epics contain user stories that correspond to the epic.

Bugs are defined as software defects encountered in completed work.
Periodically, backlog grooming occurs.
This is when stories and epics that are no longer relevant to the project are removed (e.g. because a requirement was later found to be unnecessary).

### Requirements as User Stories
User stories are created by describing software features or capabilities from a user’s point of view. 
This can be from the perspective of either regular user s or an administrator.
They are written in “story” form.
Here are some examples: 
- “As a user, I can view my data”
- “As a user, I can edit my data”
- “As an administrator, I can change the access rights of a user”

Here are some examples of user stories for non-functional requirements, though they may not become separate tasks:
- “The system is robust against changes in the database format”
- “The system responds to a database commit in less than 50 ms”

## Other Agile Methodologies
In this section, we will discuss two other Agile-based methodologies: Kanban and MoSCoW.

### Kanban
Japanese for “Board," Kanban is a lightweight method for tracking work on a project.
While it was originally done using a board marked into four columns and Post-It notes, it integrates well with GitHub.
Kanban is typically best for small to medium size projects 

Demo

### MoSCoW
MoSCoW is a lightweight technique for prioritizing work typically done in the sprint planning meeting.
This meeting's focus is on the next software release/sprint.
MoSCoW stands for: 
- Must have
    - Without this, we don’t have a useable release
- Should have
    - The release would be less valuable or compelling without this, but would still be worth releasing
- Could have
    - Nice to have, but not essential
- Won’t have
    - Maybe not ever, but too much for this time

The priority of the sprint is to work on Must Haves, and any Should Haves if there is time remaining in the sprint.

{% include links.md %}


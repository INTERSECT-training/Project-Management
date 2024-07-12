---
title: "Agile Development"
teaching: 5
exercises: 30
---

::::::::::::::::::::::::::::::::::::::: objectives

- Explore the Scrum, Kanban, and MoSCoW frameworks.
- Practice using Scrum and Kanban with a team.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- How is the Agile methodology used in practice?
- What are the features of various Agile frameworks?

::::::::::::::::::::::::::::::::::::::::::::::::::

## Scrum

**Scrum** (and its variants) is one of the most widely used Agile frameworks.
Scrum is a lightweight process that aims to break work into time-boxed iterations.

![](fig/scrum-process.png){alt='The Scrum Process - from Product goal to Sprint review'}

### Project Vision

In the initial phase, project envisioning takes place.
How long this takes depends on the scope of the project and may take as much as 2-4 weeks.

During project envisioning, the client and the team define the following at high-level:

- **A project vision**: what the project is intended to accomplish.
  This should be no longer than a few pages at most (and often  times is much shorter).
- **A project backlog**: a list of key features to be implemented.
  In envisioning, the features tend to be high-level and broad
    - Typically expressed as "User Stories"
    - Future efforts will refine the details
- **An initial roadmap**: a series of releases that include features in the backlog 
    - The first release should be the "Minimal Viable Product"

::::::::::::::::::::::::: callout

#### Requirements as User Stories

User stories are created by describing software features or capabilities from a user's point of view.
This can be from the perspective of either regular user s or an administrator.
They are written in "story" form.
Here are some examples: 

- "As a user, I can view my data"
- "As a user, I can edit my data"
- "As an administrator, I can change the access rights of a user"

Here are some examples of user stories for non-functional requirements, though
they may not become separate tasks:

- "The system is robust against changes in the database format"
- "The system responds to a database commit in less than 50 ms"

:::::::::::::::::::::::::::::::::


After project envisioning is completed, development occurs in a series of
time-boxed iterations (1 week to 4 weeks) called sprints or iterations.

### Sprint Planning

Sprints start with a planning meeting, time-boxed to 1 hour per week. 
For example,for a 4-week sprint, the planning meeting may be no longer than 4 hours.
The developers choose features from the project backlog to be implemented in the sprint.
Larger features are decomposed into smaller features and details are discussed.
Feature priority is determined by the client and the team, based on relevance
to the product roadmap, risk/uncertainty, level of difficulty, etc.
Implementation cost of the features is determined by the developers.
The developers then commit to completing those tasks within the sprint.

:::::::::::::::::::::: callout

## Defining the Work

In Scrum, the project backlog is the specification of what work remains to be done on the project. 
User stories are descriptions of features that can be implemented within a single sprint.
Epics are features that will require multiple sprints to complete.
Epics contain user stories that correspond to the epic.

Bugs are defined as software defects encountered in completed work.
Periodically, backlog grooming occurs.
This is when stories and epics that are no longer relevant to the project are
removed (e.g. because a requirement was later found to be unnecessary).

::::::::::::::::::::::::::::::


### Sprint Work

The Scrum team then completes their work throughout the sprint period.
They meet for daily stand-up meetings (generally 15 minutes) in which they discuss
what they did yesterday, what they plan to do today, and any blockers or issues
that may have occurred.

### Sprint Review

At the end of the sprint is a sprint demo and a retrospective discussion.
This tends to be a short meeting or is first part of next sprint's planning
meeting where completed work is demonstrated to the client / stakeholders.
Remember, Agile places high priority on working software and customer collaboration.

Everyone discusses lessons learned in the sprint, such as what unexpected issues
had to be dealt with and what can be done better in future sprints.
A sprint may include releasing/deploying software, or it may not. 
This depends on where the team is with respect to the product roadmap.

## Agile vs. Waterfall

Agile does requirements gathering and design incrementally, mostly just before implementation.
Overall, Agile may be more costly than a well-executed waterfall approach, as
long as requirements and design don't change!

![](fig/agilevswaterfall.png){alt='A graph of project lifetime vs. effort for agile and waterfall'}

## Other Agile Methodologies

### Kanban

Japanese for "Board," Kanban is a lightweight method for tracking work on a project.
While it was originally done using a board marked into four columns and Post-It notes,
it integrates well with GitHub.
Kanban is typically best for small to medium size projects.

![](fig/kanban.png){alt='Two team members addressing a Kanban board with four columns.'}

### MoSCoW

MoSCoW is a lightweight technique for prioritizing work typically done in the sprint planning meeting.
This meeting's focus is on the next software release/sprint.

MoSCoW stands for: 
- Must have
    - Without this, we don't have a useable release
- Should have
    - The release would be less valuable or compelling without this, but would still be worth releasing
- Could have
    - Nice to have, but not essential
- Won't have
    - Maybe not ever, but too much for this time

The priority of the sprint is to work first on **Must Haves** and then **Should Haves** (if there
is time remaining in the sprint).

::::::::::::::::::::: challenge

## Scrumban

Did you know that you can combine features from both Scrum and Kanban? This is
called Scrumban! In this exercise, you will be using LEGOs :tm: to build a car.

![](fig/car.png){alt='A car icon - created by Freepik on Flaticon.'}

0. Split into 4 groups and grab a set of LEGOs :tm:.
1. (4 min) Product vision: gather requirements, goals, visions, etc., from your customer.
2. (4 min) Project backlog: Create a Kanban board for your project on one of the walls near you
   with the columns "To Do", "In Progress", and "Done". Create your "backlog" by writing the features
   or work to be done on the sticky notes and putting them in the "To Do" column.
3. (2 min) Sprint planning: Decide what work will be completed this sprint. Move those sticky notes
   to the "In Progress" column.
4. (4 min) Sprint work: **BUILD**!
5. (2 min) Sprint review: Show what you have to your customer and get feedback. Make changes to
    your Kanban board as necessary (e.g., move completed work to "Done", adjust work in "To Do" if
    need be).
6. Repeat steps 3-5 two more times!

:::::::::: instructor

Choose two people to act as customers (either two of the attendees or other instructors/TAs).
Assign one of them as "Customer 1" and the other as "Customer 2".

Show them the appropriate images:

1. [Customer 1 - Racecar](fig/customer1-car.jpg)
2. [Customer 2 - RV](fig/customer2-car.jpg)

Assign two groups to each customer. The groups will ask questions together but then
separate to do their individual work. The intent of this is to see how two groups
who gathered the same information may approach work differently.

Instructions to give to the customers:

> Stage 2 - Agile Methodology / Scrumban: The attendees will break up into 4 groups
> - two groups assigned to each customer. You will be given a picture of a car.
> **WITHOUT SHOWING THEM THE PICTURE**, you will describe the requirements for
> the car in the picture to them. Start really basic / high level / vague
> like customers sometimes do. "I want you to build me a car." The attendees
> should then start asking you questions about the house: "How many wheels? How many
> windows and doors?" (etc. etc.) They don't get as much time for this - only 4 minutes.
> Then they go through a Kanban board task writing / backlog creation stage for 4 minutes.
> They will then do a "sprint" / iteration and try to get something created in the next 6 minutes.
> They bring it back to you. You tell them what's right / wrong. They adjust their
> Kanban board / plan their "sprint" (repeat for three total iterations).

:::::::::::::::::::::

:::::::::::::::::::::::::::::::

::::::::::::::::::::::::::::::::::::::: discussion

How was that experience? What did you like? What did you dislike?

::::::::::::::::::::::::::::::::::::::::::::::::::

That's it, folks! You now have knowledge of different project management methods
for software projects.

:::::::::::::::::::::::::::::::::::::::: keypoints

- The Scrum framework focuses on time-boxed iterations of work with consistent customer feedback.
- The Kanban method relies on visual tracking of work.
- The MoSCoW method focuses on labeling work as "Must haves", "Should haves", "Could haves", and "Won't haves."

::::::::::::::::::::::::::::::::::::::::::::::::::

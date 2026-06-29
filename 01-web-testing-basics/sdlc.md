# SDLC Notes

## 1. What is SDLC?

SDLC means Software Development Life Cycle.  
It describes the process of creating software from idea to release and support.

## 2. Main SDLC stages

1. Idea / Business Need
2. Requirements
3. Design
4. Development
5. Testing
6. Release
7. Maintenance

## 3. Where QA participates

QA can participate in requirements review, test planning, test case creation, testing, bug reporting, release checks and post-release monitoring.

## 4. Waterfall

Waterfall is a sequential development model where each stage goes after the previous one.

Example:
Requirements → Design → Development → Testing → Release

Pros:
- Clear structure
- Good documentation

Cons:
- Bugs and requirement problems may be found too late

## 5. Agile

Agile is an iterative approach where the product is developed in small parts.

Pros:
- Faster feedback
- Easier to adapt to changes

Cons:
- Requires good communication and discipline

## 6. Scrum

Scrum is an Agile framework where work is usually organized in sprints.

Typical Scrum events:
- Sprint planning
- Daily meeting
- Review / Demo
- Retrospective

## 7. Kanban

Kanban is a workflow approach where tasks move through columns.

Example:
Backlog → To Do → In Progress → Testing → Done

## 8. Example from QA work

A login feature can go through the SDLC like this:

1. Business asks for user login.
2. Requirements are written.
3. Designer creates login page design.
4. Developer implements login.
5. QA tests valid login, invalid login, empty fields and logout.
6. The feature is released.
7. The team monitors user issues after release.

## My understanding

QA should not be involved only after development, because many problems can be found earlier: in requirements, design, logic and user scenarios. The later a defect is found, the more expensive it can be to fix.

Waterfall is a sequential model where stages go one after another: requirements, design, development, testing and release. It can be useful when requirements are stable and documentation is very important.

Agile is an iterative approach where the product is developed in small parts. It allows the team to get feedback earlier and adapt to changes faster.

Scrum is an Agile framework where work is organized in sprints.

Kanban is a workflow approach where tasks move through statuses such as Backlog, To Do, In Progress, Testing and Done.

A task in Testing means that development is finished and QA is checking whether the feature works according to requirements.

QA can find problems before coding during requirements review.

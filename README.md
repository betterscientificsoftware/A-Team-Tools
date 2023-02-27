# A-Team-Tools
_A collection of resources for lightweight, agile team management by [Michael A. Heroux](https://github.com/maherou)_

This site focuses on simple, lightweight practices to help small software teams (especially research teams) introduce some structure and process to their team management efforts.  We emphasize a handful of practices we have found to be broadly useful.

**Note:** These tools can be useful for large teams, too.  Often large teams are composed of small teams, so these practices can be applied at the small team level and applied similarly to team leadership as a group.  Furthermore, team policy becomes even more important on large teams, as do lightweight communication strategies such as project Kanban boards where the status of activities can be referenced via online tools.

## Team Composition

The practices we propose are especially suited to small teams that have both senior and junior members, where team members, especially junior members, may join and depart a team on a periodic basis.  A common example is a university research team with students, postdocs and long-term faculty. This diagram depicts the basic lifecycle.
![Team Member Lifecycle](https://betterscientificsoftware.github.io/A-Team-Tools/TeamMemberLifecycle.jpg)

- **Senior staff, faculty:**
    - Stable presence, in charge of research questions, experiments.
    - Know the conceptual models well.
    - May spend less time writing code, fuzzy on details.

- **Junior staff, students:**
    - Transient, dual focus (research results, next position).
    - Staged experience: New, experienced, departing.
    - Learning conceptual models.
    - Write most code, know details.

## Team GitHub Organization

An important component of the A-Team-Tools approach is a [GitHub organization](https://help.github.com/en/articles/about-organizations).  Establishing an organization enables coordination of shared repositories.  For educational projects, a GitHub organization can contain private repositories without paying the usual GitHub fee.  Private repositories are useful for managing team activities and keeping unpublished content internally.

## Team Activity Management

A simple issue tracking system such as GitHub issues provides teams with a transparent way to manage team work.  While any repository in your team's organization will typically have its own issue database, we also recommend having an *issues-only* repository.  This repository can be used for managing team member tasks that are not specific to a particular project.  This repository is also were checklists are managed (see below).

A key dashboard for lightweight task management is a Kanban board.

- [Kanban board:](https://github.com/betterscientificsoftware/A-Team-Tools/projects/1) A Kanban board is used to manage tasks by placing them in columns indicating their status.  Of particular importance is the 'In Progress' column which lists the tasks presently being worked on.  The discipline of Kanban is that any person or team should have only so much work going on at once, in order to optimize progress and spur innovation.
 - Regular meetings, updates: Team meetings and project status can be facilitated by regular use and updating of the team Kanban board.  Discussion starts with items in the 'In Progress' column, then the 'Ready' column if a slot opens in 'In Progress'.  Other columns should be scanned as well.  For projects that rely on external contributions, it can be useful to have a 'Blocked' column.  Tasks that were in progress but blocked by an external dependence can be moved to 'Blocked'.

## Team Management Approaches

![Team Management Approaches](https://betterscientificsoftware.github.io/A-Team-Tools/TeamMemberPhaseAndActivityManagementApproach.png) 


- **Checklists:** We find that checklists enable a uniform, repeatable, trackable and ever-improving system for key events in a team member's participation on a project. The following lists (with links to examples) are particularly useful:
    - [Initiation:](NewTeamMemberChecklistTemplate) Bringing on a new team member occurs often enough to keep a comprehensive reference checklist of potential activities.  From the reference list, a custom list can be created as a GitHub issue and assigned to the new team member.
    - [Transition:](LearnJuliaSampleTransitionChecklist) Often during a project a team member (in particular a junior member) will need to learn some new material in order to prepare for their next phase of work.  A transition checklist provides them with the needed concrete steps.  Progress on the checklist is marked by checking off each item as it is completed, showing progress status.
    - [General Exit](TeamMemberExitChecklistTemplate), [Research Student Exit:](ResearchStudentExitChecklistTemplate) A smooth departure of a team member requires planning and sustainability investment throughout project execution.  An exit checklist should be established as soon as possible.

- **Policies:** The value of a team policy cannot be overstated.  The act of creating a policy is a team-building experience, prompting conversation about what team members value most in each other.  The policy establishes behavior expectations and better assures that the products being developed will be high quality and sustainable, reducing the cost of work and the loss of team members who depart.
    - This [sample policy](TeamPoliciesTemplate) illustrates one concrete example of how a team conducts its work.


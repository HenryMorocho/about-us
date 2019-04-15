Welcome to our development culture document.  Here describes how we view the world and behaviors and ideals that make you successful here at Packet

### Our Mission

`Any hardware combination, any OS, any location, in our DC or yours, 100% successful provisions under 60 seconds`

### Our Company Core Values

* We are excited about leading our industry.
* We are driven, ambitious and persistent people.
* We find creative solutions to hard problems.
* We are effective at getting things done the right way.
* We are community minded and do the right thing.

### Our Team Culture

<img src=rsrc/learning.jpg>

Teammates driven by [Autonomy, Mastery and Purpose](https://en.wikipedia.org/wiki/Drive:_The_Surprising_Truth_About_What_Motivates_Us) working together with [psychological safety](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html) is the basis for everything we do.

### Done right through Core Behaviors

Read more about our details [here](behavior_details.md).

* __Care about...__ - This is the most important behavior as all other behaviors depend on this
* __Take small purposeful steps__ - We are doing some great things, but we can only get there one commit at a time.
* __Listen then collaborate__ - Listen to understand, rather than to respond
* __Provide Continuous Feedback & Progress__ - effective communications is really hard, but essential to our work
* __Seek learning and be uncomfortable__ - Don't get complacent, find new ways to do things

If you retain anything from this article, it is the core behaviors from above.  We live by this, we [hire](interview.md) based on this and evaluate [performance](perf.md) based on this.  If you excel at those, you will go far in Packet SWE.

### How and why we do it

Here's a quick summary with more details [here](why_details.md)

What   | Type
:------- | -----
(Near) Atomic Changes | Code
High code coverage  | Code
Refactor constantly | Code
Branches and PRs | Code
Effective documentation | Docs
Aligned Development | Docs
Knowledge Base | Docs
Tight CI/CD | DevOps
Automated System/UI Testing | DevOps
DevOps Culture | DevOps

### Agile 

Packet’s SWE team has adopted an agile model that supports our engineers to be part of multidisciplinary teams that work on specific features or projects as well as being members of a group with centralized competency specific mission.

### Teams

According to the [Agile Manifesto](https://assets.uits.iu.edu/pdf/Agile-Manifesto.pdf): “The best architectures, requirements, and designs emerge from self-organising teams." Packet’s SWE team has adopted a team structure that allows for autonomy. All teams manage their own Kanban board and hold weekly or bi-weekly meetings. The teams are assembled according to having these 5 principles in common:

* Joint tasks to fulfil a compelling mission;
* Clear boundaries in terms of information flow, alignment with other organisational units, resources or decision-making policies;
* Authority to self-manage within these boundaries; and
* Stability over some reasonable period of time.

__Cross-functional__

These are self-contained teams with ownership of complete vertical strips of business functionality, unburdened by dependencies on other teams.The teams are autonomous which means the engineers work towards the common company mission by self-driving the technological strategy on execution. 
These teams have the responsibility for specific projects and or business capability, and they own all of the technology needed to build it.  They will be given visibility and responsibility of the complete project and future phases to manage proactively, and develop the technical experience in this subject matter.

Squad Name    | Main Focus | SLO 
:-------------|----------- | ---  
[X-force](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=60&useStoredSettings=true) | Customer Management and Overall Experience | [API Apdex](https://synthetics.newrelic.com/accounts/45249/monitors/ee8b6b9b-7373-411d-a801-67708572e293/sla?view=daily-sla-report) 
[Suicide Squad](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=83&projectKey=SWE) (SuS) | Compute Products, Provisioning | [Successful Provision % (internal)](https://northstar.packet.net/d/71i_Y0Jmz/vip-provision-metrics?orgId=1), [Customer Data Only (internal)](https://northstar.packet.net/d/RP-qZ82iz/northstar-dashboard-pusher-data-customer-only)
[Network Warriors](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=74&projectKey=SWE) | Network Products & Automation | TBD
[CMR](https://packet.atlassian.net/secure/RapidBoard.jspa?rapidView=66&projectKey=SWE) | Business Processes Automation & Asset Management| TBD

__Guilds__ 

These are groups of people that share a competency or interest. The same people are also part of cross-functional team however while cross-functional teams are vertical, guilds provide a horizontal layer of communication across the larger software engineering team. Guilds promote cohesion, productivity and cooperation. Implementation of the ideas and architectures defined in the guilds are implemented as part of the work that teams are working on to deliver new features. Typically one person is assigned the role of leader.

* API Guild: Creates and maintains API and Microservice standards and architectures 
* UI/UX Guild: Creates and maintains UI/UX design standards and architectures
* Testing Guild: Creates and maintains testing strategy standards and architectures 
* Data Guild: Creates and maintains Persistence, BI, and Analytics standards and architectures

__Squad Composition__

Each squad ideally is made up of these skillsets:

* Tech Team lead
* Infra Architect 
* Backend engineer
* Frontend engineer 
* UX Designer


### Roles/Titles & Responsibilities

VP of Engineering - Job title. 
* Manages the SWE team, directly manages the Engineering Managers.
* Responsible for the entire product development lifecycle.
* Interfaces between CTO and EMs.
* Cultivates a collaborative culture with other partners and customers.
* Works closely with the VP of Production Engineering to ensure a strong DevOps culture.
* Develops and grows the bench strengths at technology and leadership levels through mentoring, coaching, training, and talent retention.

Engineering Manager - Job title. 
* Is the interface between strategy and delivery.
* Manages members of one or more cross-functional teams.
* Works with the leadership team and translates directives to their team as actionable tasks and deliverables. 
* Provides a reasonable structure to allow engineers to focus on their goals. 
* Has up-to-date understanding of the current status and morale of the team. 
* Instills empowerment through coaching and nurturing, creates a culture of emotional safety.
* Oversees development and performance of team members.
* Analyzes resource allocation and recruits new engineers as needed

Team Lead - Role, embedded in cross-functional team.
* A Senior Engineer in technical lead role, does not manage people. 
* Interfaces with the product team and EMs for planning and discussing features/roadmap items. 
* Translates the product into software execution plan. 
* Keeps the pulse on and creates visibility into the day to day and milestone progress and communicates with stakeholders. 

### Prioritization 

The SWE team navigates priority between 3 primary sources of work: Product, Support and Tech. 

__Sources of Work__

*Product - Packet’s Product team uses ProductBoard as the single source of truth:
Corporate roadmap into product launches, SWE priorities with timelines, releases identified.
Customer specific requirements for large deals.
All roadmap items to be linked to Jira Epic.

The handoff of a roadmap item on the ProductBoard to SWE takes place after both teams have agreed on the expectations, scope of work and timelines of the completed product. Timelines are determined collaboratively by the team leads and engineering managers based on scope and resource allocation. The process of prioritization is a joint effort between product and SWE team where priority is weighed against that of Support and Tech work.

*Support - A goalie team with rotating members serve to triage support/ops issues, expand our Knowledge Base and reduce single points of failure. The goalies stay on for 2 weeks and are dedicated full time on business days during office hours. 

They work on the issues that have been prioritized by the Customer Support Liaison (CSL) on the board, prioritization also follows the Kanban workflow. If another task/issue (labeled with ‘goalie’ tag) comes in that is considered more urgent, this will need to be coordinated with the CSL and determined what task will be put on hold while the goalie works the issue or whether an incident should be created instead. More information in the Goalie Handbook.

*Tech - An important source of work is maintenance, tech debt, code refactoring and new architectures (e.g. RBAC system, API gateway). When doing roadmap planning and determining priorities tech work is a critical consideration. Systematically working on resolving platform architecture issues and pushing our tech to the next level of performance, scale and quality of the code we ship. Part of this work is taken into account for when building out new features. Teams need to work in the architecture that has been discussed in the Guild meetings or what the team has decided is best for the project. We also want to empower our teams to make time for working on tech debt by allowing the team to prioritize and work on tech debt. For guidance but not as a requirement a team should allow themselves to take ~20% of their time addressing debt.

### SWE Roadmap 

The 90 day SWE roadmap is made up of epics and can be viewed in Jira. The epics listed reflect the ProductBoard roadmap items as well as epics that are not on the ProductBoard but the source of work is Tech or Support. 

Epic - An epic is a larger body of work. The epic is made up of tasks that together form the release of the code that achieves the goals indicated in the description. The epics are created typically by the Team Lead.

Milestone - A milestone can be a certain functionality or period of a calendar month used as a guide post in which value is delivered to a customer. The milestones in Jira are managed in Releases. To create a new Milestone a new Release is created. When planning and scoping epics for a particular milestone the Jira tickets are associated to it by updating the ‘fix version field’, e.g. 2019-04 (Q2 Milestone 1).

### Working toward Production

At SWE we instill a production-ready mindset through iteration:
* What is the smallest change or improvement that can be pushed that brings value?
* Keep risk of failure at a minimum with a full stack of tests including end-to-end
* Value in production means ‘in use’
* Keep a healthy cadence of continuous deployments 
* Definition of ‘Done’
* When is a task done, when is a product ready for release (GA)? There is much more to that that needs to be considered than ‘I clicked this button and it works’. 

To be able to fully understand what it means for something to be done it must first be understood and agreed upon what the expectation of the completed product is between Product, SWE and other stakeholders. Based on those mutually agreed upon expectations the work is then scoped by the team lead. When scoping the lead must include the scope and ownership for the below aspects.

* UX 
* Backend
* Frontend
* Tests (unit, integration, E2E)
* PE
* Docs (Swagger, KB)
* SDK’s
* Integrations 
* Release Notes

We should leverage our deployment automation to continue building a new feature in small batches and use things like feature flagging to be able to control when the feature is released as GA.

Kanban workflow - The team practices a traditional Kanban workflow. The goal is to work toward completion of incremental, evolutionary changes. The workflow is visualized on our boards in Jira: SWE on-going and Goalie. WIP is limited and new work can only be placed into the input queue once another task has been completed. Board is prioritized right-to-left and then top-to-bottom. Items that are in the top right should be top priority. Once an engineer is free to pick up work they will work on getting things that are in progress or blocked completed before pulling in new work.

Devops - We are continuously building our application by following a tight Continuous 
Integration and Continuous Deployment process. This means that both existing and new code goes through an infinite cycle.

### Tooling, Reporting and Management Review

JIRA: Used by SWE for task tracking, milestone planning and roadmap.
GitHub: Code repositories
Discourse: Used by SWE for knowledge sharing, runbooks, troubleshooting how to’s.
Google Docs: Used by SWE for collaborating asynchronously.
Workplace Groups: Used by SWE for sharing updates, interesting articles, gathering feedback.
Slack: For day to day communication.
Lattice: For 1:1’s, review and personal goals.
Pagerduty: For paging on failures and outages, on-call scheduler.
Blameless: Incident and post mortem tool
Firehydrant: Testing out to potentially replace Blameless
Bugsnag: For reporting UI errors
NewRelic, others for monitoring: Plan in development to consolidate tools
Rollbar
Runscope
Uptime Robot

### Resources

* Our [Interview](interview.md) process    
* Our [Onboarding](onboard.md) process    
* [Leading](leading.md) @ Packet and how we evaluate [performance](perf.md)    
* SWE [Overview & Roadmap](https://trello.com/b/A814D0t8/software-eng-roadmap) (private)    
* [How to create Pyschological Safety](https://hbr.org/2017/08/high-performing-teams-need-psychological-safety-heres-how-to-create-it)

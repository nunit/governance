# NUnit Project Governance

## Overview

The **NUnit Community** is a meritocratic, consensus-based community that aims to provide the best possible software for use in developing and testing applications in the .NET environment. We maintain a number of **Software Projects**, as described below, and sometimes use the term **NUnit Project** to refer to all of those projects in the aggregate.

Anyone with an interest in one of our **Software Projects** can join the community, contribute to the project design and participate in the decision making process. This document describes how that participation takes place and how to set about earning merit within the project community. 

## Software Projects

The NUnit Community maintains an inventory of software projects, with the precise list varying over time. Projects are grouped in a number of categories. See the separate [Projects](./projects.md) document for a full list of projects in each category.

1. Core Projects

   These projects are essential and are actively maintained at the highest priority. They belong to the NUnit Community and we will continue to maintain them and release them on a regular schedule as long as they are useful to our users. If the developers maintaining one of these projects drop out, we will recruit new team members and/or appoint a new project leader.

1. Secondary Projects

   These are projects that are important to us but which are subordinate to the Core Projects in some sense. They do not follow a regular release schedule and are only updated as necessary.

1. Pre-Production Projects

   These are projects that are being developed but are not yet at the stage of a production release. Once released, the project will fall into one of the other categories. This group may include experimental projects as well.

1. Contributed Projects

   These are projects developed by others but hosted and distributed by our community. They are maintained by their individual developers who issue releases as needed. Normally, the project lead is the person who contributed the project. If the lead/contributor should decide to stop maintaining it, the Core Team would have to decide whether to keep maintaining it in some way or to drop the project.

1. Archived Projects

   These are projects we no longer maintain, but which have the last version of the source code available in case someone else wants to take them up again.

## Roles and Responsibilities

### Users

Users are community members who have a need for the project. They are the most important members of the community and without them the project would have no purpose. Anyone can be a user; there are no special requirements.

The project asks its users to participate in the project and community as much as possible. User contributions enable the project team to ensure that they are satisfying the needs of those users. Common user contributions include (but are not limited to):

* evangelising about the project (e.g. a link on a website and word-of-mouth awareness raising)
* informing developers of strengths and weaknesses from a new user perspective
* providing moral support (a ‘thank you’ goes a long way)
* providing financial support (the software is open source, but its developers need to eat)

Users who continue to engage with the project and its community will often become more and more involved. Such users may find themselves becoming contributors, as described in the next section.

### Contributors

Contributors are community members who contribute in concrete ways to the project. Anyone can become a contributor, and contributions can take many forms. There is no expectation of commitment to the project, no specific skill requirements and no selection process.

In addition to their actions as users, contributors may also find themselves doing one or more of the following:

* helping new users (existing users are often the best people to support new users)
* reporting bugs
* identifying requirements
* providing graphics and web design
* assisting with project infrastructure
* writing documentation
* fixing bugs
* adding features
* assisting in code review

Contributors engage with the project through the issue tracker and mailing list, or by writing or editing documentation. They submit changes to the project itself via pull requests, which will be considered for inclusion in the project by existing committers (see next section). The [developer mailing list](https://groups.google.com/forum/#!forum/nunit-developer) and the issue trackers for each project are the best places to ask for help when making that first contribution.

As contributors gain experience and familiarity with the project, their profile within, and commitment to, the community will increase. They may be invited to the Contributors Team on GitHub, giving them a degree of public recognition for their work. At some stage, they may find themselves being nominated as committers on one of our software projects.

### Committers

Committers are community members who have shown that they are committed to the continued development of the project through ongoing engagement with the community. Committership allows contributors to more easily carry on with their project related activities by giving them write access to the one or more project repositories.

This does not mean that a committer is free to do what they want. Each project maintains a review process, which normally requires review of code by one other committer before merging a feature branch to master. Committers are encouraged to participate in the review of pull requests for their projects, approving them for merge or requesting changes as necessary.

Becoming a committer does not imply any obligation on your part. We understand that an individual's ability to give time to the project can vary over time.

Anyone may become a committer; there are no special requirements, other than to have shown a willingness and ability to participate in the project as a team player. Typically, a potential committer will need to show that they have an understanding of the project, its objectives and its strategy. They will also have provided valuable contributions to the project over a period of time.

New committers may be nominated by any existing committer and must be appointed by the individual project lead and approved by the Core Team. Removal of committer authority requires approval of the Core Team but may be instituted by the project lead subject to later approval in case of necessity.

Committers on one software project may request committership on any other project and, if accepted, may be directly appointed by the project lead for the second project, without further approval of the Core Team.

A committer who shows an above-average level of contribution to the project, particularly with respect to its strategic direction and long-term health, may be nominated to become a member of the Core Team.

### Project Leads

The group of committers on a particular software project constitute a Project Team. Each individual project team is led by one of its committers. For smaller projects the lead may be the sole committer but it is recommended to have at least one more in order to provide for future continuity. The project lead is responsible for development and maintenance of the software itself, setting up milestones and release plans, assigning priorities to issues, organizing the work of the project among the committers and making releases.

In fact, the lead makes most day-to-day decisions about the project, normally only referring major questions of direction to the Core Team.

### Core Team

The Core Team is responsible for the NUnit Project and Community as a whole and has additional responsibilities over and above those of a committer or a project lead.

The key responsibility of the Core Team is to define and hold the vision and values of the NUnit Community and ensure that we stick to them. They should periodically review and if necessary update our vision and values documents and should ensure that all committers are aware of them.

The Core Team recruits, selects and appoints project leaders and confirms the appointment of committers on all projects. It also sets standards that are needed in order for our projects to interoperate with one another. This may include such things as coding standards, use of GitHub and inter-project decision making. It should endeavor to avoid micro-managing the software projects and should leave them as much freedom as is reasonable.

The Core Team will conduct a regular review of each software project, annually for core projects and every two years for others. Additional review may be called for if a project is having problems. The review should look at releases, bug fixing and other indications that the project is performing as desired.

The Core Team is called upon to resolve conflicts between software projects or if a consensus cannot be reached on an important decision within a single project. Individual projects may also refer important decisions to the Core Team, particularly those that reflect our community values. Issues of copyright and licensing are always referred to the core team.

The Core Team is responsible for approving, maintaining and amending these governance policies as needed.

Membership in the Core Team is by invitation of the existing members. A nomination will result in discussion and possibly a vote by the existing members. As with all its decisions, the Core Team will attempt to reach a consensus on new members. If a vote is required, the new member must be approved by 2/3 of the membership.

Core Team members remain on the team until they choose to retire or until 2/3 of the members vote to remove them.

The initial composition of the Core Team is
* Charlie Poole
* Rob Prouse
* Chris Maddock
* Terje Sandstrom
* Joseph Musser

### Core Team Chair

The Core Team Chair is a single individual, voted for by the Core Team members. Once someone has been appointed Chair, they remain in that role until they choose to retire, or the Core Team casts a two-thirds majority vote to remove them.

The Chair has no additional authority over other members of the Core Team: the role is that of a coordinator and facilitator. The Chair is also expected to ensure that all governance processes are adhered to, and has the deciding vote in case of ties. 

### Original Contributor

The .NET Foundation, which we are considering joining, defines the role of Original Contributor as the person who seeds the project with the original software base. For the purposes of NUnit - at least NUnit 3 - that individual is identified as Charlie Poole who is the copyright holder for the core NUnit software components until they are assigned or licensed elsewhere.

## Support

All participants in the community are encouraged to provide support for new users within the project management infrastructure. This support is provided as a way of growing the community. Those seeking support should recognise that all support activity within the project is voluntary and is therefore provided as and when time allows. A user requiring guaranteed response times or results should therefore seek to purchase a support contract from a community member. However, for those willing to engage with the project on its own terms and to help support other users, the community support channels are ideal.

The primary support channel for users is the [community mailing list](https://groups.google.com/forum/#!forum/nunit-discuss). Questions involving the actual development of NUnit, as well as extensions, add-ons and third-party runners, should also use the [developer mailing list](https://groups.google.com/forum/#!forum/nunit-developer).

## Contribution Process

Anyone can contribute to the project, regardless of their skills, as there are many ways to contribute. For instance, a contributor might be active on the project mailing list and issue tracker, or might supply patches. The various ways of contributing are described in more detail in the [Contributions](./contributions.md) document.

The [developer mailing list](https://groups.google.com/forum/#!forum/nunit-developer) is the most appropriate place for a contributor to ask for help when making their first contribution. 

## Decision Making Process

Major decisions about the future of the project are made through discussion with all members of the community, from the newest user to the most experienced Core Team member. All non-sensitive project management discussion takes place on the project contributors’ mailing list. Occasionally, sensitive discussion occurs on a private list or through email.

Ultimately, the final decision on major questions is made by the Core Team. The process used to reach a decision is described in the Decisions document.

# NUnit Community Decision Making Process

Major decisions about the future of the project are made through discussion with all members of the community, from the newest user to the most experienced Core Team member. All non-sensitive project management discussion takes place on the project contributors’ mailing list. Occasionally, sensitive discussion occurs on a private list or through email.

## Decisions in Individual Software Projects

Most decisions that need to be made arise out of requests made of the individual software projects. For example, a user may request a particular feature to be added to the console runner by creating a GitHub issue. Such decisions are normally handled within the project by consensus of the committers, using input provided by users.

In order to ensure that the project is not bogged down by endless discussion and continual voting, we usually follow a policy of _lazy consensus_. This allows the majority of decisions to be made without resorting to a formal vote.

In general, as long as nobody explicitly opposes a proposal, it is recognized as having the support of the community. Those who have not stated their opinion explicitly have implicitly agreed to the implementation of the proposal.

It is this process that allows a large group of people to efficiently reach consensus, as someone with no objections to a proposal need not spend time stating their position, and others need not spend time reading such mails.

For lazy consensus to be effective, we try to allow at least 72 hours before assuming that there are no objections to the proposal. This ensures that everyone is given enough time to read, digest and respond, regardless of their location and time commitments.

It may not always be possible to reach a consensus. In that case, the project leader will usually make the final decision. In some cases, however, there may be major issues involved. It may even be a question of the overall direction of the entire NUnit Project. In such a situation, the project leader could either refer the decision to the Core Team or simply make an interim decision and ask the Core Team to review it.

## Core Team Decisions

Because the Core Team generally makes major decisions, affecting multiple projects, _lazy consensus_ is normally not used. For the kind of issues we expect the Core Team to resolve, it's important to hear from each member. The Chair is responsible for getting each member's view and determining whether there is a consensus.

When a consensus cannot be reached, voting is used. Additionally, issues such as those affecting the strategic direction or legal standing of the project always require a vote. The Chair is responsible for determining the necessity of a vote as well as conducting the vote.

Where a vote is used, all votes, including that of the Chair are tallied. With certain exceptions noted below, a simple majority of members must vote for a proposal in order for it to pass. Note that this applies to all current members, not just those who actually vote, and therefore eliminates the need for a quorum. It is the responsibility of the Chair to collect the votes from the members, in case some of them do not respond immediately.

Since the role of the Chair is central in this process, it's important that we have a way to move forward in case of the absence or unavailability of the Chair for a particular decision or for a period of time. If the Chair will be absent for an extended period, they may appoint another Core Team member to serve as temporary Chair. If the Chair is unavailable and no advance provision has been made, a temporary replacement may be selected by the team. In some cases, the team may choose to proceed with one or more decisions without formally naming a replacement, in which case the team as a whole is responsible for following the process described here.

The following actions __require__ a vote of the Core Team.

* Acceptance of a new project.
* Removal or archiving of a project.
* Appointment, removal or replacement of a project lead.
* Removal of a Core Team member. (Two thirds of members must approve)
* Removal of the Core Team Chair. (Two thirds of members must approve)

## Changes to the Governance Documents

The governance documents for the NUnit Community are stored in the [GitHub nunit/governance](https://github.com/nunit/governance) repository. Any changes to those documents must go through a Pull Request and be reviewed by the Core Team. Changes may only be merged by members of the Core Team.

* Spelling, grammar, or formatting changes that do not change the meaning of a document may be merged by one Core Team member other than the member that submitted the Pull Request.
* Any changes to the content or meaning of documents must be voted on by the team and can only be merged when they have been approved by a majority of the Core Team as per the voting rules outlined in Core Team Decisions in this document.
* Pull Requests that require voting should state so.
* The Core Team will self-police and ensure that the rules are followed.

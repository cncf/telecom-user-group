# Contributing

## Table of Contents
* [Issues](#issues)
* [Pull Requests](#prs)
* [Pull Requests Approval Process](#approvals)
* [Idle Pull Requests Policy](#idle)
* [Unresolved Pull Requests Policy](#unresolved)

<a name="issues"></a>
### Issues

- Anyone can create an issue
- TBC can label issues and assign them to other contributors
- All issues must be clearly titled, described, and tagged with the right labels when created.
- WSL may label an issue as "**Returned**" to request further information or to decide not to work on it.

<a name="prs"></a>
### Pull Requests

- Pull Requests (PRs) must only be created when there is an issue present and a decision to create a PR is made.
- PRs should be created by forking the main TUG repository, creating a branch in your local fork and then raising the PR back to the TUG master.
- A PR must reference the issue it is resolving into the description field.
  - using GitHub predefined keyword "**Fixes Issue#**" will automatically close the issue which the PR is resolving when it is merged.
- A PR for an issue can be created by TBC.
- One person only is allowed to edit a given PR unless given permission to other contributor to contribute directly into the PR.
- A PR is recommended to only create/modify content within the scope of a single document.
- A PR should only add/change content related to the issue associated with the PR.
- Comments/sub-Conversations within a PR may only be marked Resolved by:
  - A) The originator of the sub-conversation.
  - B) The relevant WSL or
  - C) An automated timeout of 48hrs when there has been no additional comments after an update is posted to resolve the sub-thread.
  - **The person responding to a sub-conversation shall not mark it as Resolved**.
- Explicitly communicate all changes to existing PRs shall be made through subsequent commits.
  - **Do not modify an existing commit, create separate commits under the same PR**.
  - PRs will be merged using "Squash and Merge" to enforce a linear commit history.

<a name="approvals"></a>
### Pull Requests Approval Process

- Once a PR is created, it needs to get the following approvals before it is merged into master.
  - TBC
  - 2 business days cool off period should be applied before Final approval.
  - Final Approval by TBC (to make sure process is followed)
- Only One approval will be counted per each organization for a given PR.
- The selection of which contributor to approve a PR is made by TBC and should take those factors into consideration:
  - Contributor needs to be actively discussing the PR to be selected for approval.
- PRs will be merged automatically online by TBC once consensus is reached and all approvals are received.
- If WSL is the person who is creating the PR, They need to request an alternate approver, preferably from the co-lead or from the contributors list.

<a name="idle"></a>
### Idle Pull Requests Policy

Pull Requests will be automatically labelled as "**Idle**" when:
- No engagement/activity (content, reviews, conversations) from author, reviewers and workstream contributors on non-merge ready PRs for 15 calendar days.
  - Personal holidays or public holidays will not be counted.
- One or more identified Reviewers (including WSL) are not providing feedback/resolutions or approving the Pull Request for more than 15 calendar days.

Any Pull Requests that are labeled as "Idle" will be discussed during TUG meetings to take a decision on, such as:
- Close the PR and label it as "**Returned**".
- "**Force**" Merging of the PR without having full reviewers approvals due to their inactivity.

<a name="unresolved"></a>
### Unresolved Pull Requests Policy

Pull Requests will be automatically labelled as "**Unresolved**" (by GitHub automation flow or a similar automation mechanism) when no consensus is reached during approval process.

Any Pull Requests that are labeled as "**Unresolved**" will be discussed during TUG meetings to take a decision on it by:
- Finding Common Grounds to come to consensus.
- Follow Governance Procedures to get consensus via voting mechanisms.

# Who can contribute?

- TBC

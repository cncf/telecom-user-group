# Contributing

## Table of Contents
* [Issues](#issues)
* [Pull Requests](#prs)
* [Pull Requests Approval Process](#approvals)
* [Idle Pull Requests Policy](#idle)
* [Unresolved Pull Requests Policy](#unresolved)


<a name="issues"></a>
### Issues

- **Anyone** can create an issue here: [TUG Issues](https://github.com/cncf/telecom-user-group/issues)
- Issues can include bugs to be fixed or topics to be agreed
- The document owners can label issues and assign them to other contributors, or to return it to the originator for more information
- All issues must be clearly titled and described

<!--
Potential addition: list the labels used and what they mean (or, make them obvious).
-->

<a name="prs"></a>
### Pull Requests

- *Anyone* can create a Pull Request (PR) here: [TUG Pull Requests](https://github.com/cncf/telecom-user-group/pulls)
    > Note, using one of the [GitHub keywords](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) will automatically close the issue which the PR is resolving when it is merged
- A PR *should* be modified be just one person unless permission is given to other contributors by the original PR author
- A PR *should* only create/modify content within the scope of a single document
- A PR *should* only add/change content related to the issue associated with the PR
- Comments/Conversations within a PR may only be marked Resolved by:
  - The originator of the sub-conversation, or
  - The overall document or repository owner, or
  - An automated timeout of 48hrs when there has been no additional comments after an update is posted to resolve the sub-thread
  - **The person responding to a sub-conversation shall not mark it as Resolved**
- All changes to existing PRs *shall* be made through subsequent commits
  - **Do not modify an existing commit, create separate commits under the same PR**
  - PRs will be merged using "Squash and Merge" to enforce a linear commit history
- Break up changes into smaller chunks when possible so the PR review and acceptance is likely to occur sooner
- If you think there is unlikely to be consensus on a point then feel free to create an issue to discuss further
- If an existing PR is blocked because a change can't come to consensus open an issue to continue the discussion and see if the other parts of the PR can be accepted.
- If you want to brainstorm / spec out and idea create an issue
- If there is an existing issue when a PR is created then reference the issue

For those familiar with Git:
- Create a local fork
- Commit your changes to your local fork
- When ready, create a PR to merge those change to the `telecom-user-group/master` branch, following the guidelines above

For those new to Git:
- Browse to the document you wish to modify
- Click edit pencil
- Modify the document in the browser
- When ready, use one of the [GitHub keywords](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) to reference the Issue you are resolving in the "Add an optional extended description..." box
- Click "Propose file change"
  - This will create a PR from a local fork back to the `telecom-user-group/master` branch


<a name="approvals"></a>
### Pull Requests Approval Process

- Once a PR is created, it needs to get the following approvals before it is merged into master
  - Active contributors to that document
  - Document / repository owners
  - 2 business days cool off period should be applied before Final approval
  - Final Approval by an Editor (e.g. @ASalkever)
- Only one approval will be counted per each organization for a given PR
- The selection of which contributor to approve a PR is made by the document owner and should take those factors into consideration:
  - Contributor needs to be actively discussing the PR to be selected for approval
- PRs will be merged automatically online by an Editor (e.g. @ASalkever) once consensus is reached and all approvals are receive

<a name="idle"></a>
### Idle Pull Requests Policy

Pull Requests will be automatically labelled as "**Idle**" when:
- No engagement/activity (content, reviews, conversations) from author, reviewers and other contributors on non-merge ready PRs for 7 calendar days
  - Personal holidays or public holidays will not be counted
- One or more identified Reviewers are not providing feedback/resolutions or approving the Pull Request for more than 7 calendar days

Any Pull Requests that are labeled as "Idle" will be discussed during TUG meetings to take a decision on, such as:
- Close the PR and label it as "**Returned**".
- "**Force**" Merging of the PR without having full reviewers approvals due to their inactivity.

<a name="unresolved"></a>
### Unresolved Pull Requests Policy

Pull Requests will be labelled as "**Unresolved**" when no consensus is reached during approval process.

Any Pull Requests that are labeled as "**Unresolved**" will be discussed during TUG meetings to take a decision on it by:
- Finding Common Grounds to come to consensus
- Follow Governance Procedures to get consensus via voting mechanisms

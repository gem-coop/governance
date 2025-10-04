# Maintainer Guidelines

**This guide is for maintainers.** These special people have **write access** to Gem.coop's repositories and help merge the contributions of others. You may find what is written here interesting, but it’s definitely not a beginner’s guide.

## Overview

These documents are meant to serve as guiding principles. As a maintainer, you can make a call to either request changes from a contributor or help them out based on their comfort and previous contributions. Remember, as a team we [Prioritise Maintainers Over Users](Maintainers-Avoiding-Burnout.md) to avoid burnout. If you wish to change or discuss any of the guidelines: open a PR to suggest a change.

## Reviewing PRs

When reviewing a PR, use "approve", "approve with comments", "comment" or "request changes" when submitting based on the following guidelines:

- ✅ Approve: if you feel that the PR looks good as is, you can ✅ approve it as-is.
- ✅ Approve with comments: if you have a few questions or comments to be answered and the PR can be merged after they are addressed, you can ✅ approve with comments.
  - Please trust that other maintainers will not merge the PR until the comments are addressed rather than e.g. making them wait another 24h to get another review.
  - If auto-merge is enabled: don't worry, PRs need to have comments manually resolved before they are automatically merged.
    Please feel free to ✅ approve or ✅ approve with comments even if others have just commented and it will not be merged until the author has resolved the comments.
- 🗣️ Comment: if you need to ask questions before you can provide a ✅ approval but are fine with someone else providing a ✅ approval before you, provide a comment review and ask questions.
- 🚫 Request changes: a last resort.
  - When reviewing non-maintainers' PRs: this means "these changes must be made before this PR should be merged by anyone".
    Other maintainers can dismiss this review when these changes have been made.
  - When reviewing others maintainers' PRs: this is to be avoided whenever possible.
    - Save it for "if this PR is merged before I personally have had a chance to ✅ approve it: it seems very likely to cause user-visible problems".
    - It may be used by the Project Leader for "this functionality is not acceptable in Gem.coop".
      In that case: additional code changes should be held off until there's agreement that the functionality is acceptable.

Relatedly:

- The default option should be to ✅ approve, with or without comments.
- Whenever possible, you should try to use the GitHub "suggestion" feature to edit the code how you would like it to be.
  If you don't have time or can't be bothered: you probably don't have the time to review the PR properly.
- We're a globally distributed team and this helps us move faster.
- The PR review process is primarily a security measure, not a way to get consensus on the perfect code style before merging.
- It is easy to make changes on a PR after approval, make follow-up PRs to address comments or revert PRs before a tag.
- It is (nearly) impossible to merge a PR without approval.
- Using `gh pr checkout <URL>` is a super easy way to check out a PR branch using the GitHub CLI.

### Add comments

It may be enough to refer to an issue ticket, but make sure changes and context are clear enough so that anyone reading them for the first time can make sense of them. You don't want code you wrote to be removed because someone new doesn’t understand why it’s there. Regressions suck.

This also applies to issue and PR bodies. Be as explicit as possible. If a pull request is part of a larger initiative: link to a relevant tracking issue. If there isn't a tracking issue yet: create one to improve communication and get consensus.

### Closing issues/PRs

Maintainers (including the project leader) should not close issues or pull requests (note a merge is not considered a close in this case) opened by other maintainers unless they are stale in which case they can be closed by any maintainer. Any maintainer is encouraged to reopen a closed issue when they wish to do additional work on the issue.

Any maintainer can merge any PR they have carefully reviewed and is passing CI that has been opened by any other maintainer. If you do not wish to have other maintainers merge your PRs: please use the draft pull request status to indicate that until you're ready to merge it yourself.

## Reverting PRs

Any maintainer can revert a PR created by another maintainer after a user submitted issue or CI failure that results. The maintainer who created the original PR should be given no less than an hour to fix the issue themselves or decide to revert the PR themselves if they would rather.

### Give time for other maintainers to review

PRs that are an "enhancement" to existing functionality, i.e. not a fix to an open user issue/discussion, not a version bump, not a security fix, not a fix for CI failure, a usability improvement, a new feature, refactoring etc. should wait 24h Monday to Friday before being merged. For example,

- a new feature PR submitted at 5pm on Thursday should wait until 5pm on Friday before it is merged
- a usability fix PR submitted at 5pm on Friday should wait until 5pm on Monday before it is merged
- a user-reported issue fix PR can be merged immediately after CI is green

If a maintainer is on holiday/vacation/sick during this time and leaves comments after they are back: please treat post-merge PR comments and feedback as you would if left within the time period and follow-up with another PR to address their requests (if agreed).

## Communication

Maintainers have a variety of ways to communicate with each other:

- Gem.coop's public repositories on GitHub
- Gem.coop's group communications between more than two maintainers on private channels (e.g. GitHub/Slack)
- Gem.coop's direct 1:1 messages between two maintainers on private channels (e.g. iMessage/Slack/carrier pigeon)

All communication should ideally occur in public on GitHub. Where this is not possible or appropriate (e.g. a security disclosure, interpersonal issue between two maintainers, urgent breakage that needs to be resolved) this can move to maintainers' private group communication and, if necessary, 1:1 communication. Technical decisions should not happen in 1:1 communications but if they do (or did in the past) they must end up back as something linkable on GitHub. For example, if a technical decision was made a year ago on Slack and another maintainer/contributor/user asks about it on GitHub, that's a good chance to explain it to them and have something that can be linked to in the future.

This makes it easier for other maintainers, contributors and users to follow along with what we're doing (and, more importantly, why we're doing it) and means that decisions have a linkable URL.

All maintainers (and project leader) communication through any medium is bound by [Gem.coop's Code of Conduct](https://github.com/gem-coop/.github/blob/HEAD/CODE_OF_CONDUCT.md). Abusive behaviour towards other maintainers, contributors or users will not be tolerated; the maintainer will be given a warning and if their behaviour continues they will be removed as a maintainer.

Maintainers should feel free to pleasantly disagree with the work and decisions of other maintainers. Healthy, friendly, technical disagreement between maintainers is actively encouraged and should occur in public on the issue tracker to make the project better. Interpersonal issues should be handled privately in Slack, ideally with moderation. If work or decisions are insufficiently documented or explained any maintainer or contributor should feel free to ask for clarification. No maintainer may ever justify a decision with e.g. "because I say so" or "it was I who did X" alone. Off-topic discussions on the issue tracker, [bike-shedding](https://en.wikipedia.org/wiki/Law_of_triviality) and personal attacks are forbidden.

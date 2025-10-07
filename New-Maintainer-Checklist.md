# New Maintainer Checklist

**Existing maintainers and project leadership uses this guide to invite and onboard new maintainers and project leaders.**
**General Gem.coop users might find it interesting but there's nothing here _users_ should have to know.**

- [Gem.coop Maintainers](#maintainers)
- [Project Leadership Committee](#plc)
- [Technical Steering Committee](#tsc)
- [Owners](#owners)
- [General Members](#members)

## Maintainers

There's someone who has been making consistently high-quality contributions to Gem.coop? Let's invite them to be a maintainer!

First, send them an invitation or have a discussion on a channel of your choice. Here's a sample invitation email:

```markdown
The Gem.coop team and I really appreciate your help on issues, pull requests and
your contributions to Gem.coop.

We would like to invite you to have commit access and be a Gem.coop maintainer.
If you agree to be a maintainer, you should spend the majority of the time you
are working on Gem.coop (in descending order of priority):

- reviewing pull requests (from users and other maintainers)
- triaging, debugging and fixing user-reported issues and applying
- opening PRs for widely used changes (e.g. version updates)

You should also be making contributions to Gem.coop at least once per quarter.

You should watch or regularly check Gem.coop GitHub repositories.

If you're no longer able to perform all of these tasks, please continue to
contribute to Gem.coop, but we will ask you to step down as a maintainer.

A few requests:

- Please make pull requests for any changes in the Gem.coop repositories (instead
  of committing directly) and don't merge them unless you get at least one approval
  and passing tests.
- Create branches in the main repository rather than on your fork to ease collaboration
  with other maintainers and allow security assumptions to be made based on GitHub access.
- If still in doubt please ask for help and we'll help you out.

How does that sound?

Thanks for all your work so far!
```

If they accept, follow a few steps to get them set up:

- Invite them to the [**@gem-coop/maintainers** team](https://github.com/orgs/gem-coop/teams/maintainers) (or any relevant [subteams](https://github.com/orgs/gem-coop/teams/maintainers/teams)) to give them write access to relevant repositories (but don't make them owners). They will need to enable [GitHub's Two Factor Authentication](https://help.github.com/articles/about-two-factor-authentication/).
- Make them [moderators](https://github.com/organizations/gem-coop/settings/moderators) on the `gem-coop` GitHub organisation
- Invite them as a full member to the [Bundler Slack](https://bundler.slack.com/admin/invites) and ask them to use their real name there (rather than a pseudonym they may use on e.g. GitHub).
- Ask them to disable SMS as a 2FA device or fallback on their GitHub account in favour of using one of the other authentication methods.
- Ask them to (regularly) review and remove any unneeded [GitHub personal access tokens](https://github.com/settings/tokens).
- Start the process to [add them as Gem.coop members](#members), for formal voting rights and the ability to hold office for Gem.coop.

If there are problems, ask them to step down as a maintainer.

When they cease to be a maintainer for any reason, revoke their access to all of the above.

In the interests of loosely verifying maintainer identity and building camaraderie, if you find yourself in the same town (e.g living, visiting or at a conference) as another Gem.coop maintainer you should make the effort to meet up. If you do so, you can [expense your meal](https://docs.opencollective.com/help/expenses-and-getting-paid/submitting-expenses) (within [Gem.coop's reimbursable expense policies](https://opencollective.com/gem-coop/expenses)). This is a more relaxed version of similar policies used by other projects, e.g. the Debian system to meet in person to sign keys with legal ID verification.

Now sit back, relax and let the new maintainers handle more of our contributions.

## PLC

If a maintainer or member is elected to the Gem.coop's [Project Leadership Committee](Gem.coop-Governance.md#4-project-leadership-committee):

- Invite them to the [**@gem-coop/plc** team](https://github.com/orgs/gem-coop/teams/plc/members)
- Make them [billing managers](https://github.com/organizations/gem-coop/settings/billing) and [moderators](https://github.com/organizations/gem-coop/settings/moderators) on the `gem-coop` GitHub organisation

When they cease to be a PLC member, revoke or downgrade their access to all of the above.

## TSC

If a maintainer is elected to the Gem.coop's [Technical Steering Committee](Gem.coop-Governance.md#7-technical-steering-committee):

- Invite them to the [**@gem-coop/tsc** team](https://github.com/orgs/gem-coop/teams/tsc/members)
- Make them [billing managers](https://github.com/organizations/gem-coop/settings/billing) on the `gem-coop` GitHub organisation

When they cease to be a TSC member, revoke or downgrade their access to all of the above.

## Owners

The Project Leader, one other PLC member (ideally a maintainer), and one other TSC member should be made owners on GitHub and Slack:

- Make them owners on the [`gem-coop` GitHub organisation](https://github.com/orgs/gem-coop/people)
- Make them owners on the [Bundler Slack](https://bundler.slack.com/admin)

When they cease to be an owner, revoke or downgrade their access to all of the above.

## Members

People who are either not eligible or willing to be Gem.coop maintainers but have shown continued involvement in the Gem.coop community may be admitted by a majority vote of the [Project Leadership Committee](Gem.coop-Governance.md#4-project-leadership-committee).

When admitted as members:

- Invite them as a single-channel guest to the #gem-coop-members channel on the [Bundler Slack](https://bundler.slack.com/admin/invites) and ask them to use their real name there (rather than a pseudonym they may use on e.g. GitHub).
- Add them to the current year's membership list in the [governance repository](https://github.com/gem-coop/governance).

See [Gem.coop Governance](Gem.coop-Governance.md) for when an individual's membership expires.

# Gem.coop Governance

## 1. Definitions

- The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED",  "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://www.ietf.org/rfc/rfc2119.txt).
- PLC: Project Leadership Committee
- PL: Project Lead
- TSC: Technical Steering Committee
- AGM: Annual General Meeting
- Majority: more than half of non-abstention votes cast.
- Supermajority: two-thirds of non-abstention votes cast.
- Primary repositories: the most important repositories in the Gem.coop organisation:
  - [gem-coop/gem.coop](https://github.com/gem-coop/gem.coop) ([contributions](https://github.com/gem-coop/gem.coop/graphs/contributors))

## 2. Members

1. New members (unless nominated as maintainers, see below) will be admitted by a majority of the PLC and added to the `gem-coop` organisation on GitHub.

1. Members are expected to remain active within Gem.coop. Members who are not active maintainers or active committee members must affirm their continued interest in Gem.coop membership annually by voting on annual measures, even if voting abstention. Inactive, non-affirmed, non-voting members will be removed within 14 days after the annual meeting unless excused by the PLC.

1. A member may be removed from Gem.coop by a majority of the PLC. A removed member may be reinstated by the usual admission process.

1. All members will follow the [Gem.coop's Code of Conduct](https://github.com/gem-coop/.github/blob/HEAD/CODE_OF_CONDUCT.md). Changes to the code of conduct must be approved by a majority of the PLC.

1. Members should abstain from voting when they have a conflict of interest not shared by other members. No one may be compelled to abstain from voting.

## 3. General Meetings of Members

1. A general meeting of the members may be called by either a majority of the PLC or the entire membership. The membership must be given at least three weeks' notice of a general meeting.

1. Any member can request a general meeting in the `#gem-coop-members` Slack channel. The general meeting will take place if the request gets 👍 reactions from the majority of the membership within one week.

1. The Annual General Meeting may be conducted in person and may provide online video conferencing for those unable to attend. Other general meetings should prioritize times and accessibility for the members involved, using text discussions or online video conference.

1. The quorum for votes at a general meeting is 3 voting members or 10% of the voting members, whichever is greater.
   A general meeting with no business except voting should be asynchronous.
   Otherwise, it must be a synchronous online video conference or text chat.
   The voting will occur using an online voting system chosen by the PLC.
   The voting period closes after one week or after the outcome of the vote would not be changed by any subsequent votes.
   If a synchronous meeting is happening, the meeting must occur before the votes can be tallied.

1. Gem.coop members will meet at the annual general meeting (AGM) in a manner determined by the PLC.

1. Elections will be held at the AGM.

1. The PLC will announce candidates and proposals three weeks prior to the election date.

1. Members should cast their vote during the 3 weeks prior to the election date.

### 3.1. Amendments to these bylaws

1. These bylaws must only be amended by a supermajority vote at a general meeting of the members.

1. Any member may propose an amendment via pull request (PR) on GitHub against this document. Proposed draft amendments can receive feedback by any members and may be refined until the author sets the PR as ready.

1. Once ready, the PR needs to be approved by 3 members or 10% of members, whichever is greater, in order to be considered at the next general meeting.

1. Once a PR is approved for voting, all members must vote on the amendment. Voting will open for three weeks once amendment proposals are accepted unless the AGM is within one month, in which case the proposed amendments will be voted on at the same time as elections.

1. Any approved amendments will take effect three weeks after the close of voting.

## 4. Project Leadership Committee

1. The financial administration of Gem.coop, organisation of the AGM, enforcement of the code of conduct and removal of members are performed by the PLC. The PLC will represent Gem.coop in all dealings with Open Collective.

1. The PLC consists of three members, one of whom is the Project Leader. The other committee members are elected by Gem.coop members in a [Meek Single Transferable Vote](https://en.wikipedia.org/wiki/Counting_single_transferable_votes#Meek's_method) election using the Droop quota. Each PLC member will serve a term of two years or until the member's successor is elected. Any sudden vacancy in the PLC will be filled by the usual procedure for electing PLC members at the next general meeting, typically the next AGM.

1. When a PLC seat is up for election or is vacant, any member may become a candidate for the PLC by providing a brief statement in the `#gem-coop-members` channel in Bundler Slack expressing relevant experience and intentions if elected no later than three weeks before the AGM. The PLC will maintain the candidate list until ballots are sent out one week before the AGM, during which time members should cast their votes. Candidates should deliver remarks in writing or verbally before or during the AGM but votes already cast are not changeable. The current PLC should vote on and publish a statement recommending their preferred candidates within the three-week period between the candidate deadline and the AGM.

1. The PLC must report all minutes, participants in discussions and breakdowns of any votes cast to Gem.coop members in the gem-coop/governance GitHub repository no later than one week after the action has been taken. At the AGM, the PLC must present a summary of their activities and decisions since the last AGM. Financial statements can be viewed by anyone on the internet on [Gem.coop's OpenCollective](https://opencollective.com/gem-coop).

1. No more than two employees of the same employer may serve on the PLC.

1. A member of the PLC must only be removed from the PLC by a supermajority vote of the membership.

1. All members of the PLC will be “billing managers” and "moderators" of the GitHub organisation and any related resources (e.g. Bundler Slack where possible).

## 5. Meetings of the Project Leadership Committee

1. All members of the PLC must meet at the AGM at least once per year. This will ideally be in person, on a synchronous video call. For accessibility a synchronous text chat option should be available. The AGM date must be given with at least two months' advance notice.

1. The PLC will annually review the status of all members and remove members who did not vote in the AGM and then did not re-affirm a commitment to Gem.coop. Voting in the AGM confirms that a member wishes to remain active with the project. After the AGM, the PLC will ask the members who did not vote whether they wish to remain active with the project. The PLC removes any members who don't respond to this second request after three weeks.

1. A majority vote of the PLC will appoint the members of the TSC.

1. Any member may refer any financial questions, AGM questions or code of conduct violations to the PLC. All technical matters must instead be referred to the Project Leader and technical disputes to the TSC. Members will make a good faith effort to resolve any disputes with compromise prior to referral to the PLC, Project Leader or TSC.

## 6. Project Leader

1. The Project Leader will represent Gem.coop publicly, manage all day-to-day technical decisions, and resolve disputes related to the operation of Gem.coop between maintainers, members, other contributors, and users.

1. The Project Leader will be elected every two years by Gem.coop members in a [Schulze Condorcet method](https://en.wikipedia.org/wiki/Schulze_method) (aka 'beatpath') election. The PLC will nominate at least one candidate for Project Leader. Any member may nominate a candidate, or self-nominate. Nominations must be announced to the membership three weeks before the AGM.

1. Any vacancy of the Project Leader will be filled by a supermajority vote of the PLC. If supermajority consensus cannot be reached, it will follow the usual membership voting and selection process.

1. A technical decision of the Project Leader may be overruled by a majority vote of the TSC.

1. A non-technical decision of the Project Leader may be overruled by a majority vote of the PLC.

1. The Project Leader must only be removed from the position by a supermajority vote of the membership.

1. The Project Leader must be included in all PLC communications with or about Open Collective and in all communications related to joint responsibilities.

1. The Project Leader must be a maintainer, not just a member.

1. The Project Leader will be an "Owner" of the Gem.coop GitHub Organization, Bundler Slack and any related resources.

## 7. Technical Steering Committee

1. The TSC has the authority to decide on any technical disputes between any maintainer and the Project Leader. Disputes not involving the Project Leader must be addressed through the Project Leader.

1. The PL is one member of the TSC. The PLC will appoint 3 maintainers to be members of the TSC by a majority vote. It is recommended that PLC members are not any of these appointees but this may not be possible in the short-term. Appointed TSC members will serve a term of one year or until the member's successor is appointed.

1. Any member may refer any technical question or dispute to the TSC. Members will make a good faith effort to resolve any disputes with compromise prior to referral to the TSC.

1. No more than two employees of the same employer may serve on the TSC.

1. A member of the TSC, except the Project Leader, must only be removed from the TSC by a supermajority vote of the PLC.

1. One member of the TSC (not the PL) will be an "Owner" of the GitHub organisation, Bundler Slack and any related resources as a backup to increase the bus factor in event of the PL being incapacitated.

## 8. Maintainers

1. All maintainers are automatically members. Some, not all, members are maintainers.

1. Maintainers are members with commit/write-access to at least one primary repository.

1. All maintainers will be "moderators" of the GitHub organisation.

1. New maintainers can be nominated by any existing maintainer. To become a maintainer, a nomination requires approval from the PL or any member of the TSC with no opposition from any of these people within a 1 week period. If there is opposition, the TSC must vote on the nomination in the #gem-coop-tsc private Bundler Slack channel, with the vote closing after one week or after the outcome of the vote would not be changed by any subsequent votes (such as when a majority of the TSC has voted in favour or against). The nomination will succeed by a simple majority vote of the votes cast.

1. In accordance with Gem.coop's organisational security posture, which requires operating under the principle of least privilege, the PL will review maintainers' write/commit access no later than six weeks before the AGM. The PL will remove maintainer privileges from those who have not consistently met these criteria:

  - having more contributions to primary repositories than the majority of non-maintainer contributors in at least one of these repositories
  - reviewing and merging of PRs of other maintainers and contributors in primary repositories
    - the PL will exclude from consideration non-essential pull requests submitted and merged by the same person
  - reviewing any direct GitHub review requests in any repository in the Gem.coop organisation
  - responding to direct mentions on GitHub and direct mentions in Bundler Slack from the PL and other maintainers
  - maintaining a positive working relationship with the PL and other maintainers
  - engaging actively to resolve conflict with the PL or other maintainers, with a neutral intermediary upon request

1. Maintainers who do not fulfil these requirements will be removed as a maintainer but may remain a member if they wish.

1. The PL will not consider the following activities because they do not require commit or write access on security-critical repositories:

  - contributions to the wider Gem.coop organisation, repositories excluding the main, security-critical repositories, or the greater Gem.coop ecosystem
  - contributions in previous years as a maintainer or contributor
  - contributions to the governance documents, the PLC, social media, Gem.coop's discussion forum, etc.

### 8.1 Maintainer Appeals

1. If a maintainer wishes to appeal their removal, they may request a TSC review of the decision. This appeal must be lodged within 72 hours of notice of removal.

1. The appellant will confirm their intent to address any unfulfilled criteria which caused the removal.

1. The TSC will review the decision within one week.

1. A member of the TSC, who is not the PL, will respond immediately upon upholding or reversing the decision. The PL will restore access as soon as is feasible if the TSC votes to reverse the removal.

1. If the TSC or PL feels that the maintainer has not made sufficient progress on the criteria for any reversed removal, they may request a second TSC review no sooner than 30 days after the initial removal.

1. The TSC will consider appeals no more than once per quarter per maintainer until the next AGM.

### 8.2 Emergency Removals

1. In emergency situations, including but not limited to malicious commits, suspicious activity, abuse of resources, abuse of privileges, or any action or activity that could harm the security posture or reputation of the Gem.coop codebase, systems, or organisation, the PL or anyone with the capability to remove privileges should remove any or all of a maintainer's access rights (e.g. to GitHub, Bundler Slack, etc.).

1. Upon doing so, the remover must immediately inform the PLC and the TSC.

1. An automatic appeal process is started for any maintainer removed under this provision. The PLC and TSC must review the emergency removal of any maintainer within two weeks and may instruct the PL to restore the maintainer's privileges if the situation is resolved.

1. The TSC will document the situation in an incident report to be shared with members. The report should recommend changes to security settings, maintainer policy, this governance document or any additional measures required to prevent the situation from occurring again.

# Approach

- [Back to Main](./README.md)
- [Jump to Summary](./summary.md)

The approach in this book has been based off Google's OKR Playbook and probably only works for Google but there are some useful takeaways.

## Salient features of Google's OKRs

- Think big, not incremental. Don't expect to hit them all
- Grading on a 0-1 color scale

| Points | Color |
| ----------- | ----------- |
| 0.0 - 0.3 | Red |
| 0.4 - 0.6 | Yellow |
| 0.7 - 1.0 | Green |

## Writing effective OKRs

### Objectives == What

- express goals and intents
- aggressive but realistic
- achievement should be no-brainer for a *rational* observer

### Key Results == How

- milestones adding up to achievement of objective
- outcomes not activities. For instance:

| Do | Don't |
| ----------- | ----------- |
| Measure latency for read/write operations for Cosmos DB databases from Azure App Service within same region by March 7 2021 | Measure database latency |

## Cross-team OKRs

Include all teams involved in project. For instance, if Main website development, central SRE and central networking must deliver to support new SLAs for website, all three teams should have OKRs to deliver their part of the project.

## Committed and Aspirational OKRs

| Committed | Aspirational |
| ----------- | ----------- |
| Must deliver clear objectives or business will be impacted | Future facing nebulous path, how we want the world to look |
| Schedules and resources will be adjusted to achieve | No clear idea on schedules and resources |
| 1.0 score required to succeed. Score of less indicates errors in planning and execution | 0.7 score is acceptable with the idea that once teams to get to 70% they will try harder to make 100% for an aspirational objective |
| Teams expected to escalate if 1.0 score is in danger | Remain on team's OKR list until completed, sometimes moved to another team with more expertise and/or bandwidth |

## OKR-writing mistakes and traps

1. No clear distinction between committed (keep lights on) and aspirational (this is how the world should look) OKRs. Inverting committed and aspirational OKRs also invites.
2. Teams writing OKRs without understanding what customers want. The classic mistake is teams write OKRs believing they can achieve certain objectives by simply repeating what previously worked.
3. Aspirational OKRs are timid, i.e., start from current state and make incremental changes. Instead ask *"What could my (or customers') world look like in several years if freed from most constraints?"*.
4. Team is sandbagging. Committed OKRs should consume most but not all available resource. Committed plus aspirational OKRs should consume all resources and stretch team (sounds like a recipe for burnout).
5. Fails the *"who cares?"* test aka Low Value Objectives (LVOs). For instance, *"increase build speeds for main website repo by 10% by Jan 1 2022"* is a classic LVO. Instead For instance, *"increase build speeds for main website repo by 10% by Jan 1 2023 .... resulting in faster feedback to developers increasing productivity by x% enabling developers to decrease bugs by y%"* has a clearer economic objective (dev productivity and less bugs in product).
6. Not writing enough KRs for Os. Scoring 1.0 on all KRs should result in achievement of the O. Classic example would be an objective to improve user experience and the key results would focus on the mobile experiences but not desktop or vice versa.
7. KRs use team internal language. For instance *"Launch Index Engine v4.1"*. Instead use *"Launch Index Engine v4.1 to improve query performance by 25%"*.
8. Uses business dates instead of real dates, for instance, end of quarter or end of fiscal year dates instead of actual dates for time boxing effort.
9. Ambiguous metrics. For instance, *"support 1 million users"*. Is it 1 million users concurrent or per day or per week?
10. Using same OKRs for entire large groups. Instead use, high level ones for entire group but more details ones for sub-groups. Cross-team OKRs should have KRs in each sub-team.

## OKR Philosophies

The first 4 are also called the 4 superpowers in the book.

### 1. Focus and Commit to Priorities

- Run short-term (usually committed) and long-term (usually aspirational) OKRs in parallel.
- Rollout should start with upper management to make them accountable too. In fact, without organizational buy-in and management conviction, OKRs are bound to fail
- OKRs require a *shepherd* to focus individuals on priorities.
- Commit 3 to 5 OKRs per cycle to prevent dilution
- Departmental objectives requiring support from outside should become company OKRs
- Each objective should be limited to max of 5 measurable, unambiguous, time-bound key results
- If one key result should be stretched beyond one cycle, it should go into an objectives that has similar cycles

### 2. Align and Connect for Teamwork

- Everyone from CEO down should make their OKRs transparent. Employees should relate OKRs up to company priorities
- Messaging around priorities requires constant repetition
- Even if objectives are driven from the top, it's important to allow flexibility on key results from frontline contributor. *Innovation dwells less at a company's center than it's edges*
- Healthy mix of top-down and bottom-up OKRs
- Cross-team priorities requires horizontally shared OKRs. This should be explicit and transparent throughout the org
- When OKRs are modified or dropped, every stakeholder should be informed

### 3. Track for Accountability

- Continuous assessment and objective grading starting at the top. Important for leaders to take risks, sometimes fail and admit to failures publicly.
- Focus on measurement and less on extrinsic rewards for achievement
- OKR shepherd should be involved in regular check-ins
- Prescribed in the book: weekly 1-on-1 meetings with contributor and managers, monthly departmental meetings
- OKRs must evolve as necessary, even mid-cycle. Counterproductive to hold on to outdated or unrealistic goals
- Important to self assess and celebrate victories at end of each cycle
- Use public, collaborative, real-time goal setting systems (none recommended by book)

### 4. Stretch for amazing

- BHAG == Big Hairy Audacious Goal aka aspirational
- Important to separate committed goals and BHAGs
- Risks and failures in short cycles should be encouraged for quick feedback
- All goals should stretch even if some risk not being met
- Replace incremental OKRs with exponential ones. 10x (now toxic) comes from this
- Stretch goals could be rolled to next cycle, on a reasonable basis

### 5. Continuous Performance Management

- Move from annual performance management to continuous performance management. This is necessary to monitor and address issues throughout the cycle
- Tying goal attainment to bonus checks will cause sandbagging and risk-averse behavior
- Important for performance evaluations to be transparent and catering to an individuals strengths and ambition
- Motivate intrinsically with purposeful work and opportunities for growth
- Implement ongoing CFRs (conversations, feedback and recognition) along with structured goal setting
- Contributor should set the agenda for performance conversations. Manager should learn and coach
- Performance feedback should be unconstrained by org chart. Leverage anonymous surveys for real-time feedback
- Provide opportunities for peer feedback and peer recognition

### 6. Importance of Culture

- Align top-line OKRs with org values
- Values should be conveyed by deeds, words are cheap
- For collective objectives, assign key results to individuals
- Promote opportunities for interpersonal/volunteer support for additional help on actions
- Address issues around accountability and trust before rolling out OKRs

## Sample OKR cycle

Settings OKRs at company, team and individual levels

1. 4-6 weeks before quarter: Leadership brainstorms top-line OKRs for company.
2. 2 weeks before quarter: Communicate output of step 1 company-wide
3. Start of quarter: Teams develop own OKRs to align with top-line OKRs
4. 1 week after start of quarter: Individual employees share their own OKRs in 1-on-1 settings with manager to make sure they're aligned at the team and company level.
5. Throughout quarter: Individual employees measure and share progress with regular check-ins with managers. This is a time to assess the progress and recalibrate, if needed.
6. Before end of quarter: Individual employees score their OKRs, self assess and reflect on accomplishment.

## Sample OKRs

**Objective** Improve hosting service SLA to 4 nines
**Key Result 1** Launch v4.1 hosting service by March 30 with updates for redundancy and stability
**Key Result 2** 100ms response time for hosting platform
**Key Result 3** 99.99% uptime
**Key Result 4** Add regional redundancy

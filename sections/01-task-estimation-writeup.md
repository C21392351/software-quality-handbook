# Task Estimation in Scrum

## What Is It?

Task estimation is the process of predicting how much effort or time a piece of work will take before you start it. In Scrum, estimation happens during Sprint Planning where the team collectively sizes user stories using story points, t-shirt sizes, or hours.

The goal is not to produce a perfect prediction but to give the team and stakeholders a shared understanding of the work ahead so sprints can be planned realistically.

## Why It Matters For Our Team

Our team has struggled with unpredictable delivery. Work takes longer than expected, sprints overrun, and the pressure to catch up leads to shortcuts and defects. Poor estimation is one of the root causes. If we size work more honestly and account for all the things that can go wrong, our delivery becomes more predictable and less stressful.

---

## Research Summary

We reviewed 5 sources to inform this section. All five were practical and experience-based rather than purely theoretical.

### Source 1 — How I Estimate Work as a Staff Software Engineer
**Author:** Sean Goedecke | **URL:** [https://www.seangoedecke.com/how-i-estimate-work/](https://www.seangoedecke.com/how-i-estimate-work/)

- Unknown work always dominates software projects — you cannot estimate what you have not yet discovered
- Skilled engineers estimate around uncertainty, not around certainty
- The job is to map risks and return options with tradeoffs, not produce a single confident number
- Estimates are often used as planning and negotiation tools by management, not as engineering truths

### Source 2 — We Engineers Suck at Task Estimation
**Author:** Arpit Bhayani | **URL:** [https://www.linkedin.com/pulse/we-engineers-suck-task-estimation-arpit-bhayani-cq7gc](https://www.linkedin.com/pulse/we-engineers-suck-task-estimation-arpit-bhayani-cq7gc)

- Personal story: estimated 1 week, took 4 weeks
- Engineers forget to include testing, deployment, code review, meetings, sick days, dependency delays
- We overestimate our own speed and underestimate complexity consistently
- Unknown unknowns, especially with new technology, destroy timelines

### Source 3 — Rules of Thumb for Software Development Estimations
**Author:** Vadim Kravcenko (CTO) | **URL:** [https://vadimkravcenko.com/shorts/project-estimates/](https://vadimkravcenko.com/shorts/project-estimates/)

- Initial estimates are almost always optimistic — multiply them
- Use ranges (best case / worst case) rather than single numbers
- Communication overhead causes as many delays as technical problems
- Real teams need to account for coordination time, not just coding time

### Source 4 — Story Point Estimation Does Not Work. Here is Why.
**URL:** [https://uplevelteam.com/blog/story-point-estimation](https://uplevelteam.com/blog/story-point-estimation)

- Story points mean different things across different teams — inconsistent by nature
- New team members have to relearn the scale when they join
- Personal bias heavily influences estimates, especially for familiar-looking work
- Velocity can be gamed to look productive without delivering more

### Source 5 — Story Point Disaster (Reddit — Real Team Experience)
**URL:** [https://www.reddit.com/r/agile/comments/1gz46f7/story_point_disaster_agile_newbies_at_work_again/](https://www.reddit.com/r/agile/comments/1gz46f7/story_point_disaster_agile_newbies_at_work_again/)

- Real engineers sharing what went wrong when their team first used story points
- Half the team tried to convert hours into story points — completely defeats the purpose
- Relative sizing only works once the team has a shared reference story to compare against
- Takes several sprints before estimates stabilise — early chaos is normal

---

## Common Themes Across All 5 Sources

| Theme | What It Means For Our Team |
|---|---|
| Engineers consistently underestimate | Always add buffer — never take a first estimate at face value |
| Unknowns dominate software work | Break tasks down until hidden risks become visible |
| Non-coding work is always forgotten | Include testing, review, deployment and meetings in every estimate |
| Story points are relative, not absolute | New team members need onboarding on our sizing scale |
| Estimates are not commitments | Treat them as forecasts — revisit if scope or context changes |
| The discussion matters more than the number | Planning Poker conversation is where the real value comes from |

---

## Good Practices to Follow

- **Estimate as a team, never alone** — one person estimating creates blind spots. Discussion surfaces hidden complexity that no single person would catch
- **Use relative sizing** — compare tasks to each other rather than estimating in clock hours. Story points work better because they avoid false precision
- **Break tasks down** — if a story feels bigger than a few days of work, split it. Large tasks hide the most unknowns
- **Run Planning Poker** — structured simultaneous voting prevents anchoring (where the first number said anchors everyone else)
- **Give ranges, not single numbers** — instead of saying "3 days", say "2 days if we reuse the existing flow, 5 days if we have to touch the auth service"
- **Include all the work, not just the coding** — testing, code review, deployment, bug fixes, meetings, and integration all take time
- **Use past velocity** — base estimates on how long similar tasks actually took your team, not on how long you hope they will take
- **Revisit estimates openly** — if scope changes mid-sprint, re-estimate in the open rather than silently overrunning

---

## Bad Practices to Avoid

- **One person deciding all estimates** — the HiPPO effect (highest paid person's opinion) kills honest estimation
- **Estimating only the coding** — forgetting testing, review, deployment and communication is the single biggest cause of overruns
- **Treating estimates as deadlines** — an estimate is a forecast, not a promise. Pressure to hit estimates leads to cutting corners
- **Never reviewing accuracy** — if you never look back at how wrong your estimates were, you never improve
- **Padding estimates silently** — if you think a task is risky, say so clearly rather than secretly doubling the number
- **Skipping estimation entirely** — "we'll just see how long it takes" always results in chaos when sprint planning comes around
- **Estimating in hours for complex work** — hours create false precision and encourage padding. Relative points are more honest for uncertain work
- **Letting one sprint's velocity define everything** — velocity fluctuates. Use a rolling average, not a single sprint

---

## Estimation Flow

```
Sprint Planning Starts
        |
        v
Product Owner presents the user story
        |
        v
Team asks clarifying questions
        |
        v
Each member privately picks a story point value
        |
        v
All reveal simultaneously (Planning Poker)
        |
        v
     Consensus?
    /           \
  Yes            No
   |              |
   v              v
Log estimate   Discuss outliers
               (highest + lowest explain their reasoning)
                      |
                      v
               Re-vote until consensus
                      |
                      v
               Log agreed estimate
```

---

## Further Reading

1. [How I Estimate Work as a Staff Software Engineer — Sean Goedecke](https://www.seangoedecke.com/how-i-estimate-work/)
2. [We Engineers Suck at Task Estimation — Arpit Bhayani](https://www.linkedin.com/pulse/we-engineers-suck-task-estimation-arpit-bhayani-cq7gc)
3. [Rules of Thumb for Software Development Estimations — Vadim Kravcenko](https://vadimkravcenko.com/shorts/project-estimates/)
4. [Story Point Estimation Does Not Work — Uplevel](https://uplevelteam.com/blog/story-point-estimation)
5. [Story Point Disaster — Reddit](https://www.reddit.com/r/agile/comments/1gz46f7/story_point_disaster_agile_newbies_at_work_again/)

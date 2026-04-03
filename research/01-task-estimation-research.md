# Task Estimation in Scrum — Research Notes

This file contains research sources gathered to inform the Task Estimation section of the handbook.

---

## Source 1 — How I Estimate Work as a Staff Software Engineer

**URL:** https://www.seangoedecke.com/how-i-estimate-work/
**Published:** January 2026
**Author:** Sean Goedecke (Staff Software Engineer)

**Key points from reading:**
- A staff engineer's honest personal account of how estimation really works in large codebases
- Unknown work always dominates software projects, you cannot estimate what you don't know yet
- Skilled engineers estimate around uncertainty, not around certainty
- The job is not to produce a precise duration but to map risks and return options with tradeoffs
- Estimates are often used more as planning and negotiation tools for management than as engineering truths
- Spending more time worrying about unknowns than knowns leads to better estimates

**Why this is relevant to our team:**
We often underestimate tasks because we only think about the code we know we need
to write, not the unknown problems we will hit along the way. This article puts a
name to that problem and gives a practical mindset shift for how we should approach
estimation as a team.

---

## Source 2 — We Engineers Suck at Task Estimation

**URL:** https://www.linkedin.com/pulse/we-engineers-suck-task-estimation-arpit-bhayani-cq7gc
**Published:** May 2025
**Author:** Arpit Bhayani (Software Engineer)

**Key points from reading:**
- Engineer shares a personal story: estimated 1 week for a task, it took 4 weeks
- We consistently forget to include testing, deployment, code reviews, meetings, sick days, and dependency delays
- Engineers overestimate their own speed and underestimate complexity every time
- Unknown unknowns, especially with new technologies, destroy estimates completely
- The comments section confirms this is a universal experience across the entire industry

**Why this is relevant to our team:**
This is exactly what is happening on our team right now. Tasks take longer than
expected because we only estimate the coding part and forget everything that
surrounds it. Testing, review cycles, and integration issues are never included
in our initial estimates.

---
## Source 3 — Rules of Thumb for Software Development Estimations

**URL:** https://vadimkravcenko.com/shorts/project-estimates/  
**Published:** July 2023  
**Author:** Vadim Kravcenko (CTO)

**Key points from reading:**
- The article is written from the perspective of a CTO with hands-on experience managing software teams
- Initial estimates are usually optimistic and should be treated with caution
- It is more realistic to give estimate ranges, such as best-case and worst-case outcomes, rather than a single fixed number
- Communication overhead and coordination delays can be just as disruptive as technical challenges
- Estimation improves when teams account for both delivery work and the time needed to align with others

**Why this is relevant to our team:**
This source gives practical advice from someone who has managed real software teams.
The point about using ranges instead of fixed numbers is especially useful for us,
because our current estimates often sound too certain even when there is obvious
uncertainty in the work.

---

## Source 4 — Story Point Estimation Doesn't Work. Here's Why.

**URL:** https://uplevelteam.com/blog/story-point-estimation  
**Published:** August 2024  

**Key points from reading:**
- Story points can become inconsistent because different teams interpret them in different ways
- New team members often need time to learn how a specific team applies its estimation scale
- Personal bias can heavily influence estimates, especially when developers feel familiar with the type of work
- Velocity can be misleading if teams focus on appearing productive rather than measuring meaningful delivery
- Story point systems are only useful when the team has a shared understanding of what each size represents

**Why this is relevant to our team:**
We are still a new team and have not fully developed a shared understanding of story
points yet. This helps explain why our estimates sometimes feel inconsistent or
random, and why newer team members may not interpret sizing in the same way.

---

## Source 5 — Story Point Disaster (Reddit — Real Team Experience)

**URL:** https://www.reddit.com/r/agile/comments/1gz46f7/story_point_disaster_agile_newbies_at_work_again/  
**Published:** November 2024  

**Key points from reading:**
- The discussion captures real engineers describing problems their teams faced when first using story points
- Some team members tried to convert hours directly into story points, which defeats the purpose of relative estimation
- Relative sizing only becomes effective once a team has a shared reference point for comparison
- Estimation usually takes a few sprints to stabilise, especially for newer teams
- Early confusion with story points is common and does not necessarily mean the method has failed

**Why this is relevant to our team:**
This is highly relatable to our current situation. We are still learning how to use
story points consistently, and this source shows that early confusion is normal.
It also gives reassurance that teams usually improve after a few sprints once they
build a shared reference for sizing work.

---

## Common Themes Across All 5 Sources

| Theme | What it means for us |
|---|---|
| Engineers often underestimate work | Add buffer and avoid treating first estimates as final |
| Unknowns dominate software work | Break tasks down until risks and uncertainties are more visible |
| Non-coding work is often forgotten | Include testing, review, deployment, and communication time in every estimate |
| Story points are relative, not absolute | Make sure the team shares the same understanding of the sizing scale |
| Estimates are not commitments | Treat estimates as forecasts that can change when scope or context changes |
| Discussion matters more than the number | The Planning Poker conversation is often more valuable than the final score itself |
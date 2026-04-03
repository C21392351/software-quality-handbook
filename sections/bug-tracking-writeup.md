## Bug Tracking

## What is Bug Tracking?

Bug tracking is a process in which problems in a system are identified, reported prioritised and fixed. 

Bug tracking is very important in a fast-moving team because it ensures quality in a system and prevents problems from entering production. It is also important in a fast-moving team because it ensures better communication among members of the team. 

## Best Practices for Bug Tracking 
- Provide clear and detailed descriptions of each bug encountered including a step-by-step reproduction of the bug, expected behaviours and actual behaviours
- Provide context information like logs, screenshots, etc.
- Develop a structured triage system
- Prioritise the bugs based on severity rather than the order in which they were reported
- Assign each bug to the most appropriate developer
- Keep the bug list up-to-date by regularly reviewing it
- Develop a system of testing and Continuous Integration 
- Treat bug tracking as an active process to resolve issues

## Common Bad Practices to Avoid 
- Incomplete and vague bug reports
- Duplicate bug reports
- Low priority bugs being fixed before critical bugs
- Letting the backlogs of bugs get too large
- Minimal communication and collaboration between teams
- Using bug tracking tools to only to log the issues and not resolve them
- Incorrectly assigning bugs based on the developer experience
- Ignoring important information such as the logs or environment details

## Bug Tracking Checklist 
- Is the bug report clear and easy to read?
- is the expected behaviour and actual behaviour well defined?
- Is sufficient context provided such as logs and screenshots?
- Has the bug been prioritised appropriately based on its severity and impact
- Has the bug been assigned to the right developer?
- Has the bug been properly tested?

## Why Bug Tracking Matters for Our Team

A small and fast-moving team needs an effective bug tracking system to ensure the quality of the product and avoid problems in production.
Without a standard process in bug tracking the bug could either be misunderstood, misinterpreted or even left unsolved. 

# Further Reading

## Source 1 - Proper Bug Reporting

**URL:** https://developerexperience.io/articles/proper-bug-reporting **Published:** November 11th, 2019 **Author:** Developer Experience  

**Key points from reading:**
- Bug reports are not just documentation of problems, but also serve as a way of communication between testers and programmers
-  Poorly written bug reports cause project delays as programmers waste time trying to understand the problem
-  A good bug report should include reproduction steps, expected behaviour and actual behaviour 
-  Lack of information in the bug reports results in delays and frustrations
-  The purpose of a well written bug report is to make it easy as possible for the developers to understand and fix the problem
-  Vague bug reports are one of the most common reasons for wasting engineering time

**Why this is relevant to our team:** This is especially true for our team, as ambiguous bug reports may result in confusion and time wastage, especially if different team members are working on different aspects of the system. This article emphasises that bug tracking does not only involve reporting bugs but also effectively communicating them. Improving the quality of our bug reports will save us time and enable us to solve problems faster.

## Source 2 - Sleep more; Triage Faster with Sentry 

**URL:** https://blog.sentry.io/sleep-more-triage-faster-with-sentry/ **Published:** May 2nd, 2023 **Author:** Dhrumil Parekh  

**Key points from reading:**
- Bug triage is important to guarantee that bugs are looked at and addressed speedily 
- Ineffective bug triage procedures can cause bugs to be left unfixed or to be addressed by the wrong people 
- Without context, debugging is significantly slower
- Engineers spend considerable time debugging issues that could have been clearer right at the beginning
- The right team or person needs to be assigned bugs to avoid delays
- Good bug tracking tools should enable the team to take action on bugs speedily and not just store them
- Without triage, bug backlogs can easily get out of hand, making it more difficult to pinpoint and resolve the most critical problems

**Why this is relevant to our team:** For a fast-moving team such as ours, it is possible for bugs to pile up or be assigned inappropriately if there is no triage process in place. This article emphasises the amount of time lost due to bugs that are not provided with enough context or are not triaged well. It would be helpful to implement a triage process for our bugs, as well as make sure they are provided with enough technical detail. 

## Source 3 - Bug Triage: A Guide to Efficient Bug Management 

**URL:** https://www.atlassian.com/agile/software-development/bug-triage **Published:** Not specified **Author:** Atlassian

**Key points from reading (prioritisation focused):**
- Bug triage assists teams in prioritising bugs so that the most important bugs are fixed before less important ones
- It is important to understand that not all bugs are of equal value and so there are both severity and priority considerations
- If bugs are not properly prioritised, a team may find itself busy fixing less important bugs while more important ones are left unattended
- A well-defined set of criteria for bug prioritisation helps in ensuring that there is no inconsistency in decision-making within a team
- Regular bug triage helps in ensuring that high-priority bugs are not missed in the long list of bugs
- Prioritisation helps a team to make optimal use of time and resources.

**Why this is relevant to our team:** In our team, sometimes it is possible to solve bugs based on 'first come, first served' principle, rather than based on their importance. This article showcases the need for prioritisation of tasks in such teams to solve the most critical ones first. If we follow the criteria for prioritisation, we can make better use of our development time. 

## Source 4 - Issue Tracking Systems: Good Servant, Bad Master 

**URL:** https://www.red-gate.com/simple-talk/blogs/issue-tracking-systems-good-servant-bad-master/ **Published:** November 19th, 2015 **Author:** Tony Davis 

**Key points from reading (focused on common pitfalls):**
- Bug tracking systems may become useless if they are not maintained
- Bug Trackers may become a 'graveyard' where bugs are recorded but never fixed
- Recording bugs does not improve software quality unless there is a process to fix them
- Too many bugs make it harder to see them and prioritise them
- More emphasis may be placed on tracking bugs rather than solving them

**Why this is relevant to our team:** As a team, we should not let bugs accumulate and not fix them. This will soon make the bug tracking system difficult to manage. Bug tracking should not be a passive activity, but rather a dynamic activity that focuses on solving bugs. It should always be a small and manageable list. 

## Source 5 - Continuous Integration and Bug Tracking: Best Practices for Success 

**URL:** https://www.kualitee.com/blog/bug-management/continuous-integration-and-bug-tracking-best-practices-for-success/ **Published:** December 7th, 2023 **Author:** Kualitee

**Key points from reading (focused on prevention):**
- Bug tracking in itself is not enough; there should also be a focus on preventing bugs
- Continuous Integration (CI) can help in identifying bugs at earlier stages of development
- Automated testing can help in reducing the number of bugs reaching production
- It is easier to fix bugs that are identified at earlier stages of development
- Integrating testing and bug tracking help in improving the quality of the software.

**Why this is relevant to our team:** Our team should not only focus on tracking the bugs, but we should also work towards preventing the bugs from occurring in the first place. This can be done by implementing automated test and Continuous Integration. This will help us improve our development efficiency and reduce the time spent on debugging. 

## Common Themes Across All 5 Sources

| Theme | What it means for us |
|---|---|
| Bug Tracking is communication | Write clear, detailed bug reports to ensure that issues can be understood and reproduced easily | 
| Poor bug reports will waste time | Always include steps, expected behaviour and actual behaviour in bug report | 
| Triage is a must | Review, prioritise and assign bugs through a structured triage process |
| All bugs are not created equal | Prioritise bugs based on severity, not on when they were filed |
| Managing backlogs is a must | Regularly review and reduce bugs to keep them at a minimum | 
| Tracking is not fixing | Focus on fixing bugs, not just tracking them | 
| Too many bugs will reduce visibility | Keep a small number of bugs to ensure that critical issues can be seen | 
| Assign bugs correctly | Assign bugs to developers based on their expertise | 
| Context is key to speeding up bug fixes | Include logs, environment and other technical details to help debug issues |
| Prevention is better than cure | Use testing and continuous integration to catch bugs early |

Bug tracking also improves communication and collaboration within the teams by ensuring the bugs are described clearly and understood by the whole team which allows for them to focus on the most critical problems first. 

As a team we can reduce defects, improve development efficiency and maintain a more reliable system by following a structured bug tracking process. 

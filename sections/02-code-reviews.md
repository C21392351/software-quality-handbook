## Code Reviews

## What are Code Reviews?

Code reviews are a process where developers examine each other's code before it is merged into the main branch. The goal is to improve quality, detect defects early, and ensure consistency across the codebase.

In a fast-moving team, code reviews play a crucial role in maintaining high standards and preventing issues from reaching production.

-----

## Best Practices for Code Reviews

- Keep pull requests small and focused to make them easier to review
- Review code regularly to avoid large backlogs and delays
- Provide clear, constructive, and respectful feedback
- Ensure coding standards and conventions are followed consistently
- Include tests and verify that they cover key functionality
- Use descriptive pull request titles and explanations to give context
- Treat code reviews as a collaborative process, not criticism

-----

## Common Bad Practices to Avoid

- Submitting large pull requests that are difficult to review
- Delaying reviews, causing bottlenecks in development
- Giving vague or unclear feedback
- Criticising the developer instead of focusing on the code
- Approving code without properly reviewing it
- Ignoring test coverage or missing edge cases
- Lack of consistency in coding standards
- Allowing review backlogs to build up over time

-----

## Code Review Checklist

- Is the code readable and easy to understand?
-  Does the code follow naming conventions and standards?
- Are there any duplicated or unnecessary code blocks?
- Is error handling implemented correctly?
- Are tests included and do they cover key scenarios?
- Does the code introduce any potential bugs or edge cases?
- Is the pull request clearly described and easy to follow?

-----

## Why Code Reviews Matter for Our Team

- For a small and fast-moving team, code reviews are essential to maintaining qualty and consistency. 
- Without a proper review process, defects can easily reach production, and inconsistencies in coding style can make the system harder to maintain.
- Code reviews also improve collaboration by allowing team members to learn from each other's work and share knowledge across different parts of the system. 
- By following a structured review process, we can reduce defects, improve readability, and ensure a more maintainable codebase.

-----

## Example: Good vs Bad Pull Request

![Bad VS Good PR](images/good-vs-bad-pr.png)

### Bad Pull Request
- No clear desciption
- No context provided
- Difficult for reviewers to understand

### Good Pull Request
- Clear summary of changes
- Well-structured description
- Includes checklist and content

-----

## Further Reading

---

## Source 1 - How to Make Good Code Reviews Better
URL: https://stackoverflow.blog/2019/09/30/how-to-make-good-code-reviews-better/  
Published: September 30th, 2019  
Author: Stack Overflow

### Key points from reading:

- Code reviews often fail due to poor communication between developers  
- Smaller pull requests are easier to review and result in better feedback  
- Constructive feedback is essential to maintain a positive team environment  
- Reviews should focus on improving the code, not criticising the developer  
- Code reviews help catch issues early before they become larger problems  

### Why this is relevant to our team:
In a fast-moving team like ours, poor communication during code reviews can lead to confusion and delays. This article highlights the importance of keeping pull requests small and feedback constructive. By improving how we communicate during reviews, we can reduce misunderstandings and improve overall code quality.

---

## Source 2 - Best Practices for Peer Code Review
URL: https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/  
Published: Not specified  
Author: SmartBear

### Key points from reading:

- Code reviews should be limited in size to improve effectiveness  
- Faster reviews lead to better outcomes and reduced delays  
- Formal review processes help in identifying defects early  
- Reviewing too much code at once reduces the ability to find issues  
- Regular reviews improve team productivity and software quality  

### Why this is relevant to our team:
If code reviews are too large or delayed, they can become inefficient and lead to missed issues. This is especially important for our team, where multiple developers are contributing simultaneously. Keeping reviews small and frequent will help us detect defects early and maintain a steady development flow.

---

## Source 3 - A Complete Guide to Code Reviews
URL: https://www.swarmia.com/blog/a-complete-guide-to-code-reviews/  
Published: Not specified  
Author: Swarmia

### Key points from reading:

- Slow code reviews create bottlenecks in development  
- Continuous reviewing helps avoid large backlogs of pull requests  
- Clear ownership of reviews improves accountability  
- Teams should prioritise reviewing code regularly  
- Inefficient review processes can delay releases  

### Why this is relevant to our team:
In a small team, delays in code reviews can quickly slow down progress. This article shows that without a structured and timely review process, work can pile up and block development. Implementing consistent and timely reviews will help our team maintain productivity and avoid bottlenecks.

---

## Source 4 - Code Review Best Practices
URL: https://www.atlassian.com/blog/loom/code-review-best-practices-2  
Published: Not specified  
Author: Atlassian

### Key points from reading:

- Code reviews improve collaboration between team members  
- Pull request descriptions help reviewers understand the context  
- Reviews should be part of the team’s development culture  
- Feedback should be clear, respectful, and actionable  
- Code reviews help maintain consistency across the codebase  

### Why this is relevant to our team:
As a team, we need to ensure that everyone understands the changes being made to the codebase. This article highlights the importance of communication and collaboration in code reviews. By improving our pull request descriptions and feedback quality, we can make reviews more effective and easier to understand.

---

## Source 5 - Code Review Best Practices
URL: https://graphite.com/blog/code-review-best-practices  
Published: Not specified  
Author: Graphite

### Key points from reading:

- Small and frequent pull requests are more effective than large ones  
- Fast feedback loops improve developer productivity  
- Code reviews should focus on readability and maintainability  
- Delayed reviews can slow down the entire development process  
- Efficient workflows improve team performance  

### Why this is relevant to our team:
If reviews are delayed or too large, they can slow down development significantly. This is especially important in a fast-paced environment like ours. By focusing on smaller pull requests and faster feedback, we can improve both productivity and code quality.

---

## Common Themes Across All 5 Sources

| Theme | What it means for us |
|------|---------------------|
| Small pull requests are better | Keep PRs small and manageable to improve review quality |
| Code reviews reduce defects | Use reviews to catch issues early before production |
| Fast feedback is essential | Review code quickly to avoid delays and bottlenecks |
| Communication is critical | Provide clear, constructive, and respectful feedback |
| Consistency improves quality | Follow coding standards to maintain a clean codebase |
| Reviews improve team knowledge | Share knowledge across the team through reviews |
| Delays slow development | Avoid backlog by reviewing code regularly |
| Readability matters | Focus on clean, understandable code during reviews |
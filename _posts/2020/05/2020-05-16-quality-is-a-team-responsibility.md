---
title: "Quality is a Team Responsibility"
excerpt: "For overall product quality, teams need to ensure quality in different stages including meetings, code, automated tests, exploratory tests, monitoring"
tags: teams quality
---
Heaving a sigh of relief after deploying a hotfix, Maira and Rob step out of the “war-room” - a meeting room in their
office dedicated for people who are dealing with production outages and issues.

As they walk back to their desks, Kayla, the Product Manager, calls for a quick meeting to brainstorm ways of avoiding
such issues in the future.

Rob starts by explaining details about the issue and what he did to fix it. He continues,
“Maira tested my fix on the staging environment sometime back and she gave a sign off.
So I went ahead with the deployment to production. She also verified the fix on production post deployment.
So the issue should be resolved now”.

“When and how did we detect the issue?”, asks Kayla. “The customer support agents received a lot of complaints from our
users this morning shortly after our service deployment. They escalated the issue, and then we started looking at it”,
replies Rob.

“But why was this not caught in the regular testing that we do before every deployment?”, asks the curious Amisha.
“Isn’t this one of the most important regression testing cases that the QAs should cover?”

“We weren’t aware of this particular change that went in today. It wasn’t planned.
So, we did not check that part of the system as we thought it was unchanged”, justified Maira.

“My suggestion to avoid these types of issues in the future is for QAs to look at commits in the project so that
they understand the areas that are changed. Also, this critical case should be tested by the QAs before every deployment”,
says Amisha.  
Everyone agrees, and the meeting ends.

Is this a good solution to prevent such problems in the future?
Let’s look at some <b>problems in this team which are potentially relatable to us on our projects too.<b>

## Unplanned and Untracked Changes
Many times, the engineering teams or some of the “more helpful team members” directly get unplanned change requests that
are urgent and critical in nature. When some of the low risk changes seem easily doable,
the helpful team members may go ahead and make the changes without checking whether the key stakeholders are informed about it.

Such unplanned or untracked changes, irrespective of how small or important, have a potential to cause great damage.  
In small teams, having processes to track changes might feel like an added overhead.
Irrespective of how the teams decide to manage it, it is imperative that all the stakeholders are aware of the changes
being done and the risk areas are assessed before the changes are made.

## Testing Critical Features Late in the Feedback Cycle
Most teams understand the importance of ensuring that new changes do not cause unexpected behaviours in the older functionality.
But not everyone sees the importance of receiving feedback about unexpected behaviours early.

Even today, some teams rely solely on their QAs to verify the correctness of the entire systems before every release.
This causes not only a considerable amount of back and forth and delay in releases; but also immense strain on the
wellbeing of team members in the long run.

We, as a team, should ensure that unexpected behaviours are caught as early as possible.
Whenever an issue is found in a particular layer of the Test Pyramid, we should assess whether it can be detected at a
layer below and then take appropriate action.  
Getting good feedback about the systems as early as possible should be the team's responsibility.

## Lack of Effective Monitoring and Analytics
Products are complex and users use them in unexpected ways. Due to this, we might discover some new issues or failures
in production. How quickly we detect and react to the issues is crucial for businesses. Does our team detect some
issues ourselves or do we always need customer support agents to inform us?

Monitoring and alerting systems, analytics data which give insights into potential issues are important for the entire team.

## QAs being the sole owners of quality
“Why was this not caught in your testing?” is a question that QAs get asked often in some teams.
This causes core underlying problems to often get overlooked.

If an issue was not detected during testing, it was also not detected by any automated tests or during code reviews.
It was not mentioned as a risk area by anyone in the team during requirement discussions.  
Doesn’t this mean the problem lies in multiple places and not just with the QAs who didn’t test a scenario?

For overall quality of the product, the teams need to ensure quality in all different stages - quality of discussions
and meetings, quality of code, quality of automated tests, quality of exploratory tests, quality of monitoring and
alerting systems, etc.

Quality is a team’s collective responsibility.

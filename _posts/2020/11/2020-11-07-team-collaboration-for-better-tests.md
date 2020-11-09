---
title: "Team Collaboration for Better Tests"
excerpt: "Some ideas about how Developers and QAs can work together to ensure that the right tests are written at the right levels and a quality product is built"
tags: teams quality test
---
Many software engineering teams understand the concept of
<a href="https://martinfowler.com/bliki/TestPyramid.html" target="_blank">Test Pyramid</a>
and know the challenges of maintaining a large End-to-End functional test suite.  
Yet, a lot of these teams find themselves with many UI level tests - a great number of which could either have been
covered at the lower levels of the Test Pyramid or which are already covered but duplicated in the UI level tests.

I was fortunate to have had opportunities of working in teams where all members collaborated with each other effectively
and took a collective ownership of quality.  
Here are a few points about how Developers and QAs worked together to ensure that the right tests were written at the
right levels and a quality product was built.

## Discussing Unit & Integration Tests before Dev Box Testing
When developers finished writing code for a particular feature, they would quickly show the working software to a
Business Analyst (BA) and QA. This activity, where the BAs and QAs check the acceptance criterias,
is commonly known as Dev Box Testing.

Our team decided that the QAs and Developers would discuss unit and integration tests that were written for this
new feature before the start of a Dev Box Testing.

This helped QAs understand what tests were already covered at these lower levels.
Also, this gave them a good opportunity to suggest other cases that could be tested at those levels.  
![Discussions before Dev Box Testing](https://dynamic.pixton.com/comic/j/u/h/7/juh71pd7hq462i09_v19_.png)

<a href="https://twitter.com/mushtaqA" target="_blank">Mushtaq Ahmed</a> was one of the first to start this actively,
and the team benefited a lot from it.

## Writing a Failing Test Together when Issues were Found
When issues were found, in most cases, QAs and Developers would collaborate to write a failing test first.  
![Writing Failing Tests when Issues are Found](https://dynamic.pixton.com/comic/j/u/h/7/juh71pd771npnrmi_v13_.png)

This collaboration helped the team write tests at the lower most possible level where it could be tested effectively.

## Pair Programming with Developers
Though this was not a very frequent occurrence, there were times when Developers and QAs pair programmed and,
also did Test Driven Development.  
They learnt from each other and could deliver better quality products.  
![QAs and Developers Pair Programming](https://dynamic.pixton.com/comic/j/u/h/7/juh71pd7enpzubzs_v12_.png)

This helped QAs understand the code and design better. It led to QAs effectively contributing in design level
discussions and proactively calling out potential issues due to code design - even before any code was written.

## Collective Ownership of End-to-End Functional Test Suite
The QAs took initiative to actively discuss with Developers about the tests that should be automated at the E2E level
in order to have greater confidence in the functionality.  
They also pair programmed whenever possible in writing these end-to-end functional tests.  
![Collective Ownership of End-to-End Functional UI Tests](https://dynamic.pixton.com/comic/j/u/h/7/juh71pd75grb5xoj_v8_.png)

End-to-End tests were everyone’s responsibility. If they failed, the person whos commit caused the failure would work on
fixing it.


Our team benefited a lot with Developers and QAs working together and sharing responsibility for automated tests.
We could avoid duplication of tests across levels and have more tests at the levels where the test gave maximum value.

Hope some of these points can help your teams too!


Credits: <a href="https://www.pixton.com/comic/juh71pd7" target="_blank">Comic strip</a> was made using Pixton.com
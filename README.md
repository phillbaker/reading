# Mature Engineer Reading list

In the mode of [the distributed systems reading list](https://dancres.github.io/Pages/) and the [list of awesome](https://github.com/jnv/lists), this is a reading list to help folks improve their practice of software engineering. The title is inspired by John Allspaw's (Chief Technology Officer at Etsy) [essay on "senior engineers"](http://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/).

### How to use this list

In order to account for different learning styles, it's suggested that after reading these articles, you discuss them with someone or a group. While summarizing the article is good (what did it say), what we're really interested in is _analyzing_ the article.

A good way to take notes is to fork this repository, and add bullet points notes after each article. Here are some good discussion starters or notes to bring to a discussion:

* Of the points made in the article, what were the three most important and why? How are they connected or how are they dissimilar?
* What wasn't clear? What questions do you have?
* Where is the author wrong and why?
* What predictions can we make using the author's arguments?
* Apply the author's arguments to the current project we're working on, the team/department or the company?

To prepare for the discussion, if you're a:
* visual learner, try making tables or venn-diagrams or other charts of these categories or pros/cons,
* auditory learner, try talking these questions through with someone,
* reading/writing learner, try making an outline of your thoughts,
* kinesthetic learner, base your notes off of your recent experienes and examples.

#### Devilish Advocacy

> At the very beginning of your journey it’s difficult to identify what is good and what is bad, what is gold and what is fluff. (Lindsay Holmwood)

Some of the viewpoints expressed will be controversial, outdated or crazy - that's intentional. One goal is to challenge existing beliefs to force examination and challenge any biases. If there’s an viewpoint you disagree with, jot down a brief critique, note how the article made you feel and reflect what about the article made you feel that way. This should lead to one of two outcomes: you'll either improve your arguments about why that idea is flawed, or your perspective will become more nuanced. <sup>[1](http://fractio.nl/2014/09/19/not-a-promotion-a-career-change/#self-education)</sup>

## Books
* Beautiful Code
* Mythical Man Month
* Pragmatic Programmer
* Release It

## Essays

_Aka "blog posts"_

* [On Being A Senior Engineer](http://www.kitchensoap.com/2012/10/25/on-being-a-senior-engineer/)
  * John Allspaw gives examples of the difference between maturity and seniority in a profession.
* [The Law of Leaky Abstractions](http://www.joelonsoftware.com/articles/LeakyAbstractions.html)
  * Joel Spolsky describes how abstractions are imperfect and underlying implementation details sneak through.
* [MonolithFirst](http://martinfowler.com/bliki/MonolithFirst.html)
  * Martin Fowler discusses the tradeoffs of microservices vs. monoliths
* [Failing at Microservices.](https://rclayton.silvrback.com/failing-at-microservices)
  * Richard Clayton describes a lot of the common challenges involved in implementing a popular strategy.
* [Egoless Programming](http://blog.codinghorror.com/egoless-programming-you-are-not-your-job/)
  * Jeff Atwood reminds us that "you are not your code".
* [Applying cardiac alarm management techniques to your on-call](http://fractio.nl/2014/08/26/cardiac-alarms-and-ops/)
  * Lindsay Holmwood applies science to on call rotations!
* [Disagree And Commit](http://electronicdesign.com/energy/disagree-and-commit-risk-conflict-teams)
  * Don Reinertsen explains a way to use conflict productively in a team.
* [How to Report Bugs Effectively](https://www.chiark.greenend.org.uk/~sgtatham/bugs.html)
  * Simon Tatham breaks down a common source of frustration for both software users and developers - reporting and fixing bugs.
* [How awesome engineers ask for help](https://hackernoon.com/how-awesome-engineers-ask-for-help-93bcb2c7dbb7)
  * Greg Sabo lays out the commonsense (but maybe not always at top of mind) tips and tricks for the (necessary) habit of asking for help.
* [Notes on Distributed Systems for Young Bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)
  * Jeff Hodges compiles a hit list of the issues found in distributed systems engineering.
* [Towards an understanding of technical debt](http://laughingmeme.org/2016/01/10/towards-an-understanding-of-technical-debt/)
  * Kellan Elliott-McCrea discusses how technical debt may or may not exist.
* [The Process Myth](http://randsinrepose.com/archives/the-process-myth/)
  * Michael Lopp (aka Rands) talks about the why the P-word exists and isn't bad - "processes should reflect your values".
* [Runbooks are stupid and you’re doing them wrong](http://holyhandgrenade.org/blog/2011/08/runbooks-are-stupid-and-youre-doing-them-wrong/)
  * Jeff Goldschrafe argues that exceptional states should not be treated exceptionaly.
* [Choose Boring Technology](http://mcfunley.com/choose-boring-technology)
  * Dan McKinley argues that constraints can drive creativity.
* [Lessons learned from reading postmortems](http://danluu.com/postmortem-lessons/)
  * Dan Luu does science on some of the largest mistakes in the industry.
* [How One Jira Ticket Made My Employer $1MM/Month](https://medium.com/javascript-scene/how-one-jira-ticket-made-my-employer-1mm-month-7-metrics-that-actually-matter-ffb5b2376a6b) (really 2 separate articles, the jira ticket part is more manager-y vs. the perf. metrics)
* [Why I Love Reading Other People’s Code And You Should Too](http://www.skorks.com/2010/05/why-i-love-reading-other-peoples-code-and-you-should-too/)
  * Alan Skorkin points out that before mastering something we have to see a lot of examples.
* [A Codebase is an Organism](http://www.meltingasphalt.com/a-codebase-is-an-organism/)
  *  Since [codebases inevitably grow over time](https://www.computer.org/csdl/mags/so/2015/02/mso2015020010.pdf), Kevin Simler looks at how to manage that growth.
* [How to ask good questions](http://jvns.ca/blog/good-questions/)
  * Julia Evans dissects the art of asking a question - although there may be "no such thing as a stupid question", there certainly are poorly asked ones.
* [Why Averages Suck and Percentiles are Great](https://www.dynatrace.com/blog/why-averages-suck-and-percentiles-are-great/)
  * Michael Kopp lays out some basics of monitoring.
* [Monitoring Best Practices Learned from IT Outages](https://www.pagerduty.com/blog/monitoring-best-practices-it-outages/) , [ Zen and the Art of System Monitoring ](https://www.scalyr.com/community/guides/zen-and-the-art-of-system-monitoring)
  * Vivian Au, in a guest post by DataDog staff on the PagerDuty blog, looks at how to classify and choose data to alert on which to alert. 
  * Noah Lehmann-Haupt gives a _great_ overview of monitoring and breaks down high level principles for how to approach the problem of making sure your stuff is working.
* [Logging vs. instrumentation](https://peter.bourgon.org/blog/2016/02/07/logging-v-instrumentation.html) Also [1](https://medium.com/@copyconstruct/logs-and-metrics-6d34d3026e38) and [2](https://grafana.com/blog/2016/01/05/logs-and-metrics-and-graphs-oh-my/)
  * An opinionated piece diffentiating between two related practices.
* [Just Say No to More End-to-End Tests](https://testing.googleblog.com/2015/04/just-say-no-to-more-end-to-end-tests.html)
  * Mike Wacker (although starting from a link bait title) reviews the testing pyramid.
* [Clear Writing Means Clear Thinking Means…](https://hbr.org/1973/01/clear-writing-means-clear-thinking-means)
  * A slightly dated, but remarkably relevant argument for the power of writing - a necessary skill in larger technical organizations. 

## Practical Basics

_Introductory topics for a software engineering beginning their journey_

* [Debugging and Profiling](https://missing.csail.mit.edu/2020/debugging-profiling/#resource-monitoring) Although formal education provides solid theoretical foundations for a career in software engineering, it neglects a lot of the practical side. This topic from a course at MIT designed to cover the tools of the trade is a short list of the common tools used to debug a running Linux system. This list of tools and the [exercises](https://missing.csail.mit.edu/2020/debugging-profiling/#exercises) are a good to put in your toolbox for when things stop working.


## Videos

* [What We Actually Know About Software Development, and Why We Believe It’s True](https://vimeo.com/9270320)
  * Greg Wilson both summarizes peer-reviewed research on software development and advocates for doing science about our profession.
* [Simple Made Easy](http://www.infoq.com/presentations/Simple-Made-Easy), [slides](https://github.com/matthiasn/talk-transcripts/tree/master/Hickey_Rich/SimpleMadeEasy)
  * Rich Hickey discusses simplicity's virtues over easiness'. He showes that while many choose easiness they may end up with complexity, and the better way is to choose easiness along the simplicity path.
* [You and Your Research](https://www.youtube.com/watch?v=a1zDuOPkMSw)
  * Richard Hamming shares his observations on "why do so few scientists make significant contributions and so many are forgotten in the long run?" Some of the key ideas include: courage, luck, drive, a focus on important problems, open doors, and selling the work.
* [How To Design A Good API and Why it Matters](https://www.youtube.com/watch?v=aAb7hSCtvGw)
  * Josh Bloch examines what makes a good (programmtic) API and practices to design them.

## Slides

* [Billion User Load Balancer](https://www.usenix.org/sites/default/files/conference/protected-files/srecon15europe_slides_shuff.pdf)
  * Patrick Shuff talks about Facebook's multi-tiered network.
* [Designs, Lessons and Advice from Building Large Distributed Systems](http://www.slideshare.net/xlight/google-designs-lessons-and-advice-from-building-large-distributed-systems/24-Numbers_Everyone_Should_KnowL1_cache)
  * Jeff Dean
* [10 Deploys Per Day](http://www.slideshare.net/jallspaw/10-deploys-per-day-dev-and-ops-cooperation-at-flickr)
  * In this oldie-but-goodie, John Allspaw talks about some of the fundamental good practices around deployment.

## Why

Here are three reasons to spend time out of your busy schedule doing some reading/watching:

* stay up to date: in the 21st century, sofware will continue to change. Yesterday it was Java, today its Go, etc.
* self-improvement: everyone makes mistakes or has gaps in their skillset. Even the best are still learning and improving.
* career growth: tomorrow's bigger and harder challenges will require new skills. Think about this preparation for handling something an order of magnitude harder.

## Related

* https://github.com/mmcgrana/services-engineering/
* https://github.com/JanVanRyswyck/awesome-talks
* http://danluu.com/programming-blogs/

# Contributing

Please contribute good articles back to this list!

1. Fork it ( https://github.internal.digitalocean.com/phillip/reading/fork )
2. Create your feature branch off of origin/master (`git checkout -b my-new-feature origin/master`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

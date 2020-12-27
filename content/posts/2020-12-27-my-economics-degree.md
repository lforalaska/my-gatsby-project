---
template: post
title: Engineering Economics
slug: engineering-economics
socialImage: /media/stonks.jpg
draft: true
date: 2020-12-27T02:36:59.181Z
description: How I use my college degree in industry
category: rambles
tags:
  - economics
  - college
  - industry
---
<!--StartFragment-->

"Your college major doesn't matter!"

When I was still a student at Colorado College, meeting alums at professional networking events, this was a frequent adage. English majors turned doctors. Math majors now journalists. 


- - -

My current project is tackling our developer experience on a ML CI/CD (continuous integration/continuous deployment) product. Developers don’t have confidence that they can change things without breaking the entire product. The typical response to unreliable code is to create a robust testing infrastructure. Our problem is that an e2e (end-to-end) integration test takes a very long time and sometimes fails to give any signal at the end. The result is developers started ignoring the test result all together

On the code side, I wasn’t sure why the test was taking so long and what we could do to make it go faster. On the people side, I needed to convince more experienced engineers to abandon their failed testing infrastructure and embrace a new order. 

Enter my economics degree.

- - -

The first step was to find metrics on exactly how long the test was taking and how often it gave no signal. I knew people were attached to the e2e integration test due to risk aversion. The stats told me it was rare the e2e integration test actually prevented a failure and more often caused failures because people relied on it as a crutch to unit tests. When I presented my data, I was careful to frame the current testing infrastructure as a loss and in high impact terms ($$$). 

> "The average engineer on our team wastes 8 hours a week due to our testing infrastructure. In dollar amounts, that’s over $2000 in labor hours and $500 in computing resources. Across our team, that’s enough money to hire another engineer." 

Framing my argument in this way got my manager on board very quickly. With my manager on board, others were quick to follow. Now that I had people on board to change our testing infrastructure, the next question was how do I actually make it better? 

My economics degree says I should optimize on marginal benefit over marginal cost. I analyzed our code base for improvement opportunities and noted the labor costs for each. Even at a company like Facebook, there’s still low hanging fruit. 



<!--EndFragment-->
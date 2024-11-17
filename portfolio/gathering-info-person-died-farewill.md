---
title: Go To Market / Operations tooling, Farewill
subtitle: A complex 0 to 1 project which reduced a key aspect of case time from 19 to 6 days
description: Internal tooling · 2020
date: '2020-05-10'
thumb_image: images/thumbnail-person-died-wide.webp 
image: images/Fact-find-crit-sketch-later.webp 
layout: project
---

### Problem

Our probate team gathered a lot of information from families. We needed it to fill out forms, to apply for probate. We found the best experience for customers was to collect the information by phone. But our service was scaling – we needed tools to make the process efficient and simple and to collect the data in a usable way. 

*How might we build internal tools to help our team gather information efficiently and simply from customers over the phone?*

### Project
This was our ‘Fact find’ project. It lasted about 3 months. 

### Team
Me – sole product designer and project lead, working as part of an in-house cross-functional product team including:
User researcher (Clare), PM (James), engineers (Emily, Jacob, Gavin, Demi), plus various users and stakeholders.

### Process

**Kick-off**

>I fear it will be too rigid. Spreadsheets are messy but flexible - e.g. user can add a note anywhere, which is useful because can get a lot of info thrown at them from customer. Would be good if some way of taking info from customer in the order it's provided.

...a quote from a user in the kick-off workshop

I ran a kick-off workshop with users and stakeholders from across the business, plus all the product team. It helped to surface hopes, fears, problems and scope. I always hope a kick-off will gather a wide range of perspectives, uncover problems and help bring the team along on the journey.

![Screenshot from kick off workshop](/images/fact-find-kick-off-workshop.webp "Kick off workshop")

Above: a small section of our kick-off Miro board.

![Excerpt from kick off doc](/images/fact-find-kick-off-doc.webp "Excerpt from kick off doc")

As I often do for larger projects, I wrote a kick-off doc. It reflected user needs, project goals, team, stakeholders and success metrics. It’s a useful thing to refer back to during the project, to remember what we agreed. As always, it was in the open, for transparency and to encourage comments. 

**Research and observation**

We weren’t working from a blank slate. For a few months, the probate team had been using a Google sheet (which I designed) to collect the information. Essentially, the spreadsheet was the prototype, and it had been tested and iterated over the course of the year.

I spent extra time with the team watching them use the spreadsheet and listening in to fact find calls. One of the advantages of building internal tools for a tight-knit team is a bank of shared knowledge. 

**Critiquing early designs**

I brought early stage UI designs to our weekly design crit. Our crit is a safe environment for subjective feedback from the rest of the design team. It’s a great way to validate, tweak or throw out scrappy ideas. 

![Farewill design crit](/images/Farewill-design-crit.webp "Farewill design crit")

Above: Farewill’s design crit, early 2020 (I’m third from left) 

I used the crit to help validate or throw out sketchy ideas.

![Early rough design](/images/Fact-find-crit-sketch-earlier.webp "Early rough design")

Above: a rough sketch I brought to the crit

Feedback from one crit session included:
- The way users need to mark sections as complete is confusing
- The dark, floating list of things to do is confusing too, and why is it at the bottom of the screen?
- Because it’s at the bottom, it could be a long way from the section header, which could make things unclear or less usable
- The ‘blob’ illustration is just ‘juice’ — a needless addition that could be off-putting for users

**Designing in the open**

I ran user tests and interviews, as did our PM James. I tend to find the best insight comes from users using prototypes, and feeding back in 1:1 sessions. I was also happy to receive comments directly on the designs (see below). 

![Screenshot of feedback comments](/images/Fact-find-figma-comments.webp "Screenshot of feedback comments")

Above: on a complicated project, feedback can be quite overwhelming, but always helpful. 

**User testing**

Observations from the user tests that James and I ran included:

- There’s no section for money owed to the person who died. E.g. if they are due a council tax refund.
- When there were validation problems entering numbers,  there was a technical rather than human friendly error message.
- And more technical considerations, like, in the pension section, it’s better to ask something like “Did they receive a pension other than the state pension?” and only show further questions if the answer is yes 

**UI**

The designs called for a couple of additions to our design system. The first was an input with a floating label (a label shown within the input, which moves to make space for the text). It’s not something I’d normally consider, but space was paramount – by removing the need for an external label, it saved space, reduced the page length and helped readability. Crucially, the label remained visible after the input gained focus.

![Floating label UI pattern](/images/Fact-find-UI-floating-label.gif "Floating label UI pattern")

I also introduced a toggle. I sketched a number of options. For the final one, I mocked it up in off and on positions. Then, my colleague Emily (a developer with a wonderful eye for design) created the final interaction.

![Toggle UI pattern](/images/Fact-find-UI-toggle.gif "Toggle UI pattern")

**The final product**

Fact find was essentially a (very) long form. We included floating navigation to make it easy for users to jump between sections – particularly important as customer calls often don’t follow a strictly linear process. 

![Later designs](/images/Fact-find-crit-sketch-later.webp "Later designs")

For things like assets, we introduced a card pattern – users could add as many of a particular type of asset as needed, while keeping the UI relatively compact and readable. 
I worked closely with the engineers during the build. We ironed out various things collaboratively, like how users added notes to sections and how the data fed through to a summary page.

### Outcomes

We measured the average time from the initial fact find call to referral to our legal partners (a key metric for us and customers). Before the project it was 19 days. After the project, it was 6.1 days!

Everyone was incredibly pleased with the outcomes of the project. Although we expected to learn and make improvements after launch, very few changes were needed. 

Feedback from colleagues included...

> What you’ve done is amazing. The burden has been lifted!

> Incredible detail and beautifully put together

> Tom is brilliant at distilling down complex stakeholder requirements into well-considered designs (that are a joy to build - who wants to build ugly things?!) - i.e. the fact-find form

> I’m frequently in awe at how Tom can take in what seems to be something incredibly complex or vague and loosely defined and produce out the other side a really clear and well understood model, diagram, design or kick-off document

### Reflections

- The nitty gritty UI challenges were fun, as was introducing new patterns to our design system
- The complex legal and financial requirements were challenging – some of it got very technical! Luckily we have very engaged specialist users who are able to explain things clearly. 
- We didn’t have a way to objectively measure the success of the project, mainly because at the time we were lacking clear data on how efficiently we ran probate cases. 

[Next project →](/portfolio/cremation-forms-farewill)
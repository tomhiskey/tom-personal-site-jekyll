---
title: Blood test results · Thriva
subtitle:  Revamping Thriva's native app experience in 10 weeks, leading to a 30% drop in cancellations · Aug 2022 · B2C mobile 
date: '2022-09-10'
thumb_image: images/thumbnail-thriva-results-wide.png 
image: images/thriva-native-results.webp 
layout: project
---

### Problem

A couple of days after taking a Thriva blood test, customers see their results on the Thriva app. We had insights from customers about the experience, including:

* Difficulty finding information about a result — customers sometimes missed helpful clinical guidance
* Difficulty navigating to a particular result — the results page is quite long, with up to 14 different test profiles
* App activity dropped off significantly 20 days after download — how could we make it more useful for customers long after their test results?
* Difficulty understand the next steps after a failed test
* Difficulty interpreting colours, particularly for colourblind users

Above all, there was an unclear "so, what next?" after receiving results. 

This impacted retention rate – specifically, the percentage of customers who've had their 1st test and go on to buy a 2nd.

![A screenshot of Thriva’s app with a summary of blood test results](/images/thriva-results-app.webp "A screenshot of Thriva’s app with a summary of blood test results")
_Above: the Thriva app before this project_

We had another business problem to consider — our app’s results page was a ‘web view'. We needed to rebuild it natively, to make it more flexible and scalable and improve the experience for users. This was a good moment to make the change – usage of Thriva's app was increasing, with 57% of new Thriva users viewing their results in the app.

With these business and user needs in mind, we framed our design challenge:

_How Might We simplify the journey to and within the results page, with clearer actions for T1 users?_

(T1 is Thriva jargon for customers who’ve bought 1 test.)


### Project

This was our 'Native app results experience' project, July to Sep 2022. It lasted 10 weeks from kick-off to launch. 

### Team

Me – Design lead / project lead, working as part of a cross-functional team including:
Alexis (PM who joined half way through the project), Seth (Tech Lead), Aish and Kirstie (mobile engineers), Suse (FE engineer), Noel and Macarena (Clinical stakeholders), Becky (user research), Andrea (content design).


### Process

**Kick off**

I hosted a kick off workshop with the whole team. We reviewed the insights and shared our hopes and fears for the next steps. It helped build a shared understanding of the problem space, hone in on scope and bring a diverse range of opinions to the table.

![A screenshot of a Miro board from our discovery workshop](/images/thriva-results-miro.webp "A screenshot of a Miro board from our discovery workshop")

![Animation of colleagues using a Miro board](/images/thriva-results-hopes-fears.gif "Animation of colleagues using a Miro board")


**Measuring success**

We agreed on three metrics:

* % T1 customers who purchase supplements within 7 days of results
* % T1 customers who update next package within 7 days of results
* % T1 customers who cancel within 7 days of results

We'd also track:
* retention rate, which would be our north star metric. However, we knew retention could only be measured over a long term, and was impacted by many things.
* app load times, which the engineers used one of their measures for success

**Journey mapping and insights**

Having gathered our insights and framed our challenge, we dug deeper.

We reviewed the current user journey…

![A user journey with screenshots from our app](/images/thriva-results-user-journey.webp "A user journey with screenshots from our app")

We delved into the data…

![A screenshot of some data analysis](/images/thriva-results-data.webp "A screenshot of some data analysis")

We came up with around 40 problem statements and grouped them by impact and effort. We emerged with an achievably concise list of challenges to tackle.

![A screenshot of a Miro board with post-it notes](/images/thriva-results-impact-effort.webp "A screenshot of a Miro board with post-it notes")

I also hosted a competitor teardown. I invited people across Thriva who'd used our competitor's (or similar) products to share their experiences. I created a Miro with screenshots and journeys for a dozen or so products – it endured beyond this project and became an important tool for product teams.

**Ideation**

I ran a group sketching session. Noel and Macarena — doctors in Thriva’s Clinical team — were among the sketchers. Noel had an idea about combining results charts which I loved, and became a key part of our solution. Seth, our tech lead, shared an idea about the way we order the page and bring the most important information up top.

![A photo of hand-drawn sketches by Andrea](/images/thriva-results-sketches.webp "A photo of hand-drawn sketches by Andrea")

Everyone seems to love sketching sessions — it’s fun and mindful to be creative. As a designer, I value the output of these sessions as a jumping off point for wireframing.

**Wireframing**

One design challenge was simplifying the routes to clinical recommendations, clarifying the language and surfacing the most helpful information at the right time. I worked closely with Andrea, our content designer, and our Clinical team.

The image below shows some early content— for example, the ‘How to improve your iron (ferritin) levels’ boxes on the left and the ‘How total iron-binding capacity affects your health, and how to improve it’ on the right.

![Early designs showing a mix of content](/images/thriva-results-content.webp "Early designs showing a mix of content")

Andrea and I went through a number of iterations. In a later design (below), the box on the left said ‘Take action’, and the link on the right was ‘Understand your result’. In testing, users found these easier to read, easier to interpret, and less likely to miss.

![Later designs showing simpler, more concise content](/images/thriva-results-content2.webp "Later designs showing simpler, more concise content")

**Results summary UI**

One aspect of the UI we wanted to improve was the results summary. For example, because users – colourblind users in particular – struggled to interpret the colours. In the image below, the screenshot on the left is the existing results summary. On the right is a simulation of how a colourblind user might see it, with dulled, relatively indistinguishable colours. 

![A comparison of a screen showing a simulation of what a colourblind user might see](/images/thriva-results-colour-blind.webp "A comparison of a screen showing a simulation of what a colourblind user might see")
_Left: results summary. Right: results summary simulated for a type of colourblindness. This comparison is only helpful for non-colourblind readers of this case study – apologies to others._

Something I experimented with, but ultimately rejected, was a colourful summary donut chart (early greyscale explorations shown below) — we all loved it, but when we tested it with users, they found it tricky to use, and it was hard to make accessible.

![Early design explorations of a summary chart](/images/thriva-results-chart.webp "Early design explorations of a summary chart")

**Testing with users**

Becky and I ran two rounds of evaluative testing. The first was on usertesting.com, testing aspects of usability with non-customers. The second was with customers — moderated interviews to dig more deeply into the designs from the perspective of Thriva users. For each round, Becky and I worked together to prepare a prototype and script.

![A screenshot of a user interview](/images/thriva-results-testing.webp "A screenshot of a user interview")
_Above – a moderated user test with a Thriva customer_

I co-hosted the sessions and incorporated insights from the research into the next design pass.

**Working transparently, gathering feedback**

As well as testing externally, I was continually sharing progress in our our weekly design crit — when members of Thriva's design team come together to share work and seek feedback.

![A screenshot of a design showing feedback from a crit](/images/thriva-results-feedback.webp "A screenshot of a design showing feedback from a crit")

I also worked very closely with engineers. We had dedicated time in design reviews and tech planning to dig into the designs in more detail and gather feedback. Shout out to Aish, one of our mobile engineers, for keeping me on the straight and narrow with accordions 🙌

![A screenshot of a team meeting](/images/thriva-results-engineers.webp "A screenshot of a team meeting")

<hr>

### Outcomes

We lauched the new version of the app on time, on 15 Sep – 10 weeks after kick-off. We'd achieved a key goal – to rebuild the app natively.

In terms of metrics, the most encouraging outcome was a roughly 30% drop in cancellations within 7 days of results over the 3 months after launch. This is a proxy metric which impacts retention rate, our north star.

We also tracked supplement purchases from the app, which increased around 25% after launch. 

We tracked retention rate, though, as expected, trends can only be assessed over the long term, and are impacted by many things – it was hard to attribute to the changes we made during this project.

![Recent UI designs](/images/thriva-results-final-designs.webp "Recent UI designs"){: .large-post-image}

### Reflections

* We stuck to time and scope and rebuilt the app natively, with significant usability and accessibility improvements.
* Although outcomes were positive, the impact on our north star metric – retention rate – was inconclusive. Which raises the question, could we have used those 10 weeks to make a more tangible impact?
* However, the project was an important foundational step for further retention work – even before launch, we'd kicked off another project, again with retention rate as its north star metric.
* I look back very fondly on this project – we were a good team, collaborating really well and moving quickly. One thing I particularly enjoyed was collaborating with engineers on the app UI.

*For a different angle on this project, particularly how the different memebers of Thriva's CRD team worked together, [see my post on Medium from Aug 20222](https://tomhiskey.medium.com/re-designing-thrivas-results-experience-a-case-study-from-our-crd-team-8a4b79c34e9b).*

[Next project →](/portfolio/personas-useful-and-inclusive)

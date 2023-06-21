---
title: Native results experience @ Thriva
subtitle:  Revamping Thriva's native app experience from discovery to build, Aug 2022
date: '2022-09-10'
thumb_image: images/thumbnail-thriva-results-wide.png 
image: images/thriva-native-results.webp 
layout: project
---

*I first published this [on Medium](https://tomhiskey.medium.com/re-designing-thrivas-results-experience-a-case-study-from-our-crd-team-8a4b79c34e9b).*


### Context

Thriva exists to increase the time we all spend in good health. An important part of that is our home blood test. A couple of days after drawing a few drops of blood and posting it off to our lab, the customer receives a notification — the results are ready to view on the Thriva app.

![A screenshot of Thriva’s app with a summary of blood test results](/images/thriva-results-app.webp "A screenshot of Thriva’s app with a summary of blood test results")


### Basing our designs on problems

Over time, we’d gathered a bunch of insights about the experience of checking results — from user testing, customer interviews, feedback, data and our own product reviews.

The insights are overwhelmingly positive — there are already so many things customers love about checking their Thriva results. But there are things that could be better.

Our user researcher Becky and our data analyst Sian pulled these insights together onto a Miro board, so we could review them as a team and base our next steps on known customer problems.

![A screenshot of a Miro board from our discovery workshop](/images/thriva-results-miro.webp "A screenshot of a Miro board from our discovery workshop")


For example, problems included:

* Difficulty finding information about a result — customers sometimes missed helpful clinical guidance
* Difficulty navigating to a particular result — the results page is quite long, containing up to 14 different test profiles
* App activity dropped off significantly 20 days after download — how could we make it more useful for customers long after their test results?
* Difficulty understand the next steps after a failed test
* Difficulty interpreting colours, particularly for colourblind users

We also had a problem of our own — our app’s results page was a ‘web view’, we needed to rebuild it in native, to make it more flexible and scalable.

We ran a workshop with the whole Product Experience squad — engineers, clinicians and others. We reviewed the insights together, and shared our hopes and fears for the next steps. It helped build a shared understanding of the problem space and bring a diverse range of opinions to the table, early on.

![Animation of colleagues using a Miro board](/images/thriva-results-hopes-fears.gif "Animation of colleagues using a Miro board")

We had a good signals that this project would make a big impact — 57% of new Thriva users view their results in our app, and our insights suggested that improving the experience for customers would increase retention and engagement.

### Framing the challenge / measuring the goal

Together, we framed our design challenge. We came up with this question, to focus the rest of the project:

How Might We simplify the journey to and within the results page, with clearer actions for T1 users?

(T1 is Thriva jargon for customers who’ve just had their first set of results.)

We agreed on three metrics we wanted to move:

* % T1 customers who purchase supplements within 7 days of results
* % T1 customers who update next package within 7 days of results
* % T1 customers who cancel within 7 days of results

### Building the right thing

Having gathered our insights and framed our challenge, we dug deeper.

We reviewed the current user journey…

![A user journey with screenshots from our app](/images/thriva-results-user-journey.webp "A user journey with screenshots from our app")

We went further into the data…

![A screenshot of some data analysis](/images/thriva-results-data.webp "A screenshot of some data analysis")

We came up with around 40 problem statements, grouped them and gave each group its own How might we question. It was all a bit overwhelming, so we prioritised them by impact and effort, and ended up with an achievably concise list of challenges to tackle.

![A screenshot of a Miro board with post-it notes](/images/thriva-results-impact-effort.webp "A screenshot of a Miro board with post-it notes")

### Building the thing right

Time for some fun… commence sketching! I set up a group session with 45 minutes of focus time to sketch ideas (I chose the music — sorry everyone 🎵) followed by a group discussion.

Noel and Macarena — doctors in Thriva’s Clinical team — were among the sketchers. Noel had an idea about combining results charts which I loved, and has become a key part of our solution. Seth, our tech lead, shared an idea about the way we order the page and bring the most important information up top.

Andrea, our content designer, sketched some ideas for a product tour, with considerations for users’ varying degrees of health literacy.

![A photo of hand-drawn sketches by Andrea](/images/thriva-results-sketches.webp "A photo of hand-drawn sketches by Andrea")

Everyone seems to love sketching sessions — it’s a lot of fun to be creative, and a mindful thing to pick up a pencil and do some drawing.

<hr>

### We started wireframing
With a tonne of insights and ideas, we were in a great place to start wireframing — drawing up low fidelity designs for sharing and testing.

I was our product designer for the project — it was fun taking off my manager hat for a couple of months.

![A screenshot of designs in Figma](/images/thriva-results-feedback.webp "A screenshot of designs in Figma")


### Making the results summary accessible
One aspect of the UI we wanted to improve was the results summary. Users struggled to interpret the colours — colourblind users in particular. In the image below, the screenshot on the left is the existing results summary. On the right is a simulation of how a colourblind user might see it, with dulled, relatively indistinguishable colours.

This comparison is only helpful for non-colourblind readers of this case study – apologies to others.


![A comparison of a screen showing a simulation of what a colourblind user might see](/images/thriva-results-colour-blind.webp "A comparison of a screen showing a simulation of what a colourblind user might see")


Left: results summary. Right: results summary simulated for a type of colourblindness.

Something we experimented with, but ultimately rejected, was a colourful summary donut chart (early greyscale explorations shown below) — we all loved it, but when we tested it with users, they found it tricky to use, and it was hard to make accessible.

![Early design explorations of a summary chart](/images/thriva-results-chart.webp "Early design explorations of a summary chart")

We also wanted to re-order the results, to bring the most important up top — something we’d heard from users, and in Seth’s sketches.

After much testing (more on that below) and more iteration, we settled on the following design. Users no longer have to rely on colour to interpret the results, and can link straight through to a particular test profile

![A screenshot of a completed design](/images/thriva-results-summary.webp "A screenshot of a completed design")

### Working with Andrea, our content designer

In CRD, we work very closely across disciplines and like to blur the boundaries between product design, content design and user research.

During discovery, Andrea, our content designer, provided an analysis of app’s content through an object-oriented UX perspective. 

During the design phase, she and I frequently jumped into Figma to pair on all sorts of problems, with Andrea focusing mainly on the the content, such as the language.

An example of a content design challenge was simplifying the routes to finding clinical recommendations, clarifying the language to get there, and surfacing the most helpful information at the right time. Andrea worked closely with members of our Clinical team — we’re incredibly lucky to have a team of doctors who are embedded in product squads and engaged with the design process.

The image below shows some early content— for example, the ‘How to improve your iron (ferritin) levels’ boxes on the left and the ‘How total iron-binding capacity affects your health, and how to improve it’ on the right.

![Early designs showing a mix of content](/images/thriva-results-content.webp "Early designs showing a mix of content")

These went through a number of iterations. In a later design (below), the box on the left said ‘Take action’, and the link on the right was ‘Understand your result’. In testing, users found these easier to read, easier to interpret, and less likely to miss.

![Later designs showing simpler, more concise content](/images/thriva-results-content2.webp "Later designs showing simpler, more concise content")

### Testing with users

Our user researcher Becky ran two rounds of evaluative testing. The first was on usertesting.com, testing aspects of usability with non-customers. The second was with customers — moderated interviews to dig more deeply into the designs from the perspective of Thriva users. For each round, Becky, Andrea and I worked together to prepare a prototype, and Becky drew up a research plan and script.

![A screenshot of a user interview](/images/thriva-results-testing.webp "A screenshot of a user interview")

Above – a moderated user test with a Thriva customer


![Examples of research analysis](/images/thriva-results-research.webp "Examples of research analysis")

Above – Snippets from Becky’s research analysis

Becky analysed the results and presented them back to the whole team. Then we fed the learnings into the next version of the designs.

(As an aside, we’re working on putting all our user research insights into a research repository using Dovetail — a big job which will make our insights much more accessible and scalable.)

### Working transparently, gathering feedback from other designers and engineers

As well as testing externally, we have internal team rituals which help gather ideas and drive our designs forward. One of those is our weekly design crit — a safe space for members of CRD and our design friends in Growth to come together, share work in progress and seek feedback.

We regularly shared work in crit from the results project, including scrappy early wireframes.

![A screenshot of a design showing feedback from a crit](/images/thriva-results-feedback.webp "A screenshot of a design showing feedback from a crit")

We also worked closely with engineers, our product manager and clinicians. We had dedicated time in design reviews and tech planning to dig into the designs in more detail and gather feedback. Shout out to Aish, one of our software engineers, for keeping me on the straight and narrow with accordions 🙌

![A screenshot of a team meeting](/images/thriva-results-engineers.webp "A screenshot of a team meeting")

### Outcomes… to follow

We have no outcomes to share yet — we’re still in the build phase of the project. We’ll be launching our updated app autumn 2022! With Sian’s help we’ll be tracking those metrics (see above), and finding out whether our updates have, as hoped, improved the experience for Thriva customers checking their blood test results.


![Recent UI designs](/images/thriva-results-final-designs.webp "Recent UI designs")

This was a fun and rewarding project working on a significant aspect of the Thriva experience. It also feels like we’re just scratching the surface. Through our discovery and design phases we uncovered all sorts of other possibilities and gathering yet more insights.


[Next project →](/portfolio/personas-useful-and-inclusive)
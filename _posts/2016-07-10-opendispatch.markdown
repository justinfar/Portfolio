---
title: Building a fleet management solution that never shipped
date: 2016-12-10 23:50:26 +02:00
categories:
- work
tags:
- mobile
- product
- ux
description: As the title implies, this didn't ship, but I still wrote about it because despite not being able to see it out there in the wild, it was still a learning experience.
image: opendispatch.png
permalink: opendispatch.html
layout: post
color: "#02E16B"
title--color: "#FFF"
accent: "#02E16B"
style: translateY(-5px)
context: This project took place between July 2016 and October 2016. I was a user experience design intern making up a small team that consisted two senior engineers and an engineering intern. I was responsible for initial research, experience design, visual design and some front-end development. <br /><br />Unfortunately, most of the work that will be shown here didn’t get shipped due to reasons that I can’t go too much into detail in. What I can tell you however, is that this was one product that definitely needed some love.
team: Mark Emerson, Allan Gauci, Alessio Palmigiano, Myself
role: Product Design and Prototyping
---

<style>
	img {
		border: none;
	}
</style>

<h2>Overview</h2>

<p>Open Dispatch is a fleet management application designed to provide mobile teams such as technicians and drivers an intuitive and unobstructive experience with which to carry out their work. Fleet managers, back office managers and workshop operators are also able to view real-time updates of the progress made by field agents. </p>

</article>
</div>
</div>

<img src="img/opendispatch_all.png" alt="Some research notes from this project" style="border: none; width: 100%;">
<div class="wrapper">
<figcaption>Some iterations showing steps to be taken during a task confirmation. Yes I can see you over there looking disappointingly at that Lorem Ipsum placeholder text.</figcaption>

</div>
<div class="post wrapper">
<div class="col-sm-8">
<article class="post-content">


<!-- Problem -->
</article>
</div>
</div>

<section class="feature__context" style="margin-bottom: -70px; background-color:#02E16B;">
<div class="wrapper">
<div class="col-sm-8 white">
<h2>
	How can we make mobile workers’ communication channels with the backoffice more clear?
</h2>
<p class="white">As it stood, the mobile application that was being used was built in such a way that it needed to support specific PDA devices. Now that the client was using Android phones, it was decided that the product team needed to address the painpoints of the previous experience whilst also translate the experience onto the Android ecosystem.</p>
<br />
</div>
</div>
</section>

</div>
<div class="post wrapper">
<div class="col-sm-8">
<article class="post-content">

<!-- ////////////////// -->

<!-- Hypothesis -->
</article>
</div>
</div>

<section class="feature__context">
<div class="wrapper">
<div class="col-sm-8">
<h2 style="color: #23E16C;">A frictionless and helpful task flow designed for productivity</h2>
Productivity is critical for a mobile workforce to operate at an optimal level. If the backoffice team and the field agents were not communicating well, then that in itself would be a major headache. <strong>Thus, the more connected a workforce is to the business, the more productive they become.</strong>

<p>We knew that most of our efforts needed to go towards the task flow, because that’s where field workers need to get their work done. Thus, by improving the experience of the task flow, we can better address the issues faced by both backoffice staff and field agents.</p>
</div>
</div>
</section>

</div>
<div class="post wrapper">
<div class="col-sm-8">
<article class="post-content">

<!-- ////////////////// -->

<h2>The fundamental 'why'</h2>

<p>Naturally we weren’t just designing and building this application for the sake of having a newer version. The fundamental ‘why?’ was much more than needing a ‘refresh’.   There was an amalgamation of painpoints that needed to be addressed, however they had all seemingly stemmed from one underlying problem — <strong>task handling</strong>.</p>

<p>We had to start from somewhere. To reach our goal we knew task completion time would be something that we’d need to measure and refer to. One thing we also needed to constantly remember was — management and stakeholder buy-in. </p>

<img src="img/taskfinished.png" alt="Some research notes from this project" style="border: none; width: 100%;">
<div class="wrapper">
<figcaption>We tried to find out current pain points within the existing solution, so that we could see what was and wasn't working. As can be seen above there were definitely some problems that we needed to address.</figcaption>

<!-- People -->
</article>
</div>
</div>

<section class="feature__context">
<div class="wrapper">
<div class="col-sm-8">
	<h2 style="color: #23E16C;">
		Understanding the people and the space 
	</h2>
<p>My lack of domain knowledge in this particular space meant that I needed to dive in, and immerse myself as thoroughly and as quickly as possible. Due to a very limited timeline, I had to resort to good old desk research and adhoc interviews. </p>

<p>That basically translates to having twenty browser tabs open, chat logs, complaints, quick semi-structured interviews, research articles, blogs a plenty and whatever else I could get my hands on to inform both myself and the product decisions I would eventually make.</p>

<p>Looking at what other people had done such as OneFleet and TookanApp had really set a benchmark that we had to reach (and hopefully someday exceed), even though there was a lot of work ahead. </p>

<p>I believed that the collective mind is better than the singular mind when it comes to collecting, understanding and then synthesizing research. Sharing every last scrap of information we could find with each other, was essential, as it kind of helped us prepare mentally for the ideation process. </p>
</div>
</div>
</section>

</div>
<div class="post wrapper">
<div class="col-sm-8">
<article class="post-content">

<h2>Findings</h2>
 We found out through interviews with both field workers and the backoffice, that sometimes tasks were too ill-informed to be fully completed or even comprehended. This was true for both sides of the coin, as field workers sometimes didn’t have enough information or might have missed a step when marking a job as completed.

<div class="box">
	Had enough of me talking? Well I really like to go into depth, but if you don’t feel like reading the rest of this it’s cool. Let’s go <a href="#goodstuff" style="color: #02E16B;">see the good stuff</a> shall we?.
</div>

<p>This led to backoffice staff misperceiving whether a task had been completed or not, having to make calls which as a result made them less productive and also less likely to be responsive to emergency calls. </p>

<p>Naturally this back and forth resulted in a growing frustration which we had to tend to. This problem is important to solve because if a workforce is not productive, then not only may there be considerable revenue decrease from the business end, but business customers might also opt to switch supplier. </p>

<img src="img/opendispatch_userflow.png" alt="Some research notes from this project" style="border: none; width: 100%;">
<figcaption>This may look chatoic, but trust me this was controlled chaos. By referring to this user flow for task completion we knew where our focus had to go and what glaring painpoints we had to immediately address.</figcaption>

<!-- Ideation -->
</article>
</div>
</div>

<section class="feature__context">
<div class="wrapper">
<div class="col-sm-8">
<h2 style="color: #23E16C;">Ideation</h2>
<p>One thing that we agreed on is that we knew that whatever we put out there, we weren’t going to get it right the first try. And we were okay with that. That said, we were going to try our darndest to build something that could give us value when testing.</p>

<p>Knowing that our end-users (I prefer <em>people</em>) were sometimes going to be on the road or in motion when interacting with the product, I needed to keep in mind Fitt’s law — the larger the target, the less time needed to tap it.   Whilst sketching I asked myself <strong>three questions</strong>: 
<ul>
	<li>Who is this for?</li>
	<li>What value will this deliver</li>
	<li>Where do I go from here?</li>
</ul>
</p>

<p>We knew that most of our efforts needed to go towards the task flow, because that’s where field workers need to get their work done. Thus, by improving the experience of the task flow, we can better address the issues faced by both backoffice staff and field agents.</p>
</div>
<img src="img/opendispatch_sketches.png" alt="Some sketches from Open Dispatch" style="width: 100%; margin: 0 auto;">
<figcaption>My sketching skills aren’t the best,  but they were enough to communicate  my intentions with the engineering team.</figcaption>
</div>
</div>
</section>

</div>
<div class="post wrapper">
<div class="col-sm-8">
<article class="post-content">

<!-- ////////////////// -->

<h2 id="goodstuff">Solution and Design Decisions</h2>
<p>We chose to leverage Google’s Material Design language because as a team we felt that it gives us the comprehensiveness and flexibility we needed, to be able to communicate depth and motion when necessary throughout the different elements and interactions we incorporated into the product.</p>

</div>
<h4 class="transparent mb-0">Navigation to a task</h4>
<img src="img/opendispatch_solution1.png" alt="Some sketches from Open Dispatch" style="width: 100%;" class="m-45">
<div class="col-sm-8">
<p>One thing I had to make sure of in these views was to show only the necessary information, and nothing else. I didn’t want for the field workers to take too much time in parsing the screen and to get started by navigating to their destination. </p>
</div>
<h4 class="transparent mb-0">Taskflow (Iteration 1)</h4>
<img src="img/taskflow_iteration1.png" alt="Some sketches from Open Dispatch" style="width: 100%;" class="m-45">
<div class="col-sm-8">
<p>For the actual task flow, there were two iterations. The first of which you can see above, which took up the entirety of the screen and made use of the stepper component in the material guidelines. I felt that this was less congested, simpler and more flexible if more difficult task items were to be introduced. </p> 
</div>
<h4 class="transparent mb-0">Taskflow (Iteration 2)</h4>
<img src="img/taskflow_iteration2.png" alt="Some sketches from Open Dispatch" style="width: 100%;" class="m-45">
<div class="col-sm-8">
<p>In this iteration I was thinking, why not keep it progressive and more gradual rather than taking you to a completely different view? After all, it was task completion time that was amongst the defining metrics to success. </p>

<p>By keeping everything on one screen, seperating the sub-tasks into logically ordered steps, there was a sense of coherence. One thing I had to compromise on however, was the lightweightedness of the first solution.</p>

<!-- Prototyping -->
</article>
</div>
</div>

<section class="feature__context">
<div class="wrapper">
<div class="col-sm-8 col-xs-12">
	<h2 style="color: #23E16C;">
		Prototyping
	</h2>
<p>Tight deadlines hadn’t allowed me enough space to prototype microinteractions, but that didn’t stop me from stitching a few static mockups together in Marvel and validating my ideas. They were far from perfect, but hey I guess that’s why they’re called prototypes.</p>

<p>An interesting discussion that arose from seeing these two iterations side by side was pereceived time to complete versus actual time to complete. When we tested the iterations side by side and looked at how field agents were responding to both, we noticed that there was a small hint of frustration with the first direction even though it took slightly less time to complete.  </p>

<iframe src="https://marvelapp.com/1e1ia78?emb=1" allowTransparency="true" frameborder="0" class="center prototype "></iframe>

<p>One field worker told me that even though it was pretty straightforward, it still felt it was “a bit long-winded”. The reaction was mixed, but the team and I had deliberated that it was better if we valued how people felt since the time to complete was negligible. Even though half a second counts in this business, a happier worker is a more productive and proactive worker. Had I more time I would have used something like Framer or Principle to communicate more complex interactions, but deadlines and all that you know. </p>

</div>
</div>
</section>

</div>
<div class="post wrapper">
<div class="col-sm-8">
<article class="post-content">

<!-- ////////////////// -->


<h2>Takeaways</h2>
<p>Unfortunately our work never saw the light of day (unless you count the people we had asked to come in for testing) because the plug was pulled on this product.   As a result of this I’ve learnt that industries such as this come with a different host of topics, areas and issues that will need to be considered when architecting a solution. It was strange. </p>

<p>Being exposed to failure this early on in my career was something that I never expected after graduation.   Pushing the value of design in an area with a lot of friction, whilst mostly being exposed to people designing in the consumer space who were getting much less resistance, was another challenge. But hey, what’s building something without roadblocks?</p>




     

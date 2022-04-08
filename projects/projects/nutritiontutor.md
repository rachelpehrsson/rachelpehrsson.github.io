---
title: "Decoding Nutrition Labels"
date: 2022-01-12T22:28:30-05:00
draft: true
---

Decoding Nutrition Labels is a rule-based cognitive tutor for teaching 6th graders to read nutrition labels on food and glean information about nutrient content. It was built using [CTAT](http://ctat.pact.cs.cmu.edu/), a cognitive tutor authoring tool developed at Carnegie Mellon written in Nools.js. 

We based our design on a worksheet that helped students decode nutrition labels and then confirmed the process with a nutrition expert. We used the worksheet in a Cognitive Task Analysis (CTA) using 6th grade students and others who had never read an American nutrition label (international students) in order to determine their pain points and preferences. 

After our CTA and prototyping, I implemented our tutor using CTAT, which uses Nools, a rule-based engine written in Javascript. I used both the primary CTAT functionality and custom Javascript to implement behavior unique to our tutor, such as the multi-page navigation. 

Students can select a food item from the first page and then progress through the various steps with that item's nutrition label.

<div class = "labeled-image">
<img src="/img/nt-foodselection.png" alt="Responsive image">
<div class = "label">The opening screen, where the student chooses the food item</div>
</div>

After the first iteration, we tested it with 6th grade students and compared their results to the paper test. The tutor went through some design changes during testing. For instance, the initial version included a glossary of health terms used throughout the tutor. However, the test subjects didn't use or even ask about the glossary, so we removed it and instead showed relevant information in the sidebar. 


<div class = "labeled-image">
<div class = "images">
<div class = "image">
<img src="/img/nt-glossary.png" alt="Responsive image">
</div>
<div class="image">
<img src="/img/nt-task2.png" alt="Responsive image">
</div>
</div>
<div class = "label">Screen with glossary (first iteration) vs Relevant Information</div>
</div>

The tutor included step-specific hints. We also chose to reduce the cognitive load on the students by automatically performing math functions as they progressed. 
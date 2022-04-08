---
title: "Dynamic Quiz"
date: 2022-01-17T23:36:08-05:00
draft: true
---

My Distinguished Major Project at the University of Virginia was a dynamic quiz system that adjusted practice content based on interaction with the student. It addressed a problem within the computer science department at the University of Virginia, as well as other institutions; the department classroom size is scaling, but the number of TA’s is not expanding at the same rate. Therefore, it is important to test whether certain aspects of personalized help can be automated. 

The project began with a literature review that addressed existing theories on adaptive learning and the measuring of mastery. Furthermore, I looked into studies by UVA professors that informed how the content of the instruction should be structured. 

The quiz is an online tool with a series of multiple-choice questions. The system is built using HTML, Javascript, PHP, and MySQL. For the experimental version, students were given extra practice questions of the needed category depending on whether they answered questions wrong or used hints. The following diagram shows how the quiz questions are supplied to the student:

<div class = "labeled-image">
<img src="/img/DynamicQuizAlgo.png" alt="Responsive image">
<div class = "label">How the quiz responds to right/wrong answers</div>
</div>

The questions were separated into categories that the students progressed through. They were given a lecture before the practice questions. 

<div class = "labeled-image">
<img src="/img/quizlayout.png" alt="Responsive image">
<div class = "label">Quiz Interface</div>
</div>

Hint functionality was provided and, as previously mentioned, included in the algorithm to determine student mastery. 

<div class = "labeled-image">
<img src="/img/quizhints.png" alt="Responsive image">
<div class = "label">Hints helped students along but counted against them for mastery</div>
</div>



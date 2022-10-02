---
title: "NHH ECS530 2022 course: Spatial data analysis (with R)"
author: "Roger Bivand"
date: "September - November 2022"
output: 
  html_document:
theme: united
---

### Course information (2 October)

An introduction to materials for topic IIa is online at: https://rsbivand.github.io/ECS530_h22/ECS530_22_IIa.html.

### Updated course information (12 September)

Both this guide and introductions to materials will evolve over time. While working on the "flipped" modules, I realised that II would be too full, so I suggest splitting II into IIa spatial autocorrelation and IIb spatial regression. It remains the case that representation and visualization are both large topics, but they are better supported in the available materials.

### Course information (9 September)

We will meet for short 2-3 hour sessions on Tuesdays 09:00-12:00 CEST: 20 September (Aud. J), 4 and 18 October (both Aud. F) and 1 November (Aud. G, CET - winter time); zoom link to follow for off-site participants. We will not use all three hours, but we have time for set-up and breaks with the three hour room reservation slots. The zoom link will be posted in a Canvas announcement, and emailed only the first time to any not yet active in Canvas.

The course is partly "flipped" out of caution - you will all have the oportunity to learn quite a lot before we meet 14 November anyway. Should anything unexpected hinder our meeting 14-18 November, we should then be better placed to complete the course properly, than if no preparatory work has been completed. The intention remains that the 14-18 November week is intensive and on-site for all who require credits.

You are expected to work using online materials largely in Canvas between 20 September and 4 October on topic I: spatial data representation and visualization, and between 4 and 18 October on topic II: spatial autocorrelation and introductory spatial regression. An introduction to materials for topic I is online at: https://rsbivand.github.io/ECS530_h22/ECS530_22_I.html.

There is time for slippage if anyone is delayed in getting access to Canvas, but by 14 November everyone is expected to be well prepared, and to have a good idea which short project to conduct to present for input from other participants and if credits are required for evaluation.

On 20 September, I'll introduce the course structure, and answer your questions about the way the course is organised. Because videos, articles and books are largely only available in Canvas, access to Canvas is essential.

In addition, please think through topics that you would like to go into in more depth during the 14-18 November week, as what we cover can be adapted to your needs.

### Course structure

Combined lectures and computer practicals, concluding with draft project presentations on final days (more than one day needed given interest in the course). Participants use their own laptop computers. Autumn semester 2022: on-site talks will be streamed and recorded. It may be possible to observe remotely, but for those able to travel to Bergen, interaction with other participants will be much more fruitful.

The course is moving towards a module-based course with modules: 

- 0 introduction (week 38, 2 hours 20 September 9.00-12.00);

- Studying materials prior to QA/discussion at I

- I spatial data representation and visualization (week 40, 2 hours 4 October 9.00-12.00); 

- Studying spatial data representation and visualization materials prior to QA/discussion at IIa

- IIa spatial autocorrelation (week 42, 2 hours 18 October 9.00-12.00); 

- Studying spatial autocorrelation materials prior to QA/discussion at IIb

- IIb spatial regression; introduction to project/term-paper process (week 44, 2 hours 1 November 9.00-12.00)

- Studying spatial regression materials prior to QA/discussion at III, preparation of project topics

- III advanced topics in spatial data analysis (on-site week 46, 14-18 November). 

Modules 0-IIb by zoom and on-site for those based in Bergen, module III on-site and streamed/recorded, but off-site participants just observe; for credits, on-site participation is required unless the institution is obliged to close the campus for example because of lock-down.

Module 0 is to coordinate participants, and in particular to lets us shape the contents of module III. Since an important part of the work will be done before the intensive week, ensuring that everyone is on board matters.

Modules I, IIa and IIb are "flipped" based on recorded talks, materials and exercises, so interaction prior to the intensive week is to answer immediate questions and discussion topics raised by participants. The pre-III slot is to provide opportunities to discuss the individual project/term paper that has to be submitted (in early January 2023, date to be confirmed) for assessment if participants wish to gain ECTS credits - more details in [Project requirements](https://rsbivand.github.io/ECS530_h22/project_report_requirements.html) and [Evaluation guide](https://rsbivand.github.io/ECS530_h22/evaluation_guide.html).

Course-internal communication will be on Canvas, requiring a login issued after registration. Zoom links for I, II and pre-III will be published on Canvas; for 0, both Canvas and by email for any participants not yet in Canvas.

### Provisional course details

These may be changed. Links to materials to follow.

A PhD-level course in spatial data analysis will be held 14-18 November 2022 in Bergen, Norway (quasi-hybrid format):

https://www.nhh.no/en/courses/analysing-spatial-data/

Three short "flipped" two-hour sessions will be held in September and October online for remote participants (these will be based on own study). Intensive follow-up sessions will follow on-site in November permitting interaction between participants.

External participants should apply using this form, best well before the 1 September deadline to permit processing before the first short session:

https://www.nhh.no/en/study-programmes/phd-programme-at-nhh/phd-courses/become-a-visiting-student-at-a-phd-course-at-nhh/

For further details see the course page; participants must cover their own travel and living costs; no support is offered, I'm afraid, apart from free tuition.

### Links to materials:

(to follow)



Installing packages not yet on your system:

```
inst <- match(needed, .packages(all=TRUE))
need <- which(is.na(inst))
if (length(need) > 0) install.packages(needed[need])
```

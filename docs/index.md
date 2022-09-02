---
title: "NHH ECS530 2022 course: Spatial data analysis (with R)"
author: "Roger Bivand"
date: "14-18 November 2022"
output: 
  html_document:
theme: united
---

### Provisional course details

These may be changed. Links to materials to follow.

A PhD-level course in spatial data analysis will be held 14-18 November 2022 in Bergen, Norway (quasi-hybrid format):

https://www.nhh.no/en/courses/analysing-spatial-data/

Three short "flipped" two-hour sessions will be held in September and October online for remote participants (these will be based on own study). Intensive follow-up sessions will follow on-site in November permitting interaction between participants.

External participants should apply using this form, best well before the 1 September deadline to permit processing before the first short session:

https://www.nhh.no/en/study-programmes/phd-programme-at-nhh/phd-courses/become-a-visiting-student-at-a-phd-course-at-nhh/

For further details see the course page; participants must cover their own travel and living costs; no support is offered, I'm afraid, apart from free tuition.

### Course structure

Combined lectures and computer practicals, concluding with draft project presentations on final day. Participants use their own laptop computers. Autumn semester 2022: the talks will be streamed and recorded. It may be possible to observe remotely, but for those able to travel to Bergen, interaction with other participants will be much more fruitful.

The course is moving towards a module-based course with modules: 

- 0 introduction (week 38, 2 hours 20 September (time to follow));

- Studying materials prior to QA/discussion at I

- I spatial data representation and visualization (week 40, 2 hours 4 October (time to follow)); 

- Studying materials prior to QA/discussion at II

- II spatial autocorrelation and regression (week 42, 2 hours 18 October (time to follow)); 

- Studying materials prior to QA/discussion at III

- pre-III consultation slot (week 44, 2 hours 1 November (time to follow))

- III advanced topics in spatial data analysis (on-site week 46, 14-18 November). 

Modules 0-II by zoom and on-site for those based in Bergen, module III on-site and streamed/recorded, but off-site participants just observe; for credits, on-site participation is required unless the institution is obliged to close the campus for example because of lock-down.

Module 0 is to coordinate participants, and in particular to lets us shape the contents of module III. Since an important part of the work will be done before the intensive week, ensuring that everyone is on board matters.

Modules I and II are "flipped" based on recorded talks, materials and exercises, so interaction prior to the intensive week is to answer immediate questions and discussion topics raised by participants. The pre-III slot is to provide opportunities to discuss the individual project/term paper that has to be submitted (in early January 2023, date to be confirmed) for assessment if participants wish to gain ECTS credits - more details in [Project requirements](https://rsbivand.github.io/ECS530_h22/project_report_requirements.html) and [Evaluation guide](https://rsbivand.github.io/ECS530_h22/evaluation_guide.html).

Course-internal communication will be on Canvas, requiring a login issued after registration. Zoom links for I, II and pre-III will be published on Canvas; for 0, both Canvas and by email for any participants not yet in Canvas.

### Links to materials:

(to follow)



Installing packages not yet on your system:

```
inst <- match(needed, .packages(all=TRUE))
need <- which(is.na(inst))
if (length(need) > 0) install.packages(needed[need])
```

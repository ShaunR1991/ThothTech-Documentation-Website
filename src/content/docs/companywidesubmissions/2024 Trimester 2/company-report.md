---
title: Thoth Tech – Company Report 2024 TRIMESTER 2
description: 11.2P Task, T2 2024
tableOfContents: false
---

# Table of Contents

[1. Executive Summary](#executive-summary)

[2. Showcase Video](#showcase-video)

[3. Leadership Team](#leadership-team)

> [3.1 Company Board](#company-board)

> [3.2 Product Mentors](#product-mentors)

> [3.3 Student Leaders](#student-leads)

> [3.4 Leadership Responsibilties](#leadership-responsibilities)

[4. Company Structure](#company-structure)

[5. Project 1: OnTrack](#project-1-ontrack)

> [5.1 Project Overview](#project-overview)

> [5.2 User Manual](#user-manual)

> [5.3 Completed Deliverables](#completed-deliverables)

> [5.4 Roadmap](#roadmap)

> [5.5 Open Issues](#open-issues)

> [5.6 Lessons Learned](#lessons-learned)

> [5.7 Product Development Life Cycle](#product-development-life-cycle)

> > [5.7.1 New Tasks](#new-tasks)

> > [5.7.2 Definition of Done](#definition-of-done)

> > [5.7.3 Task Review](#task-review)

> > [5.7.4 Testing](#testing)

> > [5.7.5 Branching Strategy](#branching-strategy)

> [5.8 Product Architecture](#product-architecture)

> > [5.8.1 UML Diagram](#uml-diagram)

> > [5.8.2 Tech Stack](#tech-stack)

> [5.9 Source Code](#source-code)

> [5.10 Login Credentials](#login-credentials)

> [5.11 Other Relevant Information](#other-relevant-information)

> [5.12 Appendices](#appendices)

[6. Project 2: SplashKit](#project-2-splashkit)

> [6.1 Project Overview](#project-overview-1)

> [6.2 User Manual](#user-manual-1)

> [6.3 Completed Deliverables](#completed-deliverables-1)

> [6.4 Roadmap](#roadmap-1)

> [6.5 Open Issues](#open-issues-1)

> [6.6 Lessons Learned](#lessons-learned-1)

> [6.7 Product Development Life Cycle](#product-development-life-cycle-1)

> > [6.7.1 New Tasks](#new-tasks-1)

> > [6.7.2 Definition of Done](#definition-of-done-1)

> > [6.7.3 Task Review](#task-review-1)

> > [6.7.4 Testing](#testing-1)

> > [6.7.5 Branching Strategy](#branching-strategy-1)

> [6.8 Product Architecture](#product-architecture-1)

> > [6.8.1 UML Diagram](#uml-diagram-1)

> > [6.8.2 Tech Stack](#tech-stack-1)

> [6.9 Source Code](#source-code-1)

> [6.10 Login Credentials](#login-credentials-1)

> [6.11 Other Relevant Information](#other-relevant-information-1)

> [6.12 Appendices](#appendices-1)

# Executive Summary

Thoth Tech is an education-focused technology company located in Melbourne, Australia. Thoth Tech’s
mission is to build, operate, and deploy tools that enhance education outcomes by empowering
students, connecting them with tutors, and facilitating personalised learning experiences.

We value excellence and collaboration. We strive to deliver all our products in exceptional quality,
making sure it is sustainable in the long run. We continuously meet this goal while empowering our
people through established frameworks and a safe and supportive learning environment.

In Trimester 2, 2024, Thoth Tech ran its two main products: OnTrack, and SplashKit. This report will
outline the company structure, projects, and accomplishments for this trimester.

# Showcase Video

This video summarises the accomplishments made at Thoth Tech for Trimester 2, 2024: **_ TODO _**
[Thoth Tech Company Showcase Video](//todo)

# Leadership Team

## Company Board

- Andrew Cain - Director, Product Owner (OnTrack & SplashKit)

## Product Mentors

- Satika Jayawardena (OnTrack)
- Nebula Alam (OnTrack)
- Tien Pham (SplashKit)
- Olivia McKeon (SplashKit)
- Sean Boettger (SplashKit)

## Student Leads

- Jake Mansfield – Student Lead (OnTrack)
- Jack Carroll – Student Lead (OnTrack)
- Atharv Bhandare – Junior Leader (OnTrack)
- Bruce Wang – Senior Leader (OnTrack)
- Ivan Justin – Junior Leader (OnTrack)
- Eliya Geerlings – Junior Leader (OnTrack)
- Jonathan Tynan – Student Lead (SplashKit)
- Oscar Harris – Student Lead (SplashKit)
- Hayley Hughes – Student Lead (SplashKit)
- Shaun Ratcliff – Junior Leader (SplashKit)
- Brianna Laird – Junior Leader (SplashKit)

## Leadership Responsibilities

The following are the key responsibilities of the company student leadership team throughout the
trimester:

1. Company presentation in the first junior lecture – Introduce the company, its projects, and
   required skill sets for potential junior students

   - Student leads must prepare and organise a PowerPoint presentation representing each of their
     projects during Week 0

2. Host first company-wide meeting and onboard students – Provide a more specific overview of
   company and project goals, meeting schedules, and expectations for the trimester

   - Team building sessions may also be organised to build rapport across teams

3. Weekly company leadership team meeting – Report on project progress and concerns to company
   stakeholders

   - Date and time to be decided by members in the first week according to availability

4. Complete company tasks: progress, handover, and showcase reports and videos
   - These reports must be submitted by 1 senior and 1 junior on behalf of the company and
     appropriate communications must be made on Teams

All past company reports, showcase videos, and relevant assets can be found here:
[Company Documents & Videos]() (//to do) &
[Thoth Tech Documentation Website](https://thoth-tech.netlify.app)

# Company Structure

![Org chart](https://raw.githubusercontent.com/thoth-tech/ThothTech-Documentation-Website/refs/heads/main/public/company-structure/2024-t2-thoth-tech-structure.png)

# Project 1: OnTrack

## Project Overview

OnTrack, also known as Doubtfire, is an innovative Learning Management System (LMS) tailored for skill-based course delivery. This platform facilitates the connection between tutors and students, primarily at Deakin University and other global institutions. The overarching goal of OnTrack is to enhance the educational experience by providing a structured, efficient, and interactive learning environment. This system aims to improve student engagement, learning outcomes, and the overall teaching and learning process, benefiting both students and educational staff. 

## User Manual

Tutorial videos on setting up your local development environment: 

- [T3 2023 Setup demo](https://deakin365.sharepoint.com/:v:/s/ThothTech2/ESrgw0W_21pLn7kqS86WoJgBG71EPo7VPSp8AXt151JC2g?e=AZyu7I)  by Satika Jayawardena

- [T2 2023 Setup demo](https://video.deakin.edu.au/media/t/1_6degiyrj)  by Daniel Maddern

- [T1 2024 Common setup error solutions](https://teams.microsoft.com/l/message/19:bd20175d09414f079490a2403f7fca74@thread.tacv2/1711021331051) by Satika Jayawardena 

Contributing Guides: 

- [Doubtfire-deploy repository](https://github.com/thoth-tech/doubtfire-deploy/blob/development/CONTRIBUTING.md)

- [OnTrack documentation](https://github.com/thoth-tech/documentation/tree/main/docs/OnTrack)

- [Thoth Tech Documentation Website](https://main--strong-fairy-c1bde1.netlify.app/products/ontrack/example/)

## Completed Deliverables

This trimester, the following key deliverables were completed:
- Bug Fixes and Urgent Enhancements

  - Chat Markdown Rendering Bug: Successfully fixed an issue where markdown was not rendering properly in chat, enhancing the user experience for students and staff.
  - Documentation Enhancements: Completed and merged documentation updates for both general and specific API pages. This includes contributions from team members on various entities such as requirement sets and course entities, directly supporting the goal of comprehensive documentation for OnTrack's evolving features.

- Frontend Enhancements and Component Migrations: Several components have been successfully migrated to Angular 17 and TypeScript, including the comments-modal, group set manager, and unit-ilo-edit-modal. Additionally, enhancements were made to PDF handling and user interface elements like the grade-task-modal and grade-icon components, contributing to the ongoing frontend migration and user interface improvement objectives.
  - Ongoing Frontend Migration: The migration of legacy CoffeeScript components to TypeScript/Angular continues, with files such as timeout.coffee and grade-task-modal.coffee currently under peer review. This aligns with our aim to complete at least 10% of the existing frontend migration backlog this trimester.
  - Overlay Component Creation: Developed a new overlay component to provide additional information about units to users, enhancing the user interface and experience. This feature is currently under review.

- CourseFlow:

  - CourseMap Base Page Development: Developed the base page for CourseMap, laying the groundwork for further enhancements and integrations planned for the CourseFlow component.
  - Backend Requirements Implementation: Completed backend requirements for several critical entities, including the requirement set, course, and course map unit entities. These efforts are part of the overarching aim to enhance CourseFlow functionality and ensure robust backend support for new and existing features.
  - CourseFlow Enhancements: Several enhancements are under review, including adding authentication to endpoints and integrating new UI elements. These efforts are part of the continued development of the CourseFlow API and its related functionalities.

- JPLAG - jplag software plagiarism has been implemented as a containerised batch process. Frontend and backend additions have been made to allow plagiarism report downloads.
- Dev Container Image Downsizing - LaTex and MariaDB have been moved into their own containers; reducing rebuild time of the main container significantly
- Nginx - an nginx container has been created to utilise reverse proxying, allowing localhost:4200 and localhost:3000 to be accessed at localhost/ and localhost/api

- Ongoing and Pending Tasks:

  - Group Set Manager Migration: The migration of the group set manager component to the latest framework is in progress.
  - Unit Group Set Editor Migration: The migration of the unit-group-set-editor.coffee file continues to move forward, aligning with our frontend migration goals.
  - Tasks in Peer Review: Detailed documentation and API operations for units and task definitions, along with the migration of several legacy components, are currently under peer review. This work supports the ongoing documentation efforts and frontend migration initiatives.

| Name | Task Name | Task Attachment |
|---|---|---|
| Amos Saji | Migration: group set manager | https://github.com/thoth-tech/documentation/pull/549<br>https://github.com/thoth-tech/doubtfire-web/pull/244 |
| Amrith Jayadeep | Migration: group set selector | https://github.com/thoth-tech/documentation/pull/544/commits/6789b275af1deb663877b8953f229c5277582e59<br>https://github.com/thoth-tech/doubtfire-web/pull/239 |
| Anirudh Nellippilli Joshi | Documentation: grade-task-modal component review | https://github.com/thoth-tech/documentation/pull/525 |
| Anirudh Nellippilli Joshi | migrate file-uploader.coffee | https://github.com/thoth-tech/documentation/pull/535/files<br>https://github.com/thoth-tech/doubtfire-web/pull/246/commits/28a77cd0821ce9b66a43c47741cda35c39132fd2 |
| Anirudh Nellippilli Joshi | Migration: group set selector | https://github.com/thoth-tech/documentation/pull/544/commits/6789b275af1deb663877b8953f229c5277582e59<br>https://github.com/thoth-tech/doubtfire-web/pull/239 |
| Anirudh Nellippilli Joshi | Migration: group set manager | https://github.com/thoth-tech/documentation/pull/549<br>https://github.com/thoth-tech/doubtfire-web/pull/244 |
| Anirudh Nellippilli Joshi | Migration: csv-result-modal.coffee | https://github.com/thoth-tech/documentation/pull/524#issue-2441710229<br>https://github.com/thoth-tech/doubtfire-web/pull/248/commits/b0c23fa084e074feec9cfd4618d2e2ff9412f2c7 |
| Anirudh Nellippilli Joshi | Onboarding Juniors Guidence | https://github.com/thoth-tech/documentation/pull/551 |
| Atharv Sandip Bhandare | Migration: comments-modal | https://github.com/doubtfire-lms/doubtfire-web/pull/869<br>https://github.com/thoth-tech/documentation/pull/519<br>https://github.com/thoth-tech/doubtfire-web/pull/218 |
| Atharv Sandip Bhandare | Write documentation for JPLAG | https://github.com/thoth-tech/documentation/pull/528<br>https://www.github.com/JackSCarroll/documentation/blob/JplagDocs/docs/OnTrack/JPlag/Jplag-Feasibility-Document.md |
| Atharv Sandip Bhandare | Migration: Component task-ilo-alignment-modal.coffee |  |
| Atharv Sandip Bhandare | Add user UI does not allow user creation | https://github.com/thoth-tech/documentation/pull/556<br>https://github.com/thoth-tech/doubtfire-web/pull/254 |
| Atharv Sandip Bhandare | Migration: unit-staff-editor.coffee | https://github.com/thoth-tech/documentation/pull/543<br>https://github.com/thoth-tech/doubtfire-web/pull/235 |
| Atharv Sandip Bhandare | JPLAG UI documentation | https://github.com/thoth-tech/documentation/pull/555 |
| Bruce Wang | Migration: comments-modal | https://github.com/doubtfire-lms/doubtfire-web/pull/869<br>https://github.com/thoth-tech/documentation/pull/519<br>https://github.com/thoth-tech/doubtfire-web/pull/218 |
| Bruce Wang | Documentation: grade-task-modal component review | https://github.com/thoth-tech/documentation/pull/525 |
| Bruce Wang | migrate file-uploader.coffee | https://github.com/thoth-tech/documentation/pull/535/files<br>https://github.com/thoth-tech/doubtfire-web/pull/246/commits/28a77cd0821ce9b66a43c47741cda35c39132fd2 |
| Bruce Wang | Migration: grade-icon.coffee | https://github.com/thoth-tech/doubtfire-web/pull/231 |
| Bruce Wang | Migrate analytics.coffee | https://github.com/thoth-tech/doubtfire-web/pull/256 |
| Bruce Wang | Migrate viewer.coffee | https://github.com/thoth-tech/doubtfire-web/pull/251 |
| Bruce Wang | Migration: timeout.coffee | https://github.com/doubtfire-lms/doubtfire-web/pull/868/commits/6a965ef9927837bd3e9e77d27b035473cd974215<br>https://github.com/thoth-tech/doubtfire-web/pull/230 |
| Bruce Wang | Migration: unauthorised.coffee | https://github.com/thoth-tech/doubtfire-web/pull/257 |
| Bruce Wang | Migration: unit-staff-editor.coffee | https://github.com/thoth-tech/documentation/pull/543<br>https://github.com/thoth-tech/doubtfire-web/pull/235 |
| Bruce Wang | Migration: csv-result-modal.coffee | https://github.com/thoth-tech/documentation/pull/524#issue-2441710229<br>https://github.com/thoth-tech/doubtfire-web/pull/248/commits/b0c23fa084e074feec9cfd4618d2e2ff9412f2c7 |
| Bruce Wang | Onboarding Juniors Guidence | https://github.com/thoth-tech/documentation/pull/551 |
| Eliya Geerlings | Migration: comments-modal | https://github.com/doubtfire-lms/doubtfire-web/pull/869<br>https://github.com/thoth-tech/documentation/pull/519<br>https://github.com/thoth-tech/doubtfire-web/pull/218 |
| Eliya Geerlings | Autoload PDFs on page 2 when viewing student submissions | https://github.com/thoth-tech/doubtfire-web/pull/232 |
| Eliya Geerlings | Fix jupyter notebook latex rake test | https://github.com/doubtfire-lms/doubtfire-api/pull/444 |
| Eliya Geerlings | Fix up existing confirmation-modal migration | https://github.com/doubtfire-lms/doubtfire-web/pull/870 |
| Eliya Geerlings | Latex docker downsizing: Creation of feasibility document | https://github.com/thoth-tech/documentation/pull/534 |
| Eliya Geerlings | Latex docker downsizing: Implementation | https://github.com/thoth-tech/doubtfire-api/pull/38<br>https://github.com/thoth-tech/doubtfire-deploy/pull/13 |
| Eliya Geerlings | Persistent PDF zoom levels when selecting between different task submissions | https://github.com/thoth-tech/doubtfire-web/pull/228 |
| Eliya Geerlings | Migration: unit-staff-editor.coffee | https://github.com/thoth-tech/documentation/pull/543<br>https://github.com/thoth-tech/doubtfire-web/pull/235 |
| Ivan Justin | Latex docker downsizing: Creation of feasibility document | https://github.com/thoth-tech/documentation/pull/534 |
| Ivan Justin | Chat markdown not rendering properly bug | https://github.com/thoth-tech/doubtfire-web/pull/250 |
| Ivan Justin | Migration: Unit-ilo-edit-modal.coffee | https://github.com/thoth-tech/documentation/pull/526<br>https://github.com/thoth-tech/doubtfire-web/pull/226 |
| Jack Shinners Carroll | Write documentation for JPLAG | https://github.com/thoth-tech/documentation/pull/528<br>https://www.github.com/JackSCarroll/documentation/blob/JplagDocs/docs/OnTrack/JPlag/Jplag-Feasibility-Document.md |
| Jack Shinners Carroll | Documentation: grade-task-modal component review | https://github.com/thoth-tech/documentation/pull/525 |
| Jack Shinners Carroll | Latex docker downsizing: Creation of feasibility document | https://github.com/thoth-tech/documentation/pull/534 |
| Jack Shinners Carroll | Latex docker downsizing: Implementation | https://github.com/thoth-tech/doubtfire-api/pull/38<br>https://github.com/thoth-tech/doubtfire-deploy/pull/13 |
| Jack Shinners Carroll | Migrate analytics.coffee | https://github.com/thoth-tech/doubtfire-web/pull/256 |
| Jack Shinners Carroll | Migration: unit-staff-editor.coffee | https://github.com/thoth-tech/documentation/pull/543<br>https://github.com/thoth-tech/doubtfire-web/pull/235 |
| Jack Shinners Carroll | Add JPLAG frontend | https://github.com/doubtfire-lms/doubtfire-web/pull/873 |
| Jack Shinners Carroll | Alter JPLAG api code | https://github.com/doubtfire-lms/doubtfire-api/pull/447 |
| Jack Shinners Carroll | Create JPLAG Container | https://github.com/doubtfire-lms/doubtfire-deploy/pull/28 |
| Jack Shinners Carroll | JPLAG UI documentation | https://github.com/thoth-tech/documentation/pull/555 |
| Jake Mansfield | Document the below API pages in detail within the website - set 5 | https://github.com/thoth-tech/doubtfire-astro/pull/9 |
| Jake Mansfield | Implement the backend requirements for the course entity. | https://github.com/thoth-tech/doubtfire-api/pull/34 |
| Jake Mansfield | Implement the backend requirements for the course map entity. | https://github.com/thoth-tech/doubtfire-api/pull/35 |
| Jake Mansfield | Implement the backend requirements for the course map unit entity. | https://github.com/thoth-tech/doubtfire-api/pull/35 |
| Jake Mansfield | Implement the backend requirements for the requirement set entity. | https://github.com/thoth-tech/doubtfire-api/pull/37 |
| Jake Mansfield | Implement the backend requirements for the specialization entity. |  |
| Jake Mansfield | Add detailed operations for units API (task_definitions -tii_group_attachments ) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/12 |
| Jake Mansfield | Add Authentication to the Courseflow endpoints |  |
| Jake Mansfield | Add button to Courseflow main component | https://github.com/thoth-tech/doubtfire-web/pull/227 |
| Jake Mansfield | Created coursemap base page | https://github.com/thoth-tech/doubtfire-web/pull/233 |
| Jake Mansfield | Add detailed operations for units API (task_definitions) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/12 |
| Jake Mansfield | Add detailed operations for units API (group set - group ID) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Jake Mansfield | Add detailed operations for units API (group set - group csv) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Jake Mansfield | Add detailed operations for units API (task_definitions - task_assessment_resources ) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/13 |
| Jake Mansfield | Document the operations units API - Tutorial Streams | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Jake Mansfield | Ensure Unit Definition model satisfies all requirements (Phase 2) |  |
| Jake Mansfield | Create appropriate testing files for the Unit Definition entity (Phase 1) | https://github.com/thoth-tech/doubtfire-api/pull/42 |
| Jake Mansfield | Create dummy data for a specific course for the front end to use (Phase 3) | https://github.com/thoth-tech/doubtfire-api/pull/43 |
| Jake Mansfield | Implement the backend requirements for the Unit Definition entity (phase 1) | https://github.com/thoth-tech/doubtfire-api/pull/42 |
| Jake Mansfield | Make a Plan for Courseflow for T2 |  |
| Jake Mansfield | Migrate analytics.coffee | https://github.com/thoth-tech/doubtfire-web/pull/256 |
| Jake Mansfield | Migrate the existing Unit table to be compatible with Unit Definition (Phase 4) | https://github.com/thoth-tech/doubtfire-api/pull/41 |
| Jake Mansfield | Migration: timeout.coffee | https://github.com/doubtfire-lms/doubtfire-web/pull/868/commits/6a965ef9927837bd3e9e77d27b035473cd974215<br>https://github.com/thoth-tech/doubtfire-web/pull/230 |
| Jake Mansfield | Courseflow Documentation Requirement Analysis | https://github.com/thoth-tech/doubtfire-astro/pull/14 |
| Jake Mansfield | Onboarding Juniors Guidence | https://github.com/thoth-tech/documentation/pull/551 |
| Minu Nediyapalackal Sunil | Document the below API pages in detail within the website - set 5 | https://github.com/thoth-tech/doubtfire-astro/pull/9 |
| Minu Nediyapalackal Sunil | Add detailed operations for units API (task_definitions -tii_group_attachments ) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/12 |
| Minu Nediyapalackal Sunil | Add detailed operations for units API (task_definitions) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/12 |
| Minu Nediyapalackal Sunil | Create diagram of coursemap page | https://github.com/thoth-tech/doubtfire-astro/pull/11 |
| Minu Nediyapalackal Sunil | Add detailed operations for units API (group set - group ID) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Minu Nediyapalackal Sunil | Add detailed operations for units API (group set - group csv) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Minu Nediyapalackal Sunil | Add detailed operations for units API (task_definitions - task_assessment_resources ) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/13 |
| Minu Nediyapalackal Sunil | Document the operations units API - Tutorial Streams | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Minu Nediyapalackal Sunil | Pull the API docs from last trimester into the new folder structure | https://github.com/thoth-tech/doubtfire-astro/pull/15 |
| Minu Nediyapalackal Sunil | Courseflow Documentation Requirement Analysis | https://github.com/thoth-tech/doubtfire-astro/pull/14 |
| Muhammad Danial | Migration: Component task-ilo-alignment-modal.coffee |  |
| Sam Rolfe | Implement the backend requirements for the course entity. | https://github.com/thoth-tech/doubtfire-api/pull/34 |
| Sam Rolfe | Implement the backend requirements for the course map entity. | https://github.com/thoth-tech/doubtfire-api/pull/35 |
| Sam Rolfe | Implement the backend requirements for the course map unit entity. | https://github.com/thoth-tech/doubtfire-api/pull/35 |
| Sam Rolfe | Implement the backend requirements for the requirement set entity. | https://github.com/thoth-tech/doubtfire-api/pull/37 |
| Sam Rolfe | Implement the backend requirements for the specialization entity. |  |
| Sam Rolfe | Add Authentication to the Courseflow endpoints |  |
| Sam Rolfe | Add button to Courseflow main component | https://github.com/thoth-tech/doubtfire-web/pull/227 |
| Sam Rolfe | Created coursemap base page | https://github.com/thoth-tech/doubtfire-web/pull/233 |
| Sam Rolfe | Create a list of tasks for CourseMap FE |  |
| Sam Rolfe | Create diagram of coursemap page | https://github.com/thoth-tech/doubtfire-astro/pull/11 |
| Sam Rolfe | Ensure Unit Definition model satisfies all requirements (Phase 2) |  |
| Sam Rolfe | Migration: grade-icon.coffee | https://github.com/thoth-tech/doubtfire-web/pull/231 |
| Sam Rolfe | Add ability to add elective units to the unit pool (phase 2) | https://github.com/thoth-tech/doubtfire-web/pull/236 |
| Sam Rolfe | Create appropriate testing files for the Unit Definition entity (Phase 1) | https://github.com/thoth-tech/doubtfire-api/pull/42 |
| Sam Rolfe | Create dummy data for a specific course for the front end to use (Phase 3) | https://github.com/thoth-tech/doubtfire-api/pull/43 |
| Sam Rolfe | Create services and models for courseflow back end components. | https://github.com/thoth-tech/doubtfire-web/pull/252 |
| Sam Rolfe | Implement the backend requirements for the Unit Definition entity (phase 1) | https://github.com/thoth-tech/doubtfire-api/pull/42 |
| Sam Rolfe | Migrate the existing Unit table to be compatible with Unit Definition (Phase 4) | https://github.com/thoth-tech/doubtfire-api/pull/41 |
| Sam Rolfe | Populate remaining units container with relevant units from course (phase 2) | https://github.com/thoth-tech/doubtfire-web/pull/253 |
| Sam Rolfe | Courseflow Documentation Requirement Analysis | https://github.com/thoth-tech/doubtfire-astro/pull/14 |
| Shen Tian | Add button to Courseflow main component | https://github.com/thoth-tech/doubtfire-web/pull/227 |
| Shen Tian | Created coursemap base page | https://github.com/thoth-tech/doubtfire-web/pull/233 |
| Shen Tian | Create services and models for courseflow back end components. | https://github.com/thoth-tech/doubtfire-web/pull/252 |
| Shen Tian | Migrate analytics.coffee | https://github.com/thoth-tech/doubtfire-web/pull/256 |
| Shen Tian | Migration: timeout.coffee | https://github.com/doubtfire-lms/doubtfire-web/pull/868/commits/6a965ef9927837bd3e9e77d27b035473cd974215<br>https://github.com/thoth-tech/doubtfire-web/pull/230 |
| Shen Tian | Populate remaining units container with relevant units from course (phase 2) | https://github.com/thoth-tech/doubtfire-web/pull/253 |
| Shyama Chandrashekaran Pillai | Document the below API pages in detail within the website - set 5 | https://github.com/thoth-tech/doubtfire-astro/pull/9 |
| Shyama Chandrashekaran Pillai | Add detailed operations for units API (task_definitions -tii_group_attachments ) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/12 |
| Shyama Chandrashekaran Pillai | Add detailed operations for units API (task_definitions) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/12 |
| Shyama Chandrashekaran Pillai | Add detailed operations for units API (group set - group ID) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Shyama Chandrashekaran Pillai | Add detailed operations for units API (group set - group csv) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Shyama Chandrashekaran Pillai | Add detailed operations for units API (task_definitions - task_assessment_resources ) on Ontrack documentation website | https://github.com/thoth-tech/doubtfire-astro/pull/13 |
| Shyama Chandrashekaran Pillai | Document the operations units API - Tutorial Streams | https://github.com/thoth-tech/doubtfire-astro/pull/10 |
| Shyama Chandrashekaran Pillai | Pull the API docs from last trimester into the new folder structure | https://github.com/thoth-tech/doubtfire-astro/pull/15 |
| Thuy Tien Hoa | migrate file-uploader.coffee | https://github.com/thoth-tech/documentation/pull/535/files<br>https://github.com/thoth-tech/doubtfire-web/pull/246/commits/28a77cd0821ce9b66a43c47741cda35c39132fd2 |
| Thuy Tien Hoa | Migration: Component task-ilo-alignment-modal.coffee |  |
| Thuy Tien Hoa | Migration: grade-icon.coffee | https://github.com/thoth-tech/doubtfire-web/pull/231 |
| Thuy Tien Hoa | Add ability to add elective units to the unit pool (phase 2) | https://github.com/thoth-tech/doubtfire-web/pull/236 |
| Thuy Tien Hoa | Migrate viewer.coffee | https://github.com/thoth-tech/doubtfire-web/pull/251 |


## Roadmap

The following are areas of OnTrack students may choose to work on in Trimester 3, 2024: 
- Frontend Migrations – Angular.js and CoffeeScript to Angular and TypeScript 
- Urgent Enhancements, Improvements, and Bugs 
- Documentation Website – Enhance and add missing endpoint documentation 
- Peer reviews for previous pull requests and contributions 
- Features in development: 
  - Tutor Feedback Enhancement – feedback_api will require further development to support "criterion" or options 
  - CourseFlow – remaining backend entities and frontend 
  - Incorporate Multiple Organizations on Single OnTrack Server 
  - Authentication Module 
  - Tutor Times 
  - Incorporate Content in OnTrack 
  - Staff Grant Extensions 
  - Panopto Video Integration


## Open Issues

These are some of the common challenges we have faced in Trimester 2, 2024 and may 
continue to face in the future: 
1. Knowledge gap in using Git and GitHub – Team members are required to upskill in 
Git before starting on their assigned tasks as this is the primary tool used within the 
team to manage code and contributions. The Git and GitHub training website and 
demo videos attached in this document are some of the great resources available in 
capstone for this purpose. 

2. Unsatisfactory pull request reviews – Reviews must not be made through 
generational AI tools or just indicate how many commits have been made and what 
has changed. Instead, it must evaluate the syntax, logic, and output of the code. 
Please refer to section Task Review for more details and this past review for an 
example of a correct pull request review.


## Lessons Learned

This trimester, the traditional weekly Help Hub sessions, typically held on Thursdays and led by senior team members, experienced a noticeable decrease in attendance. 

To adapt, student leads focused on driving engagement and addressing queries through the OnTrack public Teams channel, encouraging team members to share their experiences and solutions. 

While this approach has been effective for accommodating team members' diverse schedules, we recommend exploring new ways to host Help Hub sessions alongside asynchronous Teams posts. Offering multiple formats for assistance could provide additional opportunities for leadership development.

Future student leads may consider using polls or forms to determine the most suitable time for sessions based on team availability. Additionally, offering a variety of session formats could help not only resolve existing problems but also guide team members in making contributions to specific areas.


## Product Development Life Cycle

We continue to use Agile methodologies to deliver updates and new features for OnTrack. 

Our approach includes 2-week sprints focused on completing tasks, and weekly stand-up meetings to assess progress, share updates, discuss roadblocks, and assign new tasks via Teams Planner cards.	

### New Tasks

New tasks are assigned by the project mentor during the weekly stand-up meetings. Once you are assigned a task, be sure to assign yourself to the corresponding Teams Planner card and attach your draft or completed pull request when you begin work.

If you have an idea for a new feature or enhancement, schedule a meeting with the project mentor to discuss it. Upon approval, create a new card or backlog column in Teams Planner to track the task. If the feature is large, start researching the benefits and challenges, and create a Spike document, which can be committed to the documentation repository. Spike templates are available in the documentation repository.


### Definition of Done

A task is considered complete once it has been fully tested, functions as expected, and is documented in a well-organized pull request. 

The task must also undergo peer review and be approved by your mentor. Ensure that the corresponding Teams Planner card is updated, and keep in communication with your reviewer and mentor until your contribution is merged into the upstream doubtfire-lms repository.

### Task Review

Each pull request requires a mandatory peer review before a mentor review. After creating the pull request, contact a teammate to review it. 

Tag them as the reviewer in both the Teams Planner card and the GitHub pull request. As a reviewer, ensure that you test the code by pulling the changes locally and reviewing the syntax, logic, and output. 

If any changes are needed, update the contribution and notify the reviewer. Once the updates are made, the pull request will be automatically updated.

After the peer review is complete, notify the mentor for their review. Once approved, you can submit the pull request to the upstream repository for the final review.

### Testing

For frontend changes, test the functionality in the browser or run specification tests as needed. For backend changes, use browser interactions or tools like Postman to test functionality. Additionally, GitHub CI Actions will run tests automatically when changes are pushed.

In the pull request template, include detailed instructions on how others can test your changes. Always provide before-and-after screenshots to show the outcome of your modifications.

### Branching Strategy

When starting a new contribution, fork all three thoth-tech repositories (deploy, web, and API) to your GitHub profile. 

Create a new branch from the development branch of the relevant repository. For example, for frontend migrations, you would create a branch from the doubtfire-web development branch. 

Follow the Branch Prefixes and Commit Message Format in the Contributing Guide when naming branches and creating commits.

## Product Architecture

OnTrack is built using four main components:
1.	Frontend Client: Responsible for user interactions.
2.	Backend API: Handles requests and serves data.
3.	Database: Stores application data.
4.	Deployment Infrastructure: Ensures that OnTrack is properly deployed and maintained

### Tech Stack

- Frontend: Currently being migrated from AngularJS and CoffeeScript to Angular 17 and TypeScript. The stack also includes HTML, SCSS, and Tailwind CSS.
- Backend: Built on Ruby on Rails with the Grape Framework. It uses MariaDB as the database engine. Docker is used for deployment and local development.

## Source Code

The following are the relevant GitHub repositories to this project: 
1. Deployment - https://github.com/thoth-tech/doubtfire-deploy 
2. Frontend - https://github.com/thoth-tech/doubtfire-web 
3. Backend - https://github.com/thoth-tech/doubtfire-api 
4. OnTrack Documentation Website - https://github.com/thoth-tech/doubtfire-astro 
5. Documentation (OnTrack feature documentation, frontend migration component 
reviews, etc.) - https://github.com/thoth-tech/documentation/tree/main/docs/OnTrack 
6. Templates (Spikes, component reviews) - https://github.com/thoth-tech/documentation/tree/main/docs/Templates 
7. CourseFlow documentation - https://github.com/thoth-tech/ThothTech-Documentation-Website/tree/main/src/content/docs/products/courseflow 
Note: Any pull requests must first be made to the thoth-tech forks of the repositories, not 
the upstream doubtfire-lms ones. 

## Login Credentials

Refer to the Working with Dev Containers section of the [Contributing Guide](https://github.com/thoth-tech/doubtfire-deploy/blob/main/CONTRIBUTING.md) for 
authentication credentials for locally deployed OnTrack. 

## Show Case Video

TODO : Add showcase video link

# Project 2: SplashKit

## Project Overview

SplashKit is a user-friendly programming framework designed for creating 2D games, primarily to help
students learn introductory programming through game development. The framework is mainly written in
C++, but it supports multiple languages, including C#, Python, Pascal, and JavaScript.

## Projects

### Arcade Machines

The university has acquired four arcade machines equipped with Raspberry Pi 3B+ units, designed to
showcase games developed with SplashKit. The short-term goal is to prepare these platforms for
students to display their SplashKit creations. The medium-term goal is to streamline the process for
first-year students to easily upload and test their games.

### Game Development

The Game Development team is dedicated to creating and enhancing games that run on the arcade
machines. Their mission is to demonstrate SplashKit’s capabilities and inspire students by
showcasing what can be achieved with the framework.

### SplashKit Website

Powered by the Starlight framework, the revamped SplashKit website aims to offer an enriched and
user-friendly experience for developers and learners. It will host existing tutorials and guides,
providing a central hub for exploring and learning about SplashKit.

### SplashKit Tutorials

The SplashKit Website will feature tutorials aimed at helping students learn and explore SplashKit’s
functionality. The focus is on developing smaller, high-quality tutorials across C++, C#, and
Python, rather than extensive series.

### SplashKit Expansion

The Expansion team is responsible for maintaining and enhancing the SplashKit core. This includes
bug fixes, feature improvements, and refining installation and usage workflows through package
creation and addressing installation issues.

### SplashKit Online

SplashKit Online is developing a web-based IDE that allows students to write and run code directly
in their browsers. Initially launched as a prototype in 2023, the 2024 goal is to mature this tool
into a comprehensive product, including C# support and an embeddable version for the SplashKit
website.

## User Manual

### Arcade Machines

- [Brief development environment setup instructions](https://github.com/thoth-tech/arcade-machine)
- [Machine Operations Guide](<https://deakin365.sharepoint.com/:b:/r/sites/ThothTech2/Shared%20Documents/SplashKit/Arcade%20Machine%20(Burwood%20Building%20M)%20Operation%20Guide/Thoth%20Tech%20Arcade%20Machine%20Operation.pdf?csf=1&web=1&e=Mx3iBS>)

### SplashKit Website

- [Development environment setup instructions](https://github.com/thoth-tech/splashkit.io-starlight/blob/main/CONTRIBUTE.md)

### SplashKit Tutorials

- [Tutorial Information Hub](https://thoth-tech.netlify.app/products/splashkit/splashkit-tutorials/0-overview/)
- [Development environment setup instructions](https://github.com/thoth-tech/splashkit.io-starlight/blob/main/CONTRIBUTE.md)

### SplashKit Expansion

- [Repository setup instructions](https://github.com/thoth-tech/splashkit-core/blob/develop/CONTRIBUTING.md)

### Game Development

- [Game Development Student Onboarding Guide](https://github.com/thoth-tech/arcade-games/blob/main/advanced-game-design-team/Student%20Onboarding%20Guide.md)
- [Guide to Contribute a Game to the Arcade Machine](https://github.com/thoth-tech/arcade-games/blob/main/README.md)

### SplashKit Online

- [Development environement setup instructions](https://github.com/thoth-tech/SplashkitOnline?tab=readme-ov-file#installation)
- [General developer documentation](https://thoth-tech.netlify.app/products/splashkit/splashkit-online/code-documentation/other/folderstructureoverview/)

## Completed Deliverables

This trimester, the following deliverables were completed:

### Arcade Machine

- Arcade Machine Improvements
  - Developed a test menu for the arcade machine
  - Added additional controls to the arcade menu
  - Defined the process for uploading games to the arcade machine
  - Fixed broken links in Arcade Build documentation
  - Developed Game Packaging tool, [flipper](https://github.com/thoth-tech/flipper)

### SplashKit Expansion

- General Improvements
  - Fixed bugs relating to vectors, random number generation, moving sprites and replacing text.
  - Renamed 'label' parameter to fix Pascal support
  - Investigate and identified missing functionality from SwinGame
  - Tested Python compatibility
  - Implemented insertion of XML comments into SplashKit.cs during translation process
- New Features
  - Completed development of Remote GPIO Control methods
  - Created Circle-Triangle Collision detection methods
  - Created base64 image decoding function
  - Created SplashKit Splashscreen function
  - Added unit tests for networking, utility functions, bitmaps, sound effects, and music.

### SplashKit Website

- Website Improvements
  - Begun development of an 'Onboarding Hub'
  - Resolved issues with SplashKit.io dev Container
  - Fixed the guides index page and updated broken links
  - Improved Troubleshooting section
  - Added game showcase page and improved website styling
  - Reviewed, updated and validated key policies and FAQs
  - Fixed API table formatting
  - Updated tab logo
  - Improved site styling

### SplashKit Tutorials

- New Tutorials
  - Developed 2D Vectors tutorial series covering topics such as vector magnitude, collisions and
    gravity
- Tutorial Updates
  - Created documentation detailing tutorial review process
  - Developed Onboarding process for the tutorial team
  - Added Object-Oriented Programming concepts to SplashKit tutorials
  - Added C# Code Blocks to Tutorials
    - "Introduction to JSON", "Writing JSON Data", "Reading JSON Data", guides
    - "Styling User Interfaces" guide
    - "Understanding Double Buffering" guide
  - Add Python Code Blocks to Tutorials
    - "Using Mouse Inputs" guide
- Created various usage examples
  - `fill_triangle`, `fill_circle`, `create_sprite`, `draw_sprite`,`clear_screen` and more
- Completed various tutorial reviews
  - "Getting started with servers" guide
  - "How to make a RESTful API call" guide
  - "SplashKit Camera" guide
  - "Using Mouse Inputs" guide

### SplashKit Online

- Automated installation of pre-built files
- Interface Improvements
  - Fixed scrollbar jumping to top when switching code files
  - Implemented message to prompt user for action to enable audio
  - Added Interface Minification option

### Game Development

- Game Development Improvements
  - Developed Onboarding guide for the Game Development team
  - Addressed issue that compiled .exe files are platform-specific.
  - Fixed gameplay issues in Below the Surface and Venture Adventure
  - Created programming plan for the Bee Game project, outlining core mechanics and class structures

### List Of All Complete Deliverables

| Full Name                 | Description                                                                                              |                                                                                                                                                                                                                                                            Evidence |
| :------------------------ | :------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Brianna Laird             | Fix Broken Dev Container                                                                                 |                                                                                                                                                                                                          https://github.com/splashkit/splashkit.io-starlight/pull/7 |
| Brianna Laird             | SIT102 Channel Suggestion Post                                                                           |                                                                                                                                                                                                                                                                     |
| Brianna Laird             | Update and Re-organise Trouble Shooting Section                                                          |                                                                                                                                                                                                         https://github.com/splashkit/splashkit.io-starlight/pull/10 |
| Brianna Laird             | Add Python code blocks to "Using Mouse Inputs" guide                                                     |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/139 |
| Brianna Laird             | Add Tutorial Review Documentation                                                                        |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/529 |
| Brianna Laird             | Splashkit tutorial - Documentation Update                                                                |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/89 |
| Brianna Laird             | Validate/Update Processes, Policies and FAQs                                                             |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/85 |
| Brianna Laird             | Adding OOP To Splashkit Tutorials                                                                        |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/95 |
| Brianna Laird             | Fixing Tutorial Side Guide                                                                               |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/96 |
| Brianna Laird             | Update Usage Examples to add Python code                                                                 |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/144 |
| Brianna Laird             | Create Code Usage Examples for: "fill_triangle_on_bitmap" function                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/151 |
| Brianna Laird             | Create Code Usage Examples for CreateSprite                                                              |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/152 |
| Brianna Laird             | Create Code Usage Examples for Draw sprite                                                               |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/153 |
| Brianna Laird             | Create Code Usage Examples for Free sprite                                                               |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/154 |
| Brianna Laird             | Create Code Usage example for:"clear_screen" function                                                    |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/148 |
| Brianna Laird             | Dec to Hex Usage Example                                                                                 |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/171 |
| Brianna Laird             | Hex to Dec Usage Example                                                                                 |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/172 |
| Brianna Laird             | IPv4 to Decimal Usage Example                                                                            |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/169 |
| Brianna Laird             | IPv4 to Hex Usage Example                                                                                |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/170 |
| Brianna Laird             | Introduction to JSON Tutorial - C# Language Update                                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/175 |
| Brianna Laird             | Review "Getting Started with Servers" guide                                                              |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/531 https://github.com/thoth-tech/splashkit.io-starlight/pull/145 |
| Brianna Laird             | Review "How to make a RESTful API call" guide                                                            |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/533 https://github.com/thoth-tech/splashkit.io-starlight/pull/147 |
| Brianna Laird             | Review "Splashkit Camera" Guide                                                                          |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/545 https://github.com/thoth-tech/splashkit.io-starlight/pull/164 |
| Brianna Laird             | Review "Useful Utilities" guide                                                                          |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/547 https://github.com/thoth-tech/splashkit.io-starlight/pull/176 |
| Brianna Laird             | Review: "Using Mouse Inputs" guide                                                                       |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/541 https://github.com/thoth-tech/splashkit.io-starlight/pull/161 |
| Brianna Laird             | Fix issue with ipv4_to_str function                                                                      |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/71 |
| Darren Marchiano Sunandar | Fix typo in vector magnitude squared documentation                                                       |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/62 |
| Darren Marchiano Sunandar | Identify missing functionality from SwinGame                                                             |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/536 |
| Darren Marchiano Sunandar | Arcade Machine Splashkit splash screen on startup                                                        |                                                                                                                                                                                                               https://github.com/thoth-tech/documentation/pull/548/ |
| Darren Marchiano Sunandar | Fix bug in replace_all                                                                                   |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/69 |
| Darren Marchiano Sunandar | Test python version                                                                                      |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/542 |
| Darren Marchiano Sunandar | Translator: Generate C# documentation comments from HeaderDoc                                            |                                                                                                                                                                                                          https://github.com/thoth-tech/splashkit-translator/pull/13 |
| Ethan Mark Holley         | Fix scrollbar jumping to top when switching code files                                                   |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/87 |
| Ethan Mark Holley         | Interface Minification Option                                                                            |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/89 |
| Ethan Mark Holley         | Show message to user requesting them to click into the Execution Environment iFrame to get audio working |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/90 |
| Ethan Mark Holley         | Add Network Unit Tests                                                                                   |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/73 |
| Ethan Mark Holley         | Arcade Menu - Add additional controls                                                                    |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/546 |
| Ethan Mark Holley         | Develop Test Menu for Arcade Machine                                                                     |                                                                                                                                                                                                                https://github.com/thoth-tech/arcade-machine/pull/80 |
| Hangyu Li                 | Create Code Usage Examples for: "fill_circle" function                                                   |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/163 |
| Hangyu Li                 | Create Code Usage Examples for: "fill_ellipse" function                                                  |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/162 |
| Hangyu Li                 | Create Code Usage Examples for: "fill_rectangle" function                                                |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/158 |
| Hangyu Li                 | Create Code Usage example for:"clear_screen" function                                                    |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/148 |
| Hangyu Li                 | Dec to Hex Usage Example                                                                                 |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/171 |
| Hangyu Li                 | Hex to Dec Usage Example                                                                                 |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/172 |
| Hangyu Li                 | Review "Splashkit Camera" Guide                                                                          |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/545 https://github.com/thoth-tech/splashkit.io-starlight/pull/164 |
| Hangyu Li                 | Write Line INTEGER - Usage Example for Terminal                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/185 |
| Hangyu Li                 | Writing JSON data Tutorial - C# Language Update                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/190 |
| Hayley Rose Hughes        | Define process for copying games to Arcade Machine                                                       |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/522 |
| Hayley Rose Hughes        | Fix typo in vector magnitude squared documentation                                                       |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/62 |
| Hayley Rose Hughes        | Initial implementation of remote GPIO control                                                            |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/58 |
| Hayley Rose Hughes        | Investigate bug in move_sprite_to                                                                        |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/59 |
| Hayley Rose Hughes        | Fix bug in closest_point_on_lines                                                                        |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/63 |
| Hayley Rose Hughes        | Add unit tests for utility functions                                                                     |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/68 |
| Hayley Rose Hughes        | Arcade Machine Splashkit splash screen on startup                                                        |                                                                                                                                                                                                               https://github.com/thoth-tech/documentation/pull/548/ |
| Hayley Rose Hughes        | Circle-Triangle Collision Detection Methods                                                              |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/60 |
| Hayley Rose Hughes        | Fix broken links in Arcade Build Doco                                                                    |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/523 |
| Hayley Rose Hughes        | Fix bugs in rnd                                                                                          |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/70 |
| Hayley Rose Hughes        | Fix issue with ipv4_to_str function                                                                      |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/71 |
| Hayley Rose Hughes        | Rename 'label' Parameter                                                                                 |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/66 |
| Hayley Rose Hughes        | Translator: Generate C# documentation comments from HeaderDoc                                            |                                                                                                                                                                                                          https://github.com/thoth-tech/splashkit-translator/pull/13 |
| Hayley Rose Hughes        | Updated Arcade Build Doco                                                                                |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/523 |
| Jake Andrew Oxley         | Identify missing functionality from SwinGame                                                             |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/536 |
| Jake Andrew Oxley         | SplashKit Tutorial - 2D Vectors                                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/134 |
| Jessica Balsillie         | Automate installation of pre-built files                                                                 |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/85 |
| Jessica Balsillie         | Fix scrollbar jumping to top when switching code files                                                   |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/87 |
| Jonathan James Tynan      | Define process for copying games to Arcade Machine                                                       |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/522 |
| Jonathan James Tynan      | Initial implementation of remote GPIO control                                                            |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/58 |
| Jonathan James Tynan      | Tutorial Proposal - 2D Vectors                                                                           |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/87 |
| Jonathan James Tynan      | Validate/Update Processes, Policies and FAQs                                                             |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/85 |
| Jonathan James Tynan      | Add bitmap, sound effect and music unit tests                                                            |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/64 |
| Jonathan James Tynan      | Automate installation of pre-built files                                                                 |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/85 |
| Jonathan James Tynan      | Fix bug in closest_point_on_lines                                                                        |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/63 |
| Jonathan James Tynan      | Identify missing functionality from SwinGame                                                             |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/536 |
| Jonathan James Tynan      | Fix guides index page                                                                                    |                                                                                                                                                                                                      https://github.com/thoth-tech/splashkit.io-starlight/pull/149/ |
| Jonathan James Tynan      | Add showcase page                                                                                        |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/155 |
| Jonathan James Tynan      | Update Broken Splashkit.io Links                                                                         |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/136 |
| Jonathan James Tynan      | Add unit tests for utility functions                                                                     |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/68 |
| Jonathan James Tynan      | Base64 Splashkit image decoding function                                                                 |                                                                                                                                                                                                               https://github.com/thoth-tech/splashkit-core/pull/72/ |
| Jonathan James Tynan      | Circle-Triangle Collision Detection Methods                                                              |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/60 |
| Jonathan James Tynan      | Fix broken links in Arcade Build Doco                                                                    |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/523 |
| Jonathan James Tynan      | Fix bug in replace_all                                                                                   |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/69 |
| Jonathan James Tynan      | Fix bugs in rnd                                                                                          |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/70 |
| Jonathan James Tynan      | Fix issue with ipv4_to_str function                                                                      |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/71 |
| Jonathan James Tynan      | Rename 'label' Parameter                                                                                 |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/66 |
| Jonathan James Tynan      | Test python version                                                                                      |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/542 |
| Jonathan James Tynan      | Translator: Generate C# documentation comments from HeaderDoc                                            |                                                                                                                                                                                                          https://github.com/thoth-tech/splashkit-translator/pull/13 |
| Jonathan James Tynan      | Updated Arcade Build Doco                                                                                |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/523 |
| Ka Chun Lam               | Create 1-2 page condensed, high level implementation pattern guide for rapid onboarding                  |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/227 |
| Ka Chun Lam               | project Bee - create programming plan                                                                    |                                                                                                                                                                                                                        https://github.com/zhusim222/Bee-game/pull/4 |
| Kartik Kaushik            | Create Code Usage Examples for CreateSprite                                                              |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/152 |
| Kartik Kaushik            | Create Code Usage Examples for Draw sprite                                                               |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/153 |
| Kartik Kaushik            | Create Code Usage Examples for Free sprite                                                               |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/154 |
| Kartik Kaushik            | Create Code Usage Examples for sprite set position                                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/168 |
| Kartik Kaushik            | Create Code Usage Examples for sprite set velocity                                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/165 |
| Kartik Kaushik            | Create Code Usage Examples for sprite set x                                                              |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/166 |
| Kartik Kaushik            | Create Code Usage Examples for sprite set y                                                              |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/167 |
| Kartik Kaushik            | Github Guide                                                                                             |                                                                                                                                                                                              https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/101 |
| Kartik Kaushik            | Styling Using Interfaces Tutorial - C# Language Update                                                   |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/200 |
| Kartik Kaushik            | Understanding Double Buffering Tutorial - C# Language Update                                             |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/197 |
| Kartik Kaushik            | Writing JSON data Tutorial - C# Language Update                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/190 |
| Mark Heath                | All games - locally-compiled exe(s) are platform-specific                                                |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/226 |
| Mark Heath                | Below The Surface - level 9 (FIGHT) has a collision issue next to the exit                               |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/225 |
| Mark Heath                | Create 1-2 page condensed, high level implementation pattern guide for rapid onboarding                  |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/227 |
| Mark Heath                | Misc games - fix merge conflicts from T1 PRs                                                             |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/228 |
| Mark Heath                | Venture Adventure - fix bundle files                                                                     |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/219 |
| Mark Heath                | Venture Adventure - fix level music                                                                      |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/222 |
| Mark Heath                | Venture Adventure - remove outdated credit                                                               |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/218 |
| Mark Heath                | Venture Adventure - small refactor                                                                       | https://github.com/thoth-tech/arcade-games/pull/220 https://github.com/thoth-tech/arcade-games/pull/221 https://github.com/thoth-tech/arcade-games/pull/222 https://github.com/thoth-tech/arcade-games/pull/223 https://github.com/thoth-tech/arcade-games/pull/224 |
| Mark Heath                | project Bee - create programming plan                                                                    |                                                                                                                                                                                                                        https://github.com/zhusim222/Bee-game/pull/4 |
| Matthew James Harding     | Fix typo in vector magnitude squared documentation                                                       |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/62 |
| Matthew James Harding     | Investigate bug in move_sprite_to                                                                        |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/59 |
| Matthew James Harding     | Add bitmap, sound effect and music unit tests                                                            |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/64 |
| Matthew James Harding     | Fix bug in closest_point_on_lines                                                                        |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/63 |
| Matthew James Harding     | Interface Minification Option                                                                            |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/89 |
| Matthew James Harding     | Show message to user requesting them to click into the Execution Environment iFrame to get audio working |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/90 |
| Matthew James Harding     | Add Network Unit Tests                                                                                   |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/73 |
| Matthew James Harding     | Add unit tests for utility functions                                                                     |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/68 |
| Matthew James Harding     | Arcade Menu - Add additional controls                                                                    |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/546 |
| Matthew James Harding     | Base64 Splashkit image decoding function                                                                 |                                                                                                                                                                                                               https://github.com/thoth-tech/splashkit-core/pull/72/ |
| Matthew James Harding     | Circle-Triangle Collision Detection Methods                                                              |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/60 |
| Matthew James Harding     | Develop Test Menu for Arcade Machine                                                                     |                                                                                                                                                                                                                https://github.com/thoth-tech/arcade-machine/pull/80 |
| Matthew James Harding     | Fix bug in replace_all                                                                                   |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/69 |
| Matthew James Harding     | Fix bugs in rnd                                                                                          |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/70 |
| Mounika Angadipeta        | Add C# code blocks to the 3 JSON guides                                                                  |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/133 |
| Mounika Angadipeta        | Add Python code blocks to "Using Mouse Inputs" guide                                                     |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/139 |
| Mounika Angadipeta        | Tutorial Proposal - 2D Vectors                                                                           |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/87 |
| Mounika Angadipeta        | Create Code Usage Examples for: "fill_triangle_on_bitmap" function                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/151 |
| Mounika Angadipeta        | Introduction to JSON Tutorial - C# Language Update                                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/175 |
| Mounika Angadipeta        | Reading JSON data Tutorial - C# Language Update                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/186 |
| Mounika Angadipeta        | Review "Introduction to JSON" guide                                                                      |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/540 https://github.com/thoth-tech/splashkit.io-starlight/pull/156 |
| Mounika Angadipeta        | Review: "Using Mouse Inputs" guide                                                                       |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/541 https://github.com/thoth-tech/splashkit.io-starlight/pull/161 |
| Nidhisha Pahade           | Create Code Usage Examples for CreateSprite                                                              |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/152 |
| Nidhisha Pahade           | Github Guide                                                                                             |                                                                                                                                                                                              https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/101 |
| Nidhisha Pahade           | Review "Getting Started with Servers" guide                                                              |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/531 https://github.com/thoth-tech/splashkit.io-starlight/pull/145 |
| Nidhisha Pahade           | Review "Useful Utilities" guide                                                                          |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/547 https://github.com/thoth-tech/splashkit.io-starlight/pull/176 |
| Nidhisha Pahade           | Styling Using Interfaces Tutorial - C# Language Update                                                   |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/200 |
| Nidhisha Pahade           | Understanding Double Buffering Tutorial - C# Language Update                                             |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/197 |
| Oliver Exell-Bruce        | Fix API Page Parameter Table Formatting                                                                  |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/187 |
| Oliver Exell-Bruce        | Fix guides index page                                                                                    |                                                                                                                                                                                                      https://github.com/thoth-tech/splashkit.io-starlight/pull/149/ |
| Oliver Exell-Bruce        | Website Styling                                                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/159 |
| Oliver Exell-Bruce        | Add showcase page                                                                                        |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/155 |
| Oliver Exell-Bruce        | Review "Getting Started with Servers" guide                                                              |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/531 https://github.com/thoth-tech/splashkit.io-starlight/pull/145 |
| Oliver Exell-Bruce        | Review "Useful Utilities" guide                                                                          |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/547 https://github.com/thoth-tech/splashkit.io-starlight/pull/176 |
| Oliver Exell-Bruce        | SplashKit Tutorial - 2D Vectors                                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/134 |
| Oliver Exell-Bruce        | Styling Using Interfaces Tutorial - C# Language Update                                                   |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/200 |
| Oliver Exell-Bruce        | Understanding Double Buffering Tutorial - C# Language Update                                             |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/197 |
| Oscar Harris              | Create 1-2 page condensed, high level implementation pattern guide for rapid onboarding                  |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/227 |
| Sana Noureen              | Update Tab Logo                                                                                          |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/98 |
| Sana Noureen              | Website Styling                                                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/159 |
| Sana Noureen              | Dec to Hex Usage Example                                                                                 |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/171 |
| Sana Noureen              | Documentation Site Styling                                                                               |                                                                                                                                                                                              https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/102 |
| Sana Noureen              | Write Line INTEGER - Usage Example for Terminal                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/185 |
| Sharvani Kandala          | Create Code Usage Examples for: "fill_triangle" function                                                 |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/143 |
| Sharvani Kandala          | Tutorial Proposal- Camera control functions                                                              |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/97 |
| Sharvani Kandala          | Create Code Usage Examples for: "fill_ellipse" function                                                  |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/162 |
| Sharvani Kandala          | Create Code Usage Examples for: "fill_rectangle" function                                                |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/158 |
| Sharvani Kandala          | Create Code Usage Examples for: "fill_triangle_on_bitmap" function                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/151 |
| Sharvani Kandala          | Create Code Usage Examples for Draw sprite                                                               |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/153 |
| Sharvani Kandala          | Create Code Usage example for:"clear_screen" function                                                    |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/148 |
| Sharvani Kandala          | IPv4 to Decimal Usage Example                                                                            |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/169 |
| Sharvani Kandala          | IPv4 to Hex Usage Example                                                                                |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/170 |
| Sharvani Kandala          | Review "How to make a RESTful API call" guide                                                            |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/533 https://github.com/thoth-tech/splashkit.io-starlight/pull/147 |
| Shaun Ratcliff            | Add C# code blocks to the 3 JSON guides                                                                  |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/133 |
| Shaun Ratcliff            | Splashkit tutorial - Documentation Update                                                                |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/89 |
| Shaun Ratcliff            | Tutorial Proposal - 2D Vectors                                                                           |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/87 |
| Shaun Ratcliff            | Validate/Update Processes, Policies and FAQs                                                             |                                                                                                                                                                                               https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/85 |
| Shaun Ratcliff            | Fix API Page Parameter Table Formatting                                                                  |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/187 |
| Shaun Ratcliff            | Fix guides index page                                                                                    |                                                                                                                                                                                                      https://github.com/thoth-tech/splashkit.io-starlight/pull/149/ |
| Shaun Ratcliff            | Website Styling                                                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/159 |
| Shaun Ratcliff            | Add showcase page                                                                                        |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/155 |
| Shaun Ratcliff            | Create Code Usage example for:"clear_screen" function                                                    |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/148 |
| Shaun Ratcliff            | Documentation Site Styling                                                                               |                                                                                                                                                                                              https://github.com/thoth-tech/ThothTech-Documentation-Website/pull/102 |
| Shaun Ratcliff            | Reading JSON data Tutorial - C# Language Update                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/186 |
| Shaun Ratcliff            | Review "Introduction to JSON" guide                                                                      |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/540 https://github.com/thoth-tech/splashkit.io-starlight/pull/156 |
| Shaun Ratcliff            | SplashKit Tutorial - 2D Vectors                                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/134 |
| Shaun Ratcliff            | Update Broken Splashkit.io Links                                                                         |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/136 |
| Shaun Ratcliff            | Write Line INTEGER - Usage Example for Terminal                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/185 |
| Simon Zhu                 | Below The Surface - level 9 (FIGHT) has a collision issue next to the exit                               |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/225 |
| Thomas James Shanahan     | All games - locally-compiled exe(s) are platform-specific                                                |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/226 |
| Thomas James Shanahan     | Below The Surface - level 9 (FIGHT) has a collision issue next to the exit                               |                                                                                                                                                                                                                 https://github.com/thoth-tech/arcade-games/pull/225 |
| Thomas James Shanahan     | project Bee - create programming plan                                                                    |                                                                                                                                                                                                                        https://github.com/zhusim222/Bee-game/pull/4 |
| Will Saunders             | Define process for copying games to Arcade Machine                                                       |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/522 |
| Will Saunders             | Initial implementation of remote GPIO control                                                            |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/58 |
| Will Saunders             | Investigate bug in move_sprite_to                                                                        |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/59 |
| Will Saunders             | Add bitmap, sound effect and music unit tests                                                            |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/64 |
| Will Saunders             | Interface Minification Option                                                                            |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/89 |
| Will Saunders             | Show message to user requesting them to click into the Execution Environment iFrame to get audio working |                                                                                                                                                                                                               https://github.com/thoth-tech/SplashkitOnline/pull/90 |
| Will Saunders             | Add Network Unit Tests                                                                                   |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/73 |
| Will Saunders             | Arcade Machine Splashkit splash screen on startup                                                        |                                                                                                                                                                                                               https://github.com/thoth-tech/documentation/pull/548/ |
| Will Saunders             | Arcade Menu - Add additional controls                                                                    |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/546 |
| Will Saunders             | Base64 Splashkit image decoding function                                                                 |                                                                                                                                                                                                               https://github.com/thoth-tech/splashkit-core/pull/72/ |
| Will Saunders             | Develop Test Menu for Arcade Machine                                                                     |                                                                                                                                                                                                                https://github.com/thoth-tech/arcade-machine/pull/80 |
| Will Saunders             | Fix broken links in Arcade Build Doco                                                                    |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/523 |
| Will Saunders             | Rename 'label' Parameter                                                                                 |                                                                                                                                                                                                                https://github.com/thoth-tech/splashkit-core/pull/66 |
| Will Saunders             | Test python version                                                                                      |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/542 |
| Will Saunders             | Updated Arcade Build Doco                                                                                |                                                                                                                                                                                                                https://github.com/thoth-tech/documentation/pull/523 |
| Yuyang Yang               | Add C# code blocks to the 3 JSON guides                                                                  |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/133 |
| Yuyang Yang               | Add Python code blocks to "Using Mouse Inputs" guide                                                     |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/139 |
| Yuyang Yang               | Introduction to JSON Tutorial - C# Language Update                                                       |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/175 |
| Yuyang Yang               | Reading JSON data Tutorial - C# Language Update                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/186 |
| Yuyang Yang               | Review "How to make a RESTful API call" guide                                                            |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/533 https://github.com/thoth-tech/splashkit.io-starlight/pull/147 |
| Yuyang Yang               | Review "Introduction to JSON" guide                                                                      |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/540 https://github.com/thoth-tech/splashkit.io-starlight/pull/156 |
| Yuyang Yang               | Review "Splashkit Camera" Guide                                                                          |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/545 https://github.com/thoth-tech/splashkit.io-starlight/pull/164 |
| Yuyang Yang               | Review: "Using Mouse Inputs" guide                                                                       |                                                                                                                                                  https://github.com/thoth-tech/documentation/pull/541 https://github.com/thoth-tech/splashkit.io-starlight/pull/161 |
| Yuyang Yang               | Writing JSON data Tutorial - C# Language Update                                                          |                                                                                                                                                                                                       https://github.com/thoth-tech/splashkit.io-starlight/pull/190 |

## Roadmap

### Arcade Machine

- Consolidate documentation in one place or repository
- Add additional modes to the Arcade Machine software
  - Kiosk Mode: Show only published games, ideal for events
  - Normal Mode: Display both published and test games
- Implement Voting System: Integrate a voting system to give significance to the star ranking
  currently available on the machines
- Correct the C# compatibility for ARM, as .NET currently does not run correctly in the emulated PI
  environment used for C++ games
- Implement versioning for compiled games to manage updates effectively
- Continue development of [flipper](https://github.com/thoth-tech/flipper) Game Packaging Tool

### SplashKit.io Website

- SplashKit.io Improvements
  - Improve API Reference
    - Continue to add usage examples for SplashKit API
    - Integrate live demo's to provide interactive examples
    - Add mechanism for the user to globally switch between programming languages in the API
      reference
    - Produce concise videos to support the documentation
    - Enhance documentation with more interactive and user-friendly documentation elements
  - Contributor Resources
    - Develop resources to support community contributions
    - Including detailed guides, best practices and an interactive forum
- Thoth Tech Documentation Website
  - Improve Onboarding Hub
    - Continue to expand and refine the Onboarding hub
    - Create relevant guides, checklists and tutorials for all stages of the project documentation
      and development lifecycle
    - Develop detailed Onboarding paths to guide new students
    - Implement a comprehensive upskilling section, containing curated learning materials

### SplashKit Tutorials

- Continue Reviewing Current Tutorials:
  - Compile and Run Tutorial Code: Ensure all example code works correctly, fixing any issues (e.g.,
    SplashKit Camera). Ensure they all use top level statements for C#, and include C++ and python
    code.
  - Proof-read Content: Verify that the wording is clear and comprehensible.
  - Add Python Code Tabs: Include Python code examples in any tutorials currently missing them.
- Expand and Update Tutorials:
  - Plan and develop new tutorials to cover the full range of SplashKit functionality.
  - Develop a wide range of tutorials that cover all aspects of game development using SplashKit,
    including advanced game mechanics, AI, physics, and more
  - Continuously update existing tutorials to reflect changes in SplashKit.
  - Develop advanced tutorials to cover more complex topics and advanced functionalities of
    SplashKit.
- Interactive Tutorial Platform
  - Develop an interactive platform where users can follow tutorials and write code directly within
    their browser, with real-time feedback and code execution
- Create Introductory Level Games:
  - Write short, introductory-level games using procedural C++/C#, with accompanying tutorials aimed
    at SIT102 level beginner skills.
  - Link to content on Programmers Guide to promote the use of pre-existing material.
- Create SplashKit Online IDE Tutorial:
  - Develop a tutorial series on creating a game using the SplashKit Online IDE.
- Community Engagement and Feedback:
  - Establish a system for receiving and incorporating feedback from the community to continuously
    improve tutorials.
  - Encourage contributions from the community and maintain a high standard for tutorial
    submissions.

### SplashKit Expansion

- Finish development of dev containers for SplashKit Core.
  [See here](https://github.com/thoth-tech/documentation/tree/main/docs/Splashkit/DevEnviroment/Windows_DevContainer)
  for more details.
- Deployment Packages:
  - Brew Package: Finalise and fix existing Brew packages to ensure smooth installation and usage.
- Test and Fix SplashKit Functionality:
  - Identify and resolve bugs in SplashKit functionality
  - Investigate bug regarding drawing text to second window. See
    [Issue #177](https://github.com/splashkit/splashkit-core/issues/177) for more information.
  - Investigate and implement Pascal compilation fix. See
    [Issue #151](https://github.com/splashkit/splashkit-core/issues/151) and relevant Planner card
    for more information.
    - Fix handling of negative enums in SplashKit Translator (this should be done; see Planner card
      for status)
- Port SwinGame Functions to SplashKit:
  - Review and port missing functions from SwinGames into SplashKit.
- Investigate MinGW Compatibility
  - There have been issues with using SplashKit in MinGW, this needs to be investigated.
- Improve Raspberry Pi Functionality:
  - Improve GPIO Error Handling (this should be done; see Planner card for status)
  - Implement support for the Raspberry Pi 5, as current support only extends to Raspberry Pi 4B+.
- Further Integration Testing
  - Conduct detailed testing and bug fixing of SplashKit functionality.
  - Ensure both procedural and OOP versions of each function are thoroughly tested and reliable.
- Comprehensive Testing and Bug Fixing:
  - Develop a comprehensive automated test suite to regularly test SplashKit functionality and
    quickly identify and resolve new bugs. This ensures the framework remains stable and reliable as
    new features are added and updates are made.
    - Implement unit tests for functions without them
    - Add tests for translator targets C#, Python and Pascal.
      - Alternatively, investigate the difficulty of creating a translator module to automatically
        translate the existing C++ tests into the translator target languages

### SplashKit Online

- Embed Lite Version into SplashKit Website:
  - Develop and implement a "lite" version of SplashKit Online for embedding in the SplashKit
    website to demonstrate code snippets and showcase functionalities.
  - Focus on interface changes to integrate seamlessly with the website.
  - Improve loading times and caching to ensure smooth performance.
- Improve Project Management
  - Project Handling: Add functionality for users to create, load, save, and delete projects within
    the browser, managing multiple projects with unique names.
  - Version Control: Integrate version control to track changes and revert to previous states as
    needed.
  - Export Project Builds: Enable exporting project builds as executables for C++ projects or single
    HTML files for JavaScript projects for better portability and sharing.
- Improve SplashKit Online Interface:
  - Code Editing and REPL Functionality: Implement auto-complete for variable parameters, add
    breakpoints, and create variable watch windows to improve coding and debugging.
- Extended Language Support:
  - C# Support: Continue to explore and add support for C# to broaden language options.
  - Python Support: Investigate and add support for Python to accommodate additional user needs.
- Advanced Project Features:
  - Integrated Code Snippets: Develop functionality for users to save and reuse code snippets within
    their projects.
  - Collaborative Features: Consider implementing collaborative features for simultaneous project
    work among multiple users.

### Game Development

- Establish Standardised Implementation Patterns:
  - Enforce decoupling of data/functionality and decoupling of state/render patterns.
  - Develop a prescribed implementation pattern to ensure consistency and quality across projects.
- Develop a "10 Minute Game":
  - Collaboratively plan and execute the development of a simple game (e.g., idle game, tower
    defence, survivor.io-like).
  - Ensure core game mechanics are implemented in the first sprint.
  - Focus the latter half of the trimester on improving visual representation, adding "juice," and
    implementing variations of core game elements (e.g., enemies, powerups, weapons).
  - This approach ensures that core functionality is completed within a single trimester, with
    additional features developed against a standardised interface that integrates with the core
    game types.
- Iterate on Prescribed Patterns:
  - Adjust and refine the implementation pattern based on student feedback and experiences.
- Generate Development Artifacts:
  - Create documentation covering the implementation of discrete game systems (e.g., terrain
    generation systems using IDW/random walk/noise, 2D light marching, threaded state update and
    render patterns).
- Improve Documentation:
  - Existing games often lack adequate documentation. Good documentation can significantly increase
    onboarding speed for new contributors.
  - For completed games, create UML diagrams, overviews of gameplay mechanics, and guides for
    creating levels in each game’s format.
  - Address the discoverability of existing documentation and resources. Update README files to
    reflect the current focus of work and ensure existing documentation is easy to find.
- Complete Core Functionality of Incomplete Games:
  - Focus on finishing significant core functionalities in games that are currently incomplete
    (e.g., Sky Surge, Single Combat).
- Extend Gameplay and Functionality of Completed Games:
  - Enhance and expand the gameplay and features of games that are already completed, ensuring they
    continue to engage and challenge players.

## Open Issues

The SplashKit team has faced several challenges over Trimester 2, 2024. These are detailed below:

- Lack of Communication Between Project Groups
  - While individual communication channels, threads, and chats exist for each project, there is a
    notable absence of overarching organization. The lack of regular meetings between teams or with
    the entire company has led to confusion, poor coordination, and duplicated efforts. In some
    cases, tasks were reassigned or duplicated by different team members without clear
    communication, causing disruptions in workflow. This decentralized communication structure has
    hindered collaboration across projects and created barriers to progress.
- Insufficient Onboarding Information and Lack of Codebase Exploration
  - A recurring issue was the lack of exploration of the existing codebase by team members, both in
    terms of finished and unfinished work. As a result, students often replicated previous efforts
    instead of building on them, such as recreating Git contribution guides or developer environment
    setup guides unnecessarily. This issue stems from insufficient documentation practices and a
    lack of familiarity with existing resources, causing inefficiencies and wasted effort.
- Team Members Performing Duplicate Work
  - The combination of communication gaps and poor documentation has directly led to duplicated
    work. Without a clear mechanism to track or share ongoing progress across teams, individuals
    have inadvertently recreated work completed by others. This redundancy has slowed down
    development and caused unnecessary strain on resources.

A possible solution to these issues would be the implementation of regular cross-team meetings and
company-wide updates. These would provide a clearer understanding of each team’s progress,
facilitate better collaboration, and reduce duplicated efforts. Additionally, enhancing overall
documentation and establishing more robust processes for tracking work across projects would help
ensure that past work is utilized effectively moving forward.

## Product Development Life Cycle

### New Tasks

In SplashKit it is up to individuals to assign themselves to cards – generally speaking, it is fine
to assign oneself to any card unless otherwise noted. New cards are created by discussing the
problem with mentors, either during stand-ups or directly – if approved, the mentor will create the
card and you can assign yourself to it.

### Definition of Done

A task is only considered fully done once it has been completed, submitted as a pull request, and
reviewed by two other students who approve it (see below). Once a mentor reviews it, it may be
considered fully complete, or potentially moved back to doing if unsatisfactory.

### Task Review

Two mandatory peer reviews must be completed before the mentor review. Once the pull request is
made, contact a teammate for a review and upon agreement, tag this teammate under the Teams Planner
card and GitHub pull request as the reviewer. Make sure to review and test the code syntax, logic,
and output through pulling the changes unto your local machine if you are the reviewer. If the
reviewer requests any changes, update the contribution, and notify the reviewer. Once the changes
are committed and pushed, it will automatically update the pull request; thus, there is no need to
make another pull request.
[Watch this tutorial video by Satika Jayawardena](https://deakin365.sharepoint.com/:v:/r/sites/ThothTech2/Shared%20Documents/OnTrack/Demo%20videos/pull-request-demo.mov?csf=1&web=1&e=a6p1gg&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
from the OnTrack team on creating and reviewing someone else’s pull request.

Once the peer review is complete and your contribution was deemed correct by your teammate, the pull
request may be moved into the Mentor Review column – in time, a mentor will review the work, and if
it is deemed satisfactory it will be considered complete and moved into the current sprint’s
Complete column.

### Testing

Testing strategies depend on the project – please see each project’s onboarding information for more
details.

### Branching Strategy

Refer to the Branch Prefixes and Commit Message Format sections of the
[Git Contributions Guide](https://thoth-tech.netlify.app/resources/quality-assurance/git-contributions-guide/)
for guidelines on creating Git branches and commits for contributions.

## Product Architecture

### SplashKit.io Website

The SplashKit.io website is the primary portal for developers and learners, offering a modern,
responsive interface built with Starlight (Astro), React, SolidJS, Tailwind CSS, Node.js, and
Docker. It provides users with access to API documentation, installation guides, and tutorials,
making it essential for anyone looking to learn or expand their knowledge of SplashKit. This website
supports external developers, especially beginners, in using SplashKit for 2D game development and
interactive applications.

### SplashKit SDK

The SplashKit SDK is a versatile toolkit designed to simplify 2D game development and interactive
application creation. It is primarily built using C++, SDL, and OpenGL, and is managed through CMake
and Clang/LLVM. The SDK supports cross-platform development on Windows, macOS, Linux, and Raspberry
Pi, allowing developers to create applications that run on multiple platforms using a single
codebase. Additionally, the SDK includes automated translation into C#, Python, and Pascal.

### SplashKit Online

SplashKit Online is a web-based Integrated Development Environment (IDE) that enables users to
write, compile, and run SplashKit projects directly in their browsers. It supports JavaScript and
experimental C++ through WebAssembly (WASM) via Emscripten. The platform uses Node/NPM for
dependency management and test server operation. SplashKit Online aims to make it easy for
developers, particularly beginners, to get started with SplashKit without needing to install any
software.

### Arcade Machine

The SplashKit-powered arcade machines, developed in collaboration with Deakin University, run on
Raspberry Pi using emulationstation and retropie. These machines allow students and developers to
upload and test games developed with SplashKit in a real-world arcade setting. The machines offer a
hands-on experience where games can be played and evaluated using physical arcade hardware.

### Game Development

The Game Development team produces games that showcase SplashKit's capabilities. These games are
typically built using C++ or C# and adhere to industry-standard game design practices. The games
serve as examples of what can be achieved using SplashKit, demonstrating various features of the
SDK, including graphics, input handling, and audio management.

## Source Code

- [Github Account](https://github.com/thoth-tech)
- Arcade Machine
  - [arcade-machine](https://github.com/thoth-tech/arcade-machine)
  - [arcade-machine-startup](https://github.com/thoth-tech/arcade-machine-startup)
  - [ArcadeMenu](https://github.com/thoth-tech/ArcadeMenu)
  - [flipper](https://github.com/thoth-tech/flipper)
- SplashKit Expansion
  - [splashkit-core](https://github.com/thoth-tech/splashkit-core),
    [skm](https://github.com/thoth-tech/skm)
- [SplashKit Website](https://github.com/thoth-tech/splashkit.io-starlight)
- [Games Development](https://github.com/thoth-tech/arcade-games)
- [SplashKit Online](https://github.com/thoth-tech/splashkitonline)

## Appendices

**_Include all relevant artefacts delivered during the course of the project. Anything that will
paint a clearer picture of your team’s progress this trimester, the things that informed decisions,
and the evolution of your product._**

**_Please also include a link to your team’s showcase video._**
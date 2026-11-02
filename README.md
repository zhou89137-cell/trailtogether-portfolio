# TrailTogether
### Outdoor activity discovery, shared memories, and event-day check-in

**University of Auckland · PGCertIT team project · 2026**  
**Portfolio by [zhou89137-cell](https://github.com/zhou89137-cell)**

TrailTogether is a team-built application for discovering outdoor activities, exploring event details, sharing activity photos, and supporting guests on the day of an event. It combines a web application with a Java desktop Door Station for attendance workflows.

My work connected the participant experience—from browsing activities and receiving emails—to the practical tasks of selecting guests, checking them in, and preparing name badges.

> This repository is a project case study. It contains documentation only; the team application's source code, participant data, and internal project materials are not distributed here.

## At a glance

| | |
| :--- | :--- |
| **Context** | University of Auckland postgraduate IT team project |
| **Product** | Outdoor activity platform with an event check-in desktop client |
| **My focus** | Homepage, activity detail page, photo gallery, email functionality, guest selection/check-in, and badge printing |
| **Technologies used in the project** | Svelte / SvelteKit, JavaScript, Node.js, Express, SQLite, Nodemailer, Java Swing |
| **Portfolio scope** | A description of the project and my contributions; no runnable application is included |

## The experience

**Discover → Explore → Receive event emails → Check in → Share memories**

Participants can browse activities, read event details, and view or share photos. Email functionality supports communication around invitations and confirmations. At the event, the Door Station provides a desktop workflow for finding guests, recording attendance, and preparing name badges.

## My contributions

| Area | What I worked on | Purpose |
| :--- | :--- | :--- |
| **Homepage** | Built the homepage and its activity discovery interface. | Give visitors a clear starting point for exploring activities. |
| **Activity detail page** | Developed the page presenting an individual activity and its related information. | Help participants understand an activity before taking the next step. |
| **Photo gallery** | Implemented the activity photo gallery / Photo Wall experience. | Bring shared event memories into the activity experience. |
| **Email functionality** | Worked on invitation and confirmation emails, including links back to the relevant activity or invitation. | Connect email communication with the web application. |
| **Door Station guest selection and check-in** | Added guest filtering, selection, and check-in for the selected guest in the Java desktop interface. | Help event staff locate a guest and record their arrival. |
| **Badge printing** | Added a selected-guest name-badge preview and printing workflow using the system print dialog. | Prepare a guest badge from the attendance interface. |

These are my contributions within a shared team project. Other application features and the overall product were developed collaboratively with teammates.

## How the pieces fit together

| Layer | Role in the project |
| :--- | :--- |
| **SvelteKit web application** | Activity browsing, detail pages, and photo gallery interactions |
| **Node.js / Express backend** | Application APIs and server-side workflows |
| **SQLite** | Application data storage |
| **Nodemailer** | Email delivery integration |
| **Java Swing Door Station** | Desktop guest selection, check-in, and name-badge interface |

This overview describes the project at a high level and omits deployment configuration, internal endpoints, and operational credentials.

## Engineering focus

- **Connected user journeys:** Link discovery, activity details, photos, and email entry points into a coherent experience.
- **Web and desktop integration:** Contribute to both the browser application and a Java desktop client serving event staff.
- **Practical interface design:** Keep guest selection, check-in, and badge preparation close together in the event-day workflow.
- **Team delivery:** Develop defined features within a shared application while keeping individual contribution and team ownership clear.

## Project status and access

TrailTogether was developed as an academic team project. This case study describes my contribution areas and does not claim production deployment, measured user adoption, or independent ownership of the full application.

Badge preview and the system printing integration are implemented; physical printer output is not presented here as a verified result.

No application demo, source-code download, or participant screenshots are included in this public portfolio.

## Connect

View my GitHub profile: **[zhou89137-cell](https://github.com/zhou89137-cell)**

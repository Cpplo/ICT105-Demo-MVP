# Lab 02 Opportunity Scanning

## Ideas Reviewed from Lab 1

| Idea | Problem Area | Target User | Current Alternative | Initial Technology Direction |
|---|---|---|---|---|
| Idea 1: AI Knowledge Management System | Organizations store large amounts of information; users spend too much time searching | Employees, students, administrators | Manual folder/drive search, asking colleagues | React, Node.js, OpenAI API, LangChain, Vector Database |
| Idea 2: Digital Identity & Credential Verification Platform | Fake certificates and slow manual verification reduce trust | Students, employers, universities | Manual email/phone verification, document review | React, Spring Boot, JWT, QR Code, Encryption |
| Idea 3: Student Freelancer Marketplace Platform | Students struggle to find freelance work; clients can't find affordable entry-level talent | University students, small businesses, startups | Fiverr, Upwork, social media groups | React, Spring Boot, PostgreSQL, AI Recommendation, WebSocket |

---

## Opportunity Discovery Table

| No. | Idea | Observed Problem | Target User | Current Alternative | Possible IT Solution | Feasible Technology |
|---|---|---|---|---|---|---|
| 1 | Student Freelancer Marketplace | University students with real skills (design, coding, writing) have no trusted platform to find paid freelance work and are forced to compete with professionals on platforms like Fiverr where they have no reviews or credibility | University students, small businesses | Fiverr, Upwork, Facebook/LINE groups | Student freelancer marketplace where profiles are tied to university affiliation, with a portfolio section and project listing board | HTML/CSS/JS, Google Forms, Google Sheets, GitHub Pages |
| 2 | Student Deadline Reminder Dashboard | Students juggle deadlines from multiple subjects across different platforms (LMS, LINE, email) and frequently miss submission dates because there is no single place that consolidates all their upcoming assignments | University students | Screenshots, manual notes, calendar apps | Student deadline reminder dashboard that aggregates all course deadlines in one view with color-coded urgency indicators | HTML/CSS/JS, Google Sheets (deadline data), Google Forms, GitHub Pages |
| 3 | Campus Lost-and-Found System | Students who lose personal items on campus (AirPods, water bottles, ID cards) have no structured way to report or search for lost items beyond posting in crowded LINE group chats where the message quickly gets buried | University students, campus security staff | LINE group chats, asking security manually | Campus lost-and-found web reporting system where students submit lost or found items via a form and browse an active item list | HTML/CSS/JS, Google Forms, Google Sheets, Airtable, GitHub Pages |
| 4 | AI Knowledge Management System | Employees and students waste hours every week searching through scattered folders, emails, and PDFs to find a specific piece of information that already exists inside the organization but is impossible to locate quickly | Employees, students, administrators | Manual folder search, asking colleagues, CTRL+F in documents | AI-powered document Q&A platform where users upload files and ask questions in plain language to get instant answers with source references | HTML/CSS/JS, OpenAI API (chat completion), Google Sheets as document index, Glitch for hosting |
| 5 | University Event Board | University students miss club events, workshops, and campus announcements because information is scattered across LINE groups, Facebook pages, and physical notice boards with no central place to browse or RSVP | University students, club administrators | LINE groups, Facebook posts, physical notice boards | Centralized university event board where clubs post events and students can browse and RSVP through a single web page | HTML/CSS/JS, Google Forms (event submission & RSVP), Google Sheets, GitHub Pages |
| 6 | Digital Credential Verification Platform | Employers and scholarship committees cannot quickly verify whether a job applicant's certificate or degree is genuine, leading to wasted time on manual calls and emails to institutions or the risk of accepting fraudulent credentials | Employers, HR departments, universities | Manual email/phone verification with institutions, which takes days | Digital credential verification platform where institutions issue QR-coded certificates that any employer can scan to confirm authenticity instantly | HTML/CSS/JS, Google Sheets (credential records), Google Forms, qrcode.js library, GitHub Pages |


---

## Technology Feasibility Mapping


| Idea | Prototype Type | Tools Needed | Data Needed | Difficulty | Feasible? |
|---|---|---|---|---|---|
| Idea 1: Student Freelancer Marketplace | Simple web app prototype with Google Sheets backend | HTML/CSS/JS, Google Forms (profile & project submission), Google Sheets (listings database), JavaScript fetch API to display listings, GitHub Pages for hosting | Student profiles (name, skills, university), project listings (title, budget, skill needed), client contact info | Low | Yes |
| Idea 2: Student Deadline Reminder Dashboard | Dashboard MVP connected to Google Sheets | HTML/CSS/JS, Google Forms (deadline entry), Google Sheets (deadline database), JavaScript fetch API, color-coded urgency display, GitHub Pages for hosting | Course names, assignment titles, due dates, subject codes, student year/major | Low | Yes |
| Idea 3: Campus Lost-and-Found System | Landing page MVP with Airtable item list | HTML/CSS/JS landing page, Google Forms (item report submission), Airtable (item database with filter by category/date), Airtable embed on page, GitHub Pages for hosting | Item name, description, location found/lost, date, photo link, contact info | Low | Yes |
| Idea 4: AI Knowledge Management System | Conceptual web prototype with API integration | HTML/CSS/JS frontend, OpenAI API (chat completion endpoint), Google Sheets as document index, Glitch for hosting | Sample internal documents (PDFs, notes), Q&A pairs for testing, user query examples | High | Partial |
| Idea 5: University Event Board | Simple web app prototype with Google Sheets backend | HTML/CSS/JS, Google Forms (event submission & RSVP), Google Sheets (event database), JavaScript fetch API to display events, GitHub Pages for hosting | Event name, date, time, location, organizer club, RSVP count, event description | Low | Yes |
| Idea 6: Digital Credential Verification Platform | Form-based MVP with QR code generation | HTML/CSS/JS, Google Forms (credential submission), Google Sheets (credential records), qrcode.js library for QR generation, GitHub Pages for hosting | Student name, institution, certificate type, issue date, unique credential ID | High | Partial |

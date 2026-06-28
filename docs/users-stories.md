# Lab 04 - User Stories and Acceptance Criteria

## User Story Format

**As a [user role], I want to [goal/action], so that [benefit/value].**

---

# User Stories

| Story ID | Role | User Story | Related Requirement | Priority | Acceptance Criteria | Demo Evidence |
|-----------|------|------------|---------------------|----------|---------------------|---------------|
| US-01 | Student | As a student, I want to register using my university email so that I can access the platform as a verified student. | FR-01 Student Registration | Must | Given a valid university email, when the student registers, then an account is successfully created. | Registration Page |
| US-02 | Student | As a student, I want to create and edit my profile so that clients can understand my background and skills. | FR-02 Student Profile | Must | Given a logged-in student, when profile information is saved, then the updated profile is displayed. | Student Profile |
| US-03 | Student | As a student, I want to upload my portfolio so that clients can evaluate my abilities. | FR-03 Portfolio Management | Must | Given portfolio files, when uploaded successfully, then they appear on the student's profile. | Portfolio Page |
| US-04 | Client | As a client, I want to post freelance projects so that qualified students can apply. | FR-04 Project Posting | Must | Given completed project details, when submitted, then the project is published. | Client Dashboard |
| US-05 | Student | As a student, I want to browse freelance projects so that I can find opportunities matching my skills. | FR-05 Browse Projects | Must | Given available projects, when browsing, then project details are displayed correctly. | Project Listing |
| US-06 | Student | As a student, I want to view a company's profile before applying so that I know the client is trustworthy. | FR-06 Company Profile | Must | Given a company profile exists, when opened, then company information, verification status, and contact details are displayed. | Company Profile Page |
| US-07 | Student | As a student, I want to read company ratings and reviews so that I can decide whether to apply. | FR-07 Company Reviews | Should | Given previous reviews exist, when viewing a company profile, then ratings and reviews are displayed. | Company Review Page |
| US-08 | Student | As a student, I want to apply for a freelance project so that I can gain experience and earn income. | FR-08 Project Application | Must | Given a selected project, when Apply is clicked, then the application is submitted successfully. | Application Page |
| US-09 | Client | As a client, I want to view student portfolios so that I can select suitable candidates. | FR-09 Portfolio Viewing | Must | Given a student's profile, when opened, then the student's portfolio and skills are displayed. | Student Portfolio |
| US-10 | Student & Client | As a user, I want to exchange messages so that we can discuss project details before starting work. | FR-10 Messaging | Should | Given both users are logged in, when a message is sent, then it appears in the conversation. | Chat Screen |
| US-11 | Client | As a client, I want to leave ratings and reviews after a completed project so that future students can trust my company. | FR-11 Company Rating | Should | Given a completed project, when a review is submitted, then it appears on the company profile. | Company Review Section |
| US-12 | Student | As a student, I want to receive ratings after completing projects so that I can build my reputation. | FR-12 Student Rating | Should | Given a completed project, when a client submits a review, then the rating appears on the student's profile. | Student Review Section |

---

# Acceptance Criteria Checklist

A good acceptance criterion should be:

- Testable
- Observable in the final prototype
- Connected to a functional requirement
- Supported by customer evidence
- Clear and measurable

---

# Future User Stories (Not Included in MVP)

| Story ID | Reason for Postponing | Future Condition |
|-----------|-----------------------|------------------|
| US-13 | As a student, I want AI to recommend projects based on my skills. | Future AI enhancement after MVP validation. |
| US-14 | As a student, I want secure online payments through the platform. | Requires payment gateway integration beyond the semester scope. |
| US-15 | As a client, I want to schedule video interviews with students. | Future communication enhancement. |
```


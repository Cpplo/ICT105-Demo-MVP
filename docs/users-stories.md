# Lab 04 - User Stories and Acceptance Criteria

## User Story Format

**As a [user role], I want to [goal/action], so that [benefit/value].**

---

# User Stories

| Story ID | Role | User Story | Related Requirement | Priority | Acceptance Criteria | Demo Evidence |
|-----------|------|------------|---------------------|----------|---------------------|---------------|
| US-01 | Student | As a student, I want to register using my university email so that clients know I am a verified student. | FR-01 Student Registration | Must | **Given** a valid university email, **when** the student registers, **then** the account is successfully created. | Registration page |
| US-02 | Student | As a student, I want to create and edit my profile so that clients can understand my skills and background. | FR-02 Student Profile | Must | Given a logged-in student, when profile information is saved, then the updated profile is displayed. | Student Profile |
| US-03 | Student | As a student, I want to upload my portfolio so that I can demonstrate my abilities to potential clients. | FR-03 Portfolio Management | Must | Given portfolio files, when uploaded successfully, then they appear on the student's profile. | Portfolio page |
| US-04 | Student | As a student, I want to browse available freelance projects so that I can find work related to my skills. | FR-04 Browse Projects | Must | Given available projects, when browsing the project list, then project details are displayed correctly. | Project Listing |
| US-05 | Student | As a student, I want to apply for a freelance project so that I can obtain real work experience. | FR-05 Project Application | Must | Given a selected project, when the Apply button is clicked, then the application is submitted successfully. | Application page |
| US-06 | Client | As a client, I want to post freelance projects so that students can apply for them. | FR-06 Project Posting | Must | Given completed project details, when submitted, then the project appears in the marketplace. | Client Dashboard |
| US-07 | Client | As a client, I want to review student portfolios before hiring so that I can choose suitable candidates. | FR-07 Portfolio Viewing | Must | Given a student's profile, when opened, then portfolio, skills, and achievements are displayed. | Student Portfolio |
| US-08 | Student & Client | As a user, I want to send messages so that I can communicate before starting a project. | FR-08 Messaging | Should | Given both users are logged in, when a message is sent, then it appears in the conversation. | Chat Screen |
| US-09 | Client | As a client, I want to leave ratings and reviews after project completion so that future users can trust student profiles. | FR-09 Ratings & Reviews | Should | Given a completed project, when a review is submitted, then it appears on the student's profile. | Review Page |
| US-10 | Student | As a student, I want to receive recommended projects based on my skills so that I can find suitable jobs more quickly. | FR-10 AI Project Recommendation | Could | Given the student's skill profile, when recommendations are generated, then related projects are displayed. | Recommendation Page |

---

# Acceptance Criteria Checklist

A good acceptance criterion should be:

- Testable
- Observable in the final prototype
- Connected to a functional requirement
- Supported by customer evidence
- Clear and measurable

---

# Rejected / Future User Stories

| Story ID | Reason for Postponing | Future Condition |
|-----------|-----------------------|------------------|
| US-11 | As a student, I want to receive payments directly through the platform. | Requires payment gateway integration beyond the scope of the semester MVP. |
| US-12 | As a client, I want to schedule video interviews with students. | Will be considered after the messaging feature is completed. |
| US-13 | As a student, I want AI to automatically review my portfolio and suggest improvements. | Planned as an advanced AI feature after the MVP is validated. |
| US-14 | As a client, I want to verify certificates using blockchain technology. | Outside the scope of the current semester project. |
```


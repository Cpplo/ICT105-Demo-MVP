# Lab 02 Opportunity Scanning

## Ideas Reviewed from Lab 1

| Idea | Problem Area | Target User | Current Alternative | Initial Technology Direction |
|---|---|---|---|---|
| Idea 1: AI Knowledge Management System | Organizations store large amounts of information; users spend too much time searching | Employees, students, administrators | Manual folder/drive search, asking colleagues | React, Node.js, OpenAI API, LangChain, Vector Database |
| Idea 2: Digital Identity & Credential Verification Platform | Fake certificates and slow manual verification reduce trust | Students, employers, universities | Manual email/phone verification, document review | React, Spring Boot, JWT, QR Code, Encryption |
| Idea 3: Student Freelancer Marketplace Platform | Students struggle to find freelance work; clients can't find affordable entry-level talent | University students, small businesses, startups | Fiverr, Upwork, social media groups | React, Spring Boot, PostgreSQL, AI Recommendation, WebSocket |

---

## Opportunity Discovery Table

### Idea 1: AI Knowledge Management System

| No. | Observed Problem | Target User | Current Alternative | Possible IT Solution | Feasible Technology |
|---|---|---|---|---|---|
| 1 | Employees spend 30–40% of their workday searching for documents, emails, or past decisions stored across multiple platforms (Google Drive, Slack, email, Notion) | Employees, knowledge workers | Manually browsing folders or asking teammates | AI-powered unified search that indexes all connected platforms and retrieves answers in natural language | React frontend, OpenAI API, LangChain, Vector Database (Pinecone/Weaviate) |
| 2 | When a key employee leaves, their institutional knowledge — how things were decided, why processes exist — is lost forever with no structured capture mechanism | HR managers, team leads, organizations | Exit interviews, informal documentation | AI system that continuously captures knowledge from chats, documents, and meetings into a searchable knowledge base | Node.js backend, OpenAI API, MongoDB, LangChain |
| 3 | New hires take weeks to onboard because internal knowledge is scattered, outdated, or impossible to find without asking a senior colleague | New employees, HR, onboarding teams | Onboarding documents, asking colleagues, wikis | AI onboarding assistant that answers questions about company processes from verified internal documents | React, Node.js, OpenAI API, Vector Database |
| 4 | Students working on group projects re-read the same papers, notes, and slides repeatedly to find a specific fact or quote, wasting hours of study time | University students, researchers | Ctrl+F in PDFs, rereading notes manually | AI document Q&A tool that lets students ask questions directly to their uploaded course materials | React, OpenAI API (with file upload), Node.js |
| 5 | Legal, compliance, and finance teams waste hours reviewing long policy documents to answer a single question, increasing operational risk from missed updates | Compliance officers, legal teams, administrators | Manual document review, CTRL+F, consulting lawyers | AI policy Q&A system that ingests regulatory and internal policy documents and answers queries with citations | LangChain, OpenAI API, React, Node.js, Vector Database |
| 6 | Research teams duplicate effort because there is no easy way to query what has already been studied, tested, or concluded in past internal reports | R&D teams, academic researchers, project managers | Spreadsheet logs, email searches, manual folder browsing | AI-powered internal research repository with semantic search and auto-tagging of findings | React, OpenAI Embeddings, LangChain, Pinecone, Node.js |

---

### Idea 2: Digital Identity & Credential Verification Platform

| No. | Observed Problem | Target User | Current Alternative | Possible IT Solution | Feasible Technology |
|---|---|---|---|---|---|
| 1 | Employers cannot quickly verify whether a job applicant's university degree or professional certificate is genuine, leading to costly fraudulent hires | Employers, HR departments | Phone/email verification with the issuing institution, which takes days | Digital credential platform where institutions issue tamper-proof certificates with QR codes verifiable instantly online | React, Spring Boot, QR code library, PostgreSQL, JWT, Encryption |
| 2 | Students who earned certifications from multiple institutions carry stacks of paper documents that can be lost, damaged, or easily forged | University graduates, professional certificate holders | Physical certificates, scanned PDF copies sent via email | Digital wallet where all verified credentials are stored and shareable via a secure link or QR code | React, Spring Boot, Cloud Storage, JWT, QR Code |
| 3 | Universities and training providers spend significant staff time manually responding to verification requests from employers or other institutions | University registrar offices, certification bodies | Manual email replies, phone verification hotlines | Self-service verification portal where third parties scan a QR code and get instant confirmation without contacting the institution | HTML/CSS/JS, Spring Boot, PostgreSQL, QR Code API |
| 4 | Online course platforms issue certificates that hiring managers distrust because there is no authoritative way to check if a specific person genuinely completed the course | Online learners, EdTech platforms, employers | Trusting the PDF at face value, or emailing the platform | Blockchain-anchored or cryptographically signed digital badges that any employer can verify without contacting the platform | React, Spring Boot, SHA-256 hashing, QR Code, PostgreSQL |
| 5 | Immigration and visa officers or background check agencies struggle to verify foreign academic credentials efficiently, causing long processing delays for applicants | Immigration officers, background check agencies, international students | Slow manual apostille processes, document translation, embassy verification | Cross-border digital credential verification network with multi-language support and institution registry | React, Spring Boot, REST API, JWT, PostgreSQL, i18n |
| 6 | Students participating in internship or scholarship applications have credentials rejected or delayed because companies cannot confirm them in real time during evaluation | Students, internship coordinators, scholarship committees | Emailing scanned copies and waiting for manual replies | Real-time credential sharing link that expires after a set period, letting students grant temporary view access to verifiers | React, Spring Boot, JWT time-limited tokens, QR Code, PostgreSQL |

---

### Idea 3: Student Freelancer Marketplace Platform

| No. | Observed Problem | Target User | Current Alternative | Possible IT Solution | Feasible Technology |
|---|---|---|---|---|---|
| 1 | University students with real skills (design, coding, writing, video editing) have no credible platform to showcase their work and attract paying clients, so they go unpaid or underpaid on generic platforms where they cannot compete with experienced professionals | University students with digital skills | Fiverr, Upwork, or posting in Facebook/LINE groups with no visibility | Student-focused freelance marketplace where profiles are tied to university affiliation and portfolio projects, building credibility for entry-level talent | React, Spring Boot, PostgreSQL, AWS S3 for portfolio files |
| 2 | Small businesses and startups need affordable creative or technical help for short tasks but cannot justify the high rates or complexity of enterprise freelance platforms | Small business owners, startups, NGOs | Fiverr (often overpriced for simple tasks), posting in social media groups | Lightweight marketplace matching budget-conscious clients with student freelancers at student-friendly rates, with AI-assisted project-matching | React, Spring Boot, PostgreSQL, AI Recommendation engine |
| 3 | Students complete freelance work informally via LINE or Facebook messages with no contract, no payment protection, and no formal record — leading to unpaid work and disputes | University students doing informal freelance work | Verbal agreements, PayPal friends transfer, informal chat | Marketplace with built-in milestone-based payment escrow, simple contracts, and dispute resolution so both parties are protected | React, Spring Boot, PostgreSQL, Payment API (PromptPay/Stripe), WebSocket |
| 4 | Students have no structured way to collect reviews or build a professional reputation from their freelance work, making each new gig feel like starting from zero with zero social proof | Student freelancers seeking repeat clients | LinkedIn recommendations (not gig-specific), informal word of mouth | Verified review and reputation system within the platform where past clients leave ratings linked to specific completed projects | React, Spring Boot, PostgreSQL, Star-rating component |
| 5 | University career centers have no visibility into students' real-world freelance experience, meaning valuable practical work history is invisible on official academic records | Career center staff, academic advisors, employers reviewing CVs | Students self-reporting on CVs, which cannot be verified | Platform integration with career centers that generates verified freelance experience reports students can attach to job applications | React, Spring Boot, REST API, PDF generation, PostgreSQL |
| 6 | Students working on academic projects (capstone, thesis, competitions) need specialized peer help — design, coding, data analysis — but there is no trusted campus-level place to find and hire fellow students for short-term collaboration | Students needing project help, student clubs, academic teams | Asking in class group chats, posting on faculty boards, hoping a friend can help | Campus-scoped freelance board where students post micro-tasks with clear deliverables and deadlines, filtered by university and skill set | React, Spring Boot, PostgreSQL, WebSocket for real-time notifications |

---

## Technology Feasibility Mapping

### Idea 1: AI Knowledge Management System

| Idea | Prototype Type | Tools Needed | Data Needed | Difficulty | Feasible? |
|---|---|---|---|---|---|
| 1.1: Unified Document Search | Conceptual web prototype with API | React, OpenAI API, LangChain, Pinecone | Sample documents from Google Drive / email / Notion | High | Partial |
| 1.2: Knowledge Capture System | Backend prototype with API | Node.js, OpenAI API, LangChain, MongoDB | Chat logs, meeting transcripts, decision records | High | Partial |
| 1.3: AI Onboarding Assistant | Simple web app prototype | React, Node.js, OpenAI API, Vector Database | Company policy docs, onboarding guides, FAQ pairs | Medium | Yes |
| 1.4: Student Document Q&A Tool | Simple web app prototype with API | React, OpenAI API (file upload), Node.js | Sample lecture slides, PDFs, course notes | Medium | Yes |
| 1.5: AI Policy Q&A System | Conceptual web prototype with API | LangChain, OpenAI API, React, Node.js, Vector Database | Internal policy documents, regulatory PDFs | High | Partial |
| 1.6: Internal Research Repository | Conceptual web prototype with API | React, OpenAI Embeddings, LangChain, Pinecone, Node.js | Past research reports, findings summaries | High | Partial |

### Idea 2: Digital Identity & Credential Verification Platform

| Idea | Prototype Type | Tools Needed | Data Needed | Difficulty | Feasible? |
|---|---|---|---|---|---|
| 2.1: Credential Verification Portal | Form-based MVP with QR code | React, Spring Boot, QR code library, PostgreSQL, JWT | Credential records, institution data, employer accounts | High | Partial |
| 2.2: Digital Credential Wallet | Simple web app prototype | React, Spring Boot, Cloud Storage, JWT, QR Code | Student profiles, certificate metadata, issuing institutions | High | Partial |
| 2.3: Self-Service Verification Portal | Landing page MVP | HTML/CSS/JS, Spring Boot, PostgreSQL, QR Code API | Institution registry, credential records | Medium | Yes |
| 2.4: Signed Digital Badge System | Conceptual prototype | React, Spring Boot, SHA-256 hashing, QR Code, PostgreSQL | Course completion records, platform issuer data | High | Partial |
| 2.5: Cross-Border Verification Network | Conceptual prototype | React, Spring Boot, REST API, JWT, PostgreSQL, i18n | Foreign institution registry, multilingual credential data | High | No |
| 2.6: Time-Limited Credential Sharing | Form-based MVP | React, Spring Boot, JWT time-limited tokens, QR Code, PostgreSQL | Student credentials, verifier accounts, expiry rules | Medium | Yes |

### Idea 3: Student Freelancer Marketplace Platform

| Idea | Prototype Type | Tools Needed | Data Needed | Difficulty | Feasible? |
|---|---|---|---|---|---|
| 3.1: Student Portfolio Marketplace | Simple web app prototype | React, Spring Boot, PostgreSQL, AWS S3 | Student profiles, portfolio samples, project listings | Medium | Yes |
| 3.2: AI-Matched Freelance Platform | Simple web app prototype | React, Spring Boot, PostgreSQL, AI Recommendation engine | Project listings, student skill profiles, client budgets | Medium | Yes |
| 3.3: Escrow & Contract Marketplace | Full web app prototype | React, Spring Boot, PostgreSQL, Payment API (PromptPay/Stripe), WebSocket | Project milestones, payment records, dispute logs | High | Partial |
| 3.4: Reputation & Review System | Dashboard MVP | React, Spring Boot, PostgreSQL, Star-rating component | Completed project records, client accounts, ratings data | Low | Yes |
| 3.5: Career Center Integration | Simple web app prototype | React, Spring Boot, REST API, PDF generation, PostgreSQL | Freelance project history, student IDs, career center accounts | Medium | Yes |
| 3.6: Campus Micro-Task Board | Simple web app prototype | React, Spring Boot, PostgreSQL, WebSocket | Task listings, student profiles, university registry | Low | Yes |

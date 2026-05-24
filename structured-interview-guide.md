# Structured Interview Guide — Animal Ark Stakeholders


## Purpose

The purpose of this interview guide is to support structured fact-finding sessions with Animal Ark stakeholders. The guide is designed to collect consistent information about the current workflow, operational challenges, user expectations, and system requirements for the proposed Animal Ark system.

The interview findings will support the Software Requirements Specification (SRS), especially the existing system analysis, stakeholder analysis, use case identification, functional requirements, and non-functional requirements.

---

## Interview Objectives

1. Understand the current operational workflow of Animal Ark.
2. Identify pain points in animal intake, treatment tracking, volunteer coordination, medicine stock, emergency handling, donations, and adoption.
3. Understand stakeholder expectations for the proposed system.
4. Identify system users, user roles, permissions, and responsibilities.
5. Collect evidence for SRS requirements, use cases, and system constraints.
6. Validate whether the proposed system modules match real stakeholder needs.

---

## Interview Method

| Field | Details |
|---|---|
| Method | Structured interview |
| Target Stakeholders | Animal Ark committee members, volunteer vet students, supervising doctors, medicine/donation handlers, donors, adopters, and public supporters |
| Expected Duration | 30–45 minutes per session |
| Format | In-person or online meeting |
| Recording | Only with permission |
| Notes | Notes should be written during the session and cleaned up within 24 hours |
| Privacy | Personal names may be withheld when documenting findings |

---

## Stakeholder Categories

| Stakeholder Category | Reason for Interview |
|---|---|
| Society Committee / Admins | To understand overall operations, decision-making, reporting needs, and system administration requirements. |
| Volunteer Vet Students | To understand daily treatment workflow, handover problems, emergency awareness, and usability expectations. |
| Supervising Doctors / Faculty Advisors | To understand treatment supervision, approval points, clinical accountability, and access control needs. |
| Medicine Stock Handler / Treasurer | To understand medicine inventory, expiry tracking, donations, receipts, and financial transparency needs. |
| Donors / Public Supporters | To understand donation expectations, transparency needs, sponsorship preferences, and public engagement. |
| Adopters / Potential Adopters | To understand adoption information needs, request process expectations, and follow-up requirements. |
| Public Reporters / Animal Lovers | To understand how injured or stray animals are reported and how public users expect to interact with the system. |

---

## General Interview Opening Script

Thank you for participating in this interview. We are collecting requirements for the proposed Animal Ark system, which aims to improve how Animal Ark manages animal treatment, volunteer coordination, medicine stock, emergency support, donations, and adoption activities.

Your responses will be used only for academic requirement analysis and system design purposes. Personal names can be withheld in the documentation if preferred. There are no right or wrong answers; we are interested in understanding the actual workflow, challenges, and expectations.

---

## Section A — Questions for Society Committee / Admins

### A1. Current Operations

1. Can you briefly describe the main activities handled by Animal Ark?
2. What happens from the moment a stray or injured animal is reported?
3. Who decides whether an animal case should be accepted?
4. What information is recorded when a new animal case is started?
5. How are animal case records currently stored?
6. Who is responsible for checking whether records are complete?
7. What are the most common operational problems faced by the society?

### A2. Volunteer Coordination

1. How are volunteers assigned to animal care tasks?
2. Is there a fixed shift schedule, or do volunteers participate based on availability?
3. How does the committee know who completed a task?
4. How are incomplete tasks followed up?
5. What problems occur when volunteers miss updates or fail to record work?
6. Would volunteer activity tracking be useful for the society?
7. Should the system include volunteer recognition or contribution statistics?

### A3. System Expectations

1. What are the top three problems the proposed system should solve first?
2. Which current manual processes should be digitized?
3. What system modules are most important for the committee?
4. What information should only be visible to admins or authorized users?
5. What reports would help the committee manage Animal Ark better?
6. What concerns do you have about using a digital system?
7. What would make the system easy for committee members and volunteers to use?

---

## Section B — Questions for Volunteer Vet Students

### B1. Daily Workflow

1. How do you usually find out what Animal Ark tasks need to be done?
2. What activities do you usually perform as a volunteer?
3. How do you know which animal needs treatment or follow-up?
4. How do you know whether another volunteer has already treated an animal?
5. What information do you need before starting treatment or care?
6. How are animal condition updates communicated between volunteers?
7. What is the most difficult part of the current workflow?

### B2. Treatment Tracking and Handover

1. How are treatment details currently recorded?
2. Are treatment notes always complete and easy to understand?
3. Have you experienced missing, unclear, or duplicated treatment information?
4. What details should be included in a treatment record?
5. Should treatment notes be mandatory before a task is marked as complete?
6. How important is a treatment timeline for each animal?
7. What problems happen when handover information is missing?

### B3. Emergency Handling

1. How do you usually find out about emergency animal cases?
2. What information should be included in an emergency alert?
3. How quickly do volunteers usually respond to emergency cases?
4. What causes delays in emergency response?
5. Should emergency notifications be sent instantly to selected volunteers?
6. Who should be responsible for assigning emergency tasks?
7. How should emergency case status be updated?

### B4. Technology Readiness

1. Are you comfortable using a mobile-friendly or web-based system?
2. Would you prefer a mobile app or a browser-based system?
3. How long should it take to record treatment information for one animal?
4. What would discourage volunteers from using the system?
5. What features would make the system easier to use?
6. Should the system work well on smartphones?
7. What training or guidance would volunteers need?

---

## Section C — Questions for Supervising Doctors / Faculty Advisors

### C1. Clinical Supervision

1. How are supervising doctors currently assigned to animal cases?
2. At what stage should a supervisor be assigned?
3. What treatment decisions require supervisor approval?
4. How do supervisors currently monitor animal progress?
5. What information should supervisors see before approving treatment decisions?
6. What problems occur when clinical records are incomplete?
7. Should supervisors be able to close or discharge animal cases in the system?

### C2. Treatment and Accountability

1. What treatment details must always be recorded?
2. Should the system record which volunteer performed each treatment action?
3. Should the system maintain a full medical timeline for each animal?
4. How should medicine dosage and prescription details be recorded?
5. Should treatment records be editable after submission?
6. If corrections are needed, how should they be handled?
7. What access restrictions are needed for clinical information?

### C3. System Expectations

1. What features would improve clinical accountability?
2. What reports would be useful for supervisors or faculty advisors?
3. What notifications should supervisors receive?
4. What risks should the system avoid?
5. What privacy or ethical concerns should be considered?
6. What information should not be visible to public users?
7. What would make the system reliable enough for treatment-related use?

---

## Section D — Questions for Medicine Stock Handler / Treasurer

### D1. Medicine Stock Management

1. How is medicine stock currently recorded?
2. Who is responsible for updating medicine stock?
3. How is medicine usage recorded after treatment?
4. How often is stock physically checked?
5. How are expiry dates tracked?
6. How are low-stock situations identified?
7. What problems occur in the current medicine stock process?

### D2. Inventory Requirements

1. What information should be stored for each medicine or supply item?
2. Should the system track quantity, expiry date, batch number, and storage location?
3. Should the system automatically reduce stock after treatment usage is recorded?
4. What stock level should trigger a low-stock alert?
5. Who should receive low-stock or expiry alerts?
6. Should donated medicines be recorded separately?
7. What medicine usage reports would be useful?

### D3. Donations and Finance

1. What types of donations does Animal Ark receive?
2. How are cash, bank transfer, and in-kind donations recorded?
3. Are donors given receipts or acknowledgements?
4. What problems occur in the current donation tracking process?
5. Should the system support animal-specific donation campaigns?
6. What donation reports are needed for transparency?
7. What information should be included in a donor record?

---

## Section E — Questions for Donors / Public Supporters

### E1. Donation Expectations

1. What would encourage you to donate to Animal Ark?
2. Would you prefer donating to a general fund or a specific animal case?
3. What information would you want before donating?
4. What would make you confident that your donation is used properly?
5. Would you expect an official receipt or acknowledgement?
6. Would recovery updates encourage future donations?
7. What payment or donation methods would you prefer?

### E2. Public Website Expectations

1. What information should be visible to the public?
2. Would you like to see animal recovery stories?
3. Would you like to see donation campaign progress?
4. Would you register your pet as a potential blood donor if the process was simple?
5. What concerns would you have about sharing your contact details?
6. What information would help you trust Animal Ark online?
7. What features would encourage you to support the society?

---

## Section F — Questions for Adopters / Potential Adopters

### F1. Adoption Information Needs

1. What information would you want before adopting an animal?
2. Would photos and recovery stories help your decision?
3. Should the adoption profile include health and vaccination status?
4. Should the profile include temperament and special care requirements?
5. What information should not be shown publicly?
6. How would you prefer to submit an adoption request?
7. What would make the adoption process easier and clearer?

### F2. Adoption Process

1. Have you adopted or tried to adopt an animal before?
2. What problems did you face during the adoption process?
3. Should adoption requests be reviewed by Animal Ark before approval?
4. What information should be collected from adopters?
5. Should the system support post-adoption follow-up?
6. What updates would adopters expect after submitting a request?
7. What would make you trust the adoption process?

---

## Section G — Questions for Public Reporters / Animal Lovers

### G1. Reporting Stray or Injured Animals

1. How would you currently report a stray or injured animal to Animal Ark?
2. What information would you be able to provide when reporting an animal?
3. Would you be willing to upload photos and location details?
4. Should the system allow public users to report emergency cases?
5. What response updates would you expect after reporting a case?
6. What concerns would you have when submitting a report?
7. What would make the reporting process simple and trustworthy?

---

## Common Closing Questions for All Stakeholders

1. What is the biggest problem Animal Ark faces in the current process?
2. Which part of the workflow should be improved first?
3. What features are essential for the first version of the system?
4. Are there any features that should be avoided?
5. What information should be protected or restricted?
6. What reports, alerts, or dashboards would be useful?
7. Is there anything else you would like to suggest for the proposed Animal Ark system?

---

## Mapping to SRS Areas

| Interview Topic | Related SRS Area |
|---|---|
| Animal intake workflow | Existing system analysis, use cases, functional requirements |
| Volunteer coordination | User classes, workflow analysis, system roles |
| Treatment tracking | Functional requirements, treatment use cases, data requirements |
| Emergency handling | Functional requirements, notification requirements, non-functional requirements |
| Medicine stock | Functional requirements, inventory module, reporting |
| Donations | Donation management requirements, public portal requirements |
| Adoption | Adoption use cases, public user requirements |
| Privacy and access control | Non-functional requirements, security requirements |
| Reports and analytics | Reporting requirements, admin requirements |
| Usability expectations | Non-functional requirements, usability constraints |

---

## Interview Evidence Template

After each interview, the following evidence should be saved in the research repository.

| Evidence Item | Description |
|---|---|
| Interview date | Date of the interview |
| Participants | Interviewer, note-taker, and stakeholder role |
| Notes / transcript | Summary of answers and important quotes |
| Key findings | Main findings extracted from the interview |
| Pain points | Problems identified from stakeholder responses |
| SRS inputs | Requirements, use cases, or constraints derived from the interview |
| Review status | Whether the notes were reviewed by the team |

Recommended file naming format:

```txt
research/interviews/client-interview-01.md
research/interviews/client-interview-02.md
research/interviews/stakeholder-interview-summary.md
```

---


## Acceptance Criteria Mapping

| Acceptance Criteria | How This Document Satisfies It |
|---|---|
| AC1: Interview questions are prepared for all major stakeholders. | Questions are prepared for committee/admins, volunteer vet students, supervising doctors, medicine/donation handlers, donors, adopters, and public reporters. |
| AC2: Questions cover operational workflow, challenges, and expectations. | Questions cover current workflow, problems, system expectations, reporting, privacy, and usability. |
| AC3: Questions are organised clearly by topic or stakeholder role. | The guide is divided into stakeholder-based sections and topic-based subsections. |
| AC4: Interview guide is uploaded to the research repository. | The document should be committed to `research/interviews/structured-interview-guide.md`. |

---



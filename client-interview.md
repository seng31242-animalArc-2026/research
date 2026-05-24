# Client Interview  — Animal Ark Workflow and Operational Challenges

## Interview Details

| Field | Details |
|---|---|
| Interview Reference | AA-INT-01 |
| Date | 2026-05-22 |
| Time | 10:00 AM – 11:15 AM |
|  Platform | Google Meet |
| Interviewer(s) | J. A. U. Saubhagya |
| Note-taker | D. D. N. De Silva |
| Stakeholder(s) | President and Treasurer, Animal Ark Volunteering Student Society |
| Duration | Approximately 75 minutes |
| Consent | Personal names withheld. Notes used only for academic requirement analysis. |
| Related Issue | #10 |

---

## Objective

The objective of this interview was to understand the current Animal Ark workflow, operational challenges, and expectations for the proposed Animal Ark system.

The interview focused on how the society currently manages animal intake, volunteer coordination, treatment records, medicine stock, emergency communication, donations, and adoption activities. The findings are intended to support the SRS problem statement, existing system analysis, pain point identification, and functional requirement preparation.

---

## Topics Covered

- Stray and injured animal intake
- Animal case management
- Volunteer coordination
- Treatment recording and follow-up
- Medicine stock management
- Emergency handling
- Donation tracking
- Blood donor pet support
- Adoption process
- System expectations and usability concerns

---

## Interview Notes

### 1. Stray Animal Intake

Animal intake currently starts when a stray, injured, or road-accident animal is brought to the facility or reported to Animal Ark members. The admitting volunteer records the animal details using a physical paper intake form kept in a ring binder.

The intake form usually includes the animal species, estimated age, condition on arrival, and location where the animal was found. However, the quality of the records is inconsistent. Some volunteers complete the form properly, while others only write brief details.

Supervisor assignment is informal. A WhatsApp message is sent to a relevant faculty supervisor depending on availability and the animal’s condition. There is no formal assignment record. This has created confusion in some cases, where more than one supervisor assumed the other was responsible for a case.

Each animal receives a handwritten case number, but there is no centralized digital record linking the case number with the intake form, treatment notes, medicine usage, and final outcome.

---

### 2. Volunteer Coordination

Animal Ark does not operate using fixed volunteer shifts. Volunteers are full-time students and usually visit the facility when they have free time between lectures, during evenings, weekends, or other available times.

Because there is no fixed rota or scheduled shift system, volunteer attendance is unpredictable. Some days may have several volunteers visiting independently, while on other days only one volunteer may visit, or no one may visit at all.

Volunteer coordination is mostly handled informally through communication between members and WhatsApp updates. There is no central system to show who visited, who completed which task, or which animal still needs attention.

This creates a visibility and accountability issue. Volunteers arriving later cannot easily know what has already been done unless the previous volunteer has written clear notes.

---

### 3. Treatment Recording

Treatment details are currently written in physical folders. Volunteers are expected to update treatment notes after giving medicine or completing care tasks. However, this is not strictly enforced.

There is no central view showing which animals need treatment, which treatments are overdue, or what the previous volunteer did. Treatment notes are not accessible remotely, so volunteers must physically check folders at the facility.

A major problem occurs when treatment actions are not recorded clearly. One reported incident involved a dog on a three-day antibiotic course. A volunteer gave the morning dose but did not record it clearly. Another volunteer later checked the folder, found no clear note, and gave the dose again. The animal was not harmed, but the incident showed the risk of double-dosing.

The main requirement identified from this area is the need for immediate digital treatment logging so that every volunteer can see the latest treatment history before taking action.

---

### 4. Medicine Stock Management

Medicine stock is mainly handled by the Treasurer. Purchases are recorded in a physical ledger with the date, medicine name, quantity, and cost. However, medicine dispensing is usually recorded inside each animal’s treatment folder and not always updated in the central stock ledger.

As a result, the stock ledger becomes inaccurate quickly. The Treasurer performs a physical medicine count approximately every two weeks to understand the actual available stock.

Expiry dates are not systematically tracked. Some expired medicines have remained on the shelf unnoticed. Reorder decisions are also informal, usually handled by messaging pharmacy contacts when an item appears to be low.

There is no batch or lot number tracking. This creates a traceability problem if a medicine recall or contamination issue occurs, because the society cannot easily identify which animals received a particular batch.

---

### 5. Emergency Handling

Emergency cases are currently handled through informal communication, mainly WhatsApp messages and group broadcasts. There is no formal on-call roster, official emergency contact number, or structured emergency alert system.

This creates delays because the team must wait until an available volunteer sees the message and responds. Emergency response may take longer when messages are missed, volunteers are unavailable, or responsibility is unclear.

The interview highlighted the need for faster emergency communication, clear responsibility assignment, and a structured way to track emergency cases from report to response.

---

### 6. Donations

Animal Ark receives monetary and in-kind donations. Monetary donations may be received as cash, bank transfers, or personal payment app transfers. In-kind donations may include food, medicines, equipment, and other supplies.

Donation tracking is currently informal. Some donors receive a WhatsApp thank-you message, while others may not receive a formal acknowledgement. There is no standardized receipt generation process.

In-kind donations are not always recorded properly. Some records are maintained in personal notes, but they are incomplete. This makes it difficult to maintain transparency and prepare donation summaries.

The interview also identified the need for animal-specific donation campaigns, such as campaigns for surgery or recovery support. A structured donation module could help donors understand how their contributions are used.

---

### 7. Adoption Activities

When an animal recovers, the supervisor doctor makes the clinical discharge decision. The committee then decides whether the animal should be adopted, returned to its found location, or transferred to a permanent shelter.

The adoption announcement process is currently informal. Committee members usually post a photo and short description as a WhatsApp status. Interested people reply to the status.

This method has several limitations. WhatsApp statuses disappear after 24 hours, there is no searchable public adoption listing, and there is no structured adoption request form. This reduces the visibility of animals available for adoption.

There is also no proper adoption history record. The committee cannot easily review how many animals were adopted, who adopted them, or whether follow-up was completed.

---

### 8. General Challenges

The main challenges identified during the interview are related to manual records, scattered communication, lack of centralized visibility, and missing accountability.

Current information is distributed across paper forms, physical folders, ledgers, personal notebooks, and WhatsApp messages. This makes it difficult to retrieve complete animal histories, track treatment actions, monitor stock, provide donor transparency, and manage adoption outcomes.

The stakeholders emphasized that the proposed system should be simple to use. Volunteers are busy with academic work, so the system should not require long training. It should also work through a web or mobile-friendly interface without requiring compulsory app installation.

Public users should not be able to view animal medical details. Only suitable public-facing information, such as adoption profiles, should be visible.

---

## Key Findings

| # | Finding | Severity | Source |
|---|---|---|---|
| KF-01 | Animal intake records are paper-based and inconsistent in quality. | Critical | Section 1 |
| KF-02 | Supervisor assignment is informal and has no written record. | Critical | Section 1 |
| KF-03 | Volunteer attendance is flexible and unpredictable, making coordination difficult. | Critical | Section 2 |
| KF-04 | Treatment notes are physical, fragmented, and not accessible remotely. | Critical | Section 3 |
| KF-05 | Treatment logging is not enforced, creating a risk of missed or duplicated treatment. | Critical | Section 3 |
| KF-06 | A double-dosing incident occurred because treatment notes were unclear. | High | Section 3 |
| KF-07 | Emergency communication depends mainly on WhatsApp messages. | Critical | Section 5 |
| KF-08 | There is no formal emergency roster or structured alert mechanism. | High | Section 5 |
| KF-09 | Medicine stock records become inaccurate because usage is not centrally updated. | High | Section 4 |
| KF-10 | Expiry dates and batch numbers are not systematically tracked. | High | Section 4 |
| KF-11 | Donation tracking and receipting are informal. | High | Section 6 |
| KF-12 | In-kind donations are not consistently recorded. | Medium | Section 6 |
| KF-13 | There is no formal blood donor pet database. | Critical | Section 6 |
| KF-14 | Adoption announcements depend on temporary WhatsApp statuses. | High | Section 7 |
| KF-15 | There is no structured adoption history or follow-up record. | Medium | Section 7 |

---

## Pain Points Identified

| Area | Pain Point | Impact | Related Module |
|---|---|---|---|
| Animal intake | Intake records are paper-based and inconsistent. | Complete animal history is difficult to maintain. | Animal Registration |
| Supervisor assignment | Supervisor responsibility is assigned informally. | Confusion and conflicting decisions may occur. | Case Management |
| Volunteer coordination | Volunteers visit at unpredictable times without a central task view. | Tasks may be missed, duplicated, or delayed. | Volunteer Coordination |
| Treatment tracking | Treatment notes are written in physical folders and are not always updated. | Treatment continuity is weak and clinical errors may occur. | Treatment Management |
| Emergency handling | Emergency communication depends on WhatsApp and informal responses. | Urgent cases may be delayed. | Emergency Alert Management |
| Medicine stock | Stock ledger is not updated in real time. | Actual stock levels are uncertain. | Medicine Stock Management |
| Medicine expiry | Expiry dates and batch numbers are not systematically tracked. | Expired medicine or untraceable medicine usage may occur. | Medicine Stock Management |
| Donations | Donations and acknowledgements are handled informally. | Transparency and donor confidence are reduced. | Donation Management |
| Blood donors | No structured blood donor pet database exists. | Finding emergency blood donors is slow. | Blood Donor Management |
| Adoption | Adoption is promoted mainly through WhatsApp status updates. | Suitable adopters may miss available animals. | Adoption Management |
| Adoption history | Adoption outcomes and follow-ups are not centrally recorded. | Long-term adoption tracking is difficult. | Adoption Management |

---

## Possible SRS Inputs

| Requirement Area | Possible Requirement |
|---|---|
| Animal registration | The system shall allow authorized users to register rescued animals with species, estimated age, found location, condition, photos, and case ID. |
| Animal profile | The system shall maintain a centralized profile for each animal, including intake details, treatment history, medicine usage, current status, and final outcome. |
| Supervisor assignment | The system shall allow a supervisor or responsible authority to be assigned to each animal case. |
| Treatment records | The system shall allow volunteers to record treatment actions immediately after completing them. |
| Treatment visibility | The system shall display the latest treatment history and pending care tasks for each animal. |
| Mandatory treatment log | The system shall require treatment notes before a treatment task can be marked as completed. |
| Emergency alerts | The system shall send emergency notifications to relevant volunteers or responsible users when an urgent case is reported. |
| Emergency case tracking | The system shall allow emergency cases to be logged, prioritized, assigned, and tracked until resolution. |
| Medicine stock | The system shall record medicine name, quantity, expiry date, batch number, usage, and reorder threshold. |
| Stock alerts | The system shall notify responsible users when medicine stock is low or nearing expiry. |
| Donation records | The system shall record cash, bank transfer, and in-kind donations with donor details, date, purpose, and acknowledgement status. |
| Donation campaigns | The system shall support animal-specific donation campaigns. |
| Blood donor pets | The system shall allow blood donor pet details to be registered and searched during emergencies. |
| Adoption listing | The system shall allow recovered animals to be published for adoption with approved public-facing details. |
| Adoption requests | The system shall allow interested adopters to submit adoption requests through a structured form. |
| Adoption history | The system shall maintain adoption decision, adopter details, and follow-up status. |
| Access control | The system shall restrict clinical treatment details from public users. |
| Usability | The system shall be simple enough for volunteers to learn within approximately 10 minutes. |
| Platform constraint | The system should be accessible through a web or mobile-friendly interface without requiring compulsory app installation. |

---


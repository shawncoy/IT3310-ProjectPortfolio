# Risk Register: RCHN Patient Intake and Scheduling System
**Consultant:** Shawn Coy
**Role:** Associate Consultant, NovaTech Consulting
**Engagement:** Regional Care Health Network (RCHN)
**Date:** Nov 3, 2026

---

## Risk Entries

### Risk 1
**Description:** If the automatic transfer of old patient records fails or causes data loss, then the team will have to manually enter data, causing severe schedule delays for the RCHN project.
**Probability:** Medium
**Impact:** High
**Score:** 6
**Response Strategy:** Mitigate, The team will run trial data migrations in a sandbox environment to catch syncing errors before the actual launch.
**Trigger or Monitoring Condition:** A trial migration shows missing records or formatting errors.
**Owner:** Developer, because this role is doing the hands-on technical work and is responsible for writing the scripts that physically transfer the data between systems.

### Risk 2
**Description:** If RCHN's current computers and network cannot support the new software, then we will have to buy hardware upgrades, which breaks the budget for the RCHN project.
**Probability:** Low
**Impact:** High
**Score:** 3
**Response Strategy:** Mitigate, The team will conduct a technical audit of the clinic's existing computers and network to ensure they meet the new software's minimum requirements.
**Trigger or Monitoring Condition:** The technical audit reveals hardware that falls below the required specifications.
**Owner:** Project Manager, because this role is responsible for overseeing the project constraints and managing the budget if hardware upgrades are suddenly needed.

### Risk 3
**Description:** If clinic staff do not finish their training before the launch date, then they will struggle to use the system and cause major scheduling bottlenecks for the RCHN project.
**Probability:** Medium
**Impact:** High
**Score:** 6
**Response Strategy:** Mitigate, The team will schedule mandatory training sessions during regular shifts and track completion rates weekly.
**Trigger or Monitoring Condition:** A clinic falls below 100% training completion one week before the target launch date.
**Owner:** Project Manager, because they oversee the project schedule and must coordinate with RCHN clinic stakeholders to ensure staff actually have time to complete the training.

### Risk 4
**Description:** If the final system integration and acceptance testing fails, then launching the software will risk system crashes and ruin patient data integrity for the RCHN project.
**Probability:** Medium
**Impact:** High
**Score:** 6
**Response Strategy:** Mitigate, The team will build a comprehensive test plan and execute it incrementally during development rather than waiting until the very end.
**Trigger or Monitoring Condition:** Critical acceptance tests fail during the final testing phase.
**Owner:** Scrum Master, because this role facilitates the sprints, tracks testing progress, and ensures the development team is meeting the acceptance criteria before finalizing a release.

### Risk 5
**Description:** If front desk staff do not trust the new system, then they will rely on paper backups, which completely defeats the efficiency goals for the RCHN project.
**Probability:** Medium
**Impact:** Medium
**Score:** 4
**Response Strategy:** Mitigate, The team will involve the intake coordinators early in the UI design process to build trust and ensure the system is actually easier to use than paper.
**Trigger or Monitoring Condition:** Post-launch monitoring shows staff bypassing the system to use manual processes.
**Owner:** Product Manager, because they are responsible for maximizing the value of the product, understanding the user persona, and ensuring the interface actually solves the medical assistants' frustrations so they don't revert to paper.

---

## Bring Forward
**Week 5 assumptions:** We are assuming that RCHN's current hardware and network infrastructure will be able to support the new software with no issue. If this is wrong, then we will have to pivot away from a software-only implementation and will have to adjust the scope and budget and timeline of our project to include hardware upgrades. We are assuming that all the old patient records can be automatically transferred into the new system without any data loss. If this is wrong, then we will have to pivot our resource plan and adjust our project timeline to account for the IT team and clinic staff having to manually enter that data.
**Week 7 backlog item:** As a clinic intake coordinator I want a streamlined patient registration and scheduling system so that patients can check in and update their medical history online, which will reduce wait times.
**Week 8 schedule item:** Activity or milestone: Project Kickoff Meeting Completed. Predecessor: Project Charter Approved. Planned week: Week 1.

---

## Assumption Connection
Risk 1 connects to my Week 5 assumption that all old patient records can be automatically transferred into the new system without any data loss. This became a risk because we haven't tested the database compatibility yet, which makes us unsure that the data synced properly. If it fails, it will affect our project objective of ensuring a smooth transition with zero interruptions to daily appointments.

Risk 2 connects to my Week 5 assumption that RCHN's current hardware and network infrastructure can support the new software with no issues. This became a risk because we are just assuming the old clinic computers are fast enough for the new UI without doing a real technical audit. This uncertainty threatens our main constraint of keeping this a "software-only implementation," which would destroy our budget objective if we are suddenly forced to buy new computers for the clinics.

---

## Score Justification
For risk 1, I rated probability medium because of the formatting errors or sync issues that could arise when migrating medical records between systems. I rated impact high because the corruption of data would threaten the safety of patients and cause great interruptions to regular operations.

For risk 3, I rated the probability as medium because clinic staff may not be able to find time during their work days to train on the new system. This risk would be High impact because the clinic workers being up to date is one of the most essential components to ensuring clinic operations continue to run smoothly.

---

## Risk Reflection
### Highest Priority Risk and Project Impact
My highest-priority threat is Risk 1 with a course score of 6. It deserves the most attention because if we lose patient medical data, the new scheduling system is useless and the project's main goal will not be achieved.

If this risk ended up happening, it would affect go-live readiness. It would force NovaTech to halt the system launch, push the schedule back even further to fix any data migration issues, and would ruin the confidence of our stakeholders.

### Risk vs Issue Distinction
After reviewing my five risks, I confirmed that each one is a future uncertainty because none of them have actually happened yet. For Risk 1, we haven't actually done the final data transfer. For Risk 2, we haven't tested the new software on the actual clinic computers. For Risk 3, the training deadline hasn't passed yet. For Risk 4, final acceptance testing hasn't happened. For Risk 5, the system hasn't launched, so staff haven't had the chance to use paper backups yet. The distinction matters because risks just need mitigation plans to prevent them from happening, while issues are active problems that force the project team to stop and fix them immediately.

---
*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*

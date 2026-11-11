# Resource Plan and Budget: RCHN Patient Intake and Scheduling System
**Consultant:** Shawn Coy
**Role:** Associate Consultant, Project Manager, NovaTech Consulting
**Engagement:** Riverside Community Health Network (RCHN)
**Date:** November 10, 2026
***
## Resource Plan

### Human Resources
| Role | Capability / Project Need | Weeks | Hours per Week | Total Hours | Estimated Rate | Estimated Labor Cost |
|---|---|---|---|---|---|---|
| Developer | Technical scripting and database management (Executes patient data migration and runs trial migrations in a sandbox environment to respond to Risk 1) | 14 | 25 | 350 | $135/hr | $47,250 |
| Project Manager | Budget management and schedule coordination (Coordinates mandatory staff training schedules to respond to Risk 3 and manages budget constraints during the technical audit to respond to Risk 2) | 16 | 20 | 320 | $125/hr | $40,000 |
| QA Analyst | Software testing and defect tracking (Executes the comprehensive test plan incrementally during development to prevent launch failures and respond to Risk 4) | 8 | 20 | 160 | $90/hr | $14,400 |
| UI Designer | User interface design and user experience (Integrates intake coordinators into the UI design process to ensure the system is easy to use, building staff trust to respond to Risk 5) | 12 | 30 | 360 | $110/hr | $39,600 |

### Technology Resources
- Sandbox Environment Licenses - Estimated Cost: $2,500 - Basis: Needed to safely run trial data migrations to mitigate Risk 1 before launch, assuming a standard 3-month enterprise software trial.

### Infrastructure Resources
- Database and Server Hosting Environments - Estimated Cost: $6,000 - Basis: Required infrastructure to host the new software-only patient registration system over the 16-week project schedule, assuming standard cloud hosting fees.

### Third-Party Resources
- Independent IT Auditors - Estimated Cost: $8,500 - Basis: Third-party consultants required to conduct the independent technical audit of existing clinic computers (Risk 2 mitigation), assuming 50 hours of work at a standard $170/hr consultant rate.
***
## Estimation Approach
I used parametric estimation because the labor costs were calculated by multiplying distinct parameters: the number of weeks by average weekly hours, and then multiplying that total effort by a standard hourly rate. This fits the information available for RCHN because we have high-level schedule durations (weeks) and role expectations, but lack a detailed, hour-by-hour work breakdown structure. The limitation of this estimate is that it assumes a flat, consistent workload each week and does not account for crunch times or lighter weeks during the project lifecycle.

**Labor Assumptions**
*   Assumption 1: The Developer will only need to work 25 hours per week for 14 weeks. If wrong, and the data migration fails requiring manual data entry (Risk 1), the developer's hours would increase significantly, causing the $47,250 budget for this role to overrun.
*   Assumption 2: The QA Analyst's work is contained entirely within an 8-week testing window at 20 hours per week. If wrong, and final system integration testing fails (Risk 4), the testing phase would be extended. Adding just 2 extra weeks for the QA Analyst would increase the budget by an additional $3,600 (40 hours * $90/hr).
***
## Contingency Reserve
### Risk-Based Cost Exposure
- Risk 1: Patient data migration fails - Potential Cost Exposure: $13,500
- Risk 4: Final system integration testing fails - Potential Cost Exposure: $7,200

**Recommended Contingency Reserve:** $20,700

I calculated the contingency reserve by summing the potential cost exposure of my two highest-scoring risks from Week 9 (Risk 1 and Risk 4, which both scored a 6). This $20,700 reserve provides targeted financial coverage for the specific labor overruns that would occur if our most critical threats materialize during testing and deployment.
***
## Budget Summary
**Total Labor Cost:** $141,250
**Total Non-Labor Cost:** $17,000
**Contingency Reserve:** $20,700
**Estimated Project Budget:** $178,950

### Largest Cost Category
Labor is the largest category because a software-only implementation relies heavily on human expertise—such as developers, designers, and testers—to configure and migrate systems, rather than relying on expensive physical materials or hardware manufacturing.
***
## Budget Tradeoff Analysis
Before agreeing, I would analyze the project schedule, resource allocation, and the risk register to determine if it is possible to compress the timeline or remove non-essential resources without violating our core constraints, such as keeping this a software-only implementation and ensuring zero interruptions to daily clinic operations.

**Tradeoffs and Risks**
*   Tradeoff or risk 1: Cutting the QA Analyst's hours to save on labor costs directly increases the probability of Risk 4, where final system integration and acceptance testing fails. Reducing testing time could lead to launching a flawed system that crashes and ruins patient data integrity.
*   Tradeoff or risk 2: Eliminating the independent technical audit from the non-labor budget would save money initially, but forces the team to blindly assume the existing clinic hardware can support the new software (Risk 2). If this assumption is wrong, the project would suddenly require physical hardware upgrades, which would break the budget far beyond the initial 10 percent reduction.
***
*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*

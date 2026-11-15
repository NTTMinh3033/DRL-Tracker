# Summary of Project Execution and Tracking Modifications
Updated actual screenshots for Sprint 3/PA3


# Summary of Use-Case Model & Specification Modifications
## 1. Standardized Actor Terminology
Replaced inconsistent role names across the entire Use-Case Model and Use-Case Specifications to ensure uniformity:

- Assessor -> Assessment Officer
- Faculty Assessor -> Faculty-level Assessment Officer
- University Assessor -> University-level Assessment Officer
- Administrator -> Admin
- Organizing Unit -> Organization

---

## 2. Clarified Use-Case Names
Revised ambiguous use-case names to accurately reflect their core functions and responsibilities:

| UC ID | Previous Name                        | Revised Name                                        |
| :---  | :---                                 | :---                                                |
| UC06  | Manage Activity Lifecycle            | Create and Manage Activities                        |
| UC07  |  Manage Participant List             | Manage Activity Attendance List                     |
| UC08  | Verify Evidence                      | Review & Verify Participation Evidence              |
| UC09  | Process & Forward Appeals            | Process Student Appeals                             |
| UC10  | System Audit Trail                   | View & Audit System Logs                            |
| UC11  | Handle Exception Cases               | Verify Exceptional Activity Records                 |
| UC12  | Aggregate Points & Propose (Faculty) | Review Faculty Assessment Results & Submit Proposal |
| UC13  | Moderate Activities                  | Review & Approve Activities                         |
| UC14  | Manage Rule Configurations           | Configure Training Point Regulations                |
| UC15  | Manage Accounts & Permissions        | Manage User Accounts & Permissions                  |
| UC16  | Approve Official Points (University) | Review Faculty Proposals & Finalize Official Scores |

---

## 3. Use-Case Model Updates
- Add description.
- Label Synchronization: Updated all Use Case and Actor labels in the diagram to match the revised names and standardized terminology above.
- Association Direction Adjustment: Corrected the association arrow directions connected to the Assessment Officer and Organization actors to accurately reflect initiator/receiver responsibilities.

---

## 4. Specific Use-Case Specification Refinements
- UC07 (Manage Activity Attendance List): Pre-conditions: Updated to *"The activity is in 'Completed' status."
- UC09 (Process Student Appeals): Brief Description & Post-conditions: Refined both sections to explicitly clarify the distinct roles and responsibilities of the two participating actors (Faculty-level Assessment Officer and University-level Assessment Officer).
- UC11 (Verify Exceptional Activity Records): Alternative Flow 1: Removed the redundant student notification step (eliminating duplicate notification logic).
- UC13 (Review & Approve Activities): Alternative Flow 1: Removed the redundant rejection-reason input step (streamlining the rejection flow to a single prompt).
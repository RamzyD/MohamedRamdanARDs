## Context

Visa Processing System Sequence Diagram

## Decision 1

Flow of User Registration and Visa Application Process

## Alternatives

a) A linear, less interactive process flow.
b) An interactive, step-by-step process flow with confirmations and status checks.

## Decision

Chose alternative (b) for an interactive process flow.

## Rationale

Enhances user experience by providing immediate feedback at each step, ensuring clarity and reducing errors.

## Revisions: Revision 1

## Changes

Addition of status confirmation after user registration.

## Rationale

User testing indicated that immediate confirmation improves user confidence in the system.

## Reference for Revision 1

User Experience Design Strategies by Kim (2022).

## Decision 2

Document Upload and Eligibility Check Integration

## Alternatives

a) Separating document upload and eligibility check into different system modules.
b) Integrating document upload directly with the eligibility check.

## Decision

Chose alternative (b) for integration.

## Rationale

Streamlines the process, reducing the time between document submission and eligibility feedback.

## Revisions: Revision 1

## Changes

Immediate feedback on document validity during upload.

## Rationale

Operational feedback suggested that immediate validation reduces the number of invalid applications.

## Reference for Revision 1

Agile System Development in Practice by Singh (2023).

## Decision 3

Visa Application Tracking and Notification System

## Alternatives

a) Manual status checks by the user.
b) Automated status updates and email notifications.

## Decision

Chose alternative (b) for automated updates and notifications.

## Rationale

Improves user engagement and keeps the applicant informed without requiring manual checks.

## Revisions: Revision 1

## Changes

Inclusion of an email notification system upon successful visa application status change.

## Rationale

To notify users proactively, aligning with best practices for user communication.

## Reference for Revision 1

Communication Patterns in System Design by Martinez (2024).

## References

Kim, S. (2022). User Experience Design Strategies.

Singh, A. (2023). Agile System Development in Practice.

Martinez, L. (2024). Communication Patterns in System Design

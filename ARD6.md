## Context

Visa Processing System ERD

## Decision 1

Structure and Entities of the ERD

## Alternatives

a) A minimal ERD for immediate project needs.
b) An extensive ERD for future scalability.

## Decision

Chose alternative (b) for an extensive ERD.

## Rationale

Provides system scalability and accommodates future updates.

## Revisions: Revision 1

## Changes

Addition of 'DocumentType' in 'Documents' entity.

## Rationale

Improved document processing based on operational team feedback.

## Reference for Revision 1

Operational Efficiency in Data Systems by Davis (2022).

## Revision 2

## Changes

Introduction of 'VisaRules' entity for modular rules management.

## Rationale

Flexibility for legal updates as per Legal Team request.

## Reference for Revision 2

Legal Considerations in IT Infrastructure by Thompson (2023).

## Decision

Data Relationships

## Alternatives

a) Direct relationships for simplicity.
b) Associative entities for many-to-many relationships.

## Decision

Chose alternative (b) for associative entities.

## Rationale

Clear data model for complex relationships.

## Revisions: Revision 1

## Changes

One-to-many relationship between 'VisaApplication' and 'Documents'.

## Rationale

User need for submitting multiple documents.

## Reference for Revision 1

User Requirements and Data Modeling by Lee (2024).

## Decision 3

User Authentication Attributes

## Alternatives

a) Plain text passwords for faster retrieval.
b) Hashed passwords for security.

## Decision

Chose alternative (b) for hashed passwords.

## Rationale

Security of user data and adherence to best practices.

## Revisions:Revision 1

## Changes

Addition of 'Salt' attribute for password hashing.

## Rationale

Additional security against brute-force attacks.

## Reference for Revision 1

Advanced Security Protocols in Databases by O'Neil (2023).

## References

Davis, L. (2022). Operational Efficiency in Data Systems.

Thompson, H. (2023). Legal Considerations in IT Infrastructure.

Lee, M. (2024). User Requirements and Data Modeling.

O'Neil, P. (2023). Advanced Security Protocols in Databases.

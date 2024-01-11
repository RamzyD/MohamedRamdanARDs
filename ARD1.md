## Context

Processing System Class Diagram

## Decision 1

Inheritance in User Class Hierarchy

## Alternatives:

a) Implement a flat structure with no inheritance, defining all user types as separate, distinct classes.
b) Adopt an inheritance hierarchy with a generalized User class and specialized subclasses for distinct roles (e.g., SystemAdmin, VisaApplicant).

## Decision

Chose alternative (b).

## Rationale

A hierarchical model aligns with object-oriented design principles, enabling code reuse and reducing redundancy. It simplifies the system by treating all user types as User objects with extended properties and behaviors where necessary.

## References

Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1994). Design Patterns: Elements of Reusable Object-Oriented Software. Addison-Wesley.

## Decision 2

Separation of VisaApplication and Document Classes

## Alternatives:

a) Consolidate VisaApplication and Document management into a single class.
b) Separate VisaApplication and Document into two distinct classes.

## Decision

Chose alternative (b).

## Rationale

This separation mirrors the real-world distinction between an application and its supporting documents, facilitating better data management and adherence to the Single Responsibility Principle.

## References

Martin, R. C. (2003). Agile Software Development, Principles, Patterns, and Practices. Prentice Hall.

## Decision 3

Utilization of Interfaces for Forms

## Alternatives:

a) Directly embed form functionality within the user classes.
b) Define interfaces, such as RegistrationForm and VisaApplication, to standardize form-related operations.

## Decision

Chose alternative (b).

## Rationale

Interfaces specify a contract for form handling, which enhances system flexibility and allows for multiple implementations without altering dependent classes.

## References

Bloch, J. (2008). Effective Java (2nd ed.). Addison-Wesley.

## Decision 4

Integration of Authentication and Audit Services

## Alternatives:

a) Incorporate authentication and auditing directly within the user classes.
b) Create dedicated Authentication and AuditLog classes for managing security and logging.

## Decision

Chose alternative (b).

## Rationale

Dedicated classes for authentication and auditing streamline security by centralizing these critical functions, making them more maintainable and secure.

## References

Steel, C., Nagappan, R., & Lai, R. (2005). Core Security Patterns: Best Practices and Strategies for J2EE, Web Services, and Identity Management. Prentice Hall.

## Decision 5

EmailService Class for Notifications

## Alternatives:

a) Develop a custom notification mechanism within each user class.
b) Establish an EmailService class to centralize email notification functionality.

## Decision

Chose alternative (b).

## Rationale

A dedicated service for email communications abstracts this functionality from user classes, leveraging existing infrastructure and promoting single responsibility.

## References

Richards, M. (2015). Software Architecture Patterns. O'Reilly Media.

## References

Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1994). Design Patterns: Elements of Reusable Object-Oriented Software. Addison-Wesley.
Martin, R. C. (2003). Agile Software Development, Principles, Patterns, and Practices. Prentice Hall.
Bloch, J. (2008). Effective Java (2nd ed.). Addison-Wesley.
Steel, C., Nagappan, R., & Lai, R. (2005). Core Security Patterns: Best Practices and Strategies for J2EE, Web Services, and Identity Management. Prentice Hall.
Richards, M. (2015). Software Architecture Patterns. O'Reilly Media.
Microsoft. (n.d.). Exchange Server documentation. Retrieved from https://docs.microsoft.com/en-us/Exchange/
Patel, S. K., & Jain, R. K. (2018). The impact of external APIs on software development. International Journal of Software Development & Technology, 4(2), 33-39.
Walls, C. (2016). Spring Boot in Action. Manning Publications.

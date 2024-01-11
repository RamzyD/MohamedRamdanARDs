## Context

Visa Processing System Component Diagram

## Decision 1

Modular Component Design

## Alternatives

a) Monolithic architecture with fewer components.
b) Modular architecture with distinct components for each functionality.

## Decision

Chose alternative (b).

## Rationale

Facilitates independent development, testing, and maintenance of each part of the system. Allows for easier updates and scalability.

## References

Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1994). Design patterns: Elements of reusable object-oriented software. Addison-Wesley.

## Decision 2

Database Component Separation

## Alternatives

a) Embedding the database within the application server.
b) Separating the database into its own component.

## Decision

Chose alternative (b).

## Rationale

Isolating the database component supports better security practices and data management, and adheres to the principle of separation of concerns.

## References

Fowler, M. (2002). Patterns of enterprise application architecture. Addison-Wesley.

## Decision 3

Usage of Spring Framework

## Alternatives

a) Utilizing a different framework or custom components.
b) Leveraging Spring components for email, security, and mainframe interactions.

## Decision

Chose alternative (b).

## Rationale

The Spring framework provides robust, well-supported libraries for security and email, reducing the need for custom development and leveraging community-tested solutions.

## References

Walls, C. (2016). Spring Boot in action. Manning Publications.

## Decision 4

Integration with External E-mail System

## Alternatives

a) Building an in-house email delivery system.
b) Integrating with an existing enterprise-level email system (e.g., Microsoft Exchange).

## Decision

Chose alternative (b).

## Rationale

Utilizing an established email system ensures reliability, scalability, and reduces development overhead.

## References

Microsoft (n.d.). Exchange Server documentation. Retrieved from https://docs.microsoft.com/en-us/Exchange/

## Decision 5

External Services/APIs for Eligibility Checks

## Alternatives

a) Developing an in-house eligibility checking system.
b) Using external services and APIs for eligibility verification.

## Decision

Chose alternative (b).

## Rationale

Outsourcing eligibility checks to external services that specialize in this area ensures accuracy and up-to-date compliance with immigration laws.

## References

Patel, S. K., & Jain, R. K. (2018). The impact of external APIs on software development. International Journal of Software Development & Technology, 4(2), 33-39.

## References

Fowler, M. (2002). Patterns of enterprise application architecture. Addison-Wesley.

Gamma, E., Helm, R., Johnson, R., & Vlissides, J. (1994). Design patterns: Elements of reusable object-oriented software. Addison-Wesley.

Microsoft. (n.d.). Exchange Server documentation. Retrieved from https://docs.microsoft.com/en-us/Exchange/

Patel, S. K., & Jain, R. K. (2018). The impact of external APIs on software development. International Journal of Software Development & Technology, 4(2), 33-39.

Walls, C. (2016). Spring Boot in action. Manning Publications.

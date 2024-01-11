## Context

Visa Processing System Container Diagram

## Decision 1

Representation of Application Architecture

## Alternatives:

a) Depicting a monolithic architecture.
b) Presenting a microservices-based architecture.

## Decision

Chose alternative (b) to present a microservices-based architecture with distinct containers.

## Rationale

Supports scalability and clear separation of concerns, aligning with modern software architecture practices.

## References

Microservices patterns promote better maintainability and deployment practices (Richardson, 2018).

## Decision 2

Choice of Technology Stack

## Alternatives

a) Utilizing a full-stack JavaScript approach with Node.js.
b) Using distinct technologies for the front-end (JavaScript, Angular) and back-end (Java, Spring MVC).

## Decision

Chose alternative (b) for utilizing distinct technologies for different layers.

## Rationale

Leverages the strengths of each technology for its layer, ensuring performance and maintainability.

## References

Best practices suggest that the choice of technology should match the application's needs (Fowler & Lewis, 2014).

## Decision 3

Detailing External System Interactions

## Alternatives

a) Abstract representation of external interactions.
b) Detailed depiction of external interactions and protocols.

## Decision

Chose alternative (b) to detail external interactions and protocols.

## Rationale

Provides a clear understanding of system integration points and data flow between systems.

## References

Clear documentation of system integration is key for system interoperability (Newman, 2015).

## Decision 4

Inclusion of Security Mechanisms

## Alternatives

a) Omitting explicit security mechanisms in the diagram.
b) Including security mechanisms like HTTPS and SQL over TCP.

## Decision

Chose alternative (b) to include security mechanisms.

## Rationale

Highlights the commitment to data security and integrity within the system.

## References

Security mechanisms are a critical aspect of system architecture (OWASP, n.d.).

## Decision 5

Visualization of Data Storage

## Alternatives

a) Combining all data storage into a single database container.
b) Separating user authentication data from other application data.

## Decision

Chose alternative (b) for a separation of concerns.

## Rationale

Enhances data management, security, and allows for optimized performance of each database component.

## References

Database separation can lead to performance benefits and improved security (Kimball & Ross, 2013).

## References

Fowler, M., & Lewis, J. (2014). Microservices a definition of this new architectural term. Retrieved from https://martinfowler.com/articles/microservices.html

Kimball, R., & Ross, M. (2013). The data warehouse toolkit: The definitive guide to dimensional modeling (3rd ed.). Wiley.

Newman, S. (2015). Building microservices: Designing fine-grained systems. O'Reilly Media.

OWASP. (n.d.). OWASP Top Ten Web Application Security Risks. Retrieved from https://owasp.org/www-project-top-ten/
Richardson, C. (2018). Microservices patterns: With examples in Java. Manning Publications.

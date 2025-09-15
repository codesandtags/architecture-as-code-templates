# ADR Template

## What is an ADR?

**Architecture Decision Record (ADR)** is a document that captures an important architectural decision made along with its context and consequences. Unlike RFCs which propose changes, ADRs document decisions that have already been made.

## When to Use ADRs

- **Technology choices** (e.g., "We chose React over Vue")
- **Architectural patterns** (e.g., "We adopted microservices")
- **Design decisions** (e.g., "We use event-driven architecture")
- **Process decisions** (e.g., "We use feature flags for deployments")
- **Infrastructure choices** (e.g., "We use AWS over Azure")

## ADR Template

```markdown
# ADR-XXX: [Title]

**Status:** [Proposed | Accepted | Deprecated | Superseded]
**Date:** [YYYY-MM-DD]
**Deciders:** [List of decision makers]
**Consulted:** [List of people consulted]
**Informed:** [List of people informed]
**Supersedes:** [Link to previous ADR if applicable]
**Superseded by:** [Link to subsequent ADR if applicable]

## Context and Problem Statement

[Describe the context and problem statement, e.g., in free form using two to three sentences. You may want to articulate the problem in form of a question.]

### Examples:

- "We need to choose a frontend framework for our new web application"
- "Our monolithic application is becoming difficult to maintain and scale"
- "We need to decide how to handle user authentication across our services"

## Decision Drivers

- [driver 1, e.g., a force, facing concern, …]
- [driver 2, e.g., a force, facing concern, …]
- [driver 3, e.g., a force, facing concern, …]
- … <!-- numbers of drivers can vary -->

### Examples:

- Performance requirements
- Team expertise
- Long-term maintainability
- Cost considerations
- Security requirements
- Scalability needs

## Considered Options

### Option 1: [Name]

[Description of the option]

**Pros:**

- [Advantage 1]
- [Advantage 2]

**Cons:**

- [Disadvantage 1]
- [Disadvantage 2]

### Option 2: [Name]

[Description of the option]

**Pros:**

- [Advantage 1]
- [Advantage 2]

**Cons:**

- [Disadvantage 1]
- [Disadvantage 2]

### Option 3: [Name]

[Description of the option]

**Pros:**

- [Advantage 1]
- [Advantage 2]

**Cons:**

- [Disadvantage 1]
- [Disadvantage 2]

## Decision Outcome

**Chosen option:** [Option X]

**Justification:**
[Explain why this option was chosen over the others. This should be based on the decision drivers and trade-offs.]

### Positive Consequences

- [Positive consequence 1]
- [Positive consequence 2]

### Negative Consequences

- [Negative consequence 1]
- [Negative consequence 2]

## Implementation

[Describe the implementation approach, including any specific steps or considerations.]

### Timeline

- [Phase 1]: [Description and timeline]
- [Phase 2]: [Description and timeline]

### Resources Required

- [Resource 1]
- [Resource 2]

## Monitoring and Success Criteria

[How will we measure the success of this decision?]

### Metrics

- [Metric 1]
- [Metric 2]

### Monitoring

- [How will we monitor this decision?]

## Consequences

### Positive

- [Positive consequence 1]
- [Positive consequence 2]

### Negative

- [Negative consequence 1]
- [Negative consequence 2]

### Risks

- [Risk 1 and mitigation]
- [Risk 2 and mitigation]

## References

- [Link to related documentation]
- [Link to external resources]
- [Link to similar decisions in other projects]

## Appendix

### Diagrams

[Include relevant Mermaid diagrams here]

### Code Examples

[Include code snippets if helpful]

### Migration Notes

[If applicable, include migration considerations]
```

## ADR Naming Convention

Use a sequential number format: `ADR-001`, `ADR-002`, etc.

## ADR Lifecycle

1. **Proposed**: Initial draft, open for discussion
2. **Accepted**: Decision has been made and approved
3. **Deprecated**: Decision is no longer recommended but still in use
4. **Superseded**: Decision has been replaced by a newer ADR

## Best Practices

- **Keep it concise**: Focus on the decision and rationale
- **Include context**: Explain why the decision was needed
- **Document trade-offs**: Be honest about both pros and cons
- **Use diagrams**: Visual aids help explain complex decisions
- **Regular review**: Periodically review ADRs for relevance
- **Link related decisions**: Connect related ADRs
- **Version control**: Track changes to ADRs over time

## Example ADR Topics

- "ADR-001: Use React for Frontend Development"
- "ADR-002: Adopt Microservices Architecture"
- "ADR-003: Use PostgreSQL as Primary Database"
- "ADR-004: Implement Event-Driven Communication"
- "ADR-005: Use Docker for Containerization"
- "ADR-006: Adopt GitFlow for Version Control"
- "ADR-007: Use AWS for Cloud Infrastructure"
- "ADR-008: Implement API Gateway Pattern"

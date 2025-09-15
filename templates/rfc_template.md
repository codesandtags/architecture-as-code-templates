# RFC Template

## What is an RFC?

**Request for Comments (RFC)** is a document that proposes a significant change, new feature, or architectural decision to a project. It's a collaborative process where team members can discuss, provide feedback, and reach consensus before implementation.

## When to Use RFCs

- **Major feature additions** that affect multiple systems
- **Architectural changes** that impact the overall system design
- **Breaking changes** to APIs or data structures
- **New technology adoption** that affects the tech stack
- **Process changes** that impact how the team works

## RFC Template

```markdown
# RFC: [Title]

**Status:** [Draft | Review | Accepted | Rejected | Superseded]
**Author:** [Your Name]
**Date:** [YYYY-MM-DD]
**Reviewers:** [List of reviewers]
**Supersedes:** [Link to previous RFC if applicable]

## Summary

[One paragraph summary of the proposed change]

## Motivation

### Problem Statement

[What problem are we trying to solve? Why is this change necessary?]

### Goals

[What are we trying to achieve with this change?]

### Non-Goals

[What are we explicitly NOT trying to achieve?]

## Detailed Design

### Overview

[High-level description of the proposed solution]

### Technical Approach

[Detailed technical implementation approach]

### API Changes

[If applicable, describe any API changes]

### Data Model Changes

[If applicable, describe any database or data structure changes]

### Security Considerations

[Security implications and mitigation strategies]

### Performance Impact

[Expected performance implications]

### Monitoring and Observability

[How will we monitor this change? What metrics are important?]

## Implementation Plan

### Phase 1: [Phase Name]

- [ ] [Specific task]
- [ ] [Specific task]

### Phase 2: [Phase Name]

- [ ] [Specific task]
- [ ] [Specific task]

### Rollback Plan

[How to rollback if issues arise]

## Alternatives Considered

### Alternative 1: [Name]

**Pros:**

- [Advantage]

**Cons:**

- [Disadvantage]

**Why not chosen:**
[Reason for rejection]

### Alternative 2: [Name]

[Similar structure as above]

## Open Questions

- [ ] [Question 1]
- [ ] [Question 2]

## References

- [Link to related documentation]
- [Link to external resources]
- [Link to similar implementations]

## Appendix

### Diagrams

[Include relevant Mermaid diagrams here]

### Code Examples

[Include code snippets if helpful]

### Migration Guide

[If applicable, include migration steps]
```

## RFC Process

1. **Draft**: Create the RFC document with the template
2. **Review**: Share with team for feedback (typically 1-2 weeks)
3. **Discussion**: Address feedback and iterate
4. **Decision**: Team decides to accept, reject, or request changes
5. **Implementation**: If accepted, implement according to the plan
6. **Follow-up**: Monitor implementation and document lessons learned

## Best Practices

- **Be specific**: Include concrete examples and implementation details
- **Consider alternatives**: Always discuss other approaches you considered
- **Think about edge cases**: Address potential issues upfront
- **Include diagrams**: Use Mermaid diagrams to illustrate complex concepts
- **Keep it concise**: Aim for 2-5 pages, with details in appendices
- **Get early feedback**: Share drafts early for initial feedback
- **Document decisions**: Keep track of why decisions were made

## Example RFC Topics

- "RFC: Migrate from REST to GraphQL API"
- "RFC: Implement Event Sourcing for Order Management"
- "RFC: Adopt Microservices Architecture"
- "RFC: Introduce Feature Flags System"
- "RFC: Implement Real-time Notifications"

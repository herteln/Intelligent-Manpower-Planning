# Ontology

The ontology formally defines the concepts and relationships used in the manpower-planning domain.

Example concepts include:

- Employee
- Skill
- Certification
- Role
- Team
- System
- Incident
- Shift
- Availability
- Workload
- SLA

Example relationships include:

```text
Employee → HAS_SKILL → Skill
Employee → HAS_CERTIFICATION → Certification
Employee → MEMBER_OF → Team
Employee → AVAILABLE_FOR → Shift
Incident → REQUIRES_SKILL → Skill
Incident → AFFECTS_SYSTEM → System
```

The ontology creates a shared vocabulary and provides the formal structure used when building the Knowledge Graph.

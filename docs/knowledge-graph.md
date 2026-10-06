# Knowledge Graph

The Knowledge Graph stores concrete enterprise facts and relationships using the structure defined by the ontology.

For manpower planning, it can connect employees with skills, systems, certifications, incidents, teams, shifts and availability.

## Example

```text
Employee_A
   ├── HAS_SKILL → SQL Server
   ├── KNOWS_SYSTEM → Billing Platform
   ├── MEMBER_OF → Database Support
   └── AVAILABLE_FOR → Evening Shift
```

This context allows the planning system to answer questions that are difficult to express with isolated tables alone, such as identifying which available employees have the required skills for a predicted workload.

The Knowledge Graph complements rather than replaces the analytical data platform.

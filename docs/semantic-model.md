# Semantic Model

The semantic model provides a consistent business interpretation of structured data used by the manpower-planning solution.

It can define measures, terminology and relationships such as incident volume, available capacity, skill coverage, utilization and SLA compliance.

A Power BI Semantic Model can be an important **input** to the ontology design because it already contains business entities, relationships and measures. However, it is not itself the ontology.

## Role in the Architecture

```text
Source Systems
      ↓
Data Platform / Data Warehouse
      ↓
Semantic Model
      ↓
Ontology
      ↓
Knowledge Graph
```

The semantic model supports reporting and analytics, while the ontology formalizes domain meaning and the Knowledge Graph stores actual entities and relationships.

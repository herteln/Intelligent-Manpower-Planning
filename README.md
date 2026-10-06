# Intelligent Manpower Planning for IT Support

## A Knowledge-Driven and Probabilistic AI Approach

This repository contains the **public documentation and architecture** for an intelligent manpower-planning concept for IT support organizations.

The project combines:

- semantic modeling,
- ontology design,
- knowledge graphs,
- forecasting,
- Bayesian and Markov networks,
- AI-agent-based diagnosis and recommendation,
- and human-in-the-loop decision making.

The purpose is to move beyond simple headcount planning and support questions such as:

- How many employees are required?
- Which skills and system knowledge are needed?
- When and where are they required?
- Where are future capacity or skill gaps likely?
- What is the probability of an SLA risk?
- Which planning action should be recommended?

## Public Documentation

- [Project Website](https://herteln.github.io/Intelligent-Manpower-Planning/)
- [Public Roadmap](roadmap.md)
- [Semantic Model](docs/semantic-model.md)
- [Ontology](docs/ontology.md)
- [Knowledge Graph](docs/knowledge-graph.md)
- [Probabilistic Graphical Models](docs/pgm.md)
- [AI Agent](docs/ai-agent.md)

## Architecture

The target concept follows this high-level flow:

```text
Enterprise Data
      ↓
Semantic Model
      ↓
Ontology
      ↓
Knowledge Graph
      ↓
Forecasting + Probabilistic Graphical Models
      ↓
AI Agent
      ↓
Human Approval
      ↓
Planning Action
```

The analytical data platform remains the primary foundation for historical and quantitative analysis. The Knowledge Graph adds context and relationships; probabilistic models add uncertainty and scenario reasoning; the AI Agent combines those outputs into explainable recommendations.

## Existing Visual Assets

- [Editable Draw.io semantic model](diagrams/IT_Support_Manpower_Semantic_Model.drawio)
- [Semantic Model / Ontology / Knowledge Graph image](images/Semantic_Model_Ontology_Knowledge_Graph.jpg)

## Repository Purpose

This is a **documentation repository**. Implementation code, internal project work, detailed operational data, private notebooks, and internal technical tasks are intentionally kept outside this public repository.

## Human-in-the-Loop Principle

The AI Agent is intended to support diagnosis and recommendations. Critical staffing or production decisions should remain subject to human review and approval.

## Status

The project is under active design and development. The [public roadmap](roadmap.md) describes the major steps required to build the first end-to-end proof of concept.

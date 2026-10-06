# AI Agent

The AI Agent is the diagnosis and recommendation layer of the intelligent manpower-planning architecture.

It does not replace the forecasting models, Knowledge Graph or probabilistic models. Instead, it orchestrates their outputs.

## Inputs

The Agent may use:

- Knowledge Graph context,
- forecast results,
- Bayesian Network probabilities,
- Markov Network results,
- current operational information,
- business rules and constraints.

## Reasoning Workflow

```text
Collect Context
      ↓
Identify Planning Problem
      ↓
Retrieve Relevant Knowledge
      ↓
Evaluate Forecast and Risk
      ↓
Diagnose Likely Cause
      ↓
Generate Possible Actions
      ↓
Explain Recommendation
      ↓
Human Approval
```

## Example

The system may identify that expected workload for a specific technology exceeds the available qualified capacity for an upcoming shift.

The Agent could explain:

- which workload is expected,
- which skills are required,
- which qualified employees are available,
- the probability of an SLA risk,
- and which staffing action could reduce that risk.

## Guardrails

The target design follows a human-in-the-loop principle. Important staffing and operational decisions should remain subject to human review and approval.

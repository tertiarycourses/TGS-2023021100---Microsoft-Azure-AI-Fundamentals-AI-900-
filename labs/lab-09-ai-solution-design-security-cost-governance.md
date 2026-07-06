# Lab 09 - AI Solution Design, Security, Cost, Governance

## Objectives

- Design a simple Azure AI solution.
- Identify security, privacy, and governance controls.
- Review cost considerations.
- Choose appropriate Azure AI services.

## Scenario

The retail company wants one AI solution that analyzes customer feedback, summarizes themes, and routes urgent complaints. You must recommend services and controls.

## Steps

### 1. Confirm Requirements

Write:

```text
Business goal:
Input data:
Expected output:
Users:
Latency need:
Privacy constraints:
Human review requirement:
```

### 2. Choose Services

| Requirement | Azure Service |
| --- | --- |
| Sentiment and entities | Azure AI Language |
| Translation | Azure AI Translator |
| Summarization or response drafting | Azure AI Foundry or Azure OpenAI |
| Custom ML prediction | Azure Machine Learning |
| Secure storage | Azure Storage with access control |

### 3. Add Security Controls

Document:

- Role-based access control.
- Managed identities.
- Private data handling.
- Logging and monitoring.
- Key and endpoint protection.
- Human review for high-risk actions.

### 4. Review Cost Controls

Answer:

1. Which services are billed per transaction or token?
2. How will usage be monitored?
3. What budget alert is needed?
4. How will unused resources be deleted?

### 5. Add Responsible AI Controls

Include:

- Transparency message.
- Error reporting channel.
- Human review workflow.
- Bias and fairness review.
- Privacy review.

## Validation

You should have a requirements summary, service selection table, security controls, cost controls, and responsible AI controls.

## Checkpoint Questions

1. Why does AI solution design include governance?
2. What is RBAC used for?
3. Why are budget alerts useful?
4. Why is human review important for high-impact outputs?

## Exam Focus

AI solution questions often test choosing the right service and recognizing responsible AI, privacy, and security concerns.

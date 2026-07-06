# Lab 10 - AI-900 Capstone and Course Review

## Objectives

- Review all Azure AI fundamentals topics.
- Build an end-to-end AI service map.
- Practice workload recognition.
- Create a personal review plan.
- Clean up lab resources.

## Scenario

You must brief a manager on which Azure AI services could support the retail company and what risks must be managed.

## Steps

### 1. Build a Service Map

Create a table:

| Business Need | AI Workload | Azure Service |
| --- | --- | --- |
| Analyze product photos | Computer vision | Azure AI Vision |
| Extract invoice fields | Document processing | Azure AI Document Intelligence |
| Understand customer comments | NLP | Azure AI Language |
| Convert calls to text | Speech recognition | Azure AI Speech |
| Draft response suggestions | Generative AI | Azure AI Foundry or Azure OpenAI |
| Train custom prediction model | Machine learning | Azure Machine Learning |

### 2. Review Responsible AI

For each principle, write one action:

```text
Fairness:
Reliability and safety:
Privacy and security:
Inclusiveness:
Transparency:
Accountability:
```

### 3. Review ML Techniques

Match:

| Technique | Scenario |
| --- | --- |
| Regression | Predict numeric value |
| Classification | Predict category |
| Clustering | Group similar items |
| Deep learning | Complex image, speech, or language tasks |
| Transformer | Language and generative AI workloads |

### 4. Build a Review Log

Record weak areas:

```text
Topic:
Why it is confusing:
Definition to memorize:
Example scenario:
```

### 5. Clean Up Resources

If resources were created:

```bash
az group delete --name rg-ai900-lab --yes --no-wait
```

Confirm with your instructor before deleting shared resources.

### 6. Prepare a 7-Day Study Plan

1. Day 1: AI workloads and responsible AI.
2. Day 2: Machine learning fundamentals.
3. Day 3: Azure Machine Learning.
4. Day 4: Computer vision and document intelligence.
5. Day 5: NLP, speech, and translation.
6. Day 6: Generative AI, Foundry, Azure OpenAI.
7. Day 7: Scenario practice and review log.

## Validation

You should have a service map, responsible AI action list, ML technique table, review log, and cleanup confirmation.

## Checkpoint Questions

1. Which AI workload is easiest for you to identify?
2. Which Azure service names are most confusing?
3. What is the difference between traditional ML and generative AI?
4. What responsible AI principle do you need to review most?

## Course Focus

The goal is to recognize AI workloads, understand foundational concepts, and describe how Azure AI services support common business scenarios.

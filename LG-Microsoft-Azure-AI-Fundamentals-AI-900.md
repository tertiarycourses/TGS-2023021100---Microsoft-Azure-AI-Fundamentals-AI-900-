# Learner Guide - Microsoft Azure AI Fundamentals (AI-900)

## Course Information

| Item | Details |
| --- | --- |
| Course Code | TGS-2023021100 |
| Course Title | Microsoft Azure AI Fundamentals (AI-900) |
| Registration | https://www.tertiarycourses.com.sg/wsq-microsoft-azure-ai-fundamentals-ai-900.html |
| Microsoft Study Guide | https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-900 |

## Certification Status Note

The Microsoft Learn study guide currently states that Exam AI-900 was retired on June 30, 2026. These labs are therefore written as Azure AI Fundamentals courseware based on the published AI-900 skills outline and Azure AI concepts, rather than as a guarantee of availability for a current exam appointment.

## Course Goal

This course helps learners understand foundational AI concepts and how Microsoft Azure services support common AI workloads. Learners will practice identifying AI scenarios, explaining responsible AI considerations, recognizing machine learning techniques, and mapping computer vision, natural language, speech, document, and generative AI workloads to Azure services.

## Prerequisites

- Basic computer literacy.
- Basic cloud computing awareness is helpful.
- No data science or software engineering experience is required.
- Access to Microsoft Learn, Azure portal, or an instructor-provided Azure environment.

## Learning Outcomes

By the end of the course, learners should be able to:

- Identify common AI workloads and use cases.
- Explain responsible AI principles: fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.
- Distinguish regression, classification, clustering, deep learning, and transformer-based workloads.
- Explain features, labels, training data, validation data, model training, model evaluation, and deployment.
- Describe Azure Machine Learning and automated machine learning capabilities.
- Describe computer vision workloads such as image classification, object detection, OCR, and face detection.
- Describe NLP workloads such as sentiment analysis, entity recognition, key phrase extraction, speech, and translation.
- Describe document processing and knowledge mining scenarios.
- Describe generative AI concepts, Azure AI Foundry, Azure OpenAI, and model catalog capabilities.

## Recommended Course Flow

### Day 1 - AI and Machine Learning Foundations

1. Course briefing and AI-900 study guide overview.
2. Lab 01: AI Workloads and Responsible AI.
3. Lab 02: Machine Learning Fundamentals.
4. Lab 03: Azure Machine Learning, Automated ML, Model Lifecycle.
5. Lab 04: Computer Vision, Image Analysis, OCR.
6. Day 1 review: workload recognition and responsible AI.

### Day 2 - Azure AI Services and Generative AI

1. Recap of Day 1.
2. Lab 05: Natural Language Processing and Azure AI Language.
3. Lab 06: Speech, Translation, Conversational AI.
4. Lab 07: Document Intelligence and Knowledge Mining.
5. Lab 08: Generative AI, Azure AI Foundry, Azure OpenAI, Model Catalog.
6. Lab 09: AI Solution Design, Security, Cost, Governance.
7. Lab 10: AI-900 Capstone and Course Review.

## Lab Environment Setup

### Step 1 - Confirm Azure Access

1. Open https://portal.azure.com/.
2. Sign in with your instructor-provided account or personal Azure account.
3. Confirm you can view subscriptions and resource groups.
4. If using a personal subscription, set a budget alert before creating resources.

### Step 2 - Create a Resource Group

Use the Azure portal or Azure Cloud Shell:

```bash
az group create --name rg-ai900-lab --location southeastasia
```

### Step 3 - Record Lab Details

Create a notes file:

```text
ai900-lab-notes.md
```

Record:

```text
Subscription:
Resource group:
Region:
Azure AI resource names:
Key learning points:
```

### Step 4 - Cost Control

1. Use free tiers where available.
2. Avoid creating resources that are not required by your instructor.
3. Delete resources at the end of the course.
4. Do not paste real personal or confidential data into AI demos.

## Lab Completion Standard

For each lab, learners should complete:

1. Scenario interpretation.
2. Guided tasks or design activity.
3. Validation questions.
4. Responsible AI reflection.
5. Cleanup review.
6. One exam-style takeaway.

## Final Review Checklist

Before completing the course, confirm that you can:

- Match common AI workloads to Azure services.
- Explain the difference between machine learning and generative AI.
- Distinguish regression, classification, clustering, deep learning, and transformer models.
- Explain core responsible AI principles.
- Identify computer vision, NLP, speech, document intelligence, and generative AI use cases.
- Explain when Azure Machine Learning, Azure AI services, Azure AI Foundry, and Azure OpenAI are relevant.
- Explain security, privacy, and cost considerations for AI solutions.

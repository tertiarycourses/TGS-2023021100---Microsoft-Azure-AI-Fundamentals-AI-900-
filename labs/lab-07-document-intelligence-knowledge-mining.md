# Lab 07 - Document Intelligence and Knowledge Mining

## Objectives

- Identify document processing workloads.
- Explain form extraction and OCR.
- Describe Azure AI Document Intelligence.
- Explain knowledge mining concepts.

## Scenario

The retail company processes invoices, receipts, and supplier forms manually. It wants to extract structured information and make documents searchable.

## Steps

### 1. Identify Document Tasks

| Document Task | Workload |
| --- | --- |
| Read printed text | OCR |
| Extract invoice number and amount | Form extraction |
| Extract tables | Document intelligence |
| Search across scanned files | Knowledge mining |
| Classify document type | Classification |

### 2. Review Azure AI Document Intelligence

Document:

```text
Prebuilt models
Custom extraction
Layout extraction
Tables
Key-value pairs
Confidence scores
```

### 3. Design an Invoice Processing Flow

```text
Upload invoice
Run document extraction
Validate confidence score
Human review if low confidence
Store structured fields
Search and report
Archive according to policy
```

### 4. Review Knowledge Mining

Explain how AI enrichment, indexing, and search can make unstructured documents discoverable.

### 5. Responsible AI Review

Answer:

- Do documents contain personal data?
- What confidence threshold triggers human review?
- Who can access extracted data?
- How long are documents retained?

## Validation

You should have a document task map, extraction flow, knowledge mining notes, and responsible AI review.

## Checkpoint Questions

1. What is document processing?
2. How is OCR related to document intelligence?
3. Why are confidence scores useful?
4. What is knowledge mining?

## Exam Focus

Document processing questions may reference OCR, forms, invoices, extraction, and search.

---
title: "Week 11 Worklog"
date: 2026-06-26
weight: 110
chapter: false
pre: " <b> 1.11. </b> "
---
### Week 11 Objectives:

* Finalize the automated invoice extraction and processing pipeline using Amazon Textract, Bedrock/OpenAI, and DynamoDB.
* Optimize performance, reduce execution time, and perform comprehensive testing on AWS Lambda.
* Complete the Amazon QuickSight dashboard for invoice data visualization and statistics reporting.
* Review security configurations across IAM, S3, Lambda, and API Gateway.
* Conduct system integration testing (from frontend to backend) and resolve runtime issues.
* Prepare technical documentation, slides, and demo recordings for the final project presentation.

### Tasks to be implemented this week:
| Day | Task | Start Date | End Date | Resource |
| --- | ------------------------------------------------------------------------------------------------------------------------- | ---------- | -------- | --------------------------------------------- |
| Fri | - Optimize invoice processing code, integrate OpenAI/Bedrock, and store structured data in DynamoDB | 2026-06-26 | 2026-06-26 | <https://cloudjourney.awsstudygroup.com/> |
| Sat | - Conduct unit testing for Lambda functions, measure execution latency, and optimize memory allocation | 2026-06-27 | 2026-06-27 | <https://cloudjourney.awsstudygroup.com/> |
| Sun | - Connect DynamoDB data (via Athena) to Amazon QuickSight, design and build interactive dashboard visuals | 2026-06-28 | 2026-06-28 | <https://cloudjourney.awsstudygroup.com/> |
| Mon | - Review and verify IAM Policies for services (S3, Lambda, DynamoDB), ensuring Least Privilege access | 2026-06-29 | 2026-06-29 | <https://cloudjourney.awsstudygroup.com/> |
| Tue | - Execute end-to-end integration testing from file upload on S3 to structured data rendering on the Dashboard | 2026-06-30 | 2026-06-30 | <https://cloudjourney.awsstudygroup.com/> |
| Wed | - Identify and troubleshoot system errors (CORS, JSON formatting errors from OpenAI, API Gateway auth issues) | 2026-07-01 | 2026-07-01 | <https://cloudjourney.awsstudygroup.com/> |
| Thu | - Write the technical specification documentation, build presentation slides, and record demo scenarios | 2026-07-02 | 2026-07-02 | <https://cloudjourney.awsstudygroup.com/> |


### Week 11 Outcomes:

* **Finalized Automated Invoice Processing Pipeline:**
  * Completed the end-to-end flow integrating Amazon Textract (OCR) with generative AI models to parse and structure invoice data directly into DynamoDB.
  * Optimized AWS Lambda configurations (memory, execution timeouts) yielding a 30% reduction in processing latency across various document types (PDF, PNG, JPEG).

* **Complete Analytics & Reports Dashboard:**
  * Finished building the Amazon QuickSight dashboard connected to DynamoDB, enabling real-time metrics update.
  * Visualized key metrics including total revenue, monthly invoice volumes, tag classifications, and filters based on vendors and clients.

* **Security Reviews & System Integration Testing:**
  * Reviewed all security policies, locking down access with granular IAM Policies matching Least Privilege standards.
  * Successfully resolved CORS issues on API Gateway and Lambda execution timeout errors when processing large-sized invoice documents.
  * Prepared detailed technical specifications, presentation slides, and screen-recordings of system workflows for final evaluation.

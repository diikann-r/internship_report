---
title: "Workshop"
date: 2024-01-01
weight: 5
chapter: false
pre: " <b> 5. </b> "
---

# Building a Serverless AI Invoice Scanner on AWS

#### Overview

In this lab, you will design and deploy a fully automated serverless invoice processing solution on AWS integrated with the **OpenAI API**.

The system enables users to authenticate via Cognito, upload invoice files, automatically trigger Lambda to extract raw text using Amazon Textract OCR, utilize the OpenAI API to structure the extracted data, and store records in DynamoDB. Users can view, search, tag, star, and export invoices via a React frontend.

![Architecture Diagram](/images/architecture-log.png)

#### Contents

1. [Introduction](1-introduce/)
2. [Environment Setup](2-environmentsetup/)
3. [AI-Powered Invoice Processing](3-aipoweredinvoiceprocessing/)
4. [Deploying API Gateway](4-deployingapigateway/)
5. [Testing with Postman](5-testwithpostman/)
6. [Deploying Frontend Application](6-deployingfrontend/)
7. [Resource Cleanup](7-cleanup/)
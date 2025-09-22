---
title: Download Risk Evaluation documents
excerpt: >
  Retrieves a structured ZIP archive of documents associated with a specific
  evaluation ID. Contents may include consumer-uploaded identity documents and
  attachments added by reviewers during a case evaluation. 


  The archive is organized into folders as follows:


  - `user_uploaded/`: Consumer-submitted identity documents.
    - `user_uploaded/document_verification/front`
    - `user_uploaded/document_verification/back`
    - `user_uploaded/vouched_id_verification/driver's_license`
  - `case_attachments/`: Case attachments added via the RiskOS™ Dashboard. 
    - `case_attachments/identity.pdf`
    - `case_attachments/additional_doc.pdf`
api:
  file: socure api.json
  operationId: downloadEvaluationDocuments
hidden: false
---
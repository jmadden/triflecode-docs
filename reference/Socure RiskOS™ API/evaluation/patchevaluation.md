---
title: Partially update a Risk Evaluation
excerpt: >
  Updates risk data or metadata for a previously submitted evaluation request
  that is in a **paused** state.

  The request is identified by the `eval_id`, and updates can be **partial**—any
  data not included in the request will remain unchanged. The body of the `PUT`
  request must match the structure used in the original `POST` request.

  > **Note:** Once an evaluation is completed, its data becomes immutable. Any
  attempt to update it will result in a failed request.
api:
  file: socure api.json
  operationId: patchEvaluation
hidden: false
---
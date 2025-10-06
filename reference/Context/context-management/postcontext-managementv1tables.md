---
title: Create a context table with metadata
excerpt: >-
  Create a custom context table (only CUSTOM table creation is supported) with
  attributes that define the schema. You can create new attributes by providing
  unique names or reuse existing attributes by providing their IDs. Attribute
  IDs can be retrieved using the `get attributes` endpoint. Use the `isKey`
  property to designate an attribute as the key. Note that a table can have only
  one key attribute.
api:
  file: openspec.yaml
  operationId: postContext-managementV1Tables
hidden: false
---
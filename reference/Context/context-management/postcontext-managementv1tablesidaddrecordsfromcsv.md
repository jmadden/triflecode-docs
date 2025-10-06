---
title: Add context records to an existing table from a CSV file
excerpt: >-
  Add context records to an existing table using a CSV file. The CSV file must
  contain a header row with column names for the attributes you want to map.

  File size can be a maximum of 300 MB or 500,000 records. If the CSV file
  exceeds these limits, compress it as a ZIP file. A compressed ZIP file must
  contain only one CSV file.

  Use the value of the `operation` parameter to `append` the added data or
  `replace` the existing data.
api:
  file: openspec.yaml
  operationId: postContext-managementV1TablesIdAddrecordsfromcsv
hidden: false
---
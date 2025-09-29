---
title: Update a Site Collector template
excerpt: >
  Update an existing template for a Site Collector agent by its template

  ID with all log collection configurations depending on its type

  (`Windows`, `File` etc).


  **Template Update Notice**


  - Modifying a template affects all collectors that use it.

  - Expect delays in template propagation to all affected collectors. As a
  guideline, it may take approximately 5 minutes for every 20 collectors per
  Site Collector instance.

  - Collectors under Site Collector instances that are in an error state will
  not be updated automatically. These collectors will require a manual update
  once the Site Collector instance is restored to `RUNNING`.
api:
  file: exabeam test.json
  operationId: site-collector-template-update
hidden: false
---
---
title: Get a Site Collector agent support-package command
excerpt: >-
  Support package command to generate the support package of the Site Collector
  agent.  The command is encoded in base64, necessitating a decoding step. This
  encoding ensures the command's integrity during transmission, maintaining its
  format and preventing alterations. For example, after you receive the
  response, you can decode the string using the command 

  `base64 -d <<< "c3Vkb..............."`

  After decoding the command from base64 to its original string format, you'll
  have the necessary shell commands to generate the support package of the Site
  Collector agent. The support package command varies depending on the type of
  Site Collector agent as defined in the Site Collector template. The command
  sequence downloads and runs a script to generate the support package of the
  agent.
api:
  file: exabeam test.json
  operationId: site-collectors-agent-get-support-package-command
hidden: false
---
---
title: Get a Site Collector agent installation command
excerpt: >-
  Install command to install the Site Collector agent. The command is encoded in
  base64, necessitating a decoding step. This encoding ensures the command's
  integrity during transmission, maintaining its format and preventing
  alterations. For example, after you receive the response, you can decode the
  string using the command `base64 -d <<< "c3Vkb..............."`.

  After decoding the command from base64 to its original string format, you'll
  have the necessary shell commands to install the Site Collector agent. The
  install command varies depending on the type of Site Collector agent as
  defined in the Site Collector template. The command sequence downloads and
  runs a script to configure the agent and passes in parameters
  (`deploymentHosts`, `templateIds`, and optionally `fetchStartDate` and
  `fetchHistoricalData`) that affect how the script configures the Site
  Collector agent.
api:
  file: exabeam test.json
  operationId: site-collectors-agent-get-installation-command
hidden: false
---
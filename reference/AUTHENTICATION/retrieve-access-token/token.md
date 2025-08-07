---
title: Retrieve access token using client credentials
excerpt: >-
  Use the token endpoint to retrieve a token for the client credential flow.
  Submit your client_id, client_secret, and the scopes that you’ll need the
  token to be able to access, and, CFD will return an access token with a
  specific lifetime (in the expires_in property in the response). CFD adds this
  token as a Bearer token in the Authorization header of any request going to
  the Mitek Cloud.
api:
  file: CFD API Auth.json
  operationId: token
hidden: false
---
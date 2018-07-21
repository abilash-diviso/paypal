---
swagger: "2.0"
info:
  title: PayPal (Sandbox)
  description: Bring payments to apps, mobile and social with Adaptive Payments &lt;b&gt;(Sandbox
    API).&lt;/b&gt;
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Permissions/GetBasicPersonalData:
    post:
      summary: Get Basic Personal Data
      description: Use the GetBasicPersonalData API operation to obtain basic personal
        data for an account holder
      operationId: Permissions.GetBasicPersonalData.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - profiles
definitions: []
---
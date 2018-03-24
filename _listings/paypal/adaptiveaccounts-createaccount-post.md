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
  /AdaptiveAccounts/CreateAccount:
    post:
      summary: Create Account
      description: The CreateAccount API operation enables you to create a PayPal
        account on behalf of a third party
      operationId: AdaptiveAccounts.CreateAccount.post
      parameters:
      - in: header
        name: X-PAYPAL-SANDBOX-EMAIL-ADDRESS
      responses:
        200:
          description: OK
      tags:
      - payments
definitions: []
---
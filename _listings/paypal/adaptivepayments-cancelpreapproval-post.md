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
  /AdaptivePayments/CancelPreapproval:
    post:
      summary: Cancel Preapproval
      description: Use the CancelPreapproval API operation to handle the canceling
        of preapprovals
      operationId: AdaptivePayments.CancelPreapproval.post
      responses:
        200:
          description: OK
      tags:
      - payments
definitions: []
---
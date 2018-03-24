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
  /AdaptivePayments/Refund:
    post:
      summary: Refund
      description: Use the Refund API operation to refund all or part of a payment
      operationId: AdaptivePayments.Refund.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - refunds
definitions: []
---
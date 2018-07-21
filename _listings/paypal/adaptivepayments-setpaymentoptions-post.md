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
  /AdaptivePayments/SetPaymentOptions:
    post:
      summary: Set Payment Options
      description: You use the SetPaymentOptions API operation to specify settings
        for a payment of the actionType CREATE
      operationId: AdaptivePayments.SetPaymentOptions.post
      responses:
        200:
          description: OK
      tags:
      - payments
definitions: []
---
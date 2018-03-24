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
  /AdaptivePayments/ExecutePayment:
    post:
      summary: Execute Payment
      description: The ExecutePayment API operation lets you execute a payment set
        up with the Pay API operation with the actionType CREATE
      operationId: AdaptivePayments.ExecutePayment.post
      responses:
        200:
          description: OK
      tags:
      - payments
definitions: []
---
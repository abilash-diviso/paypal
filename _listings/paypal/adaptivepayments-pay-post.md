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
  /AdaptivePayments/Pay:
    post:
      summary: Pay
      description: "Use the Pay API operation to transfer funds from a sender\u2019s
        PayPal account to one or more receivers\u2019 PayPal accounts"
      operationId: AdaptivePayments.Pay.post
      responses:
        200:
          description: OK
      tags:
      - payments
definitions: []
---
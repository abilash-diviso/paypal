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
  /AdaptivePayments/Preapproval:
    post:
      summary: Preapproval
      description: "Use the Preapproval API operation to set up an agreement between
        yourself and a sender for making payments on the sender\u2019s behalf"
      operationId: AdaptivePayments.Preapproval.post
      responses:
        200:
          description: OK
      tags:
      - payments
definitions: []
---
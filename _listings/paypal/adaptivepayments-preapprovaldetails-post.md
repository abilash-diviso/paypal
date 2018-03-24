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
  /AdaptivePayments/PreapprovalDetails:
    post:
      summary: Preapproval Details
      description: "Use the PreapprovalDetails API operation to obtain information
        about an agreement between you and a sender for making payments on the sender\u2019s
        behalf"
      operationId: AdaptivePayments.PreapprovalDetails.post
      responses:
        200:
          description: OK
      tags:
      - payments
definitions: []
---
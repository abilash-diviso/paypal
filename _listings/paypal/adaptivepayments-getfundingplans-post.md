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
  /AdaptivePayments/GetFundingPlans:
    post:
      summary: Get Funding Plans
      description: Use the GetFundingPlans API operation to determine the funding
        sources that are available for a specified payment, identified by its key,
        which takes into account the preferences and country of the receiver as well
        as the payment amount
      operationId: AdaptivePayments.GetFundingPlans.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - plans
definitions: []
---
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
  /AdaptivePayments/ConvertCurrency:
    post:
      summary: Convert Currency
      description: Use the ConvertCurrency API operation to request the current foreign
        exchange (FX) rate for a specific amount and currency
      operationId: AdaptivePayments.ConvertCurrency.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - currency
definitions: []
---
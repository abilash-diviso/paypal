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
  /AdaptivePayments/GetShippingAddresses:
    post:
      summary: Get Shipping Addresses
      description: Use the GetShippingAddresses API operation to obtain the selected
        shipping address
      operationId: AdaptivePayments.GetShippingAddresses.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - addresses
definitions: []
---
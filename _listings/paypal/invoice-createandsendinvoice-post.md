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
  /Invoice/CreateAndSendInvoice:
    post:
      summary: Create And Send Invoice
      description: Use the CreateAndSendInvoice API operation to create and send an
        invoice
      operationId: Invoice.CreateAndSendInvoice.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - invoices
definitions: []
---
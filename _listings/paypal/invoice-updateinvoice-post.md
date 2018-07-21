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
  /Invoice/UpdateInvoice:
    post:
      summary: Update Invoice
      description: Use the UpdateInvoice API operation to update an invoice
      operationId: Invoice.UpdateInvoice.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - invoices
definitions: []
---
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
  /Invoice/SendInvoice:
    post:
      summary: Send Invoice
      description: Use the SendInvoice API operation to send an invoice to a payer,
        and notify the payer of the pending invoice
      operationId: Invoice.SendInvoice.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - invoices
definitions: []
---
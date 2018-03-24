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
  /Permissions/RequestPermissions:
    post:
      summary: Request Permissions
      description: "Use the RequestPermissions API operation to request permissions
        to execute API operations on a PayPal account holder\u2019s behalf"
      operationId: Permissions.RequestPermissions.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - permissions
definitions: []
---
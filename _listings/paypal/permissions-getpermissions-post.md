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
  /Permissions/GetPermissions:
    post:
      summary: Get Permissions
      description: Use the GetPermissons API operation to obtain the permissions associated
        with an access token
      operationId: Permissions.GetPermissions.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - permissions
definitions: []
---
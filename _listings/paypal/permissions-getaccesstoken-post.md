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
  /Permissions/GetAccessToken:
    post:
      summary: GetAccess Token
      description: Use the GetAccessToken API operation to obtain an access token
        for a set of permissions
      operationId: Permissions.GetAccessToken.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - access tokens
definitions: []
---
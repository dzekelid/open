---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 1
info:
  title: SendGrid
  description: the-sendgrid-web-api-v3-documentation--this-is-the-entirety-of-the-documented-v3-endpoints--we-have-updated-all-the-descriptions-parameters-requests-and-responses--authentication-every-endpoint-requires-authentication-in-the-form-of-an-authorization-header-authorization-bearer-api-key
  version: 1.0.0
host: api.sendgrid.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /tracking_settings/open:
    get:
      summary: Get Tracking Settings Open
      description: "**This endpoint allows you to retrieve your current settings for
        open tracking.**\n\nOpen Tracking adds an invisible image at the end of the
        email which can track email opens. If the email recipient has images enabled
        on their email client, a request to SendGrid\u2019s server for the invisible
        image is executed and an open event is logged. These events are logged in
        the Statistics portal, Email Activity interface, and are reported by the Event
        Webhook.\n\nYou can track a variety of the actions your recipients may take
        when interacting with your emails including opening your emails, clicking
        on links in your emails, and subscribing to (or unsubscribing from) your emails.\n\nFor
        more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
      operationId: tracking_settings.open.get
      x-api-path-slug: tracking-settingsopen-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Tracking
      - Settings
      - Open
    patch:
      summary: Patch Tracking Settings Open
      description: "**This endpoint allows you to update your current settings for
        open tracking.**\n\nOpen Tracking adds an invisible image at the end of the
        email which can track email opens. If the email recipient has images enabled
        on their email client, a request to SendGrid\u2019s server for the invisible
        image is executed and an open event is logged. These events are logged in
        the Statistics portal, Email Activity interface, and are reported by the Event
        Webhook.\n\nYou can track a variety of the actions your recipients may take
        when interacting with your emails including opening your emails, clicking
        on links in your emails, and subscribing to (or unsubscribing from) your emails.\n\nFor
        more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html)."
      operationId: tracking_settings.open.patch
      x-api-path-slug: tracking-settingsopen-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Email
      - Tracking
      - Settings
      - Open
---
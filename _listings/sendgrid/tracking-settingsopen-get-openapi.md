---
swagger: "2.0"
x-collection-name: SendGrid
x-complete: 0
info:
  title: SendGrid Get Tracking Settings Open
  description: |-
    **This endpoint allows you to retrieve your current settings for open tracking.**

    Open Tracking adds an invisible image at the end of the email which can track email opens. If the email recipient has images enabled on their email client, a request to SendGrid???s server for the invisible image is executed and an open event is logged. These events are logged in the Statistics portal, Email Activity interface, and are reported by the Event Webhook.

    You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

    For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
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
      description: |-
        **This endpoint allows you to retrieve your current settings for open tracking.**

        Open Tracking adds an invisible image at the end of the email which can track email opens. If the email recipient has images enabled on their email client, a request to SendGrid???s server for the invisible image is executed and an open event is logged. These events are logged in the Statistics portal, Email Activity interface, and are reported by the Event Webhook.

        You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.

        For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).
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
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
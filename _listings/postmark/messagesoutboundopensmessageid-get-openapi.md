---
swagger: "2.0"
x-collection-name: Postmark
x-complete: 0
info:
  title: Postmark Get Messages Outbound Opens Message
  description: Get messages outbound opens message.
  version: 1.0.0
host: spamcheck.postmarkapp.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /messages/outbound/opens:
    get:
      summary: Get Messages Outbound Opens
      description: Get messages outbound opens.
      operationId: getMessagesOutboundOpens
      x-api-path-slug: messagesoutboundopens-get
      parameters:
      - in: query
        name: city
        description: Filter by full name of region messages were opened in, i
      - in: query
        name: client_company
        description: Filter by company, i
      - in: query
        name: client_family
        description: Filter by client family, i
      - in: query
        name: client_name
        description: Filter by client name, i
      - in: query
        name: count
        description: Number of message opens to return per request
      - in: query
        name: country
        description: Filter by country messages were opened in, i
      - in: query
        name: offset
        description: Number of messages to skip
      - in: query
        name: os_company
        description: Filter by company which produced the OS, i
      - in: query
        name: os_family
        description: Filter by kind of OS used without specific version, i
      - in: query
        name: os_name
        description: Filter by full OS name and specific version, i
      - in: query
        name: platform
        description: Filter by platform, i
      - in: query
        name: recipient
        description: Filter by To, Cc, Bcc
      - in: query
        name: region
        description: Filter by full name of region messages were opened in, i
      - in: query
        name: tag
        description: Filter by tag
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Outbound
      - Opens
  /messages/outbound/opens/{messageid}:
    get:
      summary: Get Messages Outbound Opens Message
      description: Get messages outbound opens message.
      operationId: getMessagesOutboundOpensMessage
      x-api-path-slug: messagesoutboundopensmessageid-get
      parameters:
      - in: query
        name: count
        description: Number of message opens to return per request
      - in: path
        name: messageid
        description: The ID of the Outbound Message for which open statistics should
          be retrieved
      - in: query
        name: offset
        description: Number of messages to skip
      - in: header
        name: X-Postmark-Server-Token
        description: The token associated with the Server on which this request will
          operate
      responses:
        200:
          description: OK
      tags:
      - Messages
      - Outbound
      - Opens
      - Messageid
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
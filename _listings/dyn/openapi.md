---
swagger: "2.0"
x-collection-name: Dyn
x-complete: 1
info:
  title: Dyn
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  opens/count:
    get:
      summary: Email Open Count
      description: Returns total number of opens for the specified account for the
        specified date range. Including a date range is highly recommended.
      operationId: getOpensCount
      x-api-path-slug: openscount-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: emailaddress
        description: Email address of recipient for filtering
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: u00a0Email address of sender for filtering
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - .Email
      - Open
      - Count
  reports/opens/count/unique:
    get:
      summary: Retrieve Count of Email Opens
      description: Returns total number of unique opens for the specified account
        for the specified date range. Including a date range is highly recommended.
      operationId: getReportsOpensCountUnique
      x-api-path-slug: reportsopenscountunique-get
      parameters:
      - in: query
        name: apikey
        description: Required
      - in: query
        name: emailaddress
        description: Email address of recipient for filtering
      - in: query
        name: endtime
        description: Required
      - in: query
        name: sender
        description: u00a0Email address of sender for filtering
      - in: query
        name: starttime
        description: Required
      - in: query
        name: '[X-HeaderName]'
        description: Name of searchable custom X-header
      responses:
        200:
          description: OK
      tags:
      - Retrieve
      - Count
      - of
      - Email
      - Opens
---
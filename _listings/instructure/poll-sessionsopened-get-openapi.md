---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Polls API List opened poll sessions
  description: List opened poll sessions.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /polls/{poll_id}/poll_sessions/id/open:
    get:
      summary: Open a poll session
      description: Open a poll session.
      operationId: open-a-poll-session
      x-api-path-slug: pollspoll-idpoll-sessionsidopen-get
      responses:
        200:
          description: OK
      tags:
      - Polls
      - Poll
      - Id
      - Poll
      - Sessions
      - Id
      - Open
  /poll_sessions/opened:
    get:
      summary: List opened poll sessions
      description: List opened poll sessions.
      operationId: list-opened-poll-sessions
      x-api-path-slug: poll-sessionsopened-get
      responses:
        200:
          description: OK
      tags:
      - Poll
      - Sessions
      - Opened
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
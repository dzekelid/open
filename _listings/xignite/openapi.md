---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Global Holidays
  description: this-web-service-provides-tradingholiday-information-for-all-exchangescurrenciesfinancial-centers-
  version: 1.0.0
host: globalholidays.xignite.com
basePath: xGlobalHolidays.json/XigniteGlobalHolidays
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /AreExchangesOpen:
    get:
      summary: Are Exchanges Open
      description: Are exchanges open.
      operationId: AreExchangesOpen
      x-api-path-slug: areexchangesopen-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Are
      - Exchanges
      - Open
  /IsExchangeOpenOnDate:
    get:
      summary: Is Exchange Open On Date
      description: Is exchange open on date.
      operationId: IsExchangeOpenOnDate
      x-api-path-slug: isexchangeopenondate-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Exchange
      - Open
      - "On"
      - Date
---
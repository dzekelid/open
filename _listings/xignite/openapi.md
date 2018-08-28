swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite VWAP
  description: provides-delayed-and-historical-volumeweightedaverage-price-vwap-information-
  version: 1.0.0
host: www.xignite.com
basePath: xVWAP.json/XigniteVWAP
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /GetDailyOpenHighLowClosePrice:
    get:
      summary: Get Daily Open High Low Close Price
      description: Returns daily Open, High, Low, Close (OHLC) prices for a specific
        bond reported by the price source selected in the input. Daily OHLC data is
        provided for the most recent date for which data is provided by the price
        source. Request against this operation counts as one hit.
      operationId: GetDailyOpenHighLowClosePrice
      x-api-path-slug: getdailyopenhighlowcloseprice-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Daily
      - Open
      - High
      - Low
      - Close
      - Price
  /GetDailyOpenHighLowClosePrices:
    get:
      summary: Get Daily Open High Low Close Prices
      description: Returns daily Open, High, Low, Close (OHLC) prices for the list
        of bonds specified in the input. Daily OHLC data is provided for the most
        recent date for which data is provided by the price source. Each DailyOpenHighLowClosePrice
        object  returned counts as one hit.
      operationId: GetDailyOpenHighLowClosePrices
      x-api-path-slug: getdailyopenhighlowcloseprices-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Daily
      - Open
      - High
      - Low
      - Close
      - Prices
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
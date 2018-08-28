---
swagger: "2.0"
x-collection-name: Paylocity
x-complete: 0
info:
  title: Paylocity Get Company-Specific Open API Documentation
  description: The company-specific Open API endpoint allows the client to GET an
    Open API document for the Paylocity API that is customized with company-specific
    resource schemas. These customized resource schemas define certain properties
    as enumerations of pre-defined values that correspond to the company's setup with
    Web Pay. The customized schemas also indicate which properties are required by
    the company within Web Pay.<br  />To learn more about Open API, click [here](https://www.openapis.org/)
  termsOfService: WebLink.OpenApiDoc.TermsOfService
  version: "2"
host: api.paylocity.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/companies/{companyId}/openapi:
    get:
      summary: Get Company-Specific Open API Documentation
      description: The company-specific Open API endpoint allows the client to GET
        an Open API document for the Paylocity API that is customized with company-specific
        resource schemas. These customized resource schemas define certain properties
        as enumerations of pre-defined values that correspond to the company's setup
        with Web Pay. The customized schemas also indicate which properties are required
        by the company within Web Pay.<br  />To learn more about Open API, click [here](https://www.openapis.org/)
      operationId: v2.companies.companyId.openapi.get
      x-api-path-slug: v2companiescompanyidopenapi-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer + JWT
      - in: path
        name: companyId
        description: Company Id
      responses:
        200:
          description: OK
      tags:
      - V2
      - Companies
      - CompanyId
      - Openapi
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
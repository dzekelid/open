---
swagger: "2.0"
x-collection-name: Microsoft Graph
x-complete: 0
info:
  title: Microsoft Graph Delete Open Extension
  description: Delete open extension Delete an open extension (openTypeExtension object)
    from the specified instance of a resource.
  version: 1.0.0
host: graph.microsoft.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{id|userPrincipalName}/contacts/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnamecontactsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
  /users/{id|userPrincipalName}/events/{id}/extensions/{extensionId}:
    delete:
      summary: Delete Open Extension
      description: Delete open extension Delete an open extension (openTypeExtension
        object) from the specified instance of a resource.
      operationId: DeleteOpenExtension
      x-api-path-slug: usersiduserprincipalnameeventsidextensionsextensionid-delete
      parameters:
      - in: header
        name: Authorization
        description: Bearer %token%
      - in: path
        name: extensionId
        type: string
      - in: path
        name: id
        type: string
      - in: path
        name: id|userPrincipalName
        type: string
      responses:
        200:
          description: OK
      tags:
      - Open
      - Extension
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
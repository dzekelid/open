swagger: "2.0"
x-collection-name: AWS Lightsale
x-complete: 1
info:
  title: AWS Lightsale API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=OpenInstancePublicPorts:
    get:
      summary: Open Instance Public Ports
      description: Adds public ports to an Amazon Lightsail instance.
      operationId: openInstancePublicPorts
      x-api-path-slug: actionopeninstancepublicports-get
      parameters:
      - in: query
        name: instanceName
        description: The name of the instance for which you want to open the public
          ports
        type: string
      - in: query
        name: portInfo
        description: An array of key-value pairs containing information about the
          port mappings
        type: string
      responses:
        200:
          description: OK
      tags:
      - Instances
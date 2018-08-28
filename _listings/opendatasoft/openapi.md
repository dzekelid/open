swagger: "2.0"
x-collection-name: OpenDataSoft
x-complete: 1
info:
  title: OpenDataSoft
  description: opendatasoft-is-a-cloudbased-turnkey-platform-for-data-publishing-and-api-management--its-interface-is-intuitively-designed-to-empower-anyone-regardless-of-technical-skills-to-upload-easytounderstand-open-data-or-to-even-share-data-within-an-admi---
  version: 2.1.0
host: public.opendatasoft.com
basePath: /api/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /:
    get:
      summary: Get
      description: |-
        API entry point

        Provides links for:
        * catalog, your domain's list of datasets
        * opendatasoft, all datasets on the OpenDataSoft network
      operationId: getRoot
      x-api-path-slug: get
      responses:
        200:
          description: OK
      tags:
      - ""
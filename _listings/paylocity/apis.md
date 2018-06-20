---
name: Paylocity
x-slug: paylocity
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Open
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/paylocity/apis.md
specificationVersion: "0.14"
apis:
- name: Paylocity Get Company-Specific Open API Documentation
  x-api-slug: paylocity
  description: The company-specific Open API endpoint allows the client to GET an
    Open API document for the Paylocity API that is customized with company-specific
    resource schemas. These customized resource schemas define certain properties
    as enumerations of pre-defined values that correspond to the company's setup with
    Web Pay. The customized schemas also indicate which properties are required by
    the company within Web Pay.<br  />To learn more about Open API, click [here](https://www.openapis.org/)
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api//v2/companies/{companyId}/openapi
  tags: V2,Companies,CompanyId,Openapi
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/paylocity/v2companiescompanyidopenapi-get-openapi.md
- name: Paylocity
  x-api-slug: paylocity
  description: ""
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api
  tags: Open
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/paylocity/openapi.md
x-common:
- type: x-blog
  url: https://www.paylocity.com/resources/blog/
- type: x-github
  url: https://github.com/Paylocity
- type: x-integrations
  url: https://www.paylocity.com/partnerships/integrations/
- type: x-twitter
  url: https://twitter.com/Paylocity
- type: x-website
  url: http://paylocity.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
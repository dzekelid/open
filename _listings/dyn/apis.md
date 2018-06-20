---
name: Dyn
x-slug: dyn
description: Dyn is home to the worlds most trusted DNS product suite and the worlds
  most reputable Email Deliverability Service.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
x-kinRank: "8"
x-alexaRank: "20789"
tags: Open
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/dyn/apis.md
specificationVersion: "0.14"
apis:
- name: Dyn Email Open Count
  x-api-slug: dyn
  description: Returns total number of opens for the specified account for the specified
    date range. Including a date range is highly recommended.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////opens/count
  tags: .Email, Open, Count
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/dyn/openscount-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/dyn/openscount-get-openapi.md
- name: Dyn Retrieve Count of Email Opens
  x-api-slug: dyn
  description: Returns total number of unique opens for the specified account for
    the specified date range. Including a date range is highly recommended.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:////reports/opens/count/unique
  tags: Retrieve, Count, of,Email, Opens
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/dyn/reportsopenscountunique-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/dyn/reportsopenscountunique-get-openapi.md
- name: Dyn
  x-api-slug: dyn
  description: Dyn is home to the worlds most trusted DNS product suite and the worlds
    most reputable Email Deliverability Service.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/582-dyn.jpg
  humanURL: http://dynect.net
  baseURL: https:///
  tags: Open
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/dyn/openapi.md
x-common:
- type: x-base
  url: https://api.dynect.net
- type: x-blog
  url: http://research.dyn.com/
- type: x-blog
  url: http://dyn.com/blog/
- type: x-blog-rss
  url: http://feeds.feedburner.com/dyn-blog
- type: x-blog-rss
  url: http://research.dyn.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/dyn
- type: x-crunchbase
  url: https://crunchbase.com/organization/dyn
- type: x-developer
  url: https://help.dyn.com/developers/
- type: x-email
  url: billing@dyndns.com
- type: x-email
  url: privacy@dyn.com
- type: x-forum
  url: http://www.dyndnscommunity.com/
- type: x-getting-started
  url: http://dyn.com/product-wizard/
- type: x-github
  url: https://github.com/dyninc
- type: x-partners
  url: http://dyn.com/about/partners/
- type: x-php-sdk
  url: https://github.com/dyninc/dyn-php/
- type: x-privacy
  url: http://dyn.com/legal/dyn-privacy-policy/
- type: x-python-sdk
  url: https://github.com/dyninc/dyn-python/
- type: x-selfservice-registration
  url: https://account.dyn.com/entrance/
- type: x-status
  url: http://www.dynstatus.com/
- type: x-terms-of-service
  url: http://dyn.com/legal/dyn-services-agreement/
- type: x-twitter
  url: https://twitter.com/Dyn
- type: x-website
  url: http://dynect.net
- type: x-website
  url: http://dyn.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
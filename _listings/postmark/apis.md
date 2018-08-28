---
name: Postmark
x-slug: postmark
description: Trusted by thousands of developers, Postmark is a fast and reliable transactional
  email service. Send with Postmark to ensure your transactional emails get to the
  inbox on time, every time.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
x-kinRank: "8"
x-alexaRank: "87545"
tags: Open
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/apis.md
specificationVersion: "0.14"
apis:
- name: Postmark Get Messages Outbound Opens
  x-api-slug: postmark
  description: Get messages outbound opens.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/opens
  tags: Messages,Outbound,Opens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/messagesoutboundopens-get-openapi.md
- name: Postmark Get Messages Outbound Opens Message
  x-api-slug: postmark
  description: Get messages outbound opens message.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////messages/outbound/opens/{messageid}
  tags: Messages,Outbound,Opens,Messageid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/messagesoutboundopensmessageid-get-openapi.md
- name: Postmark Get Stats Outbound Opens
  x-api-slug: postmark
  description: Get stats outbound opens.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////stats/outbound/opens
  tags: Stats,Outbound,Opens
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/statsoutboundopens-get-openapi.md
- name: Postmark Get Stats Outbound Opens Emailclients
  x-api-slug: postmark
  description: Get stats outbound opens emailclients.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////stats/outbound/opens/emailclients
  tags: Stats,Outbound,Opens,Emailclients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/statsoutboundopensemailclients-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/statsoutboundopensemailclients-get-openapi.md
- name: Postmark Get Stats Outbound Opens Platforms
  x-api-slug: postmark
  description: Get stats outbound opens platforms.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////stats/outbound/opens/platforms
  tags: Stats,Outbound,Opens,Platforms
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/statsoutboundopensplatforms-get-openapi.md
- name: Postmark Get Stats Outbound Opens Readtimes
  x-api-slug: postmark
  description: Get stats outbound opens readtimes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com////stats/outbound/opens/readtimes
  tags: Stats,Outbound,Opens,Readtimes
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/statsoutboundopensreadtimes-get-openapi.md
- name: Postmark
  x-api-slug: postmark
  description: Postmark helps deliver and track transactional emails for web applications.
    In a nutshell, the service replaces SMTP (or Sendmail) with a far more reliable,
    scalable and care-free environment. In addition, you can track statistics for
    number of emails sent, bounces and spam complaints.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/638-postmark.jpg
  humanURL: http://postmarkapp.com
  baseURL: https://spamcheck.postmarkapp.com//
  tags: Open
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/open/master/_listings/postmark/openapi.md
x-common:
- type: x--net-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#dot-net
- type: x-base
  url: https://api.postmarkapp.com
- type: x-blog
  url: http://blog.postmarkapp.com/
- type: x-blog-rss
  url: http://blog.postmarkapp.com/rss
- type: x-contact-form
  url: http://support.postmarkapp.com/customer/portal/emails/new
- type: x-crunchbase
  url: https://crunchbase.com/organization/postmark
- type: x-crunchbase
  url: http://www.crunchbase.com/company/postmark
- type: x-developer
  url: http://developer.postmarkapp.com/
- type: x-email
  url: support@postmarkapp.com
- type: x-email
  url: 451d9b70cf9364d23ff6f9d51d870251569e+ahoy@inbound.postmarkapp.com
- type: x-faq
  url: http://support.postmarkapp.com/
- type: x-pricing
  url: http://developer.postmarkapp.com/developer-api-messages.html
- type: x-privacy
  url: https://postmarkapp.com/privacy-policy
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#rails
- type: x-ruby-library
  url: http://developer.postmarkapp.com/developer-official-libs.html#ruby
- type: x-selfservice-registration
  url: https://postmarkapp.com/sign_up
- type: x-status
  url: http://status.postmarkapp.com/
- type: x-terms-of-service
  url: https://postmarkapp.com/terms-of-service
- type: x-twitter
  url: https://twitter.com/postmarkapp
- type: x-website
  url: http://postmarkapp.com
- type: x-website
  url: http://postmarkapp.com/
- type: x-website
  url: https://postmarkapp.com
- type: x-wordpress-pdk
  url: http://developer.postmarkapp.com/developer-official-libs.html#wordpress
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
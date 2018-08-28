---
name: Google Safe Browsing
x-slug: google-safe-browsing
description: The Safe Browsing APIs (v4) let your client applications check URLs against
  Googles constantly updated lists of unsafe web resources. Examples of unsafe web
  resources are social engineering sites (phishing and deceptive sites) and sites
  that host malware or unwanted software. Any URL found on a Safe Browsing list is
  considered unsafe.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Threats
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/threats/master/_listings/google-safe-browsing/apis.md
specificationVersion: "0.14"
apis:
- name: Google Safe Browsing - List Most Recent Threats
  x-api-slug: v4threatlistupdatesfetch-post
  description: |-
    Fetches the most recent threat list updates. A client can request updates
    for multiple lists at once.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com//
  tags: Google APIs, Links, Privacy, Security, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/threats/master/_listings/google-safe-browsing/v4threatlistupdatesfetch-post-openapi.md
- name: Google Safe Browsing - List Threats
  x-api-slug: v4threatlists-get
  description: Lists the Safe Browsing threat lists available for download.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com//
  tags: Google APIs, Links, Privacy, Security, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/threats/master/_listings/google-safe-browsing/v4threatlists-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/threats/master/_listings/google-safe-browsing/v4threatlists-get-openapi.md
- name: Google Safe Browsing - Find Threat Entry
  x-api-slug: v4threatmatchesfind-post
  description: Finds the threat entries that match the Safe Browsing lists.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/SafeBrowsing_Icon.png
  humanURL: https://developers.google.com/safe-browsing/
  baseURL: ://safebrowsing.googleapis.com//
  tags: Google APIs, Links, Privacy, Security, Stack Network, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/threats/master/_listings/google-safe-browsing/v4threatmatchesfind-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.qpx.express.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.safe.browsing.stack.network
- type: x-documentation
  url: https://developers.google.com/safe-browsing/v4/
- type: x-forum
  url: http://groups.google.com/group/google-safe-browsing-api
- type: x-getting-started
  url: https://developers.google.com/safe-browsing/v4/get-started
- type: x-website
  url: https://developers.google.com/safe-browsing/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
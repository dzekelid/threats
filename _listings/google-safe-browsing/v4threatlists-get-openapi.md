---
swagger: "2.0"
x-collection-name: Google Safe Browsing
x-complete: 0
info:
  title: Google Safe Browsing API List Threats
  description: Lists the Safe Browsing threat lists available for download.
  contact:
    name: Google
    url: https://google.com
  version: v4
host: safebrowsing.googleapis.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v4/threatListUpdates:fetch:
    post:
      summary: List Most Recent Threats
      description: |-
        Fetches the most recent threat list updates. A client can request updates
        for multiple lists at once.
      operationId: safebrowsing.threatListUpdates.fetch
      x-api-path-slug: v4threatlistupdatesfetch-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Threats
  /v4/threatLists:
    get:
      summary: List Threats
      description: Lists the Safe Browsing threat lists available for download.
      operationId: safebrowsing.threatLists.list
      x-api-path-slug: v4threatlists-get
      responses:
        200:
          description: OK
      tags:
      - Threats
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
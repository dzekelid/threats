---
swagger: "2.0"
info:
  title: Google Safe Browsing API Find Threat Entry
  description: Finds the threat entries that match the Safe Browsing lists.
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
  /v4/threatMatches:find:
    post:
      summary: Find Threat Entry
      description: Finds the threat entries that match the Safe Browsing lists
      operationId: safebrowsing.threatMatches.find
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - threats
definitions:
  Checksum:
    properties:
      sha256:
        description: This is a default description.
        type: post
  ClientInfo:
    properties:
      clientId:
        description: This is a default description.
        type: post
      clientVersion:
        description: This is a default description.
        type: post
  Constraints:
    properties:
      maxDatabaseEntries:
        description: This is a default description.
        type: post
      maxUpdateEntries:
        description: This is a default description.
        type: post
      region:
        description: This is a default description.
        type: post
      supportedCompressions:
        description: This is a default description.
        type: post
  FetchThreatListUpdatesRequest:
    properties:
      listUpdateRequests:
        description: This is a default description.
        type: post
  FetchThreatListUpdatesResponse:
    properties:
      listUpdateResponses:
        description: This is a default description.
        type: post
      minimumWaitDuration:
        description: This is a default description.
        type: post
  FindFullHashesRequest:
    properties:
      clientStates:
        description: This is a default description.
        type: post
  FindFullHashesResponse:
    properties:
      matches:
        description: This is a default description.
        type: post
      minimumWaitDuration:
        description: This is a default description.
        type: post
      negativeCacheDuration:
        description: This is a default description.
        type: post
  FindThreatMatchesRequest:
    properties: []
  FindThreatMatchesResponse:
    properties:
      matches:
        description: This is a default description.
        type: post
  ListThreatListsResponse:
    properties:
      threatLists:
        description: This is a default description.
        type: post
  ListUpdateRequest:
    properties:
      platformType:
        description: This is a default description.
        type: post
      state:
        description: This is a default description.
        type: post
      threatEntryType:
        description: This is a default description.
        type: post
      threatType:
        description: This is a default description.
        type: post
  ListUpdateResponse:
    properties:
      additions:
        description: This is a default description.
        type: post
      newClientState:
        description: This is a default description.
        type: post
      platformType:
        description: This is a default description.
        type: post
      removals:
        description: This is a default description.
        type: post
      responseType:
        description: This is a default description.
        type: post
      threatEntryType:
        description: This is a default description.
        type: post
      threatType:
        description: This is a default description.
        type: post
  MetadataEntry:
    properties:
      key:
        description: This is a default description.
        type: post
      value:
        description: This is a default description.
        type: post
  RawHashes:
    properties:
      prefixSize:
        description: This is a default description.
        type: post
      rawHashes:
        description: This is a default description.
        type: post
  RawIndices:
    properties:
      indices:
        description: This is a default description.
        type: post
  RiceDeltaEncoding:
    properties:
      encodedData:
        description: This is a default description.
        type: post
      firstValue:
        description: This is a default description.
        type: post
      numEntries:
        description: This is a default description.
        type: post
      riceParameter:
        description: This is a default description.
        type: post
  ThreatEntry:
    properties:
      digest:
        description: This is a default description.
        type: post
      hash:
        description: This is a default description.
        type: post
      url:
        description: This is a default description.
        type: post
  ThreatEntryMetadata:
    properties:
      entries:
        description: This is a default description.
        type: post
  ThreatEntrySet:
    properties:
      compressionType:
        description: This is a default description.
        type: post
  ThreatInfo:
    properties:
      platformTypes:
        description: This is a default description.
        type: post
      threatEntries:
        description: This is a default description.
        type: post
      threatEntryTypes:
        description: This is a default description.
        type: post
      threatTypes:
        description: This is a default description.
        type: post
  ThreatListDescriptor:
    properties:
      platformType:
        description: This is a default description.
        type: post
      threatEntryType:
        description: This is a default description.
        type: post
      threatType:
        description: This is a default description.
        type: post
  ThreatMatch:
    properties:
      cacheDuration:
        description: This is a default description.
        type: post
      platformType:
        description: This is a default description.
        type: post
      threatEntryType:
        description: This is a default description.
        type: post
      threatType:
        description: This is a default description.
        type: post
x-collection-name: Google Safe Browsing
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
---
swagger: "2.0"
info:
  title: Akamai API Get Audience Size
  description: Get Audience Size
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  timeAggInterval:
    get:
      summary: Get Audience Size
      description: Get Audience Size
      operationId: timeagginterval
      parameters:
      - in: query
        name: accountId
        description: Unique identifier for the account
        type: string
      - in: query
        name: endDate
        description: The end date
        type: string
      - in: query
        name: eventId
        description: Unique identifier for the event
        type: string
      - in: query
        name: reportPackID
        description: Unique numeric identifier for the report pack
        type: string
      - in: query
        name: startDate
        description: The start date
        type: string
      - in: query
        name: timeAggInterval
        description: Defaults to 60 minutes
        type: string
      responses:
        200:
          description: OK
      tags:
      - audience
definitions: []
x-collection-name: Akamai
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
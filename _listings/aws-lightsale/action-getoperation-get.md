---
swagger: "2.0"
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
  /?Action=GetOperation:
    get:
      summary: ' Get Operation '
      description: Returns information about a specific operation
      operationId: getOperation
      parameters:
      - in: query
        name: operationId
        description: A GUID used to identify the operation
        type: string
      responses:
        200:
          description: OK
      tags:
      - operations
definitions: []
x-collection-name: AWS Lightsale
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
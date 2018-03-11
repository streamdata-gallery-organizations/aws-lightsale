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
  /?Action=GetBlueprints&k=1:
    get:
      summary: ' Get Blueprints '
      description: Returns the list of available instance images, or blueprints
      operationId: getBlueprints
      parameters:
      - in: query
        name: includeInactive
        description: A Boolean value indicating whether to include inactive results
          in your      request
        type: string
      - in: query
        name: pageToken
        description: A token used for advancing to the next page of results from your
          get blueprints      request
        type: string
      responses:
        200:
          description: OK
      tags:
      - instances
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
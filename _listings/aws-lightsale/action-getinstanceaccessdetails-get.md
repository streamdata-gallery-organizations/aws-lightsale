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
  /?Action=GetInstanceAccessDetails:
    get:
      summary: ' Get Instance Access Details '
      description: |-
        Returns temporary SSH keys you can use to connect to a specific virtual private server,
              or instance
      operationId: getInstanceAccessDetails
      parameters:
      - in: query
        name: instanceName
        description: The name of the instance to access
        type: string
      - in: query
        name: protocol
        description: The protocol to use to connect to your instance
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
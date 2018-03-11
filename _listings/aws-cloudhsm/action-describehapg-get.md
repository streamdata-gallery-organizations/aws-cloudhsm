---
swagger: "2.0"
info:
  title: AWS CloudHSM API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DescribeHapg&k=1:
    get:
      summary: ' Describe HAPG '
      description: Retrieves information about a high-availability partition group
      operationId: describeHapg
      parameters:
      - in: query
        name: HapgArn
        description: The ARN of the high-availability partition group to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - high-availability partition group
definitions: []
x-collection-name: AWS CloudHSM
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
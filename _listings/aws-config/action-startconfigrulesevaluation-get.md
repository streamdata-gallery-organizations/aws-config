---
swagger: "2.0"
info:
  title: AWS Config API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=StartConfigRulesEvaluation:
    get:
      summary: ' Start Config Rules Evaluation '
      description: Runs an on-demand evaluation for the specified Config rules against
        the last known configuration state of the resources
      operationId: startConfigRulesEvaluation
      parameters:
      - in: query
        name: ConfigRuleNames
        description: The list of names of Config rules that you want to run evaluations
          for
        type: string
      responses:
        200:
          description: OK
      tags:
      - evaluations
definitions: []
x-collection-name: AWS Config
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
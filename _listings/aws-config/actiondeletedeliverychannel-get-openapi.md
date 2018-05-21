---
swagger: "2.0"
x-collection-name: AWS Config
x-complete: 0
info:
  title: AWS Config API Delete Delivery Channel
  version: 1.0.0
  description: Deletes the delivery channel.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteConfigRule:
    get:
      summary: Delete Config Rule
      description: Deletes the specified AWS Config rule and all of its evaluation
        results.
      operationId: deleteConfigRule
      x-api-path-slug: actiondeleteconfigrule-get
      parameters:
      - in: query
        name: ConfigRuleName
        description: The name of the AWS Config rule that you want to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Rules
  /?Action=DeleteConfigurationRecorder:
    get:
      summary: Delete Configuration Recorder
      description: Deletes the configuration recorder.
      operationId: deleteConfigurationRecorder
      x-api-path-slug: actiondeleteconfigurationrecorder-get
      parameters:
      - in: query
        name: ConfigurationRecorderName
        description: The name of the configuration recorder to be deleted
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Recorders
  /?Action=DeleteDeliveryChannel:
    get:
      summary: Delete Delivery Channel
      description: Deletes the delivery channel.
      operationId: deleteDeliveryChannel
      x-api-path-slug: actiondeletedeliverychannel-get
      parameters:
      - in: query
        name: DeliveryChannelName
        description: The name of the delivery channel to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Delivery Channels
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
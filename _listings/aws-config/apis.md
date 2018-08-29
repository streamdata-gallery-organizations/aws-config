---
name: AWS Config
x-slug: aws-config
description: AWS Config is a fully managed service that provides you with an AWS resource
  inventory, configuration history, and configuration change notifications to enable
  security and governance. Config Rules enables you to create rules that automatically
  check the configuration of AWS resources recorded by AWS Config.With AWS Config,
  you can discover existing and deleted AWS resources, determine your overall compliance
  against rules, and dive into configuration details of a resource at any point in
  time. These capabilities enable compliance auditing, security analysis, resource
  change tracking, and troubleshooting.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Config
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Config API - Delete Config Rule
  x-api-slug: actiondeleteconfigrule-get
  description: Deletes the specified AWS Config rule and all of its evaluation results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondeleteconfigrule-get-openapi.md
- name: AWS Config API - Delete Configuration Recorder
  x-api-slug: actiondeleteconfigurationrecorder-get
  description: Deletes the configuration recorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondeleteconfigurationrecorder-get-openapi.md
- name: AWS Config API - Delete Delivery Channel
  x-api-slug: actiondeletedeliverychannel-get
  description: Deletes the delivery channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondeletedeliverychannel-get-openapi.md
- name: AWS Config API - Delete Evaluation Results
  x-api-slug: actiondeleteevaluationresults-get
  description: Deletes the evaluation results for the specified Config rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondeleteevaluationresults-get-openapi.md
- name: AWS Config API - Deliver Config Snapshot
  x-api-slug: actiondeliverconfigsnapshot-get
  description: Schedules delivery of a configuration snapshot to the Amazon S3 bucket
    in the specified delivery channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondeliverconfigsnapshot-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondeliverconfigsnapshot-get-openapi.md
- name: AWS Config API - Describe Compliance By Config Rule
  x-api-slug: actiondescribecompliancebyconfigrule-get
  description: Indicates whether the specified AWS Config rules are compliant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribecompliancebyconfigrule-get-openapi.md
- name: AWS Config API - Describe Compliance By Resource
  x-api-slug: actiondescribecompliancebyresource-get
  description: Indicates whether the specified AWS resources are compliant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribecompliancebyresource-get-openapi.md
- name: AWS Config API - Describe Config Rule Evaluation Status
  x-api-slug: actiondescribeconfigruleevaluationstatus-get
  description: Returns status information for each of your AWS managed Config rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribeconfigruleevaluationstatus-get-openapi.md
- name: AWS Config API - Describe Config Rules
  x-api-slug: actiondescribeconfigrules-get
  description: Returns details about your AWS Config rules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribeconfigrules-get-openapi.md
- name: AWS Config API - Describe Configuration Recorders
  x-api-slug: actiondescribeconfigurationrecorders-get
  description: Returns the details for the specified configuration recorders.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribeconfigurationrecorders-get-openapi.md
- name: AWS Config API - Describe Configuration Recorder Status
  x-api-slug: actiondescribeconfigurationrecorderstatus-get
  description: Returns the current status of the specified configuration recorder.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribeconfigurationrecorderstatus-get-openapi.md
- name: AWS Config API - Describe Delivery Channels
  x-api-slug: actiondescribedeliverychannels-get
  description: Returns details about the specified delivery channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribedeliverychannels-get-openapi.md
- name: AWS Config API - Describe Delivery Channel Status
  x-api-slug: actiondescribedeliverychannelstatus-get
  description: Returns the current status of the specified delivery channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiondescribedeliverychannelstatus-get-openapi.md
- name: AWS Config API - Get Compliance Details By Config Rule
  x-api-slug: actiongetcompliancedetailsbyconfigrule-get
  description: Returns the evaluation results for the specified AWS Config rule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiongetcompliancedetailsbyconfigrule-get-openapi.md
- name: AWS Config API - Get Compliance Details By Resource
  x-api-slug: actiongetcompliancedetailsbyresource-get
  description: Returns the evaluation results for the specified AWS resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiongetcompliancedetailsbyresource-get-openapi.md
- name: AWS Config API - Get Compliance Summary By Config Rule
  x-api-slug: actiongetcompliancesummarybyconfigrule-get
  description: "Returns the number of AWS Config rules that are compliant and noncompliant,
    up to a\n\t\t\tmaximum of 25 for each."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiongetcompliancesummarybyconfigrule-get-openapi.md
- name: AWS Config API - Get Compliance Summary By Resource Type
  x-api-slug: actiongetcompliancesummarybyresourcetype-get
  description: Returns the number of resources that are compliant and the number that
    are noncompliant.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiongetcompliancesummarybyresourcetype-get-openapi.md
- name: AWS Config API - Get Resource Config History
  x-api-slug: actiongetresourceconfighistory-get
  description: Returns a list of configuration items for the specified resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actiongetresourceconfighistory-get-openapi.md
- name: AWS Config API - List Discovered Resources
  x-api-slug: actionlistdiscoveredresources-get
  description: Accepts a resource type and returns a list of resource identifiers
    for the resources of that type.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionlistdiscoveredresources-get-openapi.md
- name: AWS Config API - Put Config Rule
  x-api-slug: actionputconfigrule-get
  description: "Adds or updates an AWS Config rule for evaluating whether your AWS
    resources comply\n\t\t\twith your desired configurations."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionputconfigrule-get-openapi.md
- name: AWS Config API - Put Configuration Recorder
  x-api-slug: actionputconfigurationrecorder-get
  description: Creates a new configuration recorder to record the selected resource
    configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionputconfigurationrecorder-get-openapi.md
- name: AWS Config API - Put Delivery Channel
  x-api-slug: actionputdeliverychannel-get
  description: Creates a delivery channel object to deliver configuration information
    to an Amazon S3 bucket and Amazon SNS topic.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionputdeliverychannel-get-openapi.md
- name: AWS Config API - Put Evaluations
  x-api-slug: actionputevaluations-get
  description: Used by an AWS Lambda function to deliver evaluation results to AWS
    Config.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionputevaluations-get-openapi.md
- name: AWS Config API - Start Config Rules Evaluation
  x-api-slug: actionstartconfigrulesevaluation-get
  description: Runs an on-demand evaluation for the specified Config rules against
    the last known configuration state of the resources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionstartconfigrulesevaluation-get-openapi.md
- name: AWS Config API - Start Configuration Recorder
  x-api-slug: actionstartconfigurationrecorder-get
  description: Starts recording configurations of the AWS resources you have selected
    to record in your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionstartconfigurationrecorder-get-openapi.md
- name: AWS Config API - Stop Configuration Recorder
  x-api-slug: actionstopconfigurationrecorder-get
  description: Stops recording configurations of the AWS resources you have selected
    to record in your AWS account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Management-Tools_AWSConfig.png
  humanURL: https://aws.amazon.com/config/
  baseURL: :///
  tags: Amazon Web Services, Applications, Regulations, Governance, Security, Authentication,
    Stack Network, API Service Provider, API Service Provider, API Provider, Profiles,
    Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-config/master/_listings/aws-config/actionstopconfigurationrecorder-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.cognito.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.config.stack.network
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/configservice/index.html
- type: x-console
  url: https://console.aws.amazon.com/config
- type: x-documentation
  url: http://docs.aws.amazon.com/config/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/config/faq/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=184
- type: x-getting-started
  url: https://aws.amazon.com/config/getting-started/
- type: x-partners
  url: https://aws.amazon.com/config/partners/
- type: x-pricing
  url: https://aws.amazon.com/config/pricing/
- type: x-support
  url: https://console.aws.amazon.com/support/
- type: x-website
  url: https://aws.amazon.com/config/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
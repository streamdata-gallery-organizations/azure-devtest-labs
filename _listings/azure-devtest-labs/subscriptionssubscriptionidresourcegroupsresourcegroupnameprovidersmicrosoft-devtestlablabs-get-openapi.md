---
swagger: "2.0"
x-collection-name: Azure DevTest Labs
x-complete: 0
info:
  title: Azure DevTest Labs API Labs List By Resource Group
  description: List labs in a resource group.
  version: 1.0.0
host: management.azure.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /subscriptions/{subscriptionId}/providers/Microsoft.DevTestLab/labs:
    get:
      summary: Labs List By Subscription
      description: List labs in a subscription.
      operationId: Labs_ListBySubscription
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-devtestlablabs-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: query
        name: $filter
        description: The filter to apply to the operation
      - in: query
        name: $orderby
        description: The ordering expression for the results, using OData notation
      - in: query
        name: $top
        description: The maximum number of resources to return from the operation
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
  /subscriptions/{subscriptionId}/providers/Microsoft.DevTestLab/schedules:
    get:
      summary: Global Schedules List By Subscription
      description: List schedules in a subscription.
      operationId: GlobalSchedules_ListBySubscription
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoft-devtestlabschedules-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: query
        name: $filter
        description: The filter to apply to the operation
      - in: query
        name: $orderby
        description: The ordering expression for the results, using OData notation
      - in: query
        name: $top
        description: The maximum number of resources to return from the operation
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Global Schedules
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs:
    get:
      summary: Labs List By Resource Group
      description: List labs in a resource group.
      operationId: Labs_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabs-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: query
        name: $filter
        description: The filter to apply to the operation
      - in: query
        name: $orderby
        description: The ordering expression for the results, using OData notation
      - in: query
        name: $top
        description: The maximum number of resources to return from the operation
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
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
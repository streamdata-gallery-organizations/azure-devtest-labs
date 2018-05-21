---
swagger: "2.0"
x-collection-name: Azure DevTest Labs
x-complete: 0
info:
  title: Azure DevTest Labs API Custom Images Get
  description: Get custom image.
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
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftdevtestlablabs-get
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
      x-api-path-slug: subscriptionssubscriptionidprovidersmicrosoftdevtestlabschedules-get
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
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabs-get
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
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/artifactsources:
    get:
      summary: Artifact Sources List
      description: List artifact sources in a given lab.
      operationId: ArtifactSources_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsources-get
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
      - in: path
        name: labName
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifact Sources
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/artifactsources/{artifactSourceName}/armtemplates
  : get:
      summary: Arm Templates List
      description: List azure resource manager templates in a given artifact source.
      operationId: ArmTemplates_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesartifactsourcenamearmtemplates-get
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
      - in: path
        name: artifactSourceName
        description: The name of the artifact source
      - in: path
        name: labName
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ARM Templates
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/artifactsources/{artifactSourceName}/armtemplates/{name}
  : get:
      summary: Arm Templates Get
      description: Get azure resource manager template.
      operationId: ArmTemplates_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesartifactsourcenamearmtemplatesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: artifactSourceName
        description: The name of the artifact source
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the azure Resource Manager template
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - ARM Templates
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/artifactsources/{artifactSourceName}/artifacts
  : get:
      summary: Artifacts List
      description: List artifacts in a given artifact source.
      operationId: Artifacts_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesartifactsourcenameartifacts-get
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
      - in: path
        name: artifactSourceName
        description: The name of the artifact source
      - in: path
        name: labName
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifacts
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/artifactsources/{artifactSourceName}/artifacts/{name}
  : get:
      summary: Artifacts Get
      description: Get artifact.
      operationId: Artifacts_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesartifactsourcenameartifactsname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: artifactSourceName
        description: The name of the artifact source
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the artifact
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifacts
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/artifactsources/{artifactSourceName}/artifacts/{name}/generateArmTemplate
  : post:
      summary: Artifacts Generate Arm Template
      description: Generates an ARM template for the given artifact, uploads the required
        files to a storage account, and validates the generated artifact.
      operationId: Artifacts_GenerateArmTemplate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesartifactsourcenameartifactsnamegeneratearmtemplate-post
      parameters:
      - in: path
        name: artifactSourceName
        description: The name of the artifact source
      - in: body
        name: generateArmTemplateRequest
        description: Parameters for generating an ARM template for deploying artifacts
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the artifact
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifacts
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/artifactsources/{name}
  : get:
      summary: Artifact Sources Get
      description: Get artifact source.
      operationId: ArtifactSources_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the artifact source
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifact Sources
    put:
      summary: Artifact Sources Create Or Update
      description: Create or replace an existing artifact source.
      operationId: ArtifactSources_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesname-put
      parameters:
      - in: body
        name: artifactSource
        description: Properties of an artifact source
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the artifact source
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifact Sources
    delete:
      summary: Artifact Sources Delete
      description: Delete artifact source.
      operationId: ArtifactSources_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the artifact source
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifact Sources
    patch:
      summary: Artifact Sources Update
      description: Modify properties of artifact sources.
      operationId: ArtifactSources_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameartifactsourcesname-patch
      parameters:
      - in: body
        name: artifactSource
        description: Properties of an artifact source
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the artifact source
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Artifact Sources
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/costs/{name}:
    get:
      summary: Costs Get
      description: Get cost.
      operationId: Costs_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamecostsname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the cost
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Costs
    put:
      summary: Costs Create Or Update
      description: Create or replace an existing cost.
      operationId: Costs_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamecostsname-put
      parameters:
      - in: body
        name: labCost
        description: A cost item
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the cost
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Costs
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/customimages:
    get:
      summary: Custom Images List
      description: List custom images in a given lab.
      operationId: CustomImages_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamecustomimages-get
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
      - in: path
        name: labName
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Custom Images
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/customimages/{name}
  : get:
      summary: Custom Images Get
      description: Get custom image.
      operationId: CustomImages_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamecustomimagesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the custom image
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Custom Images
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
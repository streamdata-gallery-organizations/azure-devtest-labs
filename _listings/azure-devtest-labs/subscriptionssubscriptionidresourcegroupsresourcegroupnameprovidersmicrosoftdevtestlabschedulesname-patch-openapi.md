---
swagger: "2.0"
x-collection-name: Azure DevTest Labs
x-complete: 0
info:
  title: Azure DevTest Labs API Global Schedules Update
  description: Modify properties of schedules.
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
    put:
      summary: Custom Images Create Or Update
      description: Create or replace an existing custom image. This operation can
        take a while to complete.
      operationId: CustomImages_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamecustomimagesname-put
      parameters:
      - in: body
        name: customImage
        description: A custom image
        schema:
          $ref: '#/definitions/holder'
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
    delete:
      summary: Custom Images Delete
      description: Delete custom image. This operation can take a while to complete.
      operationId: CustomImages_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamecustomimagesname-delete
      parameters:
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
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/formulas:
    get:
      summary: Formulas List
      description: List formulas in a given lab.
      operationId: Formulas_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameformulas-get
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
      - Formulas
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/formulas/{name}:
    get:
      summary: Formulas Get
      description: Get formula.
      operationId: Formulas_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameformulasname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the formula
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Formulas
    put:
      summary: Formulas Create Or Update
      description: Create or replace an existing Formula. This operation can take
        a while to complete.
      operationId: Formulas_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameformulasname-put
      parameters:
      - in: body
        name: formula
        description: A formula for creating a VM, specifying an image base and other
          parameters
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the formula
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Formulas
    delete:
      summary: Formulas Delete
      description: Delete formula.
      operationId: Formulas_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameformulasname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the formula
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Formulas
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/galleryimages:
    get:
      summary: Gallery Images List
      description: List gallery images in a given lab.
      operationId: GalleryImages_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamegalleryimages-get
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
      - Gallery Images
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/notificationchannels
  : get:
      summary: Notification Channels List
      description: List notificationchannels in a given lab.
      operationId: NotificationChannels_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamenotificationchannels-get
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
      - Notification Channels
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/notificationchannels/{name}
  : get:
      summary: Notification Channels Get
      description: Get notificationchannel.
      operationId: NotificationChannels_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamenotificationchannelsname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the notificationChannel
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Notification Channels
    put:
      summary: Notification Channels Create Or Update
      description: Create or replace an existing notificationChannel.
      operationId: NotificationChannels_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamenotificationchannelsname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the notificationChannel
      - in: query
        name: No Name
      - in: body
        name: notificationChannel
        description: A notification
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Notification Channels
    delete:
      summary: Notification Channels Delete
      description: Delete notificationchannel.
      operationId: NotificationChannels_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamenotificationchannelsname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the notificationChannel
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Notification Channels
    patch:
      summary: Notification Channels Update
      description: Modify properties of notificationchannels.
      operationId: NotificationChannels_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamenotificationchannelsname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the notificationChannel
      - in: query
        name: No Name
      - in: body
        name: notificationChannel
        description: A notification
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Notification Channels
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/notificationchannels/{name}/notify
  : post:
      summary: Notification Channels Notify
      description: Send notification to provided channel.
      operationId: NotificationChannels_Notify
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamenotificationchannelsnamenotify-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the notificationChannel
      - in: query
        name: No Name
      - in: body
        name: notifyParameters
        description: Properties for generating a Notification
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Notification Channels
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/policysets/{name}/evaluatePolicies
  : post:
      summary: Policy Sets Evaluate Policies
      description: Evaluates lab policy.
      operationId: PolicySets_EvaluatePolicies
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamepolicysetsnameevaluatepolicies-post
      parameters:
      - in: body
        name: evaluatePoliciesRequest
        description: Request body for evaluating a policy set
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the policy set
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Policies
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/policysets/{policySetName}/policies
  : get:
      summary: Policies List
      description: List policies in a given policy set.
      operationId: Policies_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamepolicysetspolicysetnamepolicies-get
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
      - in: path
        name: policySetName
        description: The name of the policy set
      responses:
        200:
          description: OK
      tags:
      - Policies
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/policysets/{policySetName}/policies/{name}
  : get:
      summary: Policies Get
      description: Get policy.
      operationId: Policies_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamepolicysetspolicysetnamepoliciesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the policy
      - in: query
        name: No Name
      - in: path
        name: policySetName
        description: The name of the policy set
      responses:
        200:
          description: OK
      tags:
      - Policies
    put:
      summary: Policies Create Or Update
      description: Create or replace an existing policy.
      operationId: Policies_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamepolicysetspolicysetnamepoliciesname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the policy
      - in: query
        name: No Name
      - in: body
        name: policy
        description: A Policy
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policySetName
        description: The name of the policy set
      responses:
        200:
          description: OK
      tags:
      - Policies
    delete:
      summary: Policies Delete
      description: Delete policy.
      operationId: Policies_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamepolicysetspolicysetnamepoliciesname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the policy
      - in: query
        name: No Name
      - in: path
        name: policySetName
        description: The name of the policy set
      responses:
        200:
          description: OK
      tags:
      - Policies
    patch:
      summary: Policies Update
      description: Modify properties of policies.
      operationId: Policies_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamepolicysetspolicysetnamepoliciesname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the policy
      - in: query
        name: No Name
      - in: body
        name: policy
        description: A Policy
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: policySetName
        description: The name of the policy set
      responses:
        200:
          description: OK
      tags:
      - Policies
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/schedules:
    get:
      summary: Schedules List
      description: List schedules in a given lab.
      operationId: Schedules_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameschedules-get
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
      - Schedules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/schedules/{name}
  : get:
      summary: Schedules Get
      description: Get schedule.
      operationId: Schedules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameschedulesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Schedules
    put:
      summary: Schedules Create Or Update
      description: Create or replace an existing schedule.
      operationId: Schedules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameschedulesname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: body
        name: schedule
        description: A schedule
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Schedules
    delete:
      summary: Schedules Delete
      description: Delete schedule.
      operationId: Schedules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameschedulesname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Schedules
    patch:
      summary: Schedules Update
      description: Modify properties of schedules.
      operationId: Schedules_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameschedulesname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: body
        name: schedule
        description: A schedule
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Schedules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/schedules/{name}/execute
  : post:
      summary: Schedules Execute
      description: Execute a schedule. This operation can take a while to complete.
      operationId: Schedules_Execute
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameschedulesnameexecute-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Schedules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/schedules/{name}/listApplicable
  : post:
      summary: Schedules List Applicable
      description: Lists all applicable schedules
      operationId: Schedules_ListApplicable
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameschedulesnamelistapplicable-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Schedules
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/servicerunners:
    get:
      summary: Service Runners List
      description: List service runners in a given lab.
      operationId: ServiceRunners_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameservicerunners-get
      parameters:
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
      - Service Runners
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/servicerunners/{name}
  : get:
      summary: Service Runners Get
      description: Get service runner.
      operationId: ServiceRunners_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameservicerunnersname-get
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the service runner
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service Runners
    put:
      summary: Service Runners Create Or Update
      description: Create or replace an existing Service runner.
      operationId: ServiceRunners_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameservicerunnersname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the service runner
      - in: query
        name: No Name
      - in: body
        name: serviceRunner
        description: A container for a managed identity to execute DevTest lab services
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Service Runners
    delete:
      summary: Service Runners Delete
      description: Delete service runner.
      operationId: ServiceRunners_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameservicerunnersname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the service runner
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service Runners
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users:
    get:
      summary: Users List
      description: List user profiles in a given lab.
      operationId: Users_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusers-get
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
      - Users
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{name}:
    get:
      summary: Users Get
      description: Get user profile.
      operationId: Users_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the user profile
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
    put:
      summary: Users Create Or Update
      description: Create or replace an existing user profile.
      operationId: Users_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the user profile
      - in: query
        name: No Name
      - in: body
        name: user
        description: Profile of a lab user
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
    delete:
      summary: Users Delete
      description: Delete user profile. This operation can take a while to complete.
      operationId: Users_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the user profile
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Users
    patch:
      summary: Users Update
      description: Modify properties of user profiles.
      operationId: Users_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the user profile
      - in: query
        name: No Name
      - in: body
        name: user
        description: Profile of a lab user
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Users
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/disks
  : get:
      summary: Disks List
      description: List disks in a given user profile.
      operationId: Disks_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamedisks-get
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
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Disks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/disks/{name}
  : get:
      summary: Disks Get
      description: Get disk.
      operationId: Disks_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamedisksname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the disk
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Disks
    put:
      summary: Disks Create Or Update
      description: Create or replace an existing disk. This operation can take a while
        to complete.
      operationId: Disks_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamedisksname-put
      parameters:
      - in: body
        name: disk
        description: A Disk
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the disk
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Disks
    delete:
      summary: Disks Delete
      description: Delete disk. This operation can take a while to complete.
      operationId: Disks_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamedisksname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the disk
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Disks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/disks/{name}/attach
  : post:
      summary: Disks Attach
      description: Attach and create the lease of the disk to the virtual machine.
        This operation can take a while to complete.
      operationId: Disks_Attach
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamedisksnameattach-post
      parameters:
      - in: body
        name: attachDiskProperties
        description: Properties of the disk to attach
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the disk
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Disks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/disks/{name}/detach
  : post:
      summary: Disks Detach
      description: Detach and break the lease of the disk attached to the virtual
        machine. This operation can take a while to complete.
      operationId: Disks_Detach
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamedisksnamedetach-post
      parameters:
      - in: body
        name: detachDiskProperties
        description: Properties of the disk to detach
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the disk
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Disks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/environments
  : get:
      summary: Environments List
      description: List environments in a given user profile.
      operationId: Environments_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernameenvironments-get
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
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Environments
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/environments/{name}
  : get:
      summary: Environments Get
      description: Get environment.
      operationId: Environments_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernameenvironmentsname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the environment
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Environments
    put:
      summary: Environments Create Or Update
      description: Create or replace an existing environment. This operation can take
        a while to complete.
      operationId: Environments_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernameenvironmentsname-put
      parameters:
      - in: body
        name: dtlEnvironment
        description: An environment, which is essentially an ARM template deployment
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the environment
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Environments
    delete:
      summary: Environments Delete
      description: Delete environment. This operation can take a while to complete.
      operationId: Environments_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernameenvironmentsname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the environment
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Environments
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/secrets
  : get:
      summary: Secrets List
      description: List secrets in a given user profile.
      operationId: Secrets_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamesecrets-get
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
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Secrets
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/users/{userName}/secrets/{name}
  : get:
      summary: Secrets Get
      description: Get secret.
      operationId: Secrets_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamesecretsname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the secret
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Secrets
    put:
      summary: Secrets Create Or Update
      description: Create or replace an existing secret.
      operationId: Secrets_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamesecretsname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the secret
      - in: query
        name: No Name
      - in: body
        name: secret
        description: A secret
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Secrets
    delete:
      summary: Secrets Delete
      description: Delete secret.
      operationId: Secrets_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnameusersusernamesecretsname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the secret
      - in: query
        name: No Name
      - in: path
        name: userName
        description: The name of the user profile
      responses:
        200:
          description: OK
      tags:
      - Secrets
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines:
    get:
      summary: Virtual Machines List
      description: List virtual machines in a given lab.
      operationId: VirtualMachines_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachines-get
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
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}
  : get:
      summary: Virtual Machines Get
      description: Get virtual machine.
      operationId: VirtualMachines_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
    put:
      summary: Virtual Machines Create Or Update
      description: Create or replace an existing Virtual machine. This operation can
        take a while to complete.
      operationId: VirtualMachines_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: body
        name: labVirtualMachine
        description: A virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
    delete:
      summary: Virtual Machines Delete
      description: Delete virtual machine. This operation can take a while to complete.
      operationId: VirtualMachines_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
    patch:
      summary: Virtual Machines Update
      description: Modify properties of virtual machines.
      operationId: VirtualMachines_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: body
        name: labVirtualMachine
        description: A virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/addDataDisk
  : post:
      summary: Virtual Machines Add Data Disk
      description: Attach a new or existing data disk to virtual machine. This operation
        can take a while to complete.
      operationId: VirtualMachines_AddDataDisk
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesnameadddatadisk-post
      parameters:
      - in: body
        name: dataDiskProperties
        description: Request body for adding a new or existing data disk to a virtual
          machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/applyArtifacts
  : post:
      summary: Virtual Machines Apply Artifacts
      description: Apply artifacts to virtual machine. This operation can take a while
        to complete.
      operationId: VirtualMachines_ApplyArtifacts
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesnameapplyartifacts-post
      parameters:
      - in: body
        name: applyArtifactsRequest
        description: Request body for applying artifacts to a virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/claim
  : post:
      summary: Virtual Machines Claim
      description: Take ownership of an existing virtual machine This operation can
        take a while to complete.
      operationId: VirtualMachines_Claim
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesnameclaim-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/detachDataDisk
  : post:
      summary: Virtual Machines Detach Data Disk
      description: Detach the specified disk from the virtual machine. This operation
        can take a while to complete.
      operationId: VirtualMachines_DetachDataDisk
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesnamedetachdatadisk-post
      parameters:
      - in: body
        name: detachDataDiskProperties
        description: Request body for detaching data disk from a virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/listApplicableSchedules
  : post:
      summary: Virtual Machines List Applicable Schedules
      description: Lists all applicable schedules
      operationId: VirtualMachines_ListApplicableSchedules
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesnamelistapplicableschedules-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/start
  : post:
      summary: Virtual Machines Start
      description: Start a virtual machine. This operation can take a while to complete.
      operationId: VirtualMachines_Start
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesnamestart-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{name}/stop
  : post:
      summary: Virtual Machines Stop
      description: Stop a virtual machine This operation can take a while to complete.
      operationId: VirtualMachines_Stop
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesnamestop-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual machine
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Machines
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{virtualMachineName}/schedules
  : get:
      summary: Virtual Machine Schedules List
      description: List schedules in a given virtual machine.
      operationId: VirtualMachineSchedules_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesvirtualmachinenameschedules-get
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
      - in: path
        name: virtualMachineName
        description: The name of the virtual machine
      responses:
        200:
          description: OK
      tags:
      - Virtual Machine Schedules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{virtualMachineName}/schedules/{name}
  : get:
      summary: Virtual Machine Schedules Get
      description: Get schedule.
      operationId: VirtualMachineSchedules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: path
        name: virtualMachineName
        description: The name of the virtual machine
      responses:
        200:
          description: OK
      tags:
      - Virtual Machine Schedules
    put:
      summary: Virtual Machine Schedules Create Or Update
      description: Create or replace an existing schedule.
      operationId: VirtualMachineSchedules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: body
        name: schedule
        description: A schedule
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: virtualMachineName
        description: The name of the virtual machine
      responses:
        200:
          description: OK
      tags:
      - Virtual Machine Schedules
    delete:
      summary: Virtual Machine Schedules Delete
      description: Delete schedule.
      operationId: VirtualMachineSchedules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: path
        name: virtualMachineName
        description: The name of the virtual machine
      responses:
        200:
          description: OK
      tags:
      - Virtual Machine Schedules
    patch:
      summary: Virtual Machine Schedules Update
      description: Modify properties of schedules.
      operationId: VirtualMachineSchedules_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: body
        name: schedule
        description: A schedule
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: virtualMachineName
        description: The name of the virtual machine
      responses:
        200:
          description: OK
      tags:
      - Virtual Machine Schedules
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualmachines/{virtualMachineName}/schedules/{name}/execute
  : post:
      summary: Virtual Machine Schedules Execute
      description: Execute a schedule. This operation can take a while to complete.
      operationId: VirtualMachineSchedules_Execute
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesnameexecute-post
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: path
        name: virtualMachineName
        description: The name of the virtual machine
      responses:
        200:
          description: OK
      tags:
      - Virtual Machine Schedules Execute
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualnetworks:
    get:
      summary: Virtual Networks List
      description: List virtual networks in a given lab.
      operationId: VirtualNetworks_List
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualnetworks-get
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
      - Virtual Networks
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{labName}/virtualnetworks/{name}
  : get:
      summary: Virtual Networks Get
      description: Get virtual network.
      operationId: VirtualNetworks_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualnetworksname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual network
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
    put:
      summary: Virtual Networks Create Or Update
      description: Create or replace an existing virtual network. This operation can
        take a while to complete.
      operationId: VirtualNetworks_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualnetworksname-put
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual network
      - in: query
        name: No Name
      - in: body
        name: virtualNetwork
        description: A virtual network
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
    delete:
      summary: Virtual Networks Delete
      description: Delete virtual network. This operation can take a while to complete.
      operationId: VirtualNetworks_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualnetworksname-delete
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual network
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
    patch:
      summary: Virtual Networks Update
      description: Modify properties of virtual networks.
      operationId: VirtualNetworks_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabslabnamevirtualnetworksname-patch
      parameters:
      - in: path
        name: labName
        description: The name of the lab
      - in: path
        name: name
        description: The name of the virtual network
      - in: query
        name: No Name
      - in: body
        name: virtualNetwork
        description: A virtual network
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Virtual Networks
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{name}:
    get:
      summary: Labs Get
      description: Get lab.
      operationId: Labs_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
    put:
      summary: Labs Create Or Update
      description: Create or replace an existing lab. This operation can take a while
        to complete.
      operationId: Labs_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsname-put
      parameters:
      - in: body
        name: lab
        description: A lab
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
    delete:
      summary: Labs Delete
      description: Delete lab. This operation can take a while to complete.
      operationId: Labs_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsname-delete
      parameters:
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
    patch:
      summary: Labs Update
      description: Modify properties of labs.
      operationId: Labs_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsname-patch
      parameters:
      - in: body
        name: lab
        description: A lab
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{name}/claimAnyVm:
    post:
      summary: Labs Claim Any Vm
      description: Claim a random claimable virtual machine in the lab. This operation
        can take a while to complete.
      operationId: Labs_ClaimAnyVm
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsnameclaimanyvm-post
      parameters:
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{name}/createEnvironment:
    post:
      summary: Labs Create Environment
      description: Create virtual machines in a lab. This operation can take a while
        to complete.
      operationId: Labs_CreateEnvironment
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsnamecreateenvironment-post
      parameters:
      - in: body
        name: labVirtualMachineCreationParameter
        description: Properties for creating a virtual machine
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs Environment
  ? /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{name}/exportResourceUsage
  : post:
      summary: Labs Export Resource Usage
      description: Exports the lab resource usage into a storage account This operation
        can take a while to complete.
      operationId: Labs_ExportResourceUsage
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsnameexportresourceusage-post
      parameters:
      - in: body
        name: exportResourceUsageParameters
        description: The parameters of the export operation
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs Export
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{name}/generateUploadUri:
    post:
      summary: Labs Generate Upload Uri
      description: Generate a URI for uploading custom disk images to a Lab.
      operationId: Labs_GenerateUploadUri
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsnamegenerateuploaduri-post
      parameters:
      - in: body
        name: generateUploadUriParameter
        description: Properties for generating an upload URI
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/labs/{name}/listVhds:
    post:
      summary: Labs List Vhds
      description: List disk images available for custom image creation.
      operationId: Labs_ListVhds
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlablabsnamelistvhds-post
      parameters:
      - in: path
        name: name
        description: The name of the lab
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Labs Vhds
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/schedules:
    get:
      summary: Global Schedules List By Resource Group
      description: List schedules in a resource group.
      operationId: GlobalSchedules_ListByResourceGroup
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlabschedules-get
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
  /subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.DevTestLab/schedules/{name}:
    get:
      summary: Global Schedules Get
      description: Get schedule.
      operationId: GlobalSchedules_Get
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlabschedulesname-get
      parameters:
      - in: query
        name: $expand
        description: Specify the $expand query
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Global Schedules
    put:
      summary: Global Schedules Create Or Update
      description: Create or replace an existing schedule.
      operationId: GlobalSchedules_CreateOrUpdate
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlabschedulesname-put
      parameters:
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: body
        name: schedule
        description: A schedule
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global Schedules
    delete:
      summary: Global Schedules Delete
      description: Delete schedule.
      operationId: GlobalSchedules_Delete
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlabschedulesname-delete
      parameters:
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Global Schedules
    patch:
      summary: Global Schedules Update
      description: Modify properties of schedules.
      operationId: GlobalSchedules_Update
      x-api-path-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoftdevtestlabschedulesname-patch
      parameters:
      - in: path
        name: name
        description: The name of the schedule
      - in: query
        name: No Name
      - in: body
        name: schedule
        description: A schedule
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Global Schedules
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
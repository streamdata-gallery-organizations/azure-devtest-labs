---
swagger: "2.0"
x-collection-name: Azure DevTest Labs
x-complete: 0
info:
  title: Azure DevTest Labs API Disks Get
  description: Get disk.
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
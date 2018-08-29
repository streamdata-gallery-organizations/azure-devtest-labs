---
name: Azure DevTest Labs
x-slug: azure-devtest-labs
description: Azure DevTest Labs makes it easy to quickly create environments to deploy
  and test applications. Use reusable templates and artifacts to build Windows and
  Linux environments while minimalizing waste and controlling costs.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure DevTest Labs
created: "2018-08-29"
modified: "2018-08-29"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/apis.md
specificationVersion: "0.14"
apis:
- name: DevTestLabsClient - Labs List By Subscription
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-devtestlablabs-get
  description: List labs in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidprovidersmicrosoft-devtestlablabs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidprovidersmicrosoft-devtestlablabs-get-openapi.md
- name: DevTestLabsClient - Global Schedules List By Subscription
  x-api-slug: subscriptionssubscriptionidprovidersmicrosoft-devtestlabschedules-get
  description: List schedules in a subscription.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidprovidersmicrosoft-devtestlabschedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidprovidersmicrosoft-devtestlabschedules-get-openapi.md
- name: DevTestLabsClient - Labs List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabs-get
  description: List labs in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabs-get-openapi.md
- name: DevTestLabsClient - Artifact Sources List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsources-get
  description: List artifact sources in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsources-get-openapi.md
- name: DevTestLabsClient - Arm Templates List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenamearmtemplates-get
  description: List azure resource manager templates in a given artifact source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenamearmtemplates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenamearmtemplates-get-openapi.md
- name: DevTestLabsClient - Arm Templates Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenamearmtemplatesname-get
  description: Get azure resource manager template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenamearmtemplatesname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenamearmtemplatesname-get-openapi.md
- name: DevTestLabsClient - Artifacts List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifacts-get
  description: List artifacts in a given artifact source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifacts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifacts-get-openapi.md
- name: DevTestLabsClient - Artifacts Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifactsname-get
  description: Get artifact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifactsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifactsname-get-openapi.md
- name: DevTestLabsClient - Artifacts Generate Arm Template
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifactsnamegeneratearmtemplate-post
  description: Generates an ARM template for the given artifact, uploads the required
    files to a storage account, and validates the generated artifact.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesartifactsourcenameartifactsnamegeneratearmtemplate-post-openapi.md
- name: DevTestLabsClient - Artifact Sources Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-get
  description: Get artifact source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-get-openapi.md
- name: DevTestLabsClient - Artifact Sources Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-put
  description: Create or replace an existing artifact source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-put-openapi.md
- name: DevTestLabsClient - Artifact Sources Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-delete
  description: Delete artifact source.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-delete-openapi.md
- name: DevTestLabsClient - Artifact Sources Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-patch
  description: Modify properties of artifact sources.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameartifactsourcesname-patch-openapi.md
- name: DevTestLabsClient - Costs Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecostsname-get
  description: Get cost.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecostsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecostsname-get-openapi.md
- name: DevTestLabsClient - Costs Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecostsname-put
  description: Create or replace an existing cost.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecostsname-put-openapi.md
- name: DevTestLabsClient - Custom Images List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimages-get
  description: List custom images in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimages-get-openapi.md
- name: DevTestLabsClient - Custom Images Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-get
  description: Get custom image.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-get-openapi.md
- name: DevTestLabsClient - Custom Images Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-put
  description: Create or replace an existing custom image. This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-put-openapi.md
- name: DevTestLabsClient - Custom Images Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-delete
  description: Delete custom image. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamecustomimagesname-delete-openapi.md
- name: DevTestLabsClient - Formulas List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulas-get
  description: List formulas in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulas-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulas-get-openapi.md
- name: DevTestLabsClient - Formulas Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-get
  description: Get formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-get-openapi.md
- name: DevTestLabsClient - Formulas Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-put
  description: Create or replace an existing Formula. This operation can take a while
    to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-put-openapi.md
- name: DevTestLabsClient - Formulas Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-delete
  description: Delete formula.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameformulasname-delete-openapi.md
- name: DevTestLabsClient - Gallery Images List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamegalleryimages-get
  description: List gallery images in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamegalleryimages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamegalleryimages-get-openapi.md
- name: DevTestLabsClient - Notification Channels List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannels-get
  description: List notificationchannels in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannels-get-openapi.md
- name: DevTestLabsClient - Notification Channels Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-get
  description: Get notificationchannel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-get-openapi.md
- name: DevTestLabsClient - Notification Channels Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-put
  description: Create or replace an existing notificationChannel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-put-openapi.md
- name: DevTestLabsClient - Notification Channels Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-delete
  description: Delete notificationchannel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-delete-openapi.md
- name: DevTestLabsClient - Notification Channels Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-patch
  description: Modify properties of notificationchannels.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsname-patch-openapi.md
- name: DevTestLabsClient - Notification Channels Notify
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsnamenotify-post
  description: Send notification to provided channel.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamenotificationchannelsnamenotify-post-openapi.md
- name: DevTestLabsClient - Policy Sets Evaluate Policies
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetsnameevaluatepolicies-post
  description: Evaluates lab policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetsnameevaluatepolicies-post-openapi.md
- name: DevTestLabsClient - Policies List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepolicies-get
  description: List policies in a given policy set.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepolicies-get-openapi.md
- name: DevTestLabsClient - Policies Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-get
  description: Get policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-get-openapi.md
- name: DevTestLabsClient - Policies Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-put
  description: Create or replace an existing policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-put-openapi.md
- name: DevTestLabsClient - Policies Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-delete
  description: Delete policy.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-delete-openapi.md
- name: DevTestLabsClient - Policies Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-patch
  description: Modify properties of policies.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamepolicysetspolicysetnamepoliciesname-patch-openapi.md
- name: DevTestLabsClient - Schedules List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedules-get
  description: List schedules in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedules-get-openapi.md
- name: DevTestLabsClient - Schedules Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-get
  description: Get schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-get-openapi.md
- name: DevTestLabsClient - Schedules Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-put
  description: Create or replace an existing schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-put-openapi.md
- name: DevTestLabsClient - Schedules Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-delete
  description: Delete schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-delete-openapi.md
- name: DevTestLabsClient - Schedules Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-patch
  description: Modify properties of schedules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesname-patch-openapi.md
- name: DevTestLabsClient - Schedules Execute
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesnameexecute-post
  description: Execute a schedule. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesnameexecute-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesnameexecute-post-openapi.md
- name: DevTestLabsClient - Schedules List Applicable
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesnamelistapplicable-post
  description: Lists all applicable schedules
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesnamelistapplicable-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameschedulesnamelistapplicable-post-openapi.md
- name: DevTestLabsClient - Service Runners List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunners-get
  description: List service runners in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunners-get-openapi.md
- name: DevTestLabsClient - Service Runners Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunnersname-get
  description: Get service runner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunnersname-get-openapi.md
- name: DevTestLabsClient - Service Runners Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunnersname-put
  description: Create or replace an existing Service runner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunnersname-put-openapi.md
- name: DevTestLabsClient - Service Runners Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunnersname-delete
  description: Delete service runner.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameservicerunnersname-delete-openapi.md
- name: DevTestLabsClient - Users List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusers-get
  description: List user profiles in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusers-get-openapi.md
- name: DevTestLabsClient - Users Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-get
  description: Get user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-get-openapi.md
- name: DevTestLabsClient - Users Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-put
  description: Create or replace an existing user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-put-openapi.md
- name: DevTestLabsClient - Users Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-delete
  description: Delete user profile. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-delete-openapi.md
- name: DevTestLabsClient - Users Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-patch
  description: Modify properties of user profiles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersname-patch-openapi.md
- name: DevTestLabsClient - Disks List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisks-get
  description: List disks in a given user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisks-get-openapi.md
- name: DevTestLabsClient - Disks Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-get
  description: Get disk.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-get-openapi.md
- name: DevTestLabsClient - Disks Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-put
  description: Create or replace an existing disk. This operation can take a while
    to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-put-openapi.md
- name: DevTestLabsClient - Disks Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-delete
  description: Delete disk. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksname-delete-openapi.md
- name: DevTestLabsClient - Disks Attach
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksnameattach-post
  description: Attach and create the lease of the disk to the virtual machine. This
    operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksnameattach-post-openapi.md
- name: DevTestLabsClient - Disks Detach
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksnamedetach-post
  description: Detach and break the lease of the disk attached to the virtual machine.
    This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamedisksnamedetach-post-openapi.md
- name: DevTestLabsClient - Environments List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironments-get
  description: List environments in a given user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironments-get-openapi.md
- name: DevTestLabsClient - Environments Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-get
  description: Get environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-get-openapi.md
- name: DevTestLabsClient - Environments Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-put
  description: Create or replace an existing environment. This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-put-openapi.md
- name: DevTestLabsClient - Environments Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-delete
  description: Delete environment. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernameenvironmentsname-delete-openapi.md
- name: DevTestLabsClient - Secrets List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecrets-get
  description: List secrets in a given user profile.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecrets-get-openapi.md
- name: DevTestLabsClient - Secrets Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecretsname-get
  description: Get secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecretsname-get-openapi.md
- name: DevTestLabsClient - Secrets Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecretsname-put
  description: Create or replace an existing secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecretsname-put-openapi.md
- name: DevTestLabsClient - Secrets Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecretsname-delete
  description: Delete secret.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnameusersusernamesecretsname-delete-openapi.md
- name: DevTestLabsClient - Virtual Machines List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachines-get
  description: List virtual machines in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachines-get-openapi.md
- name: DevTestLabsClient - Virtual Machines Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-get
  description: Get virtual machine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-get-openapi.md
- name: DevTestLabsClient - Virtual Machines Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-put
  description: Create or replace an existing Virtual machine. This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-put-openapi.md
- name: DevTestLabsClient - Virtual Machines Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-delete
  description: Delete virtual machine. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-delete-openapi.md
- name: DevTestLabsClient - Virtual Machines Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-patch
  description: Modify properties of virtual machines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesname-patch-openapi.md
- name: DevTestLabsClient - Virtual Machines Add Data Disk
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameadddatadisk-post
  description: Attach a new or existing data disk to virtual machine. This operation
    can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameadddatadisk-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Apply Artifacts
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameapplyartifacts-post
  description: Apply artifacts to virtual machine. This operation can take a while
    to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameapplyartifacts-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Claim
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameclaim-post
  description: Take ownership of an existing virtual machine This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnameclaim-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Detach Data Disk
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamedetachdatadisk-post
  description: Detach the specified disk from the virtual machine. This operation
    can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamedetachdatadisk-post-openapi.md
- name: DevTestLabsClient - Virtual Machines List Applicable Schedules
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamelistapplicableschedules-post
  description: Lists all applicable schedules
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamelistapplicableschedules-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Start
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestart-post
  description: Start a virtual machine. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestart-post-openapi.md
- name: DevTestLabsClient - Virtual Machines Stop
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestop-post
  description: Stop a virtual machine This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesnamestop-post-openapi.md
- name: DevTestLabsClient - Virtual Machine Schedules List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedules-get
  description: List schedules in a given virtual machine.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedules-get-openapi.md
- name: DevTestLabsClient - Virtual Machine Schedules Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-get
  description: Get schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-get-openapi.md
- name: DevTestLabsClient - Virtual Machine Schedules Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-put
  description: Create or replace an existing schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-put-openapi.md
- name: DevTestLabsClient - Virtual Machine Schedules Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-delete
  description: Delete schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-delete-openapi.md
- name: DevTestLabsClient - Virtual Machine Schedules Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-patch
  description: Modify properties of schedules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesname-patch-openapi.md
- name: DevTestLabsClient - Virtual Machine Schedules Execute
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesnameexecute-post
  description: Execute a schedule. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesnameexecute-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualmachinesvirtualmachinenameschedulesnameexecute-post-openapi.md
- name: DevTestLabsClient - Virtual Networks List
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworks-get
  description: List virtual networks in a given lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworks-get-openapi.md
- name: DevTestLabsClient - Virtual Networks Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-get
  description: Get virtual network.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-get-openapi.md
- name: DevTestLabsClient - Virtual Networks Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-put
  description: Create or replace an existing virtual network. This operation can take
    a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-put-openapi.md
- name: DevTestLabsClient - Virtual Networks Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-delete
  description: Delete virtual network. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-delete-openapi.md
- name: DevTestLabsClient - Virtual Networks Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-patch
  description: Modify properties of virtual networks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabslabnamevirtualnetworksname-patch-openapi.md
- name: DevTestLabsClient - Labs Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-get
  description: Get lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-get-openapi.md
- name: DevTestLabsClient - Labs Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-put
  description: Create or replace an existing lab. This operation can take a while
    to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-put-openapi.md
- name: DevTestLabsClient - Labs Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-delete
  description: Delete lab. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-delete-openapi.md
- name: DevTestLabsClient - Labs Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-patch
  description: Modify properties of labs.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsname-patch-openapi.md
- name: DevTestLabsClient - Labs Claim Any Vm
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnameclaimanyvm-post
  description: Claim a random claimable virtual machine in the lab. This operation
    can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnameclaimanyvm-post-openapi.md
- name: DevTestLabsClient - Labs Create Environment
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnamecreateenvironment-post
  description: Create virtual machines in a lab. This operation can take a while to
    complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnamecreateenvironment-post-openapi.md
- name: DevTestLabsClient - Labs Export Resource Usage
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnameexportresourceusage-post
  description: Exports the lab resource usage into a storage account This operation
    can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnameexportresourceusage-post-openapi.md
- name: DevTestLabsClient - Labs Generate Upload Uri
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnamegenerateuploaduri-post
  description: Generate a URI for uploading custom disk images to a Lab.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnamegenerateuploaduri-post-openapi.md
- name: DevTestLabsClient - Labs List Vhds
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnamelistvhds-post
  description: List disk images available for custom image creation.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlablabsnamelistvhds-post-openapi.md
- name: DevTestLabsClient - Global Schedules List By Resource Group
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedules-get
  description: List schedules in a resource group.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedules-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedules-get-openapi.md
- name: DevTestLabsClient - Global Schedules Get
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-get
  description: Get schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-get-openapi.md
- name: DevTestLabsClient - Global Schedules Create Or Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-put
  description: Create or replace an existing schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-put-openapi.md
- name: DevTestLabsClient - Global Schedules Delete
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-delete
  description: Delete schedule.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-delete-openapi.md
- name: DevTestLabsClient - Global Schedules Update
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-patch
  description: Modify properties of schedules.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesname-patch-openapi.md
- name: DevTestLabsClient - Global Schedules Execute
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesnameexecute-post
  description: Execute a schedule. This operation can take a while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesnameexecute-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesnameexecute-post-openapi.md
- name: DevTestLabsClient - Global Schedules Retarget
  x-api-slug: subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesnameretarget-post
  description: Updates a schedule's target resource Id. This operation can take a
    while to complete.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-devtest-integrate.png
  humanURL: https://azure.microsoft.com/en-us/services/devtest-lab/
  baseURL: ://management.azure.com//
  tags: Testing, Microsoft, Orchestration, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-devtest-labs/master/_listings/azure-devtest-labs/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-devtestlabschedulesnameretarget-post-openapi.md
x-common:
- type: x-api-gallery
  url: http://azure.data.lake.store.api.gallery.streamdata.io
- type: x-api-stack
  url: http://azure.devtest.labs.stack.network
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/devtest-lab/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/devtest-lab/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/devtest-lab/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/devtest-lab/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
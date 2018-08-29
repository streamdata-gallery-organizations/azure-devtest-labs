{
  "info": {
    "name": "Azure DevTest Labs API Formulas Delete",
    "_postman_id": "73564d6b-7837-47e8-993d-1642d907a1f0",
    "description": "Delete formula.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "formulas",
      "item": [
        {
          "id": "b5a2466f-0d31-46ae-971c-ee1f947676b3",
          "name": "Formulas_Delete",
          "request": {
            "url": {
              "protocol": "http",
              "host": "management.azure.com",
              "path": [
                "subscriptions/:subscriptionId/resourceGroups/:resourceGroupName/providers/Microsoft.DevTestLab/labs/:labName/formulas/:name"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "labName",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "name",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "subscriptionId",
                  "value": "subscriptionId",
                  "type": "string"
                },
                {
                  "id": "resourceGroupName",
                  "value": "resourceGroupName",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "body": {
              "mode": "raw"
            },
            "description": "Delete formula"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1d773be-1732-4024-b5e2-34212f97dc33"
            }
          ]
        }
      ]
    }
  ]
}
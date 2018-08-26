{
  "info": {
    "name": "Plentymarkets Update a manufacturer",
    "_postman_id": "37b6b3c3-f37e-4a51-82ab-5b1beb7706d0",
    "description": "Updates a manufacturer. The ID of the manufacturer must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "74ef768d-8fba-4abc-9886-08e681f863c0",
          "name": "getRestItemsManufacturers",
          "request": {
            "url": "http://example.com/rest/items/manufacturers?name=%7B%7D&updatedAt=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Lists all manufacturers in the system.\n\nDisplay a listing of the resource."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cf37fe83-03fd-40d8-962a-6e94b19e3710"
            }
          ]
        }
      ]
    },
    {
      "name": "Manufacturer",
      "item": [
        {
          "id": "47ecf5c6-8b65-472b-9616-706ea4f95f89",
          "name": "postRestItemsManufacturers",
          "request": {
            "url": "http://example.com/rest/items/manufacturers",
            "method": "POST",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Creates a manufacturer."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "309b0248-7f87-43e5-bbaf-0036a4c228ae"
            }
          ]
        },
        {
          "id": "103b9c1f-6c70-4213-a6ae-687dac4d82ad",
          "name": "getRestItemsManufacturers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/manufacturers/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Gets a manufacturer. The ID of the manufacturer must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "de37ccf8-889f-4c47-9d92-78793695b3d1"
            }
          ]
        },
        {
          "id": "e6162828-ad8d-430e-a55b-5e4232249c7e",
          "name": "putRestItemsManufacturers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/manufacturers/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "PUT",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Updates a manufacturer. The ID of the manufacturer must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87c77c51-6230-40a2-a01d-a5f41db70250"
            }
          ]
        },
        {
          "id": "2679cb10-c8fa-48ee-a635-1b329c753a9b",
          "name": "deleteRestItemsManufacturers",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                "rest/items/manufacturers/:id"
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "DELETE",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Deletes a manufacturer. The ID of the manufacturer must be specified."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86949ad7-0adf-4ae6-83a1-41cf0ebd956f"
            }
          ]
        }
      ]
    }
  ]
}
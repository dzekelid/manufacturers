{
  "info": {
    "name": "Plentymarkets Get a manufacturer",
    "_postman_id": "5e785e3c-41bb-4abd-a839-b50591b34732",
    "description": "Gets a manufacturer. The ID of the manufacturer must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "67507f68-2c38-40c4-85b1-83e7645811de",
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
              "id": "d71c095b-58f5-4b15-bd0d-30110a744737"
            }
          ]
        }
      ]
    },
    {
      "name": "Manufacturer",
      "item": [
        {
          "id": "dc18f01f-2a4a-49e2-b656-4a746b8ece03",
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
              "id": "df319906-f05d-41db-98c3-b2f2394df6f2"
            }
          ]
        },
        {
          "id": "d935277a-5d58-4a28-abcf-04a3750eac79",
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
              "id": "71d18503-6a65-4678-b4d9-c558de3d1a24"
            }
          ]
        },
        {
          "id": "33cc75f6-2012-41c9-9009-7bf9294f25c1",
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
              "id": "a67e92fc-39f3-4a43-b276-43ae49bf4229"
            }
          ]
        },
        {
          "id": "95ffc09f-0ed4-411c-a1d2-51b4ad90cf16",
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
              "id": "c0620c42-9e57-4e63-81ba-f531833f02a6"
            }
          ]
        }
      ]
    }
  ]
}
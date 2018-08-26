{
  "info": {
    "name": "Plentymarkets Delete a manufacturer",
    "_postman_id": "a9bb5264-3498-40a2-b710-fdd0c3efd8ea",
    "description": "Deletes a manufacturer. The ID of the manufacturer must be specified.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "6f14498d-8b9b-40a9-9649-051466db822f",
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
              "id": "970bb409-45a5-428b-8462-7df678620a3a"
            }
          ]
        }
      ]
    },
    {
      "name": "Manufacturer",
      "item": [
        {
          "id": "5d6d9768-5394-4ded-99fa-bfadce09c996",
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
              "id": "5e5b7102-8949-4c65-a904-07b4720d32ea"
            }
          ]
        },
        {
          "id": "8e86e490-b54a-48e3-975e-df94d4501fb3",
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
              "id": "f3070318-4b45-4a28-b950-c794aef41e34"
            }
          ]
        },
        {
          "id": "97812c7d-4f80-49d6-a3da-a6f82c4c437d",
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
              "id": "d175ea01-940c-440f-b432-62b706aaafba"
            }
          ]
        },
        {
          "id": "259619d6-a4d8-4a2c-be17-d629c31db94f",
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
              "id": "4d1c6d68-0770-4201-bb94-a66b1298a18e"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Plentymarkets Create a manufacturer",
    "_postman_id": "fcbf502a-ea9c-48f6-a491-14db3e064b05",
    "description": "Creates a manufacturer.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "2398e954-2572-486d-bb78-2cba0084d342",
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
              "id": "a6f2c9b6-c4c4-4030-b5a3-5780f4760259"
            }
          ]
        }
      ]
    },
    {
      "name": "Manufacturer",
      "item": [
        {
          "id": "aa54691d-677e-45a8-8d92-3f5eb62378f6",
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
              "id": "c88cc2ab-e989-4e3d-9681-a78d922abba6"
            }
          ]
        },
        {
          "id": "76befc44-7ba2-4259-b433-f1bc9c9472b7",
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
              "id": "d44bd814-95dc-41ef-9c70-76b7177a83ec"
            }
          ]
        },
        {
          "id": "0e9d41d1-0439-425f-a11c-77cc1b679620",
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
              "id": "04c2d80d-9025-4bd3-a724-7333e3136b46"
            }
          ]
        },
        {
          "id": "a341dcb0-3886-4701-b2f3-4e65fe48a7eb",
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
              "id": "e6619216-0251-4cc1-b967-fcf4a86d90f3"
            }
          ]
        }
      ]
    }
  ]
}
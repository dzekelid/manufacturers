{
  "info": {
    "name": "Plentymarkets List manufacturers",
    "_postman_id": "a1786bb0-6224-405b-a063-3ffcd44a8f49",
    "description": "Lists all manufacturers in the system.\n\nDisplay a listing of the resource.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "List",
      "item": [
        {
          "id": "1b3d03e1-1dca-4756-90b2-cc2fd34c6551",
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
              "id": "5f7f35e8-262b-483c-9fd5-0b9b9a48dc22"
            }
          ]
        }
      ]
    }
  ]
}
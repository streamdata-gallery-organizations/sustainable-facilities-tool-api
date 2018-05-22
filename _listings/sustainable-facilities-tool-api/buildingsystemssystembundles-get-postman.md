{
  "info": {
    "name": "Sustainable Facilities Tool API Building System Bundles",
    "_postman_id": "c2a6e41d-ae55-496e-af21-d58538af96c5",
    "description": "Returns all building system bundles.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "bundles",
      "item": [
        {
          "id": "5cd211f8-c057-4fb5-805c-b9665c9c768a",
          "name": "returnsBuildingSystemBundles",
          "request": {
            "url": "http://api.data.gov/sftool/v1/building-systems/system-bundles",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all building system bundles"
          },
          "response": [
            {
              "header": [
                {
                  "key": "Content-Type",
                  "value": "application/json",
                  "disabled": false
                }
              ],
              "body": "[\r\n  {\r\n    \"id\": 205,\r\n    \"name\": \"name\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "a9189749-b435-4d73-9b6c-41efb997b068"
            }
          ]
        }
      ]
    }
  ]
}
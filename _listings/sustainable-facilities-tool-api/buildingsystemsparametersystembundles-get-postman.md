{
  "info": {
    "name": "Sustainable Facilities Tool API Building System Bundle",
    "_postman_id": "40ff7377-bbf7-4471-920c-d1c108a8264f",
    "description": "Returns a building system bundle by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "bundles",
      "item": [
        {
          "id": "60625784-ed9c-451c-a5f0-ab809499a704",
          "name": "returnsBuildingSystemBundle",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "building-systems/:parameter/system-bundles"
              ],
              "variable": [
                {
                  "id": "parameter",
                  "value": "parameter",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a building system bundle by parameter"
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
              "body": "[\r\n  {\r\n    \"id\": 7,\r\n    \"name\": \"name\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "7025fb9e-df22-42d8-9d20-2a6f3f6bdf50"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Sustainable Facilities Tool API Building System Case Study",
    "_postman_id": "123d0205-0a19-417d-8bbf-705163ad8dd4",
    "description": "Returns a building system case study by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "case studies",
      "item": [
        {
          "id": "c84ed2d0-c1ce-4cf7-87b1-6d41fffd05b9",
          "name": "returnBuildingSystemCaseStudies",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "building-systems/:parameter/case-studies"
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
            "description": "Returns a building system case study by parameter"
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
              "body": "[\r\n  {\r\n    \"id\": 98,\r\n    \"name\": \"name\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "9bd7912e-68df-4b69-bc89-b769986c8510"
            }
          ]
        }
      ]
    }
  ]
}
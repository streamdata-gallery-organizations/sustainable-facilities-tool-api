{
  "info": {
    "name": "Sustainable Facilities Tool API Building System Case Studies",
    "_postman_id": "1f14d9cb-bcfc-4eaf-ac32-2ace0c85e226",
    "description": "Returns all building systems case studies",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "case studies",
      "item": [
        {
          "id": "fd10fc88-2de3-4287-b6d9-9b40512f8d8d",
          "name": "returnBuildingSystemCaseStudies",
          "request": {
            "url": "http://api.data.gov/sftool/v1/building-systems/case-studies",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all building systems case studies"
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
              "body": "[\r\n  {\r\n    \"id\": 147,\r\n    \"name\": \"name\"\r\n  }\r\n]",
              "status": "Successful response",
              "code": 200,
              "name": "Response_200",
              "id": "991e8c82-8d1b-44d0-abcb-26d6a0e1781a"
            }
          ]
        }
      ]
    }
  ]
}
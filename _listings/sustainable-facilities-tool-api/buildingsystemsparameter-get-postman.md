{
  "info": {
    "name": "Sustainable Facilities Tool API Returns a building system by parameter.",
    "_postman_id": "4403867a-a5cb-4b08-9879-da7a22d583fe",
    "description": "Returns a building system by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "3a28f68b-49c2-4c1e-91f8-e5d56abb7fb2",
          "name": "returnBuildingSystems",
          "request": {
            "url": "http://api.data.gov/sftool/v1/building-systems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all building systems."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1a79903-64f3-47b9-958e-f466860db372"
            }
          ]
        },
        {
          "id": "ad18afff-464a-4201-85d1-941165900888",
          "name": "returnBuildingSystem",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "building-systems/:parameter"
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
            "description": "Returns a building system by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b13db3a5-3bbe-4706-97cc-247f3482643b"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Sustainable Facilities Tool API Returns all building systems.",
    "_postman_id": "29c74fa9-22cb-4d5c-884b-d5ee4e1b2383",
    "description": "Returns all building systems.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "5058113c-52e9-4cc5-983a-505e907cb1b1",
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
              "id": "0f889278-67ce-4ca3-b19f-068efc63685e"
            }
          ]
        }
      ]
    }
  ]
}
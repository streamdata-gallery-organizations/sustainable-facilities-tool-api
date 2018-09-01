{
  "info": {
    "name": "Sustainable Facilities Tool API Federal Acquisition Regulation (FAR) Clause",
    "_postman_id": "408b568e-3aa8-48fd-a339-400fa36dbf41",
    "description": "Returns Federal Acquisition Regulation (FAR) clause numbers and environmental programs for all NAICS and PSC codes with federal sustainable procurement requirements in GPC.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "2a9202bb-17e5-41c1-865c-0e7eca2f9b1a",
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
              "id": "fed28977-e4da-4ca5-abae-294d1d1cb738"
            }
          ]
        },
        {
          "id": "6144488e-dc17-4bb9-a55a-f91c3416bda8",
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
              "id": "7383d0b4-d94d-4c86-9040-3b888d79051c"
            }
          ]
        }
      ]
    },
    {
      "name": "Building System Resources",
      "item": [
        {
          "id": "92f6885a-ec47-460c-a036-fe772ee398ee",
          "name": "returnBuildingSystemResources",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "building-systems/:parameter/resources"
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
            "description": "Returns informational resources for the building system selected by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "268ae575-ab45-40b9-8112-8da2cb751994"
            }
          ]
        }
      ]
    },
    {
      "name": "Case Studies",
      "item": [
        {
          "id": "04bdb7f1-8564-475f-b6b3-421f180e1b4b",
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
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e77000a7-bba8-499b-9b0a-c22433d9697e"
            }
          ]
        },
        {
          "id": "02d73cee-4b4e-49e1-afc9-6e34e6a9cf63",
          "name": "returnBuildingSystemCaseStudies1",
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
            "description": "Returns a building system case study by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03118539-6c9b-404b-9aa2-27013e1e7b8b"
            }
          ]
        }
      ]
    },
    {
      "name": "Mandates",
      "item": [
        {
          "id": "c70bbf53-f225-4de4-917a-aaa69739f221",
          "name": "returnBuildingSystemMandates",
          "request": {
            "url": "http://api.data.gov/sftool/v1/building-systems/mandates",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all building systems mandates"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "05f2da88-57ec-482e-8e24-55fc1c9cc738"
            }
          ]
        },
        {
          "id": "c07a1812-f09a-43db-8184-4cd147945c07",
          "name": "returnBuildingSystemMandate",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "building-systems/:parameter/mandates"
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
            "description": "Returns a building system mandate by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "366aa838-c8b5-4415-aefb-a4020babcc68"
            }
          ]
        }
      ]
    },
    {
      "name": "Rating Systems",
      "item": [
        {
          "id": "e7a015e5-6df6-48bf-9b3d-25f039b7f565",
          "name": "returnBuildingSystemRating",
          "request": {
            "url": "http://api.data.gov/sftool/v1/building-systems/rating-systems",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all building system rating systems"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18c0a070-05de-431d-8ebd-08f936ce02f4"
            }
          ]
        },
        {
          "id": "b893491c-5881-414a-a3d6-28db9abd6306",
          "name": "returnBuildingSystemRating1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "building-systems/:parameter/rating-systems"
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
            "description": "Returns a building system rating system by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60ae5b36-e4dd-4bc0-b917-6965ed99b55c"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "f11cb977-8b28-4923-b3bb-d636059e8ec8",
          "name": "returnsBuildingSystemBundles",
          "request": {
            "url": "http://api.data.gov/sftool/v1/building-systems/system-bundles",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all building system bundles."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d1aeaeab-ae4c-438c-b450-f3621092ac3f"
            }
          ]
        },
        {
          "id": "c985c3ee-fb92-425e-a84d-5b2877092e7c",
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
            "description": "Returns a building system bundle by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38a8186e-02df-40f3-94b9-1fe43ceb7013"
            }
          ]
        }
      ]
    },
    {
      "name": "Teams",
      "item": [
        {
          "id": "58c5184b-cc14-4b79-8ff0-17178fd1ab46",
          "name": "returnBuildingSystemIntegrativeTeams",
          "request": {
            "url": "http://api.data.gov/sftool/v1/building-systems/integrative-teams",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all building system integrative teams."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a17ee4a6-ed24-4c26-99cc-0fe633cfe458"
            }
          ]
        },
        {
          "id": "2e699ddc-b70a-49c9-a32d-47a96c508ba4",
          "name": "returnBuildingSystemIntegrativeTeams1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "building-systems/:parameter/integrative-teams"
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
            "description": "Returns a building system integrative team by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0498fd61-91c9-4a0c-b06a-3f6eb2fda699"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "86bbd20b-4cb1-434c-a8be-44148b47d7d3",
          "name": "returnContentPages",
          "request": {
            "url": "http://api.data.gov/sftool/v1/contentpages",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all content pages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac902922-327b-4850-adc8-0528186dc1e1"
            }
          ]
        },
        {
          "id": "59f2a82b-8324-47b0-a270-4b8492ee4e83",
          "name": "returnContentPage",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "contentpages/:parameter"
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
            "description": "Returns a content page by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "601fe574-7cf1-4d21-a472-439d5eb7ca3b"
            }
          ]
        }
      ]
    },
    {
      "name": "Regulation Clause",
      "item": [
        {
          "id": "d1226873-c902-43c0-a060-061bd96aa2df",
          "name": "returnFederalAcquisitionRegulationClause",
          "request": {
            "url": "http://api.data.gov/sftool/v1/procurementclauses",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns Federal Acquisition Regulation (FAR) clause numbers and environmental programs for all NAICS and PSC codes with federal sustainable procurement requirements in GPC."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f4a25466-84d4-4557-a1f5-c979f3cb5247"
            }
          ]
        }
      ]
    }
  ]
}
{
  "info": {
    "name": "Sustainable Facilities Tool API Contract Language",
    "_postman_id": "3f235e3a-dc92-423b-bf31-e796d6bd795b",
    "description": "Returns all sample contract language for environmental programs",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "be9cd874-5ec6-4b8c-9d00-809590518c0e",
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
              "id": "46232019-c39b-404f-bc41-4304e0b34295"
            }
          ]
        },
        {
          "id": "e8eca563-17de-4bf1-95ca-9f159d508643",
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
              "id": "38c9df6f-c87f-4732-9b45-c8cb0fc988c1"
            }
          ]
        }
      ]
    },
    {
      "name": "Building System Resources",
      "item": [
        {
          "id": "2eb83123-30cc-4039-8db3-3f223c04f131",
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
              "id": "eaf9986e-1aa3-4c16-be26-e5904798cbf9"
            }
          ]
        }
      ]
    },
    {
      "name": "Case Studies",
      "item": [
        {
          "id": "bc21823c-9f28-4a9e-a247-48ed6dd98f6c",
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
              "id": "4658e971-4fb3-45c3-a6f2-2559eb538494"
            }
          ]
        },
        {
          "id": "330a84a5-32a9-4b38-b8c7-4ec231f897b9",
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
              "id": "0292fa76-12f6-4d24-92a5-741faf23352c"
            }
          ]
        }
      ]
    },
    {
      "name": "Mandates",
      "item": [
        {
          "id": "a58802c7-b21c-474d-969f-67bcc4869985",
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
              "id": "ef05b0e4-3c4c-4a07-85a9-54d7a3478a00"
            }
          ]
        },
        {
          "id": "62c2d51d-62b0-4d76-b439-43b1229bb644",
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
              "id": "7cd82e1d-cd3c-4273-9247-88329d341aea"
            }
          ]
        }
      ]
    },
    {
      "name": "Rating Systems",
      "item": [
        {
          "id": "c3c13aae-231a-423d-8539-e58e5100da70",
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
              "id": "3d2b66d4-d261-4d51-b1ac-b9c2daddde14"
            }
          ]
        },
        {
          "id": "6b2c6c0d-802f-44b1-bb68-2c0287a06cd4",
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
              "id": "ebca01d5-05b9-4c55-8d73-05108db23ca6"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "d87ebd91-48ee-4834-b631-391e17b06310",
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
              "id": "633967d3-e086-403c-adab-6947968b1d00"
            }
          ]
        },
        {
          "id": "3e96eaf7-f7ac-4fd9-b9d2-0e0a6d190d45",
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
              "id": "8c60eae9-b03c-4ff1-92d6-42cb6152e8ae"
            }
          ]
        }
      ]
    },
    {
      "name": "Teams",
      "item": [
        {
          "id": "68df9762-6d97-4b8b-bed4-50ecfca3d138",
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
              "id": "0a7f50f1-e43a-45fc-9e4f-896bc47c90db"
            }
          ]
        },
        {
          "id": "3f7890fc-9b29-4454-8476-625b63f6c700",
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
              "id": "e787f9b8-7d91-4e76-b408-420bd65c1eab"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "fdef6bf2-8718-4539-9e35-4e1233cbef5a",
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
              "id": "2cca1835-1be2-463e-900c-5aeecbec7645"
            }
          ]
        },
        {
          "id": "e7219e89-0456-482e-8607-c63070871b17",
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
              "id": "2b2add61-ae92-4fd3-a467-3d0375cc6dd3"
            }
          ]
        }
      ]
    },
    {
      "name": "Regulation Clause",
      "item": [
        {
          "id": "04b14e34-a90c-48d4-bf4f-44d1f63f7aa4",
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
              "id": "f0fd90a2-2a82-411d-b241-3f0238b24bac"
            }
          ]
        },
        {
          "id": "db75a919-179a-44ec-8f16-bf404f74a122",
          "name": "returnFederalAcquisitionRegulationClause1",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "procurementclauses/naics/:parameter"
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
            "description": "Returns any FAR clause number(s) and sample procurement language associated with the given NAICS parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7a41ca0b-42ef-4e7f-82b6-1c15c8a09891"
            }
          ]
        }
      ]
    },
    {
      "name": "Procurement Clause",
      "item": [
        {
          "id": "625b7f23-0588-49b2-895c-997beda00eff",
          "name": "returnFederalAcquisitionRegulationClause",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "procurementclauses/psc/:parameter"
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
            "description": "Returns any FAR clause number(s) and sample procurement language associated with the given PSC parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f8a9512-9710-4c09-8b22-2c23c5b2dff4"
            }
          ]
        }
      ]
    },
    {
      "name": "Contract Language",
      "item": [
        {
          "id": "25d8ad5e-b896-4494-9a95-de79b73789e8",
          "name": "contractLanguage",
          "request": {
            "url": "http://api.data.gov/sftool/v1/procurementclauses/allcontractlanguage",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all sample contract language for environmental programs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "60f22c73-8f49-4794-9a40-332b68916c1d"
            }
          ]
        }
      ]
    }
  ]
}
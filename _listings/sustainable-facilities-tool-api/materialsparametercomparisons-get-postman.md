{
  "info": {
    "name": "Sustainable Facilities Tool API Compairson Materials",
    "_postman_id": "6239937f-7766-474d-ba13-44d6a9bffbcd",
    "description": "Returns comparisons for the material selected by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "ccdda6f0-8586-40a6-825d-cfbb559e0588",
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
              "id": "4c2d8c51-d737-4be5-bd8f-c0ef136d7b8d"
            }
          ]
        },
        {
          "id": "3502015f-a1fa-4174-b87f-921908da4eb0",
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
              "id": "2d19bbb0-3b57-4601-adf2-59242b8b4679"
            }
          ]
        }
      ]
    },
    {
      "name": "Building System Resources",
      "item": [
        {
          "id": "1097e63f-b2d6-42ec-85f8-071e46740ceb",
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
              "id": "cdc31bf8-8c91-498b-bcda-2cff5e1b2796"
            }
          ]
        }
      ]
    },
    {
      "name": "Case Studies",
      "item": [
        {
          "id": "61bb4afe-fc82-42a4-89f3-d1426042e1a6",
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
              "id": "747b81c8-7cdc-44ad-94ac-0432556c1453"
            }
          ]
        },
        {
          "id": "ee07dc69-740c-4937-b5b4-b2b29225aa0c",
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
              "id": "ad603aa4-3746-49d7-b46b-36ecc214c514"
            }
          ]
        }
      ]
    },
    {
      "name": "Mandates",
      "item": [
        {
          "id": "18e8fb8b-1a63-4f77-96a7-b7792f3baef6",
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
              "id": "d19216de-5999-4381-b52a-24bd957d4bd1"
            }
          ]
        },
        {
          "id": "0ada88fc-be95-4cab-b363-98e78e194ba0",
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
              "id": "4e022f0f-b89c-4edb-9fcb-d6393937f786"
            }
          ]
        }
      ]
    },
    {
      "name": "Rating Systems",
      "item": [
        {
          "id": "6a296e73-bca6-4665-9d5b-e2f796a2f3e6",
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
              "id": "64da8f30-8951-4101-bbb3-23b6aa171be7"
            }
          ]
        },
        {
          "id": "98350fee-1f98-40f0-b2a1-89eaf4ca118a",
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
              "id": "a12dcf1f-b428-469e-b36c-6a4da1974a7b"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "a0ea8b38-2c08-41a8-83c9-5584dce40780",
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
              "id": "5245e398-60a9-4af1-b531-1db933717b4f"
            }
          ]
        },
        {
          "id": "6f04349e-f772-447a-920f-b936d68af2ba",
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
              "id": "55dfda0b-db51-4b41-81ad-c3a3daa6e97e"
            }
          ]
        }
      ]
    },
    {
      "name": "Teams",
      "item": [
        {
          "id": "8130467c-82da-4c1f-9435-d4ad4fdee65f",
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
              "id": "75173ab7-0654-4b00-9bf8-2e07cfcf23d7"
            }
          ]
        },
        {
          "id": "5c907b8d-80f0-431d-bf20-864b9617c2c1",
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
              "id": "a18bcd87-8b04-418f-aea2-c619ecef873e"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "f4490959-a719-4a65-896f-bae8343d52ba",
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
              "id": "7f3a3908-8f7d-4c71-81bc-daf2373cebb5"
            }
          ]
        },
        {
          "id": "49e7904e-4606-4a7f-8b38-6c43c58851cb",
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
              "id": "1c9b4ed7-0a27-49ac-af8e-48f4055dd88e"
            }
          ]
        }
      ]
    },
    {
      "name": "Regulation Clause",
      "item": [
        {
          "id": "860159d2-a835-46a9-a4b4-9639b8a40453",
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
              "id": "519b8ae7-adfd-4d94-a9a8-c17a60916afe"
            }
          ]
        },
        {
          "id": "0c39bb85-45a3-40fb-b5ff-479e8db9c44c",
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
              "id": "0f601a55-4016-478c-bee6-8c17c56520ad"
            }
          ]
        }
      ]
    },
    {
      "name": "Procurement Clause",
      "item": [
        {
          "id": "f6b53469-fa30-4484-9ab0-07ae13819718",
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
              "id": "9baeb293-2b6b-482c-b16f-328828fa67cd"
            }
          ]
        }
      ]
    },
    {
      "name": "Contract Language",
      "item": [
        {
          "id": "113c53fb-e60d-4da5-a665-3a2e95f754e6",
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
              "id": "59e509c6-b7c1-4d4c-9c94-c909266f5811"
            }
          ]
        }
      ]
    },
    {
      "name": "Materials",
      "item": [
        {
          "id": "aa8a6198-ef42-40e1-b3ff-05fe1fb310b0",
          "name": "returnMaterials",
          "request": {
            "url": "http://api.data.gov/sftool/v1/materials",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns all materials."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b4d09f4-53e5-404c-9bb5-54ee283a4718"
            }
          ]
        },
        {
          "id": "464c1de4-8b5b-4649-9d5f-6a3046fb2a85",
          "name": "returnMaterial",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "materials/:parameter"
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
            "description": "Returns a material by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7ec4b5a4-5103-4787-9b79-b3016b7b3b00"
            }
          ]
        }
      ]
    },
    {
      "name": "Alternative Materials",
      "item": [
        {
          "id": "5f8a3f1d-af89-467a-81e2-ca7fe06d5870",
          "name": "getAlternativeMaterials",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "materials/:parameter/alternatives"
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
            "description": "Returns alternatives for the material selected by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a1c9824f-4aa7-4a7d-a2de-d6e897778281"
            }
          ]
        }
      ]
    },
    {
      "name": "Comparison Materials",
      "item": [
        {
          "id": "8f1ca8b1-e599-45e1-b6c2-cc525004f516",
          "name": "returnCompairsonMaterials",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "sftool",
                "v1",
                "materials/:parameter/comparisons"
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
            "description": "Returns comparisons for the material selected by parameter."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1797508d-aed0-4c31-bb04-35d7b95ba421"
            }
          ]
        }
      ]
    }
  ]
}
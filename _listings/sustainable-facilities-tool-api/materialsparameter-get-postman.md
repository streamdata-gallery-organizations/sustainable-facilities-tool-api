{
  "info": {
    "name": "Sustainable Facilities Tool API Return Material",
    "_postman_id": "8d6d5ccc-77cd-4cf2-a236-ffffad7a868a",
    "description": "Returns a material by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "b96d3ada-bf9c-4132-932e-6630d2ce77df",
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
              "id": "cad0cc58-eb5c-45bd-a93a-959898dc3285"
            }
          ]
        },
        {
          "id": "1acaab15-f881-4877-8787-fbeac29a0faf",
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
              "id": "6083b123-ffeb-4ec6-8413-45ab8e6c78ae"
            }
          ]
        }
      ]
    },
    {
      "name": "Building System Resources",
      "item": [
        {
          "id": "46fefca4-e0fd-475b-b0c4-6f38cacb8862",
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
              "id": "93374442-3c8c-46dd-8f3b-d7f5704e6b5d"
            }
          ]
        }
      ]
    },
    {
      "name": "Case Studies",
      "item": [
        {
          "id": "30ea6e42-a8a9-404d-b4fb-aa5401cfe648",
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
              "id": "9c09169c-c7a1-46c9-8243-f234e1ad5b85"
            }
          ]
        },
        {
          "id": "fe370a0d-fba2-4a15-9d6c-00b7eb4e1868",
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
              "id": "49f67a60-9f3e-4fcb-8b40-b13f78b0ab7d"
            }
          ]
        }
      ]
    },
    {
      "name": "Mandates",
      "item": [
        {
          "id": "c977a3e9-f922-4ff9-9cbd-76e8922e5c5c",
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
              "id": "44dbf122-afee-46b9-9728-1f160ce5e518"
            }
          ]
        },
        {
          "id": "6f94f222-cf1c-4493-8a1f-046e19254cc4",
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
              "id": "c5461fc4-b7fa-4c21-b268-45520a3e9489"
            }
          ]
        }
      ]
    },
    {
      "name": "Rating Systems",
      "item": [
        {
          "id": "7dd915af-38bd-4563-9bc8-0b6b9ac5635e",
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
              "id": "4f040c9d-5f37-4877-9b43-522317a99897"
            }
          ]
        },
        {
          "id": "49849ffa-d9df-4962-999b-2480ef7d1051",
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
              "id": "bf1dc8fe-43be-4a14-bf0a-54b17b53a38a"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "d50d6049-9884-4e07-ada3-91b83fce0594",
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
              "id": "e9c349f4-7b1d-4bcf-8b50-dfa20241e892"
            }
          ]
        },
        {
          "id": "f1d80c38-6851-4e64-9675-903cf4e7ed42",
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
              "id": "23089943-d1be-4031-a270-110ee8bf807f"
            }
          ]
        }
      ]
    },
    {
      "name": "Teams",
      "item": [
        {
          "id": "8a61102a-0545-484c-b2f2-807b9d2aadc0",
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
              "id": "92b118b1-76f9-472d-bd32-7f6d1e027924"
            }
          ]
        },
        {
          "id": "5af55717-7d69-4415-994a-3ac00d3cf6c0",
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
              "id": "eebf539a-e23f-4ddf-8c40-473f6f24b7be"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "46e7aa7e-89b4-4300-a336-47328af47f8d",
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
              "id": "f296bfec-2cdb-4e26-89ea-b43938f6a54f"
            }
          ]
        },
        {
          "id": "ca4371fd-3845-418f-baa8-92450f816724",
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
              "id": "24239b52-d959-4383-8631-dbdbd33a6f90"
            }
          ]
        }
      ]
    },
    {
      "name": "Regulation Clause",
      "item": [
        {
          "id": "8789c998-e0ef-4981-b765-0c514182aafb",
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
              "id": "cd64ba7c-5ae8-4fbe-9920-e6aa69a2bc6c"
            }
          ]
        },
        {
          "id": "8d6c1f15-5fdc-410f-896d-252133d269c6",
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
              "id": "819fa6cb-356c-499d-863c-b2dd1af8cbcd"
            }
          ]
        }
      ]
    },
    {
      "name": "Procurement Clause",
      "item": [
        {
          "id": "3cff114f-21a9-4dd3-ae71-c4bf563ad90b",
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
              "id": "3593a909-5fb5-4ed6-9845-4a67a785cf14"
            }
          ]
        }
      ]
    },
    {
      "name": "Contract Language",
      "item": [
        {
          "id": "0ce068f5-8360-4f67-b96f-060c0ba7b7fe",
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
              "id": "cd833e15-7902-4b96-a23f-5a942b5d8936"
            }
          ]
        }
      ]
    },
    {
      "name": "Materials",
      "item": [
        {
          "id": "15e97fef-3abb-42d5-9dd1-1cee6927741c",
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
              "id": "8c6d8766-3874-4688-ae44-a5c098b6fe8f"
            }
          ]
        },
        {
          "id": "542f7230-f279-4a41-91a0-ae41281a7bd4",
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
              "id": "71b7b7c0-60ba-45dc-a55a-56d026deca4d"
            }
          ]
        }
      ]
    }
  ]
}
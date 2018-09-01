{
  "info": {
    "name": "Sustainable Facilities Tool API Return Materials",
    "_postman_id": "f1756def-76cc-4207-bc16-703c423032f0",
    "description": "Returns all materials.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "919d6164-cb78-433d-885d-fb935516fb0b",
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
              "id": "5c09d13d-cc67-4071-8895-07b6886c8825"
            }
          ]
        },
        {
          "id": "fd7457b8-62c1-450d-a846-c1c36bc999d4",
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
              "id": "23158098-e0fa-4555-994a-c6b1e6d050f3"
            }
          ]
        }
      ]
    },
    {
      "name": "Building System Resources",
      "item": [
        {
          "id": "833d24c7-12db-432d-a087-e8ec594944f4",
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
              "id": "28c3700b-c3fa-470b-90f5-c12bc9f4c532"
            }
          ]
        }
      ]
    },
    {
      "name": "Case Studies",
      "item": [
        {
          "id": "8375f258-b456-4fe8-9f1b-28d4f8a4ef32",
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
              "id": "c322e8c0-6ccc-4498-a80b-dfcc02fe9602"
            }
          ]
        },
        {
          "id": "e3641103-fb5f-4224-98f0-7e2be88fcf80",
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
              "id": "7fe5608b-01c0-4904-ada4-9c51025c0f06"
            }
          ]
        }
      ]
    },
    {
      "name": "Mandates",
      "item": [
        {
          "id": "ac053254-1690-4d7a-889b-1812d82d1d67",
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
              "id": "df5ba3f5-6cc7-4eed-8b8b-56a7be9f4cf8"
            }
          ]
        },
        {
          "id": "81f1a67e-feb9-475c-b14b-97ea236c243e",
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
              "id": "b2b1ae86-c987-4e19-b3ff-c376a7202c06"
            }
          ]
        }
      ]
    },
    {
      "name": "Rating Systems",
      "item": [
        {
          "id": "d12fee64-150b-4e26-ac7e-cfa8379611af",
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
              "id": "2374928b-fb16-4850-9d43-ea75be6ab051"
            }
          ]
        },
        {
          "id": "900a1693-ba56-4510-9702-173ece7d18f2",
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
              "id": "5e7f09b5-2d21-435b-9bc5-2e80c90893bf"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "44db8259-bd67-4926-b72d-418a35cd225a",
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
              "id": "0ddf1592-d4ad-4a2a-98c9-4590bb110b63"
            }
          ]
        },
        {
          "id": "af53cd46-7dcb-42f7-9a8b-4d22288322c9",
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
              "id": "913a2de5-dd41-4f14-856b-4d4adb196ed6"
            }
          ]
        }
      ]
    },
    {
      "name": "Teams",
      "item": [
        {
          "id": "1032c2ef-e4c2-495f-9d14-14930df8b51b",
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
              "id": "65229351-060a-4a63-860d-e22633c194f7"
            }
          ]
        },
        {
          "id": "c7e3fa89-5158-4edf-9e2b-32a885606529",
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
              "id": "2bad868b-149b-44cf-8433-96aeb0df8576"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "116d2eb7-2385-4329-8b2a-b0f8c26425dc",
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
              "id": "b1d87291-bc05-4ff5-ab3c-76e0c62f5a34"
            }
          ]
        },
        {
          "id": "00b0ec9e-5810-423e-990b-e1dee6676c91",
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
              "id": "c28b696b-be50-4ff5-97c7-e9ccc739bee1"
            }
          ]
        }
      ]
    },
    {
      "name": "Regulation Clause",
      "item": [
        {
          "id": "15fff234-641c-4afb-adf5-5852bca35c06",
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
              "id": "b59a9a49-6a6c-4987-bf2f-2c9316334153"
            }
          ]
        },
        {
          "id": "c62fe65e-ab20-4ab8-8ae4-b18d770bb70e",
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
              "id": "dff934e6-96a7-4b06-9b7a-0959f53e1550"
            }
          ]
        }
      ]
    },
    {
      "name": "Procurement Clause",
      "item": [
        {
          "id": "02f28128-3a75-4bd6-a10e-108d1e9cee84",
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
              "id": "070f9872-689d-4cf4-9629-3641f97c2741"
            }
          ]
        }
      ]
    },
    {
      "name": "Contract Language",
      "item": [
        {
          "id": "73a59bff-a89c-49a8-aed4-df901bde638e",
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
              "id": "cce6519a-98eb-4ff3-96bd-ce9b17dd57a9"
            }
          ]
        }
      ]
    },
    {
      "name": "Materials",
      "item": [
        {
          "id": "c9916b5e-0919-42c6-8c85-8e7f6e0b88df",
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
              "id": "c015c269-50f1-4269-b55b-4bf7ebddad5d"
            }
          ]
        }
      ]
    }
  ]
}
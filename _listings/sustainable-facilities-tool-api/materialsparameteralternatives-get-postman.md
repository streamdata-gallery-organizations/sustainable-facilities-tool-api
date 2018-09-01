{
  "info": {
    "name": "Sustainable Facilities Tool API Alternative Materials",
    "_postman_id": "4512fcaf-5531-4239-b2c2-04fda2bd82a8",
    "description": "Returns alternatives for the material selected by parameter.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Building Systems",
      "item": [
        {
          "id": "bb194339-6115-4ba6-b2cf-6f46384a9c29",
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
              "id": "753094c2-6e3d-4aad-ad5f-2dee06b67c64"
            }
          ]
        },
        {
          "id": "6336c673-2198-4de9-8ebb-2ac2dcbbbc3e",
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
              "id": "3e03e2f8-ef33-4001-8443-a8d1cb41cb6f"
            }
          ]
        }
      ]
    },
    {
      "name": "Building System Resources",
      "item": [
        {
          "id": "be2ad70b-1fbe-46df-a4cc-5f541a224f10",
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
              "id": "1545ec08-b135-4518-8e8c-405ec59eb960"
            }
          ]
        }
      ]
    },
    {
      "name": "Case Studies",
      "item": [
        {
          "id": "68864395-6441-47c4-8ef0-65b00747229c",
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
              "id": "952c4bd7-009d-4885-9068-5bfc87382f78"
            }
          ]
        },
        {
          "id": "f760cfa6-6fca-477b-a700-b938b0751067",
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
              "id": "6b4be3a5-8871-4e7a-a152-cab86bb65e33"
            }
          ]
        }
      ]
    },
    {
      "name": "Mandates",
      "item": [
        {
          "id": "d81fb10c-8ec8-4ca4-900a-26c466661c18",
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
              "id": "1e84697a-c6de-4a71-8007-e3e5d04f8b7d"
            }
          ]
        },
        {
          "id": "db5345ac-a9f9-410a-9754-a1341163865b",
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
              "id": "fb2844ea-f1a0-4a5c-a9b8-043ce4bab024"
            }
          ]
        }
      ]
    },
    {
      "name": "Rating Systems",
      "item": [
        {
          "id": "6466cb83-683c-4c9c-94ce-34a14732c81c",
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
              "id": "1bcd5b59-14ef-4ceb-bcf9-b4d4786f6ed7"
            }
          ]
        },
        {
          "id": "6aa385d4-e28e-4d59-953a-c035b984f0d0",
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
              "id": "bfeffbc1-bcb1-4535-981f-22a5d289e880"
            }
          ]
        }
      ]
    },
    {
      "name": "Bundles",
      "item": [
        {
          "id": "d7fa746d-c6f0-422c-a0a3-fb283bf83b24",
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
              "id": "0125ee7e-35a6-402c-8107-454910b4a1cb"
            }
          ]
        },
        {
          "id": "1fd82d40-56cb-4502-ac13-9ecf6b1bfd40",
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
              "id": "894709ba-1d16-41cb-a9a2-dc13ed480236"
            }
          ]
        }
      ]
    },
    {
      "name": "Teams",
      "item": [
        {
          "id": "b63a3d9c-baa7-495d-8aca-a77ab05cafc2",
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
              "id": "3576c2a7-645b-466a-98ed-7b0feaf352d9"
            }
          ]
        },
        {
          "id": "49254f79-8d54-488e-b8a1-b75231f8c5ef",
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
              "id": "5acb3a84-4ad3-4f30-b7e9-2fc2ec82ce59"
            }
          ]
        }
      ]
    },
    {
      "name": "Content",
      "item": [
        {
          "id": "d1a6782e-8135-49a0-b159-acde9a137078",
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
              "id": "fdcd6978-63c3-4e0f-b026-0d1964d412f8"
            }
          ]
        },
        {
          "id": "3f119bf2-0d1f-4d7a-af34-b2b6a868beb0",
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
              "id": "69837cf2-8bde-4b4e-b854-ebc6b255964c"
            }
          ]
        }
      ]
    },
    {
      "name": "Regulation Clause",
      "item": [
        {
          "id": "ec7f187a-716b-475a-ba68-85e0ab225a88",
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
              "id": "28db6369-edb2-40fd-8ada-2c25052bd781"
            }
          ]
        },
        {
          "id": "81a64c56-07fd-435b-a8c0-7df3dc1450c6",
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
              "id": "c00eea81-f42c-4e3e-a32c-d33945cfdbab"
            }
          ]
        }
      ]
    },
    {
      "name": "Procurement Clause",
      "item": [
        {
          "id": "f155b196-b475-4e09-a0e5-a1addff3133d",
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
              "id": "140262bb-6619-4724-83f8-d8c8ab5cf96f"
            }
          ]
        }
      ]
    },
    {
      "name": "Contract Language",
      "item": [
        {
          "id": "8bb98e7c-9d74-43d3-97d3-4c1d06ef54d9",
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
              "id": "222c868e-c809-41b1-9175-48e8745f44a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Materials",
      "item": [
        {
          "id": "95720bac-db11-47db-a6cf-e9de2fc45ed4",
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
              "id": "7e5605b1-335d-4105-b053-a8b8b8856027"
            }
          ]
        },
        {
          "id": "7b4f30d1-7348-4df7-b8ea-1f7c1b6f1164",
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
              "id": "8b444dd8-2c52-46bd-9e3e-cdc3a7c95fec"
            }
          ]
        }
      ]
    },
    {
      "name": "Alternative Materials",
      "item": [
        {
          "id": "6d0d2443-877d-4fa5-9e2e-fedbbb4a20cd",
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
              "id": "507e89f0-c298-474e-a412-773f5c018c23"
            }
          ]
        }
      ]
    }
  ]
}
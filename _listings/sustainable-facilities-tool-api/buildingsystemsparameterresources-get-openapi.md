---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 0
info:
  title: Sustainable Facilities Tool API Returns Building System Resources
  description: Returns informational resources for the building system selected by
    parameter.
  termsOfService: https://sftool.gov/developer/terms-of-use
  version: 1.0.0
host: api.data.gov
basePath: /sftool/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /building-systems:
    get:
      summary: Returns all building systems.
      description: Returns all building systems.
      operationId: returnBuildingSystems
      x-api-path-slug: buildingsystems-get
      responses:
        200:
          description: OK
      tags:
      - Building Systems
  /building-systems/{parameter}:
    get:
      summary: Returns a building system by parameter.
      description: Returns a building system by parameter.
      operationId: returnBuildingSystem
      x-api-path-slug: buildingsystemsparameter-get
      responses:
        200:
          description: OK
      tags:
      - Building Systems
  /building-systems/{parameter}/resources:
    get:
      summary: Returns Building System Resources
      description: Returns informational resources for the building system selected
        by parameter.
      operationId: returnBuildingSystemResources
      x-api-path-slug: buildingsystemsparameterresources-get
      responses:
        200:
          description: OK
      tags:
      - Building System Resources
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---
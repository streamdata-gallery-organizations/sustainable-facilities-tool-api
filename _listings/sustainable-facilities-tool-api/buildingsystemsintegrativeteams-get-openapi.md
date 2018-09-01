---
swagger: "2.0"
x-collection-name: Sustainable Facilities Tool API
x-complete: 0
info:
  title: Sustainable Facilities Tool API Building System Integrative Teams
  description: Returns all building system integrative teams.
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
  /building-systems/case-studies:
    get:
      summary: Building System Case Studies
      description: Returns all building systems case studies
      operationId: returnBuildingSystemCaseStudies
      x-api-path-slug: buildingsystemscasestudies-get
      responses:
        200:
          description: OK
      tags:
      - Case Studies
  /building-systems/{parameter}/case-studies:
    get:
      summary: Building System Case Study
      description: Returns a building system case study by parameter.
      operationId: returnBuildingSystemCaseStudies
      x-api-path-slug: buildingsystemsparametercasestudies-get
      responses:
        200:
          description: OK
      tags:
      - Case Studies
  /building-systems/mandates:
    get:
      summary: Building System Mandates
      description: Returns all building systems mandates
      operationId: returnBuildingSystemMandates
      x-api-path-slug: buildingsystemsmandates-get
      responses:
        200:
          description: OK
      tags:
      - Mandates
  /building-systems/{parameter}/mandates:
    get:
      summary: Building System Mandate
      description: Returns a building system mandate by parameter.
      operationId: returnBuildingSystemMandate
      x-api-path-slug: buildingsystemsparametermandates-get
      responses:
        200:
          description: OK
      tags:
      - Mandates
  /building-systems/rating-systems:
    get:
      summary: Building System Rating Systems
      description: Returns all building system rating systems
      operationId: returnBuildingSystemRating
      x-api-path-slug: buildingsystemsratingsystems-get
      responses:
        200:
          description: OK
      tags:
      - Rating Systems
  /building-systems/{parameter}/rating-systems:
    get:
      summary: Building System Rating System
      description: Returns a building system rating system by parameter.
      operationId: returnBuildingSystemRating
      x-api-path-slug: buildingsystemsparameterratingsystems-get
      responses:
        200:
          description: OK
      tags:
      - Rating Systems
  /building-systems/system-bundles:
    get:
      summary: Building System Bundles
      description: Returns all building system bundles.
      operationId: returnsBuildingSystemBundles
      x-api-path-slug: buildingsystemssystembundles-get
      responses:
        200:
          description: OK
      tags:
      - Bundles
  /building-systems/{parameter}/system-bundles:
    get:
      summary: Building System Bundle
      description: Returns a building system bundle by parameter.
      operationId: returnsBuildingSystemBundle
      x-api-path-slug: buildingsystemsparametersystembundles-get
      responses:
        200:
          description: OK
      tags:
      - Bundles
  /building-systems/integrative-teams:
    get:
      summary: Building System Integrative Teams
      description: Returns all building system integrative teams.
      operationId: returnBuildingSystemIntegrativeTeams
      x-api-path-slug: buildingsystemsintegrativeteams-get
      responses:
        200:
          description: OK
      tags:
      - Teams
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
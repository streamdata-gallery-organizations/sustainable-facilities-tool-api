---
name: Sustainable Facilities Tool API
x-slug: sustainable-facilities-tool-api
description: Our core API allows developers to interact with the Sustainable Facilities
  Tool programmatically. Its designed for public use and to be easily integrated into
  other applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
x-kinRank: "8"
x-alexaRank: "0"
tags: Sustainable Facilities Tool API
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/apis.md
specificationVersion: "0.14"
apis:
- name: Sustainable Facilities Tool API Returns all building systems.
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all building systems.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems
  tags: Building Systems
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystems-get-openapi.md
- name: Sustainable Facilities Tool API Returns a building system by parameter.
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a building system by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}
  tags: Building Systems
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameter-get-openapi.md
- name: Sustainable Facilities Tool API Returns Building System Resources
  x-api-slug: sustainable-facilities-tool-api
  description: Returns informational resources for the building system selected by
    parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}/resources
  tags: Building System Resources
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterresources-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterresources-get-openapi.md
- name: Sustainable Facilities Tool API Building System Case Studies
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all building systems case studies
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/case-studies
  tags: Case Studies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemscasestudies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemscasestudies-get-openapi.md
- name: Sustainable Facilities Tool API Building System Case Study
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a building system case study by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}/case-studies
  tags: Case Studies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparametercasestudies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparametercasestudies-get-openapi.md
- name: Sustainable Facilities Tool API Building System Mandates
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all building systems mandates
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/mandates
  tags: Mandates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsmandates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsmandates-get-openapi.md
- name: Sustainable Facilities Tool API Building System Mandate
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a building system mandate by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}/mandates
  tags: Mandates
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparametermandates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparametermandates-get-openapi.md
- name: Sustainable Facilities Tool API Building System Rating Systems
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all building system rating systems
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/rating-systems
  tags: Rating Systems
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsratingsystems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsratingsystems-get-openapi.md
- name: Sustainable Facilities Tool API Building System Rating System
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a building system rating system by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}/rating-systems
  tags: Rating Systems
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterratingsystems-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterratingsystems-get-openapi.md
- name: Sustainable Facilities Tool API Building System Bundles
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all building system bundles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/system-bundles
  tags: Bundles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemssystembundles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemssystembundles-get-openapi.md
- name: Sustainable Facilities Tool API Building System Bundle
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a building system bundle by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}/system-bundles
  tags: Bundles
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparametersystembundles-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparametersystembundles-get-openapi.md
- name: Sustainable Facilities Tool API Building System Integrative Teams
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all building system integrative teams.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/integrative-teams
  tags: Teams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsintegrativeteams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsintegrativeteams-get-openapi.md
- name: Sustainable Facilities Tool API Building System Integrative Team
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a building system integrative team by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///building-systems/{parameter}/integrative-teams
  tags: Teams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterintegrativeteams-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/buildingsystemsparameterintegrativeteams-get-openapi.md
- name: Sustainable Facilities Tool API Content Pages
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all content pages
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///contentpages
  tags: Content
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/contentpages-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/contentpages-get-openapi.md
- name: Sustainable Facilities Tool API Content Page
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a content page by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///contentpages/{parameter}
  tags: Content
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/contentpagesparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/contentpagesparameter-get-openapi.md
- name: Sustainable Facilities Tool API Federal Acquisition Regulation (FAR) Clause
  x-api-slug: sustainable-facilities-tool-api
  description: Returns Federal Acquisition Regulation (FAR) clause numbers and environmental
    programs for all NAICS and PSC codes with federal sustainable procurement requirements
    in GPC.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///procurementclauses
  tags: Regulation Clause
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclauses-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclauses-get-openapi.md
- name: Sustainable Facilities Tool API Federal Acquisition Regulation (FAR) Clause
  x-api-slug: sustainable-facilities-tool-api
  description: Returns any FAR clause number(s) and sample procurement language associated
    with the given NAICS parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///procurementclauses/naics/{parameter}
  tags: Regulation Clause
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclausesnaicsparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclausesnaicsparameter-get-openapi.md
- name: Sustainable Facilities Tool API Procurement Clause
  x-api-slug: sustainable-facilities-tool-api
  description: Returns any FAR clause number(s) and sample procurement language associated
    with the given PSC parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///procurementclauses/psc/{parameter}
  tags: Procurement Clause
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclausespscparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclausespscparameter-get-openapi.md
- name: Sustainable Facilities Tool API Contract Language
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all sample contract language for environmental programs
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///procurementclauses/allcontractlanguage
  tags: Contract Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclausesallcontractlanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/procurementclausesallcontractlanguage-get-openapi.md
- name: Sustainable Facilities Tool API Return Materials
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all materials.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///materials
  tags: Materials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materials-get-openapi.md
- name: Sustainable Facilities Tool API Return Material
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a material by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///materials/{parameter}
  tags: Materials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materialsparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materialsparameter-get-openapi.md
- name: Sustainable Facilities Tool API Alternative Materials
  x-api-slug: sustainable-facilities-tool-api
  description: Returns alternatives for the material selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///materials/{parameter}/alternatives
  tags: Alternative Materials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materialsparameteralternatives-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materialsparameteralternatives-get-openapi.md
- name: Sustainable Facilities Tool API Compairson Materials
  x-api-slug: sustainable-facilities-tool-api
  description: Returns comparisons for the material selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///materials/{parameter}/comparisons
  tags: Comparison Materials
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materialsparametercomparisons-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/materialsparametercomparisons-get-openapi.md
- name: Sustainable Facilities Tool API Products
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all products.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///products
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/products-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/products-get-openapi.md
- name: Sustainable Facilities Tool API Product Details
  x-api-slug: sustainable-facilities-tool-api
  description: Returns details for the product selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///products/{parameter}/details
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/productsparameterdetails-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/productsparameterdetails-get-openapi.md
- name: Sustainable Facilities Tool API Services
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all services
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///services
  tags: Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/services-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/services-get-openapi.md
- name: Sustainable Facilities Tool API Services
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a service by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///services/{parameter}
  tags: Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/servicesparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/servicesparameter-get-openapi.md
- name: Sustainable Facilities Tool API Related Products
  x-api-slug: sustainable-facilities-tool-api
  description: Returns products related to a service by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///services/{parameter}/related-products
  tags: Products
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/servicesparameterrelatedproducts-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/servicesparameterrelatedproducts-get-openapi.md
- name: Sustainable Facilities Tool API Tags
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all search tags.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///tags
  tags: Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/tags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/tags-get-openapi.md
- name: Sustainable Facilities Tool API Tag
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a tag by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///tags/{parameter}
  tags: Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/tagsparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/tagsparameter-get-openapi.md
- name: Sustainable Facilities Tool API Workspaces
  x-api-slug: sustainable-facilities-tool-api
  description: Returns all workspaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspaces-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspaces-get-openapi.md
- name: Sustainable Facilities Tool API Workspace
  x-api-slug: sustainable-facilities-tool-api
  description: Returns a workspace by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces/{parameter}
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspacesparameter-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspacesparameter-get-openapi.md
- name: Sustainable Facilities Tool API Workspaces
  x-api-slug: sustainable-facilities-tool-api
  description: Returns material groups for the workspace selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces/{parameter}/material-groups
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterialgroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterialgroups-get-openapi.md
- name: Sustainable Facilities Tool API Workspace Materials
  x-api-slug: sustainable-facilities-tool-api
  description: Returns materials for the workspace selected by parameter.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1///workspaces/{parameter}/materials
  tags: Workspaces
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterials-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/workspacesparametermaterials-get-openapi.md
- name: Sustainable Facilities Tool API
  x-api-slug: sustainable-facilities-tool-api
  description: Our core API allows developers to interact with the Sustainable Facilities
    Tool programmatically. Its designed for public use and to be easily integrated
    into other applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/sustainable-facilities-mobile_504b7.png
  humanURL: https://sftool.gov/
  baseURL: https://api.data.gov//sftool/v1/
  tags: Sustainable Facilities Tool API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/sustainable-facilities-tool-api/master/_listings/sustainable-facilities-tool-api/openapi.md
x-common:
- type: x-developer
  url: https://sftool.gov/developers
- type: x-terms-of-service
  url: https://sftool.gov/developer/terms-of-use
- type: x-twitter
  url: https://twitter.com/sftool
- type: x-website
  url: https://sftool.gov/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---
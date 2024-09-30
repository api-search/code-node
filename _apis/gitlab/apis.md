---
name: GitLab
description: >-
  GitLab Inc. is an open-core company that operates GitLab, a DevOps software
  package that can develop, secure, and operate software.[9] The open source
  software project was created by Ukrainian developer Dmytro Zaporozhets and
  Dutch developer Sytse Sijbrandij.[10] In 2018, GitLab Inc. was considered to
  be the first partly-Ukrainian unicorn. Since its founding, GitLab Inc. has
  promoted remote work,[13] and is known as one of the largest all-remote
  companies in the world.[14] GitLab has an estimated 30 million registered
  users, with 1 million being active licensed users.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/api-search/code/main/_apis/gitlab/apis.md
created: 2023/11/10
modified: 2023/11/10
specificationVersion: '0.16'
tags: []
apis:
  - name: GitLab GraphQL API
    description: >-
      GraphQL is a query language for APIs. You can use it to request the exact
      data you need, and therefore limit the number of requests you need.
      GraphQL data is arranged in types, so your client can use client-side
      GraphQL libraries to consume the API and avoid manual parsing. There are
      no fixed endpoints and no data model, so you can add to the API without
      creating breaking changes. This enables us to have a versionless API.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://docs.gitlab.com/ee/api/graphql/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://docs.gitlab.com/ee/api/graphql/
      - type: Deprecation
        url: >-
          https://docs.gitlab.com/ee/api/graphql/#deprecation-and-removal-process
      - type: Breaking Changes
        url: >-
          https://docs.gitlab.com/ee/api/graphql/#deprecation-and-removal-process
      - type: Rate Limits
        url: https://docs.gitlab.com/ee/api/graphql/#limits
    overlays: []
    aid: gitlab:gitlab-graphql-api
  - name: ' api/v4/groups'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-groups-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-groups-openapi-search.yml
    aid: gitlab:apiv4groups
  - name: ' api/v4/projects'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-projects-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-projects-openapi-search.yml
    aid: gitlab:apiv4projects
  - name: ' api/v4/admin'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-admin-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-admin-openapi-search.yml
    aid: gitlab:apiv4admin
  - name: ' api/v4/applications'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-applications-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-applications-openapi-search.yml
    aid: gitlab:apiv4applications
  - name: ' api/v4/avatar'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-avatar-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-avatar-openapi-search.yml
    aid: gitlab:apiv4avatar
  - name: ' api/v4/broadcast messages'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-broadcast-messages-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-broadcast-messages-openapi-search.yml
    aid: gitlab:apiv4broadcast-messages
  - name: ' api/v4/bulk imports'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-bulk-imports-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-bulk-imports-openapi-search.yml
    aid: gitlab:apiv4bulk-imports
  - name: ' api/v4/application'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-application-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-application-openapi-search.yml
    aid: gitlab:apiv4application
  - name: ' api/v4/metadata'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-metadata-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-metadata-openapi-search.yml
    aid: gitlab:apiv4metadata
  - name: ' api/v4/version'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/gitlab-api-v4-version-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/gitlab-api-v4-version-openapi-search.yml
    aid: gitlab:apiv4version
common:
  - type: Terms of Service
    url: https://about.gitlab.com/terms/
  - type: Privacy Policy
    url: https://about.gitlab.com/privacy/
  - type: Contact
    url: https://about.gitlab.com/company/contact/
  - type: IDE
    url: https://docs.gitlab.com/ee/editor_extensions/
  - type: Whats New
    url: https://about.gitlab.com/releases/categories/releases/
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: gitlab
---
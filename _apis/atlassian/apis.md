---
name: Atlassian
description: >-
  Atlassian Corporation is an Australian software company that develops products
  for software developers, project managers and other software development
  teams.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/atlassian.yml
created: 2023/11/10
modified: 2023/11/10
specificationVersion: '0.16'
tags: []
apis:
  - name: Jira API
    description: >-
      The Jira REST API enables you to interact with Jira programmatically. Use
      this API to build apps, script interactions with Jira, or develop any
      other type of integration. This page documents the REST resources
      available in Jira Cloud, including the HTTP response codes and example
      requests and responses.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/#about
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/intro/#about
      - type: OpenAPI
        url: properties/jira-openapi-original.yml
      - type: Postman Collection
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/jiracloud.3.postman.json
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://dac-static.atlassian.com/cloud/jira/platform/swagger-v3.v3.json?_v=1.6660.0-0.1294.0-openapi-search.yml
      - type: APIs.io Search
        url: overlays/jira-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/jira-openapi-api-evangelist-ratings.yml
    aid: atlassian:jira-api
  - name: Confluence API
    description: >-
      This is the reference for the Confluence Cloud REST API. This API is the
      primary way to get and modify data in Confluence Cloud, whether you are
      developing an app or any other integration. Use it to interact with
      Confluence entities, like pages and blog posts, spaces, users, groups, and
      more.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.atlassian.com/cloud/confluence/rest/v1/intro/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.atlassian.com/cloud/confluence/rest/v1/intro/
      - type: OpenAPI
        url: properties/confluence-openapi-original.yml
      - type: Postman Collection
        url: >-
          https://developer.atlassian.com/cloud/confluence/confcloud.1.postman.json
      - type: Authentication
        url: https://developer.atlassian.com/cloud/confluence/rest/v1/intro/#auth
      - type: Status Codes
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/intro/#status-code
      - type: Capabilities
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/intro/#capabilities
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://dac-static.atlassian.com/cloud/confluence/swagger.v3.json?_v=1.6660.0-0.1294.0-openapi-search.yml
      - type: APIs.io Search
        url: overlays/confluence-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/confluence-openapi-api-evangelist-ratings.yml
    aid: atlassian:confluence-api
  - name: BitBucket API
    description: >-
      The purpose of this section is to describe how to authenticate when making
      API calls using the Bitbucket REST API.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.atlassian.com/cloud/bitbucket/rest/intro/
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.atlassian.com/cloud/bitbucket/rest/intro/
      - type: OpenAPI
        url: properties/bitbucket-openapi-original.yml
      - type: Postman Collection
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/bitbucketcloud.postman.json
      - type: Authentication
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/rest/intro/#authentication
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://dac-static.atlassian.com/cloud/bitbucket/swagger.v3.json?_v=2.300.9-0.1294.0-openapi-search.yml
      - type: APIs.io Search
        url: overlays/bitbucket-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/bitbucket-openapi-api-evangelist-ratings.yml
    aid: atlassian:bitbucket-api
  - name: ' rest/api/3/announcementBanner/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-announcementbanner--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-announcementbanner--openapi-search.yml
  - name: ' rest/api/3/app/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-app--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-app--openapi-search.yml
  - name: ' rest/api/3/application-properties/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-application-properties--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-application-properties--openapi-search.yml
  - name: ' rest/api/3/applicationrole/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-applicationrole--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-applicationrole--openapi-search.yml
  - name: ' rest/api/3/attachment/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-attachment--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-attachment--openapi-search.yml
  - name: ' rest/api/3/auditing/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-auditing--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-auditing--openapi-search.yml
  - name: ' rest/api/3/avatar/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-avatar--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-avatar--openapi-search.yml
  - name: ' rest/api/3/classification-levels/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-classification-levels--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-classification-levels--openapi-search.yml
  - name: ' rest/api/3/comment/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-comment--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-comment--openapi-search.yml
  - name: ' rest/api/3/component/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-component--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-component--openapi-search.yml
  - name: ' rest/api/3/configuration/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-configuration--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-configuration--openapi-search.yml
  - name: ' rest/api/3/customFieldOption/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-customfieldoption--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-customfieldoption--openapi-search.yml
  - name: ' rest/api/3/dashboard/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-dashboard--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-dashboard--openapi-search.yml
  - name: ' rest/api/3/data-policy/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-data-policy--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-data-policy--openapi-search.yml
  - name: ' rest/api/3/events/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-events--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-events--openapi-search.yml
  - name: ' rest/api/3/expression/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-expression--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-expression--openapi-search.yml
  - name: ' rest/api/3/field/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-field--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-field--openapi-search.yml
  - name: ' rest/api/3/fieldconfiguration/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-fieldconfiguration--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-fieldconfiguration--openapi-search.yml
  - name: ' rest/api/3/fieldconfigurationscheme/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-fieldconfigurationscheme--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-fieldconfigurationscheme--openapi-search.yml
  - name: ' rest/api/3/filter/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-filter--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-filter--openapi-search.yml
  - name: ' rest/api/3/group/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-group--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-group--openapi-search.yml
  - name: ' rest/api/3/groups/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-groups--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-groups--openapi-search.yml
  - name: ' rest/api/3/groupuserpicker/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-groupuserpicker--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-groupuserpicker--openapi-search.yml
  - name: ' rest/api/3/instance/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-instance--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-instance--openapi-search.yml
  - name: ' rest/api/3/issue/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issue--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issue--openapi-search.yml
  - name: ' rest/api/3/issueLink/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuelink--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuelink--openapi-search.yml
  - name: ' rest/api/3/issueLinkType/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuelinktype--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuelinktype--openapi-search.yml
  - name: ' rest/api/3/issueLinkType/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuelinktype--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuelinktype--openapi-search.yml
  - name: ' rest/api/3/issues/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issues--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issues--openapi-search.yml
  - name: ' rest/api/3/issuesecurityschemes/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-issuesecurityschemes--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuesecurityschemes--openapi-search.yml
  - name: ' rest/api/3/issuetype/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuetype--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuetype--openapi-search.yml
  - name: ' rest/api/3/issuetypescheme/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuetypescheme--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuetypescheme--openapi-search.yml
  - name: ' rest/api/3/issuetypescreenscheme/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-issuetypescreenscheme--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-issuetypescreenscheme--openapi-search.yml
  - name: ' rest/api/3/jql/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-jql--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-jql--openapi-search.yml
  - name: ' rest/api/3/label/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-label--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-label--openapi-search.yml
  - name: ' rest/api/3/license/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-license--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-license--openapi-search.yml
  - name: ' rest/api/3/mypermissions/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-mypermissions--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-mypermissions--openapi-search.yml
  - name: ' rest/api/3/mypreferences/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-mypreferences--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-mypreferences--openapi-search.yml
  - name: ' rest/api/3/myself/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-myself--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-myself--openapi-search.yml
  - name: ' rest/api/3/notificationscheme/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-notificationscheme--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-notificationscheme--openapi-search.yml
  - name: ' rest/api/3/permissions/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-permissions--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-permissions--openapi-search.yml
  - name: ' rest/api/3/permissionscheme/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-permissionscheme--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-permissionscheme--openapi-search.yml
  - name: ' rest/api/3/priority/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-priority--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-priority--openapi-search.yml
  - name: ' rest/api/3/project/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-project--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-project--openapi-search.yml
  - name: ' rest/api/3/projectCategory/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-projectcategory--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-projectcategory--openapi-search.yml
  - name: ' rest/api/3/projectvalidate/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-projectvalidate--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-projectvalidate--openapi-search.yml
  - name: ' rest/api/3/resolution/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-resolution--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-resolution--openapi-search.yml
  - name: ' rest/api/3/role/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-role--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-role--openapi-search.yml
  - name: ' rest/api/3/screens/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-screens--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-screens--openapi-search.yml
  - name: ' rest/api/3/screenscheme/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-screenscheme--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-screenscheme--openapi-search.yml
  - name: ' rest/api/3/search/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-search--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-search--openapi-search.yml
  - name: ' rest/api/3/securitylevel/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-securitylevel--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-securitylevel--openapi-search.yml
  - name: ' rest/api/3/serverInfo/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-serverinfo--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-serverinfo--openapi-search.yml
  - name: ' rest/api/3/settings/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-settings--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-settings--openapi-search.yml
  - name: ' rest/api/3/status/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-status--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-status--openapi-search.yml
  - name: ' rest/api/3/statuscategory/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-statuscategory--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-statuscategory--openapi-search.yml
  - name: ' rest/api/3/statuses/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-statuses--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-statuses--openapi-search.yml
  - name: ' rest/api/3/task/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-task--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-task--openapi-search.yml
  - name: ' rest/api/3/uiModifications/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-uimodifications--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-uimodifications--openapi-search.yml
  - name: ' rest/api/3/universal avatar/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-universal-avatar--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-universal-avatar--openapi-search.yml
  - name: ' rest/api/3/user/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-user--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-user--openapi-search.yml
  - name: ' rest/api/3/users/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-users--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-users--openapi-search.yml
  - name: ' rest/api/3/version/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-version--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-version--openapi-search.yml
  - name: ' rest/api/3/webhook/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-webhook--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-webhook--openapi-search.yml
  - name: ' rest/api/3/workflow/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-workflow--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-workflow--openapi-search.yml
  - name: ' rest/api/3/workflows/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-workflows--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-workflows--openapi-search.yml
  - name: ' rest/api/3/workflowscheme/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-workflowscheme--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-workflowscheme--openapi-search.yml
  - name: ' rest/api/3/worklog/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-worklog--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-worklog--openapi-search.yml
  - name: ' rest/atlassian-connect/1/addons/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-addons--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-atlassian-connect-1-addons--openapi-search.yml
  - name: ' rest/atlassian-connect/1/app/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-app--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-atlassian-connect-1-app--openapi-search.yml
  - name: ' rest/atlassian-connect/1/migration/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-migration--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-atlassian-connect-1-migration--openapi-search.yml
  - name: ' rest/atlassian-connect/1/service-registry/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-service-registry--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-atlassian-connect-1-service-registry--openapi-search.yml
  - name: ' rest/forge/1/app/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-forge-1-app--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-forge-1-app--openapi-search.yml
  - name: ' wiki/rest/api/audit/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-audit--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-audit--openapi-search.yml
  - name: ' wiki/rest/api/content/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-content--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-content--openapi-search.yml
  - name: ' wiki/rest/api/content-states/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-wiki-rest-api-content-states--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-content-states--openapi-search.yml
  - name: ' wiki/rest/api/contentbody/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-contentbody--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-contentbody--openapi-search.yml
  - name: ' wiki/rest/api/inlinetasks/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-inlinetasks--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-inlinetasks--openapi-search.yml
  - name: ' wiki/rest/api/label/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-label--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-label--openapi-search.yml
  - name: ' wiki/rest/api/group/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-group--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-group--openapi-search.yml
  - name: ' wiki/rest/api/longtask/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-longtask--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-longtask--openapi-search.yml
  - name: ' wiki/rest/api/relation/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-relation--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-relation--openapi-search.yml
  - name: ' wiki/rest/api/search/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-search--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-search--openapi-search.yml
  - name: ' wiki/rest/api/settings/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-settings--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-settings--openapi-search.yml
  - name: ' wiki/rest/api/space/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-space--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-space--openapi-search.yml
  - name: ' wiki/rest/api/template/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-template--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-template--openapi-search.yml
  - name: ' wiki/rest/api/user/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-user--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-user--openapi-search.yml
  - name: ' atlassian-connect/1/app/module/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-atlassian-connect-1-app-module--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-atlassian-connect-1-app-module--openapi-search.yml
  - name: ' wiki/rest/api/analytics/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-analytics--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-analytics--openapi-search.yml
  - name: ' addon/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-addon--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-addon--openapi-search.yml
  - name: ' hook events/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-hook-events--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-hook-events--openapi-search.yml
  - name: ' pullrequests/{selected user}/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-pullrequests-selected-user--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-pullrequests-selected-user--openapi-search.yml
  - name: ' repositories/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-repositories--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-repositories--openapi-search.yml
  - name: ' snippets/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-snippets--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-snippets--openapi-search.yml
  - name: ' teams/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-teams--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-teams--openapi-search.yml
  - name: ' user'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-user-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-user-openapi-search.yml
  - name: ' workspaces/'
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-workspaces--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-workspaces--openapi-search.yml
common:
  - type: Status
    url: https://status.developer.atlassian.com/
  - type: Blog
    url: https://blog.developer.atlassian.com/
  - type: Road Map
    url: https://trello.com/b/z2GIJ3xD/forge-roadmap-for-developers
  - type: Marketplace
    url: https://marketplace.atlassian.com/
  - type: Support
    url: https://developer.atlassian.com/support
  - type: Login
    url: https://id.atlassian.com/login
  - type: Signup
    url: https://id.atlassian.com/signup
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: atlassian

---
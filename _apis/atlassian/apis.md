name: Atlassian
description: >-
  Atlassian Corporation is an Australian software company that develops products
  for software developers, project managers and other software development
  teams.
url: https://raw.githubusercontent.com/api-search/code/main/_apis/atlassian/apis.md
created: 2024/04/14
modified: '2024-07-03'
specificationVersion: '0.18'
tags: []
apis:
  - name: Atlassian Jira Announcement Banner API
    description: >-
      This API resource provides the functionality to retrieve and update
      configuration settings for an announcement banner on a website or
      application. Users can access this resource to manage the appearance and
      content of the banner displayed to their audience.
    tags:
      - Announcement
      - Banner
      - Configurations
      - REST
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-announcementbanner--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-announcement-banner/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-announcementbanner--openapi-search.yml
      - type: API Evangelist Ratings
        url: >-
          overlays/atlassian-rest-api-3-announcementbanner--openapi-api-evangelist-ratings.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-announcement-banner/#api-group-announcement-banner
    aid: atlassian:atlassian-jira-announcement-banner-api
  - name: Atlassian Jira App API
    description: >-
      This resource represents the values of custom fields added by Forge apps.
      Use it to update the value of a custom field on issues.
    tags:
      - Applications
      - Custom
      - Fields
      - REST
      - Value
      - Configurations
      - Context
      - Keys
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-app--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-custom-field-values--apps-/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-app--openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/atlassian-rest-api-3-app--openapi-api-evangelist-ratings.yml
    aid: atlassian:atlassian-jira-app-api
  - name: Atlassian Jira Application Properties API
    description: >-
      This resource represents app properties. Use it to store arbitrary data
      for your Connect app.
    tags:
      - Advanced
      - Applications
      - Properties
      - REST
      - Settings
      - Sets
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-application-properties--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-app-properties/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-application-properties--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-app-properties/#api-group-app-properties
    aid: atlassian:atlassian-jira-application-properties-api
  - name: Atlassian Jira Application Role API
    description: >-
      This resource represents application roles. Use it to get details of an
      application role or all application roles.
    tags:
      - Application Roles
      - Applications
      - Keys
      - REST
      - Roles
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-applicationrole--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-application-roles/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-applicationrole--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-application-roles/#api-group-application-roles
    aid: atlassian:atlassian-jira-application-role-api
  - name: Atlassian Jira Attachment API
    description: >-
      This resource represents issue attachments and the attachment settings for
      Jira. Use it to get the metadata for an attachment, delete an attachment,
      and view the metadata for the contents of an attachment. Also, use it to
      get the attachment settings for Jira.
    tags:
      - Attachments
      - Content
      - REST
      - Jira
      - Meta
      - Settings
      - Thumbnails
      - Metadata
      - Expand
      - Expanded
      - Human
      - Contents
      - Raw
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-attachment--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-attachments/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-attachment--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-attachments/#api-group-issue-attachments
    aid: atlassian:atlassian-jira-attachment-api
  - name: Atlassian Jira Auditing API
    description: >+
      Atlassian Audit (Advanced Auditing for DC customers) is a cross-product
      feature available in Atlassian DC products (Bitbucket, Confluence, and
      Jira) which is responsible for storing and retrieving audited events.

    tags:
      - Audit
      - Auditing
      - REST
      - Record
      - Records
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-auditing--openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/server/framework/atlassian-sdk/audit/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-auditing--openapi-search.yml
    humanURL: https://developer.atlassian.com/server/framework/atlassian-sdk/audit/
    aid: atlassian:atlassian-jira-auditing-api
  - name: Atlassian Jira Avatar API
    description: >-
      This resource represents system and custom avatars. Use it to obtain the
      details of system or custom avatars, add and remove avatars from a project
      or issue type, and obtain avatar images.
    tags:
      - Avatars
      - Systems
      - Types
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-avatar--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-avatars/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-avatar--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-avatars/#api-group-avatars
    aid: atlassian:atlassian-jira-avatar-api
  - name: Atlassian Jira Classification Levels API
    description: Use to manage the classification levels that are used across Jira.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-classification-levels--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-classification-levels/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-classification-levels--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-classification-levels/#api-group-classification-levels
    aid: atlassian:atlassian-jira-classification-levels-api
  - name: Atlassian Jira Comment API
    description: >-
      This resource represents issue comments. Use it to get, create, update,
      and delete a comment from an issue, get all comments from issue, get a
      list of comments by comment ID.
    tags:
      - Comments
      - IDs
      - REST
      - Keys
      - Properties
      - Sets
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-comment--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-comments/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-comment--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-comments/#api-group-issue-comments
    aid: atlassian:atlassian-jira-comment-api
  - name: Atlassian Jira Component API
    description: >-
      This resource represents project components. Use it to get, create,
      update, and delete project components. Also get components for project and
      get a count of issues by component.
    tags:
      - Components
      - REST
      - Count
      - Counts
      - Issues
      - Related
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-component--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-components/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-component--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-components/#api-group-project-components
    aid: atlassian:atlassian-jira-component-api
  - name: Atlassian Jira Configuration API
    description: >-
      This resource represents various settings in Jira. Use it to get and
      update Jira settings and properties.
    tags:
      - Configurations
      - Providers
      - REST
      - Selected
      - Time
      - Time Tracking
      - Tracking
      - Options
      - Settings
      - Sets
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-configuration--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-jira-settings/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-configuration--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-jira-settings/#api-group-jira-settings
    aid: atlassian:atlassian-jira-configuration-api
  - name: Atlassian Jira Custom Field Option API
    description: >-
      This resource represents custom issue field select list options created in
      Jira or using the REST API. This resource supports the following field
      types Checkboxes, Radio Buttons, Select List (single choice), Select List
      (multiple choices), Select List (cascading).
    tags:
      - Custom
      - Fields
      - Options
      - REST
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-customfieldoption--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-custom-field-options/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-customfieldoption--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-custom-field-options/#api-group-issue-custom-field-options
    aid: atlassian:atlassian-jira-custom-field-option-api
  - name: Atlassian Jira Dashboard API
    description: >-
      This resource represents dashboards. Use it to obtain the details of
      dashboards as well as get, create, update, or remove item properties and
      gadgets from dashboards.
    tags:
      - Bulk
      - Dashboard
      - Dashboards
      - Edit
      - REST
      - Available
      - Gadgets
      - Search
      - Removes
      - Items
      - Keys
      - Properties
      - Sets
      - Copy
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-dashboard--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-dashboards/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-dashboard--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-dashboards/#api-group-dashboards
    aid: atlassian:atlassian-jira-dashboard-api
  - name: Atlassian Jira Data Policy API
    description: >+
      Atlassian is adding the ability for customers to block app access to data
      using data security policies with app access rules. App access rules may
      affect your app by blocking its access to certain data. This guide
      provides an overview of potential impacts to apps and how to address them.

    tags:
      - EAP
      - Data
      - Policies
      - Projects
      - REST
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-data-policy--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/data-security-policy-developer-guide/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-data-policy--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/data-security-policy-developer-guide/
    aid: atlassian:atlassian-jira-data-policy-api
  - name: Atlassian Jira Events API
    description: >-
      Used to manage events that are aavailable across the resources made
      available via Jira API.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-events--openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/platform/forge/events-reference/jira/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-events--openapi-search.yml
    humanURL: https://developer.atlassian.com/platform/forge/events-reference/jira/
    aid: atlassian:atlassian-jira-events-api
  - name: Atlassian Jira Expression API
    description: >-
      Jira expressions is a domain-specific language designed with Jira in mind,
      evaluated on the Jira Cloud side. It can be used to evaluate custom code
      in the context of Jira entities.
    tags:
      - Analysis
      - Expression
      - Jira
      - REST
      - EULA
      - Evaluate
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-expression--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-jira-expressions/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-expression--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-jira-expressions/#api-group-jira-expressions
    aid: atlassian:atlassian-jira-expression-api
  - name: Atlassian Jira Field API
    description: >-
      This resource represents issue fields, both system and custom fields. Use
      it to get fields, field configurations, and create custom fields.
    tags:
      - Fields
      - Paginated
      - REST
      - Search
      - Trash
      - Trashed
      - Custom
      - Context
      - Contexts
      - Default
      - Value
      - Values
      - Sets
      - Issue Type Mappings
      - Issues
      - Types
      - Mapping
      - Projects
      - Project Mappings
      - Issue Types
      - Removes
      - (context)
      - Options
      - Move
      - Reorder
      - Assign
      - Screens
      - Keys
      - Edit
      - Selectable
      - Suggestions
      - Visible
      - Replace
      - Restore
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-field--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-fields/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-field--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-fields/#api-group-issue-fields
    aid: atlassian:atlassian-jira-field-api
  - name: Atlassian Jira Field Configuration API
    description: >-
      This resource represents issue field configurations. Use it to get, set,
      and delete field configurations and field configuration schemes.
    tags:
      - Configurations
      - Field Configurations
      - Fields
      - REST
      - Items
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-fieldconfiguration--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-field-configurations/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-fieldconfiguration--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-field-configurations/#api-group-issue-field-configurations
    aid: atlassian:atlassian-jira-field-configuration-api
  - name: Atlassian Jira Field Configuration Scheme API
    description: >-
      This resource represents issue field configurations. Use it to get, set,
      and delete field configurations and field configuration schemes.
    tags:
      - Configurations
      - Field Configuration Scheme
      - Fields
      - Issues
      - Items
      - Mapping
      - REST
      - Types
      - Projects
      - Schemes
      - Assign
      - Removes
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-fieldconfigurationscheme--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-field-configurations/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-fieldconfigurationscheme--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-field-configurations/#api-group-issue-field-configurations
    aid: atlassian:atlassian-jira-field-configuration-scheme-api
  - name: Atlassian Jira Filter API
    description: >-

      Postman Collection

      OpenAPI

      This resource represents filters. Use it to get, create, update, or delete
      filters. Also use it to configure the columns for a filter and set
      favorite filters.
    tags:
      - Default
      - Filter
      - REST
      - Scopes
      - Share
      - Sets
      - Favorite
      - Favourite
      - Filters
      - Search
      - Columns
      - Reset
      - Removes
      - Change
      - Owners
      - Permission
      - Permissions
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-filter--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-filters/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-filter--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-filters/#api-group-filters
    aid: atlassian:atlassian-jira-filter-api
  - name: Atlassian Jira Group API
    description: >-
      This resource represents groups of users. Use it to get, create, find, and
      delete groups as well as add and remove users from groups. ([WARNING] The
      standard Atlassian group names are default names only and can be edited or
      deleted. 
    tags:
      - Bulk
      - Groups
      - REST
      - Members
      - Users
      - Removes
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-group--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-groups/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-group--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-groups/#api-group-groups
    aid: atlassian:atlassian-jira-group-api
  - name: Atlassian Jira Groups API
    description: >-
      This resource represents groups of users. Use it to get, create, find, and
      delete groups as well as add and remove users from groups. ([WARNING] The
      standard Atlassian group names are default names only and can be edited or
      deleted. 
    tags:
      - Find
      - Groups
      - Picker
      - REST
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-groups--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-groups/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-groups--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-groups/#api-group-groups
    aid: atlassian:atlassian-jira-groups-api
  - name: Atlassian Jira Group User Picker API
    description: >-
      This resource represents a list of users and a list of groups. Use it to
      obtain the details to populate user and group picker suggestions list.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-groupuserpicker--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-group-and-user-picker/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-groupuserpicker--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-group-and-user-picker/#api-group-group-and-user-picker
    aid: atlassian:atlassian-jira-group-user-picker-api
  - name: Atlassian Jira License Metrics API
    description: >-
      This resource represents license metrics. Use it to get available metrics
      for Jira licences.
    tags:
      - Instances
      - Licenses
      - REST
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-instance--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-license-metrics/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-instance--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-license-metrics/#api-group-license-metrics
    aid: atlassian:atlassian-jira-license-metrics-api
  - name: Atlassian Jira Issue API
    description: Used to managine issues for Jira resources.
    tags:
      - Archive
      - Issues
      - JQL
      - REST
      - ID/key
      - Bulk
      - Meta
      - Metadata
      - Issue Types
      - Keys
      - Projects
      - Types
      - Fields
      - Picker
      - Suggestions
      - Properties
      - Sets
      - Multi
      - Keys/ID
      - Unarchive
      - Is
      - Watching
      - Edit
      - Assign
      - Assignee
      - Attachments
      - Change Logs
      - IDs
      - Comments
      - Notifications
      - Notify
      - Send
      - Global
      - ID
      - Link
      - Remote
      - Remote Links
      - Links
      - Transitions
      - Votes
      - Watchers
      - Worklogs
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issue--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issues/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issue--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issues/#api-group-issues
    aid: atlassian:atlassian-jira-issue-api
  - name: Atlassian Jira Issue Link API
    description: >-
      This resource represents links between issues. Use it to get, create, and
      delete links between issues.
    tags:
      - Issues
      - Link
      - REST
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuelink--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-links/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuelink--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-links/#api-group-issue-links
    aid: atlassian:atlassian-jira-issue-link-api
  - name: Atlassian Jira Issue Link Type API
    description: >-
      This resource represents links between issues. Use it to get, create, and
      delete links between issues.
    tags:
      - Issues
      - Link
      - REST
      - Types
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuelinktype--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-links/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuelinktype--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-links/#api-group-issue-links
    aid: atlassian:atlassian-jira-issue-link-type-api
  - name: Atlassian Jira Issue Link Type API
    description: >+
      This resource represents issue link types. Use it to get, create, update,
      and delete link issue types as well as get lists of all link issue types.

    tags:
      - Issues
      - Link
      - REST
      - Types
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuelinktype--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issue-link-types/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuelinktype--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issue-link-types/#api-group-issue-link-types
    aid: atlassian:atlassian-jira-issue-link-type-api
  - name: Atlassian Jira Issues API
    description: This is for managing the issues across Jira resources.
    tags:
      - Archive
      - Archived
      - Exports
      - Issues
      - REST
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issues--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issues/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issues--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issues/#api-group-issues
    aid: atlassian:atlassian-jira-issues-api
  - name: Atlassian Jira Issue Security Schemes API
    description: >-
      This resource represents issue security schemes. Use it to get an issue
      security scheme or a list of issue security schemes. Issue security
      schemes control which users or groups of users can view an issue. When an
      issue security scheme is associated with a project, its security levels
      can be applied to issues in that project. Sub-tasks also inherit the
      security level of their parent issue.
    tags:
      - Issue Security Schemes
      - Issues
      - Levels
      - REST
      - Security
      - Default
      - Sets
      - Members
      - Projects
      - Schemes
      - Using
      - Associate
      - Search
      - Removes
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-issuesecurityschemes--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-security-schemes/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuesecurityschemes--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-security-schemes/#api-group-issue-security-schemes
    aid: atlassian:atlassian-jira-issue-security-schemes-api
  - name: Atlassian Jira Issue Type API
    description: >-
      This resource represents issues types. Use it to get, create, update, and
      delete issue types, get all issue types for a user, get alternative issue
      types, and set an avatar for an issue type.
    tags:
      - Issue Types
      - Issues
      - Projects
      - REST
      - Types
      - Alternatives
      - Avatars
      - Load
      - Keys
      - Properties
      - Sets
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuetype--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issue-types/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuetype--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issue-types/#api-group-issue-types
    aid: atlassian:atlassian-jira-issue-type-api
  - name: Atlassian Jira Issue Type Scheme API
    description: >-
      This resource represents issue type schemes in classic projects. Use it to
      get issue type schemes and a list of the projects that use them, associate
      issue type schemes with projects, add issue types to issue type schemes,
      delete issue types from issue type schemes, create, update, and delete
      issue type schemes, change the order of issue types in issue type schemes.
    tags:
      - Issue Type Schemes
      - Issues
      - Items
      - Mapping
      - REST
      - Schemes
      - Types
      - Projects
      - Assign
      - Issue Types
      - Change
      - Move
      - Orders
      - Removes
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-issuetypescheme--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-type-schemes/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-issuetypescheme--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-type-schemes/#api-group-issue-type-schemes
    aid: atlassian:atlassian-jira-issue-type-scheme-api
  - name: Atlassian Jira Issue Type Screen Scheme API
    description: >-
      This resource represents issue type screen schemes. Use it to get issue
      type screen schemes and a list of the projects that use them, create issue
      type screen schemes, update issue type screen schemes, delete issue type
      screen schemes, associate issue type screen schemes with projects, append
      issue type to screen scheme mappings to issue type screen schemes, remove
      issue type to screen scheme mappings from issue type screen schemes.,
      update default screen scheme of issue type screen scheme.
    tags:
      - Issue Type Screen Schemes
      - Issues
      - Items
      - Mapping
      - REST
      - Schemes
      - Screen
      - Types
      - Projects
      - Assign
      - Append
      - Default
      - Removes
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-issuetypescreenscheme--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-type-screen-schemes/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-api-3-issuetypescreenscheme--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-type-screen-schemes/#api-group-issue-type-screen-schemes
    aid: atlassian:atlassian-jira-issue-type-screen-scheme-api
  - name: Atlassian Jira Jql API
    description: >-
      This resource represents various ways to search for issues. Use it to
      search for issues with a JQL query and find issues to populate an issue
      picker.
    tags:
      - (GET)
      - Autocomplete Data
      - Data
      - Fields
      - JQL
      - REST
      - References
      - (POST)
      - Auto
      - Complete
      - Suggestions
      - (apps)
      - Computation
      - Functions
      - Pre Computations
      - Against
      - Checks
      - Issues
      - Match
      - Parse
      - Queries
      - Accounts
      - Convert
      - IDs
      - Users
      - Sanitize
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-jql--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-search/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-jql--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-search/#api-group-issue-search
    aid: atlassian:atlassian-jira-jql-api
  - name: Atlassian Jira Label API
    description: >-
      This resource represents available labels. Use it to get available labels
      for the global label field.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-label--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-labels/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-label--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-labels/#api-group-labels
    aid: atlassian:atlassian-jira-label-api
  - name: Atlassian Jira License API
    description: >+
      Atlassian Connect provides a set of REST APIs specifically designed for
      use by cloud apps. Requests to these resources are made against the Jira
      or Confluence Cloud instance, not the Marketplace API.

    tags:
      - Approximate
      - Count
      - Licenses
      - REST
      - Applications
      - Keys
      - Products
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-license--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/platform/marketplace/license-api-for-cloud-apps/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-license--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/platform/marketplace/license-api-for-cloud-apps/
    aid: atlassian:atlassian-jira-license-api
  - name: Atlassian Jira My Permissions API
    description: >-
      This resource represents permissions. Use it to obtain details of all
      permissions and determine whether the user has certain permissions.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-mypermissions--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permissions/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-mypermissions--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permissions/#api-group-permissions
    aid: atlassian:atlassian-jira-my-permissions-api
  - name: Atlassian Jira My Preferences API
    description: >-
      This resource represents information about the current user, such as basic
      details, group membership, application roles, preferences, and locale. Use
      it to get, create, update, and delete (restore default) values of the
      user's preferences and locale.
    tags:
      - Locales
      - Prferences
      - REST
      - Sets
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-mypreferences--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-myself/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-mypreferences--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-myself/#api-group-myself
    aid: atlassian:atlassian-jira-my-preferences-api
  - name: Atlassian Jira Myself API
    description: >-
      This resource represents information about the current user, such as basic
      details, group membership, application roles, preferences, and locale. Use
      it to get, create, update, and delete (restore default) values of the
      user's preferences and locale.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-myself--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-myself/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-myself--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-myself/#api-group-myself
    aid: atlassian:atlassian-jira-myself-api
  - name: Atlassian Jira Notification Scheme API
    description: >-
      This resource represents notification schemes, lists of events and the
      recipients who will receive notifications for those events. Use it to get
      details of a notification scheme and a list of notification schemes.
    tags:
      - Notifications
      - Notificationscheme
      - Paginated
      - Projects
      - REST
      - Schemes
      - Using
      - Removes
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-api-3-notificationscheme--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-notification-schemes/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-notificationscheme--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-notification-schemes/#api-group-issue-notification-schemes
    aid: atlassian:atlassian-jira-notification-scheme-api
  - name: Atlassian Jira Permissions API
    description: >-
      This resource represents permissions. Use it to obtain details of all
      permissions and determine whether the user has certain permissions.
    tags:
      - Bulk
      - Checks
      - Permissions
      - REST
      - Permitted
      - Projects
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-permissions--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permissions/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-permissions--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-permissions/#api-group-permissions
    aid: atlassian:atlassian-jira-permissions-api
  - name: Atlassian Jira Permission Scheme API
    description: >-
      This resource represents permission schemes for a project. Use this
      resource to get details of a project's issue security levels available to
      the calling user, get the permission scheme associated with the project or
      assign different permission scheme to the project, get details of a
      project's issue security scheme.
    tags:
      - Permission
      - Permission Schemes
      - REST
      - Schemes
      - Grants
      - Grants""
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-permissionscheme--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-permission-schemes/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-permissionscheme--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-permission-schemes/#api-group-project-permission-schemes
    aid: atlassian:atlassian-jira-permission-scheme-api
  - name: Atlassian Jira Priority API
    description: >-
      his resource represents issue priorities. Use it to get, create and update
      issue priorities and details for individual issue priorities.
    tags:
      - Default
      - Priorities
      - REST
      - Sets
      - Move
      - Search
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-priority--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issue-priorities/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-priority--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-issue-priorities/#api-group-issue-priorities
    aid: atlassian:atlassian-jira-priority-api
  - name: Atlassian Jira Project API
    description: >-
      This resource represents projects. Use it to get, create, update, and
      delete projects. Also get statuses available to a project, a project's
      notification schemes, and update a project's type.
    tags:
      - Projects
      - REST
      - Recent
      - Paginated
      - Search
      - Types
      - Accessible
      - Licensed
      - Keys
      - Archive
      - Avatars
      - Sets
      - Load
      - Classifications
      - Data
      - Default
      - Levels
      - Removes
      - Components
      - Asynchronously
      - Features
      - Feature
      - States
      - Properties
      - Archived
      - Restore
      - Roles
      - Actors
      - Details
      - Role Details
      - Statuses
      - Versions
      - Emails
      - Project's
      - Sender
      - Hierarchy
      - Issues
      - Issue Security Level Scheme
      - Schemes
      - Security
      - Notifications
      - Notificationscheme
      - Assigned
      - Permission
      - Permission Schemes
      - Assign
      - Security Levels
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-project--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-projects/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-project--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-projects/#api-group-projects
    aid: atlassian:atlassian-jira-project-api
  - name: Atlassian Jira Project Category API
    description: >-
      This resource represents project categories. Use it to create, update, and
      delete project categories as well as obtain a list of all project
      categories and details of individual categories. For more information on
      managing project categories, see Adding, assigning, and deleting project
      categories.
    tags:
      - Categories
      - Projects
      - REST
      - ID
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-projectcategory--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-categories/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-projectcategory--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-categories/#api-group-project-categories
    aid: atlassian:atlassian-jira-project-category-api
  - name: Atlassian Jira Project Validate API
    description: This resource provides validation for project keys and names.
    tags:
      - Ate
      - Keys
      - Projects
      - Projectval
      - REST
      - Validate
      - Val
      - Valid
      - Names
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-projectvalidate--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-key-and-name-validation/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-projectvalidate--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-key-and-name-validation/#api-group-project-key-and-name-validation
    aid: atlassian:atlassian-jira-project-validate-api
  - name: Atlassian Jira Resolution API
    description: >-
      This resource represents issue resolution values. Use it to obtain a list
      of all issue resolution values and the details of individual resolution
      values.
    tags:
      - Default
      - REST
      - Resolutions
      - Sets
      - Move
      - Search
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-resolution--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-resolutions/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-resolution--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-resolutions/#api-group-issue-resolutions
    aid: atlassian:atlassian-jira-resolution-api
  - name: Atlassian Jira Role API
    description: >-
      This resource represents the roles that users can play in projects. Use
      this resource to get, create, update, and delete project roles.
    tags:
      - Projects
      - REST
      - Roles
      - ID
      - Partial
      - Actors
      - Default
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-role--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-project-roles/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-role--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-project-roles/#api-group-project-roles
    aid: atlassian:atlassian-jira-role-api
  - name: Atlassian Jira Screens API
    description: >-
      This resource represents the screens used to record issue details. Use it
      to get details of all screens, get details of all the fields available for
      use on screens, create screens, delete screens, update screens, add a
      field to the default screen.
    tags:
      - Default
      - Fields
      - REST
      - Screen
      - Screens
      - Bulk
      - Tabs
      - Available
      - Removes
      - Move
      - POS
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-screens--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-screens/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-screens--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-screens/
    aid: atlassian:atlassian-jira-screens-api
  - name: Atlassian Jira Screens Scheme API
    description: >-
      This resource represents screen schemes in classic projects. Use it to
      get, create, update, and delete screen schemes.
    tags:
      - REST
      - Schemes
      - Screen
      - Screen Scheme
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-screenscheme--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-screen-schemes/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-screenscheme--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-screen-schemes/#api-group-screen-schemes
    aid: atlassian:atlassian-jira-screens-scheme-api
  - name: Atlassian Jira Search API
    description: >-
      This resource represents various ways to search for issues. Use it to
      search for issues with a JQL query and find issues to populate an issue
      picker.
    tags:
      - IDs
      - Issues
      - JQL
      - REST
      - Search
      - Using
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-search--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-search/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-search--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-search/#api-group-issue-search
    aid: atlassian:atlassian-jira-search-api
  - name: Atlassian Jira Security Level API
    description: >-
      This resource represents issue security levels. Use it to obtain the
      details of any issue security level. For more information about issue
      security levels, see Configuring issue-level security.
    tags:
      - Issues
      - Levels
      - REST
      - Security
      - Security Levels
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-securitylevel--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-security-level/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-securitylevel--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-security-level/#api-group-issue-security-level
    aid: atlassian:atlassian-jira-security-level-api
  - name: Atlassian Jira Server Info API
    description: This resource provides information about the Jira instance.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-serverinfo--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-server-info/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-serverinfo--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-server-info/#api-group-server-info
    aid: atlassian:atlassian-jira-server-info-api
  - name: Atlassian Jira Settings API
    description: >-
      This resource represents various settings in Jira. Use it to get and
      update Jira settings and properties.
    tags:
      - Columns
      - Default
      - Issues
      - Navigators
      - REST
      - Settings
      - Sets
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-settings--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-jira-settings/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-settings--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-jira-settings/#api-group-jira-settings
    aid: atlassian:atlassian-jira-settings-api
  - name: Atlassian Jira Status API
    description: >-
      This resource represents issue workflow statuses. Use it to obtain a list
      of all statuses associated with workflows and the details of a status.
    tags:
      - Names
      - REST
      - Status
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-status--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-statuses/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-status--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-statuses/#api-rest-api-3-status-get
    aid: atlassian:atlassian-jira-status-api
  - name: Atlassian Jira Status Category API
    description: >-
      This resource represents status categories. Use it to obtain a list of all
      status categories and the details of a category. Status categories
      provided a mechanism for categorizing statuses.
    tags:
      - Categories
      - Keys
      - REST
      - Status
      - Status Categories
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-statuscategory--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-status-categories/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-statuscategory--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-status-categories/#api-group-workflow-status-categories
    aid: atlassian:atlassian-jira-status-category-api
  - name: Atlassian Jira Statuses API
    description: >-
      This resource represents issue workflow statuses. Use it to obtain a list
      of all statuses associated with workflows and the details of a status.
    tags:
      - Paginated
      - REST
      - Search
      - Statuses
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-statuses--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-statuses/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-statuses--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflow-statuses/#api-rest-api-3-status-get
    aid: atlassian:atlassian-jira-statuses-api
  - name: Atlassian Jira Task API
    description: >-
      This resource represents a long-running asynchronous tasks. Use it to
      obtain details about the progress of a long-running task or cancel a
      long-running task.
    tags:
      - REST
      - Tasks
      - Cancel
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-task--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-tasks/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-task--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-tasks/#api-group-tasks
    aid: atlassian:atlassian-jira-task-api
  - name: Atlassian Jira UI Modifications API
    description: >-
      UI modifications is a feature available for Forge apps only. It enables
      Forge apps to control how selected Jira fields behave on the following
      views: global issue create, issue view. For example: hide specific fields,
      set them as required, etc.
    tags:
      - Modifications
      - REST
      - UI
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-uimodifications--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-ui-modifications--apps-/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-uimodifications--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-ui-modifications--apps-/#api-group-ui-modifications--apps-
    aid: atlassian:atlassian-jira-ui-modifications-api
  - name: Atlassian Jira Universal Avatar API
    description: >-
      This resource represents system and custom avatars. Use it to obtain the
      details of system or custom avatars, add and remove avatars from a project
      or issue type, and obtain avatar images.
    tags:
      - Avatars
      - Entities
      - Owners
      - REST
      - Types
      - Universal
      - Load
      - Objects
      - Owning
      - Images
      - View
      - ID
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-universal-avatar--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-avatars/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-universal-avatar--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-avatars/#api-group-avatars
    aid: atlassian:atlassian-jira-universal-avatar-api
  - name: Atlassian Jira User API
    description: >-
      This resource represent users. Use it to get, get a list of, create, and
      delete users, get, set, and reset a user's default issue table columns,
      get a list of the groups the user belongs to, and get a list of user
      account IDs for a list of usernames or user keys.
    tags:
      - Assignable
      - Find
      - Multi
      - Projects
      - REST
      - Search
      - Users
      - Issues
      - Bulk
      - Accounts
      - IDs
      - Migrations
      - Columns
      - Default
      - Reset
      - Sets
      - Emails
      - Groups
      - Permission
      - Permissions
      - Picker
      - Keys
      - Properties
      - Queries
      - Browse
      - View Issues
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-user--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-users/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-user--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-users/#api-group-users
    aid: atlassian:atlassian-jira-user-api
  - name: Atlassian Jira Users API
    description: >-
      This resource represent users. Use it to get, get a list of, create, and
      delete users, get, set, and reset a user's default issue table columns,
      get a list of the groups the user belongs to, and get a list of user
      account IDs for a list of usernames or user keys.
    tags:
      - REST
      - Search
      - Users
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-users--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-users/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-users--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-users/
    aid: atlassian:atlassian-jira-users-api
  - name: Atlassian Jira Version API
    description: >-
      This resource represents project versions. Use it to get, get lists of,
      create, update, move, merge, and delete project versions. This resource
      also provides counts of issues by version.
    tags:
      - REST
      - Versions
      - Issues
      - Merge
      - Mergeto
      - Move
      - Count
      - Counts
      - Related
      - Version's
      - Related Work
      - Work
      - Removes
      - Replace
      - Swap
      - Unresolved
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-version--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-versions/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-version--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-project-versions/#api-group-project-versions
    aid: atlassian:atlassian-jira-version-api
  - name: Atlassian Jira Webhook API
    description: >-
      A webhook is a user-defined callback over HTTP. You can use Jira webhooks
      to notify your app or web application when certain events occur in Jira.
      For example, you might want to alert your remote application when an issue
      is updated or when sprint is started. Using a webhook to do this means
      that your remote application doesn't have to periodically poll Jira (via
      the REST APIs) to determine whether changes have occurred.
    tags:
      - Failed
      - REST
      - Webhooks
      - Extend
      - Life
      - Refresh
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-webhook--openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/server/jira/platform/webhooks/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-webhook--openapi-search.yml
    humanURL: https://developer.atlassian.com/server/jira/platform/webhooks/
    aid: atlassian:atlassian-jira-webhook-api
  - name: Atlassian Jira Workflow API
    description: >-
      This resource represents workflows. Use it to Get workflows, Create
      workflows, Update workflows, Delete inactive workflows, Get workflow
      capabilities
    tags:
      - Configurations
      - REST
      - Rules
      - Transitions
      - Workflows
      - Paginated
      - Search
      - Properties
      - Entities
      - Inactive
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-workflow--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflows/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-workflow--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflows/#api-group-workflows
    aid: atlassian:atlassian-jira-workflow-api
  - name: Atlassian Jira Workflows API
    description: >-
      This resource represents workflows. Use it to Get workflows, Create
      workflows, Update workflows, Delete inactive workflows, Get workflow
      capabilities
    tags:
      - Available
      - Capabilities
      - REST
      - Workflows
      - Bulk
      - Ation
      - Val
      - Validate
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-workflows--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflows/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-workflows--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-workflows/
    aid: atlassian:atlassian-jira-workflows-api
  - name: Atlassian Jira Workflow Scheme API
    description: >-
      This resource represents workflow schemes. Use it to manage workflow
      schemes and the workflow scheme's workflows and issue types. A workflow
      scheme maps issue types to workflows. A workflow scheme can be associated
      with one or more projects, which enables the projects to use the
      workflow-issue type mappings.
    tags:
      - Associations
      - Projects
      - REST
      - Schemes
      - Workflow Scheme
      - Workflows
      - Assign
      - Bulk
      - Read
      - Mapping
      - Required
      - Status
      - Classic
      - Draft
      - Drafts
      - Default
      - Issue Types
      - Issues
      - Types
      - Sets
      - Publish
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-workflowscheme--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-workflow-schemes/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-workflowscheme--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v2/api-group-workflow-schemes/#api-group-workflow-schemes
    aid: atlassian:atlassian-jira-workflow-scheme-api
  - name: Atlassian Jira Worklog API
    description: >-
      This resource represents issue worklogs. Use it to get, create, update,
      and delete worklogs, obtain lists of updated or deleted worklogs.
    tags:
      - IDs
      - REST
      - Worklogs
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-api-3-worklog--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-worklogs/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-api-3-worklog--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-issue-worklogs/#api-group-issue-worklogs
    aid: atlassian:atlassian-jira-worklog-api
  - name: Atlassian Jira Connect Addons API
    description: >+
      Connect is a development framework for extending Atlassian cloud products.
      Connect gives you control over the tech stack, infrastructure, and
      integration with Atlassian Cloud products. You determine your security
      implementation and authentication with external cloud providers, such as
      AWS, Google Cloud, or Heroku. It handles discovery, installation,
      authentication, and seamless integration into the user interface.

    tags:
      - Addons
      - Applications
      - Atlassian
      - Connect
      - Keys
      - Properties
      - REST
      - Sets
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-addons--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/getting-started-with-connect/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-atlassian-connect-1-addons--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/getting-started-with-connect/
    aid: atlassian:atlassian-jira-connect-addons-api
  - name: Atlassian Jira Connect App API
    description: >+
      Connect is a development framework for extending Atlassian cloud products.
      Connect gives you control over the tech stack, infrastructure, and
      integration with Atlassian Cloud products. You determine your security
      implementation and authentication with external cloud providers, such as
      AWS, Google Cloud, or Heroku. It handles discovery, installation,
      authentication, and seamless integration into the user interface.

    tags:
      - Applications
      - Atlassian
      - Connect
      - Dynamic
      - Modules
      - REST
      - Removes
      - Register
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-app--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/getting-started-with-connect/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-atlassian-connect-1-app--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/getting-started-with-connect/
    aid: atlassian:atlassian-jira-connect-app-api
  - name: Atlassian Jira Connect Migration API
    description: >-
      This Atlassian Connect feature provide a mechanism for apps to signal
      readiness for new API behaviors as well as selectively enrol during the
      introduction / deprecation period for the purposes of testing. Development
      of this mechanism was motivated by the introduction of API changes that
      are not backward compatible (e.g. the removal of legacy user references
      from our public cloud REST APIs). Such changes will break existing apps
      that do not yet support the new API version.
    tags:
      - Atlassian
      - Bulk
      - Connect
      - Custom
      - Fields
      - Migrations
      - REST
      - Value
      - Entities
      - Properties
      - Types
      - Configurations
      - Rules
      - Search
      - Transitions
      - Workflows
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-migration--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/connect-api-migration/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-atlassian-connect-1-migration--openapi-search.yml
    humanURL: https://developer.atlassian.com/cloud/jira/platform/connect-api-migration/
    aid: atlassian:atlassian-jira-connect-migration-api
  - name: Atlassian Jira Connect Service Registry API
    description: >-
      This resource represents a service registry. Use it to retrieve attributes
      related to a service registry in JSM.
    tags: []
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-rest-atlassian-connect-1-service-registry--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-service-registry/
    overlays:
      - type: OpenAPI
        url: >-
          overlays/atlassian-rest-atlassian-connect-1-service-registry--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/jira/platform/rest/v3/api-group-service-registry/#api-group-service-registry
    aid: atlassian:atlassian-jira-connect-service-registry-api
  - name: Atlassian Jira Forge App API
    description: >-
      Forge is Atlassian's new development platform for building Jira and
      Confluence Cloud apps. 
    tags:
      - (Forge)
      - Applications
      - Forge
      - Keys
      - Properties
      - REST
      - Sets
    properties:
      - type: OpenAPI
        url: properties/atlassian-rest-forge-1-app--openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/cloud/jira/platform/forge/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-rest-forge-1-app--openapi-search.yml
    humanURL: https://developer.atlassian.com/cloud/jira/platform/forge/
    aid: atlassian:atlassian-jira-forge-app-api
  - name: Atlassian Confluence Audit API
    description: Allows you to create, get, set, and export audit records from Confluence.
    tags:
      - Audit
      - Exports
      - REST
      - Records
      - Wiki
      - Period
      - Retention
      - Sets
      - Since
      - Time
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-audit--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-audit/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-audit--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-audit/#api-group-audit
    aid: atlassian:atlassian-confluence-audit-api
  - name: Atlassian Confluence Content API
    description: >-
      This is the reference for the Confluence Cloud REST API v2, with
      definitions and performance intended to be an improvement over v1. You can
      click on the meatball menu in the upper right to download the spec or
      Postman collection.
    tags:
      - Archive
      - Content
      - Pages
      - REST
      - Wiki
      - Blueprints
      - Draft
      - Instances
      - Publish
      - Shared
      - Legacy
      - CQL
      - Search
      - ID
      - Page
      - Trees
      - Child
      - Children
      - Locations
      - Move
      - Positions
      - Relative
      - Targets
      - Attachments
      - Properties
      - Data
      - Download
      - URI
      - Comments
      - Types
      - Descendants
      - History
      - Body
      - Macro
      - Versions
      - Convert
      - Representation
      - Synchronously
      - Async
      - Asynchronously
      - Labels
      - Parameters
      - Queries
      - Removes
      - Using
      - Notifications
      - Watches
      - Space
      - Copy
      - Hierarchy
      - Page Hierarchy
      - Single
      - Checks
      - Permission
      - Permissions
      - Keys
      - Restrictions
      - Operation
      - Groups
      - Names
      - Status
      - Users
      - States
      - Publishes
      - Sets
      - Available
      - Restore
      - Numbers
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-content--openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/cloud/confluence/rest/v2/intro/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-content--openapi-search.yml
    humanURL: https://developer.atlassian.com/cloud/confluence/rest/v2/intro/#about
    aid: atlassian:atlassian-confluence-content-api
  - name: Atlassian Confluence Content States API
    description: Allows you to manage the various state of content published to Confluence.
    tags:
      - Bulk
      - Content
      - REST
      - Removes
      - States
      - Wiki
      - Long
      - Running
      - Settings
      - Tasks
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-wiki-rest-api-content-states--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-states/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-content-states--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-states/#api-group-content-states
    aid: atlassian:atlassian-confluence-content-states-api
  - name: Atlassian Confluence Content Body API
    description: Provides you the ability to manage the content body of Confluence pages.
    tags:
      - Body
      - Content
      - Content Body
      - Convert
      - REST
      - Wiki
      - Async
      - Asynchronously
      - Converted
      - Current
      - Status
      - Tasks
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-contentbody--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-body/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-contentbody--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-body/#api-group-content-body
    aid: atlassian:atlassian-confluence-content-body-api
  - name: Atlassian Confluence Inline Tasks API
    description: Allows you to manage inline tasks across Confluence.
    tags:
      - Based
      - Inline
      - Inline Tasks
      - Parameters
      - REST
      - Search
      - Tasks
      - Wiki
      - Global
      - ID
      - Given
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-inlinetasks--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-inline-tasks
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-inlinetasks--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-inline-tasks#api-group-inline-tasks
    aid: atlassian:atlassian-confluence-inline-tasks-api
  - name: Atlassian Confluence Label API
    description: Provides the ability to label content across Confluence.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-label--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-labels/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-label--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-content-labels/#api-group-content-labels
    aid: atlassian:atlassian-confluence-label-api
  - name: Atlassian Confluence Group API
    description: >-
      Returns all user groups. The returned groups are ordered alphabetically in
      ascending order by group name.
    tags:
      - Groups
      - Names
      - REST
      - Wiki
      - Users
      - Members
      - Partial
      - Picker
      - Queries
      - Search
      - Removes
      - Using
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-group--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-group/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-group--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-group/#api-wiki-rest-api-group-get
    aid: atlassian:atlassian-confluence-group-api
  - name: Atlassian Confluence Longtask API
    description: >-
      Returns information about all active long-running tasks (e.g. space
      export), such as how long each task has been running and the percentage of
      each task that has completed.
    tags:
      - Long Running
      - Longtask
      - REST
      - Tasks
      - Wiki
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-longtask--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-long-running-task/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-longtask--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-long-running-task/#api-wiki-rest-api-longtask-get
    aid: atlassian:atlassian-confluence-longtask-api
  - name: Atlassian Confluence Relation API
    description: >-
      Provides the ability to manage relationships between content across
      Confluence.
    tags:
      - Entities
      - Find
      - Keys
      - Names
      - REST
      - Related
      - Relation
      - Sources
      - Targets
      - Types
      - Wiki
      - Relationships
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-relation--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-relation/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-relation--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-relation/
    aid: atlassian:atlassian-confluence-relation-api
  - name: Atlassian Confluence Search API
    description: Searches content across Confluence.
    tags:
      - REST
      - Search
      - Users
      - Wiki
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-search--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-search/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-search--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-search/#api-group-search
    aid: atlassian:atlassian-confluence-search-api
  - name: Atlassian Confluence Settings API
    description: Manages the settings for Confluence groups.
    tags:
      - Feel
      - REST
      - Settings
      - Wiki
      - Custom
      - Reset
      - Selected
      - Sets
      - Info
      - Systems
      - Theme
      - Themes
      - Global
      - Keys
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-settings--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-settings/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-settings--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-settings/#api-group-settings
    aid: atlassian:atlassian-confluence-settings-api
  - name: Atlassian Confluence Space API
    description: Used to manage all of the Confluence spaces for an account.
    tags:
      - Private
      - REST
      - Space
      - Wiki
      - Keys
      - Content
      - Permission
      - Custom
      - Removes
      - Types
      - Properties
      - Settings
      - States
      - Suggested
      - Given
      - Theme
      - Sets
      - Reset
      - Watchers
      - Labels
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-space--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-space/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-space--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-space/#api-group-space
    aid: atlassian:atlassian-confluence-space-api
  - name: Atlassian Confluence Template API
    description: Provides the ability to manage the templates applied across Confluence.
    tags:
      - Blueprints
      - REST
      - Templates
      - Wiki
      - Content
      - Page
      - Removes
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-template--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-template/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-template--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-template/#api-group-template
    aid: atlassian:atlassian-confluence-template-api
  - name: Atlassian Confluence User API
    description: Provides the ability to manage users as part of a Confluence instance.
    tags:
      - Anonymous
      - REST
      - Users
      - Wiki
      - Current
      - Groups
      - Members
      - Memberships
      - Bulk
      - Ids
      - Multiple
      - Using
      - Content
      - Status
      - Watchers
      - Removes
      - Labels
      - Names
      - Keys
      - Space
      - Addresses
      - Emails
      - Batches
      - Properties
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-user--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v2/api-group-user/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-user--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v2/api-group-user/#api-group-user
    aid: atlassian:atlassian-confluence-user-api
  - name: Atlassian Confluence Connect App Module API
    description: >-
      Connect modules are how Connect apps extend and interact with Confluence.
      If you're not familiar with Connect apps, learn how Connect works first.
    tags:
      - Applications
      - Atlassian
      - Connect
      - Dynamic
      - Modules
      - Register
      - Removes
    properties:
      - type: OpenAPI
        url: >-
          properties/atlassian-atlassian-connect-1-app-module--openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/cloud/confluence/connect-modules/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-atlassian-connect-1-app-module--openapi-search.yml
    humanURL: https://developer.atlassian.com/cloud/confluence/connect-modules/
    aid: atlassian:atlassian-confluence-connect-app-module-api
  - name: Atlassian Confluence Analytics API
    description: >-
      The Confluence Cloud Analytics REST API provides endpoints to access
      analytics data for Confluence content. It allows you to retrieve
      information such as the total number of views and distinct viewers for
      specific content within Confluence Cloud. This API enables developers to
      integrate analytics functionalities into their applications or services,
      providing insights into content engagement and audience interactions
      within Confluence Cloud.
    tags:
      - Analytics
      - Content
      - REST
      - Views
      - Wiki
      - Viewers
    properties:
      - type: OpenAPI
        url: properties/atlassian-wiki-rest-api-analytics--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-analytics/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-wiki-rest-api-analytics--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/confluence/rest/v1/api-group-analytics/#api-group-analytics
    aid: atlassian:atlassian-confluence-analytics-api
  - name: Atlassian BitBucket Addon API
    description: >+
      The addon resource is intended to use used by Bitbucket Cloud Connect
      Apps, and only supports JWT authentication.

    tags:
      - Addons
      - Applications
      - Linkers
      - Keys
      - Linker
      - Values
      - Value
    properties:
      - type: OpenAPI
        url: properties/atlassian-addon--openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/cloud/bitbucket/rest/api-group-addon/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-addon--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/bitbucket/rest/api-group-addon/#api-group-addon
    aid: atlassian:atlassian-bitbucket-addon-api
  - name: Atlassian BitBucket Hook Events API
    description: >-
      Webhooks provide a way to configure Bitbucket Cloud to make requests to
      your server (or another external service) whenever certain events occur in
      Bitbucket Cloud.
    tags:
      - Events
      - Hook
      - Subjects
      - Subscribable
      - Types
      - Webhooks
    properties:
      - type: OpenAPI
        url: properties/atlassian-hook-events--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/rest/api-group-webhooks/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-hook-events--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/bitbucket/rest/api-group-webhooks/#api-group-webhooks
    aid: atlassian:atlassian-bitbucket-hook-events-api
  - name: Atlassian BitBucket Pull Requests API
    description: >-
      Pull requests are a feature that makes it easier for developers to
      collaborate using Bitbucket. They provide a user-friendly web interface
      for discussing proposed changes before integrating them into the official
      project.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-pullrequests-selected-user--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/rest/api-group-pullrequests/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-pullrequests-selected-user--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/bitbucket/rest/api-group-pullrequests/#api-group-pullrequests
    aid: atlassian:atlassian-bitbucket-pull-requests-api
  - name: Atlassian BitBucket Repositories API
    description: >-
      A Git repository is a virtual storage of your project. It allows you to
      save versions of your code, which you can access when needed. The repo
      resource allows you to access public repos, or repos that belong to a
      specific workspace.
    tags:
      - Repositories
      - Workspaces
      - Slug
      - Branch
      - Restrictions
      - Rules
      - Branching
      - Models
      - Configurations
      - Settings
      - Commit
      - Approve
      - Unapprove
      - Comments
      - Commit's
      - Applications
      - Keys
      - Names
      - Properties
      - Contain
      - Pull
      - Pull Requests
      - Reports
      - Annotations
      - Bulk
      - Statuses
      - Build
      - Status
      - Commits
      - Include/exclude
      - Revisions
      - Using
      - Components
      - Issues
      - Default
      - Reviewers
      - Removes
      - Targets
      - User Names
      - Users
      - Deploy
      - Deployments
      - Uu
      - Environments
      - Variables
      - Compare
      - Difference
      - Statistics
      - Artifacts
      - Download
      - Downloads
      - Uploads
      - File Name
      - Link
      - Currently
      - Effective
      - Changes
      - File History
      - Files
      - Modified
      - Paths
      - Forks
      - Fork
      - Hooks
      - Webhooks
      - Exports
      - Checks
      - Tasks
      - Zip
      - Import
      - Attachments
      - Modify
      - States
      - Change
      - Objects
      - Votes
      - Current
      - If
      - Voted
      - Stop
      - Watching
      - Is
      - Ancestor
      - Base
      - Between
      - Common
      - Merge
      - Milestones
      - Inheritance
      - Overr
      - Sets
      - Patch
      - Explicit
      - Groups
      - Permissions
      - Permission
      - Selected
      - Pipelines
      - Runs
      - Caches
      - Cache
      - Content
      - URI
      - Steps
      - Logs
      - Container
      - Given
      - Services
      - Summaries
      - Tests
      - Cases
      - (output)
      - Case
      - Reasons
      - Next
      - Numbers
      - Schedules
      - Executions
      - Pairs
      - SSH
      - Hosts
      - Known
      - Host
      - Activity
      - Reopen
      - Resolve
      - Threads
      - Decline
      - Pullrequest
      - Branches
      - References
      - Tags
      - Directory
      - Root
      - Uploading
      - Contents
      - Defined
      - Versions
      - Watchers
    properties:
      - type: OpenAPI
        url: properties/atlassian-repositories--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/rest/api-group-repositories/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-repositories--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/bitbucket/rest/api-group-repositories/#api-group-repositories
    aid: atlassian:atlassian-bitbucket-repositories-api
  - name: Atlassian BitBucket Snippets API
    description: >-
      Snippets allow you share code segments or files with yourself, members of
      your workspace, or the world. Like pull requests, repositories and
      workspaces, the full set of snippets is defined by what the current user
      has access to. This includes all snippets owned by any of the workspaces
      the user is a member of, or snippets by other users that the current user
      is either watching or has collaborated on (for instance by commenting on
      it).
    tags:
      - Snippets
      - Workspaces
      - Encoded
      - Comments
      - Changes
      - Commits
      - Change
      - Previous
      - Revisions
      - Files
      - HEAD
      - Paths
      - Raw
      - Snippet's
      - Stop
      - Watching
      - Checks
      - Current
      - If
      - Is
      - Users
      - Watchers
      - Nodes
      - Between
      - Difference
      - Versions
      - Patch
    properties:
      - type: OpenAPI
        url: properties/atlassian-snippets--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/rest/api-group-snippets/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-snippets--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/bitbucket/rest/api-group-snippets/#api-group-snippets
    aid: atlassian:atlassian-bitbucket-snippets-api
  - name: Atlassian BitBucket Teams API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/atlassian-teams--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-teams--openapi-search.yml
    aid: atlassian:atlassian-bitbucket-teams-api
  - name: Atlassian BitBucket User API
    description: >-
      The users resource allows you to access public information associated with
      a user account. Most resources in the users endpoint have been deprecated
      in favor of workspaces.
    tags:
      - Configurations
      - Explicit
      - Permissions
      - Repositories
      - Slug
      - Users
      - Workspaces
      - Permission
      - Selected
      - Current
      - Addresses
      - Emails
      - Pipelines
      - Variables
      - Uu
      - Applications
      - Keys
      - Names
      - Properties
      - Code
      - Search
      - SSH
      - Projects
    properties:
      - type: OpenAPI
        url: properties/atlassian-user-openapi-original.yml
      - type: Documentation
        url: https://developer.atlassian.com/cloud/bitbucket/rest/api-group-users/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-user-openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/bitbucket/rest/api-group-users/#api-group-users
    aid: atlassian:atlassian-bitbucket-user-api
  - name: Atlassian BitBucket Workspaces API
    description: >-
      A workspace is where you create repositories, collaborate on your code,
      and organize different streams of work in your Bitbucket Cloud account.
      Workspaces replace the use of teams and users in API calls.
    tags:
      - Workspaces
      - Hooks
      - Webhooks
      - Members
      - Users
      - Memberships
      - Permissions
      - Repositories
      - Slug
      - Configurations
      - Entities
      - ID
      - Known
      - OIDC
      - Pipelines
      - Keys
      - Keys Json
      - Variables
      - Uu
      - Projects
      - Branching
      - Models
      - Settings
      - Default
      - Reviewers
      - Project's
      - Removes
      - Selected
      - Specific
      - Deploy
      - Explicit
      - Groups
      - Permission
      - Code
      - Search
    properties:
      - type: OpenAPI
        url: properties/atlassian-workspaces--openapi-original.yml
      - type: Documentation
        url: >-
          https://developer.atlassian.com/cloud/bitbucket/rest/api-group-workspaces/
    overlays:
      - type: OpenAPI
        url: overlays/atlassian-workspaces--openapi-search.yml
    humanURL: >-
      https://developer.atlassian.com/cloud/bitbucket/rest/api-group-workspaces/#api-group-workspaces
    aid: atlassian:atlassian-bitbucket-workspaces-api
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
aid: atlassian

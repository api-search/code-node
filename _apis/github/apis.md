---
name: GitHub
description: >-
  GitHub is a platform and cloud-based service for software development and
  version control using Git, allowing developers to store and manage their code.
  It provides the distributed version control of Git plus access control, bug
  tracking, software feature requests, task management, continuous integration,
  and wikis for every project.[6] Headquartered in California, it has been a
  subsidiary of Microsoft since 2018.
url: https://raw.githubusercontent.com/api-search/code/main/_apis/github/apis.md
created: 2024/04/14
modified: '2024-07-03'
specificationVersion: '0.18'
tags: []
apis:
  - name: GitHub REST API
    description: >-
      To create integrations, retrieve data, and automate your workflows, build
      with the GitHub REST API. When you make a request to the REST API, you
      will specify an HTTP method and a path. Additionally, you might also
      specify request headers and path, query, or body parameters. The API will
      return the response status code, response headers, and potentially a
      response body.
    tags: []
    overlays:
      - type: APIs.io Search
        url: overlays/github-openapi-search.yml
      - type: API Evangelist Ratings
        url: overlays/github-openapi-api-evangelist-ratings.yml
    aid: github:github-rest-api
  - name: GitHub Graph API
    description: >
      To create integrations, retrieve data, and automate your workflows, use
      the GitHub GraphQL API. The GitHub GraphQL API offers more precise and
      flexible queries than the GitHub REST API.
    tags: []
    overlays: []
    aid: github:github-graph-api
  - name: GitHub Admin API
    description: Use the REST API to administer your enterprise.
    tags:
      - Access
      - Administrative
      - Authorization
      - Download
      - Downloads
      - Environments
      - Global
      - Hook
      - Hooks
      - Impersonation
      - Keys
      - LDAP
      - Latest
      - Mapping
      - Names
      - OAuth
      - Organizations
      - Personal
      - Pings
      - Pre
      - Pre Receive
      - Public
      - Receive
      - Status
      - Sync
      - Teams
      - Tokens
      - User Names
      - Users
      - Webhooks
    properties:
      - type: OpenAPI
        url: properties/github-admin-openapi-original.yml
      - type: Documentation
        url: >-
          https://docs.github.com/en/enterprise-cloud@latest/rest/enterprise-admin
    overlays:
      - type: OpenAPI
        url: overlays/github-admin-openapi-search.yml
    humanURL: >-
      https://docs.github.com/en/enterprise-cloud@latest/rest/enterprise-admin?apiVersion=2022-11-28
    aid: github:github-admin-api
  - name: GitHub App API
    description: >-
      Use the REST API to retrieve information about GitHub Apps and GitHub App
      installations.
    tags:
      - Access
      - Actions
      - Applications
      - Approvals
      - Attempts
      - Authenticated
      - Authorization
      - Branch
      - Branches
      - Checks
      - Clients
      - Code
      - Configurations
      - Conversions
      - Deliveries
      - Git
      - Grants
      - History
      - Hook
      - Hub
      - Installations
      - Manifests
      - Owners
      - Protected
      - Protection
      - Redeliver
      - Repositories
      - Reset
      - Restrictions
      - Reviews
      - Runs
      - Scoped
      - Sets
      - Single
      - Slug
      - Suspend
      - Suspended
      - Tokens
      - Unsuspend
      - Webhooks
      - Workflows
    properties:
      - type: OpenAPI
        url: properties/github-app-openapi-original.yml
      - type: Documentation
        url: https://docs.github.com/en/rest/apps
    overlays:
      - type: OpenAPI
        url: overlays/github-app-openapi-search.yml
    humanURL: https://docs.github.com/en/rest/apps?apiVersion=2022-11-28
    baseURL: https://api.github.com
    aid: github:github-app-api
  - name: GitHub Auth API
    description: >-
      You can authenticate to the REST API to access more endpoints and have a
      higher rate limit.
    tags:
      - Administrative
      - Applications
      - Authorization
      - Authorized
      - Clients
      - Existing
      - Fingerprint
      - Impersonation
      - Keys
      - OAuth
      - SSH
      - Settings
      - Setup
      - Single
      - Specific
      - Tokens
      - User Names
      - Users
    properties:
      - type: OpenAPI
        url: properties/github-auth-openapi-original.yml
      - type: Documentation
        url: >-
          https://docs.github.com/en/rest/authentication/authenticating-to-the-rest-api
    overlays:
      - type: OpenAPI
        url: overlays/github-auth-openapi-search.yml
    humanURL: >-
      https://docs.github.com/en/rest/authentication/authenticating-to-the-rest-api?apiVersion=2022-11-28
    baseURL: https://api.github.com
    aid: github:github-auth-api
  - name: GitHub Code of Conduct API
    description: Use the REST API to get information about codes of conduct.
    tags:
      - Code
      - Codes
      - Conduct
      - Keys
    properties:
      - type: OpenAPI
        url: properties/github-codes-openapi-original.yml
      - type: Documentation
        url: https://docs.github.com/en/rest/codes-of-conduct/codes-of-conduct
    overlays:
      - type: OpenAPI
        url: overlays/github-codes-openapi-search.yml
    humanURL: >-
      https://docs.github.com/en/rest/codes-of-conduct/codes-of-conduct?apiVersion=2022-11-28
    baseURL: https://api.github.com
    aid: github:github-code-of-conduct-api
  - name: GitHub Emojis API
    description: >-
      Use the REST API to list and view all the available emojis to use on
      GitHub.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/github-emojis--openapi-original.yml
      - type: Documentation
        url: https://docs.github.com/en/rest/emojis
    overlays:
      - type: OpenAPI
        url: overlays/github-emojis--openapi-search.yml
    humanURL: https://docs.github.com/en/rest/emojis?apiVersion=2022-11-28
    baseURL: https://api.github.com
    aid: github:github-emojis-api
  - name: GitHub Enterprise API
    description: >-
      Create integrations, retrieve data, and automate your workflows with the
      GitHub REST API.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/github-enterprise-openapi-original.yml
      - type: Documentation
        url: >-
          https://docs.github.com/en/enterprise-cloud@latest/rest/enterprise-admin
    overlays:
      - type: OpenAPI
        url: overlays/github-enterprise-openapi-search.yml
    humanURL: https://docs.github.com/en/enterprise-cloud@latest/rest/enterprise-admin
    baseURL: https://api.github.com
    aid: github:github-enterprise-api
  - name: GitHub Events API
    description: Use the REST API to interact with GitHub events.
    tags:
      - Authenticated
      - Events
      - Issues
      - Organizations
      - Owners
      - Public
      - Repositories
      - User Names
      - Users
    properties:
      - type: OpenAPI
        url: properties/github-events--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-events--openapi-search.yml
    baseURL: https://api.github.com
    humanURL: https://docs.github.com/en/rest/activity/events?apiVersion=2022-11-28
    aid: github:github-events-api
  - name: GitHub Feeds API
    description: >-
      Use the REST API to interact with GitHub feeds. Lists the feeds available
      to the authenticated user. The response provides a URL for each feed. You
      can then get a specific feed by sending a request to one of the feed URLs.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/github-feeds--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-feeds--openapi-search.yml
    humanURL: https://docs.github.com/en/rest/activity/feeds?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-feeds-api
  - name: GitHub Gists API
    description: >-
      Use the REST API to list, create, update and delete the public gists on
      GitHub.
    tags:
      - Checks
      - Comments
      - Commits
      - Fork
      - Forks
      - Gists
      - Public
      - Revisions
      - SHA
      - Star
      - Starred
      - Unstar
    properties:
      - type: OpenAPI
        url: properties/github-gists--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-gists--openapi-search.yml
    baseURL: https://api.github.com/
    humanURL: https://docs.github.com/en/rest/gists?apiVersion=2022-11-28
    aid: github:github-gists-api
  - name: GitHub Gitignore Templates API
    description: >-
      Use the REST API to get .gitignore templates that can be used to ignore
      files and directories.
    tags:
      - Git Ignore
      - Names
      - Templates
    properties:
      - type: OpenAPI
        url: properties/github-gitignore-templates--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-gitignore-templates--openapi-search.yml
    humanURL: https://docs.github.com/en/rest/gitignore?apiVersion=2022-11-28
    baseURL: https://api.github.com
    aid: github:github-gitignore-templates-api
  - name: GitHub Installation API
    description: >-
      Use the REST API to get information about GitHub App installations and
      perform actions within those installations.
    tags:
      - Access
      - Accessible
      - Applications
      - Authenticated
      - Installations
      - Organizations
      - Owners
      - Repositories
      - Revoke
      - Suspend
      - Suspended
      - Tokens
      - Unsuspend
      - User Names
      - Users
    properties:
      - type: OpenAPI
        url: properties/github-installation-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-installation-openapi-search.yml
    baseURL: https://api.github.com/
    aid: github:github-installation-api
  - name: GitHub Issues API
    description: >-
      Use the REST API to view and manage issues, including issue assignees,
      comments, labels, and milestones.
    tags:
      - Assigned
      - Assignee
      - Assignees
      - Checks
      - Comments
      - Events
      - Issues
      - Labels
      - Locks
      - Names
      - Numbers
      - Owners
      - Reactions
      - Repositories
      - Sets
      - Timeline
      - Unlock
      - Users
    properties:
      - type: OpenAPI
        url: properties/github-issues--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-issues--openapi-search.yml
    baseURL: https://api.github.com/
    humanURL: https://docs.github.com/en/rest/issues?apiVersion=2022-11-28
    aid: github:github-issues-api
  - name: GitHub Licenses API
    description: >-
      Use the REST API to retrieve popular open source licenses and information
      about a particular project's license file.
    tags:
      - Licenses
    properties:
      - type: OpenAPI
        url: properties/github-licenses--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-licenses--openapi-search.yml
    humanURL: https://docs.github.com/en/rest/licenses?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-licenses-api
  - name: GitHub Manage API
    description: Needs description.
    tags:
      - Configurations
      - GHES
      - Manage
      - Metadata
      - Nodes
      - Releases
      - Replicas
      - Replication
      - Running
      - Services
      - Status
      - Versions
    properties:
      - type: OpenAPI
        url: properties/github-manage-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-manage-openapi-search.yml
    humanURL: https://docs.github.com/en/rest?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-manage-api
  - name: GitHub Markdown API
    description: >-
      Use the REST API to render a Markdown document as an HTML page or as raw
      text.
    tags:
      - Documents
      - Markdown
      - Mode
      - Raw
      - Render
    properties:
      - type: OpenAPI
        url: properties/github-markdown--openapi-original.yml
      - type: Documentation
        url: https://docs.github.com/en/rest/markdown
    overlays:
      - type: OpenAPI
        url: overlays/github-markdown--openapi-search.yml
    humanURL: https://docs.github.com/en/rest/markdown?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-markdown-api
  - name: GitHub Meta API
    description: >-
      Use the REST API to get meta information about GitHub, including the IP
      addresses of GitHub services.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/github-meta--openapi-original.yml
      - type: Documentation
        url: https://docs.github.com/en/rest/meta
    overlays:
      - type: OpenAPI
        url: overlays/github-meta--openapi-search.yml
    humanURL: https://docs.github.com/en/rest/meta?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-meta-api
  - name: GitHub Networks API
    description: Needs description.
    tags:
      - Events
      - Networks
      - Owners
      - Public
      - Repositories
    properties:
      - type: OpenAPI
        url: properties/github-networks-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-networks-openapi-search.yml
    humanURL: https://docs.github.com/en/rest?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-networks-api
  - name: GitHub Notifications API
    description: |+
      Use the REST API to manage GitHub notifications.

    tags:
      - Notifications
      - Threads
      - Mark
      - Read
      - Authenticated
      - Subscriptions
      - Users
      - Sets
    properties:
      - type: OpenAPI
        url: properties/github-notifications--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-notifications--openapi-search.yml
    humanURL: >-
      https://docs.github.com/en/rest/activity/notifications?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-notifications-api
  - name: GitHub Octocat API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/github-octocat--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-octocat--openapi-search.yml
    humanURL: https://github.com/octokit/octokit.js
    baseURL: https://api.github.com/
    aid: github:github-octocat-api
  - name: GitHub Org API
    description: Use the REST API to control and manage all your GitHub organizations.
    tags:
      - Access
      - Actions
      - Active
      - Administrative
      - Advanced
      - Alerts
      - Allowed
      - Announcement
      - Applications
      - Archive
      - Assigned
      - Attempts
      - Audit
      - Authenticated
      - Banner
      - Between
      - Billing
      - Cache
      - Checks
      - Child
      - Claim
      - Code
      - Collaborators
      - Comments
      - Committers
      - Configurations
      - Conflicting
      - Conflicts
      - Connections
      - Convert
      - Custom
      - Customizations
      - Default
      - Deliveries
      - Dependabot
      - Deprecated
      - Disable
      - Discussion
      - Discussions
      - Docker
      - Download
      - Downloads
      - During
      - Enable
      - Enabled
      - Enablement
      - Enforcement
      - Enterprise
      - Enterprises
      - Events
      - External
      - Feature
      - Fine
      - Fine Grained
      - Git
      - Grained
      - Groups
      - Hook
      - Hooks
      - Hub
      - Installations
      - Issues
      - Keys
      - Labels
      - Locks
      - Logs
      - Managers
      - Members
      - Memberships
      - Migrations
      - Names
      - Numbers
      - OIDC
      - Organizations
      - Outside
      - Owned
      - Owners
      - Packages
      - Permissions
      - Pings
      - Pre
      - Pre Receive
      - Products
      - Projects
      - Public
      - Reactions
      - Receive
      - Redeliver
      - Registrations
      - Repositories
      - Restore
      - Roles
      - Runners
      - Scanning
      - Secrets
      - Security
      - Selected
      - Self Hosted
      - Sets
      - Settings
      - Slug
      - Statistics
      - Status
      - Subjects
      - Teams
      - Templates
      - Tokens
      - Types
      - Unlock
      - Usage
      - User Names
      - Users
      - Variables
      - Versions
      - Webhooks
      - Workflows
    properties:
      - type: OpenAPI
        url: properties/github-org-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-org-openapi-search.yml
    humanURL: https://docs.github.com/en/rest/orgs?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-org-api
  - name: GitHub Projects API
    description: >-
      Use the REST API to create, list, update, delete and customize projects
      (classic).
    tags:
      - Cards
      - Checks
      - Collaborators
      - Columns
      - Existing
      - Move
      - Moves
      - Organizations
      - Owners
      - Permission
      - Permissions
      - Projects
      - Repositories
      - Slug
      - Teams
      - User Names
      - Users
    properties:
      - type: OpenAPI
        url: properties/github-projects-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-projects-openapi-search.yml
    baseURL: https://api.github.com/
    aid: github:github-projects-api
  - name: GitHub Rate Limit API
    description: >-
      Learn about REST API rate limits, how to avoid exceeding them, and what to
      do if you do exceed them.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/github-rate-limit--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-rate-limit--openapi-search.yml
    humanURL: >-
      https://docs.github.com/en/rest/using-the-rest-api/rate-limits-for-the-rest-api?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-rate-limit-api
  - name: GitHub Repos API
    description: >-
      Use the REST API to create, manage and control the workflow of public and
      private GitHub repositories.
    tags:
      - Enterprise
      - Repositories
      - Statistics
      - Accessible
      - Applications
      - Installations
      - Actions
      - Enabled
      - Git
      - Hub
      - Organizations
      - Permissions
      - Selected
      - Sets
      - Enable
      - Disable
      - Access
      - Groups
      - Runners
      - Self Hosted
      - Self Hosted
      - Self Hosted
      - Removes
      - Self Hosted
      - Names
      - Secrets
      - Variables
      - Dependabot
      - Locks
      - Migrations
      - Unlock
      - Fine
      - Fine Grained
      - Grained
      - Slug
      - Teams
      - Checks
      - Owners
      - Artifacts
      - Archive
      - Download
      - Format
      - Cache
      - Usage
      - Policies
      - Caches
      - (using
      - Keys
      - ID)
      - Jobs
      - Runs
      - Workflows
      - Logs
      - Re Run
      - Rerun
      - Claim
      - Customizations
      - OIDC
      - Subjects
      - Templates
      - Levels
      - Outside
      - Allowed
      - Default
      - Self Hosted
      - Downloads
      - Registrations
      - Tokens
      - Self Hosted
      - Self Hosted
      - Labels
      - Self Hosted
      - Custom
      - Self Hosted
      - Self Hosted
      - Self Hosted
      - Self Hosted
      - Approvals
      - History
      - Reviews
      - Attempt
      - Attempts
      - Numbers
      - Cancel
      - Deployments
      - Pending
      - Re Run
      - Failed
      - Re Run
      - Public
      - Dispatch
      - Dispatches
      - Events
      - Assignees
      - Assigned
      - Assignee
      - If
      - Users
      - Auto Links
      - Auto Link
      - References
      - Branches
      - Branch
      - Protection
      - Administrative
      - Administrator
      - Enforce
      - Pull
      - Required
      - Commit
      - Signatures
      - Status
      - Contexts
      - Restrictions
      - Protected
      - Rename
      - Annotations
      - Rerequest
      - Suites
      - Preferences
      - Alerts
      - Code
      - Scanning
      - Instances
      - Analysis
      - Configurations
      - Setup
      - Data
      - SARIF
      - Uploads
      - About
      - Information
      - Sarif
      - CODEOWNERS
      - Code Owners
      - Errors
      - Collaborators
      - Is
      - User Names
      - Permission
      - Comments
      - Reactions
      - Commits
      - HEAD
      - Head
      - SHA
      - Associated
      - Pulls
      - Combined
      - Specific
      - Statuses
      - Basehead
      - Compare
      - Content
      - Contents
      - Paths
      - Files
      - Contributors
      - Between
      - Dependencies
      - Difference
      - Graphs
      - (SBOM)
      - Bill
      - Exports
      - Materials
      - Software
      - Snapshots
      - Environments
      - Forks
      - Fork
      - Blobs
      - Objects
      - Matching
      - Tags
      - Trees
      - Hooks
      - Webhooks
      - Hook
      - Deliveries
      - Redeliver
      - Ping
      - Pings
      - Tests
      - Authenticated
      - Invitations
      - Invitation
      - Issues
      - Timeline
      - Deploy
      - Languages
      - LFS
      - Licenses
      - Merge
      - Sync
      - Upstream
      - Merges
      - Milestones
      - Notifications
      - Mark
      - Read
      - Pages
      - Servers
      - Sites
      - Builds
      - Build
      - Latest
      - Pre
      - Pre Receive
      - Receive
      - Pre Receive
      - Enforcement
      - Pre Receive
      - Pre Receive
      - Projects
      - Replies
      - Replies''
      - Merged
      - Requested
      - Reviewers
      - Dismiss
      - Dismissals
      - Submit
      - README
      - Readme
      - Directory
      - Releases
      - Assets
      - Generate
      - Notes
      - Replicas
      - Replication
      - Locations
      - Stargazers
      - Activity
      - Frequency
      - Weekly
      - Last
      - Years
      - Count
      - Participation
      - Cards
      - Days
      - Hourly
      - Punch
      - Subscribers
      - Watchers
      - Subscriptions
      - States
      - (tar)
      - Targets
      - Topics
      - Replace
      - Transfers
      - Vulnerabilities
      - (zip)
      - Using
      - Search
      - (Legacy)
      - Accept
      - Decline
    properties:
      - type: OpenAPI
        url: properties/github-repos-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-repos-openapi-search.yml
    humanURL: https://docs.github.com/en/rest/repos?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-repos-api
  - name: GitHub SCIM API
    description: >-
      Use the REST API to control and manage your GitHub organization members'
      access with SCIM.
    tags:
      - Attributes
      - Enterprise
      - Groups
      - Identities
      - Information
      - Provision
      - Provisioned
      - Provisioning
      - SCIM
      - Sets
      - Users
    properties:
      - type: OpenAPI
        url: properties/github-scim-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-scim-openapi-search.yml
    humanURL: >-
      https://docs.github.com/en/enterprise-cloud@latest/rest/scim?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-scim-api
  - name: GitHub Search API
    description: Use the REST API to search for specific items on GitHub.
    tags:
      - Code
      - Search
      - Commits
      - Issues
      - Pull
      - Labels
      - Repositories
      - Topics
      - Users
    properties:
      - type: OpenAPI
        url: properties/github-search-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-search-openapi-search.yml
    humanURL: https://docs.github.com/en/rest/search/search?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-search-api
  - name: GitHub Setup API
    description: Needs description.
    tags:
      - Configuration Check
      - Configurations
      - Setup
      - Status
      - Configure
      - Process
      - Maintenance
      - Disable
      - Enable
      - Mode
      - Settings
      - Sets
      - Authorized
      - Keys
      - SSH
      - Removes
      - Git
      - Hub
      - Licenses
      - Upgrade
    properties:
      - type: OpenAPI
        url: properties/github-setup-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-setup-openapi-search.yml
    humanURL: >-
      https://docs.github.com/en/rest/using-the-rest-api/getting-started-with-the-rest-api?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-setup-api
  - name: GitHub Teams API
    description: Use the REST API to create and manage teams in your GitHub organization.
    tags:
      - Administrative
      - LDAP
      - Mapping
      - Teams
      - Sync
      - Managers
      - Organizations
      - Security
      - Slug
      - Removes
      - Names
      - Discussions
      - Discussion
      - Numbers
      - Comments
      - Reactions
      - Between
      - Connections
      - External
      - Groups
      - Members
      - Memberships
      - User Names
      - Users
      - Projects
      - Checks
      - Permissions
      - Repositories
      - Owners
      - Child
      - Access
      - Branch
      - Branches
      - Protected
      - Protection
      - Restrictions
      - Sets
      - (Legacy)
      - Authenticated
    properties:
      - type: OpenAPI
        url: properties/github-teams-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-teams-openapi-search.yml
    humanURL: https://docs.github.com/en/rest/teams?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-teams-api
  - name: GitHub Teams API
    description: Needs description.
    tags:
      - Administrative
      - LDAP
      - Mapping
      - Teams
      - Sync
      - Managers
      - Organizations
      - Security
      - Slug
      - Removes
      - Names
      - Discussions
      - Discussion
      - Numbers
      - Comments
      - Reactions
      - Between
      - Connections
      - External
      - Groups
      - Members
      - Memberships
      - User Names
      - Users
      - Projects
      - Checks
      - Permissions
      - Repositories
      - Owners
      - Child
      - Access
      - Branch
      - Branches
      - Protected
      - Protection
      - Restrictions
      - Sets
      - (Legacy)
      - Authenticated
    properties:
      - type: OpenAPI
        url: properties/github-teams-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-teams-openapi-search.yml
    baseURL: https://api.github.com/
    aid: github:github-teams-api
  - name: GitHub Zen API
    description: Needs description.
    tags: []
    properties:
      - type: OpenAPI
        url: properties/github-zen--openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-zen--openapi-search.yml
    aid: github:github-zen-api
  - name: GitHub User API
    description: >-
      Use the REST API to get public and private information about authenticated
      users.
    tags:
      - Administrative
      - LDAP
      - Mapping
      - User Names
      - Users
      - Sync
      - Authorization
      - Impersonation
      - OAuth
      - Tokens
      - Enterprise
      - Statistics
      - Access
      - Branch
      - Branches
      - Owners
      - Protected
      - Protection
      - Repositories
      - Restrictions
      - Sets
      - Removes
      - Search
      - Authenticated
      - Authenticated User
      - Conflicting
      - Conflicts
      - Docker
      - During
      - Migrations
      - Packages
      - Addresses
      - Emails
      - Followers
      - Following
      - Follows
      - People
      - Checks
      - Followed
      - If
      - Is
      - Person
      - Follow
      - Unfollowing
      - GPG
      - Gpg
      - Keys
      - Accessible
      - Applications
      - Installations
      - Accounts
      - Assigned
      - Issues
      - Public
      - SSH
      - Memberships
      - Organizations
      - Archive
      - Download
      - Namespaces
      - Names
      - Types
      - Restore
      - Owned
      - Versions
      - Projects
      - Invitations
      - Accept
      - Invitation
      - Decline
      - Social
      - Signing
      - Starred
      - Star
      - Unstar
      - Subscriptions
      - Watched
      - Teams
      - Events
      - Another
      - Targets
      - Gists
      - Contextual
      - Hovercard
      - Information
      - Received
      - Administrator
      - Promote
      - Sites
      - Demote
      - Suspend
      - Suspended
      - Unsuspend
    properties:
      - type: OpenAPI
        url: properties/github-user-openapi-original.yml
    overlays:
      - type: OpenAPI
        url: overlays/github-user-openapi-search.yml
    humanURL: https://docs.github.com/en/rest/users?apiVersion=2022-11-28
    baseURL: https://api.github.com/
    aid: github:github-user-api
maintainers:
  - FN: API Evangelist
    url: http://apievangelist.com
    email: info@apievangelist.com
aid: github
---
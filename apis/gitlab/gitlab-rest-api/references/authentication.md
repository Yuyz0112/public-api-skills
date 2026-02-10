# Authentication

This document describes the authentication methods supported by this API.

## http

**Type:** http

- **Scheme:** bearer

## oauth2

**Type:** oauth2

**authorizationCode flow:**
- Authorization URL: https://gitlab.com/api/oauth/authorize
- Token URL: https://gitlab.com/api/oauth/token
- Scopes:
  - `api`: Grants complete read/write access to the API, including all groups and projects, the container registry, the dependency proxy, and the package registry.
  - `read_api`: Grants read access to the API, including all groups and projects, the container registry, and the package registry.
  - `read_user`: Grants read-only access to your profile through the /user API endpoint, which includes username, public email, and full name. Also grants access to read-only API endpoints under /users.
  - `create_runner`: Grants create access to the runners.
  - `manage_runner`: Grants access to manage the runners.
  - `k8s_proxy`: Grants permission to perform Kubernetes API calls using the agent for Kubernetes.
  - `self_rotate`: Grants permission for token to rotate itself.
  - `mcp`: Grants read-write access to remote Model Context Protocol (MCP) server for tools execution.


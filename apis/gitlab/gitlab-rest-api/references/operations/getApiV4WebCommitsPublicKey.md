# GET /api/v4/web_commits/public_key

**Resource:** [Web commits](../resources/Web-commits.md)
**Get the public key for web commits**
**Operation ID:** `getApiV4WebCommitsPublicKey`

This feature was introduced in GitLab 17.4.

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 404 | Public key not found. |
| 503 | The git server, Gitaly, is not available at this time. Please contact your administrator. |


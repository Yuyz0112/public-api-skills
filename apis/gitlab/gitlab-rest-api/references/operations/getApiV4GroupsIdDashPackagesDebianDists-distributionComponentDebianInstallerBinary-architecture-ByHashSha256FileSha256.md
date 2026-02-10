# GET /api/v4/groups/{id}/-/packages/debian/dists/*distribution/{component}/debian-installer/binary-{architecture}/by-hash/SHA256/{file_sha256}

**Resource:** [Packages](../resources/Packages.md)
**The installer (udeb) binary files index by hash**
**Operation ID:** `getApiV4GroupsIdDashPackagesDebianDists*distributionComponentDebianInstallerBinary{architecture}ByHashSha256FileSha256`

This feature was introduced in GitLab 15.4

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The group ID or full group path. |
| `distribution` | query | string | Yes | The Debian Codename or Suite |
| `component` | path | string | Yes | The Debian Component |
| `architecture` | query | string | Yes | The Debian Architecture |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |
| 202 | Accepted |
| 400 | Bad Request |
| 401 | Unauthorized |
| 403 | Forbidden |
| 404 | Not Found |


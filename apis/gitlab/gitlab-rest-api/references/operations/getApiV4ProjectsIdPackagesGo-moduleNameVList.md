# GET /api/v4/projects/{id}/packages/go/*module_name/@v/list

**Resource:** [Packages](../resources/Packages.md)
**List**
**Operation ID:** `getApiV4ProjectsIdPackagesGo*moduleNameVList`

Get all tagged versions for a given Go module.See `go help goproxy`, GET $GOPROXY/<module>/@v/list. This feature was introduced in GitLab 13.1.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `id` | path | any | Yes | The project ID or full path of a project |
| `module_name` | query | string | Yes | The name of the Go module |

## Responses

| Status | Description |
|--------|-------------|
| 200 | OK |


# GET /orgs/{org}/properties/values

**Resource:** [orgs](../resources/orgs.md)
**List custom property values for organization repositories**
**Operation ID:** `orgs/custom-properties-for-repos-get-organization-values`

Lists organization repositories with all of their custom property values.
Organization members can read these properties.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `repository_query` | query | string | No | Finds repositories in the organization with a query containing one or more search keywords and qualifiers. Qualifiers allow you to limit your search to specific areas of GitHub. The REST API supports the same qualifiers as the web interface for GitHub. To learn more about the format of the query, see [Constructing a search query](https://docs.github.com/rest/search/search#constructing-a-search-query). See "[Searching for repositories](https://docs.github.com/articles/searching-for-repositories/)" for a detailed list of qualifiers. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [org-repo-custom-property-values](../schemas/org-repo-custom-property-values/org-repo-custom-property-values.md)


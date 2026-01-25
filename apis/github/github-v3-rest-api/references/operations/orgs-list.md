# GET /organizations

**Resource:** [orgs](../resources/orgs.md)
**List organizations**
**Operation ID:** `orgs/list`

Lists all organizations, in the order that they were created.

> [!NOTE]
> Pagination is powered exclusively by the `since` parameter. Use the [Link header](https://docs.github.com/rest/guides/using-pagination-in-the-rest-api#using-link-headers) to get the URL for the next page of organizations.

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |

**Success Response Schema:**

Array of [organization-simple](../schemas/organization-simple/organization-simple.md)


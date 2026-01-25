# GET /orgs/{org}/projectsV2/{project_number}/views/{view_number}/items

**Resource:** [projects](../resources/projects.md)
**List items for an organization project view**
**Operation ID:** `projects/list-view-items-for-org`

List items in an organization project with the saved view's filter applied.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `fields` | query | any | No | Limit results to specific fields, by their IDs. If not specified, the
title field will be returned.

Example: `fields[]=123&fields[]=456&fields[]=789` or `fields=123,456,789` |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Response |
| 304 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |

**Success Response Schema:**

Array of [projects-v2-item-with-content](../schemas/projects-v2-item-with-content/projects-v2-item-with-content.md)


# GET /events

**Resource:** [Events](../resources/Events.md)
**Get events on a resource**
**Operation ID:** `getEvents`

Returns the full record for all events that have occurred since the sync
token was created.

A `GET` request to the endpoint `/[path_to_resource]/events` can be made in
lieu of including the resource ID in the data for the request.

Asana limits a single sync token to 100 events. If more than 100 events exist
for a given resource, `has_more: true` will be returned in the response, indicating
that there are more events to pull.

*Note: The resource returned will be the resource that triggered the
event. This may be different from the one that the events were requested
for. For example, a subscription to a project will contain events for
tasks contained within the project.*

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successfully retrieved events. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 412 | The request is missing or has an expired sync token. |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**

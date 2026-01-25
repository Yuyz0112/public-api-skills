# POST /exports/graph

**Resource:** [Exports](../resources/Exports.md)
**Initiate a graph export**
**Operation ID:** `createGraphExport`

Initiates a graph export job for a given parent object
(goal, team, portfolio, or project). The export will be processed asynchronously.
Once initiated, use the [jobs](/reference/getjob) endpoint to monitor progress.

**Export Caching:** When exporting more than 1,000 tasks, the results are cached for 4 hours. Any new export requests made within this 4-hour window will return the same cached results rather than generating a fresh export.

## Request Body

A JSON payload specifying the parent object to export.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created Graph export request. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**

# POST /templates/{id}/render

**Resource:** [Templates](../resources/Templates.md)
**Render a template**
**Operation ID:** `renderTemplate`

Render a template. This endpoint has a variable request body depending on the template type. For the `status_update` template type, the caller will provide the incident id, and a status update message.

Scoped OAuth requires: `templates.read`


## Request Body

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful operation |
| 400 | (reference) |
| 402 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

**Success Response Schema:**

[RenderedTemplate](../schemas/Rendered/RenderedTemplate.md)


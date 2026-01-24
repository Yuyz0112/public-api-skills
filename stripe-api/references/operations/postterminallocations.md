# POST /v1/terminal/locations

**Resource:** [terminal](../resources/terminal.md)
**Create a Location**
**Operation ID:** `PostTerminalLocations`

<p>Creates a new <code>Location</code> object.
For further details, including which address fields are required in each country, see the <a href="/docs/terminal/fleet/locations">Manage locations</a> guide.</p>

## Request Body

**Content Types:** `application/x-www-form-urlencoded`

## Responses

| Status | Description |
|--------|-------------|
| 200 | Successful response. |
| default | Error response. |

**Success Response Schema:**

[terminal.location](../schemas/terminal-location/terminal-location.md)


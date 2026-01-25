# POST /portfolios

**Resource:** [Portfolios](../resources/Portfolios.md)
**Create a portfolio**
**Operation ID:** `createPortfolio`

<b>Required scope: </b><code>portfolios:write</code>

Creates a new portfolio in the given workspace with the supplied name.

Note that portfolios created in the Asana UI may have some state
(like the “Priority” custom field) which is automatically added
to the portfolio when it is created. Portfolios created via our
API will *not* be created with the same initial state to allow
integrations to create their own starting state on a portfolio.

## Parameters

| Name | In | Type | Required | Description |
|------|------|------|----------|-------------|
| `opt_fields` | query | string[] | No | This endpoint returns a resource which excludes some properties by default. To include those optional properties, set this query parameter to a comma-separated list of the properties you wish to include. |

## Request Body

The portfolio to create.

**Required:** Yes

**Content Types:** `application/json`

## Responses

| Status | Description |
|--------|-------------|
| 201 | Successfully created portfolio. |
| 400 | (reference) |
| 401 | (reference) |
| 403 | (reference) |
| 404 | (reference) |
| 500 | (reference) |

## Security

- **personalAccessToken**
- **oauth2**: portfolios:write

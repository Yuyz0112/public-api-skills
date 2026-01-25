# GET /2/users/personalized_trends

**Resource:** [Trends](../resources/Trends.md)
**Get personalized Trends**
**Operation ID:** `getTrendsPersonalizedTrends`

Retrieves personalized trending topics for the authenticated user.

## Responses

| Status | Description |
|--------|-------------|
| 200 | The request has succeeded. |
| default | The request has failed. |

**Success Response Schema:**

[Get2UsersPersonalizedTrendsResponse](../schemas/Get/Get2UsersPersonalizedTrendsResponse.md)

## Security

- **OAuth2UserToken**: tweet.read, users.read
- **UserToken**

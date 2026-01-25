# account_link

Account Links are the means by which a Connect platform grants a connected account permission to access
Stripe-hosted applications, such as Connect Onboarding.

Related guide: [Connect Onboarding](https://docs.stripe.com/connect/custom/hosted-onboarding)

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `created` | integer (unix-time) | Yes | Time at which the object was created. Measured in seconds since the Unix epoch. |
| `expires_at` | integer (unix-time) | Yes | The timestamp at which this account link will expire. |
| `object` | enum: account_link | Yes | String representing the object's type. Objects of the same type share the same value. |
| `url` | string | Yes | The URL for the account link. |


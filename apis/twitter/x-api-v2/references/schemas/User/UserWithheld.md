# UserWithheld

Indicates withholding details for [withheld content](https://help.twitter.com/en/rules-and-policies/tweet-withheld-by-country).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country_codes` | CountryCode[] | Yes | Provides a list of countries where this content is not available. |
| `scope` | enum: user | No | Indicates that the content being withheld is a `user`. |


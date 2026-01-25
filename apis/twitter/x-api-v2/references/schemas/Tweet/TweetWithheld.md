# TweetWithheld

Indicates withholding details for [withheld content](https://help.twitter.com/en/rules-and-policies/tweet-withheld-by-country).

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `copyright` | boolean | Yes | Indicates if the content is being withheld for on the basis of copyright infringement. |
| `country_codes` | CountryCode[] | Yes | Provides a list of countries where this content is not available. |
| `scope` | enum: tweet, user | No | Indicates whether the content being withheld is the `tweet` or a `user`. |


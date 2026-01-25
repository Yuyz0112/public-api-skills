# tax_product_resource_jurisdiction

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `country` | string | Yes | Two-letter country code ([ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)). |
| `display_name` | string | Yes | A human-readable name for the jurisdiction imposing the tax. |
| `level` | enum: city, country, county... | Yes | Indicates the level of the jurisdiction imposing the tax. |
| `state` | string | No | [ISO 3166-2 subdivision code](https://en.wikipedia.org/wiki/ISO_3166-2), without country prefix. For example, "NY" for New York, United States. |


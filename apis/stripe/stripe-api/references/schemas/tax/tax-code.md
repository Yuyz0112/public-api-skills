# tax_code

[Tax codes](https://stripe.com/docs/tax/tax-categories) classify goods and services for tax purposes.

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `description` | string | Yes | A detailed description of which types of products the tax code represents. |
| `id` | string | Yes | Unique identifier for the object. |
| `name` | string | Yes | A short name for the tax code. |
| `object` | enum: tax_code | Yes | String representing the object's type. Objects of the same type share the same value. |


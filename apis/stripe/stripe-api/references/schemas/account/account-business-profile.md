# account_business_profile

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `annual_revenue` | any | No | The applicant's gross annual revenue for its preceding fiscal year. |
| `estimated_worker_count` | integer | No | An estimated upper bound of employees, contractors, vendors, etc. currently working for the business. |
| `mcc` | string | No | [The merchant category code for the account](/connect/setting-mcc). MCCs are used to classify businesses based on the goods or services they provide. |
| `minority_owned_business_designation` | string[] | No | Whether the business is a minority-owned, women-owned, and/or LGBTQI+ -owned business. |
| `monthly_estimated_revenue` | [account_monthly_estimated_revenue](account-monthly-estimated-revenue.md) | No |  |
| `name` | string | No | The customer-facing business name. |
| `product_description` | string | No | Internal-only description of the product sold or service provided by the business. It's used by Stripe for risk and underwriting purposes. |
| `support_address` | any | No | A publicly available mailing address for sending support issues to. |
| `support_email` | string | No | A publicly available email address for sending support issues to. |
| `support_phone` | string | No | A publicly available phone number to call with support issues. |
| `support_url` | string | No | A publicly available website for handling support issues. |
| `url` | string | No | The business's publicly available website. |


# PortfolioAddItemRequest

**Type:** object

## Fields

| Field | Type | Required | Description |
|-------|------|----------|-------------|
| `item` | string | Yes | The item to add to the portfolio. |
| `insert_before` | string | No | An id of an item in this portfolio. The new item will be added before the one specified here. `insert_before` and `insert_after` parameters cannot both be specified. |
| `insert_after` | string | No | An id of an item in this portfolio. The new item will be added after the one specified here. `insert_before` and `insert_after` parameters cannot both be specified. |


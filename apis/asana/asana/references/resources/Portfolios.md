# Portfolios

A portfolio gives a high-level overview of the status of multiple initiatives in Asana. Portfolios provide a dashboard overview of the state of multiple projects, including a progress report and the most recent [status update](/reference/status-updates).
Portfolios have some restrictions on size. Each portfolio has a max of 1500 items and, like projects, a maximum of 20 custom fields.

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/portfolios` | Get multiple portfolios | [View](../operations/getPortfolios.md) |
| POST | `/portfolios` | Create a portfolio | [View](../operations/createPortfolio.md) |
| GET | `/portfolios/{portfolio_gid}` | Get a portfolio | [View](../operations/getPortfolio.md) |
| PUT | `/portfolios/{portfolio_gid}` | Update a portfolio | [View](../operations/updatePortfolio.md) |
| DELETE | `/portfolios/{portfolio_gid}` | Delete a portfolio | [View](../operations/deletePortfolio.md) |
| GET | `/portfolios/{portfolio_gid}/items` | Get portfolio items | [View](../operations/getItemsForPortfolio.md) |
| POST | `/portfolios/{portfolio_gid}/addItem` | Add a portfolio item | [View](../operations/addItemForPortfolio.md) |
| POST | `/portfolios/{portfolio_gid}/removeItem` | Remove a portfolio item | [View](../operations/removeItemForPortfolio.md) |
| POST | `/portfolios/{portfolio_gid}/addCustomFieldSetting` | Add a custom field to a portfolio | [View](../operations/addCustomFieldSettingForPortfolio.md) |
| POST | `/portfolios/{portfolio_gid}/removeCustomFieldSetting` | Remove a custom field from a portfolio | [View](../operations/removeCustomFieldSettingForPortfolio.md) |
| POST | `/portfolios/{portfolio_gid}/addMembers` | Add users to a portfolio | [View](../operations/addMembersForPortfolio.md) |
| POST | `/portfolios/{portfolio_gid}/removeMembers` | Remove users from a portfolio | [View](../operations/removeMembersForPortfolio.md) |

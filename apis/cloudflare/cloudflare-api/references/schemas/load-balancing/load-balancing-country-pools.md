# load-balancing_country_pools

A mapping of country codes to a list of pool IDs (ordered by their failover priority) for the given country. Any country not explicitly defined will fall back to using the corresponding region_pool mapping if it exists else to default_pools.

**Type:** object


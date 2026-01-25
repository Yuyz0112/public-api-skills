# plus

## Operations

| Method | Path | Summary | Details |
|--------|------|---------|----------|
| GET | `/admin/api/2020-01/gift_cards.json` | Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-gift-cards.md) |
| POST | `/admin/api/2020-01/gift_cards.json` | Creates a gift card | [View](../operations/deprecated-202001-create-gift-cards.md) |
| GET | `/admin/api/2020-01/gift_cards/{gift_card_id}.json` | Retrieves a single gift card by its ID | [View](../operations/deprecated-202001-get-gift-cards-param-gift-card-id.md) |
| PUT | `/admin/api/2020-01/gift_cards/{gift_card_id}.json` | Updates an existing gift card.
          The gift card's balance can't be changed via the API. You can change only the expiry date, note, and template suffix. | [View](../operations/deprecated-202001-update-gift-cards-param-gift-card-id.md) |
| GET | `/admin/api/2020-01/gift_cards/count.json` | Retrieves a count of gift cards | [View](../operations/deprecated-202001-get-gift-cards-count.md) |
| POST | `/admin/api/2020-01/gift_cards/{gift_card_id}/disable.json` | Disables a gift card. Disabling a gift card can't be undone. | [View](../operations/deprecated-202001-create-gift-cards-param-gift-card-id-disable.md) |
| GET | `/admin/api/2020-01/gift_cards/search.json` | Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-gift-cards-search.md) |
| GET | `/admin/api/2020-04/gift_cards.json` | Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-gift-cards.md) |
| POST | `/admin/api/2020-04/gift_cards.json` | Creates a gift card | [View](../operations/deprecated-202004-create-gift-cards.md) |
| GET | `/admin/api/2020-04/gift_cards/{gift_card_id}.json` | Retrieves a single gift card by its ID | [View](../operations/deprecated-202004-get-gift-cards-param-gift-card-id.md) |
| PUT | `/admin/api/2020-04/gift_cards/{gift_card_id}.json` | Updates an existing gift card.
          The gift card's balance can't be changed via the API. You can change only the expiry date, note, and template suffix. | [View](../operations/deprecated-202004-update-gift-cards-param-gift-card-id.md) |
| GET | `/admin/api/2020-04/gift_cards/count.json` | Retrieves a count of gift cards | [View](../operations/deprecated-202004-get-gift-cards-count.md) |
| POST | `/admin/api/2020-04/gift_cards/{gift_card_id}/disable.json` | Disables a gift card. Disabling a gift card can't be undone. | [View](../operations/deprecated-202004-create-gift-cards-param-gift-card-id-disable.md) |
| GET | `/admin/api/2020-04/gift_cards/search.json` | Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-gift-cards-search.md) |
| GET | `/admin/api/2020-07/gift_cards.json` | Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-gift-cards.md) |
| POST | `/admin/api/2020-07/gift_cards.json` | Creates a gift card | [View](../operations/deprecated-202007-create-gift-cards.md) |
| GET | `/admin/api/2020-07/gift_cards/{gift_card_id}.json` | Retrieves a single gift card by its ID | [View](../operations/deprecated-202007-get-gift-cards-param-gift-card-id.md) |
| PUT | `/admin/api/2020-07/gift_cards/{gift_card_id}.json` | Updates an existing gift card.
          The gift card's balance can't be changed via the API. You can change only the expiry date, note, and template suffix. | [View](../operations/deprecated-202007-update-gift-cards-param-gift-card-id.md) |
| GET | `/admin/api/2020-07/gift_cards/count.json` | Retrieves a count of gift cards | [View](../operations/deprecated-202007-get-gift-cards-count.md) |
| POST | `/admin/api/2020-07/gift_cards/{gift_card_id}/disable.json` | Disables a gift card. Disabling a gift card can't be undone. | [View](../operations/deprecated-202007-create-gift-cards-param-gift-card-id-disable.md) |
| GET | `/admin/api/2020-07/gift_cards/search.json` | Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-gift-cards-search.md) |
| GET | `/admin/api/2020-10/gift_cards.json` | Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-gift-cards.md) |
| POST | `/admin/api/2020-10/gift_cards.json` | Creates a gift card | [View](../operations/create-gift-cards.md) |
| GET | `/admin/api/2020-10/gift_cards/{gift_card_id}.json` | Retrieves a single gift card by its ID | [View](../operations/get-gift-cards-param-gift-card-id.md) |
| PUT | `/admin/api/2020-10/gift_cards/{gift_card_id}.json` | Updates an existing gift card.
          The gift card's balance can't be changed via the API. You can change only the expiry date, note, and template suffix. | [View](../operations/update-gift-cards-param-gift-card-id.md) |
| GET | `/admin/api/2020-10/gift_cards/count.json` | Retrieves a count of gift cards | [View](../operations/get-gift-cards-count.md) |
| POST | `/admin/api/2020-10/gift_cards/{gift_card_id}/disable.json` | Disables a gift card. Disabling a gift card can't be undone. | [View](../operations/create-gift-cards-param-gift-card-id-disable.md) |
| GET | `/admin/api/2020-10/gift_cards/search.json` | Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-gift-cards-search.md) |
| GET | `/admin/api/2021-01/gift_cards.json` | Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-gift-cards.md) |
| POST | `/admin/api/2021-01/gift_cards.json` | Creates a gift card | [View](../operations/deprecated-202101-create-gift-cards.md) |
| GET | `/admin/api/2021-01/gift_cards/{gift_card_id}.json` | Retrieves a single gift card by its ID | [View](../operations/deprecated-202101-get-gift-cards-param-gift-card-id.md) |
| PUT | `/admin/api/2021-01/gift_cards/{gift_card_id}.json` | Updates an existing gift card.
          The gift card's balance can't be changed via the API. You can change only the expiry date, note, and template suffix. | [View](../operations/deprecated-202101-update-gift-cards-param-gift-card-id.md) |
| GET | `/admin/api/2021-01/gift_cards/count.json` | Retrieves a count of gift cards | [View](../operations/deprecated-202101-get-gift-cards-count.md) |
| POST | `/admin/api/2021-01/gift_cards/{gift_card_id}/disable.json` | Disables a gift card. Disabling a gift card can't be undone. | [View](../operations/deprecated-202101-create-gift-cards-param-gift-card-id-disable.md) |
| GET | `/admin/api/2021-01/gift_cards/search.json` | Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-gift-cards-search.md) |
| GET | `/admin/api/unstable/gift_cards.json` | Retrieves a list of gift cards. Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-gift-cards.md) |
| POST | `/admin/api/unstable/gift_cards.json` | Creates a gift card | [View](../operations/deprecated-unstable-create-gift-cards.md) |
| GET | `/admin/api/unstable/gift_cards/{gift_card_id}.json` | Retrieves a single gift card by its ID | [View](../operations/deprecated-unstable-get-gift-cards-param-gift-card-id.md) |
| PUT | `/admin/api/unstable/gift_cards/{gift_card_id}.json` | Updates an existing gift card.
          The gift card's balance can't be changed via the API. You can change only the expiry date, note, and template suffix. | [View](../operations/deprecated-unstable-update-gift-cards-param-gift-card-id.md) |
| GET | `/admin/api/unstable/gift_cards/count.json` | Retrieves a count of gift cards | [View](../operations/deprecated-unstable-get-gift-cards-count.md) |
| POST | `/admin/api/unstable/gift_cards/{gift_card_id}/disable.json` | Disables a gift card. Disabling a gift card can't be undone. | [View](../operations/deprecated-unstable-create-gift-cards-param-gift-card-id-disable.md) |
| GET | `/admin/api/unstable/gift_cards/search.json` | Searches for gift cards that match a supplied query. The following fields are indexed by search:
          
            created_at
            updated_at
            disabled_at
            balance
            initial_value
            amount_spent
            email
            last_characters
          
          Note: As of version 2019-10, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-gift-cards-search.md) |
| GET | `/admin/api/2020-01/users.json` | Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202001-get-users.md) |
| GET | `/admin/api/2020-01/users/{user_id}.json` | Retrieves a single user | [View](../operations/deprecated-202001-get-users-param-user-id.md) |
| GET | `/admin/api/2020-01/users/current.json` | Retrieves information about the user account associated with the access token used to make this API request. This request works only when the access token was created for a specific user of the shop. | [View](../operations/deprecated-202001-get-users-current.md) |
| GET | `/admin/api/2020-04/users.json` | Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202004-get-users.md) |
| GET | `/admin/api/2020-04/users/{user_id}.json` | Retrieves a single user | [View](../operations/deprecated-202004-get-users-param-user-id.md) |
| GET | `/admin/api/2020-04/users/current.json` | Retrieves information about the user account associated with the access token used to make this API request. This request works only when the access token was created for a specific user of the shop. | [View](../operations/deprecated-202004-get-users-current.md) |
| GET | `/admin/api/2020-07/users.json` | Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202007-get-users.md) |
| GET | `/admin/api/2020-07/users/{user_id}.json` | Retrieves a single user | [View](../operations/deprecated-202007-get-users-param-user-id.md) |
| GET | `/admin/api/2020-07/users/current.json` | Retrieves information about the user account associated with the access token used to make this API request. This request works only when the access token was created for a specific user of the shop. | [View](../operations/deprecated-202007-get-users-current.md) |
| GET | `/admin/api/2020-10/users.json` | Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/get-users.md) |
| GET | `/admin/api/2020-10/users/{user_id}.json` | Retrieves a single user | [View](../operations/get-users-param-user-id.md) |
| GET | `/admin/api/2020-10/users/current.json` | Retrieves information about the user account associated with the access token used to make this API request. This request works only when the access token was created for a specific user of the shop. | [View](../operations/get-users-current.md) |
| GET | `/admin/api/2021-01/users.json` | Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-202101-get-users.md) |
| GET | `/admin/api/2021-01/users/{user_id}.json` | Retrieves a single user | [View](../operations/deprecated-202101-get-users-param-user-id.md) |
| GET | `/admin/api/2021-01/users/current.json` | Retrieves information about the user account associated with the access token used to make this API request. This request works only when the access token was created for a specific user of the shop. | [View](../operations/deprecated-202101-get-users-current.md) |
| GET | `/admin/api/unstable/users.json` | Retrieves a list of all users. Note: As of version 2021-01, this endpoint implements pagination by using links that are provided in the response header. Sending the page parameter will return an error. To learn more, see Making requests to paginated REST Admin API endpoints. | [View](../operations/deprecated-unstable-get-users.md) |
| GET | `/admin/api/unstable/users/{user_id}.json` | Retrieves a single user | [View](../operations/deprecated-unstable-get-users-param-user-id.md) |
| GET | `/admin/api/unstable/users/current.json` | Retrieves information about the user account associated with the access token used to make this API request. This request works only when the access token was created for a specific user of the shop. | [View](../operations/deprecated-unstable-get-users-current.md) |
